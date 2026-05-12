# Week 01: 高级句子拆解 (Advanced Sentence Dissection) + 300 B2-C1 词汇

> 目标：将过去五个月学到的所有语法知识——句子结构、时态、被动语态、三大从句、虚拟语气、非限定动词、倒装、强调、冠词与介词——融合为一个系统的"句子拆解工具箱"。学会面对任何一个复杂英语长句时，能够在 2 分钟内定位主干、分层修饰、理解句法逻辑。同时积累 300 个远程工作与分布式团队、技术写作与文档、工程领导与管理、全球科技产业、开发者体验与工具、职业成长与专业发展领域的高阶词汇。

---

## 1. The Systematic Approach to Sentence Dissection（系统拆解法）

### 1.1 核心原则

面对一个复杂长句，不要从左到右逐词阅读。按以下四步走：

**Step 1: Find the Main Clause（找主句）**
- 忽略所有逗号、破折号、括号中的内容
- 找到主句的主语和谓语
- 用笔圈出主谓，或心中默念 "Who does what?"

**Step 2: Identify Subordination（识别从属结构）**
- that/which/who/when/where/why/how 引导的定语从句和名词从句
- because/although/if/unless/while/whereas 引导的状语从句
- 不定式短语、分词短语、介词短语
- 用括号将每个从属结构括起来

**Step 3: Trace the Modification Chain（追踪修饰链）**
- 每个修饰成分修饰前面的哪个词？
- 介词短语 → 修饰哪个名词？
- 定语从句 → 修饰哪个先行词？
- 分词短语 → 逻辑主语是谁？

**Step 4: Reconstruct the Logic（重建逻辑关系）**
- 把骨架（主句）和修饰（从属结构）拼回去
- 理解因果关系、时间顺序、对比关系
- 用自己的话复述句子含义

---

### 1.2 实战技术

#### 技术 1：括号法（Bracketing）

将长句中的每一个从属结构用括号括起来，暴露句子骨架。

示例：
> The engineer (who had initially proposed the microservice migration) eventually conceded (that the monolith, (which everyone had dismissed as "legacy debt,") was, (for all practical purposes,) more reliable than the distributed system (that replaced it).)

去掉括号内容后，骨架是：
> The engineer eventually conceded [that] the monolith was more reliable.

#### 技术 2：箭头法（Arrow Tracing）

在每个修饰成分和它所修饰的词之间画箭头。

```
The architecture → that the team inherited → from the previous CTO
     ↓
was built → on an assumption → about database latency
     ↓
that turned out → to be wrong → by an order of magnitude.
```

#### 技术 3：颜色标注法（Color Coding）

- **蓝色** = 主句主谓宾
- **红色** = 从属连词和关系词
- **绿色** = 介词短语
- **黄色** = 分词短语和不定式短语

在阅读时用颜色区分句子结构，视觉化语法层次。

---

### 1.3 常见困难结构及破解策略

| 困难结构 | 破解策略 |
|----------|----------|
| **长插入语** | 忽略两个破折号/逗号之间的内容，先看外面 |
| **嵌套定语从句** | 从最外层的 that/which 开始，一层一层往里剥 |
| **长主语** | 找 is/was/are/were — 系动词前所有内容是主语 |
| **倒装句** | 识别触发词（Never, Not only, Only, So, Had），还原成正常语序 |
| **省略** | 识别省略了什么（常见：关系代词、if、比较结构中的重复） |
| **长介词链** | 从最后一个名词开始反向追踪：A of B of C = C 的 B 的 A |
| **多重否定** | 每次两个否定取消（not uncommon = common），逐个消除 |
| **分隔结构** | 主语和谓语被长定语分隔 → 忽略定语，先找谓语 |

---

## 2. Complex Sentence Dissections（复杂句拆解）

以下 6 个句子来自真实的技术写作、学术论文和工程文档，代表了你在实际工作中会遇到的复杂程度。每个句子标注了 Months 1-5 涉及的语法点。

---

### 2.1 Sentence 1 — 来自 Google SRE Book 风格

> **Had the engineers who were responsible for maintaining the legacy authentication system—a system that, by the time of the incident, had been in continuous operation for nearly a decade without a single major failure—been given the opportunity to review the proposed migration plan before it was approved by the architecture committee, the cascading series of failures that ultimately brought down the entire payment processing pipeline for the better part of a business day would almost certainly have been prevented.**

#### Step 1: Find the Main Clause

句首 Had... 触发倒装 → 还原正常语序：

> If the engineers had been given the opportunity to review the proposed migration plan, the cascading series of failures would have been prevented.

**主句骨架**：
- 条件从句：the engineers had been given the opportunity to review the plan
- 主句：the cascading series of failures would have been prevented

#### Step 2: Identify Subordination

用括号标出所有从属结构：

```
[Had the engineers
  (who were responsible for maintaining the legacy authentication system
    —a system
      (that, by the time of the incident,
       had been in continuous operation for nearly a decade
       without a single major failure)—)
  been given the opportunity
  (to review the proposed migration plan
    before it was approved by the architecture committee),]
the cascading series of failures
  (that ultimately brought down the entire payment processing pipeline
    for the better part of a business day)
would almost certainly have been prevented.
```

**从属结构清单**：
1. who were responsible for... — 定语从句修饰 engineers
2. —a system that... — 同位语 + 定语从句修饰 legacy auth system
3. to review the proposed migration plan — 不定式修饰 opportunity
4. before it was approved by... — 时间状语从句
5. that ultimately brought down... — 定语从句修饰 the cascading series of failures

#### Step 3: Trace the Modification Chain

```
the engineers
  ← who were responsible for maintaining [the legacy authentication system]
       ← —a system
            ← that had been in continuous operation
                 ← for nearly a decade (时间段)
                 ← without a single major failure (伴随)
                 ← by the time of the incident (时间点)

the opportunity
  ← to review [the proposed migration plan]
       ← before it was approved
            ← by the architecture committee

the cascading series of failures
  ← that ultimately brought down [the entire payment processing pipeline]
       ← for the better part of a business day (时间段)
```

#### Step 4: Reconstruct the Logic

条件：工程师有权审查迁移计划 → 结果：级联故障不会发生
为什么？因为这些工程师维护了一个十年无故障运行的系统 → 他们对迁移中的风险有独特的洞察力
隐含逻辑：经验最丰富的人没有被咨询 → 可预防的故障发生了

#### 语法标注总览

| Month | Grammar | Location |
|-------|---------|----------|
| M1 | Sentence patterns | 主句: S + would + have been + prevented (被动) |
| M2 | Passive voice, perfect tenses | had been in operation (过去完成); would have been prevented (被动完成虚拟) |
| M3 | Relative clauses | who were responsible...; that had been...; that ultimately brought down... |
| M4 | Conditionals, subjunctive | Had the engineers been given... = Type 3 conditional (与过去事实相反) |
| M5 | Inversion, articles/prepositions | Had...been given (条件虚拟倒装); for a decade; by the time; without failure; for the better part of |

---

### 2.2 Sentence 2 — 来自 Distributed Systems Paper 风格

> **What the postmortem ultimately revealed—and what every engineer who had worked on the system intuitively knew but could not articulate until the data confirmed it—was not that the consensus algorithm itself was flawed, but rather that the assumptions upon which the algorithm's correctness proof rested, assumptions about the bounded nature of message delays and the relative ordering of node failures, assumptions that had been explicitly documented as preconditions in the original paper, had been violated by a subtle but systematic configuration drift that had occurred over the course of eighteen months of incremental infrastructure changes, none of which, in isolation, had triggered an alert or raised a concern during the weekly change review.**

#### Step 1: Find the Main Clause

忽略破折号中的插入内容，找主干：

> What the postmortem revealed was not that the algorithm itself was flawed, but rather that the assumptions had been violated.

骨架：
- 主语：What the postmortem revealed (What 伪分裂句)
- 系动词：was
- 表语：not that X, but rather that Y

#### Step 2: Identify Subordination

```
[What the postmortem ultimately revealed]
  —and [what every engineer
         (who had worked on the system)
         intuitively knew
         but could not articulate
         [until the data confirmed it]]—
was
  not [that the consensus algorithm itself was flawed],
  but rather [that the assumptions
              (upon which the algorithm's correctness proof rested,)
              —assumptions
                (about the bounded nature of message delays
                 and the relative ordering of node failures,)
              —assumptions
                (that had been explicitly documented as preconditions
                 in the original paper,)—
              had been violated
              [by a subtle but systematic configuration drift
               (that had occurred
                over the course of eighteen months
                of incremental infrastructure changes,
                none of which, in isolation,
                had triggered an alert
                or raised a concern
                during the weekly change review.)]]
```

**从属结构清单**：
1. What the postmortem revealed — 主语从句
2. what every engineer knew — 第二个主语从句 (插入)
3. who had worked on the system — 定语从句
4. until the data confirmed it — 时间状语从句
5. that the consensus algorithm was flawed — 表语从句 1
6. that the assumptions had been violated — 表语从句 2
7. upon which the proof rested — 定语从句 (介词 + which)
8. about the bounded nature... — 介词短语修饰 assumptions
9. that had been documented as preconditions — 定语从句修饰 assumptions
10. that had occurred over... — 定语从句修饰 configuration drift
11. none of which had triggered — 定语从句修饰 changes

#### Step 3: Trace the Modification Chain

```
What the postmortem revealed...was not [X] but rather [Y]

Y = the assumptions
      ← upon which the algorithm's correctness proof rested (定语)
      ← assumptions about the bounded nature... (同位语解释)
      ← assumptions that had been documented... (同位语解释)
      ← had been violated (谓语)
           ← by a subtle but systematic configuration drift (方式)
                ← that had occurred over 18 months (定语)
                     ← none of which had triggered an alert (定语修饰 changes)
```

#### Step 4: Reconstruct the Logic

根因：不是共识算法本身有问题，而是算法成立的前提条件被违反了。
前提条件是什么？消息延迟有界 + 节点故障相对有序。
怎么被违反的？18 个月的配置漂移，每一次变更单独看都没问题，合在一起就出事了。
教训：系统性的配置审计比算法正确性证明更重要。

#### 语法标注总览

| Month | Grammar | Location |
|-------|---------|----------|
| M1 | 句子的基本结构 | 主系表 |
| M2 | Perfect tenses, passive voice | had worked; had been documented; had been violated; had occurred |
| M3 | Noun clauses (What), relative clauses | What...revealed; that the algorithm was flawed; upon which...rested; that had occurred |
| M4 |  | (no subjunctive in this sentence) |
| M5 | Emphasis (What pseudo-cleft), prepositions | What...was; upon which; over the course of; during; about; by; in isolation |

---

### 2.3 Sentence 3 — 来自 Technical Blog Post 风格

> **Only after spending the better part of a weekend tracing a production outage through seventeen different microservices, three message queues, two databases, and a load balancer that, as it turned out, had been silently dropping packets for six months because of a firmware bug that the vendor had documented in a release note that nobody on the team had read, did the engineers finally understand what the old guard had meant when they said that "distributed systems are an exercise in partial failure"—and it was precisely this understanding, hard-won and painfully acquired, that led to the creation of the chaos engineering program that, within a year, would become the gold standard for reliability practices across the entire organization.**

#### Step 1: Find the Main Clause

Only after... 触发倒装。

正常语序：
> The engineers finally understood [what the old guard had meant] — and it was this understanding that led to the creation of the chaos engineering program.

主句骨架：
- 第一分句：Only after X did Y understand Z
- 第二分句：it was A that led to B（强调句）

#### Step 2: Identify Subordination

```
[Only after spending the better part of a weekend
  tracing a production outage
  through seventeen different microservices,
  three message queues,
  two databases,
  and a load balancer
    (that, as it turned out,
     had been silently dropping packets for six months
     [because of a firmware bug
      (that the vendor had documented
       in a release note
       (that nobody on the team had read))])]
did the engineers finally understand
  [what the old guard had meant
   [when they said
    [that "distributed systems are an exercise in partial failure"]]]
—and
  it was precisely this understanding,
    hard-won and painfully acquired,
    that led to the creation of the chaos engineering program
      (that, within a year,
       would become the gold standard
       for reliability practices
       across the entire organization).
```

**从属结构清单**：
1. Only after spending... + tracing... — 介词 + 动名词结构
2. that had been dropping packets — 第一层定语从句 (修饰 load balancer)
3. because of a firmware bug — 原因状语
4. that the vendor had documented — 第二层定语 (修饰 bug)
5. that nobody on the team had read — 第三层定语 (修饰 release note)
6. what the old guard had meant — 宾语从句 (understand 的宾语)
7. when they said that... — 时间状语从句
8. that "distributed systems..." — 宾语从句 (said 的宾语)
9. it was this understanding that led — 强调句型
10. that would become the gold standard — 定语从句

#### Step 3: Trace the Modification Chain — 三层嵌套定语

```
a load balancer
  ← that had been silently dropping packets (第一层: LB 做了什么)
       ← because of a firmware bug (原因)
            ← that the vendor had documented (第二层: bug 的性质)
                 ← in a release note (地点)
                      ← that nobody on the team had read (第三层: note 的命运)
```

这就是典型的"嵌套定语从句链"：LB → bug → release note。阅读时从外向内逐层剥离。

#### Step 4: Reconstruct the Logic

工程师花了一个周末追踪一个生产事故 → 发现一个 LB 因固件 bug 掉包了六个月 → 这个 bug 供应商文档里有，但没人读过 → 最终理解了老员工说的"分布式系统是部分故障的练习" → 正是这个痛苦的理解导致了混沌工程项目的创立。

#### 语法标注总览

| Month | Grammar | Location |
|-------|---------|----------|
| M1 | Basic patterns | S + V + O (understood what...) |
| M2 | Perfect tenses, passive voice | had been dropping; had documented; had read; had meant; was precisely...that |
| M3 | Three clause types | that...read (relative); what...meant (noun); when...said (adverbial) |
| M4 | Non-finite verbs | spending, tracing, hard-won, acquired |
| M5 | Inversion (Only after), Emphasis (it was...that), Prepositions | Only after...did; it was precisely...that; through; because of; across |

---

### 2.4 Sentence 4 — 来自 Academic Paper Abstract 风格

> **Not only does the prevailing approach to microservice decomposition—an approach that, for all its superficial elegance, reduces the problem of system modularity to a set of heuristics about code size and team ownership rather than to a principled analysis of runtime coupling and data co-locality—fail to account for the emergent behaviors that arise when independently deployed services interact under conditions of partial failure, but the very heuristics that were meant to simplify the decomposition problem have, in practice, introduced a new class of failure modes that are both harder to detect and more expensive to remediate than the monolithic fragility they were designed to replace.**

#### Step 1: Find the Main Clause

Not only... → 倒装结构。

正常语序：
> The prevailing approach fails to account for emergent behaviors, but the very heuristics have introduced a new class of failure modes.

骨架：
- 主语 1：the prevailing approach
- 谓语 1：fails to account for...
- 主语 2：the very heuristics
- 谓语 2：have introduced...

#### Step 2: Identify Subordination

```
[Not only does the prevailing approach to microservice decomposition
  —an approach
    (that, for all its superficial elegance,
     reduces the problem of system modularity
     to a set of heuristics about code size and team ownership
     rather than to a principled analysis of runtime coupling and data co-locality)—
  fail to account for the emergent behaviors
  (that arise
   [when independently deployed services interact
    under conditions of partial failure])],
but the very heuristics
  (that were meant to simplify the decomposition problem)
have, in practice, introduced a new class of failure modes
  (that are both harder to detect
   and more expensive to remediate
   than the monolithic fragility
   (they were designed to replace)).
```

#### Step 3: Trace the Key Contrast

```
the prevailing approach → fails to account for → emergent behaviors
                          (when services interact under partial failure)

BUT

the very heuristics → have introduced → new failure modes
                      (harder to detect + more expensive to fix)
                      (than the monolith they replaced)
```

**讽刺结构**：这个方法论（微服务拆分）不仅没有解决原来的问题，反而引入了更难检测、代价更高的问题。而这些问题比它要替换的单体架构更严重。

#### 语法标注总览

| Month | Grammar | Location |
|-------|---------|----------|
| M1 | S + V + O | approach fails to account for... |
| M2 | Perfect tenses | have introduced |
| M3 | Noun clauses, relative clauses | that arise when...; that were meant to...; that are both harder... |
| M4 | Conditionals/subjunctive, non-finite | reduce to (不定式); to replace (不定式) |
| M5 | Inversion (Not only), Emphasis (the very), Articles/Prepositions | Not only does...; the very heuristics; under conditions of; in practice; rather than |

---

### 2.5 Sentence 5 — 来自 Engineering Blog 风格

> **It was not until the third consecutive weekend of on-call escalations, during which the same pattern of cascading timeouts had played out across four different services in three different ways, that the team finally acknowledged what the principal architect had been saying for nearly a year: that the asynchronous messaging layer, which had been introduced to decouple the services and which had, in every architectural review, been praised as the very embodiment of loose coupling, was in fact a synchronous dependency in disguise—a dependency that, under the specific failure modes that materialized during peak traffic, transformed what should have been a graceful degradation into a hard failure that took down the entire system.**

