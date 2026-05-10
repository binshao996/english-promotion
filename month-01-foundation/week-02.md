# Week 02: 一般现在时 & 现在进行时 + 核心开发名词

> 目标：彻底掌握一般现在时和现在进行时的用法与区别，并学会 20 个最高频开发名词的核心含义。本周你要建立"时态意识"——中文没有动词变化，但英语的时态是句子意思的重要组成部分。

---

## 1. Grammar: Simple Present & Present Continuous

句子结构掌握之后，下一个关键问题是时态。中文没有"动词变位"这个概念——我们说"昨天部署"和"明天部署"，"部署"这两个字写法一模一样。英语则不同，动词形态会随时间和情境变化。本周我们从最基础、也是最容易被忽视的两个时态开始。

---

### Part A: Simple Present（一般现在时）

**核心概念：** 一般现在时描述的是"稳定状态"——事实、习惯、固定安排、当前状态。它不是"现在正在发生"的动作，而是"经常发生"或"一直成立"的情况。

#### 1. 核心用法

**用法 1：客观事实 / 普遍真理**
描述科学事实、技术原理等不随时间改变的内容。
- "REST APIs **are** stateless."
- "Water **boils** at 100 degrees Celsius."
- "JavaScript **runs** in both the browser and the server."

**用法 2：习惯 / 常规操作**
描述定期发生的行为、日常操作。
- "We **deploy** to production every Monday."
- "The team **holds** a standup meeting at 9:30 AM."
- "I **review** pull requests before lunch."

**用法 3：固定时间表 / 计划**
描述已经确定好时间的事件（列车时刻表、会议安排、sprint 周期）。
- "The sprint **starts** on Wednesday and **ends** two weeks later."
- "The release **is** scheduled for next Friday."
- "Our on-call rotation **begins** at 9 AM."

**用法 4：当前状态 / 所属关系**
描述某人或某物当前所处的状态，或所属关系。
- "This codebase **belongs** to the platform team."
- "The database server **has** 64 GB of RAM."
- "She **works** on the frontend team."

---

#### 2. 第三人称单数 -s 规则

当主语是 he / she / it 或相当于第三人称单数的名词（the server, the team, the API），动词要加 -s 或 -es。

**基本规则：**

| 情况 | 变化 | 示例 |
|------|------|------|
| 大多数动词 | 加 -s | run → runs, write → writes, work → works |
| 以 -s, -sh, -ch, -x, -o 结尾 | 加 -es | push → pushes, fix → fixes, go → goes, do → does |
| 以"辅音 + y"结尾 | 变 y 为 i，加 -es | try → tries, apply → applies, deploy → deploys |
| have | 变为 has | have → has |
| be | 变为 is | be → is |

**常见误区：**
- ❌ "The API return a JSON object."（漏了 -s）
- ✅ "The API return**s** a JSON object."
- ❌ "He have 10 years of experience."
- ✅ "He ha**s** 10 years of experience."
- ❌ "The team deploy the fix on Friday."
- ✅ "The team deploy**s** the fix on Friday."（注意：team 是集合名词，在英式英语中可看作复数，但在美式英语中通常视为单数。为安全起见，一律用单数处理。）

---

#### 3. 否定形式

**结构：** don't / doesn't + **动词原形**

- "I **don't need** more memory for this task."
- "The server **doesn't support** HTTP/2."
- "We **don't use** that library anymore."
- "This endpoint **doesn't require** authentication."

关键点：用了 doesn't 之后，动词必须还原——不需要再加 -s。
- ❌ "The server doesn't supports HTTP/2."
- ✅ "The server doesn't **support** HTTP/2."（doesn't 已经体现了第三人称单数，后面的动词用原形）

---

#### 4. 疑问形式

**结构：** Do / Does + 主语 + **动词原形** + ?

- "**Do** you **work** on the backend team?"
- "**Does** the API **return** paginated results?"
- "**How** **does** this function **handle** errors?"
- "**Why** **do** we **need** a staging environment?"

和否定一样，用 Does 提问时，动词也用原形。

---

#### 5. 完整语法拆解示例

```
示例 1：The CI pipeline runs every time we push to main.
- The CI pipeline (主语/名词短语) + runs (谓语/一般现在时第三人称单数)
  + every time we push to main (时间状语从句)
- 分析：主语 "The CI pipeline" 是第三人称单数，所以 run 加 -s 变成 runs。
  "every time we push to main" 表示这是一个常规触发条件。
- 理解技巧：一般现在时就像系统的"默认配置"——描述的是每次都会发生的事，
  不需要特殊条件。问自己："这件事是每次都这样吗？"是→用一般现在时。
- 常见错误：忘记加 -s 是最常见的问题。
  ❌ "The CI pipeline run every time we push to main."
  ✅ "The CI pipeline run**s** every time we push to main."
```

```
示例 2：This endpoint returns user profile data in JSON format.
- This endpoint (主语/名词短语) + returns (谓语/第三人称单数)
  + user profile data (宾语/名词短语) + in JSON format (方式状语)
- 分析：描述 API 端点的功能——这是一个"客观事实"，
  不随时间改变。无论你什么时候调用它，它都做同样的事。
- 理解技巧：技术文档、API 说明、代码注释——这些地方几乎全是 Simple Present。
  因为你在描述"这个系统默认怎么工作"。
```

```
示例 3：We deploy to production every Monday.
- We (主语/代词) + deploy (谓语/动词原形，因为主语是 We) +
  to production (介词短语/目的地) + every Monday (时间状语)
- 分析：主语是 "We"（第一人称复数），所以动词 deploy 保持原形。
  "every Monday" 明确表示这是一个常规操作。
- 理解技巧：描述团队惯例时，用一般现在时。"我们每周一上线"
  是一个固定安排，不是"正在发生"的事。
```

