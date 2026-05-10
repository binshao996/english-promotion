# Week 01: 五大基本句型 + 300 核心词汇 + 复杂句分析

> 目标：彻底掌握英语五大基本句型，学会深入分析复杂句子的结构，并积累 300 个高频词汇（开发 + 日常）。本周的重点是从"看懂简单句"进阶到"能拆解复杂句"。

---

## 1. Grammar: 句子结构

### 1.1 五大基本句型（快速回顾）

英语所有句子，无论多长多复杂，最终都可以归结为以下五种基础骨架。理解这五种结构是分析复杂句的前提。

---

**Pattern 1: S + V (主语 + 不及物动词)**

不及物动词的动作在主语这里就结束了，不需要宾语。常见的如：crash, work, run, fail, succeed, sleep, wait, happen。

- "The server **crashed**." 服务器崩溃了。
- "The deployment **failed**." 部署失败了。
- 关键：不及物动词后面不能直接跟宾语。❌ "The server crashed the process." ✅ "The server crashed."

---

**Pattern 2: S + V + O (主语 + 及物动词 + 宾语)**

及物动词的动作需要作用在某物上，所以必须跟宾语。大部分动词是及物的。

- "I **wrote** a script." 我写了一个脚本。
- "We **fixed** the memory leak." 我们修复了内存泄漏。
- 关键：及物动词必须有宾语。❌ "Did you fix the bug?" — "Yes, I fixed." ✅ "Yes, I fixed it."

---

**Pattern 3: S + V + C (主语 + 系动词 + 主语补足语)**

系动词像"等号"，连接主语和描述它的补足语（表语）。最常见的是 be，还有 look, seem, become, feel, remain 等。

- "The code **is** messy." 代码很乱。
- "This bug **seems** critical." 这个 bug 看起来很严重。
- 关键：系动词后跟形容词或名词作补足语。❌ "The code is messily." ✅ "The code is messy."

---

**Pattern 4: S + V + O + O (主语 + 动词 + 间接宾语 + 直接宾语)**

动词需要两个宾语：一个"接收者"（人，间接宾语），一个"内容"（物，直接宾语）。常见动词：send, give, tell, show, offer, assign, pass。

- "She **sent** me the patch." 她把补丁发给了我。
- "The lead **assigned** me a new task." 主管给我分配了一个新任务。
- 关键：顺序是"人→物"。调换时需加介词：sent the patch **to** me。

---

**Pattern 5: S + V + O + C (主语 + 动词 + 宾语 + 宾语补足语)**

宾语补足语描述宾语的状态，宾语和补足语之间有隐含的"主谓关系"。常见动词：make, keep, find, consider, call, set, leave。

- "We **made** the API faster." 我们让 API 更快了。（the API is faster）
- "I **find** this language confusing." 我觉得这门语言令人困惑。
- 关键：Pattern 4 的双宾语之间没有主谓关系（me ≠ the patch），Pattern 5 的有（the API = faster）。

---

**快速对照表**

| 模式 | 结构 | 示例 | 关键特征 |
|------|------|------|---------|
| P1: S+V | 主语 + 不及物动词 | The server crashed. | 动词后不加宾语 |
| P2: S+V+O | 主语 + 及物动词 + 宾语 | I wrote a script. | 必须有宾语 |
| P3: S+V+C | 主语 + 系动词 + 补足语 | The code is messy. | 系动词 = "等号" |
| P4: S+V+O+O | 主语 + 动词 + 间宾 + 直宾 | She sent me the patch. | "人→物"顺序 |
| P5: S+V+O+C | 主语 + 动词 + 宾语 + 补足语 | We made the API faster. | 宾语与补足语有主谓关系 |

---

### 1.2 复杂句深度拆解（本周核心）

本周的核心技能：**无论句子多长，能逐层拆解，识别每个成分**。下面 6 个句子覆盖了定语从句、状语从句、宾语从句、非限制性定语从句等最常见的复杂结构。

---

#### 复杂句 1

**"The server that we deployed last Monday crashed because the database connection pool, which had been running without issues for months, suddenly timed out."**

**中文翻译：** 我们上周一部署的那台服务器崩溃了，因为那个已经正常运行了好几个月的数据库连接池突然超时了。

**逐词句法分析：**

```
The server  ——  that we deployed last Monday  ——  crashed  ——  because  ——  the database connection pool  ——  , which had been running without issues for months,  ——  suddenly timed out.

层级 1 — 主句主干：
  ├── The server (主语/名词短语)
  │     └── 被后边的定语从句"that we deployed last Monday"修饰
  └── crashed (谓语/不及物动词) — 主句的谓语，说明服务器发生了什么

层级 2 — that we deployed last Monday (定语从句，修饰 The server)：
  ├── that (关系代词/宾语) — 指代 The server，在从句中作 deployed 的宾语
  ├── we (主语/代词) — 从句的主语
  ├── deployed (谓语/及物动词) — 从句的谓语
  └── last Monday (状语/名词短语) — 时间状语，说明 deployed 发生的时间

层级 3 — because ... timed out (原因状语从句，说明崩溃的原因)：
  ├── because (连词) — 引导原因状语从句，连接主句和从句
  ├── the database connection pool (主语/名词短语) — 从句的主语
  │     └── 被插入的非限制性定语从句修饰
  ├── , which had been running without issues for months, (非限制性定语从句)
  │     ├── which (关系代词/主语) — 指代 the database connection pool
  │     ├── had been running (谓语/过去完成进行时) — 强调持续到过去某时的动作
  │     ├── without issues (介词短语/状语) — 方式状语，修饰 running
  │     └── for months (介词短语/状语) — 时间状语，修饰 running
  ├── suddenly (副词/状语) — 修饰 timed out
  └── timed out (谓语/动词短语) — 从句的谓语，说明连接池发生了什么

关键连接点：
  - that 引导的定语从句 → 限定 the server（限制性 = 不可或缺的信息）
  - because 引导的原因状语从句 → 解释崩溃的原因（主从关系）
  - which 引导的非限制性定语从句 → 补充说明 connection pool（非限制性 = 可有可无的额外信息，前后用逗号隔开）
```

---

#### 复杂句 2

**"Although the code looked correct, the bug that the junior developer introduced caused the entire pipeline to fail."**

**中文翻译：** 虽然代码看起来是对的，但那个初级开发者引入的 bug 导致整个流水线失败了。

**逐词句法分析：**

```
Although the code looked correct  ——  , the bug  ——  that the junior developer introduced  ——  caused  ——  the entire pipeline  ——  to fail.

层级 1 — 让步状语从句：
  ├── Although (连词) — 引导让步状语从句，表示"虽然/尽管"
  ├── the code (主语/名词短语) — 从句的主语
  ├── looked (系动词) — look 在这里不是"看"，而是系动词"看起来"
  └── correct (主语补足语/形容词) — 描述 code 的状态

层级 2 — 主句主干：
  ├── the bug (主语/名词短语) — 主句的主语
  │     └── 被后边的定语从句"that the junior developer introduced"修饰
  ├── caused (谓语/及物动词) — 主句的谓语动词
  ├── the entire pipeline (宾语/名词短语) — caused 的宾语
  └── to fail (宾语补足语/不定式短语) — 说明 pipeline 的结果状态
        └── 结构分析：cause + O + to do = "导致某物做某事"

层级 3 — that the junior developer introduced (定语从句，修饰 the bug)：
  ├── that (关系代词/宾语) — 指代 the bug，在从句中作 introduced 的宾语
  ├── the junior developer (主语/名词短语) — 从句的主语
  └── introduced (谓语/及物动词) — 从句的谓语

关键连接点：
  - Although 引导的让步状语从句 = 与主句形成"对比关系"
  - that 引导的定语从句 = 限定 the bug，告诉我们"是哪个 bug"
  - to fail 不定式短语 = 作宾语补足语，属于 Pattern 5 (S+V+O+C) 结构
```

---

#### 复杂句 3

**"We made the API faster by implementing a caching layer that stores frequently accessed data in memory."**

**中文翻译：** 我们通过实现一个缓存层来让 API 更快了，这个缓存层把频繁访问的数据存储在内存中。

**逐词句法分析：**

```
We  ——  made  ——  the API  ——  faster  ——  by implementing a caching layer  ——  that stores frequently accessed data in memory.

层级 1 — 主句主干 (Pattern 5: S+V+O+C)：
  ├── We (主语/代词) — 动作的执行者
  ├── made (谓语/及物动词) — 使役动词，"使/让"
  ├── the API (宾语/名词短语) — 动作的接受者
  └── faster (宾语补足语/形容词比较级) — 描述宾语变成的状态
        └── 隐含关系：the API (is) faster — 宾语和补足语之间有主谓关系

层级 2 — by implementing a caching layer (介词短语/方式状语)：
  ├── by (介词) — "通过……方式"
  └── implementing a caching layer (动名词短语) — 介词 by 的宾语
        ├── implementing (动名词/动词的-ing形式用作名词)
        └── a caching layer (宾语/名词短语) — implementing 的宾语

层级 3 — that stores frequently accessed data in memory (定语从句，修饰 a caching layer)：
  ├── that (关系代词/主语) — 指代 a caching layer，在从句中作主语
  ├── stores (谓语/及物动词) — 从句的谓语动词
  ├── frequently accessed data (宾语/名词短语) — 从句的宾语
  │     ├── frequently (副词/状语) — 修饰 accessed
  │     └── accessed (过去分词/定语) — 作定语修饰 data，"被频繁访问的"
  └── in memory (介词短语/状语) — 地点状语，说明存储位置

关键连接点：
  - made + O + adj = Pattern 5 的典型结构（使役用法）
  - by + 动名词 = 表示"方式/手段"的状语
  - that 引导的定语从句 = 限定 caching layer 的功能
  - 过去分词 accessed 作定语 = 省略了"which is"的被动结构
```

---

#### 复杂句 4

**"The team sent me the patch after I had spent three hours debugging the memory leak that was affecting production."**

**中文翻译：** 在我花了三个小时调试那个影响生产环境的内存泄漏之后，团队把补丁发给了我。

**逐词句法分析：**

```
The team  ——  sent  ——  me  ——  the patch  ——  after  ——  I  ——  had spent  ——  three hours  ——  debugging the memory leak  ——  that was affecting production.

层级 1 — 主句主干 (Pattern 4: S+V+O+O)：
  ├── The team (主语/名词短语) — 动作的执行者
  ├── sent (谓语/及物动词) — 双宾语动词，"发送"
  ├── me (间接宾语/代词) — 动作的接收者（人）
  └── the patch (直接宾语/名词短语) — 动作的内容（物）

层级 2 — after ... production (时间状语从句，说明发送的时间)：
  ├── after (连词) — 引导时间状语从句，"在……之后"
  ├── I (主语/代词) — 从句的主语
  ├── had spent (谓语/过去完成时) — 表示"主句的 sent 发生时，这个动作已经完成了"
  ├── three hours (宾语/名词短语) — 时间作为 spent 的宾语
  └── debugging the memory leak ... (现在分词短语/状语) — 伴随动作
        ├── debugging (现在分词) — 说明"花时间做了什么事"
        └── the memory leak (宾语/名词短语) — debugging 的宾语
              └── 被后面的定语从句修饰

层级 3 — that was affecting production (定语从句，修饰 the memory leak)：
  ├── that (关系代词/主语) — 指代 the memory leak，在从句中作主语
  ├── was affecting (谓语/过去进行时) — 强调当时正在持续的动作
  └── production (宾语/名词短语) — 从句的宾语

关键连接点：
  - sent + me + the patch = Pattern 4 (S+V+O间+O直)
  - after 引导时间状语从句 = 明确先后顺序
  - 过去完成时 had spent = 强调"在主句动作之前已完成"
  - 现在分词 debugging = 伴随状语，说明 spent three hours 的具体内容
  - that 引导定语从句 = 限定是"哪一个" memory leak
```

---

#### 复杂句 5

**"The deployment failed, but the rollback succeeded, which meant that no users were affected by the incident."**

**中文翻译：** 部署失败了，但回滚成功了，这意味着没有用户受到该事故的影响。

**逐词句法分析：**

```
The deployment failed  ——  , but  ——  the rollback succeeded  ——  , which meant  ——  that  ——  no users were affected by the incident.

层级 1 — 并列复合句：
  ├── The deployment failed (独立分句1)
  │     ├── The deployment (主语/名词短语)
  │     └── failed (谓语/不及物动词)
  ├── but (并列连词) — 连接两个并列分句，表示"转折"
  └── the rollback succeeded (独立分句2)
        ├── the rollback (主语/名词短语)
        └── succeeded (谓语/不及物动词)

层级 2 — , which meant that ... (非限制性定语从句，修饰整个前句)：
  ├── , which (关系代词/主语) — 指代前面整句话的内容
  │     └── 非限制性定语从句 + 逗号 = 表示"which 指代前文整件事"
  └── meant (谓语/及物动词) — 从句的谓语

层级 3 — that no users were affected by the incident (宾语从句，作 meant 的宾语)：
  ├── that (连词) — 引导宾语从句，无实际意义，起连接作用
  ├── no users (主语/名词短语) — 从句的主语
  ├── were affected (谓语/被动语态) — "被影响"
  └── by the incident (介词短语/状语) — 被动语态的动作发出者

关键连接点：
  - but 连接两个分句 = 转折关系，形成"对比"
  - which 指代前文整个句子 = 非限制性定语从句的"句指"用法
  - that 引导宾语从句 = 作 meant 的"内容"
  - 被动语态 were affected by = 强调"用户"是承受动作的一方
```

---

#### 复杂句 6

**"When you push to the main branch, the CI pipeline triggers a series of automated tests that validate every endpoint before the deployment proceeds."**

**中文翻译：** 当你推送到主分支时，CI 流水线会触发一系列自动化测试，这些测试在部署继续之前验证每个端点。

**逐词句法分析：**

```
When you push to the main branch  ——  , the CI pipeline  ——  triggers  ——  a series of automated tests  ——  that validate every endpoint  ——  before the deployment proceeds.

层级 1 — When ... branch (时间状语从句，说明触发的时间)：
  ├── When (连词) — 引导时间状语从句，"当……时"
  ├── you (主语/代词) — 从句的主语
  ├── push (谓语/不及物动词) — 从句的谓语
  └── to the main branch (介词短语/状语) — 目标/方向状语

层级 2 — 主句主干：
  ├── the CI pipeline (主语/名词短语) — 主句的主语
  ├── triggers (谓语/及物动词) — 主句的谓语（一般现在时，表示一般情况）
  └── a series of automated tests (宾语/名词短语) — triggers 的宾语
        └── 被后面的定语从句修饰

层级 3 — that validate every endpoint (定语从句，修饰 tests)：
  ├── that (关系代词/主语) — 指代 tests，在从句中作主语
  ├── validate (谓语/及物动词) — 从句的谓语
  └── every endpoint (宾语/名词短语) — 从句的宾语

层级 4 — before the deployment proceeds (时间状语从句，修饰 validate)：
  ├── before (连词) — 引导时间状语从句，"在……之前"
  ├── the deployment (主语/名词短语) — 从句的主语
  └── proceeds (谓语/不及物动词) — 从句的谓语

关键连接点：
  - When 引导时间状语从句 = 表明主句动作发生的"时间窗口"
  - that 引导定语从句 = 限定是什么样的 tests
  - before 引导时间状语从句 = 进一步限定 validate 发生的时间
  - 嵌套结构：主句 → 定语从句 → 从句内的状语从句（三层嵌套）
  - 使用一般现在时 = 描述"一般情况 / 一贯如此"
```

---

## 2. Vocabulary: 300 核心词汇

---

### Group 1: Core Dev Verbs（50 个核心开发动词）

---

### 1. deploy
- **义项 1: 部署 (动词)** — To release software to a server or runtime environment
  - "We deploy new features to production every Monday."
- **义项 2: 调度/安排 (动词)** — To strategically arrange or distribute resources
  - "The team deployed three senior engineers to handle the outage."
- **义项 3: 施展/运用 (动词)** — To effectively use a skill or strategy
  - "She deployed her knowledge of distributed systems to optimize the query."

---

### 2. implement
- **义项 1: 实现功能 (动词)** — To write code that realizes a feature or interface
  - "I need to implement the user authentication module this sprint."
- **义项 2: 执行方案 (动词)** — To put a plan or decision into action
  - "We decided to implement a rate-limiting policy for the public API."
- **义项 3: 引入系统 (动词)** — To introduce and enable a system or tool
  - "The company implemented a new incident management system last quarter."

---

### 3. execute
- **义项 1: 运行代码 (动词)** — To run a piece of code or a command
  - "The cron job executes a cleanup script every midnight."
- **义项 2: 执行计划 (动词)** — To carry out a plan according to schedule
  - "We executed the migration plan without any downtime."
- **义项 3: 签署执行 (动词)** — To formally sign or execute a contract/agreement
  - "The contract was executed after both parties agreed on the SLA."

---

### 4. configure
- **义项 1: 配置参数 (动词)** — To set parameters or options for software
  - "You need to configure the database connection string in the .env file."
- **义项 2: 设置系统 (动词)** — To set up a system in a particular way
  - "We configured the load balancer to route 10% of traffic to the new version."
- **义项 3: 自定义调整 (动词)** — To adjust settings according to personal needs
  - "I configured my IDE to auto-format code on save."

---

### 5. trigger
- **义项 1: 触发事件 (动词)** — To cause an automated process to begin
  - "Pushing to the main branch triggers a CI build automatically."