#### Step 1: Find the Main Clause

It was not until X that Y → 强调句型 + not until 结构。

骨架：
> It was not until [the third consecutive weekend of on-call escalations] that the team finally acknowledged [what the architect had been saying].

#### Step 2: Identify Subordination

```
[It was not until the third consecutive weekend of on-call escalations,
  (during which the same pattern of cascading timeouts
   had played out
   across four different services
   in three different ways),]
that the team finally acknowledged
  [what the principal architect had been saying
   for nearly a year]:
    that the asynchronous messaging layer,
      (which had been introduced to decouple the services
       and which had, in every architectural review,
       been praised as the very embodiment of loose coupling),
      was in fact a synchronous dependency in disguise
      —a dependency
        (that, under the specific failure modes
         (that materialized during peak traffic),
         transformed
           [what should have been a graceful degradation]
           into a hard failure
         (that took down the entire system)).
```

#### Step 3: Trace the Irony Chain

```
asynchronous messaging layer  →  introduced to decouple
                              →  praised as embodiment of loose coupling
                              →  WAS ACTUALLY a synchronous dependency
                                     →  under peak traffic
                                     →  graceful degradation → hard failure
                                     →  took down the entire system
```

**修辞效果**：通过对比"被认为是的东西"和"实际上是的东西"，创造强烈的讽刺效果。

#### Step 4: Reconstruct the Logic

发生了三次同样的 on-call 升级 → 团队终于承认架构师的警告是对的 → 那个被所有人称赞为"松耦合典范"的异步消息层 → 实际上是一个伪装的同步依赖 → 在峰值流量下，它把应该的优雅降级变成了整个系统的硬故障。

#### 语法标注总览

| Month | Grammar | Location |
|-------|---------|----------|
| M1 | 句子的基本结构 | the team acknowledged what... |
| M2 | Passive voice, perfect tenses | had been introduced; had been praised; had been saying |
| M3 | Noun clauses (what), relative clauses | what the architect had been saying; which had been introduced; that materialized; that took down |
| M4 | Subjunctive (should have been) | what should have been a graceful degradation |
| M5 | Emphasis (It was not until...that), Articles/Prepositions | It was not until that; the very embodiment; across; during; under |

---

### 2.6 Sentence 6 — 来自 Postmortem 风格

> **Were one to ask any of the engineers who were in the war room that night what single factor, more than any other, transformed what should have been a routine service degradation—the kind that the automated remediation systems were designed to handle without human intervention—into a seven-hour outage that required the manual intervention of three separate teams across two time zones and ultimately cost the company what the CFO later described as "an uncomfortable but not existential amount of revenue," the answer, delivered without hesitation and with the kind of clarity that only comes from having spent six months analyzing the incident from every conceivable angle, would be this: the most sophisticated system in the world cannot compensate for an organizational structure that discourages engineers from escalating when something feels wrong, and it is precisely this cultural failure—not any technical failure—that the postmortem identified as the root cause.**

#### Step 1: Find the Main Clause

Were one to ask...the answer would be...

条件虚拟倒装 + 超长宾语结构。

还原正常语序：
> If one were to ask any of the engineers what single factor transformed X into Y, the answer would be this: ...

骨架：
- 条件从句：Were one to ask [engineers] [question]
- 主句：the answer would be [answer]

#### Step 2: Identify Subordination

```
[Were one to ask any of the engineers
  (who were in the war room that night)
  [what single factor, more than any other,
   transformed
     [what should have been a routine service degradation
       —the kind
         (that the automated remediation systems were designed to handle
          without human intervention)—]
     into a seven-hour outage
       (that required the manual intervention of three separate teams
        across two time zones
        and ultimately cost the company
          [what the CFO later described
           as "an uncomfortable but not existential amount of revenue,")]]]
the answer,
  delivered without hesitation
  and with the kind of clarity
    (that only comes from having spent six months
     analyzing the incident
     from every conceivable angle),
would be this:
  the most sophisticated system in the world cannot compensate
  for an organizational structure
    (that discourages engineers from escalating
     [when something feels wrong]),
  and it is precisely this cultural failure
    —not any technical failure—
    that the postmortem identified as the root cause.
```

#### Step 3: Trace the Core Argument

```
Question: What transformed a routine event → into a 7-hour outage?

Answer: NOT a technical failure.
        An organizational structure that discouraged escalation.
        = a CULTURAL failure.

Emphasis: it was precisely this cultural failure that was the root cause.
```

#### Syntax Highlight: 嵌套宾语从句

```
ask [any of the engineers] [what single factor transformed X into Y]
                              ↑
                              宾语从句（what = the thing that）
    其中 X = what should have been a routine degradation
            ↑ 嵌套的 what 从句
    其中 Y = a seven-hour outage that required...and cost...
                                           ↑ 嵌套的定语从句
```

#### 语法标注总览

| Month | Grammar | Location |
|-------|---------|----------|
| M1 | Basic patterns | the answer would be this |
| M2 | Passive voice, perfect tenses | were designed; having spent |
| M3 | Noun clauses, relative clauses, adverbial clauses | what single factor; who were in the war room; that discourages; when something feels wrong |
| M4 | Subjunctive, non-finite verbs | Were one to ask; should have been; delivered; analyzing |
| M5 | Inversion, Emphasis, Articles/Prepositions | Were one to ask (条件倒装); it is precisely this...that (强调); across two time zones; without; from |

---

## 3. Vocabulary — 300 B2-C1 词汇

### Group 1/6: Remote Work & Distributed Teams（远程工作与分布式团队）

| # | Word | Pronunciation | Meanings | Example Sentences |
|---|------|--------------|----------|-------------------|
| 1 | **asynchronous** | /eɪˈsɪŋkrənəs/ | ① 异步的② 非同步的③ 不同时的 | ① **Asynchronous** communication is the backbone of remote work. ② The team uses **asynchronous** standups via Slack. ③ **Asynchronous** code review respects everyone's time zone. |
| 2 | **distributed** | /dɪˈstrɪbjuːtɪd/ | ① 分布式的② 分散的③ 分布的 | ① **Distributed** teams need deliberate communication practices. ② The database is **distributed** across three regions. ③ Trust is harder to build in **distributed** environments—but not impossible. |
| 3 | **colocate** | /kəʊˈləʊkeɪt/ | ① v.同地协作/共处一地② 并置③ 放在一起 | ① The team was **colocated** before going remote in 2020. ② Don't **colocate** all critical services in the same availability zone. ③ Being **colocated** doesn't guarantee good communication. |
| 4 | **time zone** | /taɪm zəʊn/ | ① 时区② 时差③ 时间区域 | ① Coordinating across eight **time zones** is the hardest part of distributed work. ② **Time zone** overlap is precious—use it for synchronous discussion. ③ Async culture reduces **time zone** friction. |
| 5 | **overlap** | /ˈəʊvəlæp/ | ① n/v.重叠/交叉② 重合③ 部分相同 | ① We have a four-hour **overlap** between the US and EU teams. ② The two services' responsibilities **overlap**—that's the source of the confusion. ③ Schedule meetings during the **overlap** window. |
| 6 | **onboarding** | /ˈɒnbɔːdɪŋ/ | ① 入职/上手培训② 融入过程③ 新员工引导 | ① Remote **onboarding** requires more structure than in-person **onboarding**. ② The **onboarding** process for the codebase takes about two weeks. ③ Good documentation is the best **onboarding** tool. |
| 7 | **standup** | /ˈstændʌp/ | ① 站会/每日例会② 每日同步③ 简明汇报 | ① Async **standups** replace synchronous ones in distributed teams. ② The daily **standup** should take no more than 15 minutes. ③ Long **standups** are a sign of process debt. |
| 8 | **scrum** | /skrʌm/ | ① 敏捷开发框架② 并列争球③ 密集协作 | ① **Scrum** ceremonies need adaptation for remote teams. ② The **scrum** master facilitates but doesn't manage. ③ **Scrum** without engineering practices is theater. |
| 9 | **sprint** | /sprɪnt/ | ① n.冲刺/短周期② v.短跑③ n.迭代周期 | ① The two-week **sprint** cadence is the team's heartbeat. ② We **sprinted** to fix the P0 bug before the weekend. ③ **Sprint** planning determines the next two weeks of work. |
| 10 | **retrospective** | /ˌretrəˈspektɪv/ | ① n.回顾/复盘② adj.回顾的③ 反思 | ① The **retrospective** surfaced three action items for improving async communication. ② A **retrospective** without action items is just complaining. ③ Remote **retrospectives** benefit from structured facilitation. |
| 11 | **facilitate** | /fəˈsɪlɪteɪt/ | ① 促进/推动② 使容易③ 帮助 | ① The meeting was **facilitated** by the engineering manager. ② Good tooling **facilitates** remote collaboration. ③ The RFC process **facilitates** architectural decision-making. |
| 12 | **serendipity** | /ˌserənˈdɪpɪti/ | ① 意外发现/机缘巧合② 偶然的好运③ 无心插柳 | ① Remote work reduces **serendipity**—the chance hallway conversations that spark ideas. ② We need to engineer **serendipity** through virtual coffee chats. ③ The bug was discovered by pure **serendipity**. |
| 13 | **watercooler** | /ˈwɔːtəkuːlə/ | ① 饮水机（比喻非正式交流）② 冷水机③ 闲聊场所 | ① **Watercooler** conversations don't happen in remote teams—you need to create them. ② The Slack #random channel is the virtual **watercooler**. ③ Some of the best ideas come from **watercooler** talk. |
| 14 | **isolation** | /ˌaɪsəˈleɪʃən/ | ① 隔离/孤立② 分离③ 孤独 | ① Remote work can lead to feelings of **isolation**. ② The microservice runs in **isolation** from other services. ③ **Isolation** is the biggest mental health challenge of remote work. |
| 15 | **burnout** | /ˈbɜːnaʊt/ | ① 倦怠/过度疲劳② 烧尽③ 筋疲力竭 | ① Remote work blurs boundaries, increasing **burnout** risk. ② On-call **burnout** is a systemic failure, not an individual weakness. ③ The team experienced **burnout** after six months of crunch. |
| 16 | **autonomy** | /ɔːˈtɒnəmi/ | ① 自治/自主权② 独立③ 自由 | ① Remote work requires trust and **autonomy**—not micromanagement. ② Each squad has **autonomy** over its tech stack. ③ **Autonomy** without alignment creates chaos. |
| 17 | **accountability** | /əˌkaʊntəˈbɪlɪti/ | ① 问责制/责任制② 可说明性③ 负责 | ① Remote work shifts emphasis from presence to **accountability**. ② Clear ownership establishes **accountability**. ③ **Accountability** without blame is the foundation of psychological safety. |
| 18 | **transparency** | /trænsˈpærənsi/ | ① 透明/公开② 透明度③ 清晰 | ① Default to **transparency** in remote communication—over-share rather than under-share. ② Decision **transparency** builds trust in distributed teams. ③ The RFC process brings **transparency** to architectural choices. |
| 19 | **synchronous** | /ˈsɪŋkrənəs/ | ① 同步的② 同时的③ 即时的 | ① Too many **synchronous** meetings exclude team members in distant time zones. ② Reserve **synchronous** time for decisions, not status updates. ③ The API call is **synchronous**—it blocks until the response arrives. |
| 20 | **hybrid** | /ˈhaɪbrɪd/ | ① adj.混合的/结合的② n.混合物③ 杂合的 | ① The **hybrid** model—some in office, some remote—creates two tiers of employees. ② The architecture is a **hybrid** of monolith and microservices. ③ **Hybrid** meetings are the hardest to get right. |
| 21 | **engagement** | /ɪnˈɡeɪdʒmənt/ | ① 参与/投入② 约定/订婚③ 交战 | ① Remote work can reduce **engagement** if people feel disconnected. ② The all-hands boosted team **engagement**. ③ Employee **engagement** surveys showed a 15% dip after the reorg. |
| 22 | **disengagement** | /ˌdɪsɪnˈɡeɪdʒmənt/ | ① 脱离/疏离② 解约③ 退出 | ① Quiet quitting is a form of **disengagement**. ② **Disengagement** is often a response to lack of autonomy or purpose. ③ The team's **disengagement** was visible in the declining code review participation. |
| 23 | **screen fatigue** | /skriːn fəˈtiːɡ/ | ① 屏幕疲劳/视频会议疲劳② 视觉疲劳③ 视疲劳 | ① **Screen fatigue** is a real occupational hazard of remote work. ② The team introduced no-meeting Wednesdays to combat **screen fatigue**. ③ **Screen fatigue** reduces the quality of code reviews in the afternoon. |
| 24 | **deep work** | /diːp wɜːk/ | ① 深度工作/专注工作② 沉浸式工作③ 深度思考 | ① Remote work can enable more **deep work**—fewer interruptions. ② Protect two-hour blocks for **deep work** on your calendar. ③ **Deep work** is where the best code gets written. |
| 25 | **context switching** | /ˈkɒntekst swɪtʃɪŋ/ | ① 上下文切换/任务切换② 环境切换③ 注意力转移 | ① **Context switching** is the productivity killer of remote work. ② Each notification causes a **context switch** that costs 15-20 minutes of focus. ③ Async communication reduces forced **context switching**. |
| 26 | **all-hands** | /ɔːl hændz/ | ① 全员大会② 全体会议③ 总动员 | ① The CEO gives a monthly **all-hands** update. ② Remote **all-hands** are recorded for those who can't attend live. ③ The **all-hands** is not a status meeting—it's for vision and alignment. |
| 27 | **skip-level** | /skɪp ˈlevəl/ | ① 跳级（与上级的上级沟通）② 跨级③ 越级 | ① **Skip-level** one-on-ones are essential for transparency in flat orgs. ② The engineer raised the concern in a **skip-level** meeting. ③ **Skip-level** feedback helps managers improve. |
| 28 | **pulse survey** | /pʌls ˈsɜːveɪ/ | ① 脉搏调查/短问卷② 快速调查③ 状态检测 | ① The weekly **pulse survey** measures team morale. ② **Pulse surveys** catch issues before they become crises. ③ The **pulse survey** showed that on-call stress was the top concern. |
| 29 | **psychological safety** | /ˌsaɪkəˈlɒdʒɪkəl ˈseɪfti/ | ① 心理安全② 心理安全感③ 放心表达的环境 | ① **Psychological safety** means you can admit mistakes without fear. ② Remote teams need to work harder at **psychological safety**—cues are easy to miss. ③ Blameless postmortems build **psychological safety**. |
| 30 | **inclusion** | /ɪnˈkluːʒən/ | ① 包容/包含② 融入③ 融合 | ① **Inclusion** in remote meetings means actively soliciting input from quieter participants. ② Diversity is who's in the room; **inclusion** is who feels safe to speak. ③ The async-first culture improved **inclusion** across time zones. |
| 31 | **deliberate** | /dɪˈlɪbərət/ | ① adj.有意的/审慎的② v.仔细考虑③ 从容的 | ① Remote culture must be **deliberate**—it won't happen by accident. ② The team **deliberated** for a week before choosing the framework. ③ A **deliberate** approach to documentation pays off within months. |
| 32 | **equitable** | /ˈekwɪtəbəl/ | ① 公平的/公正的② 平等的③ 合理的 | ① On-call rotations must be **equitable**—everyone takes the weekend shift. ② Meeting times should be **equitable** across time zones. ③ The promotion process was overhauled to be more **equitable**. |
| 33 | **friction** | /ˈfrɪkʃən/ | ① 摩擦/阻力② 矛盾③ 摩擦力 | ① Every additional tool adds **friction** to the remote workflow. ② The **friction** between engineering and product was addressed in the retro. ③ Reducing **friction** in the CI pipeline is an ongoing effort. |
| 34 | **heads-up** | /hedz ʌp/ | ① n.提前通知/提醒② 预警③ 告知 | ① Give the team a **heads-up** before making a breaking change. ② A quick **heads-up** in Slack prevents misunderstandings. ③ The **heads-up** about the maintenance window came too late. |
| 35 | **handoff** | /ˈhændɒf/ | ① 移交/交接② 传递③ 转交 | ① The **handoff** between the US and APAC on-call teams happens at 9am UTC. ② Clear **handoff** notes prevent incidents from falling through cracks. ③ The **handoff** document summarized everything the outgoing engineer knew. |
| 36 | **camera fatigue** | /ˈkæmərə fəˈtiːɡ/ | ① 摄像头疲劳② 视频倦怠③ 露面疲惫 | ① **Camera fatigue** led the team to adopt camera-optional meetings. ② Being on camera all day is exhausting—**camera fatigue** is real. ③ **Camera fatigue** disproportionately affects neurodivergent engineers. |
| 37 | **flexible hours** | /ˈfleksɪbəl aʊəz/ | ① 弹性工作时间② 灵活工时③ 自由安排时间 | ① **Flexible hours** are the biggest perk of remote work. ② The team has **flexible hours** but a four-hour core overlap. ③ **Flexible hours** mean you can do deep work when you're most productive. |
| 38 | **offsite** | /ˈɒfsaɪt/ | ① n.异地团建/外部会议② adj.外部的③ n.外出活动 | ① The annual **offsite** brings the distributed team together. ② The **offsite** in Barcelona was the team's first in-person meeting. ③ **Offsites** are for bonding, not for presentations you could watch on Zoom. |
| 39 | **swag** | /swæɡ/ | ① 公司纪念品/赠品② 赃物③ 装饰品 | ① The remote team received **swag** boxes for the holiday party. ② Company **swag** is nice, but flexibility is a better perk. ③ The onboarding kit included a laptop, a hoodie, and other **swag**. |
| 40 | **async-first** | /eɪˈsɪŋk fɜːst/ | ① 异步优先的② 以异步沟通为主的③ 异步文化 | ① The company adopted an **async-first** communication policy. ② **Async-first** means: write it down before you schedule a meeting. ③ **Async-first** culture respects everyone's time and flow. |
| 41 | **scalability** | /ˌskeɪləˈbɪlɪti/ | ① 可扩展性② 规模化能力③ 伸缩性 | ① Remote processes must have **scalability**—what works for 10 won't work for 100. ② Technical **scalability** is easier than organizational **scalability**. ③ The onboarding process lost **scalability** after the team doubled. |
| 42 | **digital nomad** | /ˈdɪdʒɪtəl ˈnəʊmæd/ | ① 数字游民② 远程工作旅行者③ 数字流浪者 | ① The engineer became a **digital nomad**, working from a different country each month. ② **Digital nomad** visas are offered by more than 30 countries. ③ Being a **digital nomad** requires stellar async communication skills. |
| 43 | **co-working** | /kəʊ ˈwɜːkɪŋ/ | ① 共享办公② 联合工作③ 协同工作 | ① **Co-working** spaces provide the office experience for remote workers. ② The team rented a **co-working** space for the week-long sprint. ③ **Co-working** reduces isolation but doesn't solve the commute problem. |
| 44 | **work-life balance** | /wɜːk laɪf ˈbæləns/ | ① 工作与生活的平衡② 劳逸结合③ 工作生活均衡 | ① Remote work can improve **work-life balance**—or destroy it completely. ② **Work-life balance** is different for everyone; flexibility is the common need. ③ The on-call rotation was redesigned for better **work-life balance**. |
| 45 | **unplug** | /ʌnˈplʌɡ/ | ① v.脱离/断开② 拔掉插头③ 放松 | ① It's hard to **unplug** when your office is also your living room. ② The manager explicitly told the team to **unplug** during vacation. ③ **Unplugging** is a skill—practice it. |
| 46 | **on-call** | /ɒn kɔːl/ | ① 值班/待命② 随时响应③ 应急待命 | ① The **on-call** rotation is staffed by engineers across three time zones. ② **On-call** stress is the leading cause of burnout in SRE teams. ③ A healthy **on-call** culture requires psychological safety and proper compensation. |
| 47 | **incident response** | /ˈɪnsɪdənt rɪˈspɒns/ | ① 事故响应/事件响应② 应急处理③ 故障响应 | ① **Incident response** in distributed teams requires clear escalation paths. ② The **incident response** runbook is tested quarterly. ③ Async **incident response** means documenting every action in the incident channel. |
| 48 | **runbook** | /ˈrʌnbʊk/ | ① 操作手册/运维手册② 应急预案③ 操作指南 | ① Every alert should link to a **runbook** with step-by-step instructions. ② The **runbook** for the database failover hadn't been updated in two years. ③ A **runbook** is only as good as its last test. |
| 49 | **postmortem** | /pəʊstˈmɔːtəm/ | ① 事后分析/复盘② 验尸③ 事后检查 | ① The **postmortem** culture is blameless—focus on systems, not individuals. ② Every Sev-1 incident requires a **postmortem** within five business days. ③ The **postmortem** revealed that the same root cause had caused three previous incidents. |
| 50 | **follow-the-sun** | /ˈfɒləʊ ðə sʌn/ | ① 逐日运维/全天候接力② 全球接力③ 时区接力 | ① The **follow-the-sun** support model means no one works nights. ② **Follow-the-sun** on-call passes the pager from APAC to EU to US. ③ **Follow-the-sun** requires excellent handoff documentation. |