```
示例 4：The sprint starts on Wednesday and ends two weeks later.
- The sprint (主语/名词短语) + starts (谓语/第三人称单数)
  + on Wednesday (时间状语) + and (连接词) + ends (谓语/第三人称单数)
  + two weeks later (时间状语)
- 分析：sprint 的起止时间是提前定好的，即使它还没发生，也用一般现在时。
  这是"固定时间表"的用法。
- 难点提醒：中文说"这个 sprint 将在周三开始"，用"将"字表达将来。
  但英语中对于固定时间表，直接用一般现在时。
  ✅ "The sprint starts on Wednesday."（不是 The sprint will start——虽然也可以，但固定安排用 starts 更地道）
```

```
示例 5：This codebase belongs to the platform team.
- This codebase (主语/名词短语) + belongs (谓语/第三人称单数)
  + to the platform team (介词短语/归属对象)
- 分析：belong 是一个"状态动词"，描述的是"属于"这个状态。
  它不是一个动作，不涉及"正在发生"。
- 理解技巧："belong"、"have"、"own" 这类词描述的是"已经是这样"的状态。
  你不会说 "This codebase is belonging"——状态不需要进行时。
```

---

#### 6. 中国学生的常见错误

**错误 1：忘记第三人称单数的 -s**
- ❌ "The developer push the code to main."
- ✅ "The developer pushe**s** the code to main."
- 为什么容易错：中文动词没有形态变化，所以中国学生本能地忽略 -s。解决方案：每次看到第三人称单数主语，条件反射地检查动词。

**错误 2：用一般现在时描述过去的动作**
- ❌ "I deploy the fix yesterday."（yesterday 是过去时间，不能用一般现在时）
- ✅ "I **deployed** the fix yesterday."
- 关键点：一般现在时不能用于已完成的过去事件。看到表示过去的时间词（yesterday, last week, ago），必须用过去时。

**错误 3：过度使用 "will" 表达一般事实**
- ❌ "The API will return a 404 if the user doesn't exist."
- ✅ "The API **returns** a 404 if the user doesn't exist."（这是条件事实，不需要 will）
- 关键点：如果描述的是"每次都是这样"的条件逻辑，用一般现在时，不需要 will。will 只用于"预测"或"当场决定"。

---

### Part B: Present Continuous（现在进行时）

**核心概念：** 现在进行时描述的是"正在进行中"的动作或状况——有开始，有结束，不在默认状态下。

#### 1. 核心用法

**用法 1：说话时正在进行的动作**
描述此时此刻正在发生的事情。
- "I **am debugging** the production issue right now."
- "The server **is running** out of memory."
- "Hold on — I **'m reviewing** your pull request."

**用法 2：当前阶段的临时情况**
描述一段时期内在做的事情（不一定是说话这一刻正在做）。
- "We **'re migrating** to a new database this quarter."
- "I **'m working** on the authentication module this sprint."
- "The team **is transitioning** from monorepo to multi-repo."

**用法 3：已经安排好的近期将来**
描述已经确定好计划、近期一定会发生的事情。这是英语中非常常见的"将来"表达方式。
- "I **'m meeting** the client tomorrow afternoon."
- "We **'re deploying** the hotfix tonight."
- "She **'s presenting** the architecture proposal on Friday."

---

#### 2. 形式构成

**肯定：** am / is / are + V-ing
- I **am** debugging → I'm debugging
- He/She/It **is** running → The server's running
- We/You/They **are** deploying → We're deploying

**否定：** am / is / are + not + V-ing
- "I **am not** working on that feature."
- "The database **is not** responding."
- "We **are not** using that approach anymore."

**疑问：** Am / Is / Are + 主语 + V-ing + ?
- "**Are** you **working** on the frontend today?"
- "**Is** the server **running** the latest version?"
- "**Why** **are** they **migrating** the database?"

**V-ing 拼写规则：**

| 情况 | 变化 | 示例 |
|------|------|------|
| 大多数动词 | 直接加 -ing | deploy → deploying, review → reviewing |
| 以不发音的 -e 结尾 | 去掉 e，加 -ing | make → making, have → having, write → writing |
| 以 -ie 结尾 | ie → y，加 -ing | lie → lying, die → dying |
| 重读闭音节（一个元音 + 一个辅音结尾） | 双写最后一个辅音，加 -ing | run → running, commit → committing, debug → debugging |
| 以 -c 结尾 | c → ck，加 -ing | picnic → picnicking（在编程语境罕见） |

**重点记忆：** debug → debugging（双写 g），commit → committing（双写 t），run → running（双写 n）。

---

#### 3. 不使用进行时的状态动词（Stative Verbs）

有些动词描述的是"状态"而非"动作"。状态是"已经存在的"，不是"正在进行的"。这些动词通常**不能**用于进行时。

**常见状态动词分类：**

| 类别 | 动词 |
|------|------|
| 思维/认知 | know, understand, believe, think（认为）, doubt, remember, forget |
| 情感/感受 | like, love, hate, want, need, prefer, mind |
| 所属/存在 | belong, own, have（拥有）, contain, consist, exist |
| 感官 | seem, appear（看起来）, look（看起来）, sound, taste, feel |
| 其他状态 | be（是）, cost, weigh, depend, concern |

