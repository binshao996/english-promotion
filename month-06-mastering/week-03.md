# Week 03: 远程工作英语实战 — PR、RFC、Postmortem、Async Updates + 300 B2-C1 词汇

> 目标：将 Months 1-6 的所有语法能力、纠错能力和句子拆解能力应用到远程工作的真实场景中。学会用英语写出清晰的 PR 描述、有说服力的 RFC、有洞察力的 postmortem、高效的异步更新——这些都是你每天在 Slack、GitHub、邮件和 Notion 中实际需要做的事情。积累 300 个远程协作与工具、技术文档与写作、工程管理与领导力、DevOps 与基础设施、数据科学与机器学习、产品管理与战略领域的 B2-C1 词汇。

---

## 1. Grammar — 远程工作中的英语写作实战

Months 1-5 教了你英语语法体系，Month 6 Week 01 教了你如何拆解任何复杂句子，Week 02 帮你识别了中国学习者最常犯的 52 个错误。本周，所有这些能力将合而为一，应用到六个远程工作场景中。

每个场景包含：
- **Why this matters** — 这个场景为什么重要
- **Template / Structure** — 推荐的写作框架
- **Language Patterns** — 高频句式和表达
- **Annotated Example** — 一个带语法标注的完整示例
- **Common Pitfalls** — 中国学习者在这个场景中最容易犯的错误

---

### 1.1 场景一：写一份清晰的 PR 描述 (Pull Request Description)

**Why this matters:** 你的 PR 描述是分布式代码审查的基础。如果你的 reviewer 在印度、你在美国，她不能"拍你肩膀问一下"——PR 描述必须包含所有她需要的上下文，让她可以异步完成 review。

#### Template

```markdown
## What
[1-2 句话说明这个 PR 做了什么]

## Why
[1-2 句话说明为什么做这个改动——链接 issue / 产品需求 / 技术债务背景]

## How
[2-4 bullet points 说明实现方案的关键选择]

## Testing
- [ ] Unit tests added/updated
- [ ] Integration tests pass
- [ ] Manually tested on staging

## Risks & Rollback
- Risk: [最大的风险是什么]
- Rollback: [如何回滚——feature flag? DB migration?]

## Screenshots / Evidence
[如果有 UI 改动]
```

#### Language Patterns

| 场景 | 推荐表达 | 避免表达 |
|------|---------|---------|
| 说明 PR 做了什么 | This PR **adds** / **fixes** / **refactors** / **introduces**... | I add... / Adding... (用一般现在时) |
| 说明为什么要做 | This change **is needed because**... / **Addresses** issue #123 | Because of the reason that... (太啰嗦) |
| 说明做了什么权衡 | We **chose to** use X over Y **because**... | We selected X. (没有解释 why) |
| 标记破坏性变更 | **Breaking change:** ... | This might break something. (不够明确) |
| 请求特定反馈 | **I'd especially like feedback on**... / **PTAL at** (Please Take A Look at)... | Please review. (不够具体) |
| 标记 WIP | **WIP:** Do not merge yet. | Not done. (不够清楚) |

#### Annotated Example — A Real PR Description

> **Note:** 下面的语法标注使用了 Months 1-5 的标签：
> - [M1] 基本句型
> - [M2] 完成时/被动语态/情态动词
> - [M3] 名词从句/关系从句/状语从句
> - [M4] 条件句/虚拟语气/非谓语动词
> - [M5] 倒装/强调/冠词与介词
> - [⚠] Week 02 错误类型

```markdown
## What

This PR [⚠ 单数主语 + 单数动词] introduces [M5: the — 特指] a new rate-limiting middleware
for [M5: preposition — for + purpose] the API gateway.

## Why

Under peak traffic, [M5: the — 特指] the gateway currently has no backpressure mechanism
[M2: present perfect — 从过去到现在持续没有]. [M5: ∅ — 零冠词,抽象名词泛指]
High latency on one endpoint can cascade [M5: preposition — cascade 是及物动词,还是不及物?]
to other services [M3: relative clause — that share the same thread pool],
causing [M4: -ing 分词表结果] a complete outage of [M5: the — of 修饰限定 → the outage]
the API layer.

This PR addresses [M5: issue 前不加 the — 专有名词? 不是,issue 前需要 the]
the issue #456.

## How

- Added [M2: 被动语态,省略主语] a token-bucket rate limiter [M3: relative clause — that]
  that can be configured per-endpoint.
- [M5: ∅ — 零冠词,泛指] Rate limits are enforced [M2: present passive]
  before [M5: preposition — before + noun/-ing] the request reaches the application logic.
- [M5: Preposition choice] The middleware integrates with our existing observability stack
  via [M5: via = through,比 "by" 更精确] OpenTelemetry.

## Testing

- [M2: present perfect passive] Unit tests have been added for [M5: all + three] all three
  rate-limiting algorithms.
- Integration tests were run [M2: passive voice, past tense — 完成了的动作]
  against [M5: preposition — against] a staging集群 of 50 concurrent connections.
- No [M2: modal — should] should break existing behavior — all existing tests pass.

## Risks & Rollback

- **Risk:** [M5: ∅ — 不可数名词泛指] Memory usage may increase [M2: modal — may]
  by ~5% due to [M5: preposition — due to + noun/-ing] the token bucket state.
- **Rollback:** [M4: Type 1 conditional — real possibility]
  If [M5: the — 特指这个 feature flag] the feature flag `rate_limit_v2` is turned off,
  [M5: the — 特指这个中间件] the middleware will pass through all requests unchanged.
- [M2: present perfect — 已经验证] The rollback procedure has been tested on staging.
```

#### Common Pitfalls in PR Descriptions

1. **冠词缺失**: "This PR fixes bug in production" → "This PR fixes **a** bug in production" (单数可数名词必须有冠词)
2. **时态错误**: 用一般现在时描述 PR 做了什么 (This PR **adds**...)，不要用将来时 (This PR **will add**...)
3. **被动语态缺失**: "Added rate limiter" → "**A** rate limiter **was** added" 或直接用主动 (This PR adds...)
4. **介词错误**: "depends of" → "depends **on**", "consists from" → "consists **of**"
5. **Why 部分太弱**: 不要只说 "Fix bug" — 说清楚什么条件下触发、影响多大

---

### 1.2 场景二：写一份有说服力的 RFC / 设计文档 (Request for Comments)

**Why this matters:** RFC 是你影响技术决策的主要战场。一份好的 RFC 不只是"描述了你的方案"——它说服别人你的方案是当前约束下最优的选择。在异步的远程工作环境中,RFC 必须自给自足——读者不能在 15 分钟的同步会议中提问。

#### Template

```markdown
# RFC: [Title]

| Field | Value |
|-------|-------|
| **Status** | Draft / In Review / Approved / Implemented |
| **Author** | @handle |
| **Date** | YYYY-MM-DD |
| **Stakeholders** | @team-a, @team-b |

## Summary
[2-3 句话：问题是什么，建议的解决方案是什么]

## Motivation
[为什么现在要解决这个问题？不解决会怎样？]

## Proposed Solution
[核心方案——技术决策、架构图、API 设计]

## Alternatives Considered
[你考虑过哪些替代方案？为什么没有选它们？]

## Trade-offs
[你的方案牺牲了什么？这是有意为之还是无奈妥协？]

## Migration Plan
[如何从现在的状态过渡到你的方案？回滚计划？]

## Open Questions
[哪些决策点你还没想清楚，需要读者帮你思考？]
```

#### Language Patterns

| 场景 | 推荐表达 | 语法要点 |
|------|---------|---------|
| 陈述问题 | Currently, [problem]. This **leads to** / **results in** / **causes** [consequence]. | 一般现在时 (陈述当前事实) |
| 提出方案 | **I propose that we** [verb]... / **The proposal is to** [verb]... | propose 后从句用虚拟语气 (动词原形) |
| 陈述权衡 | This **comes at the cost of**... / **The trade-off here is** [X] **versus** [Y]. | at the cost of — 介词短语 |
| 对比方案 | **Compared to** [alternative], this approach... / **Unlike** [alternative], this approach... | 分词短语引导对比 |
| 做推荐 | **On balance**, I recommend... / **Given** [constraints], this is the best option. | given + 名词 = considering |
| 承认不确定性 | **One open question is whether**... / **It remains to be seen whether**... | whether 引导名词从句 |
| 请求反馈 | **I'd appreciate thoughts on**... / **Feedback is especially welcome on**... | 礼貌但直接 |
| 标记决定 | Once this RFC is **approved**, we will... / **Pending** review, the implementation... | approved — 过去分词表被动; pending + noun = awaiting |

