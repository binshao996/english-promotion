# Week 01: 五大基本句型与核心开发动词

> 目标：彻底掌握英语五大基本句型，并学会 20 个最高频开发动词的用法。本周不追求华丽表达，只求每个句子都"结构正确、意思清楚"。

---

## 1. Grammar: 5 Basic English Sentence Patterns

英语句子看似千变万化，但拆开来看，其实只有五种骨架结构。记住这五种句型，你就有了搭建任何句子的"脚手架"。

---

### Pattern 1: S + V（主语 + 不及物动词）

**结构说明：** 主语 + 不及物动词。不及物动词的特点是"动作到此为止"，后面不需要接任何东西句子意思就完整了。常见的不及物动词：crash, work, run, fail, succeed, happen, sleep, wait 等。

**示例 1：** The server crashed.
**示例 2：** The deployment failed.
**示例 3：** Your code works.

**Syntax Breakdown：**

```
Example: The deployment failed.
- The (限定词) + deployment (主语/名词) + failed (谓语/不及物动词)
- 分析：主语是 "The deployment"（这次部署），谓语 "failed"（失败了）。不需要宾语，意思已经完整。
- 理解技巧：不及物动词就像"独角戏"——主语自己就能完成动作，不需要"接收者"。
- 常见错误：中国学生受中文影响，喜欢在不及物动词后面硬加宾语。记住：不及物动词后面绝对不能直接跟名词作宾语。
  ❌ "The deployment failed the process."
  ✅ "The deployment failed."（失败的是"部署"这件事本身，不需要加宾语）
  ✅ "The deployment failed **because** the process timed out."（加状语从句解释原因，不是在加宾语）
```

**更多实例：**
- "The system **runs**." 系统在运行。
- "The migration **completed** without errors." 迁移完成了，没有报错。
  ❌ 常见错误："The migration completed the task." — completed 在这里是不及物用法，"完成"本身；如果要表达"完成了某个任务"，才用及物：✅ "The migration **completed**." / "The migration **completed the data transfer**."
- "My laptop **died** during the meeting." 我开会时笔记本没电了。

---

### Pattern 2: S + V + O（主语 + 及物动词 + 宾语）

**结构说明：** 主语 + 及物动词 + 宾语。及物动词的动作用于"作用"在某个对象上，所以后面必须跟一个宾语，否则句子不完整。大部分英语动词都是及物动词。

**示例 1：** I wrote a script.
**示例 2：** We fixed the memory leak.
**示例 3：** She reviewed the pull request.

**Syntax Breakdown：**

```
Example: I wrote a script.
- I (主语/代词) + wrote (谓语/及物动词) + a script (宾语/名词短语)
- 分析：主语 "I" 发出 "wrote" 这个动作，动作作用在 "a script" 上。如果只说 "I wrote"，
  读者会问"你写了什么？"，所以及物动词必须有宾语。
- 理解技巧：及物动词就像"扔球"——你必须扔"某样东西"出去，动作才算完整。
- 常见错误：中国学生有时会遗漏及物动词的宾语，尤其是在回答问题时。
  ❌ "Did you fix the bug?" — "Yes, I fixed."
  ✅ "Yes, I fixed **it**." 或 "Yes, I fixed **the bug**."
```

**更多实例：**
- "The CI pipeline **failed the build**." CI 管道导致构建失败。（注意：这里 fail 是及物用法，意思是"使...失败"）
- "We **need more test coverage**." 我们需要更高的测试覆盖率。
- "I **reproduced the issue** in the staging environment." 我在 staging 环境复现了这个问题。

---

### Pattern 3: S + V + C（主语 + 系动词 + 主语补足语/表语）

**结构说明：** 主语 + 系动词 + 主语补足语（也叫表语）。系动词本身不表示具体动作，它像一个"等号"，把主语和它的描述连接起来。最常见的系动词是 **be**（am/is/are/was/were），还有 look, seem, become, feel, remain, appear, sound 等。

**示例 1：** The code is messy.
**示例 2：** The feature looks promising.
**示例 3：** This bug seems critical.

**Syntax Breakdown：**