**错误示范 vs. 正确用法：**
- ❌ "I **am knowing** the answer."
- ✅ "I **know** the answer."
- ❌ "This **is belonging** to the frontend team."
- ✅ "This **belongs** to the frontend team."
- ❌ "We **are needing** more test coverage."
- ✅ "We **need** more test coverage."
- ❌ "The solution **is seeming** too complex."
- ✅ "The solution **seems** too complex."

**⚠️ 特殊提醒：** 有些动词既有"状态"含义又有"动作"含义，用法不同。

| 动词 | 状态义（不用进行时） | 动作义（可以用进行时） |
|------|---------------------|---------------------|
| have | "I **have** a question."（有） | "I **'m having** lunch."（吃） |
| think | "I **think** it's a good idea."（认为） | "I **'m thinking** about the architecture."（思考） |
| look | "It **looks** good."（看起来） | "I **'m looking** at the logs."（看） |
| see | "I **see** the problem."（明白） | "I **'m seeing** the client later."（见面） |

---

#### 4. 完整语法拆解示例

```
示例 1：I am debugging a memory leak in the production environment.
- I (主语/代词) + am (be 动词) + debugging (现在分词) + a memory leak (宾语/名词短语)
  + in the production environment (地点状语)
- 分析：am/is/are + V-ing 结构。主语 "I" 对应 "am"。"debugging" 是 debug
  的现在分词形式，双写 g 再加 -ing。
- 理解技巧：现在进行时就像代码里的"运行中"状态——一个任务正在执行，尚未完成。
  如果任务做完了，就不再用进行时（改成过去时或完成时）。
- 常见错误：忘记 be 动词。
  ❌ "I debugging a memory leak."（缺了 am）
  ✅ "I **am** debugging a memory leak."
```

```
示例 2：We are migrating the database to a new cluster this quarter.
- We (主语/代词) + are (be 动词) + migrating (现在分词) + the database (宾语/名词短语)
  + to a new cluster (介词短语/目的地) + this quarter (时间状语)
- 分析：这句话描述的是一段时期内的临时状况——迁移过程持续一整个季度，
  不是说话这一刻正在发生的动作。
- 理解技巧：现在进行时的"临时性"是一个关键特征。
  如果一件事是永久的，用一般现在时；如果是临时的，用现在进行时。
  对比：✅ "We **migrate** databases for clients."（这是我们的业务，永久性的）
  ✅ "We **are migrating** our own database."（这是当前的临时项目）
```

```
示例 3：The server is running out of memory — we need to scale up.
- The server (主语/名词短语) + is (be 动词) + running out of (现在分词短语)
  + memory (宾语/名词短语)
- 分析："run out of" 是一个动词短语（用完/耗尽），在现在进行时中 be 动词变位，
  短语中的动词加 -ing。"need" 是状态动词，用一般现在时。
- 理解技巧：前半句描述"正在发生的内存耗尽过程"，后半句描述"需要扩展"（一般事实）。
  同一个句子里两种时态切换是正常的。
```

```
示例 4：I am meeting the product manager tomorrow to discuss the roadmap.
- I (主语/代词) + am (be 动词) + meeting (现在分词) + the product manager (宾语/名词短语)
  + tomorrow (时间状语/将来的标志词) + to discuss the roadmap (不定式表示目的)
- 分析：虽然 "tomorrow" 是将来时间，但这里用的是现在进行时。
  这是因为 "meeting" 是一个已经确定好的安排。
- 理解技巧：英语中表达"将来安排"，现在进行时比 "will" 更常用。
  ✅ "I'm meeting the PM tomorrow."（安排好了）
  ✅ "I'll meet the PM tomorrow."（可以，但更正式或更随意——取决于语境）
  ✅ "I meet the PM tomorrow."（× 不对，时间表类的动词如 start/begin 可以用
  一般现在时表将来，但 meet 不行）
```

```
示例 5：Are you still reviewing my pull request?
- Are (be 动词) + you (主语) + still (副词/仍然) + reviewing (现在分词)
  + my pull request (宾语/名词短语) + ?
- 分析：这是一般疑问句。be 动词提前到主语前面，动词的 -ing 形态保持不变。
  "still" 放在 reviewing 前面，表示"还在……吗？"
- 常见错误：疑问句中忘记把 be 动词提前，或者把主要动词也提前了。
  ❌ "You are reviewing my PR?"（口语中可接受，但不标准）
  ✅ "**Are** you reviewing my PR?"
  ❌ "Are you **review** my PR?"（be 动词和 V-ing 不匹配）
  ✅ "Are you **reviewing** my PR?"
```

---

#### 5. 中国学生的常见错误

**错误 1：对状态动词使用进行时**
- ❌ "I **'m knowing** React well."
- ✅ "I **know** React well."
- **解决方案**：记住状态动词列表。当你想用 -ing 时，先问自己：这个词描述的是"动作"还是"状态"？描述状态就不能用。

**错误 2：忘记 be 动词**
- ❌ "We **working** on a new feature."
- ✅ "We **'re working** on a new feature."
- **原因**：中文说"我们在做一个新功能"，没有"是"字（"我们是做"听起来很奇怪）。但英语的进行时必须有 be 动词。这是中文母语者最顽固的错误之一。

**错误 3：否定句和疑问句中的语序错误**
- ❌ "I not working today."
- ✅ "I **am not** working today."
- ❌ "Why you are deploying now?"
- ✅ "Why **are you** deploying now?"

---

### Part C: Simple Present vs. Present Continuous — 对比

两者的核心区别：**Simple Present = 默认状态 / 常规操作**，**Present Continuous = 正在进行 / 暂时情况**。

