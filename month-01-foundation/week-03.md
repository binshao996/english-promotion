# Week 03: 一般过去时 & 过去进行时 + 团队协作词汇

> 目标：彻底掌握一般过去时和过去进行时的用法与区别，并学会 20 个最高频的团队协作词汇。本周你将学会如何用英语描述"过去发生了什么"——无论是写 postmortem、做 retro、还是汇报昨天的工作。

---

## 1. Grammar: Simple Past & Past Continuous

前两周我们学了"现在"——一般现在时描述常态，现在进行时描述此刻正在进行的事。但工作中更多时候你需要说"过去的事"：昨天发生了什么？上次上线出了什么问题？用户反馈的 bug 是什么时候引入的？这就是过去时态登场的时候了。

---

### Part A: Simple Past（一般过去时）

**核心概念：** 一般过去时描述的是"在过去的某个时间已经完成的事情"——动作已经结束，和现在没有必然联系。这是英语中最简单的"讲过去的故事"的方式。

#### 1. 核心用法

**用法 1：过去完成的动作**
描述在过去某个时间点已经做完的事。
- "I **deployed** the hotfix at 2 AM."
- "The team **released** version 3.0 last quarter."
- "She **fixed** the memory leak yesterday."

**用法 2：过去的一系列连续事件**
按时间顺序叙述过去发生的事情（像讲故事一样）。
- "I **pulled** the latest changes, **ran** the tests, and **merged** the PR."
- "He **opened** the ticket, **investigated** the root cause, and **submitted** a fix."
- "We **identified** the bottleneck, **optimized** the query, and **reduced** latency by 80%."

**用法 3：过去的习惯或状态**
描述过去经常发生的事或过去存在的状态（现在已经不这样了）。
- "We **used** Jenkins for CI, but now we use GitHub Actions."
- "The service **was** unstable during the migration period."
- "I **worked** remotely before the company opened the new office."

---

#### 2. 规则动词 -ed 的发音规则

这是一个被严重忽视但非常重要的细节。同样写 -ed，实际读音有三种不同方式。读错不会影响语法正确性，但会影响你的听力和口语的地道程度。