```
Example: The code is messy.
- The code (主语/名词短语) + is (系动词) + messy (主语补足语/形容词)
- 分析：系动词 "is" 把主语 "The code" 和它的状态描述 "messy" 连接起来。说白了就是
  "code = messy" 这个等式。
- 理解技巧：把 "be" 动词想象成等号 "="。The code = messy。This language = hard。
  其他系动词（look, seem, become）则像是带修饰的等号。
- 常见错误：中国学生容易在形容词补足语前加多余的副词或冠词。
  ❌ "The code is messily."（messily 是副词，不能作补足语）
  ❌ "The code is a messy."（messy 是形容词，前面不需要冠词）
  ✅ "The code is messy."
```

**更多实例：**
- "The database **remains unstable**." 数据库仍然不稳定。
- "This approach **sounds reasonable**." 这个方法听起来合理。
- "He **became a senior engineer** last year."（注意：这里补足语是名词短语 a senior engineer，系动词+名词也是 Pattern 3）

---

### Pattern 4: S + V + O + O（主语 + 动词 + 间接宾语 + 直接宾语）

**结构说明：** 主语 + 动词 + 间接宾语（人）+ 直接宾语（物）。这种句型中，动词需要两个宾语才能表达完整的意思：一个是动作的"接收者"（间接宾语，通常是人），一个是动作的"内容"（直接宾语，通常是物）。常见的双宾语动词：send, give, tell, show, offer, assign, pass, write 等。

**示例 1：** She sent me the patch.
**示例 2：** I gave the team a demo.
**示例 3：** The lead assigned me a new task.

**Syntax Breakdown：**

```
Example: She sent me the patch.
- She (主语/代词) + sent (谓语/及物动词) + me (间接宾语/代词) + the patch (直接宾语/名词短语)
- 分析：主语 "She" 发出 "sent" 动作。"me" 是"收到补丁的人"（间接宾语），
  "the patch" 是"被发送的内容"（直接宾语）。关键：间接宾语在前，直接宾语在后。
- 理解技巧：记住"人→物"的顺序。She sent **me** + **the patch** = 她把补丁**给我**。
  如果要把物放前面，需要加介词：She sent the patch **to** me.
- 常见错误：中国学生经常弄混两个宾语的顺序，或者忘了加介词。
  ❌ "She sent the patch me."（物和人顺序反了）
  ✅ "She sent **me** the patch." 或 "She sent the patch **to me**."
```

**更多实例：**
- "The PM **showed us the roadmap**." 产品经理给我们看了路线图。
- "I'll **send you the meeting notes** after the call." 我会在会后把会议记录发给你。
- "Could you **pass me the deployment log**?" 你能把部署日志传给我吗？

---

### Pattern 5: S + V + O + C（主语 + 动词 + 宾语 + 宾语补足语）

**结构说明：** 主语 + 动词 + 宾语 + 宾语补足语。这个句型中，动词后的宾语+补足语之间存在"主谓关系"——补足语描述宾语的状态或性质。常见的此类动词：make, keep, find, consider, call, set, leave, turn 等。

**示例 1：** We made the API faster.
**示例 2：** I find this language confusing.
**示例 3：** They kept the server running overnight.

**Syntax Breakdown：**

```
Example: We made the API faster.
- We (主语/代词) + made (谓语/及物动词) + the API (宾语/名词短语) + faster (宾语补足语/形容词比较级)
- 分析：主语 "We" 发出 "made" 动作。"the API" 是动作的宾语。
  "faster" 是补足语，描述宾语变成的状态——"API 变得更快了"。
  宾语和补足语之间有隐含的主谓关系：the API (is) faster。
- 理解技巧：Pattern 4 vs Pattern 5 的区别——Pattern 4 的双宾语（人和物）之间没有主谓关系，
  Pattern 5 的宾语和补足语之间有主谓关系。试比较：
  Pattern 4: "She sent **me** **the patch**."（me ≠ the patch，没关系）
  Pattern 5: "We made **the API** **faster**."（the API is faster，有主谓关系）
- 常见错误：中国学生容易在补足语前多加一个 "to be"。
  ❌ "We made the API to be faster."
  ✅ "We made the API faster."（make + O + 形容词，直接跟形容词，不需要 to be）
```

**更多实例：**
- "I'll **keep you updated** on the progress." 我会让你随时了解进展。
- "We **found the root cause hard to identify**." 我们发现根本原因很难定位。
- "They **declared the incident resolved**." 他们宣布事故已解决。