| 对比维度 | Simple Present | Present Continuous |
|---------|----------------|-------------------|
| **时间特征** | 永久、经常、固定 | 正在进行、临时、近期安排 |
| **关键标志词** | always, usually, often, sometimes, never, every day/week/Monday | now, right now, at the moment, currently, today, this week/quarter |
| **核心问题** | "这件事是一直这样吗？" | "这件事现在正在发生吗？" |

**对比场景 1：常规 vs. 此刻**
- "We **deploy** every Monday."（常规操作，每周一都上线）
- "We **are deploying** the security patch right now."（此刻正在上线安全补丁）

**对比场景 2：职责 vs. 当前任务**
- "I **work** on the platform team."（这是我的团队归属，是固定的）
- "I **'m working** on the notification service this sprint."（这是当前 sprint 的临时任务）

**对比场景 3：永久真理 vs. 暂时现象**
- "The API **returns** JSON."（API 的功能定义——永远都是）
- "The API **is returning** a 503 error."（当前暂时的异常——API 本身不是"返回 503"的）

**对比场景 4：习惯 vs. 变化**
- "The server **runs** Ubuntu 20.04."（服务器当前的操作系统配置）
- "We **'re running** out of disk space."（磁盘空间正在耗尽——这是一个变化过程）

**对比场景 5：客观描述 vs. 当下的抱怨/强调**
- "This code **works**."（代码能用——客观事实）
- "This code **is working** now."（代码"现在"能用了——暗示之前有问题，强调当前状态）

---

## 2. Vocabulary: Top 20 Dev Nouns

以下 20 个名词是你在日常开发中最常遇到的高频词汇。每个名词学习三个常见的语境义项，全部使用你在工作中会遇到的真实句子。注意：名词在句子中通常作主语或宾语，和上周的动词配合使用。

---

### 1. repository
- **义项 1: 代码仓库 (n.)** — 存放项目代码的版本控制存储位置
  - "Make sure to pull the latest changes from the **repository** before you start coding."
- **义项 2: 数据仓库 (n.)** — 集中存储大量数据的系统
  - "The data team uses a central **repository** to store all customer event logs."
- **义项 3: 知识库 (n.)** — 存储文档、资源等的地方
  - "We keep our architecture decision records in the team **repository**."
- **用法提示:** 在 Git 语境中常简称为 **repo**（复数 repos）。非常口语化，会议和聊天中频繁使用。"I forked the **repo** yesterday."

---

### 2. dependency
- **义项 1: 依赖项 (n.)** — 项目所依赖的外部包或库
  - "This project has over 200 **dependencies** in the node_modules folder."
- **义项 2: 依赖关系 (n.)** — 模块或服务之间的相互依赖关系
  - "The circular **dependency** between service A and service B is causing build issues."
- **义项 3: 依赖性 (n.)** — 对某事物的依赖状态
  - "Our heavy **dependency** on a single cloud provider is a risk we need to address."
- **用法提示:** 注意区分 dependencies（项目依赖）和 devDependencies（开发依赖）。在英文技术讨论中，常说 "dependency hell" 来形容依赖管理混乱的情况。

---

### 3. endpoint
- **义项 1: API 端点 (n.)** — API 中对外暴露的 URL 地址
  - "The `/users` **endpoint** returns a list of all registered users."
- **义项 2: 通信端点 (n.)** — 网络通信的接入点
  - "Each microservice exposes a health check **endpoint** for the monitoring system."
- **义项 3: 服务入口 (n.)** — 服务的对外接口地址
  - "The load balancer routes traffic to the nearest available **endpoint**."
- **用法提示:** endpoint 和 route 经常混用。严格来说，endpoint = URL + HTTP method，如 `GET /users` 是一个 endpoint。

---

### 4. interface
- **义项 1: 接口 (n.)** — TypeScript 或面向对象编程中定义的接口
  - "We defined an `User` **interface** with `id`, `name`, and `email` fields."
- **义项 2: 用户界面 (n.)** — 用户与系统交互的可视化界面
  - "The new **interface** loads 40% faster than the previous version."
- **义项 3: 对接方式 (n.)** — 不同系统之间的交互协议
  - "The payment gateway provides a RESTful **interface** for processing transactions."
- **用法提示:** 在 TypeScript/Go 中，interface 是一个语言关键词。在 Java 中 interface 也是有特殊地位的抽象类型。

---

### 5. variable
- **义项 1: 变量 (n.)** — 编程中用于存储数据的命名容器
  - "Declare a **variable** using `const` if you don't plan to reassign it."
- **义项 2: 环境变量 (n.)** — 操作系统或运行环境中的配置值
  - "Make sure to set the `DATABASE_URL` environment **variable** before running the migration."
- **义项 3: 可变因素 (n.)** — 在讨论或计划中可能变化的因素
  - "The timeline is the biggest **variable** in this project — it depends on how many engineers we can assign."
- **用法提示:** 变量命名规范的英文表达：camelCase（小驼峰，JS/TS 标准）、snake_case（下划线，Python 标准）、PascalCase（大驼峰，类名）。

---

### 6. function
- **义项 1: 函数 (n.)** — 执行特定任务并可被调用的代码块
  - "This **function** takes a user ID and returns the user's profile data."
- **义项 2: 功能 (n.)** — 系统或产品提供的特性
  - "The search **function** needs to support both full-text and fuzzy matching."
- **义项 3: 作用/职能 (n.)** — 某事物所起的作用
  - "The **function** of a cache is to reduce database load during high traffic."
- **用法提示:** function 和 method 的区别：function 是独立存在的，method 是定义在对象/类中的。JavaScript 中两者界限模糊（函数可以作为对象属性），但概念区分仍然重要。