---

### Group 2/6: Technical Writing & Documentation（技术写作与文档）

| # | Word | Pronunciation | Meanings | Example Sentences |
|---|------|--------------|----------|-------------------|
| 1 | **terse** | /tɜːs/ | ① 简洁的/简练的② 精练的③ 简要的 | ① The best documentation is **terse**—every word earns its place. ② The commit message was **terse** to the point of being unhelpful: "fix." ③ A **terse** API doc is better than a verbose one that nobody reads. |
| 2 | **verbose** | /vɜːˈbəʊs/ | ① 冗长的/啰嗦的② 详细的③ 唠叨的 | ① **Verbose** error messages are useful for debugging but annoying for users. ② The README was too **verbose**—500 lines when 100 would do. ③ The **verbose** flag enables detailed logging. |
| 3 | **elucidate** | /ɪˈluːsɪdeɪt/ | ① 阐明/解释② 说明③ 澄清 | ① The diagram **elucidates** the data flow better than the text. ② Could you **elucidate** what "eventual consistency" means in this context? ③ The RFC **elucidated** the tradeoffs clearly. |
| 4 | **ambiguous** | /æmˈbɪɡjuəs/ | ① 模糊的/歧义的② 不明确的③ 含糊的 | ① API contracts must not be **ambiguous**—every field must have a clear type. ② The spec was deliberately **ambiguous** about the error handling. ③ An **ambiguous** requirement will produce an **ambiguous** implementation. |
| 5 | **unambiguous** | /ˌʌnæmˈbɪɡjuəs/ | ① 明确的/不含糊的② 清晰的③ 确定的 | ① Write **unambiguous** acceptance criteria. ② The error message should be **unambiguous**: "Connection timed out after 30s." ③ Good variable names are **unambiguous**—`userCount`, not `cnt`. |
| 6 | **conventions** | /kənˈvenʃənz/ | ① 惯例/规范② 约定③ 习俗 | ① Code **conventions** make the codebase navigable. ② The team's naming **conventions** were documented in the style guide. ③ Breaking **conventions** is fine—if you document why. |
| 7 | **boilerplate** | /ˈbɔɪləpleɪt/ | ① n.样板/模板代码② adj.模板的③ 标准措辞 | ① The PR template removes **boilerplate** from the description. ② Every project starts with the same **boilerplate** configuration. ③ **Boilerplate** code is a sign that the framework needs better abstractions. |
| 8 | **scaffold** | /ˈskæfəld/ | ① n.脚手架/支架② v.搭建基础③ 临时支撑 | ① The CLI tool **scaffolds** a new project in seconds. ② The documentation provides a **scaffold** for new contributors. ③ Remove the **scaffolding** once the team understands the pattern. |
| 9 | **onboard** | /ˈɒnbɔːd/ | ① v.入职/上手② 搭载③ 引入 | ① Good documentation **onboards** new engineers in days, not weeks. ② The README alone can't **onboard** someone—you need working examples. ③ We **onboarded** the service onto the new monitoring platform. |
| 10 | **prerequisite** | /priːˈrekwɪzɪt/ | ① n.先决条件/前提② n.必备条件③ adj.必需的 | ① A **prerequisite** for this tutorial is basic knowledge of Python. ② The **prerequisite** section lists everything you need installed. ③ Understanding CAP theorem is a **prerequisite** for designing distributed systems. |
| 11 | **disambiguate** | /ˌdɪsæmˈbɪɡjueɪt/ | ① 消除歧义/澄清② 区分③ 明确 | ① Use types to **disambiguate** function signatures. ② The naming convention helps **disambiguate** between internal and external APIs. ③ A good example **disambiguates** more than a paragraph of explanation. |
| 12 | **succinct** | /səkˈsɪŋkt/ | ① 简洁的/言简意赅的② 简明的③ 扼要的 | ① A **succinct** commit message is harder to write than a long one. ② The TL;DR should be **succinct**—three sentences max. ③ Her code reviews are refreshingly **succinct**: one point, one suggestion. |
| 13 | **glossary** | /ˈɡlɒsəri/ | ① 术语表/词汇表② 专用词表③ 名词解释 | ① The documentation includes a **glossary** of domain-specific terms. ② Every RFC should have a **glossary** if it introduces new concepts. ③ The **glossary** prevents miscommunication between teams. |
| 14 | **cross-reference** | /krɒs ˈrefərəns/ | ① 交叉引用② 相互参照③ 对照 | ① The documentation is heavily **cross-referenced** for easy navigation. ② **Cross-reference** the RFC with the API spec for complete context. ③ The postmortem **cross-references** related incidents. |
| 15 | **stub** | /stʌb/ | ① n.存根/占位符② n.空白页③ v.临时替代 | ① The API docs have a **stub** for the new endpoint—details coming next sprint. ② A test **stub** returns canned responses for isolated testing. ③ Don't merge a **stub** without a follow-up ticket. |
| 16 | **deprecate** | /ˈdeprɪkeɪt/ | ① v.弃用/不推荐② v.反对③ v.贬低 | ① The v1 API was **deprecated** with six months' notice. ② Always **deprecate** before you remove. ③ The compiler **deprecates** the old syntax with a warning. |
| 17 | **changelog** | /ˈtʃeɪndʒlɒɡ/ | ① 变更日志/更新日志② 修改记录③ 版本说明 | ① The **changelog** documents every user-facing change. ② A good **changelog** answers "what's new?" and "should I upgrade?" ③ The **changelog** is auto-generated from conventional commits. |
| 18 | **style guide** | /staɪl ɡaɪd/ | ① 风格指南/样式规范② 编写规范③ 格式指南 | ① The **style guide** covers naming, formatting, and comment conventions. ② A **style guide** eliminates bikeshedding in code reviews. ③ The **style guide** is enforced by a linter, not by hand. |
| 19 | **troubleshooting** | /ˈtrʌbəlʃuːtɪŋ/ | ① 故障排除/问题解决② 排错③ 故障诊断 | ① The **troubleshooting** section of the README saved me two hours. ② Good **troubleshooting** guides anticipate common mistakes. ③ **Troubleshooting** documentation ages better than API docs—bugs are timeless. |
| 20 | **playbook** | /ˈpleɪbʊk/ | ① 战术手册/策略指南② 剧本③ 操作手册 | ① The incident response **playbook** covers every known failure mode. ② The hiring **playbook** standardizes the interview process. ③ A **playbook** is not a runbook—it's strategy, not steps. |
| 21 | **annotate** | /ˈænəteɪt/ | ① v.注释/注解② v.标注③ v.加批注 | ① The code is heavily **annotated** with explaining-the-why comments. ② The architecture diagram was **annotated** with latency numbers. ③ **Annotate** the PR with inline comments, not just a summary. |
| 22 | **proofread** | /ˈpruːfriːd/ | ① v.校对/审校② 校正③ 审阅 | ① Always **proofread** your RFC before sharing it with stakeholders. ② The documentation was **proofread** by three engineers. ③ A tool can catch typos, but it can't **proofread** for logical clarity. |
| 23 | **coherent** | /kəʊˈhɪərənt/ | ① 连贯的/一致的② 条理清楚的③ 合乎逻辑的 | ① The architecture document should tell a **coherent** story. ② The API design lacks **coherent** naming—some use snake_case, others camelCase. ③ A **coherent** argument is more persuasive than a clever one. |
| 24 | **excerpt** | /ˈeksɜːpt/ | ① n.摘录/节选② v.引用③ 片段 | ① The postmortem includes an **excerpt** from the incident channel. ② The docs **excerpt** the relevant error messages. ③ An **excerpt** from the log file revealed the root cause. |
| 25 | **placeholder** | /ˈpleɪshəʊldə/ | ① n.占位符/填补空位者② n.临时替代③ n.预留位置 | ① Use descriptive **placeholder** text, not "Lorem ipsum." ② The function is a **placeholder**—the real implementation comes next sprint. ③ **Placeholders** in documentation signal unfinished work to readers. |
| 26 | **versioning** | /ˈvɜːʃənɪŋ/ | ① 版本控制/版本管理② 版本编号③ 版本划分 | ① Semantic **versioning** (semver) communicates the impact of changes. ② API **versioning** in the URL path is the simplest approach. ③ Documentation **versioning** lets users read docs for their specific release. |
| 27 | **Javadoc** | /ˈdʒævədɒk/ | ① Java 文档注释② API 文档生成器③ 代码文档规范 | ① **Javadoc**-style comments explain what a function does, not how. ② Every public method has a **Javadoc** comment. ③ The **Javadoc** convention has been adopted by many languages beyond Java. |
| 28 | **README** | /riːd miː/ | ① 自述文件/说明文档② 项目简介③ 入门文档 | ① The **README** is the most important document in any open-source project. ② A good **README** answers "what is this?" and "why should I care?" ③ The **README** should make sense to someone who has never seen the project. |
| 29 | **diagram** | /ˈdaɪəɡræm/ | ① n.图表/示意图② n.图解③ v.用图表表示 | ① A **diagram** is worth a thousand words of documentation. ② The architecture **diagram** showed every service and data flow. ③ **Diagram** as code—use PlantUML or Mermaid, not PowerPoint. |
| 30 | **whitepaper** | /ˈwaɪtpeɪpə/ | ① 白皮书/技术白皮书② 权威报告③ 政策文件 | ① The Bitcoin **whitepaper** is only nine pages long. ② The architecture **whitepaper** makes the case for the migration. ③ A **whitepaper** explains the problem before proposing the solution. |
| 31 | **abstract** | /ˈæbstrækt/ | ① n.摘要/概要② adj.抽象的③ v.提取 | ① The **abstract** of the paper summarizes the key findings. ② An **abstract** class defines an interface but not an implementation. ③ Every RFC should start with an **abstract**—three sentences that tell the reader whether to keep reading. |
| 32 | **preamble** | /priːˈæmbəl/ | ① 前言/序言② 导言③ 开场白 | ① The **preamble** of the RFC explains the motivation. ② Skip the **preamble** and get to the point. ③ The **preamble** to the style guide explains the philosophy behind the rules. |
| 33 | **appendix** | /əˈpendɪks/ | ① 附录/附件② 附加物③ 阑尾 | ① The benchmarking methodology is detailed in the **appendix**. ② An **appendix** is where detailed data goes—don't put it in the main body. ③ The **appendix** includes the full list of affected API endpoints. |
| 34 | **footnote** | /ˈfʊtnəʊt/ | ① 脚注/注释② 附注③ 补充说明 | ① A **footnote** clarifies a point without interrupting the flow. ② The **footnote** acknowledged the contribution of the intern who found the bug. ③ Use **footnotes** sparingly—they should be optional, not essential. |
| 35 | **callout** | /ˈkɔːlaʊt/ | ① 标注/强调框② 插注③ 醒目提示 | ① A **callout** box highlights important warnings in the documentation. ② The **callout** "⚠️ Breaking Change" caught every reviewer's attention. ③ Use **callouts** for gotchas, not for routine information. |
| 36 | **taxonomy** | /tækˈsɒnəmi/ | ① 分类法/分类体系② 分类学③ 命名法 | ① The bug **taxonomy** classifies incidents by root cause. ② A shared **taxonomy** for microservices helps teams discuss architecture. ③ The **taxonomy** of errors—transient, permanent, fatal, recoverable—guides the retry strategy. |
| 37 | **lexicon** | /ˈleksɪkən/ | ① 词汇/词典② 专业词汇③ 术语集 | ① Every domain has its own **lexicon**—learn it to communicate effectively. ② The team's internal **lexicon** includes terms like "frobnicate" and "grok." ③ A shared **lexicon** prevents the same thing having three different names. |
| 38 | **nomenclature** | /nəˈmeŋklətʃə/ | ① 命名法/命名体系② 术语③ 名称 | ① Consistent **nomenclature** across the codebase makes it navigable. ② The **nomenclature** for API versions—v1, v2, v3—is simple but effective. ③ Bad **nomenclature** is a signal of unclear thinking. |
| 39 | **specification** | /ˌspesɪfɪˈkeɪʃən/ | ① 规范/说明② 规格③ 详细说明 | ① The OpenAPI **specification** defines every endpoint. ② A good **spec** is precise enough to implement from. ③ Writing the **specification** before the code prevents rework. |
| 40 | **errata** | /ɪˈrɑːtə/ | ① 勘误表/错误更正② 正误表③ 更正 | ① The documentation **errata** lists known mistakes. ② An **errata** section shows that you care about accuracy. ③ The **errata** for the original paper took longer to write than the paper itself. |
| 41 | **canonical** | /kəˈnɒnɪkəl/ | ① 权威的/标准的② 规范的③ 典范的 | ① The README is the **canonical** source of truth for the project. ② A **canonical** example demonstrates the idiomatic way to use the API. ③ Every concept should have one **canonical** name in the codebase. |
| 42 | **idiomatic** | /ˌɪdiəˈmætɪk/ | ① 地道的/惯用的② 符合语言习惯的③ 自然的 | ① **Idiomatic** Python looks different from **idiomatic** Java. ② Write **idiomatic** code—don't fight the language. ③ An **idiomatic** expression in English can't be translated word-for-word. |
| 43 | **terseness** | /tɜːsnəs/ | ① 简洁/精练② 简要③ 扼要 | ① The **terseness** of the Go language is a feature, not a bug. ② **Terseness** at the expense of clarity is a net negative. ③ Her code review comments are known for their **terseness**—three words that say everything. |
| 44 | **verbosity** | /vɜːˈbɒsɪti/ | ① 冗长/啰嗦② 详细③ 唠叨 | ① Java's **verbosity** is both its criticism and its documentation. ② **Verbosity** in log messages is acceptable; **verbosity** in variable names is not. ③ The **verbosity** of the error message actually helped—it pinpointed the exact line. |
| 45 | **proofreading** | /ˈpruːfriːdɪŋ/ | ① 校对/审校② 校正③ 审阅 | ① **Proofreading** is not the same as editing—it's about catching errors, not improving style. ② Automated **proofreading** catches typos but not logic errors. ③ Spend 10 minutes **proofreading** your RFC before the review. |
| 46 | **human-readable** | /ˈhjuːmən ˈriːdəbəl/ | ① 人类可读的② 易读的③ 可理解的 | ① JSON is **human-readable**; protobuf is not. ② Log messages should be **human-readable**—no stack traces as the first thing you see. ③ A **human-readable** slug is better than a UUID in URLs. |
| 47 | **self-documenting** | /self ˈdɒkjʊmentɪŋ/ | ① 自文档化的② 自解释的③ 不言自明的 | ① Well-named code is **self-documenting**. ② **Self-documenting** APIs make documentation less critical. ③ Strive for **self-documenting** code, but write documentation anyway. |
| 48 | **deprecation notice** | /ˌdeprɪˈkeɪʃən ˈnəʊtɪs/ | ① 弃用通知② 废止公告③ 停止支持通知 | ① The **deprecation notice** gave developers 12 months to migrate. ② A **deprecation notice** should explain the replacement and the timeline. ③ Ignoring a **deprecation notice** is a choice—just don't be surprised when it breaks. |
| 49 | **migration guide** | /maɪˈɡreɪʃən ɡaɪd/ | ① 迁移指南② 升级指南③ 转换指南 | ① The **migration guide** walks users from v2 to v3 step by step. ② A **migration guide** should include before-and-after code examples. ③ The best **migration guide** is an automated script. |
| 50 | **onboarding doc** | /ˈɒnbɔːdɪŋ dɒk/ | ① 入职文档/上手文档② 新手指南③ 入门指南 | ① The **onboarding doc** got me from zero to first commit in two hours. ② An **onboarding doc** that's out of date is worse than no **onboarding doc**. ③ The **onboarding doc** is tested by every new hire—keep it current. |