---

### 快速对照表

| 模式 | 结构 | 示例 | 关键特征 |
|------|------|------|---------|
| P1: S+V | 主语 + 不及物动词 | The server crashed. | 动词后不加宾语 |
| P2: S+V+O | 主语 + 及物动词 + 宾语 | I wrote a script. | 必须有宾语 |
| P3: S+V+C | 主语 + 系动词 + 补足语 | The code is messy. | 系动词 = "等号" |
| P4: S+V+O+O | 主语 + 动词 + 间宾 + 直宾 | She sent me the patch. | "人→物"顺序 |
| P5: S+V+O+C | 主语 + 动词 + 宾语 + 补足语 | We made the API faster. | 宾语与补足语有主谓关系 |

---

## 2. Vocabulary: Top 20 Dev Verbs

以下 20 个动词是日常开发中使用频率最高的动词。每个动词我们学习三个常见的语境义项，全部使用你在工作中会遇到的真实句子。

---

### 1. deploy
- **义项 1: 部署 (v.)** — 将软件发布到服务器或运行环境
  - "We **deploy** new features to production every Monday."
- **义项 2: 安排/配置 (v.)** — 有策略地安排或分配资源
  - "The team **deployed** three engineers to handle the incident."
- **义项 3: 施展/运用 (v.)** — 有效地运用某能力或技术
  - "She **deployed** her deep knowledge of JavaScript to fix the performance bug."

---

### 2. implement
- **义项 1: 实现功能 (v.)** — 编写代码来实现某个功能或接口
  - "I need to **implement** the user authentication module this sprint."
- **义项 2: 执行方案 (v.)** — 将计划或决策付诸行动
  - "We decided to **implement** a rate-limiting policy for the public API."
- **义项 3: 实施工具/系统 (v.)** — 引入并启用某系统或工具
  - "The company **implemented** a new incident management system last quarter."
- **用法提示:**
  - implement 一般不再和 "functionality" 搭配，因为 implement 本身就隐含"实现功能"。
  - ❌ "We implemented the functionality of user login."
  - ✅ "We implemented user login."

---

### 3. execute
- **义项 1: 执行运行 (v.)** — 运行一段代码或一个命令
  - "The cron job **executes** a cleanup script every midnight."
- **义项 2: 执行计划 (v.)** — 按计划实施某操作
  - "We **executed** the migration plan without any downtime."
- **义项 3: 执行签合同 (v.)** — 在法律意义上签署或执行（较正式，DevOps 中较少用，但面试时可能出现）
  - "The contract was **executed** after both parties agreed on the SLA."
- **用法提示:** execute 比 run 更正式。日常口语说 "run the script"，正式文档写 "execute the script"。

---

### 4. configure
- **义项 1: 配置参数 (v.)** — 设置软件或系统的参数
  - "You need to **configure** the database connection string in the .env file."
- **义项 2: 组装组建 (v.)** — 以特定方式设置某系统
  - "We **configured** the load balancer to route 10% of traffic to the new version."
- **义项 3: 自定义调整 (v.)** — 按需求调整某工具的行为
  - "I **configured** my IDE to auto-format code on save."
- **用法提示:** configure 的介词搭配典型是 "configure A to do B" 或 "configure A for B"。

---

### 5. trigger
- **义项 1: 触发事件 (v.)** — 导致某个自动化过程开始
  - "Pushing to the main branch **triggers** a CI build automatically."
- **义项 2: 引发问题 (v.)** — 引起某个（通常不好的）状况
  - "The race condition **triggered** a cascade of service failures."
- **义项 3: 触发函数 (v.)** — 在编程中手动或自动调用某函数/流程
  - "The webhook **triggers** a serverless function to process the payment."

---

### 6. resolve
- **义项 1: 修复解决 (v.)** — 解决问题或错误
  - "The SRE team **resolved** the production incident in under 30 minutes."
- **义项 2: 解析地址 (v.)** — 将域名转换为 IP 地址
  - "DNS **resolved** the domain to the correct IP address."
- **义项 3: 决定 (v.)** — 下定决心或做决定（较正式，在技术决策中常见）
  - "We **resolved** to migrate from monolith to microservices by Q3."