---

### 7. parameter
- **义项 1: 形参 (n.)** — 函数定义中的形式参数
  - "This **function** takes two **parameters** : a request object and a callback function."
- **义项 2: 配置参数 (n.)** — 系统或算法的配置项
  - "Tune the **parameters** of the machine learning model to improve accuracy."
- **义项 3: 限制条件 (n.)** — 决定某事物边界的参数
  - "The design **parameters** include a maximum response time of 200ms."
- **用法提示:** parameter（形参）和 argument（实参）的区别很重要。你在定义函数时写的是 **parameters**，你在调用函数时传入的是 **arguments**。

---

### 8. argument
- **义项 1: 实参 (n.)** — 调用函数时实际传入的值
  - "If you pass the wrong **arguments** to this function, it will throw a TypeError."
- **义项 2: 论据 (n.)** — 支持或反对某观点的理由
  - "His main **argument** for choosing GraphQL is the flexibility it gives to the frontend team."
- **义项 3: 争论 (n.)** — 双方意见不一致的讨论
  - "We had a productive technical **argument** about whether to use microservices or a monolith."
- **用法提示:** 在编程上下文中，argument 通常和 parameter 对比出现。但在日常英语中，argument 最常用的含义是"争论"——比如 "We had an argument about the architecture." 注意语境。

---

### 9. database
- **义项 1: 数据库系统 (n.)** — 管理结构化数据存储的系统
  - "We use PostgreSQL as our primary **database** for transactional data."
- **义项 2: 数据库实例 (n.)** — 一个正在运行的数据库服务
  - "The production **database** needs to be upgraded to the latest version."
- **义项 3: 数据集 (n.)** — 有组织的数据集合
  - "The customer **database** contains over two million records."
- **用法提示:** database 常简称为 DB。数据库的主要操作：CRUD（Create, Read, Update, Delete）。

---

### 10. query
- **义项 1: 查询 (n.)** — 向数据库发送的数据请求
  - "This SQL **query** retrieves all orders placed in the last 24 hours."
- **义项 2: 查询语句 (n.)** — 具体的一条查询指令
  - "The slow **query** took over 10 seconds to complete, blocking other requests."
- **义项 3: 询问/提问 (n.)** — 在非数据库语境中的提问
  - "I have a quick **query** about the deployment process — should we notify users beforehand?"
- **用法提示:** query 作为动词的用法："We **query** the database for active users." 名词和动词同形。注意发音：/ˈkwɪri/，不是 /ˈkwei/。

---

### 11. schema
- **义项 1: 数据库模式 (n.)** — 数据库表结构、字段和关系的定义
  - "We need to update the database **schema** to include a new `phone_number` column."
- **义项 2: 数据格式定义 (n.)** — 描述数据结构的规范（如 JSON Schema）
  - "The API request body must follow the JSON **schema** defined in the documentation."
- **义项 3: 思维模型 (n.)** — 对某事物的抽象结构或框架
  - "The team's mental **schema** of the system architecture needs to be updated after the migration."
- **用法提示:** schema 的复数形式有两种：schemas（通用）和 schemata（学术/正式）。在技术文档中 schemas 更常见。

---

### 12. instance
- **义项 1: 实例对象 (n.)** — 类的一个具体对象
  - "Every time you call `new User()`, you create a new **instance** of the User class."
- **义项 2: 服务器实例 (n.)** — 一台正在运行的虚拟机或服务器
  - "We spun up three EC2 **instances** to handle the traffic spike."
- **义项 3: 实例/事例 (n.)** — 一个具体的事例
  - "There have been several **instances** of the service timing out under heavy load."
- **用法提示:** "instance" 在云服务语境中非常常见——"instance type"（实例类型）、"instance count"（实例数量）。短语 "for instance" = "for example"。

---

### 13. container
- **义项 1: 容器 (n.)** — Docker 等容器化技术创建的运行环境
  - "Each microservice runs in its own Docker **container** for isolation."
- **义项 2: 容器对象 (n.)** — 存放其他元素的数据结构
  - "An array is a **container** that holds multiple values in a specific order."
- **义项 3: 承载物 (n.)** — 用于打包和运输软件的环境
  - "The **container** includes the application code, runtime, and all its dependencies."
- **用法提示:** 区分 container 和 image：image 是只读模板（像类），container 是运行中的实例（像对象）。"We built the **image** and then started a **container** from it."

---

### 14. deployment
- **义项 1: 部署过程 (n.)** — 将软件发布到目标环境的过程
  - "The **deployment** took longer than expected due to a database migration step."
- **义项 2: 部署版本 (n.)** — 某个特定版本的发布
  - "Version 3.2 is the most stable **deployment** we have had this quarter."
- **义项 3: 部署策略 (n.)** — 部署的方式和策略
  - "We use a blue-green **deployment** strategy to minimize downtime during releases."
- **用法提示:** deployment 是 deploy 的名词形式。注意用法：❌ "We did a deploy yesterday."（但口语中常说）✅ 更正式："We did a **deployment** yesterday."

---

### 15. pipeline
- **义项 1: CI/CD 管道 (n.)** — 自动化构建、测试和部署的流程
  - "The CI **pipeline** runs linting, unit tests, and integration tests on every commit."
- **义项 2: 数据处理流程 (n.)** — 数据从输入到输出的处理链
  - "The data **pipeline** processes millions of events and loads them into the data warehouse."
- **义项 3: 流水线操作 (n.)** — 一系列串行或并行的处理阶段
  - "We split the build **pipeline** into parallel stages to reduce total execution time."