---

### Group 3/6: Engineering Leadership & Management（工程领导与管理）

| # | Word | Pronunciation | Meanings | Example Sentences |
|---|------|--------------|----------|-------------------|
| 1 | **mentorship** | /ˈmentɔːʃɪp/ | ① 导师制/指导关系② 师徒制③ 辅导 | ① **Mentorship** accelerates growth more than any course. ② The **mentorship** program pairs junior engineers with staff engineers. ③ **Mentorship** is a two-way street—mentors learn too. |
| 2 | **sponsorship** | /ˈspɒnsəʃɪp/ | ① 赞助/支持② 举荐③ 庇护 | ① **Sponsorship** is different from mentorship—a sponsor advocates for you when you're not in the room. ② The project had executive **sponsorship** from the CTO. ③ Career advancement requires **sponsorship**, not just mentorship. |
| 3 | **delegation** | /ˌdelɪˈɡeɪʃən/ | ① 委托/授权② 代表团③ 下放权力 | ① Effective **delegation** is the hardest skill for new managers. ② **Delegation** is not abdication—you still own the outcome. ③ The art of **delegation**: give away the how, keep the what and why. |
| 4 | **stakeholder** | /ˈsteɪkhəʊldə/ | ① 利益相关者② 股东③ 利害关系人 | ① Every architectural decision has **stakeholders** beyond engineering. ② Map your **stakeholders** before writing the RFC. ③ The **stakeholder** review caught requirements engineering had missed. |
| 5 | **alignment** | /əˈlaɪnmənt/ | ① 一致/协调② 对齐③ 联盟 | ① **Alignment** on priorities prevents teams from working at cross-purposes. ② The offsite created **alignment** around the technical vision. ③ **Alignment** doesn't mean everyone agrees—it means everyone can commit. |
| 6 | **buy-in** | /baɪ ɪn/ | ① 认同/接受② 支持③ 认可 | ① The RFC process builds **buy-in** before a line of code is written. ② Without engineering **buy-in**, the migration will fail. ③ Getting **buy-in** from the team takes longer than writing the code. |
| 7 | **bandwidth** | /ˈbændwɪdθ/ | ① 带宽/处理能力② 精力③ 人力 | ① The team doesn't have **bandwidth** for new features this quarter. ② Asking "do you have **bandwidth**?" respects the other person's time. ③ Cognitive **bandwidth** is finite—reduce meetings to increase it. |
| 8 | **velocity** | /vɪˈlɒsɪti/ | ① 速度/速率② 开发速度③ 工作效率 | ① Story points measure **velocity**, not value. ② The team's **velocity** dropped after the reorg—and that's normal. ③ **Velocity** is a planning tool, not a performance metric. |
| 9 | **retro** | /ˈretrəʊ/ | ① 回顾会（简称）② 复古③ 回溯 | ① The **retro** surfaced frustration with the flaky CI pipeline. ② A good **retro** produces actionable items, not just complaints. ③ The monthly **retro** is the team's most important meeting. |
| 10 | **one-on-one** | /wʌn ɒn wʌn/ | ① 一对一会议② 单独交流③ 面谈 | ① The weekly **one-on-one** is the most important meeting on a manager's calendar. ② **One-on-ones** are for the report, not the manager. ③ The **one-on-one** agenda belongs to the engineer—the manager is there to listen. |
| 11 | **skip-level** | /skɪp ˈlevəl/ | ① 跳级沟通② 跨级一对一③ 越级 | ① The director holds quarterly **skip-level** meetings with every engineer. ② **Skip-level** feedback gives managers insight into their managers. ③ A **skip-level** is not for escalation—it's for perspective. |
| 12 | **performance review** | /pəˈfɔːməns rɪˈvjuː/ | ① 绩效评估② 业绩考核③ 绩效审核 | ① The **performance review** should contain no surprises. ② **Performance reviews** that happen once a year are a failure of management. ③ Continuous feedback makes the **performance review** a summary, not a revelation. |
| 13 | **360 review** | /θriː ˈsɪksti rɪˈvjuː/ | ① 360度评估② 全方位评估③ 多方反馈评审 | ① The **360 review** collects feedback from peers, reports, and managers. ② A **360 review** reveals blind spots. ③ **360 reviews** are only useful in a culture of psychological safety. |
| 14 | **promotion packet** | /prəˈməʊʃən ˈpækɪt/ | ① 晋升材料/晋升包② 升职申请③ 晋升文档 | ① The **promotion packet** documents impact, not just activity. ② A **promotion packet** should tell a story of growth and impact. ③ Start your **promotion packet** six months before you need it. |
| 15 | **career ladder** | /kəˈrɪə ˈlædə/ | ① 职业阶梯/职级体系② 晋升通道③ 职业等级 | ① The engineering **career ladder** has parallel IC and management tracks. ② A well-defined **career ladder** makes expectations transparent. ③ The **career ladder** should describe impact, not years of experience. |
| 16 | **calibration** | /ˌkælɪˈbreɪʃən/ | ① 校准/标定② 调整③ 统一标准 | ① The **calibration** meeting ensures consistent promotion standards across teams. ② Performance **calibration** reduces manager bias. ③ Without **calibration**, promotion is a lottery. |
| 17 | **low-performer** | /ləʊ pəˈfɔːmə/ | ① 低绩效者② 表现不佳者③ 绩效落后者 | ① A **low-performer** in one context may be a high-performer in another. ② Managing a **low-performer** starts with clear expectations. ③ The term **low-performer** is a label, not a diagnosis—understand the why. |
| 18 | **PIP** | /pɪp/ | ① 绩效改进计划② 留用察看③ 改善计划 | ① A **PIP** should never be a surprise—it's the last step after months of feedback. ② A **PIP** with clear, achievable goals can work; a **PIP** as a formality is cruel. ③ Being put on a **PIP** is often the signal to start looking elsewhere. |
| 19 | **attrition** | /əˈtrɪʃən/ | ① 流失/减员② 损耗③ 消磨 | ① Engineer **attrition** spiked after the return-to-office mandate. ② **Attrition** is a lagging indicator of deeper problems. ③ The cost of **attrition**—recruiting, onboarding, lost productivity—is enormous. |
| 20 | **retention** | /rɪˈtenʃən/ | ① 保留/留存② 记忆③ 保持 | ① **Retention** is cheaper than hiring. ② The best **retention** strategy is meaningful work and psychological safety. ③ **Retention** interviews tell you why people stay—exit interviews tell you why they left. |
| 21 | **headcount** | /ˈhedkaʊnt/ | ① 编制人数/人员数② 员工数量③ 人数 | ① The **headcount** freeze meant no new hires for two quarters. ② **Headcount** planning determines the team's capacity for the year. ③ **Headcount** is an input; team effectiveness is the output. |
| 22 | **RACI** | /ˈreɪsi/ | ① 责任分配矩阵② 职责分工③ 角色明晰工具 | ① The **RACI** matrix clarified who approves vs. who is informed. ② A **RACI** chart prevents the "everyone is responsible so no one is responsible" problem. ③ **RACI** stands for Responsible, Accountable, Consulted, Informed. |
| 23 | **OKR** | /əʊ keɪ ɑː/ | ① 目标与关键结果② 目标管理法③ 绩效目标 | ① The team's **OKRs** align with the company's strategic goals. ② An **OKR** should be ambitious—"100% uptime" is not a good OKR, it's a baseline. ③ **OKRs** without regular check-ins are just wishlists. |
| 24 | **KPI** | /keɪ piː aɪ/ | ① 关键绩效指标② 主要指标③ 核心度量 | ① P99 latency is a **KPI** for the platform team. ② A **KPI** that can't be gamed is rare—think carefully about incentives. ③ Vanity **KPIs** look good on slides but don't drive decisions. |
| 25 | **roadmap** | /ˈrəʊdmæp/ | ① 路线图/规划② 发展蓝图③ 战略计划 | ① The product **roadmap** is a statement of intent, not a contract. ② An engineering **roadmap** balances features, tech debt, and reliability. ③ A **roadmap** beyond six months is fiction. |
| 26 | **tech debt** | /tek det/ | ① 技术债务（简称）② 技术欠账③ 代码负债 | ① Not all **tech debt** is bad—some is a deliberate tradeoff for speed. ② **Tech debt** that isn't tracked becomes invisible and grows. ③ Paying down **tech debt** should be a continuous activity, not a special project. |
| 27 | **refactor** | /riːˈfæktə/ | ① v/n.重构② 代码重组③ 重整 | ① We spent a sprint **refactoring** the authentication module. ② A **refactor** changes internal structure without changing external behavior. ③ **Refactor** mercilessly—but always with tests. |
| 28 | **migration** | /maɪˈɡreɪʃən/ | ① 迁移/转移② 迁徙③ 过渡 | ① The database **migration** took six months of preparation and two hours of execution. ② Cloud **migration** is a organizational change, not just a technical one. ③ Every **migration** needs a rollback plan. |
| 29 | **platform team** | /ˈplætfɔːm tiːm/ | ① 平台团队/基础设施团队② 平台工程组③ 基础架构团队 | ① The **platform team** builds tools that make other teams faster. ② A **platform team** treats other engineers as customers. ③ The **platform team** reduced deploy time from 45 minutes to 3. |
| 30 | **DevOps** | /ˈdevɒps/ | ① 开发运维一体化② DevOps 文化③ 开发运维 | ① **DevOps** is a culture, not a job title. ② The **DevOps** movement broke down the wall between developers and operators. ③ "You build it, you run it" is the essence of **DevOps**. |
| 31 | **SRE** | /es ɑːr iː/ | ① 站点可靠性工程师② 网站可靠性工程③ 运维开发 | ① **SRE** applies software engineering to operations problems. ② The **SRE** team maintains the error budget. ③ **SRE** is what happens when you ask a software engineer to design an operations function. |
| 32 | **error budget** | /ˈerə ˈbʌdʒɪt/ | ① 错误预算/故障预算② 容错额度③ 可接受故障量 | ① The **error budget** is 0.1%—that's 43 minutes of downtime per month. ② Once the **error budget** is exhausted, feature development stops. ③ The **error budget** aligns incentives between dev and SRE. |
| 33 | **SLO** | /es el əʊ/ | ① 服务等级目标② 服务水平目标③ 服务质量目标 | ① The **SLO** for API latency is 99% of requests under 100ms. ② An **SLO** that is too tight causes burnout; too loose, user dissatisfaction. ③ **SLOs** without consequences are just monitoring. |
| 34 | **SLA** | /es el eɪ/ | ① 服务等级协议② 服务水平协议③ 服务质量保障 | ① The **SLA** guarantees 99.9% uptime with financial penalties. ② An **SLA** is a contract with customers; an SLO is an internal target. ③ Breaking the **SLA** costs money—that's the point. |
| 35 | **blameless** | /ˈbleɪmləs/ | ① 不追责的/免责的② 无过错的③ 不指责的 | ① A **blameless** postmortem focuses on systems, not individuals. ② **Blameless** culture encourages incident reporting. ③ **Blameless** does not mean "no accountability." |
| 36 | **post-incident review** | /pəʊst ˈɪnsɪdənt rɪˈvjuː/ | ① 事后评估/事故复盘② 事件后评审③ 故障后分析 | ① The **post-incident review** is blameless and action-oriented. ② Every Sev-1 triggers a **post-incident review** within five days. ③ The **post-incident review** culture is the best thing about our engineering org. |
| 37 | **decision fatigue** | /dɪˈsɪʒən fəˈtiːɡ/ | ① 决策疲劳② 选择疲惫③ 判断力下降 | ① Limit architectural decisions to reduce **decision fatigue**. ② The style guide eliminates **decision fatigue** about formatting. ③ **Decision fatigue** explains why judges grant fewer paroles later in the day. |
| 38 | **bikeshedding** | /ˈbaɪkʃedɪŋ/ | ① 鸡毛蒜皮的争论② 避重就轻的讨论③ 无意义的细节争执 | ① The team spent an hour **bikeshedding** the name of the variable. ② **Bikeshedding** happens because trivial things are easy to have opinions about. ③ A style guide eliminates **bikeshedding** about formatting. |
| 39 | **bottleneck** | /ˈbɒtəlnek/ | ① 瓶颈/障碍② 阻塞点③ 狭窄处 | ① The tech lead is the **bottleneck**—every decision goes through them. ② The code review **bottleneck** was addressed by adding more reviewers. ③ The single database was the **bottleneck** at 1,000 QPS. |
| 40 | **bus factor** | /bʌs ˈfæktə/ | ① 巴士因子/关键人员风险② 单点知识风险③ 人员依赖度 | ① The **bus factor** for the authentication module is 1—that's a risk. ② Increase the **bus factor** through pair programming and documentation. ③ A **bus factor** of 1 is an organizational failure, not an individual problem. |
| 41 | **knowledge silo** | /ˈnɒlɪdʒ ˈsaɪləʊ/ | ① 知识孤岛/信息壁垒② 知识隔离③ 信息孤岛 | ① The **knowledge silo** around the legacy system was dangerous. ② **Knowledge silos** form when documentation is lacking and turnover is low. ③ Break **knowledge silos** with rotation programs and documentation sprints. |
| 42 | **documentation** | /ˌdɒkjʊmenˈteɪʃən/ | ① 文档/文件② 文献资料③ 证明文件 | ① **Documentation** is a love letter to your future self. ② The **documentation** is tested by every new hire—keep it current. ③ Outdated **documentation** is worse than no documentation. |
| 43 | **runbook** | /ˈrʌnbʊk/ | ① 操作手册/运维手册② 应急预案③ 操作指南 | ① Every alert should link to a **runbook**. ② The **runbook** was tested during the last fire drill. ③ A **runbook** that hasn't been tested is just a hope. |
| 44 | **playbook** | /ˈpleɪbʊk/ | ① 战术手册/策略指南② 剧本③ 操作手册 | ① The incident **playbook** covers common failure patterns. ② The hiring **playbook** standardizes the interview process. ③ A **playbook** is strategy; a runbook is execution. |
| 45 | **capacity planning** | /kəˈpæsɪti ˈplænɪŋ/ | ① 容量规划/产能规划② 能力规划③ 资源规划 | ① **Capacity planning** ensures we have enough servers for Black Friday. ② Team **capacity planning** accounts for vacations, on-call, and meetings. ③ **Capacity planning** without historical data is guesswork. |
| 46 | **succession plan** | /səkˈseʃən plæn/ | ① 继任计划/接替计划② 接班人计划③ 连续计划 | ① Every critical role needs a **succession plan**. ② The **succession plan** for the tech lead was her senior engineer. ③ No **succession plan** means a bus factor of 1 for leadership. |
| 47 | **empowerment** | /ɪmˈpaʊəmənt/ | ① 赋权/授权② 赋能③ 准许 | ① **Empowerment** means giving engineers the authority to make decisions. ② The platform team's mission is **empowerment** of other teams. ③ **Empowerment** without clear boundaries leads to chaos. |
| 48 | **micromanage** | /ˈmaɪkrəʊˌmænɪdʒ/ | ① v.微观管理/过度干预② 事无巨细地管理③ 过度控制 | ① Don't **micromanage** engineers—they know their code better than you do. ② **Micromanagement** is usually driven by anxiety, not malice. ③ The manager **micromanaged** every commit message until the team pushed back. |
| 49 | **servant leadership** | /ˈsɜːvənt ˈliːdəʃɪp/ | ① 仆人式领导② 服务型领导③ 公仆领导 | ① **Servant leadership** asks "how can I help you succeed?" not "why aren't you performing?" ② The best engineering managers practice **servant leadership**. ③ **Servant leadership** is not about being nice—it's about removing obstacles. |
| 50 | **psychological safety** | /ˌsaɪkəˈlɒdʒɪkəl ˈseɪfti/ | ① 心理安全② 心理安全感③ 放心表达 | ① **Psychological safety** means you can say "I don't know" without fear. ② Google's Project Aristotle found **psychological safety** was the #1 predictor of team success. ③ Without **psychological safety**, postmortems become cover-ups. |