- **义项 2: 引发问题 (动词)** — To cause a negative situation or chain reaction
  - "The race condition triggered a cascade of service failures."
- **义项 3: 调用函数 (动词)** — To manually or automatically invoke a function
  - "The webhook triggers a serverless function to process the payment."

---

### 6. resolve
- **义项 1: 修复解决 (动词)** — To fix a problem or error
  - "The SRE team resolved the production incident in under 30 minutes."
- **义项 2: 解析地址 (动词)** — To convert a domain name to an IP address
  - "DNS resolved the domain to the correct IP address."
- **义项 3: 下定决心 (动词)** — To make a firm decision about something
  - "We resolved to migrate from monolith to microservices by Q3."

---

### 7. debug
- **义项 1: 调试代码 (动词)** — To find and fix errors in code
  - "I have been debugging this race condition for three hours."
- **义项 2: 排查问题 (动词)** — To troubleshoot issues in a broader context
  - "We need to debug why the production traffic is dropping."
- **义项 3: 检修设备 (动词)** — To diagnose faults in electronic devices
  - "The IoT device logs help us debug connectivity issues in the field."

---

### 8. fetch
- **义项 1: 获取数据 (动词)** — To retrieve data from a remote source
  - "The frontend fetches user data from the API on page load."
- **义项 2: 拉取更新 (动词)** — To pull updates from a remote git repository
  - "Make sure to fetch the latest changes before you rebase."
- **义项 3: 检索记录 (动词)** — To retrieve data from a database or storage
  - "The query fetches all orders placed in the last 24 hours."

---

### 9. render
- **义项 1: 渲染页面 (动词)** — To draw UI on screen in a browser
  - "React renders the component tree when the state changes."
- **义项 2: 生成输出 (动词)** — To convert data into a readable format
  - "The template engine renders HTML from the markdown content."
- **义项 3: 提供交付 (动词)** — To provide a service or result
  - "The GPU renders the 3D model in real time during the simulation."

---

### 10. parse
- **义项 1: 解析格式 (动词)** — To analyze and understand structured text or code
  - "The JSON parser parses the response body into a JavaScript object."
- **义项 2: 提取信息 (动词)** — To extract useful data from complex text
  - "The script parses the server logs to extract error frequencies."
- **义项 3: 分析理解 (动词)** — To carefully analyze information in a non-tech context
  - "It took me a while to parse what the reviewer meant in their comments."

---

### 11. validate
- **义项 1: 验证输入 (动词)** — To check if data meets required rules or formats
  - "The form validates the email address before submitting the data."
- **义项 2: 确认有效 (动词)** — To test whether something is valid or correct
  - "We need to validate the hypothesis before building the full feature."
- **义项 3: 使生效 (动词)** — To formally confirm that something is valid
  - "The security audit validated our compliance with PCI DSS standards."

---

### 12. merge
- **义项 1: 合并代码 (动词)** — To integrate one branch into another in version control
  - "Can you merge this pull request after the CI checks pass?"
- **义项 2: 合并数据 (动词)** — To combine multiple data sets into one
  - "The function merges the user's local changes with the server state."
- **义项 3: 融合结合 (动词)** — To combine two things in a broader sense
  - "This new role merges DevOps responsibilities with data engineering."

---

### 13. rollback
- **义项 1: 回滚版本 (动词)** — To revert code or version to a previous state
  - "We had to rollback the deployment because the new version had a memory leak."
- **义项 2: 撤销操作 (动词)** — To undo or reverse an operation
  - "The database transaction will rollback automatically if the script fails."
- **义项 3: 退回方案 (动词)** — To abandon a strategy and return to the previous approach
  - "After two weeks of trying the new framework, we rolled back to the previous stack."

---

### 14. refactor
- **义项 1: 重构代码 (动词)** — To optimize code structure without changing external behavior
  - "I spent the afternoon refactoring the legacy authentication module."
- **义项 2: 优化结构 (动词)** — To reorganize system architecture for maintainability
  - "We need to refactor this function — it has grown to over 500 lines."
- **义项 3: 重新设计 (动词)** — To restructure any process or workflow broadly
  - "The team refactored their sprint process to include more pair programming."

---

### 15. deprecate
- **义项 1: 弃用 API (动词)** — To formally declare a feature no longer recommended
  - "The team deprecated the v1 API in favor of the v2 endpoint."
- **义项 2: 淘汰方法 (动词)** — To announce that a method or practice is no longer supported
  - "Python 3.8 has been deprecated and will no longer receive security updates."
- **义项 3: 反对批评 (动词)** — To express strong disapproval in a non-tech context
  - "The security team deprecated the use of HTTP for internal services."

---

### 16. iterate
- **义项 1: 迭代开发 (动词)** — To improve a product incrementally through repeated cycles
  - "We plan to launch a minimal version first and iterate based on user feedback."
- **义项 2: 循环遍历 (动词)** — To access each element of a collection sequentially
  - "The function iterates over the array and checks each element."
- **义项 3: 重复改进 (动词)** — To repeat a process to achieve better results
  - "We iterated on the design five times before the final version."

---

### 17. initialize
- **义项 1: 初始化对象 (动词)** — To create an object or variable and assign an initial value
  - "The constructor initializes the database connection pool."
- **义项 2: 初始化项目 (动词)** — To set up a new project or system
  - "Run npm init to initialize a new Node.js project."
- **义项 3: 启动过程 (动词)** — To start or prepare a process for execution
  - "The system initializes all services on startup, which takes about 30 seconds."

---

### 18. log
- **义项 1: 记录日志 (动词)** — To record events or information during program execution
  - "The application logs every incoming request with a timestamp."
- **义项 2: 登录系统 (动词)** — To enter credentials to access a system
  - "You need to log into the VPN before accessing internal resources."
- **义项 3: 记录工时 (动词)** — To record working hours in a time-tracking tool
  - "Don't forget to log your hours in the time-tracking tool."

---

### 19. cache
- **义项 1: 缓存数据 (动词)** — To store data temporarily for faster access
  - "The application caches the API response for 5 minutes to reduce latency."
- **义项 2: 存储结果 (动词)** — To save computational results to avoid recalculation
  - "We cache the rendered HTML so the server does not regenerate it on every request."
- **义项 3: 储备备用 (动词)** — To reserve something for future use in a broader sense
  - "The CDN caches static assets across edge locations worldwide."

---

### 20. scale
- **义项 1: 水平扩展 (动词)** — To add more instances to increase system capacity
  - "The system automatically scales out during traffic spikes."
- **义项 2: 垂直扩容 (动词)** — To add more resources to an existing machine
  - "We had to scale up the database server when the data volume grew."
- **义项 3: 拓展规模 (动词)** — To expand the size of a team or business
  - "Our team scaled from 3 engineers to 15 in less than a year."

---

### 21. compile
- **义项 1: 编译代码 (动词)** — To translate source code into machine code or bytecode
  - "The TypeScript compiler compiles .ts files into .js files."
- **义项 2: 汇编收集 (动词)** — To gather information or data from various sources
  - "I need to compile the performance metrics from all services into a report."
- **义项 3: 编纂成册 (动词)** — To collect and organize material into a single document
  - "The team compiled a list of all known issues before the release meeting."

---

### 22. allocate
- **义项 1: 分配内存 (动词)** — To reserve a portion of memory for a program to use
  - "The program allocates 512 MB of memory for the caching layer."
- **义项 2: 分配资源 (动词)** — To assign resources or tasks to specific purposes
  - "We need to allocate more engineering resources to the security project."
- **义项 3: 拨出时间 (动词)** — To set aside time for a specific activity
  - "I allocate one hour every morning for code review."

---

### 23. append
- **义项 1: 追加数据 (动词)** — To add data to the end of a file, array, or string
  - "The function appends the new row to the CSV file."
- **义项 2: 附加内容 (动词)** — To add extra text or information to a document
  - "I appended a note to the PR explaining why the change was necessary."
- **义项 3: 补充说明 (动词)** — To add something as a supplement in a broader context
  - "She appended her signature to the bottom of the email."

---

### 24. archive
- **义项 1: 归档文件 (动词)** — To move old data or files to long-term storage
  - "We archive logs older than 30 days to save disk space."
- **义项 2: 压缩打包 (动词)** — To compress files into a single archive package
  - "The script archives the build artifacts into a .tar.gz file."
- **义项 3: 封存记录 (动词)** — To store historical records for future reference
  - "The team archived the project documentation after the release."

---

### 25. buffer
- **义项 1: 缓冲数据 (动词)** — To temporarily hold data while it is being processed or transferred
  - "The video player buffers the next few seconds of content in advance."
- **义项 2: 缓冲保护 (动词)** — To reduce the impact of sudden changes or shocks
  - "The queue buffers the incoming requests during traffic spikes."
- **义项 3: 减轻影响 (动词)** — To soften the effect of something negative
  - "Having a financial reserve buffered the company against the economic downturn."

---

### 26. clone
- **义项 1: 克隆仓库 (动词)** — To create a local copy of a remote git repository
  - "Clone the repository before you start making changes."
- **义项 2: 复制对象 (动词)** — To create an exact copy of an object or data structure
  - "The function clones the array to avoid mutating the original data."
- **义项 3: 仿制复制 (动词)** — To make an identical copy of something in a general sense
  - "The startup cloned the business model of a successful Silicon Valley company."

---

### 27. commit
- **义项 1: 提交代码 (动词)** — To save changes to a local git repository
  - "Remember to commit your changes before switching branches."
- **义项 2: 承诺保证 (动词)** — To promise to do something or to be dedicated
  - "The team committed to delivering the feature by the end of the sprint."
- **义项 3: 投入资源 (动词)** — To dedicate resources or effort to a purpose
  - "The company committed $2 million to the new research project."

---

### 28. compress
- **义项 1: 压缩数据 (动词)** — To reduce the size of data using compression algorithms
  - "The tool compresses the images before uploading them to the CDN."
- **义项 2: 压缩文件 (动词)** — To make a file take up less space
  - "We compress the log files weekly to save storage costs."
- **义项 3: 压缩时间 (动词)** — To fit something into a shorter time frame
  - "We had to compress the three-month project timeline into six weeks."

---

### 29. encrypt
- **义项 1: 加密数据 (动词)** — To convert data into a coded form to prevent unauthorized access
  - "The application encrypts all user passwords before storing them."
- **义项 2: 加密通信 (动词)** — To secure communication channels with encryption
  - "All data transmitted between the client and server is encrypted using TLS."
- **义项 3: 保护信息 (动词)** — To protect sensitive information in a general sense
  - "You should encrypt your backup files if they contain personal data."

---

### 30. decrypt
- **义项 1: 解密数据 (动词)** — To convert encrypted data back into its original readable form
  - "The server decrypts the request payload using the private key."
- **义项 2: 解码信息 (动词)** — To interpret coded or obscured information
  - "The tool decrypts the configuration file at runtime."
- **义项 3: 解读理解 (动词)** — To make sense of something confusing or mysterious
  - "It took me a while to decrypt the meaning of the error message."

---

### 31. expose
- **义项 1: 暴露接口 (动词)** — To make a service or endpoint accessible
  - "The microservice exposes a REST API for other services to consume."
- **义项 2: 公开暴露 (动词)** — To reveal something that was previously hidden
  - "The security audit exposed several vulnerabilities in the legacy system."
- **义项 3: 使接触 (动词)** — To make someone experience something new
  - "The internship exposed me to a wide range of technologies."

---

### 32. flush
- **义项 1: 刷新缓冲区 (动词)** — To force data from a buffer to be written to disk
  - "The program flushes the buffer before closing the file."
- **义项 2: 清除缓存 (动词)** — To clear or reset a cache or queue
  - "Run this command to flush the Redis cache after deploying the new config."
- **义项 3: 冲走清除 (动词)** — To remove unwanted things completely
  - "We need to flush out all the deprecated code paths by next release."

---

### 33. fork
- **义项 1: 分叉仓库 (动词)** — To create a personal copy of someone else's repository
  - "I forked the open-source project to contribute a new feature."
- **义项 2: 创建子进程 (动词)** — To create a child process in an operating system
  - "The parent process forks a new process to handle each incoming request."
- **义项 3: 分裂分化 (动词)** — To divide into branches or separate paths
  - "The project forked into two separate libraries after the disagreement."

---

### 34. inject
- **义项 1: 注入依赖 (动词)** — To provide an object with its required dependencies
  - "The framework injects the database service into the controller."
- **义项 2: 注入代码 (动词)** — To insert code or data into a running process
  - "The attacker injected malicious SQL code into the input field."
- **义项 3: 注入资源 (动词)** — To introduce something new into a situation
  - "The manager injected new ideas into the stagnant project."

---

### 35. intercept
- **义项 1: 拦截请求 (动词)** — To capture and potentially modify a network request or response
  - "The middleware intercepts all HTTP requests and adds authentication headers."
- **义项 2: 中途阻止 (动词)** — To stop or catch something in transit
  - "The firewall intercepted the suspicious network traffic."
- **义项 3: 切断打断 (动词)** — To interrupt the course of something
  - "She intercepted the conversation to clarify a critical point."

---

### 36. mount
- **义项 1: 挂载卷 (动词)** — To make a filesystem or storage device accessible
  - "The script mounts the network drive before writing logs to it."
- **义项 2: 挂载组件 (动词)** — To attach a component to the DOM in frontend frameworks
  - "React mounts the root component to the div element with id 'root'."
- **义项 3: 安装固定 (动词)** — To physically attach or set up equipment
  - "The IT team mounted the new servers in the rack."

---

### 37. override
- **义项 1: 重写方法 (动词)** — To replace a method inherited from a parent class
  - "The subclass overrides the toString method to return custom output."
- **义项 2: 覆盖设置 (动词)** — To use a different setting instead of the default one
  - "You can override the default timeout by setting the TIMEOUT environment variable."
- **义项 3: 推翻否决 (动词)** — To use authority to reject a decision or rule
  - "The project manager overrode the team's decision to delay the release."

---

### 38. persist
- **义项 1: 持久化存储 (动词)** — To save data to permanent storage so it survives restarts
  - "The ORM framework persists the object to the database automatically."
- **义项 2: 持续存在 (动词)** — To continue to exist despite challenges
  - "The connection error persisted even after restarting the server."
- **义项 3: 坚持主张 (动词)** — To continue firmly in a course of action despite opposition
  - "She persisted in advocating for the microservices architecture."

---

### 39. propagate
- **义项 1: 传播扩散 (动词)** — To spread or transmit data, signals, or changes through a system
  - "The configuration change propagates to all nodes within 30 seconds."
- **义项 2: 传递属性 (动词)** — To pass down properties or characteristics
  - "CSS styles propagate from parent elements to child elements."
- **义项 3: 扩散蔓延 (动词)** — To spread widely in a general context
  - "The error propagated through the entire system, causing a cascade of failures."

---

### 40. provision
- **义项 1: 配置资源 (动词)** — To set up and allocate computing resources
  - "The DevOps team provisions a new server for the staging environment."
- **义项 2: 部署基础 (动词)** — To prepare and provide infrastructure or services
  - "We use Terraform to provision cloud resources automatically."
- **义项 3: 提供供应 (动词)** — To supply something needed in a general context
  - "The company provisions each new employee with a laptop and development tools."

---

### 41. purge
- **义项 1: 清除数据 (动词)** — To permanently delete data or records
  - "The script purges all logs older than 90 days from the database."
- **义项 2: 清理缓存 (动词)** — To clear cached content from a CDN or storage
  - "We purged the CDN cache after updating the static assets."
- **义项 3: 彻底清除 (动词)** — To remove undesirable things completely
  - "The new management purged several outdated processes from the workflow."

---

### 42. replicate
- **义项 1: 数据复制 (动词)** — To copy data from one location to another for redundancy
  - "The database replicates data across three data centers for high availability."
- **义项 2: 复现问题 (动词)** — To reproduce a bug or issue in a different environment
  - "I cannot replicate the issue on my local machine — it only happens in production."
- **义项 3: 复制模仿 (动词)** — To make an exact copy or imitation
  - "The startup replicated the business model of a successful competitor."

---

### 43. sanitize
- **义项 1: 净化数据 (动词)** — To clean input data by removing dangerous or invalid characters
  - "Always sanitize user input before rendering it on the page to prevent XSS attacks."
- **义项 2: 清理日志 (动词)** — To remove sensitive information from logs or outputs
  - "The function sanitizes the log output by masking email addresses and passwords."
- **义项 3: 消毒清洁 (动词)** — To make something clean and free from harmful elements
  - "The IT team sanitized the returned hardware before redeploying it."

---

### 44. serialize
- **义项 1: 序列化 (动词)** — To convert an object or data structure into a storable format
  - "The program serializes the user session object into JSON before storing it."
- **义项 2: 编码传输 (动词)** — To convert data into a format suitable for network transmission
  - "The message broker serializes the event before publishing it to the queue."
- **义项 3: 整理排序 (动词)** — To arrange items in a sequential order
  - "The script serializes the records by timestamp before processing them."

---

### 45. terminate
- **义项 1: 终止进程 (动词)** — To end a process or program execution
  - "The operating system terminates the process when it runs out of memory."
- **义项 2: 中止连接 (动词)** — To end a network connection or session
  - "The load balancer terminates the SSL connection at the edge."
- **义项 3: 解雇终止 (动词)** — To dismiss someone from employment or end a contract
  - "The company terminated the contract with the vendor due to poor service."

---

### 46. throttle
- **义项 1: 限流控制 (动词)** — To limit the rate of requests or data transfer
  - "The API gateway throttles requests that exceed 1000 per minute."