- **用法提示:** pipeline 强调的是"自动化"和"流程化"。区别于手动操作——如果你的部署还有"人肉步骤"，那就不能称之为真正的 pipeline。

---

### 16. artifact
- **义项 1: 构建产物 (n.)** — 构建过程产生的文件（如 .jar, .zip, Docker image）
  - "The build **artifact** is uploaded to the artifact repository after a successful build."
- **义项 2: 归档文件 (n.)** — 存储并共享的构建输出
  - "You can download the latest **artifact** from the GitHub Actions page."
- **义项 3: 产出物 (n.)** — 任何过程中产生的结果或文档
  - "The design document is an important **artifact** of the planning phase."
- **用法提示:** 在 CI/CD 语境中，artifact 通常指 build artifact。不要和 dependency 混淆——dependency 是"你依赖的东西"，artifact 是"你产出的东西"。

---

### 17. threshold
- **义项 1: 阈值 (n.)** — 触发某个操作或报警的临界值
  - "Set the alert **threshold** to 90% CPU usage so we get notified before the server crashes."
- **义项 2: 警戒线 (n.)** — 在监控和可观测性中的界限值
  - "When the error rate crosses the **threshold** of 1%, the on-call engineer gets paged."
- **义项 3: 门槛 (n.)** — 进入某种状态的边界
  - "Below a certain **threshold** of traffic, it's cheaper to use serverless instead of dedicated servers."
- **用法提示:** threshold 常与动词 cross/exceed/reach 搭配。如 "cross the **threshold**"（超过阈值）、"set a **threshold**"（设置阈值）。

---

### 18. redundancy
- **义项 1: 冗余/高可用 (n.)** — 通过复制组件提高系统可靠性
  - "We need **redundancy** across multiple availability zones to ensure high availability."
- **义项 2: 冗余数据 (n.)** — 重复存储的数据（有时是浪费，有时是必要备份）
  - "The data deduplication process removes **redundancy** to save storage costs."
- **义项 3: 冗余配置 (n.)** — 多于最低需要的配置或人员
  - "The system has built-in **redundancy** : if one server fails, another takes over automatically."
- **用法提示:** 在系统设计面试中，"redundancy" 是一个高频话题。redundant 是形容词。记住：redundancy ≠ waste——在系统设计中，它是高可用的必要手段。

---

### 19. latency
- **义项 1: 网络延迟 (n.)** — 数据从源到目的地的传输时间
  - "Users in Asia experience higher **latency** because the servers are located in the US."
- **义项 2: 响应延迟 (n.)** — 系统从接收请求到返回响应的间隔时间
  - "We optimized the database queries to reduce API **latency** from 500ms to 50ms."
- **义项 3: 等待时间 (n.)** — 任何需要等待的时间
  - "The cold start **latency** of the serverless function is about 2 seconds."
- **用法提示:** latency 常与 throughput 一起讨论——latency = 快不快（响应时间），throughput = 多不多（处理数量）。"Low latency" = 好，"high latency" = 不好。口诀：「延迟」越「低」越好。

---

### 20. throughput
- **义项 1: 吞吐量 (n.)** — 系统在单位时间内能处理的数据量
  - "The new caching layer increased **throughput** from 1,000 to 10,000 requests per second."
- **义项 2: 处理能力 (n.)** — 系统在单位时间内完成的任务数量
  - "The database can handle a **throughput** of 5,000 write operations per second."
- **义项 3: 数据传输速率 (n.)** — 网络或 I/O 的传输效率
  - "We measured the disk I/O **throughput** to identify the bottleneck in the data pipeline."
- **用法提示:** throughput 通常用复数单位表示：requests per second (RPS), transactions per second (TPS), queries per second (QPS)。注意："high throughput" = 好，"high latency" = 不好。

---

### 词汇速查表

| 编号 | 名词 | 中文核心意思 | 常见搭配 |
|------|------|-------------|---------|
| 1 | repository | 仓库 | clone/push/pull the repository |
| 2 | dependency | 依赖 | install/manage/update dependencies |
| 3 | endpoint | 端点 | expose/call/secure the endpoint |
| 4 | interface | 接口 | define/implement the interface |
| 5 | variable | 变量 | declare/set/get a variable |
| 6 | function | 函数 | call/define/export a function |
| 7 | parameter | 参数 | pass/accept/tune parameters |
| 8 | argument | 实参/论据 | pass an argument / make an argument |
| 9 | database | 数据库 | query/backup/migrate the database |
| 10 | query | 查询 | run/optimize/schedule a query |
| 11 | schema | 模式 | define/update/migrate the schema |
| 12 | instance | 实例 | launch/stop/terminate an instance |
| 13 | container | 容器 | run/build/orchestrate container |
| 14 | deployment | 部署 | perform/rollback/schedule deployment |
| 15 | pipeline | 管道 | build/trigger/optimize the pipeline |
| 16 | artifact | 产物 | upload/store/download artifact |
| 17 | threshold | 阈值 | set/cross/exceed the threshold |
| 18 | redundancy | 冗余 | add/provide/ensure redundancy |
| 19 | latency | 延迟 | reduce/minimize/low latency |
| 20 | throughput | 吞吐量 | improve/increase/high throughput |

---

## 3. Sentence-Making Practice

以下 10 个练习结合了**上周的 20 个开发动词**、**本周的 20 个开发名词**，以及**一般现在时和现在进行时**。每个练习模拟一个真实工作场景。先自己写，再对照参考答案。

---

### 1. 你向新同事解释你的团队什么情况下会自动部署。用一般现在时（Simple Present）和名词 **pipeline**、动词 **trigger**。