---

### Group 4/6: Global Tech Industry & Trends（全球科技产业与趋势）

| # | Word | Pronunciation | Meanings | Example Sentences |
|---|------|--------------|----------|-------------------|
| 1 | **disruption** | /dɪsˈrʌpʃən/ | ① 颠覆/破坏性创新② 中断③ 扰乱 | ① The smartphone was a **disruption** to the entire camera industry. ② Every pitch deck claims to be a **disruption** to something. ③ Genuine **disruption** is rare—most "disruption" is just competition. |
| 2 | **unicorn** | /ˈjuːnɪkɔːn/ | ① 独角兽公司（估值超10亿美元）② 独角兽③ 稀有的 | ① The startup became a **unicorn** within 18 months of launch. ② **Unicorn** valuations don't guarantee **unicorn** outcomes. ③ The **unicorn** engineer—full-stack, DevOps, and design—doesn't exist. |
| 3 | **decacorn** | /ˈdekəkɔːn/ | ① 十角兽（估值超100亿美元）② 超级独角兽③ 百亿估值公司 | ① The company achieved **decacorn** status after the Series E. ② **Decacorns** are rarer than unicorns but face the same scaling challenges. ③ The difference between a **decacorn** and a unicorn is often just timing. |
| 4 | **venture capital** | /ˈventʃə ˈkæpɪtəl/ | ① 风险投资/创业投资② VC③ 风投资金 | ① The startup raised $20M in **venture capital**. ② **Venture capital** is not the only path—bootstrap if you can. ③ The **venture capital** model expects 10× returns on winners to cover the losers. |
| 5 | **IPO** | /aɪ piː əʊ/ | ① 首次公开募股/上市② 公开发行③ 股票上市 | ① The **IPO** valued the company at $5 billion. ② An **IPO** is a financing event, not an exit. ③ The **IPO** lockup period prevents insiders from selling for 180 days. |
| 6 | **SPAC** | /spæk/ | ① 特殊目的收购公司② 空白支票公司③ 借壳上市工具 | ① The company went public via a **SPAC** merger. ② **SPACs** boomed in 2020 and busted in 2022. ③ A **SPAC** is faster than a traditional IPO but has less scrutiny. |
| 7 | **acquisition** | /ˌækwɪˈzɪʃən/ | ① 收购/并购② 获得③ 取得 | ① The **acquisition** of the startup was an acqui-hire. ② The **acquisition** integration took 18 months. ③ Most **acquisitions** destroy value—the exceptions are legendary. |
| 8 | **acqui-hire** | /ˈækwɪhaɪə/ | ① 人才收购/以人才为目的的收购② 团队收购③ 挖人式收购 | ① The **acqui-hire** brought a team of five ML engineers to the company. ② The startup's product was shut down after the **acqui-hire**. ③ An **acqui-hire** values the team, not the technology. |
| 9 | **merger** | /ˈmɜːdʒə/ | ① 合并/兼并② 融合③ 结合 | ① The **merger** of the two platforms created a unified API. ② Culture clashes are the leading cause of failed **mergers**. ③ A **merger** of equals is rarely equal. |
| 10 | **due diligence** | /djuː ˈdɪlɪdʒəns/ | ① 尽职调查/审慎调查② 背景核查 | ① The **due diligence** process uncovered three security vulnerabilities. ② Technical **due diligence** is part of every acquisition. ③ **Due diligence** in hiring means reference checks and work sample tests. |
| 11 | **valuation** | /ˌvæljuˈeɪʃən/ | ① 估值/估价② 评价③ 定价 | ① The **valuation** was based on 50× ARR. ② **Valuation** is what someone will pay; it's not the same as value. ③ Down rounds are a hit to **valuation** and morale. |
| 12 | **runway** | /ˈrʌnweɪ/ | ① 资金跑道/存活时间② 跑道③ T台 | ① The startup has 18 months of **runway** at the current burn rate. ② Extending **runway** means cutting costs or raising more money. ③ **Runway** is measured in months, not dollars. |
| 13 | **burn rate** | /bɜːn reɪt/ | ① 资金消耗率/烧钱速度② 消耗速率③ 燃烧率 | ① The **burn rate** is $500K per month—that's $6M per year. ② A high **burn rate** is fine if growth justifies it. ③ The **burn rate** doubled after the hiring spree. |
| 14 | **bootstrapping** | /ˈbuːtstræpɪŋ/ | ① 白手起家/自力更生② 自举③ 自我引导 | ① The company was **bootstrapped** to profitability without VC funding. ② **Bootstrapping** forces discipline—every dollar counts. ③ **Bootstrapping** a compiler means it can compile itself. |
| 15 | **pivot** | /ˈpɪvət/ | ① v/n.转型/转向② 转变方向③ 调整策略 | ① The startup **pivoted** from enterprise to consumer. ② The **pivot** saved the company—the original idea didn't work. ③ A **pivot** is not a failure; it's a response to evidence. |
| 16 | **product-market fit** | /ˈprɒdʌkt ˈmɑːkɪt fɪt/ | ① 产品市场契合② 产品与市场的匹配③ 市场需求契合 | ① The startup found **product-market fit** in month 14. ② **Product-market fit** feels like a wave pushing you forward. ③ Before **product-market fit**, nothing else matters. |
| 17 | **churn** | /tʃɜːn/ | ① 流失/搅动② 客户流失率③ 翻腾 | ① Monthly **churn** dropped from 5% to 2% after the redesign. ② Engineer **churn** is a leading indicator of cultural problems. ③ High **churn** means you're filling a leaky bucket. |
| 18 | **cac** | /siː eɪ siː/ | ① 客户获取成本② 获客成本③ CAC | ① The **CAC** is $200 per customer. ② If **CAC** exceeds LTV, the business model is broken. ③ Reducing **CAC** through organic growth is the holy grail of SaaS. |
| 19 | **LTV** | /el tiː viː/ | ① 客户终身价值② 生命周期总价值③ 终身价值 | ① The **LTV** of an enterprise customer is $50K. ② An **LTV**:CAC ratio of 3:1 is considered healthy. ③ Improving **LTV** through retention is more efficient than reducing CAC. |
| 20 | **scale-up** | /skeɪl ʌp/ | ① n.规模扩大/扩张② v.按比例增加③ 成长阶段 | ① The **scale-up** phase is harder than the startup phase. ② **Scale-up** challenges are organizational, not technical. ③ What works for 50 people won't work for 500—that's the **scale-up** problem. |
| 21 | **down round** | /daʊn raʊnd/ | ① 折价融资/估值下调轮② 降级融资③ 贬损融资 | ① The **down round** cut the valuation from $2B to $800M. ② A **down round** is painful but sometimes necessary for survival. ③ **Down rounds** dilute existing shareholders significantly. |
| 22 | **anti-dilution** | /ˌænti daɪˈluːʃən/ | ① 反稀释② 防止稀释③ 反摊薄 | ① The investors had **anti-dilution** protection from the Series A. ② **Anti-dilution** clauses protect early investors in down rounds. ③ **Anti-dilution** provisions can make fundraising harder later. |
| 23 | **open source** | /ˈəʊpən sɔːs/ | ① 开源/开放源代码② 开源软件③ 开放协作 | ① **Open source** is the dominant model for infrastructure software. ② The company **open-sourced** its machine learning framework. ③ **Open source** is about collaboration, not just free code. |
| 24 | **inner source** | /ˈɪnə sɔːs/ | ① 内部开源② 内部开放协作③ 企业内开源 | ① **Inner source** applies open-source practices within the company. ② **Inner source** lets any team contribute to any codebase. ③ **Inner source** reduces duplication across teams. |
| 25 | **freemium** | /ˈfriːmiəm/ | ① 免费增值模式② 基础免费高级收费③ 免费+付费 | ① The **freemium** tier serves as both marketing and a trial. ② **Freemium** SaaS typically converts 2-5% of users to paid. ③ The **freemium** model works when the free tier is genuinely useful. |
| 26 | **SaaS** | /sæs/ | ① 软件即服务② SaaS 模式③ 云软件服务 | ① **SaaS** companies trade at higher multiples than on-prem companies. ② The **SaaS** model generates recurring revenue. ③ Every software company is becoming a **SaaS** company. |
| 27 | **PaaS** | /pæs/ | ① 平台即服务② 云平台服务③ PaaS | ① Heroku pioneered the **PaaS** model. ② **PaaS** abstracts away infrastructure management. ③ Kubernetes made **PaaS** less relevant—or more, depending on who you ask. |
| 28 | **IaaS** | /aɪ æs/ | ① 基础设施即服务② 云基础设施③ IaaS | ① AWS is the dominant **IaaS** provider. ② **IaaS** gives you virtual machines; PaaS gives you a platform. ③ The line between **IaaS** and PaaS is blurring. |
| 29 | **multi-cloud** | /ˈmʌlti klaʊd/ | ① 多云/多云架构② 多云计算③ 跨云 | ① The **multi-cloud** strategy prevents vendor lock-in. ② **Multi-cloud** adds complexity that most companies don't need. ③ **Multi-cloud** is often an accident, not a strategy. |
| 30 | **hybrid cloud** | /ˈhaɪbrɪd klaʊd/ | ① 混合云② 公有私有混合③ 混合云计算 | ① The **hybrid cloud** model keeps sensitive data on-prem. ② **Hybrid cloud** is a stepping stone, not a destination. ③ **Hybrid cloud** doubles your operational burden. |
| 31 | **edge computing** | /edʒ kəmˈpjuːtɪŋ/ | ① 边缘计算② 近端计算③ 分布式前端计算 | ① **Edge computing** reduces latency by processing data near the source. ② CDN is the original **edge computing**. ③ **Edge computing** shifts compute from centralized clouds to distributed nodes. |
| 32 | **quantum computing** | /ˈkwɒntəm kəmˈpjuːtɪŋ/ | ① 量子计算② 量子运算③ 量子电脑 | ① **Quantum computing** promises to break RSA encryption. ② **Quantum computing** is still in the "physics experiment" phase. ③ The **quantum computing** hype cycle is measured in decades. |
| 33 | **AGI** | /eɪ dʒiː aɪ/ | ① 通用人工智能/强人工智能② 人类级别的AI③ 全能AI | ① **AGI**—Artificial General Intelligence—is the holy grail of AI research. ② Predictions for **AGI** range from 5 years to never. ③ **AGI** that surpasses humans at everything is called superintelligence. |
| 34 | **LLM** | /el el em/ | ① 大语言模型/大型语言模型② 语言大模型③ LLM | ① **LLMs** like GPT-4 have transformed natural language processing. ② An **LLM** is not AGI—it's a next-token predictor. ③ **LLM** hallucinations are a fundamental limitation, not a bug. |
| 35 | **alignment** | /əˈlaɪnmənt/ | ① AI对齐/价值对齐② 协调③ 调整 | ① AI **alignment** research ensures AI systems do what humans intend. ② The **alignment** problem: how do you make an AI want what we want? ③ **Alignment** is the most important unsolved problem in AI safety. |
| 36 | **hallucination** | /həˌluːsɪˈneɪʃən/ | ① 幻觉/AI编造信息② 错觉③ 幻象 | ① LLM **hallucination** produces convincing but false information. ② **Hallucination** is a feature in creative writing, a bug in legal documents. ③ Reducing **hallucination** is a top priority for enterprise LLM adoption. |
| 37 | **prompt engineering** | /prɒmpt ˌendʒɪˈnɪərɪŋ/ | ① 提示工程/提示设计② 调教AI③ 提示词优化 | ① **Prompt engineering** is the art of getting LLMs to produce useful output. ② **Prompt engineering** may be a temporary job category. ③ The best **prompt engineers** are clear writers. |
| 38 | **fine-tuning** | /faɪn ˈtjuːnɪŋ/ | ① 微调/精调② 精细调整③ 优化 | ① **Fine-tuning** adapts a pre-trained model to a specific task. ② **Fine-tuning** is cheaper than training from scratch. ③ The model was **fine-tuned** on the company's internal documentation. |
| 39 | **RAG** | /ræɡ/ | ① 检索增强生成② 检索辅助生成③ RAG架构 | ① **RAG** grounds LLM responses in retrieved documents. ② **RAG** reduces hallucinations by providing the model with relevant context. ③ The **RAG** architecture combines retrieval with generation. |
| 40 | **GPU** | /dʒiː piː juː/ | ① 图形处理器/显卡② GPU③ 并行计算芯片 | ① Training LLMs requires thousands of **GPUs**. ② The **GPU** shortage drove up cloud costs. ③ **GPUs** are the new oil—whoever controls supply controls the AI race. |
| 41 | **TPU** | /tiː piː juː/ | ① 张量处理单元② Google的AI芯片③ TPU | ① Google's **TPUs** are optimized for tensor operations. ② **TPUs** are more efficient than GPUs for certain ML workloads. ③ The **TPU** v5 is only available through Google Cloud. |
| 42 | **moat** | /məʊt/ | ① 护城河/竞争壁垒② 防御优势③ 竞争优势 | ① Network effects create a powerful **moat**. ② The company's data **moat**—proprietary training data—is its main advantage. ③ No **moat** lasts forever in tech. |
| 43 | **network effect** | /ˈnetwɜːk ɪˈfekt/ | ① 网络效应② 网络外部性③ 用的人越多价值越高 | ① **Network effects** made eBay nearly unassailable for a decade. ② Two-sided marketplaces have the strongest **network effects**. ③ **Network effects** are the most defensible moat in tech. |
| 44 | **flywheel** | /ˈflaɪwiːl/ | ① 飞轮效应/增长飞轮② 惯性轮③ 良性循环 | ① More content → more users → more content—that's the **flywheel**. ② The Amazon **flywheel** is the most famous in business. ③ A good **flywheel** makes each investment compound. |
| 45 | **ecosystem** | /ˈiːkəʊˌsɪstəm/ | ① 生态系统/生态圈② 生态③ 体系 | ① The iOS developer **ecosystem** generates $100B annually. ② A platform is only as strong as its **ecosystem**. ③ Developer **ecosystem** is the new distribution channel. |
| 46 | **disintermediation** | /dɪsˌɪntəmiːdiˈeɪʃən/ | ① 去中介化/脱媒② 减少中间人③ 直接化 | ① The internet **disintermediated** travel agents. ② Blockchain promises **disintermediation** of financial services. ③ Platforms re-intermediate what the internet **disintermediated**. |
| 47 | **commoditization** | /kəˌmɒdɪtaɪˈzeɪʃən/ | ① 商品化/同质化② 大众化③ 廉价化 | ① Cloud compute is undergoing **commoditization**. ② **Commoditization** of a technology shifts value to the layer above. ③ Your complement's **commoditization** is good for you. |
| 48 | **winner-take-all** | /ˈwɪnə teɪk ɔːl/ | ① 赢家通吃/胜者全得② 赢家独占③ 全赢 | ① Search is a **winner-take-all** market. ② Network effects tend toward **winner-take-all** dynamics. ③ **Winner-take-all** markets produce outsized returns for the leader. |
| 49 | **regulation** | /ˌreɡjʊˈleɪʃən/ | ① 监管/法规② 管理条例③ 调控 | ① Tech **regulation** is coming—the question is what form it takes. ② GDPR **regulation** reshaped how companies handle user data. ③ **Regulation** can protect incumbents more than consumers. |
| 50 | **antitrust** | /ˌæntiˈtrʌst/ | ① 反垄断/反托拉斯② 反垄断法③ 反竞争 | ① The **antitrust** lawsuit could force the company to divest acquisitions. ② **Antitrust** enforcement has been reinvigorated globally. ③ **Antitrust** action against tech giants is bipartisan in the US. |