#### Annotated Example — RFC Opening Paragraph

> **Problems with our current authentication system have been accumulating over the past year: JWT tokens are not revocable, the session store has been the source of three P1 incidents in Q3 alone, and — most critically — the current architecture makes it impossible to implement the role-based access control (RBAC) that our enterprise customers have been requesting. This RFC proposes migrating from JWT-based stateless authentication to a session-based system backed by Redis, with a phased rollout that preserves backward compatibility throughout the transition.**

**逐词句法拆解:**

| # | 词/词组 | 句法角色 | 语法标注 |
|---|---------|----------|----------|
| 1 | Problems with our current authentication system | 名词短语 (主语) | [M5] ∅ 零冠词 — 复数泛指; [M5] preposition: with = 与...相关的 |
| 2 | have been accumulating | 现在完成进行时 (谓语) | [M2] have been + -ing — 从过去开始持续到现在，且仍在继续 |
| 3 | over the past year | 时间状语 | [M5] preposition: over = 在...期间 |
| 4 | JWT tokens are not revocable | 并列分句 1 | [M2] present passive — 陈述当前事实 |
| 5 | the session store has been the source | 并列分句 2 | [M2] present perfect — 过去到现在的持续状态 |
| 6 | of three P1 incidents in Q3 alone | 介词短语 (修饰 source) | [M5] of + 数字; alone = 仅仅(强调) |
| 7 | — and, most critically — | 插入语 (强调) | [M5] 破折号 emphasis — 比逗号更重的停顿 |
| 8 | the current architecture makes it impossible | 并列分句 3 | [M4] make + it + adj + to do — it 作形式宾语 |
| 9 | to implement the RBAC that... | 不定式短语 (真正宾语) | [M3] that 引导定语从句修饰 RBAC |
| 10 | This RFC proposes migrating... | 主句 | [M4] propose + -ing (动名词作宾语) |
| 11 | from JWT-based...to a session-based system... | 介词短语 | [M5] from X to Y — 介词搭配 |
| 12 | backed by Redis | 过去分词短语 (后置定语) | [M2] passive — (which is) backed by... |
| 13 | with a phased rollout that preserves... | 介词短语 + 定语从句 | [M3] that 从句修饰 rollout; [M5] with = 带有 |

**语言要点:**
- [M2] 现在完成进行时 "have been accumulating" 的力量——不是"积累完毕了"，而是"一直在积累，而且还在继续"
- [M5] 破折号的战略使用——"and, most critically, " 比 "and most critically" 更重、更引人注意
- [M4] make + it + adj + to do —— 避免头重脚轻
- [M3] that 定语从句链: "RBAC that our enterprise customers have been requesting" —— 精准限定

#### Common Pitfalls in RFCs

1. **Summary 太弱**: "We should change auth" → "I propose migrating from stateless JWT to stateful Redis-based sessions to enable RBAC and eliminate session-store incidents."
2. **Alternatives 太敷衍**: "We could also use OAuth but it's worse" → 给出「具体」的理由: 为什么 OAuth 在这个场景下不合适？是延迟问题？是复杂度？是不支持 on-prem？
3. **虚拟语气遗漏**: "I propose that we **migrate** (不是 migrates / migrated / will migrate)" —— propose/suggest/recommend + that + 动词原形
4. **冠词**: "**∅** JWT tokens" (泛指) vs "**the** JWT tokens **in our system**" (特指)
5. **Preposition**: "different **from**" (不是 different with), "similar **to**" (不是 similar with), "compared **to**" (不是 compared with — 虽然 compared with 也在用，但 compared to 更常见于对比不同事物)

---

### 1.3 场景三：写一份有洞察力的 Postmortem / Incident Report

**Why this matters:** Postmortem 不是一份"认罪书"——它是一份"系统学习文档"。写得好的 postmortem 让整个组织从每一次事故中变得更强；写得不好的 postmortem 让所有人更害怕出错。在远程环境下，postmortem 是你"异步教学"的绝佳工具——一个好 postmortem 读完，读者不仅了解了事故本身，还学到了这个系统的运作原理。

**Key principle: Blameless.** 不问责个人，问责系统和流程。

#### Template

```markdown
# Incident Report: [Brief Title]

| Field | Value |
|-------|-------|
| **Date** | YYYY-MM-DD |
| **Duration** | HH:MM–HH:MM (X hours Y minutes) |
| **Severity** | P0 / P1 / P2 |
| **Impact** | [谁受影响？多少用户？丢了多少钱？] |
| **Authors** | @handle-1, @handle-2 |

## Timeline (all times in UTC)

| Time | Event |
|------|-------|
| 14:32 | [First symptom / alert] |
| 14:35 | [Engineer acknowledges] |
| 14:42 | [First diagnosis attempt] |
| 14:58 | [Root cause identified] |
| 15:10 | [Fix deployed] |
| 15:15 | [System fully recovered] |

## Root Cause

[用 1-2 段解释：不是"谁做了什么错事"，而是"什么系统条件允许了错误的发生"]

## What Went Well

- [发现环节、响应速度、协作、回滚效率...]

## What Went Wrong

- [告警延迟？诊断工具不够？知识覆盖不足？依赖关系不清楚？]

## Action Items

| # | Action | Owner | Priority | Due |
|---|--------|-------|----------|-----|
| 1 | [具体、可执行、可验证] | @ | P0 | |
| 2 | | | | |
```

#### Language Patterns for Blameless Writing

"Blameless"不是"不追究"——它是"改变主语"的艺术。把主语从"人"换成"系统/流程/条件"。

| 问责式 (Avoid) | 无问责式 (Use) | 语法技巧 |
|---------------|---------------|---------|
| Bob pushed the wrong config and took down prod. | A configuration change triggered an unexpected cascading failure. | 主语从人 (Bob) 换成事 (A configuration change) |
| Alice forgot to add a rate limit. | The endpoint lacked rate limiting. | 主语从事人 (Alice) 换成系统属性 (The endpoint) |
| The on-call didn't notice the alert for 20 minutes. | The alert was not acknowledged for 20 minutes. | 用被动语态消去人的动作 |
| Tom misconfigured the load balancer. | The load balancer was configured in a way that... | 被动语态 + 事实陈述 |
| If only we had tested more... | Our test coverage did not include this edge case. | 用事实代替反事实假设 |

#### Annotated Example — Root Cause Section

> **The root cause was a subtle interaction between the connection pool configuration and the database's transaction isolation level. Specifically, when the connection pool was exhausted under peak load — a scenario that had been observed in staging but dismissed as "unlikely in production" — the application, rather than failing fast with a clear error, began to queue requests indefinitely. This behavior was the result of a default timeout value of `0` (meaning "no timeout") in the connection library, which had been carried over from the initial prototype without review. Under normal load, this default was harmless; under the specific traffic pattern that triggered the incident, it caused a complete thread-pool exhaustion within 90 seconds.**

**语法亮点:**
- [M2] 过去完成时 (had been exhausted, had been observed, had been carried over) — 精确排序: 事故发生在过去，而这些条件在事故发生前就已存在
- [M3] 复杂定语从句链: "a default timeout value of `0`...in the connection library, which had been carried over..."
- [M4] rather than + -ing (rather than failing) — 优雅的对比
- [M5] 破折号中的插入语 "— a scenario that had been observed..." — 补充关键背景而不打断主句
- [M4] Under normal load..., under the specific traffic pattern... — 两个条件状语形成对比

#### Common Pitfalls in Postmortems

1. **时态一致性**: 大多数描述用过去时。但"系统当前的状态"用现在时。不要混用。
2. **冠词**: "**the** connection pool" (特指这个系统的), "**∅** connection pools in general" (泛指)
3. **介词**: "**under** peak load", "**in** production", "**within** 90 seconds", "**as a result of**"
4. **被动语态过度使用**: 偶尔用主动语态让人读起来更轻松——"We identified the root cause at 14:58" 比 "The root cause was identified at 14:58" 更直接
5. **模糊的 Action Items**: "Improve monitoring" → "Add a pager alert for connection pool utilization > 80%"

---

### 1.4 场景四：写高效的异步更新 (Async Updates — Slack, Email, Status Reports)