**参考答案:** "The CI pipeline **triggers** an automatic deployment whenever we merge a pull request to the main branch."
> （一般现在时，描述常规流程。主语 "The CI pipeline" 是第三人称单数 → trigger**s**。whenever 引导时间状语从句。）

---

### 2. 你正在处理一个生产事故——数据库查询非常慢。用现在进行时（Present Continuous）和名词 **query**、动词 **debug**。

**参考答案:** "I **'m debugging** a slow **query** that is blocking the user dashboard from loading."
> （现在进行时：am + debugging。描述此刻正在进行的动作。 "that is blocking" 是另一个现在进行时结构，描述"正在阻塞"的过程。）

---

### 3. 在技术文档中，描述一个 API 端点的作用。用一般现在时（Simple Present）和名词 **endpoint**、动词 **return**。

**参考答案:** "This **endpoint** **returns** user profile data in JSON format when you send a GET request to `/users/:id`."
> （一般现在时，描述 API 的固定功能。主语 "This endpoint" 是第三人称单数 → return**s**。注意：即使读者还没调用它，你描述的也是"这个端点每次都会这样工作"。）

---

### 4. 你在 standup meeting 上说本周的工作内容——团队正在重构整个代码仓库的结构。用现在进行时（Present Continuous）和名词 **repository**、动词 **refactor**。

**参考答案:** "We **'re refactoring** the entire **repository** to adopt a modular architecture this sprint."
> （现在进行时：are + refactoring。描述当前 sprint 的临时任务。 "this sprint" 表示这是一段时期内的安排，不是永久性的。现在进行时强调"正在进行中"。"refactoring" 注意拼写——不需要双写 t，以 t 结尾但重音不在最后一个音节上。）

---

### 5. 在 sprint planning 会议上，告知团队下个 sprint 开始和结束的时间。用一般现在时（Simple Present，表固定安排）和名词 **pipeline**。

**参考答案:** "The next sprint **starts** next Tuesday and the release **pipeline** **runs** every Friday."
> （一般现在时表固定时间表：start**s** 和 run**s**。虽然说的是将来时间，但因为 sprint 周期是定好的，所以用一般现在时。注意：不能说 "The pipeline is running every Friday"——那是描述"正在运行"，而这里说的是每周五的固定安排。）

---

### 6. 你明天要和产品经理开会，讨论新功能的接口定义。用现在进行时（Present Continuous，表将来安排）和名词 **interface**、动词 **implement**。

**参考答案:** "I **'m meeting** the PM tomorrow to discuss the **interface** we **'re implementing** for the new feature."
> （现在进行时表将来安排：'m meeting。第二个现在进行时 "we're implementing" 描述当前 sprint 正在进行的功能实现。两个现在进行时的使用场景不同：一个是未来安排，一个是当前进度。）

---

### 7. 解释为什么某个容器没有正常运行。用一般现在时的否定形式（don't/doesn't）和名词 **container**、名词 **dependency**。

**参考答案:** "The **container** **doesn't start** because one of its **dependencies** **isn't** available in the registry."
> （一般现在时否定：doesn't + 动词原形（start）。"isn't available" 也是 Simple Present 否定。整个描述是当前的状态事实——"这个容器不启动"不是一个动作，而是一个状态。）

---

### 8. 你在 standup 上问前端同事，他是否正在处理用户界面的缓存问题。用现在进行时的疑问句形式（Present Continuous Question）和名词 **interface**、动词 **cache**。

**参考答案:** "**Are** you **caching** the API responses on the frontend **interface** to improve load times?"
> （现在进行时疑问句：Are + 主语 + V-ing。主语是 "you" → 用 "are"。这句话问的是"正在做"的临时性工作。如果问一般情况：❌ "Do you cache..." — 那就变成问"你平时是不是都缓存"了，语境不对。）

---

### 9. 你发现数据库的延迟（latency）通常很低，但此刻突然飙升。用一般现在时描述通常情况，再用现在进行时描述当前异常。

**参考答案:** "The **latency** is usually under 50ms, but it **'s spiking** to over 500ms right now — we need to investigate."
> （前半句用一般现在时：is（通常情况，客观事实）。后半句用现在进行时：'s spiking（此刻正在发生，异常情况）。"right now" 是现在进行时的典型标志词。同一个句子里两种时态切换，体现"常态 vs. 异常"的对比。）

---

### 10. 你想知道同事的实例（instance）为什么没有冗余（redundancy）。用一般现在时疑问句（Simple Present Question）和这两个名词。

**参考答案:** "Why **does** this **instance** **have** no **redundancy**? If it fails, we'll lose the service."
> （一般现在时疑问句：Does + 主语 + 动词原形。这里用 "does...have" 而不是 "has"——疑问句中用了 does，动词还原为 have。"Why does this instance have..." 询问的是一个配置状态——"为什么这个实例没有冗余"。）

---

### 练习覆盖检查

| 语法点 | 题号 |
|--------|------|
| Simple Present（常规/事实） | 1, 3 |
| Simple Present（固定时间表） | 5 |
| Simple Present（否定） | 7 |
| Simple Present（疑问） | 10 |
| Present Continuous（此刻进行） | 2, 4 |
| Present Continuous（将来安排） | 6 |
| Present Continuous（疑问） | 8 |
| Simple Present vs Continuous（对比） | 9 |

| 本周名词重点 | 题号 |
|-------------|------|
| pipeline | 1, 5 |
| query | 2 |
| endpoint | 3 |
| repository | 4 |
| interface | 6, 8 |
| container, dependency | 7 |
| latency | 9 |
| instance, redundancy | 10 |