---

### Group 5/6: Developer Experience & Tooling（开发者体验与工具）

| # | Word | Pronunciation | Meanings | Example Sentences |
|---|------|--------------|----------|-------------------|
| 1 | **DX** | /diː eks/ | ① 开发者体验② 开发体验③ 开发人员体验 | ① **DX** is as important as UX—happy developers build better products. ② We invested in **DX** by improving the CI pipeline. ③ Good **DX** means: clone, run one command, and you're developing. |
| 2 | **ergonomics** | /ˌɜːɡəˈnɒmɪks/ | ① 人体工程学/宜人性② 工效学③ 使用舒适度 | ① API **ergonomics** determine whether developers enjoy using your library. ② The language's **ergonomics**—error messages, tooling, syntax—affect adoption. ③ Good **ergonomics** reduce cognitive load. |
| 3 | **IDE** | /aɪ diː iː/ | ① 集成开发环境② IDE③ 开发工具 | ① VS Code is the most popular **IDE** in the world. ② A good **IDE** is like a second brain. ③ The **IDE**'s refactoring tools saved hours of manual work. |
| 4 | **completions** | /kəmˈpliːʃənz/ | ① 自动补全/代码补全② 完成③ 补充 | ① AI **completions** speed up boilerplate coding. ② Tab **completions** in the terminal reduce typing. ③ **Completions** that guess wrong are worse than no completions. |
| 5 | **linting** | /lɪntɪŋ/ | ① 代码检查/静态分析② 代码风格检查③ 格式化检查 | ① **Linting** catches errors before they reach code review. ② The **linting** rules are enforced in CI. ③ **Linting** eliminates bikeshedding about style. |
| 6 | **formatting** | /ˈfɔːmætɪŋ/ | ① 格式化/格式编排② 排版③ 样式设定 | ① Prettier handles code **formatting** so humans don't have to argue about it. ② Automatic **formatting** on save is a productivity multiplier. ③ **Formatting** consistency makes diffs readable. |
| 7 | **hot reload** | /hɒt riːˈləʊd/ | ① 热重载/热更新② 实时重载③ 即时更新 | ① **Hot reload** lets you see changes instantly without restarting. ② **Hot reload** turns a 30-second feedback loop into a 2-second loop. ③ **Hot reload** is the feature you miss most when you switch languages. |
| 8 | **REPL** | /repəl/ | ① 交互式解释器/REPL环境② 读-求值-输出循环③ 命令行交互 | ① The Python **REPL** is great for quick experiments. ② A good **REPL** is worth a thousand lines of documentation. ③ **REPL**-driven development is a legitimate workflow in Lisp. |
| 9 | **debugger** | /diːˈbʌɡə/ | ① 调试器/除错工具② 纠错程序③ 排错器 | ① The **debugger** found the race condition in five minutes. ② print() is a poor man's **debugger**. ③ A time-travel **debugger** lets you step backward through execution. |
| 10 | **profiler** | /ˈprəʊfaɪlə/ | ① 性能分析器/剖析器② 分析工具③ 特征提取器 | ① The **profiler** showed that 80% of time was spent in one function. ② A **profiler** tells you where to optimize—guessing is expensive. ③ Run the **profiler** before and after every optimization. |
| 11 | **CI/CD** | /siː aɪ siː diː/ | ① 持续集成/持续交付② CI/CD管道③ 自动化发布 | ① The **CI/CD** pipeline deploys every commit to staging. ② **CI/CD** is not a tool—it's a practice. ③ A broken **CI/CD** pipeline is the #1 thing to fix. |
| 12 | **artifact** | /ˈɑːtɪfækt/ | ① 构建产物/工件② 人工制品③ 物证 | ① The Docker image is the deployable **artifact**. ② Every CI run produces an immutable **artifact**. ③ The **artifact** repository stores every version ever built. |
| 13 | **registry** | /ˈredʒɪstri/ | ① 注册表/注册中心② 登记处③ 仓库 | ① The container **registry** holds all Docker images. ② The npm **registry** hosts millions of packages. ③ A private **registry** is required for proprietary artifacts. |
| 14 | **orchestration** | /ˌɔːkɪˈstreɪʃən/ | ① 编排/协调② 统筹③ 管弦乐编曲 | ① Kubernetes handles container **orchestration**. ② Release **orchestration** coordinates deployments across services. ③ The **orchestration** layer is the most complex part of the platform. |
| 15 | **observability** | /əbˌzɜːvəˈbɪlɪti/ | ① 可观测性/可观察性② 系统观测③ 监控可见性 | ① **Observability** goes beyond monitoring—it's about understanding unknown unknowns. ② The three pillars of **observability**: logs, metrics, and traces. ③ **Observability** without actionability is just noise. |
| 16 | **telemetry** | /tɪˈlemɪtri/ | ① 遥测/远程测量② 遥测数据③ 远程监控 | ① **Telemetry** data feeds the observability platform. ② Privacy-preserving **telemetry** collects only what's needed. ③ The spacecraft's **telemetry** stream provided real-time diagnostics. |
| 17 | **tracing** | /ˈtreɪsɪŋ/ | ① 链路追踪/请求追踪② 跟踪③ 描绘 | ① Distributed **tracing** follows a request across microservices. ② **Tracing** shows where latency accumulates. ③ Without **tracing**, debugging a distributed system is guesswork. |
| 18 | **logging** | /ˈlɒɡɪŋ/ | ① 日志记录/日志② 记录③ 伐木 | ① Structured **logging** makes logs queryable. ② **Logging** everything is cheap; finding the signal is hard. ③ **Logging** levels—DEBUG, INFO, WARN, ERROR—should be used consistently. |
| 19 | **metrics** | /ˈmetrɪks/ | ① 指标/度量② 测量标准③ 数据指标 | ① The four golden **metrics**: latency, traffic, errors, saturation. ② **Metrics** tell you that something is wrong; logs tell you what. ③ Alert on **metrics**, not on logs. |
| 20 | **dashboard** | /ˈdæʃbɔːd/ | ① 仪表板/数据看板② 控制面板③ 信息展示屏 | ① The on-call **dashboard** shows real-time system health. ② A **dashboard** that takes 10 seconds to load is useless in an incident. ③ Every **dashboard** should answer one question well. |
| 21 | **alert** | /əˈlɜːt/ | ① n.告警/警报② v.警告③ adj.警觉的 | ① An **alert** that fires every night becomes noise. ② Every **alert** should require human action—otherwise it should be automated. ③ **Alert** fatigue is a leading cause of missed incidents. |
| 22 | **runbook automation** | /ˈrʌnbʊk ˌɔːtəˈmeɪʃən/ | ① 操作手册自动化② 自动修复③ 运维自动化 | ① **Runbook automation** executes the fix before a human even wakes up. ② The best alert is one that's handled by **runbook automation**. ③ **Runbook automation** reduces mean time to resolution from hours to minutes. |
| 23 | **IaC** | /aɪ eɪ siː/ | ① 基础设施即代码② 代码化基础设施③ IaC | ① Terraform is the dominant **IaC** tool. ② **IaC** makes infrastructure reproducible and reviewable. ③ **IaC** without version control is just scripts. |
| 24 | **GitOps** | /ɡɪt ɒps/ | ① Git运维/Git操作② 基于Git的运维③ GitOps | ① **GitOps** means Git is the single source of truth for infrastructure. ② In **GitOps**, a merge to main triggers a deployment. ③ **GitOps** extends CI/CD to infrastructure. |
| 25 | **feature flag** | /ˈfiːtʃə flæɡ/ | ① 功能开关/特性标志② 功能切换器③ 特性标记 | ① **Feature flags** decouple deployment from release. ② A **feature flag** turns every launch into a canary. ③ **Feature flags** that live forever become technical debt. |
| 26 | **canary** | /kəˈneəri/ | ① 金丝雀发布/灰度发布② 预警③ 试探 | ① The **canary** deployment routes 5% of traffic to the new version. ② If the **canary** is healthy for an hour, roll out to 100%. ③ The **canary** caught the memory leak before it affected all users. |
| 27 | **rollback** | /ˈrəʊlbæk/ | ① 回滚/回退② 撤销部署③ 还原 | ① A **rollback** should be a one-click operation. ② If **rollback** takes longer than deploy, you're doing it wrong. ③ The **rollback** was triggered automatically when error rates spiked. |
| 28 | **incident** | /ˈɪnsɪdənt/ | ① 事故/事件② 故障③ 意外事件 | ① Every **incident** is a learning opportunity. ② The **incident** commander coordinates the response. ③ An **incident** that repeats is a failure of the postmortem process. |
| 29 | **Sev** | /sev/ | ① 严重级别/事故等级② 严重性③ 优先级 | ① A **Sev-1** incident means the entire service is down. ② The **Sev** level determines the response SLA. ③ Don't declare **Sev-1** lightly—it mobilizes the entire on-call org. |
| 30 | **code review** | /kəʊd rɪˈvjuː/ | ① 代码审查/代码评审② 代码复查③ 代码审阅 | ① **Code review** is the last line of defense before production. ② A good **code review** asks why, not just what. ③ **Code review** is a conversation, not an inspection. |
| 31 | **pair programming** | /peə ˈprəʊɡræmɪŋ/ | ① 结对编程② 双人编程③ 协同编程 | ① **Pair programming** reduces bugs and spreads knowledge. ② **Pair programming** full-time is exhausting—use it deliberately. ③ Remote **pair programming** requires good tooling and a willingness to collaborate. |
| 32 | **mob programming** | /mɒb ˈprəʊɡræmɪŋ/ | ① 群体编程/集体编程② 多人编程③ 协作编程 | ① **Mob programming** puts the entire team on one problem. ② **Mob programming** is extreme but effective for hard problems. ③ **Mob programming** works best for onboarding and complex refactors. |
| 33 | **TDD** | /tiː diː diː/ | ① 测试驱动开发② 先写测试再写代码③ TDD | ① **TDD** means writing the test before the implementation. ② **TDD** is a design practice, not a testing practice. ③ Red, green, refactor—that's the **TDD** cycle. |
| 34 | **unit test** | /ˈjuːnɪt test/ | ① 单元测试② 单位测试③ 组件测试 | ① A **unit test** verifies a single function in isolation. ② **Unit tests** are fast but don't catch integration bugs. ③ Write **unit tests** for logic, not for getters and setters. |
| 35 | **integration test** | /ˌɪntɪˈɡreɪʃən test/ | ① 集成测试/整合测试② 综合测试③ 联合测试 | ① **Integration tests** verify that components work together. ② **Integration tests** are slower but more realistic than unit tests. ③ The **integration test** caught the serialization mismatch. |
| 36 | **end-to-end test** | /end tə end test/ | ① 端到端测试/全链路测试② 全面测试③ E2E测试 | ① **End-to-end tests** simulate real user journeys. ② **E2E tests** are the most expensive to maintain. ③ An **E2E test** that fails intermittently is worse than no test. |
| 37 | **flaky test** | /ˈfleɪki test/ | ① 不稳定测试/随机失败测试② 不靠谱的测试③ 偶发性失败测试 | ① A **flaky test** that passes and fails randomly destroys trust in CI. ② **Flaky tests** should be fixed or deleted—there's no third option. ③ The **flaky test** problem got so bad that engineers started ignoring CI failures. |
| 38 | **code coverage** | /kəʊd ˈkʌvərɪdʒ/ | ① 代码覆盖率② 测试覆盖率③ 代码覆盖 | ① **Code coverage** measures which lines are executed by tests. ② 100% **code coverage** doesn't mean 100% correctness. ③ **Code coverage** is a floor, not a ceiling—it tells you what's NOT tested. |
| 39 | **mocking** | /ˈmɒkɪŋ/ | ① 模拟/打桩② 嘲笑③ 模仿 | ① **Mocking** external services isolates the code under test. ② Over-**mocking** creates tests that pass but don't verify real behavior. ③ **Mocking** is a code smell—consider whether you need a real integration test. |
| 40 | **GitHub Actions** | /ˈɡɪthʌb ˈækʃənz/ | ① GitHub的CI/CD平台② GitHub自动化③ GitHub工作流 | ① **GitHub Actions** runs CI on every push. ② The **GitHub Actions** workflow file defines the CI pipeline. ③ **GitHub Actions** marketplace has thousands of pre-built actions. |
| 41 | **monorepo** | /ˈmɒnəʊriːpəʊ/ | ① 单体仓库/单仓库② 统一代码库③ 大仓 | ① Google uses a **monorepo** for all its code. ② A **monorepo** simplifies dependency management but requires investment in tooling. ③ **Monorepo** vs. polyrepo is a tradeoff, not a religion. |
| 42 | **merge conflict** | /mɜːdʒ ˈkɒnflɪkt/ | ① 合并冲突② 融合冲突③ 代码合并冲突 | ① **Merge conflicts** are a sign that communication failed. ② Resolving a **merge conflict** is the most dangerous moment in Git. ③ Frequent integration reduces **merge conflicts**. |
| 43 | **technical debt** | /ˈteknɪkəl det/ | ① 技术债务② 技术欠账③ 代码质量欠账 | ① **Technical debt** is any code that's more expensive to change than it should be. ② **Technical debt** is not always bad—it can be a deliberate tradeoff. ③ The interest on **technical debt** is paid in slower development velocity. |
| 44 | **bikeshedding** | /ˈbaɪkʃedɪŋ/ | ① 鸡毛蒜皮的争论② 无关细节的纠结③ 浪费时间讨论琐事 | ① The team spent an hour **bikeshedding** the folder structure. ② **Bikeshedding** happens because trivial things are easy to have opinions about. ③ Automate the trivial to eliminate **bikeshedding**. |
| 45 | **YAGNI** | /ˈjæɡni/ | ① 你不需要它/不要过度设计② 不需要原则③ 按需开发 | ① **YAGNI**: You Aren't Gonna Need It—don't build features you don't need yet. ② **YAGNI** is the antidote to speculative generality. ③ **YAGNI** doesn't mean "never plan"—it means "don't build for hypothetical futures." |
| 46 | **KISS** | /kɪs/ | ① 保持简单原则/简约设计② 简易原则③ 简洁至上 | ① **KISS**: Keep It Simple, Stupid—complexity is the enemy. ② **KISS** is the principle behind every great design. ③ **KISS** is easy to say, hard to do. |
| 47 | **DRY** | /draɪ/ | ① 不要重复/避免重复② 单一原则③ 复用原则 | ① **DRY**: Don't Repeat Yourself—every piece of knowledge should have one canonical representation. ② **DRY** applied too aggressively creates coupling. ③ Sometimes a little duplication (**WET**—Write Everything Twice) is better than the wrong abstraction. |
| 48 | **SOLID** | /ˈsɒlɪd/ | ① SOLID设计原则② 面向对象五原则③ 软件设计原则 | ① **SOLID** principles guide object-oriented design. ② The Single Responsibility Principle—the S in **SOLID**—applies to services too. ③ **SOLID** principles are guidelines, not laws. |
| 49 | **design pattern** | /dɪˈzaɪn ˈpætən/ | ① 设计模式/设计范式② 设计模式论③ 程式设计规范 | ① The repository pattern is a common **design pattern** for data access. ② **Design patterns** are solutions to recurring problems, not templates to copy. ③ Knowing **design patterns** helps you recognize problems you've seen before. |
| 50 | **anti-pattern** | /ˈænti ˈpætən/ | ① 反模式/不良模式② 常见错误模式③ 反面典范 | ① The God Object is a classic **anti-pattern**. ② **Anti-patterns** are patterns that look right but produce bad outcomes. ③ Recognizing **anti-patterns** is more valuable than memorizing patterns. |

---

### Group 6/6: Career Growth & Professional Development（职业成长与专业发展）