- **义项 2: 降低速度 (动词)** — To deliberately reduce the speed of a process
  - "The CPU throttles down to save power when the system is idle."
- **义项 3: 节制控制 (动词)** — To control or restrict something in a general context
  - "The manager throttled the pace of new features to focus on stability."

---

### 47. wire
- **义项 1: 连接组件 (动词)** — To connect software components together
  - "The dependency injection framework wires the services together automatically."
- **义项 2: 接线布线 (动词)** — To connect hardware devices with cables
  - "The IT team wired the new office with Ethernet connections."
- **义项 3: 电汇转账 (动词)** — To transfer money electronically
  - "The client wired the payment to the company's bank account."

---

### 48. yield
- **义项 1: 生成返回 (动词)** — To produce a result or value (especially in generators)
  - "The generator function yields one value at a time using the yield keyword."
- **义项 2: 产生结果 (动词)** — To produce a result, profit, or consequence
  - "The optimization yielded a 40% improvement in response time."
- **义项 3: 让步屈服 (动词)** — To give way to demands or pressure
  - "The team yielded to the security team's demand to add additional checks."

---

### 49. revert
- **义项 1: 回退版本 (动词)** — To return to a previous commit or version in git
  - "We had to revert the commit because it introduced a breaking change."
- **义项 2: 恢复原状 (动词)** — To return to a previous state or condition
  - "The system reverts to the default configuration if the custom config is invalid."
- **义项 3: 回复联系 (动词)** — To respond to someone in communication
  - "I will revert to you with the details after the investigation."

---

### 50. migrate
- **义项 1: 迁移数据 (动词)** — To move data from one system or format to another
  - "We need to migrate the legacy database to the new schema by Friday."
- **义项 2: 迁移架构 (动词)** — To move from one technology stack or platform to another
  - "The team is migrating from a monolith to a microservices architecture."
- **义项 3: 迁徙移居 (动词)** — To move from one place to live in another
  - "Many tech workers migrated to smaller cities during the remote work era."

---

### Group 2: Core Dev Nouns（50 个核心开发名词）

---

### 1. repository
- **义项 1: 代码仓库 (名词)** — A storage location for source code with version history
  - "Clone the repository from GitHub before you start working."
- **义项 2: 数据仓库 (名词)** — A central location where data is stored and managed
  - "The data repository stores all historical transaction records."
- **义项 3: 存储库 (名词)** — A place where things are stored in a general sense
  - "The team maintains a repository of best practices and coding standards."

---

### 2. dependency
- **义项 1: 依赖包 (名词)** — An external library or package that a project requires
  - "Run npm install to download all the project dependencies."
- **义项 2: 依赖关系 (名词)** — A relationship where one thing relies on another
  - "This module has a circular dependency with the authentication service."
- **义项 3: 依赖物 (名词)** — Something that is needed for survival or success
  - "The company's dependency on a single vendor poses a risk."

---

### 3. endpoint
- **义项 1: API 端点 (名词)** — A specific URL where an API can be accessed
  - "The /users endpoint returns a list of all registered users."
- **义项 2: 通信端点 (名词)** — One end of a communication channel
  - "Each IoT device is a network endpoint that sends data to the server."
- **义项 3: 连接末端 (名词)** — The final point of a process or journey
  - "The VPN creates a secure tunnel between two network endpoints."

---

### 4. interface
- **义项 1: 接口定义 (名词)** — A contract that defines how components interact
  - "The interface defines three methods that all implementations must provide."
- **义项 2: 用户界面 (名词)** — The visual part of an application that users interact with
  - "The user interface needs to be redesigned for better accessibility."
- **义项 3: 连接界面 (名词)** — A point of interaction between two systems or devices
  - "The USB interface allows the device to communicate with the computer."

---

### 5. variable
- **义项 1: 变量 (名词)** — A named storage location in memory for data
  - "Declare the variable with const if its value should not change."
- **义项 2: 可变因素 (名词)** — A factor that can change in an experiment or situation
  - "Server response time is a key variable in the performance analysis."
- **义项 3: 易变物 (名词)** — Something that is likely to change
  - "The weather is a variable we cannot control during the outdoor event."

---

### 6. function
- **义项 1: 函数 (名词)** — A named block of code that performs a specific task
  - "The calculateTotal function sums up all items in the shopping cart."
- **义项 2: 功能作用 (名词)** — The purpose or role of something
  - "The main function of the load balancer is to distribute traffic."
- **义项 3: 社交活动 (名词)** — A formal social event or gathering
  - "The company held a function to celebrate the successful product launch."

---

### 7. parameter
- **义项 1: 参数 (名词)** — A value passed to a function or method
  - "The function takes two parameters: the user ID and the access token."
- **义项 2: 配置参数 (名词)** — A configurable value that determines system behavior
  - "We adjusted the timeout parameter to 30 seconds."
- **义项 3: 限定因素 (名词)** — A factor that defines the boundaries of a system or process
  - "Budget and timeline are the main parameters of this project."

---

### 8. argument
- **义项 1: 实参 (名词)** — The actual value passed to a function when it is called
  - "The function received the string 'hello' as its first argument."
- **义项 2: 论点 (名词)** — A reason or set of reasons given to support an idea
  - "His argument for switching to TypeScript was convincing."
- **义项 3: 争论 (名词)** — A heated exchange of opposing views
  - "The team had an argument about which framework to use."

---

### 9. database
- **义项 1: 数据库 (名词)** — An organized collection of structured data
  - "The database stores all user information and transaction records."
- **义项 2: 数据源 (名词)** — The system that manages data storage and retrieval
  - "The application connects to the database through a connection pool."
- **义项 3: 信息库 (名词)** — A large collection of information on a specific topic
  - "The company maintains a database of industry contacts."

---

### 10. query
- **义项 1: 查询 (名词)** — A request for data from a database
  - "This SQL query retrieves all orders placed in the last 24 hours."
- **义项 2: 疑问 (名词)** — A question or request for information
  - "The client sent a query about the status of their support ticket."
- **义项 3: 质疑 (名词)** — A doubt or question about the validity of something
  - "There is a query about whether the test results are accurate."

---

### 11. schema
- **义项 1: 数据库模式 (名词)** — The structure that defines how data is organized in a database
  - "We need to update the database schema to support the new feature."
- **义项 2: 数据模型 (名词)** — A formal definition of the structure of data
  - "The JSON schema validates the structure of the API request body."
- **义项 3: 计划纲要 (名词)** — A structured framework or plan in a broader sense
  - "The project schema outlines all milestones and deliverables."

---

### 12. instance
- **义项 1: 实例 (名词)** — A single occurrence of an object or server
  - "Each microservice runs in its own Docker container instance."
- **义项 2: 事例 (名词)** — An example or particular case of something
  - "This bug is a classic instance of a race condition."
- **义项 3: 场合 (名词)** — A particular situation or case
  - "In this instance, it is better to roll back than to fix forward."

---

### 13. container
- **义项 1: 容器 (名词)** — A lightweight, standalone executable package for software
  - "We run each microservice in a separate Docker container."
- **义项 2: 容器对象 (名词)** — An object that can contain other objects in programming
  - "An array is a container that holds multiple values."
- **义项 3: 容器箱 (名词)** — A physical container for storage or transport
  - "The shipping container arrived at the warehouse this morning."

---

### 14. deployment
- **义项 1: 部署 (名词)** — The process of releasing software to a runtime environment
  - "The deployment to production was completed without any issues."
- **义项 2: 发布版本 (名词)** — A specific release of software that has been deployed
  - "Version 3.2 is the latest deployment to the staging environment."
- **义项 3: 部署行动 (名词)** — The act of strategically positioning resources
  - "The deployment of additional servers helped handle the traffic spike."

---

### 15. pipeline
- **义项 1: CI/CD 流水线 (名词)** — An automated sequence of steps for building, testing, and deploying code
  - "The CI pipeline runs linting, unit tests, and integration tests on every push."
- **义项 2: 数据处理管道 (名词)** — A series of data processing stages
  - "The data pipeline extracts, transforms, and loads data from multiple sources."
- **义项 3: 管道 (名词)** — A physical tube for conveying liquids or gases
  - "The oil pipeline runs hundreds of kilometers across the desert."

---

### 16. artifact
- **义项 1: 构建产物 (名词)** — A file produced by a build process
  - "The build artifacts are stored in the artifact repository for future releases."
- **义项 2: 人工制品 (名词)** — An object made by a human, typically of cultural or historical interest
  - "The museum displays artifacts from ancient civilizations."
- **义项 3: 副产品 (名词)** — A byproduct of a process or system
  - "The noise is an artifact of the signal processing algorithm."

---

### 17. threshold
- **义项 1: 阈值 (名词)** — The limit or level at which something changes or triggers
  - "The alert fires when CPU usage exceeds the 90% threshold."
- **义项 2: 门槛 (名词)** — The level at which something starts to happen
  - "You need to reach a certain threshold of experience before applying."
- **义项 3: 界限 (名词)** — A point of entry or beginning
  - "We are on the threshold of a major technological breakthrough."

---

### 18. redundancy
- **义项 1: 冗余备份 (名词)** — Duplication of critical components for reliability
  - "The system has built-in redundancy so that no single point of failure exists."
- **义项 2: 多余重复 (名词)** — Unnecessary repetition of words or information
  - "The report contained too much redundancy — the same data appeared in three tables."
- **义项 3: 裁员 (名词)** — The state of being no longer employed because the job is no longer needed
  - "The company announced 200 redundancies due to the restructuring."

---

### 19. latency
- **义项 1: 延迟 (名词)** — The time delay between a request and a response
  - "The API has an average latency of 50 milliseconds."
- **义项 2: 网络延迟 (名词)** — The time it takes for data to travel from source to destination
  - "High network latency causes lag in video conferencing."
- **义项 3: 潜伏期 (名词)** — The time between a cause and its visible effect
  - "There is a latency between the deployment and when users see the changes."

---

### 20. throughput
- **义项 1: 吞吐量 (名词)** — The amount of data processed per unit of time
  - "The database can handle a throughput of 10,000 queries per second."
- **义项 2: 处理能力 (名词)** — The rate at which a system can complete work
  - "We increased throughput by optimizing the batch processing pipeline."
- **义项 3: 产出量 (名词)** — The amount of work or output produced in a given time
  - "The team's throughput increased after adopting agile methodologies."

---

### 21. algorithm
- **义项 1: 算法 (名词)** — A step-by-step procedure for solving a problem
  - "The sorting algorithm arranges the array in ascending order."
- **义项 2: 计算方法 (名词)** — A mathematical method for computation
  - "The recommendation algorithm analyzes user behavior to suggest content."
- **义项 3: 逻辑流程 (名词)** — A systematic process in a broader context
  - "We need a clear algorithm for handling customer complaints."

---

### 22. API
- **义项 1: API 接口 (名词)** — A set of defined rules for software communication
  - "The REST API exposes endpoints for managing user accounts."
- **义项 2: 外部接口 (名词)** — The interface through which external systems interact
  - "The payment API processes transactions securely."
- **义项 3: 调用方式 (名词)** — A way to access functionality provided by a system
  - "The library has a clean API that is easy to learn."

---

### 23. array
- **义项 1: 数组 (名词)** — A data structure that stores a collection of elements
  - "The function takes an array of numbers and returns the sum."
- **义项 2: 排列 (名词)** — An ordered arrangement of items
  - "The data center has a neat array of server racks."
- **义项 3: 阵列 (名词)** — A large group or collection of things
  - "The company offers a wide array of cloud services."

---

### 24. binary
- **义项 1: 二进制 (名词)** — A number system using only 0 and 1
  - "The computer stores all data in binary format."
- **义项 2: 编译文件 (名词)** — A compiled executable file
  - "Download the binary for your operating system from the releases page."
- **义项 3: 二元选择 (名词)** — A situation with two mutually exclusive options
  - "The deployment decision is binary: either we release or we do not."

---

### 25. boolean
- **义项 1: 布尔值 (名词)** — A data type with two possible values: true or false
  - "The function returns a boolean indicating whether the user is authorized."
- **义项 2: 逻辑判断 (名词)** — A logical condition that evaluates to true or false
  - "Use a boolean flag to track whether the initialization is complete."
- **义项 3: 二元状态 (名词)** — A binary state or condition
  - "The answer to the question is a simple boolean: yes or no."

---

### 26. callback
- **义项 1: 回调函数 (名词)** — A function passed as an argument to be executed later
  - "The setTimeout function takes a callback that runs after 3 seconds."
- **义项 2: 回调机制 (名词)** — A programming pattern where a function is called after an operation completes
  - "We used a callback to handle the response from the asynchronous API call."
- **义项 3: 回访 (名词)** — A follow-up call or contact
  - "The support team scheduled a callback for the next day."

---

### 27. class
- **义项 1: 类 (名词)** — A blueprint for creating objects in object-oriented programming
  - "The User class defines properties like name and email."
- **义项 2: 班级 (名词)** — A group of students taught together
  - "The training class covers advanced TypeScript patterns."
- **义项 3: 阶级等级 (名词)** — A division of society based on social or economic status
  - "The middle class has grown significantly in the last decade."

---

### 28. compiler
- **义项 1: 编译器 (名词)** — A program that translates source code into machine code
  - "The TypeScript compiler compiles .ts files into .js files."
- **义项 2: 编译工具 (名词)** — The tool that performs compilation
  - "The compiler optimized the code for better performance."
- **义项 3: 汇编者 (名词)** — A person who collects and organizes information
  - "The compiler of the report gathered data from multiple departments."

---

### 29. constructor
- **义项 1: 构造函数 (名词)** — A special method called when an object is instantiated
  - "The constructor initializes the object's properties with default values."
- **义项 2: 构造器 (名词)** — The code that sets up an object's initial state
  - "Call the parent constructor with super() before accessing 'this'."
- **义项 3: 建造者 (名词)** — A person or company that builds things
  - "The constructor completed the building ahead of schedule."

---

### 30. deadlock
- **义项 1: 死锁 (名词)** — A situation where two processes each wait for the other to release a resource
  - "The database deadlock occurred when two transactions locked different tables."
- **义项 2: 僵局 (名词)** — A situation where no progress can be made
  - "The negotiation reached a deadlock because neither side would compromise."
- **义项 3: 停滞 (名词)** — A state of complete standstill
  - "The project hit a deadlock due to conflicting requirements."

---

### 31. debugger
- **义项 1: 调试器 (名词)** — A tool used to test and debug programs
  - "The debugger allows you to set breakpoints and inspect variables."
- **义项 2: 调试工具 (名词)** — A software tool for identifying and removing errors
  - "Use the browser's built-in debugger to step through the JavaScript code."
- **义项 3: 调试者 (名词)** — A person who finds and fixes bugs
  - "She is an excellent debugger who can find the root cause quickly."

---

### 32. exception
- **义项 1: 异常 (名词)** — An error event that disrupts normal program execution
  - "The function throws an exception when the file is not found."
- **义项 2: 例外情况 (名词)** — Something that does not follow the general rule
  - "As an exception, we extended the deadline by one day."
- **义项 3: 异议 (名词)** — An objection or disagreement
  - "She took exception to the way the incident was handled."

---

### 33. framework
- **义项 1: 框架 (名词)** — A reusable set of tools and conventions for building applications
  - "We chose React as our frontend framework for this project."
- **义项 2: 体系结构 (名词)** — A supporting structure around which something is built
  - "The project needs a clear framework for decision-making."
- **义项 3: 构架 (名词)** — A basic structure underlying a system or concept
  - "The legal framework for data protection has become stricter."

---

### 34. garbage collector
- **义项 1: 垃圾回收器 (名词)** — Automatic memory management that reclaims unused memory
  - "The garbage collector frees memory that is no longer referenced by the program."
- **义项 2: 内存回收 (名词)** — The process of automatically deallocating unused memory
  - "Java's garbage collector runs periodically to clean up unused objects."
- **义项 3: 废物处理者 (名词)** — A person or machine that collects waste
  - "The garbage collector truck comes every Tuesday morning."

---

### 35. hash
- **义项 1: 哈希值 (名词)** — A fixed-size string generated from input data
  - "Store the hash of the password instead of the password itself."
- **义项 2: 哈希表 (名词)** — A data structure that maps keys to values
  - "A hash map provides O(1) lookups on average."
- **义项 3: 杂烩 (名词)** — A mixture of chopped food or a jumbled mix
  - "The codebase was a hash of different coding styles and conventions."

---

### 36. iterator
- **义项 1: 迭代器 (名词)** — An object that enables traversal through a collection
  - "The iterator allows you to loop through each element in the array."
- **义项 2: 遍历工具 (名词)** — A pattern for sequentially accessing elements
  - "JavaScript arrays have a built-in iterator that works with for...of loops."
- **义项 3: 反复者 (名词)** — Someone or something that repeats a process
  - "He is a constant iterator, always refining his approach."

---

### 37. kernel
- **义项 1: 内核 (名词)** — The core component of an operating system
  - "The Linux kernel manages hardware resources and system calls."
- **义项 2: 核心部分 (名词)** — The central or essential part of something
  - "The kernel of the problem is the outdated authentication mechanism."
- **义项 3: 核心/本质 (名词)** — The most important element of an idea or argument
  - "The kernel of his argument is that we need to prioritize security."

---

### 38. library
- **义项 1: 库 (名词)** — A collection of reusable code that can be imported
  - "This JavaScript library provides utility functions for working with dates."