---

### 7. debug
- **义项 1: 调试代码 (v.)** — 找出并修复代码中的错误
  - "I've been **debugging** this race condition for three hours."
- **义项 2: 排查问题 (v.)** — 在更宽泛的上下文中排除故障
  - "We need to **debug** why the production traffic is dropping."
- **义项 3: 仪表排查 (v.)** — 检查电子设备的故障
  - "The IoT device logs help us **debug** connectivity issues in the field."
- **用法提示:** debug 的时态变化是 debug → debugged → debugged。
  ❌ "I have debugged the bug."（debug 本身已经包含"找 bug"的意思，说"debug a bug" 是中文式重复）
  ✅ "I have debugged the issue."

---

### 8. fetch
- **义项 1: 获取数据 (v.)** — 从远程位置拉取或请求数据
  - "The frontend **fetches** user data from the API on page load."
- **义项 2: 拉取远程分支 (v.)** — Git 中从远程仓库拉取更新
  - "Make sure to **fetch** the latest changes before you rebase."
- **义项 3: 检索记录 (v.)** — 从数据库或存储中取出数据
  - "The query **fetches** all orders placed in the last 24 hours."
- **用法提示:** fetch 在 JavaScript 中是一个标准 API（fetch()），在 Git 中也是标准命令。名词含义是"取到的数据"。

---

### 9. render
- **义项 1: 渲染页面 (v.)** — 在浏览器或屏幕上绘制 UI
  - "React **renders** the component tree when the state changes."
- **义项 2: 生成输出 (v.)** — 将数据转换为人可读的格式
  - "The template engine **renders** the HTML from the markdown content."
- **义项 3: 提供交付 (v.)** — 提供服务或结果（较抽象含义）
  - "The GPU **renders** the 3D model in real time during the simulation."

---

### 10. parse
- **义项 1: 解析格式 (v.)** — 分析并理解结构化文本或代码
  - "The JSON parser **parses** the response body into a JavaScript object."
- **义项 2: 提取信息 (v.)** — 从复杂文本中提取有用的数据
  - "The script **parses** the server logs to extract error frequencies."
- **义项 3: 分析理解 (v.)** — 在非编程语境中，指深入分析某段信息
  - "It took me a while to **parse** what the reviewer meant in their comments."

---

### 11. validate
- **义项 1: 验证输入 (v.)** — 检查数据是否符合规定的格式或规则
  - "The form **validates** the email address before submitting the data."
- **义项 2: 确认有效性 (v.)** — 测试某事是否有效或正确
  - "We need to **validate** the hypothesis before building the full feature."
- **义项 3: 使生效 (v.)** — 在正式或法律意义上确认某事有效
  - "The security audit **validated** our compliance with PCI DSS standards."

---

### 12. merge
- **义项 1: 合并代码 (v.)** — 在版本控制中将一个分支合并到另一个分支
  - "Can you **merge** this pull request after the CI checks pass?"
- **义项 2: 合并数据 (v.)** — 将多个数据集整合在一起
  - "The function **merges** the user's local changes with the server state."
- **义项 3: 融合合并 (v.)** — 在更广泛的意义上结合两个事物
  - "This new role **merges** DevOps responsibilities with data engineering."

---

### 13. rollback
- **义项 1: 回滚代码 (v.)** — 将代码或版本恢复到之前的状态
  - "We had to **rollback** the deployment because the new version had a memory leak."
- **义项 2: 撤销操作 (v.)** — 取消或逆转某个操作
  - "The database transaction will **rollback** automatically if the script fails."
- **义项 3: 退回方案 (v.)** — 放弃当前策略，回到原先的方法
  - "After two weeks of trying the new framework, we **rolled back** to the previous stack."
- **用法提示:** rollback 既可以是动词，也可以是名词。作名词时："We performed a **rollback**."
  过去式是 rolled back（可分开写），不是 rollbacked。❌ rollbacked 不存在。

---

### 14. refactor
- **义项 1: 重构代码 (v.)** — 在不改变外部行为的前提下优化代码内部结构
  - "I spent the afternoon **refactoring** the legacy authentication module."
- **义项 2: 优化架构 (v.)** — 重新组织系统结构以提升可维护性
  - "We need to **refactor** this function — it's grown to over 500 lines."