| # | Word | Pronunciation | Meanings | Example Sentences |
|---|------|--------------|----------|-------------------|
| 1 | **trajectory** | /trəˈdʒektəri/ | ① 职业轨迹/发展路线② 轨道③ 路径 | ① My career **trajectory** shifted from IC to management. ② The startup's growth **trajectory** was unsustainable. ③ A **trajectory** is shaped by deliberate choices, not luck. |
| 2 | **upskill** | /ʌpˈskɪl/ | ① v.提升技能/学习新技能② 提高技术③ 进阶学习 | ① The engineer **upskilled** by learning Rust on weekends. ② Companies should invest in **upskilling** existing employees, not just hiring. ③ **Upskill** in the direction the industry is heading. |
| 3 | **reskill** | /riːˈskɪl/ | ① v.重新培训/技能转型② 学习全新技能③ 转行培训 | ① The QA engineer **reskilled** as a data engineer. ② AI may require millions of workers to **reskill**. ③ **Reskilling** is harder than upskilling—it means starting over. |
| 4 | **pivot** | /ˈpɪvət/ | ① v/n.转型/转向② 转变③ 调整 | ① She **pivoted** from backend engineering to developer relations. ② A career **pivot** is not a failure—it's a response to learning. ③ The best **pivots** build on existing skills in a new context. |
| 5 | **IC track** | /aɪ siː træk/ | ① 个人贡献者路线/技术路线② IC晋升通道③ 技术专家方向 | ① The **IC track** lets you grow without becoming a manager. ② A strong **IC track** retains engineers who don't want to manage. ③ The **IC track** should go as high as the management track. |
| 6 | **staff engineer** | /stɑːf ˌendʒɪˈnɪə/ | ① 资深工程师/高级技术专家② 主任工程师③ 技术主管 | ① The **staff engineer** operates across multiple teams. ② A **staff engineer**'s impact is measured in team multipliers, not lines of code. ③ The path to **staff engineer** is about scope, not tenure. |
| 7 | **principal engineer** | /ˈprɪnsɪpəl ˌendʒɪˈnɪə/ | ① 首席工程师/技术带头人② 主任工程师③ 技术导师 | ① The **principal engineer** sets technical direction for the entire org. ② A **principal engineer** is a force multiplier—they make everyone around them better. ③ There are fewer **principal engineers** than VPs for a reason. |
| 8 | **distinguished engineer** | /dɪˈstɪŋɡwɪʃt ˌendʒɪˈnɪə/ | ① 杰出工程师/院士级工程师② 特级工程师③ 荣誉工程师 | ① The **distinguished engineer** title is reserved for the top ~0.1% of engineers. ② A **distinguished engineer** influences the entire industry, not just the company. ③ **Distinguished engineer** is a title earned over decades. |
| 9 | **fellow** | /ˈfeləʊ/ | ① 院士/会士② 研究员③ 同事 | ① She was named an ACM **Fellow** for her contributions to cryptography. ② A **Fellow** at a tech company is the highest individual contributor title. ③ The **Fellow** program recognizes technical achievement at the highest level. |
| 10 | **tech lead** | /tek liːd/ | ① 技术负责人/技术组长② 技术带头人③ 技术主管 | ① The **tech lead** is responsible for the team's technical decisions. ② A **tech lead** is still hands-on—they code, review, and architect. ③ The **tech lead** role is the first step beyond senior engineer. |
| 11 | **engineering manager** | /ˌendʒɪˈnɪərɪŋ ˈmænɪdʒə/ | ① 工程经理/技术经理② 研发经理③ 工程管理 | ① The **engineering manager** focuses on people, process, and delivery. ② An **EM** who doesn't shield their team from distractions isn't doing their job. ③ The transition from IC to **EM** is a career change, not a promotion. |
| 12 | **CTO** | /siː tiː əʊ/ | ① 首席技术官/技术总监② CTO③ 技术负责人 | ① The **CTO** sets the technical vision for the entire company. ② A startup **CTO** writes code; an enterprise **CTO** writes strategy. ③ The **CTO** role changes more than any other as the company grows. |
| 13 | **VP of Engineering** | /viː piː əv ˌendʒɪˈnɪərɪŋ/ | ① 工程副总裁/研发副总裁② 技术VP③ 工程副总裁 | ① The **VP of Engineering** manages the engineering managers. ② A great **VPE** creates an environment where engineers do their best work. ③ The **VPE** is responsible for delivery, culture, and hiring. |
| 14 | **resume** | /ˈrezjʊmeɪ/ | ① 简历/履历② 摘要③ 经历 | ① A good **resume** shows impact, not just responsibilities. ② Your **resume** should tell a story, not list tasks. ③ The best **resume** is a trail of public work—code, writing, speaking. |
| 15 | **portfolio** | /pɔːtˈfəʊliəʊ/ | ① 作品集/投资组合② 文件夹③ 代表作 | ① A GitHub **portfolio** speaks louder than a resume. ② A **portfolio** of side projects shows what you care about. ③ Your **portfolio** is your career's proof of work. |
| 16 | **networking** | /ˈnetwɜːkɪŋ/ | ① 社交/人脉建设② 建立关系网③ 网络连接 | ① **Networking** is not about collecting contacts—it's about building relationships. ② The best time for **networking** is when you don't need anything. ③ Open-source contribution is the most authentic form of **networking** for engineers. |
| 17 | **personal brand** | /ˈpɜːsənəl brænd/ | ① 个人品牌/个人形象② 个人声誉③ 个人标识 | ① Your **personal brand** is what people say about you when you're not in the room. ② A **personal brand** built on genuine expertise is unshakeable. ③ Writing and speaking build your **personal brand** faster than anything else. |
| 18 | **elevator pitch** | /ˈelɪveɪtə pɪtʃ/ | ① 电梯演讲/简短介绍② 30秒自我介绍③ 快速陈述 | ① Your **elevator pitch** should explain who you are and what you do in 30 seconds. ② Every engineer should have an **elevator pitch** for their current project. ③ The **elevator pitch** for the RFC convinced the CTO in two minutes. |
| 19 | **negotiation** | /nɪˌɡəʊʃiˈeɪʃən/ | ① 谈判/协商② 交涉③ 议价 | ① Salary **negotiation** is a skill every engineer should learn. ② **Negotiation** is not about winning—it's about finding a deal both sides can live with. ③ The best **negotiation** is based on data, not demands. |
| 20 | **counteroffer** | /ˈkaʊntərˌɒfə/ | ① 还价/反报价② 对方报价③ 回应报价 | ① The **counteroffer** was 20% higher than the original. ② Accepting a **counteroffer** from your current employer rarely works out long-term. ③ Always get the **counteroffer** in writing. |
| 21 | **equity** | /ˈekwɪti/ | ① 股权/股票② 公平③ 资产净值 | ① The startup offered 0.5% **equity** as part of the compensation package. ② **Equity** in a startup is a lottery ticket—don't count it as salary. ③ Understand your **equity** vesting schedule before signing. |
| 22 | **vesting** | /ˈvestɪŋ/ | ① 归属/授予② 赋予权利③ 逐步获得 | ① The standard **vesting** schedule is four years with a one-year cliff. ② Options start **vesting** after the cliff period. ③ If you leave before **vesting**, you forfeit unvested equity. |
| 23 | **cliff** | /klɪf/ | ① 悬崖/归属期临界点② 陡崖③ 分界线 | ① The one-year **cliff** means no equity vests until your first anniversary. ② If you leave before the **cliff**, you walk away with nothing. ③ The **cliff** protects the company from short-term hires taking equity. |
| 24 | **sabbatical** | /səˈbætɪkəl/ | ① 长假/学术休假② 休假期③ 学术假 | ① The company offers a six-week **sabbatical** after five years of service. ② Taking a **sabbatical** to learn a new skill can accelerate your career. ③ A **sabbatical** is not a vacation—it's time for exploration and renewal. |
| 25 | **conference** | /ˈkɒnfərəns/ | ① 会议/技术大会② 研讨会③ 协商会 | ① Speaking at a **conference** is the fastest way to build credibility. ② The **conference** hallway track is more valuable than the talks. ③ Choose one **conference** a year and go deep—don't scatter your attention. |
| 26 | **meetup** | /ˈmiːtʌp/ | ① 行业聚会/技术交流会② 见面会③ 小聚会 | ① The local Rust **meetup** has 500 members. ② **Meetups** are lower-pressure than conferences for networking. ③ Organizing a **meetup** builds leadership skills and community. |
| 27 | **speaker** | /ˈspiːkə/ | ① 演讲者/发言人② 讲者③ 演说家 | ① Becoming a **speaker** at conferences opens doors you didn't know existed. ② Every **speaker** started as someone who was terrified of public speaking. ③ A good **speaker** tells a story, not a slide deck. |
| 28 | **thought leadership** | /θɔːt ˈliːdəʃɪp/ | ① 思想领导力/意见领袖② 思想领袖③ 专业影响力 | ① **Thought leadership** is not about being loud—it's about being insightful. ② The best **thought leadership** comes from doing, not speculating. ③ Blogging about hard problems you've solved is a form of **thought leadership**. |
| 29 | **side project** | /saɪd ˈprɒdʒekt/ | ① 业余项目/副业项目② 小项目③ 兴趣项目 | ① The best **side projects** solve a problem you personally have. ② A **side project** is a playground for learning without deadlines. ③ Her **side project** became the company's main product. |
| 30 | **open source contribution** | /ˈəʊpən sɔːs ˌkɒntrɪˈbjuːʃən/ | ① 开源贡献② 开源参与③ 开源社区贡献 | ① An **open source contribution** is the best resume item for an engineer. ② Start with documentation **contributions**—they're always needed. ③ Consistent small **contributions** are better than one big PR that never ships. |
| 31 | **mentor** | /ˈmentɔː/ | ① n.导师/指导者② v.指导③ n.顾问 | ① A good **mentor** asks questions, not gives answers. ② Everyone needs a **mentor**—and everyone can be a **mentor**. ③ Find a **mentor** who is two steps ahead, not ten—their advice will be more relevant. |
| 32 | **mentee** | /menˈtiː/ | ① 被指导者/学员② 徒弟③ 受指导者 | ① A good **mentee** comes to meetings with specific questions. ② Being a **mentee** is an active role—you drive the relationship. ③ The best **mentees** make their mentors better. |
| 33 | **sponsor** | /ˈspɒnsə/ | ① n.推举人/支持者② v.赞助③ n.担保人 | ① A **sponsor** advocates for you when you're not in the room. ② Mentors give advice; **sponsors** give opportunities. ③ You can't ask someone to be your **sponsor**—you earn it through excellent work. |
| 34 | **peer** | /pɪə/ | ① 同侪/同级同事② 同等的人③ 同伴 | ① Your **peers** are your most honest source of feedback. ② **Peer** review improves both the reviewer and the reviewed. ③ A culture of **peer** feedback is a competitive advantage. |
| 35 | **feedback culture** | /ˈfiːdbæk ˈkʌltʃə/ | ① 反馈文化/反馈氛围② 反馈机制③ 评价文化 | ① A healthy **feedback culture** makes feedback normal, not scary. ② **Feedback culture** starts with leaders modeling how to receive criticism. ③ Radical candor is the goal of **feedback culture**—challenge directly, care personally. |
| 36 | **radical candor** | /ˈrædɪkəl ˈkændə/ | ① 彻底坦诚/绝对坦率② 激进的坦率③ 直接且关怀 | ① **Radical candor** means challenging directly while caring personally. ② **Radical candor** without caring is just obnoxious aggression. ③ The best code reviews practice **radical candor**—honest and kind. |
| 37 | **imposter syndrome** | /ɪmˈpɒstə ˈsɪndrəʊm/ | ① 冒名顶替综合征/冒充者恐惧② 自我怀疑感③ 自我否定 | ① **Imposter syndrome** tells you that you don't belong—and it lies. ② Most senior engineers have experienced **imposter syndrome** at some point. ③ **Imposter syndrome** is most common among high achievers who know how much they don't know. |
| 38 | **Dunning-Kruger** | /ˈdʌnɪŋ ˈkruːɡə/ | ① 达克效应/自信过度② 认知偏差③ 能力与自信的错位 | ① The **Dunning-Kruger** effect: the least competent are the most confident. ② Be aware of **Dunning-Kruger** when you think something looks easy. ③ The antidote to **Dunning-Kruger** is continuous feedback and measurement. |
| 39 | **growth mindset** | /ɡrəʊθ ˈmaɪndset/ | ① 成长型思维/成长心态② 进步心态③ 发展思维 | ① A **growth mindset** sees challenges as opportunities to learn. ② "I'm not good at this yet" is **growth mindset**; "I'm bad at this" is fixed. ③ Hiring for **growth mindset** predicts success better than hiring for specific skills. |
| 40 | **deliberate practice** | /dɪˈlɪbərət ˈpræktɪs/ | ① 刻意练习/有目的的练习② 精心练习③ 专注训练 | ① **Deliberate practice** means working on specific weaknesses, not just repeating what you know. ② Ten years of experience is not the same as one year of **deliberate practice** repeated ten times. ③ **Deliberate practice** is uncomfortable—that's how you know it's working. |
| 41 | **T-shaped** | /tiː ʃeɪpt/ | ① T型人才/多能专一② 横向视野纵向深度③ T型技能 | ① A **T-shaped** engineer has broad knowledge across many areas and deep expertise in one. ② **T-shaped** skills make you adaptable while still having a spike. ③ The **T-shaped** model is the ideal for modern engineering teams. |
| 42 | **specialization** | /ˌspeʃəlaɪˈzeɪʃən/ | ① 专业化/专门化② 专长③ 特长 | ① Early in your career, breadth beats **specialization**. ② **Specialization** increases your value but reduces your options. ③ The best **specialization** is one you'd do for free. |
| 43 | **generalist** | /ˈdʒenərəlɪst/ | ① 通才/多面手② 全能型人才③ 通晓多领域者 | ① A **generalist** thrives in ambiguity and connects dots across domains. ② Startups need **generalists**; large companies need specialists. ③ The best architects are **generalists** with a few deep specialties. |
| 44 | **polyglot** | /ˈpɒlɪɡlɒt/ | ① n.多语言者/通晓多国语言者② adj.多语言的③ n.多语种程序员 | ① A programming **polyglot** is comfortable in multiple languages and paradigms. ② Being a **polyglot** engineer makes you adaptable to any stack. ③ A true **polyglot** doesn't just know the syntax—they know the idioms. |
| 45 | **full-stack** | /fʊl stæk/ | ① 全栈的/全方面的② 全栈开发③ 全方位的 | ① A **full-stack** engineer works on frontend, backend, and infrastructure. ② **Full-stack** doesn't mean equally good at everything—it means not blocked by anything. ③ The **full-stack** engineer myth: nobody is actually great at everything. |
| 46 | **remote-first** | /rɪˈməʊt fɜːst/ | ① 远程优先的② 以远程工作为主的③ 远程文化 | ① The company is **remote-first**—even office employees work like they're remote. ② **Remote-first** means async-first and documentation-first. ③ **Remote-first** is a different philosophy from remote-friendly. |
| 47 | **digital literacy** | /ˈdɪdʒɪtəl ˈlɪtərəsi/ | ① 数字素养/数字能力② 数字技能③ 科技素养 | ① **Digital literacy** is as important as traditional literacy in the modern workplace. ② **Digital literacy** goes beyond using tools—it's understanding how they work. ③ The **digital literacy** gap is the new inequality. |
| 48 | **lifelong learning** | /ˈlaɪflɒŋ ˈlɜːnɪŋ/ | ① 终身学习/持续学习② 终生学习③ 持续进修 | ① The half-life of technical skills is about five years—**lifelong learning** is not optional. ② A culture of **lifelong learning** retains engineers longer. ③ **Lifelong learning** is a mindset, not a checklist. |
| 49 | **sabbatical** | /səˈbætɪkəl/ | ① 长假/学术休假② 进修假③ 公休假 | ① After seven years, she took a six-month **sabbatical** to travel and write. ② A **sabbatical** can prevent burnout before it starts. ③ Tech companies are increasingly offering **sabbaticals** as a retention tool. |
| 50 | **exit interview** | /ˈeksɪt ˈɪntəvjuː/ | ① 离职面谈/离职访谈② 退职面试③ 离职调查 | ① The **exit interview** revealed that the real reason for leaving was lack of growth. ② **Exit interviews** tell you what engagement surveys can't. ③ An **exit interview** is too late—the time to listen was six months ago. |

---

## 4. Sentence-Making Practice（造句练习）

### Instructions

Translate the following 10 Chinese prompts into English. Each prompt requires precise grammar from all 6 months of learning. Write your answer before comparing with the reference.

---

**1. 回顾我过去五个月的英语学习——从句子的基本骨架，到各种时态、语态，到三大从句，到非限定动词和虚拟语气，到倒装和强调——我发现最有效的学习方法不是背诵规则，而是把每一个复杂句子当作一个拼图来拆解，搞清楚每一个词的句法角色。**

Reference:

> Looking back on my past five months of English learning—from basic sentence skeletons, to various tenses and voices, to the three clause types, to non-finite verbs and the subjunctive, to inversion and emphasis—I have found that the most effective way to learn is not to memorize rules, but rather to treat every complex sentence as a puzzle to be dissected, figuring out the syntactic role of every single word.

Key structures:
- **Non-finite verbs**: Looking back, figuring out (分词短语)
- **A chain of "from...to"**: parallel structure with prepositions
- **Present perfect**: I have found
- **Emphasis**: every single word
- **Article precision**: the most effective way (最高级), a puzzle (泛指), the syntactic role (特指)

---