- **义项 2: 图书馆 (名词)** — A building or room containing a collection of books
  - "I spent the afternoon reading technical books at the library."
- **义项 3: 收藏集 (名词)** — A personal collection of books, media, or resources
  - "My home library has over 200 programming books."

---

### 39. middleware
- **义项 1: 中间件 (名词)** — Software that sits between applications and operating systems
  - "The message queue middleware handles communication between microservices."
- **义项 2: 中间层 (名词)** — A layer that processes requests between the client and the server
  - "The authentication middleware checks the token before forwarding the request."
- **义项 3: 中介软件 (名词)** — Software that connects different components in a system
  - "The API gateway acts as middleware between clients and backend services."

---

### 40. namespace
- **义项 1: 命名空间 (名词)** — A container that prevents naming conflicts
  - "The code is organized into namespaces to avoid naming collisions."
- **义项 2: 作用域 (名词)** — A scope that groups related identifiers
  - "All math-related functions are grouped under the Math namespace."
- **义项 3: 领域范围 (名词)** — A conceptual space that defines a context
  - "This discussion is outside the namespace of the current project."

---

### 41. object
- **义项 1: 对象 (名词)** — A data structure containing properties and methods
  - "The user object contains properties like name, email, and role."
- **义项 2: 目标 (名词)** — A goal or purpose
  - "The object of the sprint is to deliver the authentication feature."
- **义项 3: 物体 (名词)** — A material thing that can be seen and touched
  - "The object on the desk is a 3D-printed prototype of the device."

---

### 42. pointer
- **义项 1: 指针 (名词)** — A variable that stores a memory address
  - "In C, a pointer stores the address of another variable."
- **义项 2: 光标 (名词)** — A visual indicator on a screen
  - "Move the pointer to the top-right corner to close the window."
- **义项 3: 提示指引 (名词)** — A helpful piece of advice or indication
  - "The manager gave me some pointers on how to improve the presentation."

---

### 43. protocol
- **义项 1: 协议 (名词)** — A set of rules governing data communication
  - "HTTP is the protocol used for transferring web pages."
- **义项 2: 作规程 (名词)** — A standard procedure or set of guidelines
  - "Follow the incident response protocol when a production outage occurs."
- **义项 3: 礼仪 (名词)** — The official procedure or system of rules for formal occasions
  - "According to protocol, you should inform the manager before escalating the issue."

---

### 44. recursion
- **义项 1: 递归 (名词)** — A technique where a function calls itself
  - "Recursion is useful for solving problems that can be broken into smaller subproblems."
- **义项 2: 循环调用 (名词)** — The process of repeatedly applying a function to its own output
  - "The directory traversal uses recursion to visit every nested folder."
- **义项 3: 循环重现 (名词)** — The repeated occurrence of a pattern or structure
  - "There is a recursion of similar problems across different projects."

---

### 45. runtime
- **义项 1: 运行时 (名词)** — The environment in which a program executes
  - "Node.js is a JavaScript runtime built on Chrome's V8 engine."
- **义项 2: 运行期间 (名词)** — The period during which a program is executing
  - "The error occurs at runtime, not during compilation."
- **义项 3: 执行环境 (名词)** — The system that provides services to a running program
  - "The Python runtime manages memory allocation and garbage collection."

---

### 46. stack
- **义项 1: 技术栈 (名词)** — A combination of technologies used to build an application
  - "Our stack includes React, Node.js, and PostgreSQL."
- **义项 2: 堆栈 (名词)** — A LIFO data structure (Last In, First Out)
  - "The call stack tracks which functions are currently being executed."
- **义项 3: 堆叠 (名词)** — An orderly pile or arrangement
  - "There is a stack of unread technical books on my desk."

---

### 47. syntax
- **义项 1: 语法 (名词)** — The set of rules defining valid code structure
  - "The syntax of Python uses indentation to define code blocks."
- **义项 2: 语法结构 (名词)** — The structure of statements in a programming language
  - "The syntax for declaring a variable in JavaScript is 'let' or 'const'."
- **义项 3: 句法 (名词)** — The arrangement of words in a sentence in natural language
  - "English syntax requires a subject before the verb in declarative sentences."

---

### 48. thread
- **义项 1: 线程 (名词)** — The smallest unit of execution within a process
  - "Each thread runs independently and can access shared memory."
- **义项 2: 线索 (名词)** — A sequence of connected ideas or events
  - "I lost the thread of the conversation during the technical discussion."
- **义项 3: 线 (名词)** — A thin strand of material used for sewing
  - "The thread on the server cable was damaged, causing connectivity issues."

---

### 49. token
- **义项 1: 令牌 (名词)** — A piece of data used for authentication or authorization
  - "The API requires a valid JWT token in the Authorization header."
- **义项 2: 词法单元 (名词)** — The smallest unit in lexical analysis
  - "The lexer breaks the source code into tokens like keywords and operators."
- **义项 3: 代币/凭证 (名词)** — A physical or digital item representing a right or value
  - "Each team member received a token to access the secure building."

---

### 50. version
- **义项 1: 版本 (名词)** — A specific release or iteration of software
  - "Version 3.0 of the framework introduced several breaking changes."
- **义项 2: 版本控制 (名词)** — A system that tracks changes to files over time
  - "We use Git for version control to manage our source code history."
- **义项 3: 说法 (名词)** — An account of something from a particular perspective
  - "His version of the incident differs from what the logs show."

---

### Group 3: Daily Life Verbs（50 个日常高频动词）

---

### 1. accept
- **义项 1: 接受 (动词)** — To willingly receive something offered
  - "I accepted the job offer from the tech company."
- **义项 2: 承认 (动词)** — To recognize something as true
  - "She accepted that the bug was her fault."
- **义项 3: 接纳 (动词)** — To allow someone to join a group
  - "The university accepted him into the computer science program."

---

### 2. allow
- **义项 1: 允许 (动词)** — To let someone do something
  - "The manager allowed us to work remotely on Fridays."
- **义项 2: 使可能 (动词)** — To make something possible
  - "The new framework allows faster development."
- **义项 3: 给予 (动词)** — To provide or set aside
  - "Allow yourself enough time to review the code."

---

### 3. answer
- **义项 1: 回答 (动词)** — To respond to a question
  - "Please answer my email by the end of the day."
- **义项 2: 接电话 (动词)** — To pick up a phone call
  - "I called three times but nobody answered."
- **义项 3: 回应 (动词)** — To react to a situation
  - "The system answered the request with a 200 status code."

---

### 4. ask
- **义项 1: 问 (动词)** — To inquire or request information
  - "Ask the senior developer if she has time for a code review."
- **义项 2: 请求 (动词)** — To request something from someone
  - "He asked for an extension on the deadline."
- **义项 3: 邀请 (动词)** — To invite someone
  - "They asked me to join the architecture meeting."

---

### 5. believe
- **义项 1: 相信 (动词)** — To accept something as true
  - "I believe the test coverage is above 80%."
- **义项 2: 认为 (动词)** — To have an opinion
  - "She believes the microservice migration is worth the effort."
- **义项 3: 信任 (动词)** — To have confidence in someone
  - "I believe in the team's ability to deliver on time."

---

### 6. bring
- **义项 1: 带来 (动词)** — To carry something to a place
  - "Bring your laptop to the workshop tomorrow."
- **义项 2: 引起 (动词)** — To cause a situation
  - "The new update brought significant performance improvements."
- **义项 3: 提出 (动词)** — To raise a topic or issue
  - "She brought up an important concern during the standup."

---

### 7. buy
- **义项 1: 买 (动词)** — To purchase something with money
  - "I bought a new monitor for my home office."
- **义项 2: 买通 (动词)** — To bribe someone
  - "The company bought the rights to the patent."
- **义项 3: 相信接受 (动词)** — To accept something as valid
  - "I do not buy his excuse for the delayed delivery."

---

### 8. call
- **义项 1: 打电话 (动词)** — To telephone someone
  - "Call me when you finish the deployment."
- **义项 2: 调用 (动词)** — To invoke a function or method
  - "The program calls the API every 30 seconds."
- **义项 3: 称呼 (动词)** — To name or describe someone as
  - "We call this pattern 'dependency injection'."

---

### 9. change
- **义项 1: 改变 (动词)** — To make something different
  - "We changed the database schema to support the new feature."
- **义项 2: 更换 (动词)** — To replace with another
  - "I changed my password after the security alert."
- **义项 3: 换乘 (动词)** — To switch transportation
  - "Change trains at the central station."

---

### 10. check
- **义项 1: 检查 (动词)** — To examine something for accuracy or quality
  - "Check the logs to see why the server crashed."
- **义项 2: 验证 (动词)** — To confirm that something is correct
  - "Double-check the configuration before deploying."
- **义项 3: 查看 (动词)** — To look at or consult
  - "Check your email for the meeting invitation."

---

### 11. choose
- **义项 1: 选择 (动词)** — To pick one option from several
  - "We chose React over Vue for this project."
- **义项 2: 决定 (动词)** — To make a decision
  - "She chose to rewrite the module from scratch."
- **义项 3: 挑选 (动词)** — To select carefully
  - "Choose the right data structure for your use case."

---

### 12. come
- **义项 1: 来 (动词)** — To move toward the speaker
  - "Come to the meeting room when you are ready."
- **义项 2: 出现 (动词)** — To happen or occur
  - "The error comes from a null pointer in the code."
- **义项 3: 来源于 (动词)** — To originate from
  - "This requirement comes directly from the customer."

---

### 13. consider
- **义项 1: 考虑 (动词)** — To think about carefully
  - "We are considering moving to a microservices architecture."
- **义项 2: 认为 (动词)** — To have a particular opinion
  - "I consider him the best engineer on the team."
- **义项 3: 顾及 (动词)** — To take into account
  - "Consider the impact on existing users before making changes."

---

### 14. continue
- **义项 1: 继续 (动词)** — To keep doing something without stopping
  - "Continue monitoring the server performance for another hour."
- **义项 2: 延续 (动词)** — To extend or last
  - "The meeting continued for over two hours."
- **义项 3: 恢复 (动词)** — To resume after a break
  - "We will continue the discussion after lunch."

---

### 15. control
- **义项 1: 控制 (动词)** — To direct or manage something
  - "The version control system controls changes to the codebase."
- **义项 2: 掌控 (动词)** — To have power over something
  - "The firewall controls incoming and outgoing network traffic."
- **义项 3: 克制 (动词)** — To restrain or manage emotions
  - "Control your frustration and focus on finding a solution."

---

### 16. cook
- **义项 1: 做饭 (动词)** — To prepare food by heating it
  - "I cook dinner every evening after work."
- **义项 2: 烹饪 (动词)** — To prepare a specific dish
  - "She cooked a traditional Chinese meal for the team."
- **义项 3: 伪造 (动词)** — To falsify data or results
  - "The auditor discovered that someone had cooked the books."

---

### 17. create
- **义项 1: 创建 (动词)** — To make something new
  - "The script creates a new user account in the database."
- **义项 2: 创造 (动词)** — To produce something original
  - "She created a new component library for the team."
- **义项 3: 引起 (动词)** — To cause a situation
  - "The change created unexpected issues in production."

---

### 18. decide
- **义项 1: 决定 (动词)** — To make a choice after consideration
  - "We decided to postpone the release until next week."
- **义项 2: 判决 (动词)** — To make a formal judgment
  - "The court decided in favor of the open-source license."
- **义项 3: 使决定 (动词)** — To cause someone to make a choice
  - "The performance issues decided us against using that framework."

---

### 19. describe
- **义项 1: 描述 (动词)** — To say what something is like
  - "Describe the bug in detail so I can reproduce it."
- **义项 2: 说明 (动词)** — To explain the nature of something
  - "The document describes the system architecture clearly."
- **义项 3: 形容 (动词)** — To characterize something
  - "He described the project as the most challenging of his career."

---

### 20. discuss
- **义项 1: 讨论 (动词)** — To talk about something with others
  - "We need to discuss the deployment strategy for the new release."
- **义项 2: 商议 (动词)** — To examine a topic in detail
  - "The team discussed the pros and cons of each approach."
- **义项 3: 论述 (动词)** — To write or speak about a topic
  - "The article discusses best practices for API design."

---

### 21. enjoy
- **义项 1: 享受 (动词)** — To get pleasure from something
  - "I enjoy debugging complex issues — it is like solving a puzzle."
- **义项 2: 喜欢 (动词)** — To like doing something
  - "She enjoys pair programming because she learns from others."
- **义项 3: 享有 (动词)** — To have the benefit of something
  - "The employees enjoy flexible working hours."

---

### 22. explain
- **义项 1: 解释 (动词)** — To make something clear or understandable
  - "Explain the root cause of the incident in the postmortem."
- **义项 2: 说明原因 (动词)** — To give reasons for something
  - "He explained why the deployment was delayed."
- **义项 3: 讲解 (动词)** — To teach or describe in detail
  - "The senior engineer explained the architecture to the new hire."

---

### 23. feel
- **义项 1: 感觉 (动词)** — To experience an emotion or sensation
  - "I feel confident about the release after all the tests passed."
- **义项 2: 觉得 (动词)** — To have an opinion or belief
  - "I feel that we should refactor this module before adding new features."
- **义项 3: 摸起来 (动词)** — To have a particular texture when touched
  - "The 3D-printed prototype feels smooth and solid."

---

### 24. find
- **义项 1: 找到 (动词)** — To discover or locate something
  - "I found the bug in the authentication module."
- **义项 2: 觉得 (动词)** — To have a particular opinion
  - "I find TypeScript much easier to work with than plain JavaScript."
- **义项 3: 发现 (动词)** — To become aware of something
  - "We found that the database query was the bottleneck."

---

### 25. finish
- **义项 1: 完成 (动词)** — To bring something to an end
  - "I finished the code review before lunch."
- **义项 2: 结束 (动词)** — To stop doing something
  - "The meeting finished five minutes early."
- **义项 3: 吃完 (动词)** — To consume all of something
  - "Finish your coffee and let us start the standup."

---

### 26. follow
- **义项 1: 跟随 (动词)** — To go after someone or something
  - "Follow the instructions in the README to set up the project."
- **义项 2: 遵循 (动词)** — To obey or act according to rules
  - "Follow the coding style guidelines when writing new code."
- **义项 3: 理解 (动词)** — To understand a sequence or explanation
  - "I followed his explanation of the distributed system architecture."

---

### 27. forget
- **义项 1: 忘记 (动词)** — To not remember something
  - "Do not forget to update the API documentation after the change."
- **义项 2: 遗忘 (动词)** — To fail to do something because of a memory lapse
  - "I forgot to push my changes before leaving for the day."
- **义项 3: 不再想 (动词)** — To stop thinking about something
  - "Forget about the failed experiment and try a different approach."

---

### 28. get
- **义项 1: 得到 (动词)** — To receive or obtain something
  - "I got approval for the new server purchase."
- **义项 2: 理解 (动词)** — To understand something
  - "I do not get why the test is failing."
- **义项 3: 变得 (动词)** — To become a certain state
  - "The code gets complicated when too many conditions are added."

---

### 29. give
- **义项 1: 给 (动词)** — To hand something to someone
  - "Give me the deployment log so I can check the error."
- **义项 2: 提供 (动词)** — To provide information or help
  - "The senior engineer gave us valuable advice on system design."
- **义项 3: 做动作 (动词)** — To perform an action
  - "She gave a presentation on the new architecture."

---

### 30. go
- **义项 1: 去 (动词)** — To move from one place to another
  - "I go to the office three days a week."
- **义项 2: 运行 (动词)** — To function or operate
  - "The system goes down for maintenance every Sunday."
- **义项 3: 进展 (动词)** — To proceed or develop
  - "How is the project going? — It is going well."

---

### 31. help
- **义项 1: 帮助 (动词)** — To assist someone
  - "Can you help me debug this issue?"
- **义项 2: 有助于 (动词)** — To make something easier
  - "The monitoring dashboard helps us identify problems early."
- **义项 3: 忍不住 (动词)** — To be unable to avoid doing something
  - "I cannot help checking my email first thing in the morning."

---

### 32. improve
- **义项 1: 改进 (动词)** — To make something better
  - "We improved the response time by optimizing the database queries."
- **义项 2: 提高 (动词)** — To increase in quality or value
  - "Her English has improved significantly since she started practicing daily."
- **义项 3: 完善 (动词)** — To refine or perfect something
  - "The team improved the deployment process to reduce downtime."

---

### 33. include
- **义项 1: 包含 (动词)** — To contain as part of a whole
  - "The package includes the source code and the documentation."
- **义项 2: 包括 (动词)** — To make someone or something part of a group
  - "Please include me in the meeting invitation."
- **义项 3: 纳入 (动词)** — To incorporate into a plan or calculation
  - "We included the testing time in the project estimate."

---

### 34. keep
- **义项 1: 保持 (动词)** — To continue in a particular state or position
  - "Keep the server running while we investigate the issue."
- **义项 2: 保留 (动词)** — To retain possession of something
  - "Keep a backup of the database before making changes."
- **义项 3: 遵守 (动词)** — To honor or fulfill a commitment
  - "We kept our promise to deliver the feature on time."

---

### 35. know
- **义项 1: 知道 (动词)** — To have information or knowledge
  - "I know how to fix this bug — it is a configuration issue."
- **义项 2: 认识 (动词)** — To be familiar with a person
  - "I know the lead engineer from a previous company."
- **义项 3: 会 (动词)** — To have a skill
  - "She knows three programming languages: Python, Java, and Go."

---

### 36. learn
- **义项 1: 学习 (动词)** — To gain knowledge or skill through study
  - "I am learning Kubernetes this quarter."