- **义项 3: 重新设计 (v.)** — 广泛意义上重组任何流程或结构
  - "The team **refactored** their sprint process to include more pair programming."

---

### 15. deprecate
- **义项 1: 弃用 API (v.)** — 正式宣布某个功能不再推荐使用（但通常暂时保留）
  - "The team **deprecated** the v1 API in favor of the v2 endpoint."
- **义项 2: 淘汰方法 (v.)** — 宣布某个方法或做法不再被支持
  - "Python 3.8 has been **deprecated** and will no longer receive security updates."
- **义项 3: 反对批评 (v.)** — 在非技术语境中，表示强烈反对
  - "The security team **deprecated** the use of HTTP for internal services."
- **用法提示:** deprecate 和 delete 不同。deprecated 意味着"不再推荐但还在"；deleted 是"删了，用不了了"。

---

### 16. iterate
- **义项 1: 迭代开发 (v.)** — 以增量方式逐步改进产品
  - "We plan to launch a minimal version first and **iterate** based on user feedback."
- **义项 2: 循环遍历 (v.)** — 在编程中依次访问集合中的每个元素
  - "The function **iterates** over the array and checks each element."
- **义项 3: 重复过程 (v.)** — 重复某个过程以达到更好的结果
  - "We **iterated** on the design five times before the final version."
- **用法提示:** iterate over/through something 是正确搭配。❌ "iterate the array" ✅ "iterate **over** the array"

---

### 17. initialize
- **义项 1: 初始化对象 (v.)** — 创建一个对象或变量并赋予初始值
  - "The constructor **initializes** the database connection pool."
- **义项 2: 初始化项目 (v.)** — 设置一个新的项目或系统
  - "Run `npm init` to **initialize** a new Node.js project."
- **义项 3: 启动过程 (v.)** — 启动或准备某个流程
  - "The system **initializes** all services on startup, which takes about 30 seconds."

---

### 18. log
- **义项 1: 记录日志 (v.)** — 在程序运行过程中记录事件或信息
  - "The application **logs** every incoming request with a timestamp."
- **义项 2: 登录系统 (v.)** — 输入凭据以访问系统
  - "You need to **log** into the VPN before accessing internal resources."
- **义项 3: 记录工时 (v.)** — 在管理系统中记录工作时间
  - "Don't forget to **log** your hours in the time-tracking tool."
- **用法提示:** 区分 login（登录）和 log in（动词短语）。不可说 ❌ "log in the system"，应该说 ✅ "log in **to** the system"。

---

### 19. cache
- **义项 1: 缓存数据 (v.)** — 将数据临时存储以便快速访问
  - "The application **caches** the API response for 5 minutes to reduce latency."
- **义项 2: 存储在缓存 (v.)** — 将计算结果保存以减少重复计算
  - "We **cache** the rendered HTML so the server doesn't regenerate it on every request."
- **义项 3: 储存备用 (v.)** — 在更广泛的意义上，储备某物以备后用
  - "The CDN **caches** static assets across edge locations worldwide."

---

### 20. scale
- **义项 1: 水平扩展 (v.)** — 通过增加更多实例来提升系统能力
  - "The system automatically **scales** out during traffic spikes."
- **义项 2: 垂直扩容 (v.)** — 通过给现有机器增加更多资源来提升能力
  - "We had to **scale** up the database server when the data volume grew."
- **义项 3: 拓展业务 (v.)** — 扩大业务或团队的规模
  - "Our team **scaled** from 3 engineers to 15 in less than a year."
- **用法提示:** scale up（扩大）、scale down（缩小）、scale out（横向扩展）、scale in（缩减实例）。注意这几个短语动词的区别。

---

### 词汇速查表