**Why this matters:** 分布式团队的核心沟通模式是异步的。你每天在 Slack 和 Email 中写的消息，比你写的任何 RFC 或 PR 描述都多得多。好的异步消息是：读完不需要追问。差的消息引发 5 轮"Wait, what do you mean?"的回复。

#### Template — Daily Standup (Async)

```markdown
**Yesterday:**
- [What I did — 1-2 bullets]
- [Blockers encountered — if any]

**Today:**
- [What I plan to do — 1-2 bullets]

**Blockers / Need help with:**
- [Specific ask — no vague "need to discuss architecture"]
```

#### Template — Status Update / Email

```markdown
Subject: [Project Name] Update — [Date]

TL;DR: [1 sentence summary of where things stand]

**Progress this week:**
- ✅ [Completed items]
- 🟡 [In progress, on track]
- 🔴 [In progress, at risk — with explanation]

**Key decisions needed:**
- [Decision 1 — with options and recommendation]
- [Decision 2]

**Next steps:**
- [What happens next and who's responsible]
```

#### Language Patterns

| 场景 | 推荐表达 | 语法要点 |
|------|---------|---------|
| 快速总结 (TL;DR) | **TL;DR:** The migration is on track and we're targeting a Monday deploy. | TL;DR = Too Long; Didn't Read; 用一般现在时 |
| 标记进度 | The feature is **on track** / **at risk** / **blocked on** [dependency]. | blocked on = 被...阻塞 |
| 请求帮助 | **I could use some help with** [specific thing]. / **Would appreciate a second pair of eyes on** [thing]. | 礼貌但不卑微; 不用 "Sorry for bothering you" |
| 请求决策 | **Decision needed:** [options]. I recommend [X] because [reason]. | 提供选项 + 推荐 + 原因 — 减少来回 |
| 标记就绪 | [Thing] **is ready for review** / **is unblocked** / **has been deployed**. | 被动语态标记状态 |
| 表达不确定性 | **My understanding is that**... / **As far as I can tell**,... / **I'm not 100% sure, but**... | 降低确定性的表达——在英语中很重要 |
| 表达关注 | **One thing I'm watching is**... / **A potential risk is**... / **I'm slightly concerned about**... | 用名词短语 (I'm concerned) 而不是 you should be concerned |

#### Annotated Example — Async Standup in Slack

> **Yesterday:** Shipped the rate-limiting middleware to staging — all integration tests passed. Ran into a minor issue with Redis Cluster topology detection that took ~2 hours to debug. [M2: simple past — 昨天发生的事]
>
> **Today:** Plan to run the staging soak test for 4 hours, and — assuming [M3: -ing participle as conditional] no issues surface — will flip the feature flag for 1% canary in production by EOD. [M2: future with will — 今日计划]
>
> **Blocker:** Need a review on PR #892 (auth middleware refactor) before I can proceed with the canary. [M4: before I can proceed — present tense in time clause] @sarah whenever you get a chance — no rush. [M5: imperative softened with "whenever you get a chance"]

**语言要点:**
- 动词时态信号: Yesterday → simple past; Today → future/plan to; Blocker → present tense
- 折线号 — 用于插入条件而不打断句子节奏
- "@sarah whenever you get a chance — no rush" — 缓和请求，不施加不必要的压力

#### Common Pitfalls in Async Updates

1. **"Sorry for bothering you"**: 每分钟在 Slack 上发送的消息中都有这句话。正面表达: "Thanks for taking a look", "When you have a moment..."
2. **模糊的请求**: "Need help with the auth stuff" → "Need a review on the auth middleware PR (#892) — specifically the token refresh logic."
3. **信息密度过低**: "Yesterday I did some coding. Today I will do more coding." → 无信息量。至少说出你写了什么、在哪。
4. **TL;DR 没有提供真正有用的信息**: "TL;DR: Things are going well" → "TL;DR: Migration is 60% done; on track for Monday; no blockers."
5. **时态乱跳**: 不要昨天的更新用现在时，今天的计划用过去时。建立明确的时态节奏。

---

### 1.5 场景五：用英语进行会议发言 (Meeting Facilitation — Standup, Retro, Planning)

**Why this matters:** 分布式团队有同步会议——standup, retro, sprint planning。这些会议中，你需要用英语表达观点、推动议程、回应他人、处理冲突。中国工程师常因为"担心英语不够好"而选择沉默——但往往你的观点是最需要的那个。

#### Language Patterns by Meeting Type

**Daily Standup (15 min, 每人 1-2 分钟)**

| 你需要说的事 | 推荐表达 |
|-----------|---------|
| 报告进度 | Yesterday I **worked on**..., and I **got** [X] working / merged / deployed. |
| 今天的计划 | Today I'll **be focusing on**... / I **plan to pick up** [ticket]. |
| 遇到了阻碍 | I'm **blocked on** [thing]. / I **ran into an issue with** [thing]. / **Could use some help** with [thing]. |
| 正在等某人 | I'm **waiting on** a review from @handle / **pending** a decision on [thing]. |

**Sprint Retrospective (1 hour)**

| 你需要说的事 | 推荐表达 |
|-----------|---------|
| 分享正面观察 | One thing that **went really well** was... / I **really appreciated** how [person] did [thing]. |
| 分享建设性反馈 | One thing **I think we could improve** is... / **It might help if** we... / **I wonder if** we could... |
| 表达不同意见 | **I see it a bit differently** — [reason]. / **That's a fair point, and I'd add** that... / **I hear you, but** my concern is... |
| 建议试验/行动 | **What if we tried** [idea] for one sprint? / **Could we experiment with** [thing]? |
| 总结共识 | **So it sounds like we're all agreed on** [X]. / **To summarize,** we'll try [Y] next sprint. |

**Sprint Planning (1-2 hours)**

| 你需要说的事 | 推荐表达 |
|-----------|---------|
| 估算任务 | **I'd estimate** this at [N] points **because**... / **This one feels** like an 8 — there's a lot of unknowns. |
| 质疑估算 | **What makes this an 8?** / **Can you walk me through** the complexity? |
| 拆分任务 | **Could we break this down** into smaller deliverables? / **What's the smallest shippable version** of this? |
| 标记依赖 | **This depends on** [ticket/team] completing [thing]. / **We can't start this until** [condition]. |
| 承揽任务 | **I can take that** / **I'll pick that up** / **Happy to own** [thing]. |

#### Handling Difficult Moments

| 时刻 | 可能想说的话 (但可能太生硬) | 更好的表达方式 |
|------|----------|------------|
| 你想打断某人 | (沉默) | **Sorry to jump in, but** I want to make sure we capture this point... |
| 你不同意某人的方案 | "That won't work." | **I'm a bit worried about** [specific concern]. **What if** [scenario]? |
| 你觉得会议跑题了 | "This is off-topic." | **This is an important discussion — should we table it** for a follow-up and get back to the main agenda? |
| 你不确定是否理解对了 | "I don't understand." | **Let me play back what I'm hearing** to make sure I've got it right... |
| 你想支持某人的观点 | (沉默) | **I just want to +1 what [person] said** about [point]. That matches my experience. |
| 你需要更多时间思考 | "I don't know." | **That's a great question — let me think about it** and get back to you async. |

#### Common Pitfalls in Meeting Communication

1. **过度道歉**: "Sorry, my English is not good" / "Sorry, maybe this is a stupid question" → 直接说你的观点。同事在乎的是你的想法，不是你的口音。
2. **过度简略**: "I think this is bad." → "I think this approach has a scalability concern — if traffic doubles, the current design won't handle the load."
3. **过度复杂**: 试图一次性展示你的全部英语能力 → 在会议中用简洁、清晰的短句比复杂的从句更有效。
4. **不会表示"不确定"**: 英语中有大量降低确定性的表达 (hedging) — "I'm not entirely sure but...", "My gut feeling is...", "I could be wrong, but..." — 使用它们，不要觉得表达不确定就是"不专业"。
5. **不会说"不"**: "Maybe..." (当你其实想说"不") → "I don't think that's the right approach **because**..." / "I'd push back on that **because**..."

---

### 1.6 场景六：处理困难的异步对话 (Difficult Conversations in Async)

**Why this matters:** 远程工作中，最困难的那些对话往往是在 Slack / Email / Notion 中而非面对面发生的——说"不"、提出批评、质疑方案、反馈不佳的绩效。这些对话需要同时做到：清晰、直接、尊重、不引发防御反应。这对母语者都很难，对非母语者是更大的挑战。

#### Pattern 1: Saying "No" to a Request

**The Formula:** Acknowledge → Explain constraint → Offer alternative → Leave door open

> ❌ "No, we can't do this right now." (太直接，无上下文)
>
> ✅ "This is a great idea — and I can see why it's a priority for the customer. **However**, given that we're currently focused on the Q3 reliability push (which has a hard deadline of Sept 30), **I don't think we should** context-switch the team onto this right now. **What I can do is** add it to the backlog for Q4 planning, or if it's more urgent, we could discuss pulling in a contractor. **Does that work for you?**"

**Language breakdown:**
- "This is a great idea — and I can see why..." — validation before pushback
- "However, given that..." — explain constraint (given + clause = considering)
- "I don't think we should..." — not "we can't" but "I don't think we should" — personal opinion rather than universal rule
- "What I can do is..." — M5 emphasis: What 伪分裂句，强调你愿意做的替代方案
- "Does that work for you?" — 不是 end of conversation, 而是邀请继续对话

#### Pattern 2: Giving Critical Feedback on a Technical Proposal

**The Formula:** Point to the work, not the person → Be specific → Suggest

> ❌ "This architecture won't scale." (太模糊,太绝对)
>
> ✅ "I've been reading through the RFC, and I have a concern about the **scalability of the proposed event-sourcing approach**. Specifically [M5: emphasis — 具体化], if we project to 10x traffic over the next year, the event store would need to handle ~500K writes/sec — which, based on our load tests from last quarter, the current Kafka setup won't support without significant tuning. **One alternative we could consider** is CQRS with a read-optimized projection — it's more operational complexity upfront, but it decouples read and write scaling. **Curious to hear your thoughts on this.**"

**Language breakdown:**
- "I have a concern about the scalability **of the proposed**..." — 评论的是提案，不是提案的人
- "Specifically, if we project to..." — 用数据/场景支撑你的关切，而不是凭感觉
- "One alternative we could consider..." — could 表示建议而非命令; one 表示"可能还有别的"
- "Curious to hear your thoughts" — 邀请讨论，而非单方面评判

#### Pattern 3: Raising a Concern About a Timeline

**The Formula:** State your concern clearly → Provide evidence → Suggest a path forward

> ❌ "This deadline is unrealistic." (正确但太直接)
>
> ✅ "I'm a bit worried about the **October 1 deadline**. Here's why: we've historically needed ~3 weeks for integration testing for changes of this size, and we haven't started yet — which would put us at Oct 10 at the earliest if we started integration testing tomorrow. **I want to flag this now** rather than closer to the deadline. **My suggestion would be** to either extend the date by two weeks, or reduce scope by moving the reporting module to Phase 2. **What do folks think?**"

**Language breakdown:**
- "I'm a bit worried about..." — 明确表达担忧,用 "a bit" 降低语气而非降低内容
- "Here's why:" + 数据 → 事实 > 感受
- "I want to flag this now rather than..." — 体现你提前说话是负责任，不是找麻烦
- "My suggestion would be..." — would be (conditional / softening), not "My suggestion is..."
- "What do folks think?" — 不是 "We need to do this", 而是把选择权交给团队

#### Pattern 4: Following Up on an Unanswered Request

**The Formula:** Gentle reminder → Restate the ask → Make it easy to respond

> ❌ "Did you see my message?" (听起来像指责)
>
> ✅ "Hey @person, just a gentle nudge on the PR review for #892 whenever you get a chance. I know things are busy — if there's someone else who could review it, happy to redirect. Thanks!"

**Language breakdown:**
- "just a gentle nudge" — 低压力提示
- "whenever you get a chance" — 不紧迫
- "I know things are busy" — 承认对方可能很忙 — empathy
- "if there's someone else..." — 提供逃生舱口
- "Thanks!" — 正面结束

#### Common Pitfalls in Difficult Conversations

1. **过度委婉导致信息丢失**: "I was just thinking maybe perhaps we could consider..." — 这是在说什么？
2. **直接翻译中文客套**: "I am really ashamed to say this but..." / "I am sorry to raise this but..." → 不要让中文的谦逊文化削弱你的英语表达。
3. **缺少结构**: 一段长文字无段落无结构 → 用公式: Acknowledge → Explain → Suggest → Ask
4. **太绝对**: "This is wrong" → "I think there might be an issue with..."
5. **不会结束对话**: "That's all." → "Let me know what you think." / "Happy to discuss further."

---

## 2. Vocabulary — 300 B2-C1 词汇

### Group 1: Remote Work & Collaboration Tools (远程协作与工具)

| # | Word | Meanings | Example Sentences |
|---|------|----------|-------------------|
| 1 | **async** | ① 异步的 not occurring at the same time ② (工作语境) 异步沟通 communication that doesn't require immediate response ③ (编程语境) 非阻塞的 not blocking execution | ① Remote teams default to **async** communication to respect time zones. ② An **async** standup in Slack replaces the synchronous morning meeting. ③ The **async** function returns a promise rather than blocking the main thread. |
| 2 | **bandwidth** | ① 带宽 the range of frequencies within a given band ② 网络带宽 the maximum data transfer rate of a network ③ (口语) 精力/时间 capacity to take on additional work | ① Video calls consume significantly more **bandwidth** than audio. ② I don't have the **bandwidth** to take on another project this quarter. ③ We upgraded the server's **bandwidth** to handle the traffic spike. |
| 3 | **onboarding** | ① 入职培训 the process of integrating a new employee ② 新用户体验 the process of familiarizing a new user with a product ③ 上手引导 the initial orientation to a system | ① Our **onboarding** process pairs each new hire with a buddy for the first month. ② The app's **onboarding** flow has a 40% drop-off rate at step 3. ③ Developer **onboarding** should take no more than one day to ship a first commit. |
| 4 | **standup** | ① 站立会议 a brief daily team meeting ② 每日敏捷会议 a daily scrum meeting ③ 站立 posture of standing | ① Our daily **standup** is async — we post updates in Slack by 10am. ② Keep the **standup** brief — if it's over 15 minutes, it's a status meeting. ③ The comedian's **standup** routine went viral on YouTube. |
| 5 | **retro** | ① 回顾会议 a meeting to reflect on what went well and what to improve ② 迭代回顾 a sprint retrospective in scrum ③ (游戏语境) 复古风格 imitative of a past style | ① The sprint **retro** is our most valuable meeting — it's where we actually improve. ② We run blameless **retros** — no finger-pointing, just process improvement. ③ The game has a charming **retro** aesthetic inspired by 16-bit consoles. |
| 6 | **unblock** | ① 清除障碍 to remove an obstacle preventing progress ② 解决问题 to help someone overcome a blocker ③ 疏通 to clear a blocked passage | ① Can someone from the platform team **unblock** me on this deployment issue? ② The best use of an engineering manager's time is to **unblock** their reports. ③ The plumber came to **unblock** the drain. |
| 7 | **stakeholder** | ① 利益相关者 a person with an interest or concern in something ② 相关方 someone involved in or affected by a project ③ 股东 a person who holds shares in a company | ① We need to align with all **stakeholders** before the architecture decision. ② The PM presented the roadmap to **stakeholders** across product, engineering, and sales. ③ Shareholders are financial **stakeholders**, but employees are operational **stakeholders**. |
| 8 | **sync** | ① 同步 to make things operate at the same time ② 沟通对齐 to exchange updates to reach alignment ③ 同步数据 to make data consistent across devices | ① Let's **sync** up on the migration plan before the all-hands. ② I'll **sync** with the platform team and report back. ③ The offline-first app **syncs** data when connectivity is restored. |
| 9 | **deep dive** | ① 深入探讨 a thorough analysis of a topic ② 深潜 to thoroughly investigate something ③ (潜水语境) to dive deep underwater | ① We'll do a **deep dive** into the latency issue in tomorrow's tech talk. ② The postmortem includes a **deep dive** into the connection pool configuration. ③ The submarine can **deep dive** to 300 meters. |
| 10 | **pager** | ① 寻呼机 a device that receives alerts ② 值班报警 the on-call alerting system ③ 寻呼 to send an alert to an on-call engineer | ① My **pager** went off at 3am — the database was down. ② We use PagerDuty to route **pager** alerts to the on-call rotation. ③ The **pager** fatigue from false alarms is a real problem for SRE teams. |
| 11 | **on-call** | ① 值班的 available to respond to emergencies outside working hours ② 待命的 ready to be called upon when needed ③ 值班工程师 the engineer responsible for incident response | ① I'm **on-call** this week — don't expect rapid PR reviews from me. ② The **on-call** rotation is one week primary, one week secondary, two weeks off. ③ **On-call** responsibility should be compensated and sustainable. |
| 12 | **war room** | ① 作战室 a room dedicated to managing an emergency ② 应急指挥中心 a command centre for incident response ③ (引申) 临时应紧团队 an ad-hoc team assembled for a crisis | ① We opened a **war room** channel in Slack when the database went down. ② The **war room** had engineers from three teams debugging simultaneously. ③ After 4 hours in the **war room**, we finally identified the root cause. |
| 13 | **postmortem** | ① 事故复盘 a review of an incident after it occurs ② 事后分析 an analysis conducted after an event ③ (医学语境) 验尸 an examination of a dead body | ① Every P1 incident requires a blameless **postmortem** within 48 hours. ② The **postmortem** revealed that the alert fired, but nobody was on-call. ③ Writing **postmortems** is the closest thing engineers have to organizational learning. |
| 14 | **rollback** | ① 回滚 to revert to a previous version ② 撤销部署 the act of undoing a deployment ③ 回档 restoring a previous state | ① The feature flag allowed an instant **rollback** — we just turned it off. ② Database migrations are hard to **rollback** — always test them on a clone first. ③ The **rollback** procedure was documented and took 2 minutes to execute. |
| 15 | **canary** | ① 金丝雀 a small songbird ② (技术语境) 金丝雀部署 a deployment to a small subset of users ③ 预警信号 an early indicator of danger | ① The **canary** deployment routes 1% of traffic to the new version. ② If the **canary** shows no errors for 30 minutes, we proceed to full rollout. ③ Miners used **canaries** to detect toxic gases — our canary deployment serves the same purpose. |
| 16 | **flag** | ① 旗帜 a piece of cloth used as a symbol ② (技术语境) 功能开关 a toggle for enabling/disabling a feature ③ 标记 to call attention to something | ① We launched behind a feature **flag** — only internal users can see it. ② I **flagged** this risk in the design review last month. ③ The linter **flagged** three potential security vulnerabilities. |
| 17 | **flake** | ① 不可靠的 tending to cancel plans or commitments ② (测试语境) 不稳定测试 a test that passes and fails intermittently ③ 薄片 a small, flat, thin piece | ① The test is **flaky** — it passes locally but fails on CI about 30% of the time. ② We disabled the **flake** test and filed a ticket to investigate. ③ Don't be **flaky** — if you say you'll do something, do it. |
| 18 | **hydrate** | ① 水合 to cause to absorb water ② (技术语境) 填充数据 to fill a data structure with data ③ 补水 to restore fluid levels | ① The frontend **hydrates** the server-rendered HTML with client-side interactivity. ② The API response is **hydrated** with related entities before being sent to the client. ③ Remember to **hydrate** during long debugging sessions — your brain needs water. |
| 19 | **idempotent** | ① 幂等的 (of an operation) producing the same result if applied multiple times ② 可重复执行的 safe to retry without side effects ③ (数学语境) unchanged when multiplied by itself | ① PUT requests should be **idempotent** — making the same request twice should have the same effect as making it once. ② We made the payment processing **idempotent** to prevent double-charging on retries. ③ An **idempotent** operation is essential for reliable distributed systems. |
| 20 | **throttle** | ① 节流/限流 to control or limit the speed or capacity of something ② 油门 a device controlling the flow of fuel to an engine ③ 压制 to suppress or inhibit | ① The API gateway **throttles** requests that exceed 1000/min per client. ② We need to **throttle** the database writes to prevent replication lag. ③ He pushed the **throttle** to full speed. |
| 21 | **spin up** | ① 启动 to start a new instance or environment ② 快速创建 to create quickly ③ 旋转加速 to rotate faster | ① I need to **spin up** a staging environment to test the migration. ② It takes about 30 seconds to **spin up** a new container. ③ Let me **spin up** a quick proof of concept before we commit to the full implementation. |
| 22 | **teardown** | ① 拆除 to dismantle or take apart ② 清理 to clean up infrastructure after use ③ 拆除工作 the process of dismantling something | ① The CI pipeline automates environment **teardown** after tests complete. ② We forgot to run the **teardown** script, and the cloud bill was $2,000 higher than expected. ③ The stage crew handled the set **teardown** after the concert. |
| 23 | **boot** | ① 启动 to start a computer or system ② 踢 to kick someone or something ③ (口语) 开除 to dismiss someone from a job | ① The server takes ~90 seconds to **boot** completely. ② A cold **boot** of the application loads all data from scratch. ③ He was **booted** from the project after missing three consecutive deadlines. |
| 24 | **provision** | ① 配置/供应 to provide or make available ② 基础设施即代码 the automated setup of infrastructure ③ 法律条款 a clause in a legal document | ① Terraform **provisions** our cloud infrastructure declaratively. ② New developer environments are **provisioned** automatically on the first day. ③ The contract includes a **provision** for early termination. |
| 25 | **orchestrate** | ① 编排 to arrange or coordinate complex operations ② 精心策划 to organize a complicated plan ③ (音乐语境) 配器 to arrange music for an orchestra | ① Kubernetes **orchestrates** container deployment across the cluster. ② The release manager **orchestrated** the complex multi-service rollout. ③ The CTO **orchestrated** the merger of two engineering organizations. |
| 26 | **ingest** | ① 摄入/采集 to take in or absorb ② 数据采集 to take data into a system for processing ③ 摄取 to consume food or drink | ① Our telemetry pipeline **ingests** 2 million events per second. ② The log **ingestion** service buffers data before writing to S3. ③ The patient was unable to **ingest** solid food after the surgery. |
| 27 | **funnel** | ① 漏斗 a tube with a wide top and narrow bottom ② 转化漏斗 a model of customer journey from awareness to purchase ③ 汇聚 to channel or direct something | ① The signup **funnel** converts 12% of visitors to registered users. ② We analyzed the drop-off at each stage of the onboarding **funnel**. ③ All support tickets are **funnelled** through a single triage queue. |
| 28 | **ramp** | ① 斜坡 a sloping surface joining two levels ② 逐步增加 to increase something gradually ③ 加速 to increase in speed or intensity | ① We'll **ramp up** the traffic gradually — 1%, 10%, 50%, 100%. ② New hires typically need 3 months to fully **ramp up** on the codebase. ③ The **ramp** at the entrance provides wheelchair access. |
| 29 | **graceful** | ① 优雅的 showing elegance in form or movement ② (技术语境) 优雅的 handling failure without crashing ③ 体面的 polite and considerate | ① The system is designed to fail **gracefully** — it degrades functionality rather than crashing completely. ② A **graceful** shutdown lets in-flight requests complete before terminating. ③ She gave a **graceful** response to the tough question — acknowledging the concern without getting defensive. |
| 30 | **offline** | ① 离线的 not connected to the internet ② 脱机的 not online ③ (口语) 私下讨论 to discuss outside the current context | ① The app supports **offline** mode and syncs when connectivity returns. ② Let's take this **offline** — we can discuss the details in a separate thread. ③ The satellite was temporarily **offline** during the solar storm. |
| 31 | **availability** | ① 可用性 the state of being able to be used or obtained ② (系统语境) 正常运行时间 the proportion of time a system is operational ③ 可获取性 the quality of being at hand when needed | ① Our SLA guarantees 99.99% **availability** — that's less than 53 minutes of downtime per year. ② The **availability** zone architecture ensures the system survives a single data center failure. ③ Check the team calendar for the PM's **availability** before scheduling the review. |
| 32 | **fault-tolerant** | ① 容错的 able to continue functioning despite failures ② 具备容错能力的 designed to handle component failures ③ 容错 tolerance for errors or faults | ① A **fault-tolerant** system continues to serve traffic when a node fails. ② The consensus algorithm is **fault-tolerant** up to (n-1)/2 node failures. ③ Code review culture should be **fault-tolerant** — punishing every mistake creates fear. |
| 33 | **dashboard** | ① 仪表盘 a panel with instruments and controls ② 数据看板 a visual display of key metrics ③ 控制面板 a graphical summary of important information | ① The Grafana **dashboard** shows real-time latency, error rate, and throughput. ② The CEO has a **dashboard** of company-wide KPIs on her second monitor. ③ We built a custom **dashboard** to track the migration progress across all services. |
| 34 | **alert** | ① 警报 a warning of danger or a problem ② 告警通知 a notification requiring attention ③ 提醒 to warn someone of a situation | ① The monitoring system sends an **alert** when the error rate exceeds 1%. ② Alert fatigue — when engineers start ignoring **alerts** — is worse than no alerts at all. ③ I'll **alert** the team when the deployment completes. |
| 35 | **incident** | ① 事故 an event that disrupts normal operations ② 事件 an occurrence, especially one that is unexpected ③ 严重事件 a serious event requiring investigation | ① Every production **incident** has a postmortem and action items. ② The **incident** response process is documented in the on-call playbook. ③ What first seemed like a minor issue escalated into a major **incident** within 30 minutes. |
| 36 | **pipeline** | ① 管道 a system of pipes for transporting liquids or gas ② (技术语境) 持续集成/交付管道 the automated build-test-deploy workflow ③ 流程 a linear sequence of processing stages | ① The CI **pipeline** runs linting, tests, and security scans on every commit. ② We're expanding our data **pipeline** to handle 10x the current volume. ③ The feature is in the development **pipeline** for Q4. |
| 37 | **source of truth** | ① 单一事实来源 the authoritative source for a given piece of information ② 真实数据源 the primary location where data is maintained ③ 标准参考 the definitive reference | ① The git repository is the **source of truth** for all infrastructure configuration. ② Don't let Slack messages become the **source of truth** — write it down in a document. ③ The API is the **source of truth** for user data — the database should not be accessed directly. |
| 38 | **turnaround** | ① 周转时间 the time taken to complete a task ② 彻底的转变 a sudden and complete change ③ 掉头 a vehicle's ability to reverse direction | ① We have a 24-hour **turnaround** on PR reviews. ② The new CTO led a remarkable **turnaround** of the engineering culture. ③ The quick **turnaround** on the hotfix impressed the customer. |
| 39 | **regression** | ① 回归 a return to a former or less developed state ② (技术语境) 功能回退 a bug that causes a previously working feature to break ③ (统计语境) 回归分析 a statistical method for estimating relationships | ① The refactor introduced a **regression** — the login page no longer works. ② We run a full **regression** suite before every release. ③ **Regression** testing ensures that new changes don't break existing functionality. |
| 40 | **handoff** | ① 交接 the transfer of responsibility from one person to another ② 移交 the act of passing work to someone else ③ (体育语境) the act of passing the ball to a teammate | ① The **handoff** between the US and India teams happens at 10am ET. ② Write clear **handoff** notes — assume the next person has zero context. ③ The on-call **handoff** includes a summary of overnight incidents. |
| 41 | **overlap** | ① 重叠 to partially cover the same area or period ② 交叉 a period when two people or things coexist ③ 共同之处 an area of shared interest or responsibility | ① We have a 2-hour **overlap** window with the Berlin office for synchronous meetings. ② There's significant **overlap** between the two microservices — they should probably be merged. ③ The **overlap** between backend and SRE responsibilities needs clarification. |
| 42 | **distributed** | ① 分布的 spread across different locations ② 分布式的 operating across multiple nodes ③ 分散的 not centralized or concentrated | ① Our team is **distributed** across 8 time zones. ② **Distributed** systems introduce challenges that single-machine applications never face. ③ Knowledge should be **distributed** across the team — no single person should be a bottleneck. |
| 43 | **timezone** | ① 时区 a region with a uniform standard time ② 跨时区的 across multiple time zones ③ 时间差 the difference in time between locations | ① We schedule meetings during the **timezone** overlap window (3-5pm UTC). ② Working across **timezones** requires strong async communication habits. ③ I keep three clocks on my desktop: my **timezone**, my team's **timezone**, and UTC. |
| 44 | **whiteboard** | ① 白板 a wipeable board for writing or drawing ② 协作绘图 to sketch ideas collaboratively ③ (面试语境) 白板面试 a technical interview involving writing code on a board | ① Let's **whiteboard** the architecture before we start coding. ② Miro is our virtual **whiteboard** for remote design sessions. ③ **Whiteboard** interviews are increasingly being replaced by take-home exercises. |
| 45 | **screen share** | ① 屏幕共享 the act of sharing one's computer screen ② 共享屏幕 to allow others to view your display ③ 桌面共享 desktop sharing during video calls | ① Let me **screen share** the error logs — it's easier than describing them. ② **Screen sharing** during debugging sessions is the remote equivalent of pair programming. ③ Before your presentation, make sure to close any personal tabs — you'll be **screen sharing**. |
| 46 | **brainstorm** | ① 头脑风暴 to generate ideas spontaneously ② 集思广益 a group discussion to produce ideas ③ 脑力激荡 to think creatively and collaboratively | ① Let's **brainstorm** solutions before we evaluate any single approach. ② The **brainstorming** session produced more bad ideas than good ones — that's the point. ③ We **brainstormed** the architecture for two hours and landed on a promising direction. |
| 47 | **rubber duck** | ① 橡皮鸭 a bath toy ② (编程语境) 橡皮鸭调试法 explaining a problem to an inanimate object to find the solution ③ (引申) 倾诉对象 someone who listens while you think out loud | ① Let me **rubber duck** this bug with you — I just need to talk it through. ② Half the time, explaining the problem to a **rubber duck** makes the solution obvious. ③ A good mentor knows when to be a **rubber duck** — just listening — and when to jump in. |
| 48 | **dogfood** | ① (技术语境) 内部测试 to use one's own product internally ② 吃自己的狗粮 the practice of using your own product ③ 自用测试 internal usage before external release | ① We **dogfood** every feature for at least two weeks before public release. ② **Dogfooding** the developer tool uncovered UX issues we'd never have found otherwise. ③ If you won't use your own product, why should anyone else? |
| 49 | **permission** | ① 许可 authorization to do something ② 权限 the access rights granted to a user ③ 允许 consent given by someone in authority | ① I don't have **permission** to deploy to production — can someone approve? ② The principle of least **permission** means granting only the access a role strictly needs. ③ Always ask for **permission** before force-pushing to a shared branch. |
| 50 | **calendar** | ① 日历 a chart showing the days, weeks, and months of a year ② 日程安排 a schedule of planned events ③ 日历应用 the software managing appointments | ① My **calendar** is open — feel free to grab a slot that works for you. ② Block **calendar** time for deep work or your day will fill with meetings. ③ The release **calendar** shows all planned deployments for the quarter. |

### Group 2: Technical Documentation & Writing (技术文档与写作)

| # | Word | Meanings | Example Sentences |
|---|------|----------|-------------------|
| 51 | **prose** | ① 散文 written language in its ordinary form ② 文风 a style of written expression ③ 平实文字 plain, straightforward writing | ① Good code comments are concise **prose**, not technical poetry. ② The documentation should be clear **prose** that a new hire can understand. ③ His writing style — **prose** that is precise without being cold — makes even RFCs enjoyable to read. |
| 52 | **disambiguation** | ① 消歧义 the process of resolving ambiguity ② 澄清 clarifying which meaning is intended ③ 消除歧义 removing confusion about meaning | ① Technical writing is mostly **disambiguation** — making sure every sentence has exactly one interpretation. ② We added a glossary for **disambiguation** of overloaded terms like "service" and "module". ③ Named parameters improve **disambiguation** in function calls — `createUser(name: "John")` is clearer than `createUser("John")`. |
| 53 | **jargon** | ① 行话 special words used by a profession ② 专业术语 technical terminology ③ 难懂的语言 language that is difficult for outsiders to understand | ① Too much **jargon** in the README will scare away new contributors. ② **Jargon** accelerates communication within a team but excludes outsiders. ③ "Synergy", "paradigm shift", "circle back" — business **jargon** that conveys very little. |
| 54 | **glossary** | ① 术语表 an alphabetical list of terms with definitions ② 词汇表 a dictionary of specialized terms ③ 术语汇编 a collection of terms in a specific domain | ① Every project should have a **glossary** defining key terms — what exactly is a "workspace"? ② The **glossary** helped the new team members understand our domain language. ③ Domain-Driven Design emphasizes maintaining a **glossary** of ubiquitous language. |
| 55 | **concise** | ① 简洁的 giving a lot of information clearly in a few words ② 简练的 brief but comprehensive ③ 言简意赅的 short and clear, with no wasted words | ① A good commit message is **concise** — 50 characters or less for the subject line. ② The best engineer I ever worked with wrote **concise** RFCs — every paragraph earned its place. ③ Be **concise** without being cryptic. |
| 56 | **verbose** | ① 冗长的 using more words than needed ② 啰嗦的 expressed in more words than necessary ③ (技术语境) 详细的 producing detailed logging output | ① The documentation is too **verbose** — it takes 10 pages to explain what could be a diagram. ② Run the compiler in **verbose** mode to see what's happening under the hood. ③ Avoid **verbose** variable names — `userList` is fine, `listOfAllRegisteredUsersInTheSystem` is not. |
| 57 | **coherent** | ① 连贯的 logical and consistent ② 条理清晰的 united as or forming a whole ③ 有逻辑的 easy to understand because of logical connection | ① The RFC was remarkably **coherent** — every section flowed naturally into the next. ② After three rounds of edits, the postmortem became **coherent** and persuasive. ③ A **coherent** strategy makes every tactical decision easier. |
| 58 | **succinct** | ① 言简意赅的 briefly and clearly expressed ② 简洁的 concise and precise ③ 精炼的 using few words to convey much meaning | ① A good status update is **succinct**: TL;DR, progress, blockers, asks. ② Her code review comments were **succinct** but always insightful. ③ Being **succinct** is harder than being verbose — it requires deeper understanding. |
| 59 | **proofread** | ① 校对 to read and correct written material ② 审校 to check for errors before publication ③ 检查文字 to read for mistakes | ① Always **proofread** your RFC before sharing it with stakeholders. ② The bug was caught because an engineer **proofread** the release notes and noticed a version mismatch. ③ **Proofread** your Slack messages too — a typo in an incident channel creates confusion. |
| 60 | **annotate** | ① 注释 to add explanatory notes to a text or diagram ② 标注 to add notes to provide explanation ③ 批注 to add critical or explanatory comments | ① The code review tool lets you **annotate** specific lines with comments. ② I **annotated** the RFC diagrams with deployment considerations. ③ The best engineers **annotate** their code — not what it does, but why. |
| 61 | **format** | ① 格式 the way something is arranged or set out ② 格式化 to arrange in a particular format ③ 版式 the layout and presentation of a document | ① Consistent **formatting** makes code easier to read — use a formatter. ② The RFC template standardizes the **format** of all design proposals. ③ We **formatted** the postmortem as a markdown document with clear section headers. |
| 62 | **boilerplate** | ① 样板文件 standardized text that can be reused ② 模板代码 code that is repeated with little alteration ③ 标准措辞 formulaic or standard wording | ① The PR template provides **boilerplate** for the description structure. ② Don't make me read through **boilerplate** — highlight what's different about this PR. ③ Scaffolding tools generate the **boilerplate** so you can focus on business logic. |
| 63 | **outline** | ① 大纲 a general description showing the essential features ② 提纲 a line indicating the shape of something ③ 概述 to give a summary of something | ① Before writing the RFC, share an **outline** with stakeholders for early feedback. ② The postmortem **outline** follows a standard structure: timeline, root cause, action items. ③ Let me **outline** the proposal before diving into implementation details. |
| 64 | **documentation** | ① 文档 material that provides official information ② 说明文件 written instructions about software ③ 文献 documentary evidence or records | ① **Documentation** is a feature — if it's not documented, it doesn't exist. ② The best **documentation** I've ever read was the SQLite website. ③ Code is read far more often than it's written — **documentation** is read even more often. |
| 65 | **style guide** | ① 风格指南 a set of standards for writing and design ② 写作规范 rules for consistent writing style ③ 代码风格指南 rules for code formatting and conventions | ① Google's developer **style guide** is the industry standard for technical writing. ② We have a code **style guide** — tabs vs spaces is no longer a debate. ③ A **style guide** removes trivial decisions so you can focus on substance. |
| 66 | **readme** | ① 自述文件 a file introducing a project ② 项目说明文档 introductory documentation for a repository ③ 项目入门指南 the first document a new user sees | ① The **README** is the most important document in any open-source project. ② A good **README** answers: What is this? Why does it exist? How do I start? ③ If your **README** is 50 pages long, it's not a README — it's a wiki. |
| 67 | **changelog** | ① 更新日志 a record of notable changes for each version ② 版本变更记录 a log of all changes made to a project ③ 修改记录 a list of modifications | ① The **changelog** should be written for users, not for the developers who made the changes. ② Keep a **changelog** — your future self will thank you when debugging a regression. ③ We auto-generate the **changelog** from conventional commit messages. |
| 68 | **whitepaper** | ① 白皮书 an authoritative report on a topic ② 技术白皮书 a document describing a technology or solution ③ 立场文件 a detailed informational document | ① The Bitcoin **whitepaper** proposed a decentralized digital currency in 2008. ② The CTO published a **whitepaper** on the company's technical vision for the next five years. ③ A good **whitepaper** educates without selling — it lets the reader reach their own conclusion. |
| 69 | **pseudocode** | ① 伪代码 a simplified programming language for explaining algorithms ② 类代码 a notation resembling code for explaining logic ③ 算法描述 a human-readable description of an algorithm | ① The RFC uses **pseudocode** to describe the consensus algorithm without language specifics. ② Write the **pseudocode** first — it clarifies your thinking before you commit to a language. ③ Good **pseudocode** should be understandable by a non-programmer. |
| 70 | **playbook** | ① 行动手册 a set of rules or suggestions for handling situations ② 战术手册 a book of strategies or techniques ③ 应急手册 a guidebook for responding to specific scenarios | ① The incident response **playbook** covers the 10 most common failure modes. ② Every senior engineer builds their own debugging **playbook**. ③ When the database went down, the on-call followed the **playbook** and restored service in 8 minutes. |
| 71 | **disclaimer** | ① 免责声明 a statement that denies responsibility ② 声明 a warning or qualification ③ 保留声明 a statement of limitations | ① The postmortem included a **disclaimer**: the timeline was reconstructed from logs and may not be exact. ② Every benchmark needs a **disclaimer** — no single number tells the whole story. ③ The RFC carries the standard **disclaimer**: this is a proposal, not a commitment. |
| 72 | **excerpt** | ① 摘录 a short extract from a text or performance ② 节选 a passage taken from a longer work ③ 片段 a small part of a larger whole | ① Here's an **excerpt** from the postmortem that explains the root cause. ② I'll share an **excerpt** of the design doc in the meeting — the full version is in Notion. ③ The code **excerpt** shows the bug clearly: the array index was off by one. |
| 73 | **verbose** | ① 冗长的 using more words than needed ② 啰嗦的 expressed in more words than necessary ③ (技术语境) 详细的 producing detailed logging output | ① The documentation is too **verbose** — it takes 10 pages to explain what could be a diagram. ② Switch the logger to **verbose** mode to capture all debug output. ③ Avoid **verbose** variable names. |
| 74 | **peer review** | ① 同行评审 evaluation of work by others in the same field ② 代码审查 code review by fellow developers ③ 同级评审 review by people of equal status | ① All RFCs go through **peer review** before the architecture decision. ② **Peer review** is not about finding bugs — it's about sharing knowledge. ③ The paper was accepted after extensive **peer review**. |
| 75 | **wikis** | ① 维基 a website that allows collaborative editing ② 知识库 a shared repository of information ③ 协作编辑平台 a collaborative content platform | ① Our internal **wiki** has become a graveyard of outdated documentation. ② A **wiki** is only as good as its maintenance — someone needs to own it. ③ The team **wiki** is the source of truth for onboarding, runbooks, and architecture decisions. |
| 76 | **draft** | ① 草稿 a preliminary version of a document ② 起草 to prepare a preliminary version ③ 草案 an early version of a proposal | ① This RFC is still a **draft** — feedback welcome, but don't implement yet. ② I'll **draft** a postmortem tomorrow and share it for review. ③ The first **draft** of anything is usually bad — that's what editing is for. |
| 77 | **handbook** | ① 手册 a book giving information or instructions ② 员工手册 the company policy manual ③ 参考手册 a reference book for a specific domain | ① GitLab's company **handbook** is publicly available — all 2,000+ pages of it. ② A team **handbook** documents: how we work, what we believe, and how to get things done. ③ The engineering **handbook** covers our development process, code review standards, and on-call procedures. |
| 78 | **truncate** | ① 截短 to shorten by cutting off a part ② 截断 to cut short ③ (数据库语境) 清空表 to remove all rows from a table | ① The log message was **truncated** — it was too long for the Slack message limit. ② The CSV export **truncated** values longer than 256 characters. ③ NEVER run `TRUNCATE TABLE` on production without a backup and at least two approvals. |
| 79 | **monospace** | ① 等宽字体 a font where each character occupies the same width ② 固定宽度的 having characters of equal width ③ 代码字体 the font style used for code | ① Use **monospace** formatting for inline code in documentation. ② All code examples should be in a **monospace** font. ③ **Monospace** text is easier to align in tables and ASCII diagrams. |
| 80 | **readability** | ① 可读性 the quality of being easy to read ② 易读性 how easy text is to understand ③ 清晰性 clearness and comprehensibility of written content | ① Code **readability** is more important than cleverness — you write once, others read hundreds of times. ② A 5-line function with clear naming has more **readability** than a 1-liner that requires a PhD. ③ **Readability** of postmortems matters — if nobody reads them, the organization doesn't learn. |
| 81 | **typography** | ① 排版 the style and appearance of printed matter ② 字体排印 the art of arranging type ③ 版面设计 the design of text on a page | ① Good **typography** makes documentation more inviting to read. ② The blog's **typography** is clean — generous line spacing, readable font size, clear headings. ③ Developers don't need to be **typography** experts, but they should care enough to make docs readable. |
| 82 | **cross-reference** | ① 交叉引用 a reference to another part of a text ② 对照参考 to refer to another source for additional information ③ 相互参照 a notation directing readers to related content | ① The documentation uses extensive **cross-referencing** — every concept links to its definition. ② Add a **cross-reference** from the API docs to the relevant RFC. ③ **Cross-referencing** creates a web of knowledge rather than isolated pages. |
| 83 | **deprecate** | ① 弃用 to disallow the use of something ② 不推荐 to express disapproval of ③ 声明过时 to mark as obsolete | ① The v1 API has been **deprecated** — migrate to v2 by December. ② The `@deprecated` annotation warns developers that a method will be removed. ③ We **deprecated** the legacy auth system two years ago, but it's still serving 5% of traffic. |
| 84 | **parameter** | ① 参数 a numerical factor forming part of a calculation ② 函数参数 a variable in a function definition ③ 边界条件 a limit or boundary of a system | ① The function takes two **parameters**: a string and a timeout in milliseconds. ② We tuned the garbage collection **parameters** to reduce latency. ③ The team operates within certain **parameters** — budget, timeline, and technical constraints. |
| 85 | **initialization** | ① 初始化 the act of setting initial values ② 启动初始化 the preparation of a system for use ③ 初始设置 the process of preparing something to start | ① The application crashes during **initialization** if the config file is missing. ② Lazy **initialization** defers object creation until it's actually needed. ③ The **initialization** script sets up the database schema and seed data. |
| 86 | **serialize** | ① 序列化 to convert data into a transmittable format ② 连载 to publish in installments ③ 顺序化 to arrange in a series | ① JSON **serializes** objects into a string representation for network transfer. ② The response is **serialized** as protobuf for efficiency. ③ The memoir was **serialized** in the New Yorker before publication. |
| 87 | **payload** | ① 有效载荷 the cargo carried by a vehicle ② 数据负载 the actual data in a network transmission ③ 载荷 the useful content as opposed to overhead | ① The API response **payload** was 2MB — far too large for mobile clients. ② Headers are metadata; the body contains the **payload**. ③ The rocket's **payload** was a communications satellite weighing 4 tons. |
| 88 | **explicit** | ① 明确的 stated clearly and in detail ② 显式的 directly expressed, not implied ③ 不含糊的 leaving no room for confusion | ① Be **explicit** about your assumptions in the RFC — what's obvious to you may not be obvious to readers. ② An **explicit** dependency is better than a hidden one. ③ The API contract is **explicit**: the response will always include these fields. |
| 89 | **implicit** | ① 隐含的 suggested but not directly expressed ② 不言明的 implied though not stated ③ 隐式的 inherent in the nature of something | ① There's an **implicit** assumption that all services speak JSON — is that documented? ② **Implicit** dependencies create surprising failures when things change. ③ The trust between the two teams was **implicit** — it didn't need to be stated. |
| 90 | **comprehensive** | ① 全面的 including all elements ② 综合的 covering completely ③ 详尽的 thorough and inclusive | ① The onboarding guide is **comprehensive** — it covers everything from IDE setup to production access. ② A **comprehensive** test suite catches regressions before they're deployed. ③ The postmortem was **comprehensive** without being overwhelming — every detail served a purpose. |
| 91 | **specification** | ① 规范 an act of describing something precisely ② 技术规格 a detailed description of design and materials ③ 规约 a standard for how something should work | ① The OpenAPI **specification** defines the API contract in a machine-readable format. ② RFCs should be **specifications**, not vague suggestions. ③ Write the **specification** before the implementation — it's cheaper to change prose than code. |
| 92 | **inline** | ① 行内的 arranged within a line of text ② 内联的 placed within the flow of text ③ 嵌入的 incorporated directly rather than by reference | ① The code comment uses **inline** annotations to explain each parameter. ② **Inline** styles in HTML are discouraged — use CSS classes instead. ③ We do **inline** code reviews directly in the GitHub PR interface. |
| 93 | **toggle** | ① 切换 to switch between two states ② 功能开关 a control that switches a feature on or off ③ 切换键 a key or command that alternates between states | ① The feature is behind a **toggle** — you can turn it on in Settings. ② Press `Ctrl+T` to **toggle** between light and dark mode. ③ We use feature **toggles** to decouple deployment from release. |
| 94 | **fallback** | ① 后退策略 an alternative plan to use if things go wrong ② 备选方案 a backup option ③ 回落 to revert to a previous state | ① If the primary database is unreachable, the system has a **fallback** to the read replica. ② The **fallback** strategy for the migration: if anything fails, rollback is one click. ③ Always have a **fallback** — never put yourself in a position with no exit. |
| 95 | **invariant** | ① 不变量 a property that remains unchanged by a transformation ② 恒定性 a condition that always holds true ③ 不变式 a logical assertion that must be maintained | ① The database **invariant** is that every user has exactly one email address. ② An **invariant** of the system is that all writes are idempotent. ③ If an **invariant** is violated, the system is in an inconsistent state and must be repaired. |
| 96 | **canonical** | ① 规范的 accepted as being accurate and authoritative ② 标准的 conforming to a general rule ③ 公认的 recognized as the standard form | ① The git repository is the **canonical** source of truth for all configuration. ② Always refer to the **canonical** documentation, not a third-party blog post. ③ There should be exactly one **canonical** way to do any common task in the codebase. |
| 97 | **strict** | ① 严格的 demanding that rules are obeyed ② 严密的 precisely limited and closely defined ③ 严谨的 rigorous and exacting | ① TypeScript's **strict** mode catches more potential errors at compile time. ② A **strict** schema validation rejects any unknown fields. ③ The API has **strict** rate limits — exceeding them gets you a 429. |
| 98 | **lenient** | ① 宽容的 more permissive than strict ② 宽松的 not strict ③ 温和的 merciful and tolerant | ① The JSON parser is **lenient** — it accepts trailing commas that the spec disallows. ② A **lenient** schema validation accepts extra fields and silently drops them. ③ Be **lenient** in what you accept, strict in what you produce. |
| 99 | **heuristic** | ① 启发式的 enabling discovery through trial and error ② 经验法则 a practical method not guaranteed to be perfect ③ 试探法 a rule of thumb for decision-making | ① The load balancer uses a **heuristic** to detect unhealthy instances. ② The monitoring system applies **heuristics** to distinguish real incidents from noise. ③ A good code review **heuristic**: if you can't understand it in 30 seconds, it needs refactoring. |
| 100 | **deterministic** | ① 确定性的 producing the same output given the same input ② 必然的 causally determined by preceding events ③ 可预测的 predictable and non-random | ① A **deterministic** build produces identical artifacts from the same source code. ② Hash functions are **deterministic** — the same input always produces the same output. ③ Most bugs are **deterministic** even if they appear random — you just haven't found the trigger yet. |