- **义项 2: 了解 (动词)** — To become aware of information
  - "We learned about the security breach from the monitoring alert."
- **义项 3: 吸取教训 (动词)** — To gain understanding from experience
  - "We learned from the outage that we need better monitoring."

---

### 37. leave
- **义项 1: 离开 (动词)** — To go away from a place
  - "I leave the office at 6 PM every day."
- **义项 2: 留下 (动词)** — To let something remain in a place
  - "Leave the server running — I will check it later."
- **义项 3: 请假 (动词)** — To take time off from work
  - "I am leaving early today for a doctor's appointment."

---

### 38. listen
- **义项 1: 听 (动词)** — To pay attention to sound
  - "Listen to the podcast on the way to work."
- **义项 2: 听从 (动词)** — To follow advice or instructions
  - "You should listen to the senior engineer's advice."
- **义项 3: 倾听 (动词)** — To pay close attention to someone
  - "A good manager listens to the team's concerns."

---

### 39. look
- **义项 1: 看 (动词)** — To direct your eyes at something
  - "Look at the error message in the console."
- **义项 2: 看起来 (动词)** — To seem or appear (系动词用法)
  - "The deployment log looks clean — no errors found."
- **义项 3: 寻找 (动词)** — To search for something
  - "I am looking for the root cause of this issue."

---

### 40. lose
- **义项 1: 丢失 (动词)** — To be unable to find something
  - "I lost my changes when the system crashed unexpectedly."
- **义项 2: 失去 (动词)** — To stop having something
  - "We lost two hours of work because of the power outage."
- **义项 3: 输 (动词)** — To fail to win
  - "The team lost the contract to a competitor."

---

### 41. love
- **义项 1: 爱 (动词)** — To have strong affection for someone
  - "I love my family more than anything."
- **义项 2: 热爱 (动词)** — To enjoy something very much
  - "She loves solving complex algorithmic problems."
- **义项 3: 喜欢 (动词)** — To like something very much
  - "I love the new code editor — it has great features."

---

### 42. make
- **义项 1: 做 (动词)** — To create or produce something
  - "Make sure to test your changes before pushing."
- **义项 2: 使 (动词)** — To cause something to happen or change
  - "The optimization made the application run twice as fast."
- **义项 3: 做出 (动词)** — To perform an action
  - "We need to make a decision by Friday."

---

### 43. move
- **义项 1: 移动 (动词)** — To change position or location
  - "We moved the database to a new server."
- **义项 2: 搬家 (动词)** — To change residence
  - "She moved to Shanghai for a new job opportunity."
- **义项 3: 进展 (动词)** — To make progress
  - "The project is moving forward according to plan."

---

### 44. need
- **义项 1: 需要 (动词)** — To require something essential
  - "We need more test coverage before the release."
- **义项 2: 必须 (动词)** — To have an obligation to do something
  - "You need to complete the security training by Friday."
- **义项 3: 需求 (动词)** — To express a necessity
  - "The application needs a database connection to function."

---

### 45. open
- **义项 1: 打开 (动词)** — To make something accessible or not closed
  - "Open the terminal and run the build command."
- **义项 2: 开设 (动词)** — To start or establish
  - "The company opened a new office in Singapore."
- **义项 3: 开放 (动词)** — To make available
  - "We opened the API to third-party developers."

---

### 46. play
- **义项 1: 玩 (动词)** — To engage in an activity for enjoyment
  - "I play basketball every weekend with my friends."
- **义项 2: 播放 (动词)** — To start audio or video
  - "Play the meeting recording if you missed the session."
- **义项 3: 扮演 (动词)** — To take on a role
  - "Developers play a key role in the product design process."

---

### 47. read
- **义项 1: 读 (动词)** — To look at written words and understand them
  - "I read the error log to understand what went wrong."
- **义项 2: 阅读 (动词)** — To read for information or pleasure
  - "Read the API documentation before integrating with the service."
- **义项 3: 读取 (动词)** — To access data from storage
  - "The application reads the configuration from a JSON file."

---

### 48. run
- **义项 1: 跑步 (动词)** — To move at a speed faster than walking
  - "I run for 30 minutes every morning."
- **义项 2: 运行 (动词)** — To execute a program or process
  - "Run the test suite before pushing your changes."
- **义项 3: 管理 (动词)** — To be in charge of something
  - "She runs the DevOps team at a fast-growing startup."

---

### 49. start
- **义项 1: 开始 (动词)** — To begin doing something
  - "We start the sprint planning meeting at 10 AM."
- **义项 2: 启动 (动词)** — To cause a machine or system to begin operating
  - "Start the server and check if the application loads correctly."
- **义项 3: 创办 (动词)** — To establish or set up
  - "He started his own software company at the age of 25."

---

### 50. work
- **义项 1: 工作 (动词)** — To do a job or task
  - "I work as a backend engineer at a fintech company."
- **义项 2: 运转 (动词)** — To function or operate correctly
  - "The deployment script worked without any issues."
- **义项 3: 有效 (动词)** — To have the desired effect
  - "The caching strategy worked — response times dropped by 50%."

---

### Group 4: Daily Life Nouns（50 个日常高频名词）

---

### 1. account
- **义项 1: 账户 (名词)** — A user registration for a service
  - "I need to create a new account for the cloud platform."
- **义项 2: 描述 (名词)** — A report or description of an event
  - "He gave a detailed account of the incident during the meeting."
- **义项 3: 客户 (名词)** — A client or customer in business
  - "Our account manager handles the relationship with the client."

---

### 2. answer
- **义项 1: 答案 (名词)** — A response to a question
  - "I finally found the answer to the performance issue."
- **义项 2: 回答 (名词)** — A verbal or written reply
  - "I am waiting for an answer from the support team."
- **义项 3: 解决方法 (名词)** — A solution to a problem
  - "The answer to our scaling problem is to add more servers."

---

### 3. bank
- **义项 1: 银行 (名词)** — A financial institution
  - "The bank approved our company's loan application."
- **义项 2: 库 (名词)** — A stock or reserve of something
  - "We have a data bank of customer information."
- **义项 3: 河岸 (名词)** — The land alongside a river
  - "We had a team-building picnic on the river bank."

---

### 4. book
- **义项 1: 书 (名词)** — A set of written pages bound together
  - "I am reading a book on distributed systems."
- **义项 2: 预订 (动词同形)** — A reservation or record
  - "I have a booking for the conference room at 2 PM."
- **义项 3: 账本 (名词)** — A financial record
  - "The accountant balanced the books at the end of the month."

---

### 5. business
- **义项 1: 业务 (名词)** — Commercial activity or enterprise
  - "Our business focuses on cloud infrastructure solutions."
- **义项 2: 公司 (名词)** — A commercial organization
  - "She started her own software business five years ago."
- **义项 3: 事务 (名词)** — Matters that need attention
  - "I have some personal business to take care of this afternoon."

---

### 6. car
- **义项 1: 汽车 (名词)** — A motor vehicle for road transport
  - "I drive my car to the office every day."
- **义项 2: 车厢 (名词)** — A carriage of a train
  - "The dining car is in the middle of the train."
- **义项 3: 车辆 (名词)** — Any wheeled vehicle
  - "The company provides a company car for business travel."

---

### 7. city
- **义项 1: 城市 (名词)** — A large town
  - "Shanghai is a major technology hub in China."
- **义项 2: 市区 (名词)** — The central area of a metropolis
  - "Our office is in the city center near the subway station."
- **义项 3: 全市 (名词)** — The people of a city collectively
  - "The whole city celebrated the tech festival."

---

### 8. company
- **义项 1: 公司 (名词)** — A business organization
  - "I work for a multinational technology company."
- **义项 2: 陪伴 (名词)** — The presence of someone
  - "I enjoy the company of my colleagues during lunch."
- **义项 3: 剧团 (名词)** — A group of performers
  - "A theater company performed at the annual company party."

---

### 9. computer
- **义项 1: 电脑 (名词)** — An electronic device for processing data
  - "My computer crashed during the important presentation."
- **义项 2: 计算机 (名词)** — A machine that performs calculations
  - "The quantum computer can solve problems that traditional computers cannot."
- **义项 3: 计算设备 (名词)** — Any programmable device
  - "The embedded computer in the IoT device monitors temperature."

---

### 10. conversation
- **义项 1: 对话 (名词)** — An informal talk between people
  - "I had an interesting conversation with the CTO about our tech strategy."
- **义项 2: 交谈 (名词)** — A spoken exchange of ideas
  - "The conversation during the standup was very productive."
- **义项 3: 讨论 (名词)** — A discussion about a particular topic
  - "We had a conversation about migrating to the cloud."

---

### 11. country
- **义项 1: 国家 (名词)** — A nation with its own government
  - "China has a rapidly growing technology sector."
- **义项 2: 乡村 (名词)** — Rural areas outside cities
  - "I grew up in the country before moving to the city for college."
- **义项 3: 祖国 (名词)** — One's native land
  - "He returned to his home country after working abroad."

---

### 12. day
- **义项 1: 天 (名词)** — A 24-hour period
  - "The deployment took two days to complete."
- **义项 2: 工作日 (名词)** — The time spent working during a day
  - "I have a busy day ahead with back-to-back meetings."
- **义项 3: 时代 (名词)** — A particular period or era
  - "In my day, we did not have cloud computing."

---

### 13. education
- **义项 1: 教育 (名词)** — The process of teaching and learning
  - "Continuous education is important in the tech industry."
- **义项 2: 学历 (名词)** — Formal schooling or qualifications
  - "She has a degree in computer science education."
- **义项 3: 培训 (名词)** — Training and development
  - "The company provides education reimbursement for employees."

---

### 14. energy
- **义项 1: 精力 (名词)** — The capacity for doing work
  - "I do not have the energy to debug this after a long day."
- **义项 2: 能源 (名词)** — Power derived from physical resources
  - "The data center uses renewable energy sources."
- **义项 3: 活力 (名词)** — Enthusiasm and vitality
  - "The new team member brings fresh energy to the project."

---

### 15. evening
- **义项 1: 晚上 (名词)** — The period at the end of the day
  - "I usually study English in the evening after work."
- **义项 2: 晚会 (名词)** — An evening social event
  - "The company held a evening event to celebrate the product launch."
- **义项 3: 黄昏 (名词)** — The time from sunset to bedtime
  - "We went for a walk in the cool of the evening."

---

### 16. event
- **义项 1: 事件 (名词)** — Something that happens, especially something important
  - "The system logs every significant event for auditing purposes."
- **义项 2: 活动 (名词)** — A planned social occasion
  - "The company organized a team-building event last weekend."
- **义项 3: 赛事 (名词)** — A competitive activity
  - "The hackathon was a three-day event with over 100 participants."

---

### 17. experience
- **义项 1: 经验 (名词)** — Knowledge gained through doing something
  - "She has five years of experience in backend development."
- **义项 2: 体验 (名词)** — An event that affects one personally
  - "Working at a startup was a valuable learning experience."
- **义项 3: 经历 (名词)** — Something that happens to someone
  - "Tell us about your experience migrating the legacy system."

---

### 18. family
- **义项 1: 家庭 (名词)** — A group of related people
  - "I spend weekends with my family."
- **义项 2: 家人 (名词)** — One's children, spouse, and relatives
  - "My family supports my decision to study abroad."
- **义项 3: 家族 (名词)** — A group of related things or people
  - "JavaScript belongs to the family of C-like languages."

---

### 19. food
- **义项 1: 食物 (名词)** — Things that people eat
  - "The company provides free food in the cafeteria."
- **义项 2: 食品 (名词)** — Edible substances
  - "I ordered food delivery for lunch because I was busy coding."
- **义项 3: 养料 (名词)** — Material that provides nourishment
  - "Mental food like reading technical blogs helps me grow."

---

### 20. friend
- **义项 1: 朋友 (名词)** — A person you know and like
  - "I made a lot of friends at the tech conference."
- **义项 2: 同事 (名词)** — A friendly acquaintance
  - "We have been friends since we worked together at the startup."
- **义项 3: 支持者 (名词)** — A person who supports a cause
  - "The open-source project has many friends in the community."

---

### 21. health
- **义项 1: 健康 (名词)** — The state of being free from illness
  - "Sitting at a desk all day is bad for your health."
- **义项 2: 健康状态 (名词)** — The condition of a system
  - "The monitoring dashboard shows the health of all services."
- **义项 3: 卫生 (名词)** — The practice of keeping clean
  - "The company promotes mental health awareness among employees."

---

### 22. home
- **义项 1: 家 (名词)** — The place where you live
  - "I work from home every Tuesday and Thursday."
- **义项 2: 家乡 (名词)** — Hometown or native place
  - "My home is in a small city in southern China."
- **义项 3: 主页 (名词)** — The main page of a website
  - "Click the logo to go back to the home page."

---

### 23. hospital
- **义项 1: 医院 (名词)** — A place where sick people receive medical treatment
  - "I went to the hospital for a regular health checkup."
- **义项 2: 医疗机构 (名词)** — A medical institution
  - "The hospital uses a new electronic health record system."
- **义项 3: 住院 (名词)** — The period of staying in a hospital
  - "He was in the hospital for two weeks after the surgery."

---

### 24. hotel
- **义项 1: 酒店 (名词)** — A place where travelers can stay
  - "We stayed at a hotel near the conference center."
- **义项 2: 旅馆 (名词)** — An establishment providing accommodation
  - "The company booked a hotel for the training session."
- **义项 3: 住宿 (名词)** — Lodging or accommodation
  - "The hotel has a business center with high-speed internet."

---

### 25. house
- **义项 1: 房子 (名词)** — A building for people to live in
  - "I am saving money to buy a house."
- **义项 2: 住宅 (名词)** — A home or dwelling
  - "The company rented a house for the visiting engineers."
- **义项 3: 机构 (名词)** — A business or organization
  - "The publishing house released a new book on software architecture."

---

### 26. idea
- **义项 1: 想法 (名词)** — A thought or suggestion
  - "I have an idea for improving the deployment process."
- **义项 2: 概念 (名词)** — A concept or notion
  - "The idea of microservices is not new — it has been around for years."
- **义项 3: 主意 (名词)** — A plan or intention
  - "That is a great idea — let us implement it in the next sprint."

---

### 27. information
- **义项 1: 信息 (名词)** — Facts or knowledge about something
  - "The README file contains important information about the project."
- **义项 2: 资料 (名词)** — Data that has been collected
  - "We need more information before we can diagnose the issue."
- **义项 3: 情报 (名词)** — Knowledge of events or situations
  - "The security team gathered information about the potential threat."

---

### 28. job
- **义项 1: 工作 (名词)** — Employment or a paid position
  - "I got a new job as a senior software engineer."
- **义项 2: 任务 (名词)** — A task or piece of work
  - "The CI job runs all the tests automatically."
- **义项 3: 职责 (名词)** — A responsibility or duty
  - "It is your job to ensure the code is properly tested."

---

### 29. knowledge
- **义项 1: 知识 (名词)** — Information and skills gained through experience
  - "Continuous learning is important to keep your knowledge up to date."
- **义项 2: 了解 (名词)** — Awareness or familiarity with something
  - "He has a working knowledge of several programming languages."
- **义项 3: 学识 (名词)** — Deep understanding of a field
  - "Her knowledge of distributed systems is impressive."

---

### 30. language
- **义项 1: 语言 (名词)** — A system of communication
  - "English is the universal language of the tech industry."
- **义项 2: 编程语言 (名词)** — A formal language for programming
  - "Python is a versatile programming language for data science."
- **义项 3: 术语 (名词)** — Specialized vocabulary of a field
  - "The language used in the technical document is very precise."

---

### 31. life
- **义项 1: 生活 (名词)** — The way someone lives
  - "I try to maintain a healthy work-life balance."
- **义项 2: 生命 (名词)** — The existence of a living being
  - "The software saves lives in medical applications."
- **义项 3: 寿命 (名词)** — The period of existence of something
  - "The battery life of my laptop is about 8 hours."

---

### 32. meeting
- **义项 1: 会议 (名词)** — A gathering of people for discussion
  - "We have a sprint planning meeting every Monday morning."
- **义项 2: 会面 (名词)** — A planned encounter between people
  - "I have a meeting with the project manager at 3 PM."
- **义项 3: 碰面 (名词)** — An accidental or informal encounter
  - "I had a chance meeting with an old colleague at the conference."

---

### 33. money
- **义项 1: 钱 (名词)** — Currency used for transactions
  - "The company made a lot of money from the cloud service."
- **义项 2: 资金 (名词)** — Financial resources
  - "We need to raise more money for the research project."
- **义项 3: 财富 (名词)** — Wealth or financial assets
  - "Time is more valuable than money in the software industry."

---

### 34. morning
- **义项 1: 早晨 (名词)** — The early part of the day
  - "I review my code in the morning when I am most focused."
- **义项 2: 上午 (名词)** — The period from sunrise to noon
  - "The standup meeting is every morning at 9:30."
- **义项 3: 清晨 (名词)** — The very early part of the day
  - "I go for a run in the early morning before work."

---

### 35. night
- **义项 1: 夜晚 (名词)** — The time when it is dark
  - "I worked late into the night to fix the critical bug."
- **义项 2: 晚上 (名词)** — The period from sunset to bedtime
  - "We had a team dinner on Friday night."
- **义项 3: 夜间 (名词)** — The period of darkness
  - "The deployment was scheduled for the night to minimize user impact."

---