| 编号 | 动词 | 中文核心意思 | 编程语境 |
|------|------|-------------|---------|
| 1 | deploy | 部署 | deploy to production |
| 2 | implement | 实现 | implement a feature |
| 3 | execute | 执行 | execute a script |
| 4 | configure | 配置 | configure the environment |
| 5 | trigger | 触发 | trigger a build |
| 6 | resolve | 解决/解析 | resolve a bug / resolve DNS |
| 7 | debug | 调试 | debug the issue |
| 8 | fetch | 获取 | fetch data from API |
| 9 | render | 渲染 | render the page |
| 10 | parse | 解析 | parse the JSON |
| 11 | validate | 验证 | validate user input |
| 12 | merge | 合并 | merge a PR |
| 13 | rollback | 回滚 | rollback a deployment |
| 14 | refactor | 重构 | refactor the codebase |
| 15 | deprecate | 弃用 | deprecate the old API |
| 16 | iterate | 迭代 | iterate over an array |
| 17 | initialize | 初始化 | initialize the project |
| 18 | log | 记录/登录 | log the error |
| 19 | cache | 缓存 | cache the response |
| 20 | scale | 扩展 | scale the service |

---

## 3. Sentence-Making Practice

以下 10 个练习模拟了你在工作中会遇到的实际场景。每个练习要求你用指定的句型和本周学过的动词造句。先自己写，再对照参考答案。

### 1. 你的 CI 管道刚刚在部署后失败了。用 Pattern 2 (SVO) 和动词 "trigger" 写一句解释发生了什么。
**参考答案:** "The failed deployment triggered an automatic rollback."
> (S + V + O: The failed deployment / triggered / an automatic rollback)

---

### 2. 你的同事问你为什么昨天没跟他 merge PR。用 Pattern 5 (SVOC) 和动词 "keep" 解释你当时在等他 review。
**参考答案:** "I kept the PR open waiting for your review."
> (S + V + O + C: I / kept / the PR / open — "open" 是宾语补足语，描述 PR 的状态)

---

### 3. 你在 standup 上说这次 sprint 你在做什么。用 Pattern 3 (SVC) 和动词 "refactor"（可以用现在进行时）描述你正在重构的模块。
**参考答案:** "The refactoring of the auth module is almost complete."
> 或者用现在进行时 + Pattern 2: "I am refactoring the auth module this sprint."
>
> Pattern 3 示例: "The current codebase is too messy to extend, so I am refactoring it."

---

### 4. 需要向一个新同事解释 DNS 的作用。用 Pattern 3 (SVC) 和动词 "resolve" 说明 DNS 做什么。
**参考答案:** "DNS resolves domain names into IP addresses."
> (S + V + O: DNS / resolves / domain names / into IP addresses — Pattern 2 结构)
>
> Pattern 3 例句: "DNS is essential for internet communication."

---

### 5. 产品经理给了你一个新需求，说用户觉得页面加载太慢。用 Pattern 5 (SVOC) 和动词 "render" 解释你们的优化措施。
**参考答案:** "We made the page render faster by lazy-loading images."
> (S + V + O + C: We / made / the page / render faster — 不定式短语 "render faster" 是宾语补足语)
>
> 简化版: "We made the page faster."

---

### 6. 你刚给团队成员分配了任务。用 Pattern 4 (SVOO) 和动词 "assign" 写这句话。
**参考答案:** "The tech lead assigned me the database migration task."
> (S + V + O + O: The tech lead / assigned / me / the database migration task)

---

### 7. 线上出了事故，你用 git 把版本恢复了。用 Pattern 1 (SV) 和动词 "rollback" 描述发生了什么。
**参考答案:** "The deployment rolled back automatically when the health check failed."
> (S + V: The deployment / rolled back — 这里 rollback 是不及物用法)

---

### 8. 你在 code review 中建议同事把一段逻辑抽取出来。用 Pattern 2 (SVO) 和动词 "refactor" 或 "extract" 写建议。
**参考答案:** "You should extract the validation logic into a separate helper function."
> (S + V + O: You / should extract / the validation logic — 情态动词 + 及物动词 + 宾语)

---

### 9. 架构师主张先做个 MVP 再迭代。用 Pattern 3 (SVC) 和动词 "iterate" 描述这个策略。
**参考答案:** "The best approach is to launch a minimal version first and then iterate based on feedback."
> (S + V + C: The best approach / is / to launch...and then iterate — 不定式短语作补足语)

---

### 10. 开发过程中发现旧 API 不再推荐使用。用 Pattern 2 (SVO) 和动词 "deprecate" 告诉团队应该怎么做。
**参考答案:** "We should deprecate the v1 API and migrate all clients to v2 by next quarter."
> (S + V + O: We / should deprecate / the v1 API)

---

### 练习覆盖检查