---

## 4. Weekend Review

### 易混淆词对比

**1. parameter vs. argument（形参 vs. 实参）**
- "This function takes two **parameters** : `userId` and `callback`."（定义时写的是 parameter）
- "When calling the function, pass the correct **arguments**."（调用时传的是 argument）
- 关键区别：parameter = 函数定义中的"占位符"；argument = 调用时传入的"实际值"。先有 parameter 再有 argument。

**2. latency vs. throughput（延迟 vs. 吞吐量）**
- "We need to reduce **latency** because users are experiencing slow page loads."（速度问题——每次请求慢）
- "We need to increase **throughput** because the server can't handle the traffic volume."（容量问题——整体处理量不够）
- 关键区别：latency = 每次请求的响应时间（越快越好），throughput = 单位时间能处理的请求量（越大越好）。两者通常需要权衡——有时优化 latency 会降低 throughput。

**3. container vs. image（容器 vs. 镜像）**
- "We built a Docker **image** from the Dockerfile."（镜像：只读模板，类似于"类"）
- "We started a **container** from the image on the production server."（容器：运行中的实例，类似于"对象"）
- 关键区别：image = 静态模板，container = 运行中的实例。一个 image 可以启动多个 container。类比 OOP：image = class，container = object。

**4. schema vs. database（模式 vs. 数据库）**
- "We need to update the **schema** to add a new column."（改了表结构——结构层面的变化）
- "We need to migrate the **database** to a new server."（迁移了整个数据库——物理/基础设施层面的变化）
- 关键区别：schema = 数据结构的"蓝图"，database = 存储数据的"容器"。一个 database 可以有多个 schema。

**5. deploy (v.) vs. deployment (n.)（部署动作 vs. 部署过程/版本）**
- "We **deploy** to staging first to catch any issues."（动作/过程——动词）
- "The **deployment** was rolled back due to a database issue."（事件/版本——名词）
- 关键区别：deploy = 你要做的事（动作），deployment = 描述这件事（名词，可指过程也可指具体的发布版本）。在简历上你要写 "I **deploy** regularly" 或 "led the **deployment** of..."，注意词性。

---

### 语法自我检测清单

逐一检查，诚实地标记自己是否掌握：

**一般现在时（Simple Present）：**
- [ ] 我能说出一一般现在时的 4 种核心用法吗？（事实、习惯、时间表、状态）
- [ ] 我能在第三人称单数主语的句子里正确加 -s 吗？
- [ ] 我能正确使用 don't/doesn't 构成否定句吗？（注意动词还原）
- [ ] 我能用 Do/Does 正确构成疑问句吗？
- [ ] 我知道哪些时间标志词提示用一般现在时吗？（always, usually, every day, on Mondays...）

**现在进行时（Present Continuous）：**
- [ ] 我能说出现在进行时的 3 种核心用法吗？（此刻正在、临时情况、将来安排）
- [ ] 我在写句子时不会忘记 be 动词吗？（❌ "I debugging" / ✅ "I **am** debugging"）
- [ ] 我能在否定和疑问句中正确调整语序吗？
- [ ] 我能正确写出 V-ing 形式吗？（run→running, debug→debugging, write→writing）
- [ ] 我能识别哪些动词是状态动词、不能用于进行时吗？

**时态对比：**
- [ ] 我能解释 "The API returns JSON" 和 "The API is returning a 503 error" 的含义差别吗？
- [ ] 如果我说 "I work on the platform team" 和 "I'm working on a new feature"，两句话的时态选择理由是什么？
- [ ] 看到 "right now"、"every Monday"、"this sprint"、"always" 这些词，我能快速反应出该用什么时态吗？

---

### 周末练习建议

**建议用时：** 周六 45 分钟 + 周日 45 分钟

**周六练习：时态扫描**
打开你最近使用的一个开源项目的 README 或技术文档（比如 React、Vue、Express 的文档）。找 10 个使用了 Simple Present 的句子和 5 个使用了 Present Continuous 的句子。逐句分析：
- 为什么选这个时态？（事实？习惯？当前情况？）
- 主语是第几人称？动词是否加 -s？
- 如果是否定句或疑问句，结构是否正确？
- 你可能会惊讶地发现，技术文档中 80% 以上的句子都用的是 Simple Present。

**周日练习：时态切换写作**
写 5 组"对比句"，每组包含一个 Simple Present 句子和一个 Present Continuous 句子，表达同一个话题的"常态"和"此刻状态"。例如：

| 话题 | Simple Present（常态） | Present Continuous（此刻/临时） |
|------|----------------------|-------------------------------|
| 部署 | We deploy every Monday. | We are deploying a hotfix right now. |
| 数据库 | The database has 64GB RAM. | The database is running low on memory. |
| 你自己 | I work on the frontend team. | I'm working on the auth module. |

写完后读出来，感受两种时态在"时间感"上的区别。Simple Present 读起来"稳定"，Present Continuous 读起来"临时"。

**下周生存贴士：**
- Standup 上想说"我在做..."的时候，用 "I'm working on..." 开头（现在进行时）
- 想说"我们每周一上线"的时候，用 "We deploy every Monday"（一般现在时）
- 想问"你在干什么"的时候，用 "What are you working on?"（现在进行时疑问句）
- 想写技术文档的时候，全部用一般现在时——你描述的是"这个系统怎么工作"，是客观事实

---

> **下周预告：** Week 3 将学习**一般过去时（Simple Past）和现在完成时（Present Perfect）**——这是中国学生最难区分的两个时态。我们还会学习 20 个高频开发形容词。周末好好复习，下周见。