### 36. office
- **义项 1: 办公室 (名词)** — A room or building where people work
  - "Our office is on the 15th floor of the building."
- **义项 2: 办事处 (名词)** — A branch or location of a company
  - "The company opened a new office in Beijing."
- **义项 3: 职位 (名词)** — An official position
  - "She holds the office of Chief Technology Officer."

---

### 37. people
- **义项 1: 人们 (名词)** — Human beings in general
  - "People in the tech industry are always learning new skills."
- **义项 2: 人民 (名词)** — The citizens of a country
  - "The Chinese people have embraced digital technology rapidly."
- **义项 3: 员工 (名词)** — The employees of an organization
  - "Our company has over 500 people across three offices."

---

### 38. person
- **义项 1: 人 (名词)** — An individual human being
  - "She is the right person for the senior developer role."
- **义项 2: 本人 (名词)** — Someone's own self
  - "I need to speak to the person in charge of the deployment."
- **义项 3: 人称 (名词)** — A grammatical category
  - "The verb changes form depending on the person (first, second, third)."

---

### 39. phone
- **义项 1: 电话 (名词)** — A device for voice communication
  - "I called him on the phone to discuss the urgent issue."
- **义项 2: 手机 (名词)** — A mobile telephone
  - "I check my phone for work emails first thing in the morning."
- **义项 3: 电话系统 (名词)** — The telephone system
  - "The office phone is not working — we need to call IT support."

---

### 40. problem
- **义项 1: 问题 (名词)** — A matter that is difficult to solve
  - "We have a problem with the database replication."
- **义项 2: 故障 (名词)** — A malfunction or error
  - "The network problem caused the deployment to fail."
- **义项 3: 难题 (名词)** — A difficult question or challenge
  - "Solving the performance problem requires deep analysis."

---

### 41. restaurant
- **义项 1: 餐厅 (名词)** — A place where meals are served to customers
  - "We had lunch at a restaurant near the office."
- **义项 2: 饭店 (名词)** — An establishment serving food
  - "The team celebrated the successful release at a nice restaurant."
- **义项 3: 餐馆 (名词)** — A commercial establishment for dining
  - "The restaurant has a private room for business dinners."

---

### 42. school
- **义项 1: 学校 (名词)** — An institution for education
  - "I studied computer science at a top university."
- **义项 2: 学院 (名词)** — A department within a university
  - "The School of Engineering has a strong software program."
- **义项 3: 学派 (名词)** — A group of people sharing similar ideas
  - "There are different schools of thought on agile methodology."

---

### 43. store
- **义项 1: 商店 (名词)** — A retail establishment
  - "I bought a new keyboard at the electronics store."
- **义项 2: 库存 (名词)** — A supply of something kept for use
  - "We have a store of backup hardware in the server room."
- **义项 3: 存储 (名词)** — A place where data is kept
  - "The app store has thousands of productivity applications."

---

### 44. team
- **义项 1: 团队 (名词)** — A group of people working together
  - "Our team is responsible for the payment system."
- **义项 2: 小队 (名词)** — A small group organized for a purpose
  - "The SRE team handles all production incidents."
- **义项 3: 队友 (名词)** — Fellow members of a team
  - "The whole team worked together to meet the deadline."

---

### 45. technology
- **义项 1: 技术 (名词)** — The application of scientific knowledge for practical purposes
  - "Technology is changing the way we work and live."
- **义项 2: 科技 (名词)** — Advanced tools and methods
  - "Our company invests heavily in new technology."
- **义项 3: 技术手段 (名词)** — A specific technical method
  - "Container technology has revolutionized software deployment."

---

### 46. time
- **义项 1: 时间 (名词)** — A measurable period of events
  - "I do not have enough time to finish this today."
- **义项 2: 次数 (名词)** — An instance or occurrence
  - "I have told you three times to update the documentation."
- **义项 3: 时代 (名词)** — A period in history
  - "At that time, we were still using monolithic architecture."

---

### 47. travel
- **义项 1: 旅行 (名词)** — The act of going from one place to another
  - "Business travel is part of my job — I visit clients regularly."
- **义项 2: 出差 (名词)** — A journey for work purposes
  - "The company covers all travel expenses for the conference."
- **义项 3: 行程 (名词)** — A journey or trip
  - "The travel to the client site takes about two hours."

---

### 48. university
- **义项 1: 大学 (名词)** — A higher education institution
  - "I graduated from a university with a degree in software engineering."
- **义项 2: 大学校园 (名词)** — The campus of a university
  - "The job fair was held at the university."
- **义项 3: 大学教育 (名词)** — University education
  - "University taught me how to learn, not just what to learn."

---

### 49. water
- **义项 1: 水 (名词)** — A clear liquid essential for life
  - "Drink plenty of water during long coding sessions."
- **义项 2: 水域 (名词)** — An area of water
  - "The office has a great view of the water."
- **义项 3: 自来水 (名词)** — Running water from a tap
  - "The water in the office is safe to drink."

---

### 50. work
- **义项 1: 工作 (名词)** — Activity involving effort for a purpose
  - "I have a lot of work to do before the deadline."
- **义项 2: 作品 (名词)** — Something produced by effort
  - "Her work on the authentication system is excellent."
- **义项 3: 著作 (名词)** — A creative or intellectual product
  - "The published work on software architecture is widely read."

---

### Group 5: Common Adjectives（50 个常用形容词）

---

### 1. able
- **义项 1: 能够的 (形容词)** — Having the ability to do something
  - "I am able to complete the task by Friday."
- **义项 2: 有能力的 (形容词)** — Skilled or competent
  - "She is an able engineer who can handle complex problems."
- **义项 3: 有才华的 (形容词)** — Talented or capable
  - "The team is made up of able and dedicated professionals."

---

### 2. bad
- **义项 1: 坏的 (形容词)** — Of poor quality or low standard
  - "The code quality is bad — we need to refactor it."
- **义项 2: 严重的 (形容词)** — Serious or severe
  - "The data loss was bad, but we had a backup."
- **义项 3: 不好的 (形容词)** — Unpleasant or unfavorable
  - "The news about the security breach is bad for the company."

---

### 3. best
- **义项 1: 最好的 (形容词)** — Of the highest quality or standard
  - "This is the best approach for handling high traffic."
- **义项 2: 最合适的 (形容词)** — Most suitable or appropriate
  - "The best time to deploy is late at night."
- **义项 3: 最大的 (形容词)** — The greatest in amount
  - "The best part of my job is solving challenging problems."

---

### 4. better
- **义项 1: 更好的 (形容词)** — Of a higher quality than something else
  - "This solution is better than the previous one."
- **义项 2: 好转的 (形容词)** — Improving in health or condition
  - "The server performance is better after the optimization."
- **义项 3: 更合适的 (形容词)** — More suitable or appropriate
  - "It is better to test thoroughly before deploying."

---

### 5. big
- **义项 1: 大的 (形容词)** — Large in size or scale
  - "We have a big project coming up next quarter."
- **义项 2: 重要的 (形容词)** — Important or significant
  - "This is a big opportunity for the company."
- **义项 3: 巨大的 (形容词)** — Large in amount or degree
  - "There is a big difference between theory and practice."

---

### 6. clear
- **义项 1: 清楚的 (形容词)** — Easy to understand
  - "The documentation is clear and well-organized."
- **义项 2: 明确的 (形容词)** — Obvious and definite
  - "The requirements are clear — we know exactly what to build."
- **义项 3: 清晰的 (形容词)** — Easy to see or hear
  - "The error message is not clear — it needs more details."

---

### 7. cold
- **义项 1: 冷的 (形容词)** — Having a low temperature
  - "The server room is too cold — I need a jacket."
- **义项 2: 冷淡的 (形容词)** — Unfriendly or unemotional
  - "His response was cold and unhelpful."
- **义项 3: 凉的 (形容词)** — Not warm enough
  - "My coffee went cold while I was debugging."

---

### 8. common
- **义项 1: 常见的 (形容词)** — Happening frequently
  - "Null pointer exceptions are a common bug in Java."
- **义项 2: 共同的 (形容词)** — Shared by two or more people
  - "We have a common goal: to deliver a quality product."
- **义项 3: 普通的 (形容词)** — Ordinary or typical
  - "It is common practice to run tests before pushing code."

---

### 9. complete
- **义项 1: 完整的 (形容词)** — Having all necessary parts
  - "The test suite is complete — it covers all edge cases."
- **义项 2: 完成的 (形容词)** — Finished or concluded
  - "The migration is complete — all data has been transferred."
- **义项 3: 彻底的 (形容词)** — Thorough and absolute
  - "The audit was a complete investigation of the system."

---

### 10. dark
- **义项 1: 暗的 (形容词)** — Without light or not bright
  - "It gets dark early in winter, so I leave the office before sunset."
- **义项 2: 深色的 (形容词)** — Deep in color
  - "Set the IDE to dark mode to reduce eye strain."
- **义项 3: 黑暗的 (形容词)** — Gloomy or pessimistic
  - "The outlook for the project looked dark after the budget cut."

---

### 11. different
- **义项 1: 不同的 (形容词)** — Not the same as something else
  - "Each microservice has a different deployment schedule."
- **义项 2: 各种各样的 (形容词)** — Various or diverse
  - "There are different ways to solve this problem."
- **义项 3: 与众不同的 (形容词)** — Distinctive or unusual
  - "Her approach to debugging is different from most engineers."

---

### 12. difficult
- **义项 1: 困难的 (形容词)** — Hard to do or accomplish
  - "Debugging a race condition is very difficult."
- **义项 2: 难懂的 (形容词)** - Hard to understand
  - "The technical concept was difficult to grasp at first."
- **义项 3: 难相处的 (形容词)** — Hard to deal with
  - "The client was difficult to please, but we managed."

---

### 13. early
- **义项 1: 早的 (形容词)** — Happening before the expected time
  - "We had an early morning standup to discuss the incident."
- **义项 2: 早期的 (形容词)** — Near the beginning of a period
  - "In the early stages of the project, we focused on architecture."
- **义项 3: 提前的 (形容词)** — Before the usual time
  - "The deployment finished earlier than expected."

---

### 14. easy
- **义项 1: 容易的 (形容词)** — Not difficult
  - "This bug is easy to fix — it is just a typo."
- **义项 2: 轻松的 (形容词)** — Comfortable and without worry
  - "We had an easy day after the big release."
- **义项 3: 简单的 (形容词)** — Simple and straightforward
  - "The setup process is easy if you follow the instructions."

---

### 15. excellent
- **义项 1: 优秀的 (形容词)** — Extremely good
  - "She did an excellent job on the performance optimization."
- **义项 2: 出色的 (形容词)** — Outstanding or exceptional
  - "The team's work on the migration was excellent."
- **义项 3: 极好的 (形容词)** — Very high quality
  - "The restaurant has excellent food — we should go there for the team dinner."

---

### 16. expensive
- **义项 1: 贵的 (形容词)** — Costing a lot of money
  - "The new server hardware is quite expensive."
- **义项 2: 昂贵的 (形容词)** — High in price
  - "Cloud computing can be expensive if not managed properly."
- **义项 3: 代价大的 (形容词)** — Involving a high cost or sacrifice
  - "The mistake was expensive — we lost two days of work."

---

### 17. fair
- **义项 1: 公平的 (形容词)** — Treating everyone equally
  - "The performance review process should be fair to all employees."
- **义项 2: 尚可的 (形容词)** — Average or moderately good
  - "The code quality is fair, but it could be better."
- **义项 3: 晴朗的 (形容词)** — (Of weather) bright and clear
  - "The weather was fair for the outdoor team-building event."

---

### 18. famous
- **义项 1: 著名的 (形容词)** — Known by many people
  - "He is a famous open-source contributor."
- **义项 2: 出名的 (形容词)** — Widely recognized
  - "The company is famous for its innovative culture."
- **义项 3: 有名的 (形容词)** — Well-known for a particular quality
  - "The city is famous for its technology parks."

---

### 19. fast
- **义项 1: 快的 (形容词)** — Moving or operating at high speed
  - "The new server is much faster than the old one."
- **义项 2: 迅速的 (形容词)** — Done in a short time
  - "We need a fast response to the security incident."
- **义项 3: 牢固的 (形容词)** — Firmly fixed or attached
  - "Make sure the cable connection is fast and secure."

---

### 20. free
- **义项 1: 免费的 (形容词)** — Costing nothing
  - "The community edition of the software is free."
- **义项 2: 自由的 (形容词)** — Not restricted or confined
  - "I feel free to express my ideas in the team."
- **义项 3: 空闲的 (形容词)** — Not occupied or in use
  - "I am free this afternoon if you want to do a code review."

---

### 21. full
- **义项 1: 满的 (形容词)** — Containing as much as possible
  - "The disk is full — we need to free up some space."
- **义项 2: 完整的 (形容词)** — Complete or entire
  - "Please provide a full description of the bug."
- **义项 3: 饱的 (形容词)** — Having eaten enough
  - "I am full after the team lunch."

---

### 22. good
- **义项 1: 好的 (形容词)** — Of a high quality or standard
  - "This is a good solution to the performance problem."
- **义项 2: 擅长的 (形容词)** — Skilled at doing something
  - "She is good at debugging complex issues."
- **义项 3: 有益的 (形容词)** — Beneficial or advantageous
  - "Regular code reviews are good for team development."

---

### 23. great
- **义项 1: 伟大的 (形容词)** — Very good or excellent
  - "The team did a great job on the release."
- **义项 2: 巨大的 (形容词)** — Large in amount or size
  - "There is a great demand for cloud engineers."
- **义项 3: 极好的 (形容词)** — Very enjoyable or impressive
  - "It is great to see the project succeed."

---

### 24. happy
- **义项 1: 高兴的 (形容词)** — Feeling or showing pleasure
  - "I am happy with the test results."
- **义项 2: 满意的 (形容词)** — Content or satisfied
  - "The client is happy with the progress we have made."
- **义项 3: 乐意的 (形容词)** — Willing to do something
  - "I am happy to help with the code review."

---

### 25. hard
- **义项 1: 难的 (形容词)** — Requiring a lot of effort
  - "The algorithm problem is hard to solve."
- **义项 2: 努力的 (形容词)** — Using a lot of effort
  - "She is a hard worker who always meets deadlines."
- **义项 3: 硬的 (形容词)** — Firm and not soft
  - "The hard drive stores all of the company's data."

---

### 26. heavy
- **义项 1: 重的 (形容词)** — Of great weight
  - "The server is too heavy for one person to carry."
- **义项 2: 大量的 (形容词)** — Large in amount or degree
  - "The database has heavy traffic during business hours."
- **义项 3: 沉重的 (形容词)** — Serious or intense
  - "The responsibility of the production system is a heavy burden."

---

### 27. high
- **义项 1: 高的 (形容词)** — Of great vertical extent
  - "The server rack is about two meters high."
- **义项 2: 高的 (形容词)** — Large in amount or value
  - "The system has high availability requirements."
- **义项 3: 高级的 (形容词)** — Advanced or above average
  - "She holds a high position in the engineering department."

---

### 28. hot
- **义项 1: 热的 (形容词)** — Having a high temperature
  - "The server room gets very hot in the summer."
- **义项 2: 辣的 (形容词)** — Spicy in flavor
  - "I like hot food — Sichuan cuisine is my favorite."
- **义项 3: 热门的 (形容词)** — Popular or trending
  - "Kubernetes is a hot topic in the DevOps world."

---

### 29. important
- **义项 1: 重要的 (形容词)** — Having great significance
  - "Security is important for any software application."
- **义项 2: 要紧的 (形容词)** — Urgent or critical
  - "It is important that we fix this bug before the release."
- **义项 3: 有影响力的 (形容词)** — Having power or influence
  - "She is an important figure in the open-source community."

---

### 30. large
- **义项 1: 大的 (形容词)** — Big in size or amount
  - "We need a large database to store all the user data."
- **义项 2: 大规模的 (形容词)** — Extensive or wide-ranging
  - "The company made large investments in cloud infrastructure."
- **义项 3: 广泛的 (形容词)** — Broad or comprehensive
  - "The update introduces a large number of new features."

---

### 31. late
- **义项 1: 晚的 (形容词)** — After the expected time
  - "I was late for the standup meeting because of a traffic jam."
- **义项 2: 迟的 (形容词)** — Happening near the end of a period
  - "We made a late decision to postpone the release."
- **义项 3: 最近的 (形容词)** — Recent (late + noun)
  - "The latest version of the software includes bug fixes."

---

### 32. likely
- **义项 1: 可能的 (形容词)** — Probably going to happen
  - "It is likely that the deployment will be delayed."
- **义项 2: 有可能的 (形容词)** — Reasonably expected
  - "A memory leak is the likely cause of the crash."
- **义项 3: 合适的 (形容词)** — Suitable or appropriate
  - "This is a likely candidate for the optimization."

---

### 33. little
- **义项 1: 小的 (形容词)** — Small in size or amount
  - "I made a little change to the configuration file."
- **义项 2: 少的 (形容词)** — Not much or not enough
  - "There is little we can do about the network issue."
- **义项 3: 年轻的 (形容词)** — Young or small in age
  - "My little brother is also studying computer science."

---

### 34. local
- **义项 1: 本地的 (形容词)** — Relating to a specific place or area
  - "The bug only appears in the local development environment."
- **义项 2: 当地的 (形容词)** — Nearby or in the area
  - "We hired local talent for the new office."
- **义项 3: 局部的 (形容词)** — Limited to a specific part
  - "The issue is local to the authentication service only."

---