**2. 正是因为我在拆解句子时从来不只是看整体意思，而是逐词追问"这个词做什么成分？""这个介词为什么是 in 而不是 at？""这个冠词为什么是 a 而不是 the？"——正是这种近乎偏执的精确性，才让我逐渐建立起了对英语句法的一种直觉。**

Reference:

> It is precisely because I never just look at the overall meaning when dissecting a sentence but instead ask word by word—"What role does this word play?" "Why is the preposition in rather than at?" "Why is the article a rather than the?"—it is precisely this almost obsessive precision that has gradually helped me build an intuition for English syntax.

Key structures:
- **Emphasis**: It is precisely because...that... (强调原因状语)
- **Inversion/Embedded questions**: What role does this word play?
- **Articles**: the overall meaning (特指), a sentence (泛指), the preposition (特指), an intuition (泛指)
- **Prepositions**: for English syntax (for = 对…而言), at (vs. in)

---

**3. 要不是我在第一个月花了两周时间专门攻克了关系从句的嵌套结构——特别是那种一个 that 套一个 that 再套一个 that 的句子——后面学非限定动词和虚拟语气的时候我肯定会完全卡住。**

Reference:

> Had I not spent two weeks in the first month specifically tackling the nested structure of relative clauses—especially those sentences in which one that clause wraps around another that clause which in turn wraps around yet another that—I would certainly have been completely stuck later when learning non-finite verbs and the subjunctive mood.

Key structures:
- **Inversion (conditional)**: Had I not spent... (条件虚拟倒装)
- **Relative clauses nested**: those sentences in which one that...which in turn...that
- **Subjunctive**: I would have been stuck (Type 3 conditional)
- **Articles**: the first month (序数词), the nested structure (特指), the subjunctive mood (独一无二)

---

**4. 我写代码有个习惯，这个习惯是我从学英语中迁移过来的：不只是让代码跑得通，还要让代码的结构"读起来像一句好英文"——主逻辑是主句，分支是关系从句，错误处理是条件状语，而每一个函数名都像一个精确选择的介词那样，告诉你它连接的是什么。**

Reference:

> I have a habit in coding that I've carried over from learning English: don't just make the code work—make its structure "read like a good English sentence." The main logic is the main clause; branches are relative clauses; error handling is the conditional adverbial; and every function name, like a precisely chosen preposition, tells you what it connects.

Key structures:
- **Metaphor through grammar**: code structure = sentence structure
- **Articles**: a habit (泛指), the main clause (特指), a precisely chosen preposition (泛指)
- **Like + noun**: like a precisely chosen preposition
- **Parallel structure**: main logic = main clause; branches = relative clauses; error handling = conditional

---

**5. 在我面试远程公司的时候，有一轮是让我现场拆解一段来自 Linux 内核邮件列表的技术英语长句——让我在两分钟之内找到主谓宾、识别每一个从句、解释每一个介词短语修饰的是谁。我过了这一轮，很大程度上就是因为这五个月的训练。**

Reference:

> When I interviewed with a remote-first company, one round had me dissect, on the spot, a long technical English sentence from the Linux kernel mailing list—I had to find the subject, verb, and object within two minutes, identify every clause, and explain what each prepositional phrase modified. I passed that round, in large part, because of these five months of training.

Key structures:
- **Infinitive**: had me dissect... (have someone do something)
- **Prepositions**: on the spot, within two minutes, in large part, because of
- **Articles**: a remote-first company (泛指), the Linux kernel mailing list (特指), the subject (特指)
- **Complex object chain**: find X, identify Y, and explain Z (三个并列不定式)
- **Article precision**: these five months of training (特指 this training)

---

**6. 现在回头看那些曾经让我感到恐惧的句子——比如一篇 Stratum 论文的摘要，或者 Google Bigtable 论文里那些一段话只有一句话的怪物——我发现我不再像以前那样看到第三行就放弃了。现在我知道：先找主句，再分层拆解，最终每一个句子都会被拆成一张清晰的结构图。**

Reference:

> Looking back now at the sentences that used to terrify me—the abstract of a Stratum paper, for instance, or those monsters in the Google Bigtable paper where an entire paragraph is a single sentence—I find that I no longer give up by the third line the way I used to. Now I know: find the main clause first, then peel back the layers, and eventually every sentence will be broken down into a clear structural diagram.

Key structures:
- **Non-finite**: Looking back (分词短语)
- **Relative clause**: the sentences that used to terrify me; where an entire paragraph is a single sentence
- **The way + clause**: the way I used to (方式状语从句)
- **Articles**: a Stratum paper (泛指), a single sentence (泛指 — 但 single 强调一整个), a clear structural diagram (泛指)
- **Peel back**: phrasal verb (剥开/分层)

---

**7. 说真的，最让我惊讶的甚至不是我能读懂复杂句子了——最让我惊讶的是，写英文的时候，我现在会自然而然地在脑子里问自己："这个名词是要泛指还是特指？""这个动词和它后面的介词是不是固定搭配？""这里要不要倒装来增强语气？"这些问题在我脑子里自动跳出来，已经不需要刻意提醒自己了。**

Reference:

> Honestly, what has surprised me most is not even that I can now read complex sentences—what has surprised me most is that, when writing in English, I now naturally ask myself in my head: "Is this noun meant to be general or specific?" "Is this verb and the preposition after it a fixed collocation?" "Should I use inversion here for emphasis?" These questions pop up automatically in my mind now—I no longer need to consciously remind myself.

Key structures:
- **Emphasis (What pseudo-cleft)**: what has surprised me most is...
- **Embedded questions**: Is this noun meant to be...? Should I use...?
- **Articles**: a fixed collocation (泛指), inversion (抽象名词零冠词)
- **Preposition**: for emphasis (for = 为了/表目的), in my head (固定), in my mind (固定)
- **Conscious vs. consciously**: adjective vs. adverb precision

---

**8. 上个周五，我跟我的技术主管用英文做了一次一对一的代码评审——全程没有切换回中文。虽然中间有那么两次我卡住了，在想"这个句子的 that 到底是关系从句还是名词从句"，但整体上，这是我们第一次没有因为英语问题而被打断的交流。**

Reference:

> Last Friday, I did a one-on-one code review with my tech lead entirely in English—without switching back to Chinese at any point. Although there were a couple of moments when I got stuck, wondering whether that that in the sentence was a relative clause marker or a noun clause marker, overall, it was our first conversation that was not interrupted by English-language issues.

Key structures:
- **Articles**: a one-on-one code review (泛指), my tech lead (特指), a couple of moments (泛指)
- **Without + -ing**: without switching back (介词 + 动名词)
- **Noun clause**: wondering whether that that... (whether + 完整从句; 两个 that: 第一个是 "那个 that"，第二个是关系代词/名词从句引导词)
- **Emphasis**: it was our first conversation that was not interrupted (分裂句)
- **A couple of**: 固定表达 = 几个

---

**9. 我现在回头看这六个月的学习计划，我会把它比作搭建一个编译器——Month 1-2 是词法分析（词汇和基础语法），Month 3-4 是语法分析（从句和非限定结构），Month 5-6 是代码生成和优化（精确的倒装、强调、冠词介词选择，让输出不仅是正确的，而且是地道的）。**

Reference:

> When I look back on this six-month learning plan now, I would compare it to building a compiler: Months 1-2 were lexical analysis (vocabulary and basic grammar), Months 3-4 were syntactic analysis (clauses and non-finite structures), and Months 5-6 are code generation and optimization (the precise choice of inversion, emphasis, articles, and prepositions, making the output not just correct but idiomatic).

Key structures:
- **Metaphor**: learning plan = compiler
- **Subjunctive-like comparison**: I would compare (委婉表达)
- **Articles**: a compiler (泛指), lexical analysis (抽象名词零冠词), the output (特指)
- **Not just...but...**: not just correct but idiomatic
- **Precision adjectives**: precise choice (精确的选择)
- **Parallel structure**: Months 1-2 were X, Months 3-4 were Y, Months 5-6 are Z

---

**10. 所以，如果有人问我："学了六个月英语，你最大的收获是什么？"我会这样说：我最大的收获不是学会了倒装或者虚拟语气或者 7200 个单词——我最大的收获是，当我看到一个复杂英语句子的时候，我不再害怕它了。我知道我可以拆开它，理解它，然后从中学到新的东西。而正是这种不再害怕的感觉，让我真正有勇气去申请那些纯英文工作环境的远程职位。**

Reference:

> So, if someone were to ask me, "After six months of learning English, what is your biggest takeaway?" I would say this: my biggest takeaway is not that I've learned inversion or the subjunctive or 7,200 words—my biggest takeaway is that, when I see a complex English sentence, I am no longer afraid of it. I know I can take it apart, understand it, and then learn something new from it. And it is precisely this absence of fear that has given me the real courage to apply for remote positions in purely English-speaking work environments.

Key structures:
- **Subjunctive**: if someone were to ask me...I would say (Type 2 conditional)
- **Emphasis**: it is precisely this absence of fear that has given me... (分裂句强调)
- **Noun clause**: my biggest takeaway is not that...but that... (表语从句)
- **Articles**: a complex English sentence (泛指), the subjunctive (独一无二), the real courage (特指), remote positions (复数泛指)
- **Phrasal verb**: take apart (拆开)
- **Past perfect**: I've learned (现在完成)
- **Inversion embedded**: no longer afraid (no longer = 时间上的否定)

---

## 5. Weekend Review（周末复习）

### 5.1 Independent Sentence Dissection Challenge（独立拆解挑战）

Use the four-step method to independently dissect the following sentence. Write out your analysis before checking the reference.

> "It is a truth universally acknowledged among engineers who have spent any significant amount of time maintaining production systems that a service which has never failed is not a reliable service but rather a service whose failure modes are simply unknown—and it is precisely these unknown failure modes, lurking just beyond the edge of what the monitoring covers, that constitute the greatest operational risk to any distributed system, regardless of how meticulously the architecture was designed or how thoroughly the code was reviewed."

**Step 1: Find the Main Clause**

________________________________

**Step 2: Identify Subordination** (bracket every subordinate structure)

________________________________

**Step 3: Trace the Modification Chain**

________________________________

**Step 4: Reconstruct the Logic**

________________________________

### 5.2 Vocabulary Self-Test（词汇自测）

Test yourself on 20 randomly selected words from this week's 300:

**Part A: Meaning Recall**

1. asynchronous
2. elucidate
3. sponsorship
4. disruption
5. DX (Developer Experience)
6. trajectory
7. onboarding
8. glossary
9. retention
10. observability

**Part B: Choose the Correct Word**

11. A ______ test that passes and fails randomly destroys trust in CI. (flaky / mocked / unit)
12. ______ leadership asks "how can I help you succeed?" not "why aren't you performing?" (Autocratic / Servant / Transactional)
13. The one-year ______ means no equity vests until your first anniversary. (cliff / sprint / ramp)
14. ______ means writing the test before the implementation. (BDD / TDD / FDD)
15. Being on camera all day is exhausting—______ is real. (camera fatigue / screen fatigue / zoom fatigue)
16. The engineer ______ from backend to developer relations. (pivoted / rotated / shifted — the word that means career change)
17. ______ is the most important unsolved problem in AI safety. (Hallucination / Alignment / Prompt engineering)
18. The startup has 18 months of ______ at the current burn rate. (runway / budget / capital)
19. A good engineer's ______ tells a story, not lists tasks. (resume / portfolio / bio)
20. ______ is not about being loud—it's about being insightful. (Thought leadership / Personal branding / Networking)

### 5.3 Sentence Synthesis（句子合成）

Write ONE English sentence that contains ALL of the following:
- A Type 3 conditional (past hypothetical)
- A relative clause with "whose"
- An emphatic "it is...that" structure
- At least 3 different prepositions used correctly
- Correct article choices for at least 2 abstract nouns

Your sentence:

________________________________

________________________________

________________________________

---

## 6. Weekend Review — Answers（答案）

### 6.1 Independent Sentence Dissection — Reference

**Step 1: Main Clause**

> It is a truth...that a service...is not a reliable service but rather a service...—and it is precisely these unknown failure modes...that constitute the greatest operational risk...

骨架（去掉所有从属结构和插入语）：

> It is a truth that a service is not a reliable service but rather a service—and it is these unknown failure modes that constitute the greatest operational risk.

两个分句：
1. It is a truth that A is not B but rather C (强调句型 + 对比)
2. it is precisely these unknown failure modes that constitute the greatest risk (强调句型)

**Step 2: Subordination**

```
[It is a truth
  universally acknowledged
  among engineers
    (who have spent any significant amount of time
     maintaining production systems)]
that
  [a service
    (which has never failed)]
  is not a reliable service
  but rather a service
    (whose failure modes are simply unknown)
—
and
  [it is precisely these unknown failure modes,
    lurking just beyond the edge
      (of what the monitoring covers),]
  that constitute the greatest operational risk
    to any distributed system,
    [regardless of
      (how meticulously the architecture was designed)
      or
      (how thoroughly the code was reviewed)].
```

**Step 3: Modification Chain**

```
a truth
  ← universally acknowledged (分词短语修饰 truth)
  ← among engineers (范围)
       ← who have spent time maintaining systems (定语从句)

a service
  ← which has never failed (第一层定语)
  ← whose failure modes are simply unknown (第二层定语 — 对比)

these unknown failure modes
  ← lurking just beyond the edge (分词短语 — 位置)
       ← of what the monitoring covers (of + what 从句 — 范围)

the greatest operational risk
  ← to any distributed system (to = 对…而言)
  ← regardless of how meticulously... (让步状语)
```

**Step 4: Reconstructed Logic**

作者的论点：
1. 工程师的普遍共识：从未失败过的服务不是可靠服务，而是未知故障模式的服务。
2. 正是这些未知的故障模式——潜伏在监控覆盖范围的边缘——构成了最大的运维风险。
3. 无论架构设计和代码审查多么严谨，这个风险都存在。

**Grammar highlights**:
- M1: Basic patterns — it is a truth that S + V...
- M2: Passive voice — was designed, was reviewed
- M3: Relative clauses — who have spent; which has never failed; whose failure modes...
- M4: Non-finite — lurking; maintaining
- M5: Emphasis — it is X that Y (used twice); Inversion — none directly
- M1-5: Article precision throughout

**Literary reference**: The opening parodies Jane Austen's "It is a truth universally acknowledged, that a single man in possession of a good fortune, must be in want of a wife" — applying 19th-century prose style to modern engineering wisdom.

### 6.2 Vocabulary Self-Test Answers

**Part A:**
1. asynchronous = 异步的
2. elucidate = 阐明/解释
3. sponsorship = 赞助/举荐（不同于 mentorship）
4. disruption = 颠覆/破坏性创新
5. DX = Developer Experience 开发者体验
6. trajectory = 职业轨迹/发展路线
7. onboarding = 入职/上手培训
8. glossary = 术语表/词汇表
9. retention = 保留/留存（员工留任）
10. observability = 可观测性（系统监控的高级形式）

**Part B:**
11. flaky — A **flaky** test that passes and fails randomly destroys trust in CI.
12. Servant — **Servant** leadership asks "how can I help you succeed?"
13. cliff — The one-year **cliff** means no equity vests until your first anniversary.
14. TDD — **TDD** means writing the test before the implementation.
15. camera fatigue — Being on camera all day is exhausting—**camera fatigue** is real.
16. pivoted — The engineer **pivoted** from backend to developer relations.
17. Alignment — **Alignment** is the most important unsolved problem in AI safety.
18. runway — The startup has 18 months of **runway** at the current burn rate.
19. resume — A good engineer's **resume** tells a story, not lists tasks.
20. Thought leadership — **Thought leadership** is not about being loud—it's about being insightful.

### 6.3 Sentence Synthesis — Reference Example

> Had our team invested in the kind of documentation whose value becomes apparent only after the original authors have left, it is precisely the new hires—those who were not even at the company when the code was written—that would have been spared the months of reverse-engineering that the absence of such documentation inevitably entails.

Grammar check:
- Type 3 conditional: Had our team invested...would have been spared ✓
- Relative clause with "whose": whose value becomes apparent ✓
- Emphatic "it is...that": it is precisely the new hires...that would have been spared ✓
- 3+ prepositions: in the kind; after the original authors; at the company; of reverse-engineering; of such documentation ✓
- Articles for abstract nouns: the kind (特指), ∅ documentation (泛指), the absence (特指) ✓

---

**Week 01 完成。你已经掌握了独立拆解任何英语复杂句的系统方法——先找主句，再分层剥离，再追踪修饰链，最后重建逻辑。这是五个月语法学习的"毕业考试"：你现在面对的每一个复杂句子，都同时包含了 Months 1-5 的所有语法要素，而你的任务不是辨认某一个语法点，而是在一个真实的句子中一次性处理所有语法现象。**

**下周 Week 02，我们将系统梳理中国英语学习者最常犯的 50 个错误——从冠词到介词，从时态到语序——并给出有针对性的自纠练习。错误不是敌人；错误是你进步最快的地方。**