| 发音 | 适用条件 | 示例 |
|------|---------|------|
| **/t/** | 动词以清辅音结尾（p, k, f, s, sh, ch, x） | fi**x**ed → /fɪkst/，pu**sh**ed → /pʊʃt/，**k**issed → /kɪst/，**p**laced → /pleɪst/ |
| **/d/** | 动词以浊辅音或元音结尾（b, g, l, m, n, r, v, z 及所有元音） | deplo**y**ed → /dɪˈplɔɪd/，confi**g**ured → /kənˈfɪɡjərd/，ru**l**ed → /ruːld/，li**v**ed → /lɪvd/ |
| **/ɪd/** | 动词以 /t/ 或 /d/ 音结尾 | test**ed** → /ˈtestɪd/，implement**ed** → /ˈɪmplɪmɛntɪd/，start**ed** → /ˈstɑːrtɪd/，need**ed** → /ˈniːdɪd/ |

**快速判断口诀：**
- 结尾音是**气音**（声带不振）→ /t/：fixed, pushed, kissed, placed, finished
- 结尾音是**响音**（声带振动）→ /d/：deployed, configured, reviewed, called, lived
- 结尾音是 /t/ 或 /d/ → /ɪd/：tested, implemented, needed, started, wanted

**常见错误：**
- ❌ 把 fixed 读成 /ˈfɪksɪd/（应该是 /fɪkst/）
- ❌ 把 deployed 读成 /dɪˈplɔɪt/（应该是 /dɪˈplɔɪd/）
- ✅ 规则：看动词**原形最后一个音**，不是看字母。比如 "fixed" 的 x 读 /ks/，最后一个音是 /s/（清辅音）→ /t/

---

#### 3. 不规则动词表

英语中大约有 200 个不规则动词。好消息是，最常用的那几十个覆盖了你日常使用频率的 90% 以上。以下是开发场景中最常见的 30 个不规则动词。

| 编号 | 原形 (Base) | 过去式 (Past) | 过去分词 (Past Participle) | 中文 |
|------|------------|--------------|--------------------------|------|
| 1 | write | wrote | written | 写 |
| 2 | build | built | built | 构建 |
| 3 | send | sent | sent | 发送 |
| 4 | make | made | made | 制作/使 |
| 5 | run | ran | run | 运行 |
| 6 | take | took | taken | 拿/花费 |
| 7 | see | saw | seen | 看见 |
| 8 | give | gave | given | 给 |
| 9 | find | found | found | 找到 |
| 10 | break | broke | broken | 打破/破坏 |
| 11 | keep | kept | kept | 保持 |
| 12 | deal | dealt | dealt | 处理 |
| 13 | bring | brought | brought | 带来 |
| 14 | think | thought | thought | 认为/思考 |
| 15 | tell | told | told | 告诉 |
| 16 | speak | spoke | spoken | 说话 |
| 17 | leave | left | left | 离开/遗留 |
| 18 | lose | lost | lost | 丢失 |
| 19 | spend | spent | spent | 花费 |
| 20 | lead | led | led | 领导/导致 |
| 21 | set | set | set | 设置 |
| 22 | let | let | let | 让 |
| 23 | cut | cut | cut | 削减/剪切 |
| 24 | hit | hit | hit | 击中/达到 |
| 25 | put | put | put | 放置 |
| 26 | read | read /red/ | read /red/ | 阅读 |
| 27 | go | went | gone | 去 |
| 28 | get | got | gotten | 得到/使 |
| 29 | know | knew | known | 知道 |
| 30 | mean | meant | meant | 意味着 |

**关于过去分词的说明：** 严格来说，一般过去时只需要过去式（第二列）。过去分词用于完成时态和被动语态（将在后面的周次学习）。但现在一起记忆更高效——三列一起背。

**记忆技巧：**
- **AAA 组（三形相同）：** set-set-set, let-let-let, cut-cut-cut, hit-hit-hit, put-put-put
- **ABB 组（过去式和过去分词相同）：** build-built-built, send-sent-sent, make-made-made, find-found-found, keep-kept-kept, deal-dealt-dealt, bring-brought-brought, think-thought-thought, tell-told-told, leave-left-left, lose-lost-lost, spend-spent-spent, lead-led-led, mean-meant-meant
- **ABA 组（原形和过去分词相同）：** run-ran-run, come-came-come
- **ABC 组（三个都不相同）：** write-wrote-written, take-took-taken, see-saw-seen, give-gave-given, break-broke-broken, speak-spoke-spoken, go-went-gone, know-knew-known

---

#### 4. 否定形式

**结构：** didn't + **动词原形**

这个规则特别简单：不管主语是谁，一律用 **didn't + 动词原形**。记住：用了 didn't，后面的动词**必须还原**。

- "I **didn't deploy** yesterday."（不是 I didn't deployed）
- "We **didn't receive** any alerts."（不是 We didn't received）
- "The bug **didn't appear** in the staging environment."（不是 didn't appeared）
- "She **didn't attend** the standup this morning."（不是 didn't attended）

**常见错误：**
- ❌ "I **didn't saw** the error message."（saw 是过去式，用了 didn't 必须还原）
- ✅ "I **didn't see** the error message."（didn't + 动词原形 see）
- ❌ "The server **didn't started**."（started 是过去式，需要还原）
- ✅ "The server **didn't start**."（didn't + 动词原形 start）

**核心原理：** 在英语中，**一句话只需要一个过去标记**。did 已经是过去式了，所以后面的动词不再需要变成过去式。

---

#### 5. 疑问形式

**结构：** Did + 主语 + **动词原形** + ?

和否定一样，疑问句中用 Did 体现"过去"，后面的动词用原形。

- "**Did** you **deploy** to production last night?"
- "**Did** the tests **pass** before the merge?"
- "**What** **did** the customer **report** in the ticket?"
- "**Why** **did** the pipeline **fail**?"
- "**When** **did** you **notice** the issue?"

**Wh- 疑问句结构：** 疑问词 + did + 主语 + 动词原形 + ?
- ❌ "Why the pipeline failed?"（这是中文式直译——"为什么管道失败了？"）
- ✅ "Why **did** the pipeline **fail**?"（英语必须用 did 体现过去和疑问）

**Yes/No 简短回答：**
- "Did you deploy last night?" → "Yes, I **did**." / "No, I **didn't**."
- 注意：简短回答不要重复主要动词。"Yes, I deployed" 虽然也对，但 "Yes, I did" 更自然。

---

#### 6. 完整语法拆解示例

```
示例 1：I deployed the hotfix at 2 AM.
- I (主语/代词) + deployed (谓语/一般过去时规则变化) + the hotfix (宾语/名词短语)
  + at 2 AM (时间状语/介词短语)
- 分析：主语 "I" 发出 "deployed" 动作。"deploy" 是规则动词，加 -ed 变成过去式。
  "at 2 AM" 明确了动作发生的过去时间点。
- 理解技巧：一般过去时就像一张"已完成的照片"——事情在过去的某个时刻发生了，
  现在结束了。不管是一个小时前还是十年前，都用同样的语法结构。
- 发音注意：deployed 的 -ed 读 /d/，因为 /ɔɪ/ 是元音（浊音）→ 读 /dɪˈplɔɪd/
- 常见错误：时间状语的位置——"at 2 AM" 放在句末，而非句首。
  中文说"凌晨两点我部署了热修复"，英文通常把时间放后面。
```

```
示例 2：The CI pipeline failed because a test timed out.
- The CI pipeline (主语/名词短语) + failed (谓语/规则变化)
  + because a test timed out (原因状语从句)
- 分析：主句 "The CI pipeline failed" 是 Simple Past。从句 "a test timed out"
  也是 Simple Past——两个过去事件，一个导致另一个。
- 理解技巧：描述"过去某个事件的原因"时，原因和结果都用 Simple Past。
  fail → failed（规则变化，-ed 读 /d/）。time out → timed out（规则变化，-ed 读 /d/）。
```

```
示例 3：She wrote the unit tests after she fixed the bug.
- She (主语/代词) + wrote (谓语/不规则变化) + the unit tests (宾语/名词短语)
  + after she fixed the bug (时间状语从句)
- 分析："wrote" 是 write 的不规则过去式。两个动作按时间顺序发生——
  先修 bug，再写测试。注意：after 从句中的 fixed 是规则过去式。
- 理解技巧：叙述过去一系列事件时，每个动词都用过去式，不区分"先发生的用过去的过去"。
  那是过去完成时的活（以后学）。Simple Past 够用了——只要事件是按时间顺序叙述的。
```

```
示例 4：We didn't receive any alerts during the outage.
- We (主语/代词) + didn't receive (谓语/否定形式) + any alerts (宾语/名词短语)
  + during the outage (时间状语)
- 分析：didn't 放在动词 receive 之前，receive 保持原形（不是 received）。
  "any" 用于否定句（肯定句说 "some alerts"，否定句说 "any alerts"）。
- 理解技巧：否定+过去一定要记住"didn't + 原形"这个模式。
  不管主语是什么（I/you/he/we/they），didn't 不变，动词不变。
```

```
示例 5：Who deployed this change without testing it first?
- Who (疑问词/主语) + deployed (谓语/规则变化) + this change (宾语/名词短语)
  + without testing it first (介词短语/方式状语)
- 分析：当 "Who" 作主语时（Who + 动词），不用再加 did。
  因为 who 本身就是主语，语序是 "Who + 过去式 + 宾语"。
  对比：如果是 "Whom"（在正式英语中作宾语），则用 "Whom did + 主语 + 动词"。
- 理解技巧：Who（谁）作主语 → 动词直接变过去。What（什么）作主语也一样：
  "What caused the outage?"（不是 "What did cause"）
```

---

#### 7. 中国学生的常见错误

**错误 1：双重过去标记**
- ❌ "I **didn't deployed** the fix."（didn't 已经是过去，deploy 不能再加 -ed）
- ✅ "I **didn't deploy** the fix."
- 原因：中文说"没有部署"，没有"过去"的标记。但英语中 didn't 已经包含了"过去+否定"，后面的动词保持原形。

**错误 2：不规则动词用错形式**
- ❌ "I **writed** a script."（write 不是规则动词）
- ✅ "I **wrote** a script."
- ❌ "He **builded** a new service."
- ✅ "He **built** a new service."
- 原因：英语中有大约 200 个不规则动词，它们不遵守 -ed 规则。这是"硬记忆"，没有捷径。多做自测题是最好的方法。

**错误 3：用一般现在时描述过去事件**
- ❌ "I **deploy** the fix yesterday."（yesterday → 必须用过去时）
- ✅ "I **deployed** the fix yesterday."
- 原因：中文说"昨天部署了"，"部署"这两个字本身没变，"了"字才是过去标记。但英语的过去标记在动词形态上，出现 yesterday/last week/ago 等词就是 Simple Past 的信号。

**错误 4：疑问句中忘记用 did**
- ❌ "What time the server crashed?"（缺少助动词，语序不对）
- ✅ "What time **did** the server **crash**?"
- ❌ "Why you didn't attend the meeting?"（间接引用不算，直接问需要倒装）
- ✅ "Why **didn't you** attend the meeting?"

**错误 5：不规则动词变位记忆混乱——把过去分词当过去式用**
- ❌ "I **seen** the error."（seen 是过去分词，不能单独作谓语）
- ✅ "I **saw** the error."（saw 才是过去式）
- 关键：一般过去时只用到"过去式"这一列。过去分词（第三列）后面会用于完成时和被动语态，现在还不需要。

---

### Part B: Past Continuous（过去进行时）

**核心概念：** 过去进行时描述的是"过去某个时间正在进行的动作"。它强调的是"过程"而不是"结果"——不是说"做完了"，而是说"那时正在做"。

#### 1. 核心用法

**用法 1：过去某个时刻正在进行的动作**
强调在过去的某一具体时间点，某个动作正在进行中。
- "I **was debugging** the issue at 3 AM."
- "The server **was running** out of memory when I checked."
- "We **were having** a sprint retro at that time."

**用法 2：两个同时进行的过去动作**
描述过去两个动作同时发生，都用过去进行时。
- "While the server **was restarting**, I **was checking** the error logs."
- "The frontend team **was migrating** to React while the backend team **was refactoring** the API."
- "I **was writing** the unit tests while the build **was running**."

**用法 3：一个动作被另一个动作打断**
这是最经典的过去进行时使用场景——一个"正在进行的长动作"被一个"突然发生的短动作"打断。长动作用过去进行时，短动作用一般过去时。
- "I **was reviewing** the PR when the incident **happened**."
- "We **were testing** the feature when the database **crashed**."
- "She **was deploying** to staging when she **noticed** the misconfiguration."

---

#### 2. 形式构成

**肯定：** was / were + V-ing
- I / He / She / It **was** debugging → "I **was debugging** the issue."
- We / You / They **were** deploying → "We **were deploying** the release."

**否定：** was / were + not + V-ing
- "The server **was not responding** to health checks."
- "We **were not expecting** such a high error rate."
- 口语缩写：was not → wasn't，were not → weren't

**疑问：** Was / Were + 主语 + V-ing + ?
- "**Was** the server **running** the latest version at that time?"
- "**Were** you **working** on the authentication module yesterday afternoon?"
- "**What** **were** you **doing** when the outage occurred?"

**V-ing 拼写规则回顾：** 同现在进行时（Week 2）。
- deploy → deploying（直接加 -ing）
- debug → debugging（双写 g）
- run → running（双写 n）
- write → writing（去 e）
- make → making（去 e）
- commit → committing（双写 t）

---

#### 3. 完整语法拆解示例

```
示例 1：I was debugging a race condition at 3 AM.
- I (主语/代词) + was (be 动词过去式) + debugging (现在分词)
  + a race condition (宾语/名词短语) + at 3 AM (时间状语)
- 分析：was/were + V-ing 结构。主语 "I" → 用 "was"。"debugging" 是 debug 的现在分词。
  "at 3 AM" 指定了"过去的某个时间点"。
- 理解技巧：这句话不关心 bug 最后修好没有——它只告诉你"在那个时间点，我正在做那件事"。
  动作是"未完成"的视角。
- 常见错误：忘记 be 动词。
  ❌ "I debugging a race condition at 3 AM."（缺了 was）
  ✅ "I **was** debugging a race condition at 3 AM."
```

```
示例 2：We were migrating the database while users were still active on the site.
- We (主语/代词) + were (be 动词过去式) + migrating (现在分词)
  + the database (宾语/名词短语) + while users were still active (时间状语从句)
- 分析：主句用过去进行时 "were migrating"，描述正在进行的迁移过程。
  while 从句也是过去时态（"were still active"），表示"在用户还在活跃的时候"。
- 理解技巧：两个同时进行的动作，如果都是持续性的，都可以用过去进行时。
  这个结构在描述"做了某件事的同时另一件事也在发生"时非常有用。
- 常见错误：while 后面的动词形式——while + 主语 + be 动词 + 形容词是正确结构。
  ✅ "while users were still active"
  ❌ "while users still active"（缺了 were）
```

```
示例 3：She was deploying the hotfix when the CI pipeline failed.
- She (主语/代词) + was (be 动词过去式) + deploying (现在分词)
  + the hotfix (宾语/名词短语) + when the CI pipeline failed (时间状语从句)
- 分析：这是"长动作被打断"的经典结构。
  长动作 "was deploying"（正在进行中）→ 过去进行时
  短动作 "failed"（突然发生）→ 一般过去时
- 理解技巧：想象你在看电影——"was deploying" 是背景环境（持续的画面），
  "failed" 是突然插入的事件（砰一声）。背景用进行时，插入事件用过去时。
- 常见错误：把短动作也写成进行时。
  ❌ "She was deploying when the pipeline was failing."（failing 是过程，说"正在失败"很奇怪）
  ✅ "She was deploying when the pipeline **failed**."（failed 是瞬间发生的事件）
```

```
示例 4：While I was reviewing the PR, the author pushed a new commit.
- While I was reviewing the PR (时间状语从句) + the author (主语/名词短语)
  + pushed (谓语/一般过去时) + a new commit (宾语/名词短语)
- 分析：while 从句用过去进行时 "was reviewing"，描述"正在做 review 的过程中"。
  主句用一般过去时 "pushed"，描述在这个过程中发生的另一件事。
- 理解技巧：while 引导的从句通常是"持续背景"，主句是"插入事件"。
  while + 进行时（背景），主句 + 过去时（事件）。
- 常见错误：while 后面跟一般过去时也可以，但是意思不同。
  ✅ "While I **was reviewing** the PR, ..."（强调 review 正在进行）
  ✅ "While I **reviewed** the PR, ..."（强调 review 这件事完成了——但不够自然）
```

```
示例 5：The deployment was going smoothly until the database ran out of disk space.
- The deployment (主语/名词短语) + was going (谓语/过去进行时)
  + smoothly (状语/副词) + until the database ran out of disk space (时间状语从句)
- 分析：过去进行时 "was going" 描述"部署一直顺利进行"这个持续过程。
  "until..." 从句用一般过去时 "ran out"，标记了这个持续过程被终止的时间点。
- 理解技巧："was going smoothly" 不像一般过去时 "went smoothly" 那样陈述"结果"，
  它强调的是"当时的状态是顺利的"——暗示后面有变化。
```

---

#### 4. 中国学生的常见错误

**错误 1：忘记 was/were**
- ❌ "I **debugging** the issue when you called."（少了 was）
- ✅ "I **was debugging** the issue when you called."
- 这是最顽固的错误之一——中文没有对应"正在"的系动词，所以容易漏。

**错误 2：用过去进行时描述已完成的动作**
- ❌ "Yesterday, I **was deploying** the release."（除非强调"正在部署的过程中"，否则用一般过去时更合适）
- ✅ "Yesterday, I **deployed** the release."（只是陈述"做了部署"这件事）
- 关键：如果动作已经完成，且你只是陈述事实，用一般过去时。过去进行时强调"过程/背景"。

**错误 3：同时发生的两个动作，一个用进行时一个用过去时，逻辑搞反**
- ❌ "I **ate** dinner while the server **was rebooting**."（语法对，但语义奇怪——你在吃饭时服务器重启，两个都没问题）
- ✅ "The server **was rebooting** while I **ate** dinner."（服务器重启是背景，吃饭是插入事件——但也别扭，因为两个都不算"打断"）
- ✅ 更好的表达：两个都用过去进行时。"While the server **was rebooting**, I **was reviewing** the documentation."

**错误 4：对状态动词使用过去进行时**
- ❌ "I **was knowing** the answer when the manager asked me."
- ✅ "I **knew** the answer when the manager asked me."（know 是状态动词，不用进行时）
- 和现在进行时一样，状态动词（know, understand, belong, need 等）通常不能用于进行时态。

---

### Part C: Simple Past vs. Past Continuous — 对比

两者的核心区别：**Simple Past = 完整发生的动作（结果）**，**Past Continuous = 正在进行的过程（背景）**。

| 对比维度 | Simple Past | Past Continuous |
|---------|------------|----------------|
| **动作状态** | 已完成 | 进行中（未完成） |
| **时间感** | 点状/完成的事件 | 线状/持续的过程 |
| **核心问题** | "这件事发生了吗？" | "这件事当时正在发生吗？" |

**对比场景 1：完整事件 vs. 进行背景**
- "I **deployed** the fix."（我部署了修复——事情做完了，陈述事实）
- "I **was deploying** the fix when the server crashed."（我正在部署修复时服务器崩溃了——部署这件事被中断了，暗示部署没有完成）
- 关键差别：第一句告诉你"结果"（部署完成了），第二句告诉你"背景"（部署进行中，但没说完）。

**对比场景 2：先后顺序 vs. 同时发生**
- "When the manager **arrived**, I **finished** the report."（经理到了 → 我写完了报告。两个动作先后发生）
- "When the manager **arrived**, I **was finishing** the report."（经理到的时候我正在写报告的结尾。两件事同时——经理到的时候，写报告这件事还在进行中）
- 关键差别：一般过去时表示"后一个动作在前一个动作之后完成"；过去进行时表示"前一个动作发生时，后一个动作正在进行"。

**对比场景 3：事实陈述 vs. 场景描述**
- "We **migrated** the database last weekend."（我们上周末迁移了数据库——纯粹的事实，像新闻标题）
- "We **were migrating** the database all weekend. It was a nightmare."（我们整个周末都在迁移数据库。那是一场噩梦。——描述了"过程"和"感受"）
- 关键差别：在讲故事的语境中（retro、postmortem、闲聊），过去进行时让听众"身临其境"。阅读对比：
  - "The server crashed. I fixed it."（干巴巴的流水账）
  - "The server **was crashing** repeatedly. I **was debugging** it for hours while users **were reporting** errors."（生动地描述了当时的场景）

**经典模式汇总：**

| 结构 | 含义 | 示例 |
|------|------|------|
| was/were V-ing + when + 一般过去时 | 正在 A 时，B 突然发生 | "I was reviewing the PR when the incident happened." |
| while + 过去进行时 + 过去进行时 | A 和 B 同时进行 | "While I was checking the logs, she was restarting the server." |
| while + 过去进行时 + 一般过去时 | 在 A 的过程中 B 发生 | "While he was deploying, the build failed." |
| 一般过去时 + after + 一般过去时 | A 之后 B 发生（先后顺序） | "I fixed the bug after I reproduced it." |

---

## 2. Vocabulary: Top 20 Collaboration Words

以下 20 个词汇是在团队协作、会议沟通和技术讨论中最高频使用的单词。每个单词学习三个常见的语境义项。这些词汇是你在英文工作环境中"说清楚事"的关键。

---

### 1. align
- **义项 1: 对齐/保持一致 (v.)** — 确保团队成员或部门对目标有共同理解
  - "We need to **align** on the delivery timeline before the sprint starts."
- **义项 2: 使（代码/设计）对齐 (v.)** — 调整代码风格或架构以保持一致
  - "We should **align** our code style with the team's ESLint configuration."
- **义项 3: 与……结盟 (v.)** — 与某人或某团队达成合作共识
  - "The frontend team should **align** with the design team on the new component library."

---

### 2. clarify
- **义项 1: 澄清/说明 (v.)** — 解释清楚模糊或不明确的内容
  - "Could you **clarify** the requirements for this user story?"
- **义项 2: 阐明观点 (v.)** — 让自己的想法更容易被理解
  - "Let me **clarify** what I meant — I'm not saying we should rewrite everything."
- **义项 3: 理清（问题/情况）(v.)** — 弄清楚某个复杂的情况
  - "We need to **clarify** the root cause before jumping to a solution."

---

### 3. escalate
- **义项 1: 升级问题 (v.)** — 将问题上报给更高级别的人处理
  - "If the incident is not resolved in 30 minutes, **escalate** it to the SRE team."
- **义项 2: 加剧/恶化 (v.)** — 问题变得更严重
  - "The production issue **escalated** from a minor bug to a full outage within an hour."
- **义项 3: 扩大范围 (v.)** — 使某事的规模或严重性增加
  - "The scope of the project **escalated** after the client requested additional features."
- **用法提示:** 在 on-call 场景中，escalate 有特定流程——"escalation path"（升级路径）、"escalation policy"（升级策略）。

---

### 4. prioritize
- **义项 1: 排序优先级 (v.)** — 决定哪些任务先做、哪些后做
  - "We need to **prioritize** the security fixes over the new features."
- **义项 2: 优先处理 (v.)** — 把某件事放在最重要的位置
  - "The team **prioritized** performance optimization after the user complaints."
- **义项 3: 分清主次 (v.)** — 在多个需求中识别真正重要的
  - "It's important to **prioritize** your tasks based on business impact."
- **用法提示:** 名词形式是 priority（优先级）。"top priority" = 最高优先级。"prioritize A over B" = 认为 A 比 B 重要。

---

### 5. delegate
- **义项 1: 委派任务 (v.)** — 将任务分配给团队成员去做
  - "As a tech lead, you need to **delegate** tasks instead of doing everything yourself."
- **义项 2: 授权 (v.)** — 将权限或职责交给别人
  - "The manager **delegated** the decision-making authority to the senior engineers."
- **义项 3: 代理/委托 (v.)** — 在编程中，将行为委托给另一个对象（delegation pattern）
  - "In this design pattern, the parent component **delegates** event handling to the child."
- **用法提示:** delegate 的重音在第一音节：/ˈdɛlɪɡeɪt/。不要读成 /dɪˈleɪɡeɪt/。

---

### 6. brainstorm
- **义项 1: 头脑风暴 (v.)** — 集体自由讨论，产生多个想法
  - "Let's **brainstorm** solutions for the database performance issue."
- **义项 2: 集思广益 (v.)** — 广泛收集各方意见
  - "We **brainstormed** several approaches before settling on the microservices architecture."
- **义项 3: 想出/构思 (v.)** — 独自思考产生想法（也可用于个人）
  - "I need some quiet time to **brainstorm** ideas for the system design."
- **用法提示:** brainstorm 既是动词也是名词（"Let's have a **brainstorm** session"）。过去式：brainstormed。常见搭配：brainstorm ideas/solutions/approaches。

---

### 7. sync
- **义项 1: 同步信息 (v.)** — 互相更新信息，保持一致的理解
  - "Let's **sync** up after the meeting to discuss the next steps."
- **义项 2: 数据同步 (v.)** — 在多设备或多系统之间保持数据一致
  - "The mobile app **syncs** with the server every time the user goes online."
- **义项 3: 对齐进度 (v.)** — 确保各方对进度有共同认识
  - "We should **sync** with the QA team before the release."
- **用法提示:** sync 是 synchronization 的缩写。非常口语化——"Let's sync"、"Keep me in sync"、"out of sync"。在正式文档中用 synchronize。

---

### 8. onboard
- **义项 1: 入职引导 (v.)** — 帮助新成员了解团队和项目
  - "I spent the morning **onboarding** the new junior developer."
- **义项 2: 接入系统 (v.)** — 将新用户或新客户接入系统
  - "The team is **onboarding** three new clients this quarter."
- **义项 3: 熟悉上手 (v.)** — 让自己或他人学习和适应新工具
  - "It took me a week to **onboard** onto the new cloud infrastructure."
- **用法提示:** 名词是 onboarding（"The **onboarding** process takes about two weeks"）。onboard 作为动词，过去式是 onboarded（❌ "onboarded" 没有拼写错误）。

---

### 9. offload
- **义项 1: 分担任务 (v.)** — 将部分工作转移给他人
  - "I need to **offload** some of my tasks to free up time for the architecture review."
- **义项 2: 卸载/转移负载 (v.)** — 将计算任务从主系统转移到其他系统
  - "The CDN **offloads** static asset delivery from the main server."
- **义项 3: 推卸/甩掉 (v.)** — 把责任或问题转给别人（略带负面）
  - "He tried to **offload** the blame for the missed deadline onto the QA team."
- **用法提示:** 技术语境下，"compute offloading"（计算卸载）是边缘计算中的常用术语。

---

### 10. follow up
- **义项 1: 跟进 (v.)** — 继续跟进某个任务或话题
  - "I'll **follow up** with the DevOps team about the certificate renewal."
- **义项 2: 追问 (v.)** — 在初次沟通后再次联系确认
  - "She **followed up** with the client to confirm the requirements."
- **义项 3: 后续行动 (v.)** — 在某个事件后采取进一步行动
  - "We need to **follow up** on the incident with a root cause analysis."
- **用法提示:** follow up 是动词短语，名词形式是 follow-up（带连字符）。"I'll **follow up** with you"（动词）vs. "a **follow-up** meeting"（名词/形容词）。过去式：followed up。

---

### 11. stakeholder
- **义项 1: 利益相关者 (n.)** — 对项目或决策有利益关系的人
  - "We need to present the proposal to all **stakeholders** before making a decision."
- **义项 2: 项目干系人 (n.)** — 在项目管理中受项目结果影响的人
  - "The key **stakeholders** for this project include the product, engineering, and sales teams."
- **义项 3: 股东 (n.)** — 在商业语境中，持有公司股份的人
  - "The CEO updated the **stakeholders** on the company's growth strategy."
- **用法提示:** stakeholder 在 tech 语境中最常见的是义项 1。常见搭配：key stakeholders、project stakeholders、business stakeholders。

---

### 12. consensus
- **义项 1: 共识 (n.)** — 团队成员达成的一致意见
  - "After a long discussion, the team reached a **consensus** on the architecture choice."
- **义项 2: 集体意见 (n.)** — 多数人认同的看法
  - "The **consensus** among the engineers is that we should rewrite the legacy module."
- **义项 3: 共识机制 (n.)** — 分布式系统中节点间达成一致的算法机制
  - "The blockchain uses a **consensus** algorithm to validate transactions."
- **用法提示:** 常见搭配：reach a consensus（达成共识）、build consensus（建立共识）。注意：consensus 后面通常跟 on/about："consensus on the approach"。

---

### 13. blocker
- **义项 1: 阻塞项 (n.)** — 阻碍任务进度的问题或障碍
  - "The pending security review is a **blocker** for the release."
- **义项 2: 代码阻塞 (n.)** — 阻止其他代码合并的 PR 或 issue
  - "This bug is a **blocker** for the v2.0 release — we can't ship without fixing it."
- **义项 3: 阻碍者 (n.)** — 在敏捷开发中阻碍团队达到 sprint goal 的事情
  - "What are the **blockers** for this sprint? Put them on the board."
- **用法提示:** blocker 是敏捷/scrum 中的标准术语。daily standup 上你经常被问到："Do you have any blockers?"（有什么阻塞吗？）动词形式是 block。

---

### 14. deliverable
- **义项 1: 交付物 (n.)** — 项目或 sprint 需要产出的具体成果
  - "The main **deliverable** for this sprint is the user authentication module."
- **义项 2: 可交付成果 (n.)** — 合同中规定的需交付的产品或文档
  - "The architecture design document is a **deliverable** for the project kickoff phase."
- **义项 3: 预期产出 (n.)** — 在某个时间点前需要完成的工作
  - "What are the key **deliverables** for the next milestone?"
- **用法提示:** deliverable 基本都是名词。发音时注意重音在第二个音节：/dɪˈlɪvərəbəl/。在项目管理中非常高频。"key deliverables"、"project deliverables"、"sprint deliverables"。

---

### 15. milestone
- **义项 1: 里程碑 (n.)** — 项目中的重要阶段性节点
  - "The beta release is a major **milestone** for the project."
- **义项 2: 关键事件 (n.)** — 开发过程中的重要日期或事件
  - "Code freeze is the next **milestone** — all features must be merged by then."
- **义项 3: 历史转折点 (n.)** — 职业生涯或技术发展中的重要节点
  - "Getting my first pull request merged was a personal **milestone**."
- **用法提示:** 在项目管理工具中（Jira, Asana, GitHub Projects），milestone 是一个可设置的功能模块。"reach a milestone"、"set a milestone"、"milestone deadline"。

---

### 16. timeline
- **义项 1: 时间线 (n.)** — 项目各阶段的起止时间安排
  - "The **timeline** for this project is aggressive — we only have two months."
- **义项 2: 时间轴 (n.)** — 按时间顺序展示事件或阶段的图表
  - "Let me draw a **timeline** of the incidents that led to the outage."
- **义项 3: 截止日期 (n.)** — 非正式语境中指最终期限
  - "The client wants to move the **timeline** up by two weeks."
- **用法提示:** 常见搭配："tight timeline"（紧张的时间线）、"extend the timeline"（延长）、"timeline shift"（时间线变动）。

---

### 17. scope
- **义项 1: 范围 (n.)** — 项目或任务包含的工作边界
  - "The **scope** of this sprint includes the payment feature and the notification system."
- **义项 2: 作用域 (n.)** — 编程中变量的可见范围
  - "In JavaScript, `let` has block **scope**, while `var` has function **scope**."
- **义项 3: 确定范围 (v.)** — 评估和定义某工作包含的内容
  - "We need to **scope** the project before we can give you an accurate estimate."
- **用法提示:** "scope creep"（范围蔓延）是一个常见短语，指项目范围不受控制地扩大。"out of scope" = 不在范围内，"in scope" = 在范围内。

---

### 18. trade-off
- **义项 1: 权衡/折中 (n.)** — 在两个或多个选项中做出取舍
  - "There's always a **trade-off** between development speed and code quality."
- **义项 2: 交换 (n.)** — 为了获得某方面的好处而放弃另一方面的好处
  - "The **trade-off** of using a NoSQL database is flexibility versus consistency."
- **义项 3: 交易/交换条件 (n.)** — 双方互相让步达成一致
  - "We made a **trade-off** with the product team: they get the feature faster, but we skip the animation polish."
- **用法提示:** 在系统设计中，"trade-off analysis"（权衡分析）是面试必考点。"Everything is a trade-off." 连字符可加可不加（tradeoff 也是标准写法）。

---

### 19. bandwidth
- **义项 1: 带宽 (n.)** — 网络传输能力的度量
  - "The video streaming service requires at least 5 Mbps of **bandwidth**."
- **义项 2: 个人精力/时间 (n.)** — 某人能用来处理某事的可用时间或精力（幽默的比喻用法）
  - "I don't have the **bandwidth** to review your PR today — let's do it tomorrow."
- **义项 3: 团队容量 (n.)** — 团队在给定时间能处理的工作量
  - "The team doesn't have enough **bandwidth** to take on another project this quarter."
- **用法提示:** 义项 2 是非常高频的口语用法——"I don't have bandwidth" 比 "I'm too busy" 更礼貌，暗示"我确实想做，但实在没时间"。

---

### 20. capacity
- **义项 1: 容量 (n.)** — 系统能承受的最大负载
  - "The server has a **capacity** of handling 10,000 concurrent users."
- **义项 2: 团队能力 (n.)** — 团队在单位时间内能完成的任务量
  - "We need to calculate the team's **capacity** for the next sprint."
- **义项 3: 个人角色/身份 (n.)** — 以某种身份或角色行事
  - "I'm speaking in my **capacity** as the tech lead, not as your friend."
- **用法提示:** "capacity planning"（容量规划）是 SRE/DevOps 的核心工作。义项 3 在正式场合中用："in my capacity as..."（以……的身份）。

---

### 词汇速查表

| 编号 | 词汇 | 词性 | 中文核心意思 | 常见搭配 |
|------|------|------|-------------|---------|
| 1 | align | v. | 对齐 | align on/with, stay aligned |
| 2 | clarify | v. | 澄清 | clarify the requirements, clarify what you mean |
| 3 | escalate | v. | 升级 | escalate to, escalate the issue |
| 4 | prioritize | v. | 优先处理 | prioritize A over B, prioritize tasks |
| 5 | delegate | v. | 委派 | delegate tasks/authority to |
| 6 | brainstorm | v. | 头脑风暴 | brainstorm ideas/solutions |
| 7 | sync | v. | 同步 | sync up, sync with, keep in sync |
| 8 | onboard | v. | 入职引导 | onboard new members/clients |
| 9 | offload | v. | 分担 | offload tasks/work to |
| 10 | follow up | v. | 跟进 | follow up with/on |
| 11 | stakeholder | n. | 利益相关者 | key stakeholders, project stakeholders |
| 12 | consensus | n. | 共识 | reach consensus, build consensus |
| 13 | blocker | n. | 阻塞项 | have/raise/remove a blocker |
| 14 | deliverable | n. | 交付物 | key deliverables, sprint deliverables |
| 15 | milestone | n. | 里程碑 | reach/set a milestone |
| 16 | timeline | n. | 时间线 | tight timeline, extend the timeline |
| 17 | scope | n./v. | 范围 | in/out of scope, scope creep, scope the project |
| 18 | trade-off | n. | 权衡 | make a trade-off, trade-off between A and B |
| 19 | bandwidth | n. | 带宽/精力 | have bandwidth, enough bandwidth |
| 20 | capacity | n. | 容量/能力 | capacity planning, team capacity |

---

## 3. Sentence-Making Practice

以下 10 个练习结合了前几周的词汇和本周的过去时态。每个练习模拟一个真实工作场景。先自己写，再对照参考答案。

---

### 1. 你在 postmortem 中描述：昨天线上事故发生时，你正在查看日志。用过去进行时和一般过去时的"打断"结构。

**参考答案:** "I **was checking** the error logs when the production incident **happened** yesterday."
> （"was checking" = 过去进行时，表示"正在查看日志"这个长动作；"happened" = 一般过去时，表示"发生事故"这个瞬间动作。经典的 was V-ing + when + past 结构。）

---

### 2. 在 retro 会议上，你说上周团队花了很多时间讨论架构方案，最后达成了共识。用一般过去时和名词 **consensus**、动词 **reach**。

**参考答案:** "Last week, we **spent** a lot of time discussing the architecture options, and we finally **reached** a **consensus** on using microservices."
> （一般过去时：spend → spent（不规则），reach → reached（规则）。"spent time doing" 是固定搭配。reach a consensus on = 就……达成共识。注意："spent a lot of time to discuss" ❌ 应该说 "spent a lot of time **discussing**" ✅。）

---

### 3. 解释为什么某个 deadline 没有赶上——因为一个第三方服务的变更阻塞了你们的进度。用一般过去时和名词 **blocker**、动词 **raise**。

**参考答案:** "We **didn't meet** the deadline because the third-party API change **raised** a critical **blocker** that **required** an architecture adjustment."
> （一般过去时：didn't meet（否定），raised（规则变化），required（规则变化，-ed 读 /d/）。"didn't meet the deadline" = 没赶上截止日期。"raise a blocker" = 产生了一个阻塞项。）

---

### 4. 在 standup 上说：你昨天一边在 review PR，一边在等 CI 跑完。用过去进行时（两个同时进行的动作）和动词 **review**、名词 **pipeline**。

**参考答案:** "While I **was reviewing** the PR, the CI **pipeline** **was running** the integration tests."
> （两个同时进行的动作都用过去进行时："was reviewing" 和 "was running"。while 从句和主句使用同一时态，表示两个动作并行发生。注意：不需要说 "I was reviewing the PR, at the same time the CI was running"——while 本身就表达了"同时"。）

---

### 5. 在项目 kickoff 会议上，你提醒大家需要和相关干系人对齐项目范围。用一般过去时和名词 **stakeholder**、动词 **align**。

**参考答案:** "We **aligned** with the key **stakeholders** on the project **scope** before creating the timeline."
> （一般过去时：aligned（规则变化，-ed 读 /d/）。"align with someone on something" = 就某事与某人达成一致。"before creating the timeline" 中的 creating 是动名词，在介词 before 后使用。）

---

### 6. 你要把某个任务委派给新入职的同事，但因为对方还在熟悉阶段，你决定先自己处理。用一般过去时的否定和动词 **delegate**、动词 **onboard**。

**参考答案:** "I **didn't delegate** the task to the new hire because she was still **onboarding** and **didn't have** enough context yet."
> （一般过去时否定：didn't delegate，didn't have。原因从句用了过去进行时 "was still onboarding"——描述当时她正在经历的过程。注意：didn't have 比 had not 更口语化。）

---

### 7. 在 incident review 中，你说大家当时在头脑风暴解决方案，但你意识到应该先把问题升级给 SRE 团队。用过去进行时和动词 **brainstorm**、动词 **escalate**。

**参考答案:** "While the team **was brainstorming** solutions, I **realized** we should **escalate** the issue to the SRE team first."
> （"was brainstorming" = 过去进行时（背景动作）；"realized" = 一般过去时（插入的瞬间动作）。"should escalate" 中 should 后面跟动词原形，这是情态动词的规则。）

---

### 8. 在讲项目经历时，你说之前的项目中你们一直在做权衡——快还是稳。用一般过去时和名词 **trade-off**、动词 **prioritize**。

**参考答案:** "In that project, we **constantly made trade-offs** between shipping speed and stability. We **prioritized** stability over new features during the migration period."
> （一般过去时："made"（不规则），"prioritized"（规则，-ed 读 /d/）。"trade-off between A and B" = A 和 B 之间的权衡。"prioritize A over B" = 优先考虑 A 而非 B。"constantly" 放在动词 made 前面——副词的位置在"be 动词之后，实义动词之前"。）

---

### 9. 描述一个过去的状态变化：数据库本来运行正常，但在流量峰值时超出了容量。用动词 **run**、名词 **capacity**。

**参考答案:** "The database **was running** smoothly until the traffic spike **pushed** it beyond its **capacity**."
> （过去进行时 "was running" 描述"当时正常的运行状态"（背景），一般过去时 "pushed" 描述"超出容量"这个变化事件。"until" 是连接前后语境的桥梁——表示了"一直……直到……"的时间关系。beyond its capacity = 超出容量。）

---

### 10. 在 retrospective 上总结：这个 sprint 最值得改进的地方是早期没有及时同步信息，导致后面出现了阻塞。用一般过去时和动词 **sync**、名词 **blocker**。

**参考答案:** "The biggest lesson from this sprint is that we **didn't sync** early enough, which **caused** several **blockers** later in the cycle."
> （一般过去时否定：didn't sync。一般过去时：caused（规则变化，-ed 读 /d/）。"early enough" = 足够早。定语从句 "which caused several blockers" 用 which 指代前面整件事。注意：主句 "The biggest lesson is" ——虽然描述的是过去的事，但"教训是什么"是一个客观陈述，所以用一般现在时。）

---

### 练习覆盖检查

| 语法点 | 题号 |
|--------|------|
| Simple Past（肯定） | 2, 3, 5, 8 |
| Simple Past（否定） | 3, 6, 10 |
| Past Continuous（单独使用） | 7 |
| Past Continuous（被打断的 when 结构） | 1, 9 |
| Past Continuous（while 同时发生） | 4 |
| 不规则动词 | 2, 3, 5, 8, 9 |

| 本周词汇重点 | 题号 |
|-------------|------|
| blocker | 3, 10 |
| consensus | 2 |
| stakeholder/scope | 5 |
| delegate/onboard | 6 |
| brainstorm/escalate | 7 |
| trade-off/prioritize | 8 |
| capacity | 9 |
| sync | 10 |

---

## 4. Weekend Review

### 不规则动词自测

不看书，写出下列动词的**过去式**和**过去分词**。

| 原形 (Base) | 过去式 (Past) | 过去分词 (Past Participle) |
|------------|--------------|--------------------------|
| write | __________ | __________ |
| build | __________ | __________ |
| send | __________ | __________ |
| make | __________ | __________ |
| run | __________ | __________ |
| take | __________ | __________ |
| see | __________ | __________ |
| give | __________ | __________ |
| find | __________ | __________ |
| break | __________ | __________ |
| keep | __________ | __________ |
| deal | __________ | __________ |
| bring | __________ | __________ |
| think | __________ | __________ |
| tell | __________ | __________ |
| speak | __________ | __________ |
| leave | __________ | __________ |
| lose | __________ | __________ |
| spend | __________ | __________ |
| lead | __________ | __________ |
| set | __________ | __________ |
| let | __________ | __________ |
| cut | __________ | __________ |
| hit | __________ | __________ |
| read | __________ | __________ |
| go | __________ | __________ |
| get | __________ | __________ |
| know | __________ | __________ |
| mean | __________ | __________ |

**参考答案：** wrote/written, built/built, sent/sent, made/made, ran/run, took/taken, saw/seen, gave/given, found/found, broke/broken, kept/kept, dealt/dealt, brought/brought, thought/thought, told/told, spoke/spoken, left/left, lost/lost, spent/spent, led/led, set/set, let/let, cut/cut, hit/hit, read/read, went/gone, got/gotten, knew/known, meant/meant

**易错提醒：**
- run 的过去分词是 **run**（不是 ran）—— AAA 变体的特例
- read 拼写不变但发音变化：原形 /riːd/，过去式和过去分词 /red/
- lead 的过去式是 **led**（不是 leaded，也不是 lede）
- mean 的过去式是 **meant** /mɛnt/（不是 meaned）
- get 的美式过去分词是 **gotten**，英式是 **got**

---

### 易混淆词对比（Weeks 1-3 精选）

**1. deploy vs. rollback（部署 vs. 回滚）**
- "Yesterday we **deployed** v3.0 to staging for testing."（部署——向外发布新版本）
- "An hour later, we **rolled back** because of a database migration error."（回滚——撤回版本）
- 关键区别：direction of change——deploy 是"向前"（新版本上线），rollback 是"向后"（回到之前的版本）。

**2. break vs. fix（破坏 vs. 修复）**
- "The new deployment **broke** the login service."（过去时，broke 是 break 的不规则变化）
- "The SRE team **fixed** it within 20 minutes."（过去时，fixed 是规则变化）
- 关键区别：break 和 fix 是开发日常中最常见的"破坏-修复"对。brea**k** → bro**ke** → bro**ken**；fix 是规则动词 fix → fi**xed** → fi**xed**。

**3. stakeholder vs. blocker（干系人 vs. 阻塞项）**
- "The **stakeholders** requested an additional feature in the middle of the sprint."（干系人——人，对项目有利益关系的人）
- "This feature request became a **blocker** because it required a database schema change."（阻塞项——事，阻碍进度的问题）
- 关键区别：stakeholder 是"人"，blocker 是"事"。一个是"谁"，一个是"什么"。

**4. timeline vs. scope（时间线 vs. 范围）**
- "The **timeline** for this project is six weeks."（时间线——长度/起止）
- "The **scope** of this project includes the web app and the mobile API."（范围——边界/内容）
- 关键区别：timeline = 多久（时间维度），scope = 多少（内容维度）。scope 变了一般 timeline 也要跟着变。

**5. capacity vs. bandwidth（容量 vs. 带宽）**
- "The server **ran out of capacity** during the flash sale."（容量——系统的最大承受力，客观的数值）
- "I don't have the **bandwidth** to take on another project right now."（带宽——比喻用法，指个人的时间和精力，较口语化）
- 关键区别：capacity 是客观的、工程范畴的；bandwidth 常是比喻的、人际范畴的。但在工程语境中，bandwidth 也可以指网络带宽。

---

### 语法自我检测清单

逐一检查，诚实地标记自己是否掌握：

**一般过去时（Simple Past）：**
- [ ] 我能区分规则动词的三种 -ed 发音吗？（/t/, /d/, /ɪd/）能不能各举 3 个例子？
- [ ] 我至少记住了 25 个不规则动词的过去式吗？
- [ ] 我能在否定句和疑问句中正确使用 "didn't + 原形" 和 "Did + 主语 + 原形" 吗？
- [ ] 我能避免"双重过去标记"的错误吗？（❌ I didn't saw）
- [ ] 我能在有 yesterday/last week/ago 等词的句子里正确使用时态吗？

**过去进行时（Past Continuous）：**
- [ ] 我知道过去进行时的三种核心用法吗？（过去某一时刻正在进行的动作、两个同时进行的动作、被打断的动作）
- [ ] 我能在构建过去进行时句子时正确使用 was/were 吗？
- [ ] 我能正确使用"过去进行时 + when + 一般过去时"的打断结构吗？
- [ ] 我能正确使用"While + 过去进行时 + 过去进行时"的同时结构吗？
- [ ] 我能在写英语句子时避免对状态动词使用过去进行时吗？（❌ was knowing，✅ knew）

**过去时态对比：**
- [ ] 我能解释"I deployed the fix"和"I was deploying the fix"的语感差异吗？
- [ ] 看到 "when" 和 "while"，我知道哪个通常跟进行时搭配吗？
- [ ] 我能区分"先后发生的事情"（都用一般过去时）和"同时发生的（背景+事件）"（过去进行时+一般过去时）吗？

---

### 周末练习建议

**建议用时：** 周六 45 分钟 + 周日 45 分钟

**周六练习：写一个 postmortem（事故复盘）**

找一个你最近经历过或了解的生产事故（或者想象一个场景），用英语写一段简短的 postmortem 描述。要求：
- 至少使用 5 个一般过去时的句子（描述发生了什么）
- 至少使用 2 个过去进行时的句子（描述当时正在发生什么）
- 使用本周学到的至少 3 个协作词汇（blocker, escalate, sync, timeline 等）
- 使用至少 2 个不规则动词（broke, found, left, lost 等）

**示例：**
> "Last Friday at 2:30 PM, the payment service **started** returning 502 errors. I **was monitoring** the dashboard when the alert **fired**. The root cause **was** a database migration that **ran** out of disk space. While the SRE team **was restoring** the database backup, we **escalated** the issue to the engineering manager. The main **blocker** was that nobody **had** synced the migration schedule with the on-call team. We **restored** the service within 45 minutes, but this incident **raised** important questions about our deployment **timeline** and communication process."

写完后，逐句检查：
- 每个过去时的动词形式是否正确？（不规则动词查对照表）
- 进行时的句子是否真的需要强调"过程"？还是应该用一般过去时？
- 过去进行时的句子有没有忘记 was/were？

**周日练习：时态切换写作 + 角色扮演**

**Part A — 时态切换写作：** 写 5 组句子，用同一种场景展示 Simple Past 和 Past Continuous 的区别。

| 话题 | Simple Past（完整事件） | Past Continuous（过程/背景） |
|------|----------------------|-------------------------------|
| 修复 bug | I fixed the race condition. | I was fixing the race condition when the server crashed. |
| 部署 |  |  |
| 开会 |  |  |
| 代码审查 |  |  |
| 迁移 |  |  |

**Part B — Retro 角色扮演（可选挑战）：** 用英语"表演"一个 2 分钟的 retro 发言，描述过去这个 sprint 你做了什么、遇到了什么阻塞、学到了什么。全部用过去时态。可以录下来听自己的发音——注意 -ed 的三种发音和 irregular verbs 的发音。

**下周生存贴士：**
- 看到 yesterday / last week / two days ago / in 2023 → 条件反射用一般过去时
- 描述事故、写 postmortem、做 retro → 90% 的动词都是过去时态
- 在写"正在……的时候突然……" → 记住结构：was/were V-ing + when + 一般过去时
- 两个动作同时在过去进行 → 用 While + Past Continuous, Past Continuous
- 不确定一个动词是否规则 → 默念一遍不规则动词表，如果不在表里→ 规则动词加 -ed

---

> **下周预告：** Week 4 将学习**现在完成时**——中国学生最难掌握的时态，没有之一。什么时候用 "I have deployed" 而不是 "I deployed"？这两个到底有什么区别？我们下周见分晓。另外还会学习 20 个高频技术英语形容词，让你的技术交流更精准。