### 35. long
- **义项 1: 长的 (形容词)** — Extending far in distance or time
  - "The build process takes a long time."
- **义项 2: 长时间的 (形容词)** — Lasting for a considerable time
  - "We had a long meeting about the project roadmap."
- **义项 3: 长期的 (形容词)** — Involving a long period
  - "We need a long-term solution for the scaling problem."

---

### 36. low
- **义项 1: 低的 (形容词)** — Small in height or amount
  - "The server load is low during the weekend."
- **义项 2: 少的 (形容词)** — Below average in quantity
  - "The test coverage is too low — we need more tests."
- **义项 3: 低落的 (形容词)** — Lacking energy or enthusiasm
  - "Team morale was low after the failed release."

---

### 37. main
- **义项 1: 主要的 (形容词)** — Most important or primary
  - "The main branch should always be stable."
- **义项 2: 主干的 (形容词)** — Central or principal
  - "The main function is the entry point of the program."
- **义项 3: 主要的 (形容词)** — Largest or most significant
  - "The main office is in Beijing, with branches in other cities."

---

### 38. major
- **义项 1: 主要的 (形容词)** — Important or significant
  - "This is a major update with many new features."
- **义项 2: 重大的 (形容词)** — Serious in effect
  - "The security breach was a major incident."
- **义项 3: 主要的 (形容词)** — Larger in degree or importance
  - "A major refactor of the codebase is overdue."

---

### 39. national
- **义项 1: 国家的 (形容词)** — Relating to a whole nation
  - "The company has offices in all major national cities."
- **义项 2: 国内的 (形容词)** — Domestic rather than international
  - "The national market is our primary focus this year."
- **义项 3: 民族的 (形容词)** — Relating to a particular ethnic group
  - "The national culture influences how teams communicate."

---

### 40. natural
- **义项 1: 自然的 (形容词)** — Existing in or derived from nature
  - "Natural language processing is a key AI technology."
- **义项 2: 天生的 (形容词)** — Innate or inborn
  - "She has a natural talent for system architecture."
- **义项 3: 正常的 (形容词)** — Normal or expected
  - "It is natural to make mistakes when learning a new framework."

---

### 41. necessary
- **义项 1: 必要的 (形容词)** — Required or essential
  - "A backup is necessary before upgrading the system."
- **义项 2: 必需的 (形容词)** — Needed to achieve a goal
  - "Code reviews are necessary for maintaining quality."
- **义项 3: 不可避免的 (形容词)** — Inevitable or unavoidable
  - "Some downtime is necessary for the hardware upgrade."

---

### 42. new
- **义项 1: 新的 (形容词)** — Recently made or discovered
  - "We are adopting a new framework for the frontend."
- **义项 2: 新来的 (形容词)** — Recently arrived or joined
  - "The new developer started today."
- **义项 3: 陌生的 (形容词)** — Not previously known or experienced
  - "The new system takes time to get used to."

---

### 43. nice
- **义项 1: 好的 (形容词)** — Pleasant or enjoyable
  - "It is nice to see the tests passing."
- **义项 2: 友好的 (形容词)** — Kind or friendly
  - "The team is very nice to new members."
- **义项 3: 精致的 (形容词)** — Fine or subtle
  - "That is a nice solution to the problem."

---

### 44. normal
- **义项 1: 正常的 (形容词)** — Usual or typical
  - "The server load is normal for this time of day."
- **义项 2: 普通的 (形容词)** — Standard or average
  - "Under normal circumstances, the deployment takes 10 minutes."
- **义项 3: 精神正常的 (形容词)** — Mentally sound
  - "Only a normal person would double-check before deploying on Friday."

---

### 45. old
- **义项 1: 旧的 (形容词)** — Having existed for a long time
  - "The old server is being decommissioned next week."
- **义项 2: 老的 (形容词)** — Advanced in age
  - "My old manager taught me a lot about software engineering."
- **义项 3: 以前的 (形容词)** — Former or previous
  - "In the old system, we did not have automated testing."

---

### 46. open
- **义项 1: 开着的 (形容词)** — Not closed or shut
  - "The database connection is still open."
- **义项 2: 开放的 (形容词)** — Accessible or available
  - "The issue is still open — nobody has fixed it yet."
- **义项 3: 公开的 (形容词)** — Not hidden or secret
  - "We believe in open communication within the team."

---

### 47. personal
- **义项 1: 个人的 (形容词)** — Relating to a particular person
  - "I use my personal laptop for the remote work."
- **义项 2: 私人的 (形容词)** — Private or confidential
  - "Do not share personal information in the public chat."
- **义项 3: 亲自的 (形容词)** — Done in person
  - "I will give it my personal attention."

---

### 48. popular
- **义项 1: 流行的 (形容词)** — Liked or admired by many people
  - "React is a popular frontend framework."
- **义项 2: 受欢迎的 (形容词)** — Well-liked or widely accepted
  - "The new feature is popular among users."
- **义项 3: 大众的 (形容词)** — Relating to the general public
  - "Python is popular in the data science community."

---

### 49. possible
- **义项 1: 可能的 (形容词)** — Able to be done or achieved
  - "Is it possible to deploy twice a week?"
- **义项 2: 潜在的 (形容词)** — That may exist or happen
  - "We identified all possible failure scenarios."
- **义项 3: 合理的 (形容词)** — Reasonable or plausible
  - "It is possible that the bug is caused by a configuration error."

---

### 50. public
- **义项 1: 公共的 (形容词)** — Open to all people
  - "The API is public — anyone can access it."
- **义项 2: 公开的 (形容词)** — Not private or secret
  - "The incident report is public to the engineering team."
- **义项 3: 政府的 (形容词)** — Relating to government services
  - "The company works on public sector projects."

---

### Group 6: Adverbs, Prepositions, Conjunctions（50 个功能词）

---

### 1. about
- **义项 1: 关于 (介词)** — On the subject of
  - "This book is about distributed systems."
- **义项 2: 大约 (副词)** — Approximately or roughly
  - "The deployment takes about 15 minutes."
- **义项 3: 到处 (副词)** — In many directions or places (美式英语)
  - "Stop running about and focus on the task."

---

### 2. after
- **义项 1: 在……之后 (介词)** — Following in time
  - "After the deployment, we monitored the system for an hour."
- **义项 2: 之后 (连词)** — Following the time when
  - "After we finish the sprint, we will have a retrospective."
- **义项 3: 追赶 (副词)** — Following in pursuit
  - "The security team is after the root cause of the breach."

---

### 3. already
- **义项 1: 已经 (副词)** — Before now or before a particular time
  - "The tests are already passing — we can merge the PR."
- **义项 2: 早已 (副词)** — So soon
  - "Have you already finished the code review?"
- **义项 3: 已经 (副词)** — Used to emphasize that something is done
  - "I already told you — the database migration is complete."

---

### 4. also
- **义项 1: 也 (副词)** — In addition to
  - "She is also working on the authentication feature."
- **义项 2: 还 (副词)** — Besides or as well
  - "The bug also affects the search functionality."
- **义项 3: 同样 (副词)** — Likewise or similarly
  - "Also, remember to update the API documentation."

---

### 5. although
- **义项 1: 虽然 (连词)** — Despite the fact that
  - "Although the tests passed, we found a bug in production."
- **义项 2: 尽管 (连词)** — Even though
  - "Although he is a junior developer, he writes clean code."
- **义项 3: 但是 (连词)** — However or nevertheless (at end of clause)
  - "The system is stable, although we should still monitor it."

---

### 6. always
- **义项 1: 总是 (副词)** — At all times or every time
  - "Always test your code before pushing."
- **义项 2: 一直 (副词)** — Continuously or forever
  - "The server is always running — it never goes down."
- **义项 3: 老是 (副词)** — Repeatedly or persistently
  - "He is always suggesting new ideas in meetings."

---

### 7. among
- **义项 1: 在……之中 (介词)** — Surrounded by or in the middle of
  - "Among the team members, she has the most experience."
- **义项 2: 其中之一 (介词)** — Being a member of a group
  - "This issue is among the top priorities for this sprint."
- **义项 3: 在……之间 (介词)** — Shared by a group
  - "The tasks were divided among the team members."

---

### 8. and
- **义项 1: 和 (连词)** — Used to connect words or phrases
  - "I fixed the bug and deployed the fix to production."
- **义项 2: 并且 (连词)** — In addition to
  - "The application is fast and reliable."
- **义项 3: 然后 (连词)** — Then or as a result
  - "Complete the review and submit your feedback."

---

### 9. around
- **义项 1: 大约 (副词)** — Approximately
  - "The meeting starts around 2 PM."
- **义项 2: 环绕 (介词)** — On all sides of something
  - "There is a security fence around the data center."
- **义项 3: 到处 (副词)** — In various places
  - "I looked around for the error in the log file."

---

### 10. as
- **义项 1: 作为 (介词)** — In the role of
  - "As a senior engineer, she leads the architecture discussions."
- **义项 2: 当……时 (连词)** — At the same time that
  - "As the server started, the logs began to fill up."
- **义项 3: 因为 (连词)** — Because or since
  - "As the deadline is approaching, we need to work faster."

---

### 11. because
- **义项 1: 因为 (连词)** — For the reason that
  - "The deployment failed because the tests did not pass."
- **义项 2: 由于 (连词)** — As a result of
  - "We chose AWS because it offers better scaling options."
- **义项 3: 原因是 (连词)** — The reason being
  - "The bug was hard to find because it only appeared at night."

---

### 12. before
- **义项 1: 在……之前 (介词)** — Earlier than a specific time
  - "Review the code before merging the PR."
- **义项 2: 在……之前 (连词)** — Earlier than the time when
  - "Before you deploy, make sure all tests pass."
- **义项 3: 之前 (副词)** — At an earlier time
  - "I have seen this error before — it is a configuration issue."

---

### 13. between
- **义项 1: 在……之间 (介词，两者)** — In the space separating two things
  - "The connection between the database and the server timed out."
- **义项 2: 在……之间 (介词，选择)** — In the interval separating
  - "Choose between the monolith and microservices approach."
- **义项 3: 介于 (介词)** — Shared by two people
  - "The collaboration between the teams was excellent."

---

### 14. both
- **义项 1: 两者都 (限定词)** — The two as well as each other
  - "Both the frontend and backend need to be updated."
- **义项 2: 两者都 (代词)** — The two people or things
  - "Both of the servers are down for maintenance."
- **义项 3: 既……又 (连词，both...and)** — Not only...but also
  - "The solution is both efficient and cost-effective."

---

### 15. but
- **义项 1: 但是 (连词)** — Used to introduce a contrast
  - "The code compiled, but the tests failed."
- **义项 2: 除了 (介词)** — Except or apart from
  - "All but one of the services are running normally."
- **义项 3: 而 (连词)** — On the contrary
  - "Not the quantity but the quality of code matters."

---

### 16. by
- **义项 1: 通过 (介词)** — Indicating the means or method
  - "We improved performance by adding a caching layer."
- **义项 2: 在……之前 (介词)** — Not later than a specific time
  - "The report must be submitted by Friday."
- **义项 3: 被 (介词)** — Indicating the agent in passive voice
  - "The bug was fixed by a junior developer."

---

### 17. during
- **义项 1: 在……期间 (介词)** — Throughout a period of time
  - "During the deployment, the site was in maintenance mode."
- **义项 2: 在……时候 (介词)** — At some point in a period
  - "The server crashed during the peak traffic hours."
- **义项 3: 在……过程中 (介词)** — In the course of an activity
  - "During the code review, several issues were identified."

---

### 18. either
- **义项 1: 两者之一 (限定词)** — One or the other of two
  - "Either solution will work for our use case."
- **义项 2: 也（不）(副词)** — Used with negative for "also not"
  - "The API is not responding, and the database is not either."
- **义项 3: 要么……要么 (连词，either...or)** — Used to present alternatives
  - "Either we refactor now, or we will pay the technical debt later."

---

### 19. enough
- **义项 1: 足够的 (限定词)** — As much as is needed
  - "We do not have enough test coverage for this module."
- **义项 2: 足够地 (副词)** — To the required degree
  - "The server is fast enough for our current needs."
- **义项 3: 充分 (副词)** — Adequately or sufficiently
  - "The documentation explains the process well enough."

---

### 20. especially
- **义项 1: 尤其 (副词)** — In particular or above all
  - "I enjoy debugging, especially when the root cause is tricky."
- **义项 2: 特别 (副词)** — Particularly or exceptionally
  - "The database is especially slow during peak hours."
- **义项 3: 专门 (副词)** — For a particular purpose
  - "This tool was designed especially for log analysis."

---

### 21. even
- **义项 1: 甚至 (副词)** — Used to emphasize something surprising
  - "Even senior developers make mistakes sometimes."
- **义项 2: 更 (副词)** — Used with comparatives for emphasis
  - "The new server is even faster than we expected."
- **义项 3: 即使 (连词，even if/though)** — Despite the fact that
  - "Even if the tests pass, we should still do a manual check."

---

### 22. eventually
- **义项 1: 最终 (副词)** — In the end or after some time
  - "The team eventually found the root cause of the crash."
- **义项 2: 终于 (副词)** — After a long wait or effort
  - "The deployment eventually completed after three attempts."
- **义项 3: 终究 (副词)** — Ultimately or in the final analysis
  - "All bugs will eventually be found and fixed."

---

### 23. finally
- **义项 1: 终于 (副词)** — After a long time or delay
  - "The build finally finished after 20 minutes."
- **义项 2: 最后 (副词)** — As the last point or item
  - "Finally, remember to update the documentation."
- **义项 3: 最终 (副词)** — At the end or conclusion
  - "We finally agreed on the architecture design."

---

### 24. for
- **义项 1: 为了 (介词)** — Indicating purpose or intended use
  - "This tool is for monitoring server performance."
- **义项 2: 持续 (介词)** — Indicating duration of time
  - "The server has been running for 30 days without issues."
- **义项 3: 因为 (连词)** — Because or since (formal/rare)
  - "The deployment was delayed, for the tests had failed."

---

### 25. from
- **义项 1: 从 (介词)** — Indicating a starting point
  - "The error originates from a null pointer dereference."
- **义项 2: 来自 (介词)** — Indicating origin or source
  - "I received an email from the support team."
- **义项 3: 从……离开 (介词)** — Indicating separation or removal
  - "Remove the old server from the cluster."

---

### 26. further
- **义项 1: 进一步 (副词)** — To a greater degree or extent
  - "We need to investigate the issue further."
- **义项 2: 更远 (形容词)** — More distant or advanced
  - "For further details, refer to the documentation."
- **义项 3: 此外 (副词)** — In addition or moreover
  - "Further, we recommend upgrading the database version."

---

### 27. however
- **义项 1: 然而 (副词)** — Used to introduce a contrasting point
  - "The tests passed; however, we found a bug in production."
- **义项 2: 不管怎样 (副词)** — To whatever extent
  - "However long it takes, we must fix this issue."
- **义项 3: 尽管如此 (副词)** — Nevertheless
  - "The approach is risky. However, it might be worth trying."

---

### 28. immediately
- **义项 1: 立即 (副词)** — Without any delay
  - "The system immediately triggered an alert when the error occurred."
- **义项 2: 马上 (副词)** — At once or instantly
  - "Respond to production incidents immediately."
- **义项 3: 直接地 (副词)** — With no intermediary
  - "The changes were immediately visible after the deployment."

---

### 29. just
- **义项 1: 刚才 (副词)** — A very short time ago
  - "I just finished the code review."
- **义项 2: 仅仅 (副词)** — Only or simply
  - "Just run the test command to verify your changes."
- **义项 3: 正好 (副词)** — Exactly or precisely
  - "That is just what we needed to fix the bug."

---

### 30. later
- **义项 1: 以后 (副词)** — At a subsequent time
  - "I will check the logs later when I have more time."
- **义项 2: 后来 (副词)** — After the present or a specified time
  - "Later, we discovered that the issue was a configuration error."
- **义项 3: 稍后 (副词)** — After some time has passed
  - "Let us discuss this later in the meeting."

---

### 31. meanwhile
- **义项 1: 与此同时 (副词)** — At the same time
  - "The frontend team worked on the UI; meanwhile, the backend team optimized the API."
- **义项 2: 在此期间 (副词)** — During the intervening time
  - "The server was rebooting; meanwhile, we prepared the rollback plan."
- **义项 3: 另一方面 (副词)** — Used to introduce a contrasting point
  - "The new feature was popular with users. Meanwhile, the engineering team struggled with maintenance."

---

### 32. more
- **义项 1: 更多 (限定词)** — A greater amount or number
  - "We need more test coverage for the new feature."
- **义项 2: 更 (副词)** — To a greater extent
  - "The new framework is more efficient than the old one."
- **义项 3: 另外 (副词)** — Further or additionally
  - "More importantly, the system is now stable."

---

### 33. moreover
- **义项 1: 此外 (副词)** — In addition to what has been said
  - "The solution is fast. Moreover, it is easy to maintain."
- **义项 2: 而且 (副词)** — Furthermore or besides
  - "The deployment was smooth. Moreover, no issues were reported."
- **义项 3: 更重要的是 (副词)** — Used to add a stronger point
  - "The team met the deadline; moreover, they exceeded expectations."

---

### 34. mostly
- **义项 1: 主要地 (副词)** — Mainly or for the most part
  - "The delay was mostly caused by the database migration."
- **义项 2: 通常 (副词)** — In most cases or usually
  - "The system mostly runs without issues."
- **义项 3: 几乎全部 (副词)** — Almost all or almost completely
  - "The codebase is mostly written in Python."