| 句型 | 题号 |
|------|------|
| Pattern 1: S+V | 7 |
| Pattern 2: S+V+O | 1, 8, 10 |
| Pattern 3: S+V+C | 3, 4, 9 |
| Pattern 4: S+V+O+O | 6 |
| Pattern 5: S+V+O+C | 2, 5 |

---

## 4. Weekend Review

### 易混淆动词对比

本周的 20 个动词中，有 5 组特别容易混淆。这里用对比句子帮你分清。

**1. implement vs. deploy**
- "We **implemented** the new caching logic."（我们写了代码，实现了功能）
- "We **deployed** the new caching logic to production."（我们把写好的代码发布上线了）
- 关键区别：implement = 编写实现，deploy = 部署上线。先 implement 再 deploy。

**2. merge vs. rollback**
- "Please **merge** my PR after review."（向前操作，把代码合进来）
- "We had to **rollback** the release."（向后操作，回退到之前的版本）
- 关键区别：merge 是"正向"，rollback 是"逆向"。

**3. fetch vs. parse**
- "The app **fetches** user data from the backend."（从外部拉取数据）
- "The app **parses** the JSON response into HTML."（把拉取到的数据拆解分析）
- 关键区别：fetch = 获取（网络/数据库），parse = 解析（格式/内容）。先 fetch 再 parse。

**4. validate vs. debug**
- "We **validate** the input before saving it to the database."（检查数据是否合规，预防性问题）
- "We **debug** the issue after the bug was reported."（检查代码为何出问题，事后排查）
- 关键区别：validate = 事前校验（防错），debug = 事后排查（纠错）。

**5. deprecate vs. delete**
- "The old endpoint is **deprecated** — it still works but will be removed next version."（弃用但还在）
- "We **deleted** the legacy code from the repository."（删了，没了）
- 关键区别：deprecated = 还能用但不推荐，delete = 彻底移除。

---

### 自我检测清单

逐一检查，诚实地标记自己是否掌握：

**语法部分：**
- [ ] 我能不看笔记说出 5 种基本句型吗？
- [ ] 我能区分及物动词和不及物动词吗？
- [ ] 我知道 Pattern 4 (SVOO) 和 Pattern 5 (SVOC) 的本质区别吗？
- [ ] 我能用中文解释每种句型的结构吗？

**词汇部分：**
- [ ] 我能为 20 个动词中的每一个脱口而出一个例句吗？
- [ ] 我知道 deploy/implement、merge/rollback、fetch/parse 的区别吗？
- [ ] 我能正确使用 "trigger" 和 "resolve" 造句吗？
- [ ] 我知道 rollback 的过去式不是 "rollbacked" 吗？

**应用部分：**
- [ ] 我能用本周学过的句型来写一个简短的 standup update 吗？
- [ ] 写一个简单的 commit message 时，我知道用什么句型最合适吗？

---

### 周末练习建议

**建议用时：** 周六 45 分钟 + 周日 45 分钟

**周六练习：** 打开你最近写的代码仓库，找 10 条你写过的 commit message。逐条分析它们属于哪种句型。然后试着用本周学的 5 种句型改写它们。你可能会发现大多数 commit message 都在用 S+V+O（Pattern 2），用 S+V+C（Pattern 3）会让你的表达更丰富。

**周日练习：** 在下周一之前，试着在以下场合有意识使用本周学过的内容：
- Standup meeting 上，试着用英语说 "I implemented X"、"I'm debugging Y"、"The build failed because Z triggered an error"
- Code review 时，写评论时注意句型完整
- 看一篇英文技术文章，标出你遇到的 5 个 new sentences，分析它们的句型

**关于时态的快速提醒：** 本周我们专注于"句型结构"，暂时没有涉及时态。下周我们会深入时态。但如果你写句子时不确定时态，记住一个安全规则：**描述一般事实、日常操作、计划表上的事 → 用一般现在时（deploy, implements, triggers）；描述过去已完成的事 → 用一般过去时（deployed, implemented, triggered）**。先保证结构正确，再追求时态精确。慢慢来，比较快。

---

> **下周预告：** Week 2 将学习**英语时态（Tenses）**——特别是过去时、完成时和将来时的用法。我们还会学习另一个高频动词集。周末好好复习，下周见。