---

### 35. neither
- **义项 1: 两者都不 (限定词)** — Not one nor the other
  - "Neither approach solved the performance problem."
- **义项 2: 也不 (副词)** — Used with negative to agree
  - "The API is not responding. Neither is the database."
- **义项 3: 既不……也不 (连词，neither...nor)** — Used to negate two things
  - "Neither the frontend nor the backend was affected."

---

### 36. never
- **义项 1: 从不 (副词)** — At no time or not ever
  - "I never deploy on a Friday."
- **义项 2: 决不 (副词)** — Not at all or absolutely not
  - "Never push directly to the main branch."
- **义项 3: 从未 (副词)** — Not ever in the past
  - "I have never seen this error before."

---

### 37. nor
- **义项 1: 也不 (连词)** — And not (used after neither)
  - "Neither the developers nor the testers noticed the bug."
- **义项 2: 也不 (连词)** — And not or also not
  - "The logs did not show the error, nor did the monitoring alerts fire."
- **义项 3: 也不 (连词)** — Used in negative sentences for emphasis
  - "The system is not slow, nor is it unreliable."

---

### 38. now
- **义项 1: 现在 (副词)** — At the present time
  - "Now is the best time to deploy."
- **义项 2: 立刻 (副词)** — Immediately or without delay
  - "Fix the bug now before it causes more issues."
- **义项 3: 既然 (连词，now that)** — Because of the fact that
  - "Now that the tests pass, we can merge the PR."

---

### 39. often
- **义项 1: 经常 (副词)** — Frequently or many times
  - "We often do code reviews after lunch."
- **义项 2: 常常 (副词)** — In many instances
  - "The database often becomes the bottleneck under heavy load."
- **义项 3: 往往 (副词)** — Typically or usually
  - "Senior engineers often catch subtle issues in code reviews."

---

### 40. once
- **义项 1: 一次 (副词)** — One time only
  - "Run the test suite once more to make sure everything passes."
- **义项 2: 曾经 (副词)** — At some time in the past
  - "Once, the system crashed and took two days to recover."
- **义项 3: 一旦 (连词)** — As soon as or when
  - "Once the deployment is complete, verify the services are healthy."

---

### 41. only
- **义项 1: 只有 (副词)** — Solely or exclusively
  - "Only merge the PR after the CI checks pass."
- **义项 2: 仅仅 (形容词)** — Single or sole
  - "The only solution is to rollback the deployment."
- **义项 3: 唯一的 (形容词)** — Alone of its kind
  - "This is the only server that supports the legacy system."

---

### 42. or
- **义项 1: 或者 (连词)** — Used to connect alternatives
  - "We can use MongoDB or PostgreSQL for the database."
- **义项 2: 否则 (连词)** — If not or otherwise
  - "Fix the bug now, or the release will be delayed."
- **义项 3: 还是 (连词)** — Used in questions to present choices
  - "Do you prefer Agile or Waterfall methodology?"

---

### 43. rather
- **义项 1: 相当 (副词)** — To a certain extent or fairly
  - "The new API is rather slow under heavy load."
- **义项 2: 宁愿 (副词)** — More willingly or preferably
  - "I would rather refactor the code than add new features."
- **义项 3: 而不是 (连词，rather than)** — Instead of
  - "We should fix the root cause rather than treating the symptoms."

---

### 44. since
- **义项 1: 自从 (介词)** — From a specific time in the past
  - "The server has been stable since the last update."
- **义项 2: 因为 (连词)** — Because or as
  - "Since the tests passed, we can proceed with the deployment."
- **义项 3: 自从……以来 (连词)** — From a past time until now
  - "Since we moved to the cloud, our uptime has improved."

---

### 45. so
- **义项 1: 所以 (连词)** — Therefore or as a result
  - "The database connection failed, so the application crashed."
- **义项 2: 这么 (副词)** — To such a great degree
  - "The error message was so vague that nobody understood it."
- **义项 3: 如此 (副词)** — In such a way or manner
  - "The code was so well-written that no refactoring was needed."

---

### 46. still
- **义项 1: 仍然 (副词)** — Continuing up to the present
  - "The server is still down — the team is working on it."
- **义项 2: 还是 (副词)** — Despite what has happened
  - "He still decided to deploy even though the tests failed."
- **义项 3: 尽管如此 (副词)** — Nevertheless or all the same
  - "The bug is minor. Still, we should fix it before the release."

---

### 47. than
- **义项 1: 比 (连词)** — Used in comparisons
  - "The new server is faster than the old one."
- **义项 2: 比 (介词)** — Compared to
  - "More than 90% of the tests passed on the first run."
- **义项 3: 除了 (连词)** — Other than or except
  - "There is no solution other than rolling back the deployment."

---

### 48. then
- **义项 1: 然后 (副词)** — Next or after that
  - "First, complete the code review; then, deploy to staging."
- **义项 2: 那么 (副词)** — In that case or accordingly
  - "If the tests pass, then we can merge the PR."
- **义项 3: 当时 (副词)** — At that time
  - "I was a junior developer back then."

---

### 49. therefore
- **义项 1: 因此 (副词)** — For that reason
  - "The deployment failed; therefore, we triggered a rollback."
- **义项 2: 所以 (副词)** — As a logical consequence
  - "The database is corrupted; therefore, we need to restore from backup."
- **义项 3: 因而 (副词)** — Consequently or thus
  - "The system was unstable; therefore, we scheduled maintenance."

---

### 50. yet
- **义项 1: 还 (副词)** — Up to the present time (in negatives)
  - "The build has not finished yet."
- **义项 2: 然而 (连词)** — But or nevertheless
  - "The code looks simple, yet it is surprisingly hard to maintain."
- **义项 3: 更 (副词)** — Even (with comparatives)
  - "We need yet more test coverage to feel confident about the release."

---

## 3. Sentence-Making Practice

以下 10 个练习要求你结合本周学习的词汇和复杂句型造句。先自己写，再对照参考答案。每个答案都附有句法分析。

---

### 1. 你的同事在 code review 中问你：为什么这个函数现在返回不同的结果？你想解释是因为你在方法签名上加了 **参数**，并且**实现了**一个新的排序**算法**。

**要求:** 用 **because** 引导原因状语从句，句中包含定语从句。

**参考答案:** "The function returns different results now because I added a parameter that specifies the sorting algorithm."
> **句法分析:**
> - The function returns different results now (主句)
> - because I added a parameter (原因状语从句，连词 because 引导)
> - that specifies the sorting algorithm (定语从句，关系代词 that 指代 a parameter，在从句中作主语)
> - 关键连接词: because 连接"结果"和"原因"，that 连接"参数"和"它的功能"

---

### 2. 你在 postmortem 会议上解释线上事故。你说**部署**失败了，**但是**回滚成功了，**这意味着**没有用户受到影响。

**要求:** 用 **but** 连接两个并列分句，再用 **which** 引导非限制性定语从句指代前句内容。

**参考答案:** "The deployment failed, but the rollback succeeded, which meant that no users were affected by the incident."
> **句法分析:**
> - The deployment failed (分句1)
> - but the rollback succeeded (分句2，but 表转折)
> - , which meant that no users were affected (非限制性定语从句，which 指代前文整件事)
> - that no users were affected by the incident (宾语从句，作 meant 的宾语)
> - 关键: which 的"句指"用法 — 指代前面整句话，而不是某个名词

---

### 3. 你向新同事解释 CI 流程。你告诉他：**当**你推送到主分支时，CI 管道会**触发**一系列自动化测试，**这些测试**会**验证**每个**端点**。

**要求:** 用 **When** 引导时间状语从句，再用 **that** 引导定语从句修饰测试。

**参考答案:** "When you push to the main branch, the CI pipeline triggers a series of automated tests that validate every endpoint."
> **句法分析:**
> - When you push to the main branch (时间状语从句)
> - the CI pipeline triggers a series of automated tests (主句)
> - that validate every endpoint (定语从句，that 指代 tests)
> - 注意: 从句嵌套结构 — 时间状语从句 → 主句 → 定语从句

---

### 4. 你在设计评审会上发言：**虽然**这段代码看起来正确，**但是**初级开发者**引入**的 bug **导致**整个流水线失败。

**要求:** 用 **Although** 引导让步状语从句，句中包含 **that** 引导的定语从句。

**参考答案:** "Although the code looked correct, the bug that the junior developer introduced caused the entire pipeline to fail."
> **句法分析:**
> - Although the code looked correct (让步状语从句)
> - the bug (主句主语) — 被定语从句修饰
> - that the junior developer introduced (定语从句，that 指代 the bug)
> - caused the entire pipeline to fail (主句谓语 + 宾语 + 宾补)
> - 结构: causal → cause + O + to do (Pattern 5)

---

### 5. 你向产品经理汇报性能优化成果：我们**通过**实现一个**缓存**层来**让 API 更快**了，这个缓存层把频繁访问的**数据**存储在内存中。

**要求:** 使用 **by + 动名词** 表示方式，再用 **that** 引导定语从句。

**参考答案:** "We made the API faster by implementing a caching layer that stores frequently accessed data in memory."
> **句法分析:**
> - We made the API faster (主句，Pattern 5: S+V+O+C)
> - by implementing a caching layer (介词短语/方式状语，by + 动名词)
> - that stores frequently accessed data in memory (定语从句，修饰 caching layer)
> - 关键词法: made + O + adj = 使役结构

---

### 6. 你给新员工发邮件安排任务。你说：团队**把补丁发给我**之后，我会**把任务分配给你**。

**要求:** 使用 Pattern 4 (S+V+O+O) 结构，句中包含 **after** 引导的时间状语从句。

**参考答案:** "The team sent me the patch after I had completed the review, and I will assign you a new task tomorrow."
> **句法分析:**
> - The team sent me the patch (分句1，Pattern 4: S+V+O间+O直)
> - after I had completed the review (时间状语从句，after 引导)
> - and I will assign you a new task (分句2，Pattern 4)
> - 关键: Pattern 4 的"人→物"顺序 — sent me the patch、assign you a new task

---

### 7. 你在做技术选型时解释原因：我们对两个**框架**都做了评估，但**两者都不**适合我们的使用场景，**因为**它会导致高**延迟**。

**要求:** 使用 **neither** 作主语，用 **because** 解释原因。

**参考答案:** "We evaluated both frameworks, but neither met our requirements because they would introduce high latency."
> **句法分析:**
> - We evaluated both frameworks (独立分句1)
> - but (并列连词，表转折)
> - neither met our requirements (独立分句2，neither 作主语 = neither framework)
> - because they would introduce high latency (原因状语从句)
> - 语法点: neither 作主语时谓语用单数

---

### 8. 你在 code review 中写到：这段代码**虽然**没有语法错误，**但是**很难维护。你应该**把验证逻辑提取**成一个单独的**函数**。

**要求:** 使用 **although** 引导的让步句，第二句用 **should + V** 建议。

**参考答案:** "Although this code has no syntax errors, it is difficult to maintain. You should extract the validation logic into a separate function."
> **句法分析:**
> - Although this code has no syntax errors (让步状语从句)
> - it is difficult to maintain (主句，Pattern 3: S+V+C)
> - You should extract the validation logic (第二句的 Pattern 2: S+V+O)
> - into a separate function (介词短语/状语)
> - though 和 although 的区别: although 更正式，常用于句首

---

### 9. 你在回顾会议上说：**既然**我们已经完成了**迁移**，我们应该考虑如何进一步**迭代**这个系统。

**要求:** 使用 **Now that** 引导原因状语从句，主句用 **should** 提出建议。

**参考答案:** "Now that we have completed the migration, we should consider how to further iterate on the system."
> **句法分析:**
> - Now that we have completed the migration (原因状语从句，now that = "既然")
> - we should consider (主句)
> - how to further iterate on the system (宾语/疑问词+不定式，作 consider 的宾语)
> - 常见错误: ❌ "Now we have completed..." ✅ "Now that we have completed..."

---

### 10. 你在写 incident report: **当**数据库连接池超时的时候，服务器**崩溃了**，**这导致** API **响应**延迟飙升，**直到**运维团队重启了服务。

**要求:** 这是一个综合练习。用 **When** 引导时间状语从句，用 **which** 引导非限制性定语从句，用 **until** 引导时间状语从句。

**参考答案:** "When the database connection pool timed out, the server crashed, which caused the API response latency to spike until the operations team restarted the service."
> **句法分析:**
> - When the database connection pool timed out (时间状语从句1)
> - the server crashed (主句)
> - , which caused the API response latency to spike (非限制性定语从句，which 指代前句)
> - until the operations team restarted the service (时间状语从句2)
> - 三层嵌套: When → 主句 → which → until

---

## 4. Weekend Review

### 4.1 易混淆词对比

**1. deploy vs. rollback**
- "We **deploy** new features to production every Monday." (正向操作，发布新版本)
- "We had to **rollback** the deployment because of a critical bug." (逆向操作，回到旧版本)
- 关键区别：deploy 是"发布出去"，rollback 是"撤回来"。方向相反。

**2. implement vs. refactor**
- "I need to **implement** user authentication this sprint." (从无到有地创建新功能)
- "I need to **refactor** the legacy authentication module." (已有代码，优化内部结构)
- 关键区别：implement = 新建/实现，refactor = 优化/重构（不改变外部行为）。

**3. merge vs. clone**
- "Can you **merge** my PR after the review?" (把一个分支的变更合并到另一个分支)
- "**Clone** the repository before you start making changes." (从远程复制整个仓库到本地)
- 关键区别：merge = 合并变更，clone = 复制整个仓库。

**4. compile vs. execute**
- "The TypeScript compiler **compiles** .ts files into .js files." (源代码 → 机器码/字节码的转换)
- "The cron job **executes** a cleanup script every midnight." (运行程序/脚本)
- 关键区别：compile = 编译（代码转换），execute = 执行/运行（实际运行程序）。

**5. validate vs. debug**
- "Always **validate** user input before saving it to the database." (事前校验，预防问题)
- "I spent three hours **debugging** the memory leak." (事后排查，找出问题)
- 关键区别：validate = 事前防错，debug = 事后纠错。

---

### 4.2 自我检测清单

逐一检查，诚实地标记自己是否掌握：

**语法部分（复杂句拆解）：**
- [ ] 我能不看笔记说出 5 种基本句型吗？
- [ ] 我能区分限制性定语从句和非限制性定语从句吗？
- [ ] 我知道 which 可以指代"前面整句话"吗？
- [ ] 我能识别 because、although、when、after、before、until 引导的状语从句吗？
- [ ] 我看到一个 40 词以上的复杂句时，知道从哪儿开始拆解吗？
- [ ] 我知道 that 在定语从句中可以作主语也可以作宾语吗？

**语法部分（五大句型）：**
- [ ] 我能区分及物动词和不及物动词吗？
- [ ] 我知道 Pattern 4 (SVOO) 和 Pattern 5 (SVOC) 的本质区别吗？
- [ ] 我能在自己的句子中正确使用这些句型吗？

**词汇部分：**
- [ ] 我能为 Group 1 的 50 个开发动词中的每一个脱口而出一个例句吗？
- [ ] 我能为 Group 2 的 50 个开发名词正确匹配中文含义吗？
- [ ] 我能在日常对话中主动使用 Group 3 的日常动词吗？
- [ ] 我能在读技术文档时认出 Group 2 的词汇吗？
- [ ] 我知道 deploy/rollback、implement/refactor、validate/debug 的区别吗？

**应用部分：**
- [ ] 我能用本周学的复杂句型写一个技术邮件吗？
- [ ] 我能在写 commit message 时有意识地使用正确的句型吗？
- [ ] 我能在 code review 评论中使用定语从句让表达更精确吗？
- [ ] 我能在 standup 上说出包含状语从句的完整句子吗？

---

### 4.3 周末练习建议

**建议用时：** 周六 60 分钟 + 周日 60 分钟

**周六练习：句子拆解训练**
1. 从你最近看的一篇英文技术文章中，找出 5 个超过 15 个单词的长句。
2. 逐句分析：标注出主语、谓语、宾语、定语从句、状语从句。
3. 对照本文第 1.2 节的 6 个复杂句拆解格式，尝试用同样的格式写出每个句子的层级分析。
4. 特别关注：每个复合句的"连接点"——是什么词把两个从句连在一起的？是关系代词（that/which/who）、连词（because/although/when），还是并列连词（and/but）？

**周日练习：主动输出训练**
1. 用本周学的 300 个词汇自测：随机选 30 个词，说出一个包含该词的完整句子。
2. 写一段 5-8 句话的英文工作日志，描述你上周做了什么。要求至少包含 2 个定语从句和 2 个状语从句。
3. 用英语向自己解释一个技术概念（比如"什么是缓存"或"什么是CI/CD"），录音后回听，注意句式是否完整。
4. 下周一 standup 上，试着说至少一个含定语从句的句子（例如："The bug **that I fixed yesterday** was caused by a configuration error."）。

**长期建议：**
- 每天花 5 分钟拆解一个英文技术文章中的长句。坚持 4 周，阅读复杂句的能力会有质的飞跃。
- 用手机备忘录记录你遇到的"看不懂的长句"，每周日统一拆解。
- 不要怕句子长——记住：再长的句子，拆开都是一层层的"主 + 谓 + 宾"骨架。

---

> **下周预告：** Week 2 将学习**英语时态系统（Tenses）**——一般现在时、过去时、将来时、完成时的深入对比，以及如何在复杂句中使用正确的时态搭配。我们还会继续积累 300 个核心词汇。周末好好复习，下周见。
