# Week 03: 一般过去时 & 过去进行时 + 复杂句拆解 + 300 词汇

> 目标：巩固一般过去时和过去进行时，并学会 **300** 个高频生活与工作词汇。本周重点是从"简单句"走向"复杂句"——学会逐词拆解包含多从句的复杂句子，为阅读英文技术文档和撰写详细报告打下基础。

---

## 1. Grammar: Simple Past & Past Continuous

---

### Part A: Simple Past — 快速参考

**结构：** 主语 + 动词过去式

**核心用法：** 描述"在过去某个时间已经完成的事情"——动作已结束，和现在没有必然联系。

**规则动词 -ed 发音：**

| 发音 | 条件 | 示例 |
|------|------|------|
| /t/ | 动词以清辅音结尾 (p, k, f, s, sh, ch, x) | fixed /fɪkst/, pushed /pʊʃt/ |
| /d/ | 动词以浊辅音或元音结尾 (b, g, l, m, n, r, v, z) | deployed /dɪˈplɔɪd/, called /kɔːld/ |
| /ɪd/ | 动词以 /t/ 或 /d/ 结尾 | tested /ˈtestɪd/, needed /ˈniːdɪd/ |

**常见不规则动词（前 25 高频）：**

| 原形 | 过去式 | 过去分词 | 原形 | 过去式 | 过去分词 |
|------|--------|----------|------|--------|----------|
| write | wrote | written | build | built | built |
| send | sent | sent | make | made | made |
| run | ran | run | take | took | taken |
| see | saw | seen | give | gave | given |
| find | found | found | break | broke | broken |
| keep | kept | kept | bring | brought | brought |
| think | thought | thought | tell | told | told |
| speak | spoke | spoken | leave | left | left |
| lose | lost | lost | spend | spent | spent |
| lead | led | led | set | set | set |
| let | let | let | cut | cut | cut |
| read | read /red/ | read /red/ | go | went | gone |
| get | got | gotten | — | — | — |

**否定：** didn't + **动词原形**（一句话只需要一个过去标记）
- ❌ "I didn't **saw** the error." → ✅ "I didn't **see** the error."

**疑问：** Did + 主语 + **动词原形** ?
- "**Did** you **deploy** yesterday?" / "Why **did** the build **fail**?"

---

### Part B: Past Continuous — 快速参考

**结构：** was/were + V-ing

**核心用法：**
1. **过去某时刻正在进行的动作** — "I **was debugging** at 3 AM."
2. **两个同时进行的动作** — "While I **was checking** logs, she **was restarting** the server."
3. **被另一个动作打断** — "I **was reviewing** the PR when the incident **happened**."

**否定：** was/were + not + V-ing（wasn't / weren't）
**疑问：** Was/Were + 主语 + V-ing ?

**关键对比：**
- Simple Past = 完整发生的动作（结果）— "I **deployed** the fix."
- Past Continuous = 正在进行的过程（背景）— "I **was deploying** the fix when the server crashed."

---

### Part C: Complex Sentence Breakdowns（复杂句拆解）

本周核心。通过逐词拆解理解包含多从句的复杂句子。每个句子我们标注每个成分的语法功能。

---

#### Sentence 1

**原文：** I was reviewing the pull request when I noticed that someone had removed the validation logic that we had specifically added to prevent SQL injection attacks.

```
逐词拆解：
- I (主语/代词)
- was reviewing (谓语/过去进行时 — 长动作背景)
- the pull request (宾语/名词短语)
- when (连词 — 引导时间状语从句)
- I (主语/代词)
- noticed (谓语/一般过去时 — 短动作中断)
- that (连词 — 引导宾语从句)
- someone (主语/不定代词)
- had removed (谓语/过去完成时 — 动作发生在 noticed 之前)
- the validation logic (宾语/名词短语)
- that (关系代词 — 引导定语从句，修饰 validation logic)
- we (主语/代词)
- had specifically added (谓语/过去完成时 — 发生在 removed 之前)
- to prevent (目的状语/不定式短语)
- SQL injection attacks (宾语/名词短语)
```

**中文翻译：** 我正在审查 pull request，突然注意到有人删除了我们特意添加的用于防止 SQL 注入攻击的验证逻辑。

**结构总结：** 过去进行时（背景）+ when + 一般过去时（中断）+ that 宾语从句（内含过去完成时 + that 定语从句）

---

#### Sentence 2

**原文：** The incident had already escalated to the VP of Engineering by the time we realized that the root cause was a misconfigured load balancer that had been deployed the previous night.

```
逐词拆解：
- The incident (主语/名词短语)
- had already escalated (谓语/过去完成时 — 在 realized 之前已发生)
- to the VP of Engineering (介词短语/宾语)
- by the time (连词短语 — 引导时间状语从句)
- we (主语/代词)
- realized (谓语/一般过去时)
- that (连词 — 引导宾语从句)
- the root cause (主语/名词短语)
- was (系动词/一般过去时)
- a misconfigured load balancer (主语补足语/名词短语)
- that (关系代词 — 引导定语从句)
- had been deployed (谓语/过去完成时被动语态)
- the previous night (时间状语/名词短语)
```

**中文翻译：** 当我们意识到根本原因是一个前一晚部署的配置错误的负载均衡器时，事件已经升级到了工程副总裁。

**结构总结：** 主句（过去完成时）+ by the time 时间状语从句 + that 宾语从句 + that 定语从句（过去完成时被动）

---

#### Sentence 3

**原文：** While the SRE team was investigating the outage, the product manager kept the stakeholders updated through the status page and the engineering director coordinated the incident response.

```
逐词拆解：
- While (连词 — 引导时间状语从句)
- the SRE team (主语/名词短语)
- was investigating (谓语/过去进行时)
- the outage (宾语/名词短语)
- the product manager (主语/名词短语 — 第一个并列主句主语)
- kept (谓语/一般过去时)
- the stakeholders (宾语/名词短语)
- updated (宾语补足语/形容词 — keep + O + C 结构)
- through the status page (方式状语/介词短语)
- and (连词 — 连接两个并列主句)
- the engineering director (主语/名词短语 — 第二个并列主句主语)
- coordinated (谓语/一般过去时)
- the incident response (宾语/名词短语)
```

**中文翻译：** 在 SRE 团队调查故障期间，产品经理通过状态页面让干系人了解最新情况，同时工程总监协调了事故响应。

**结构总结：** While 时间状语从句（过去进行时）+ 并列主句（S+V+O+C + and + S+V+O，均用一般过去时）

---

#### Sentence 4

**原文：** We had been planning to deploy on Friday, but the consensus among the senior engineers was that we should wait until Monday because the test coverage was insufficient.

```
逐词拆解：
- We (主语/代词)
- had been planning (谓语/过去完成进行时 — 强调一直计划到某个时间点)
- to deploy (不定式短语/宾语)
- on Friday (时间状语/介词短语)
- but (连词 — 表转折)
- the consensus (主语/名词短语)
- among the senior engineers (定语/介词短语 — 修饰 consensus)
- was (系动词/一般过去时)
- that (连词 — 引导表语从句)
- we (主语/代词)
- should wait (谓语/情态动词 + 动词原形)
- until Monday (时间状语/介词短语)
- because (连词 — 引导原因状语从句)
- the test coverage (主语/名词短语)
- was insufficient (系动词 + 形容词补足语)
```

**中文翻译：** 我们一直计划周五部署，但资深工程师们的共识是我们应该等到周一，因为测试覆盖率不足。

**结构总结：** 主句（过去完成进行时）+ but 转折 + 主句（SVC）+ that 表语从句（内含 because 原因状语从句）

---

#### Sentence 5

**原文：** The team brainstormed several approaches before we finally aligned on a solution that balanced performance with maintainability and that could be implemented within the sprint.

```
逐词拆解：
- The team (主语/名词短语)
- brainstormed (谓语/一般过去时)
- several approaches (宾语/名词短语)
- before (连词 — 引导时间状语从句)
- we (主语/代词)
- finally (状语/副词)
- aligned (谓语/一般过去时)
- on a solution (介词短语/补足部分)
- that (关系代词 — 引导第一个定语从句，修饰 solution)
- balanced (谓语/一般过去时)
- performance (宾语/名词短语)
- with maintainability (介词短语/状语)
- and (连词 — 连接两个并列定语从句)
- that (关系代词 — 引导第二个定语从句，同样修饰 solution)
- could be implemented (谓语/情态动词被动语态)
- within the sprint (时间状语/介词短语)
```

**中文翻译：** 团队集思广益了几种方案，最后我们就一个在性能与可维护性之间取得平衡且能在 sprint 内实施的方案达成了一致。

**结构总结：** 主句（一般过去时）+ before 时间状语从句 + 两个并列 that 定语从句修饰同一个名词

---

#### Sentence 6

**原文：** After we rolled back the faulty deployment, the on-call engineer spent the entire night tracing the bug to a race condition that only manifested under heavy load.

```
逐词拆解：
- After (连词 — 引导时间状语从句)
- we (主语/代词)
- rolled back (谓语/一般过去时 — 短语动词)
- the faulty deployment (宾语/名词短语)
- the on-call engineer (主语/名词短语)
- spent (谓语/一般过去时)
- the entire night (宾语/名词短语 — 表时间)
- tracing (现在分词/宾语补足语 — spend + 时间 + V-ing 结构)
- the bug (宾语/tracing 的宾语)
- to a race condition (介词短语/状语)
- that (关系代词 — 引导定语从句)
- only (状语/副词)
- manifested (谓语/一般过去时)
- under heavy load (状语/介词短语)
```

**中文翻译：** 在我们回滚了有问题的部署之后，值班工程师花了整个晚上追踪 bug，最终定位到只在重负载下才会出现的竞态条件。

**结构总结：** After 时间状语从句（一般过去时）+ 主句（spend + 时间 + V-ing 结构）+ that 定语从句

---

## 2. Vocabulary: 300 Words（6 Groups × 50 Words）

本周词汇分成 6 组，每组 50 个，涵盖架构设计决策、系统行为操作、精准与微调形容词、情绪态度表达、谈判风险与决策名词、变化成长与进展表达六大领域。所有词汇均为 B2-C1 级别——学习者阅读时能识别，但主动输出时很少使用。

---

### Group 1: Architecture, Design & Decision Verbs（架构设计与决策动词）

---

### 1. architect
- **义项 1: 设计架构 (v.)** — 从全局角度设计系统或方案的结构
  - "We need to **architect** the system to handle millions of concurrent users."
- **义项 2: 规划构建 (v.)** — 精心策划某事物的结构
  - "She **architected** a complete restructuring of the data pipeline."
- **义项 3: 主导设计 (v.)** — 在高层面上主导某事物的设计
  - "He **architected** the migration from monolith to microservices."

### 2. devise
- **义项 1: 设计发明 (v.)** — 经过思考设计出新的方案或方法
  - "The team **devised** a creative solution to the caching problem."
- **义项 2: 策划 (v.)** — 制定详细的计划
  - "We **devised** a rollback strategy in case the deployment went wrong."
- **义项 3: 想出 (v.)** — 凭智力想出
  - "She **devised** an elegant algorithm that reduced processing time by half."

### 3. conceive
- **义项 1: 构想 (v.)** — 在脑中形成想法或概念
  - "The product was first **conceived** during a hackathon in 2019."
- **义项 2: 设想 (v.)** — 想象某事可能或应该怎样
  - "I cannot **conceive** of a scenario where this design would fail."
- **义项 3: 孕育 (v.)** — 开始形成某个计划
  - "The architecture was **conceived** as a distributed system from day one."

### 4. formulate
- **义项 1: 制定 (v.)** — 系统性地制定计划或策略
  - "We **formulated** a comprehensive incident response plan."
- **义项 2: 表述 (v.)** — 清晰地表达想法或观点
  - "She **formulated** her concerns in a way the stakeholders could understand."
- **义项 3: 规划 (v.)** — 系统化地设计算法或方法
  - "The team **formulated** a new approach to database sharding."

### 5. draft
- **义项 1: 起草 (v.)** — 写出初稿或初步版本
  - "I **drafted** the architecture decision record for the team to review."
- **义项 2: 拟定 (v.)** — 初步设计或制定
  - "We **drafted** a timeline for the Q3 release before the planning meeting."
- **义项 3: 征召 (v.)** — 从某处调动人员
  - "The team **drafted** two engineers from the platform team to help with the migration."

### 6. outline
- **义项 1: 概述 (v.)** — 简要描述主要要点
  - "The tech lead **outlined** the key milestones for the project."
- **义项 2: 勾勒 (v.)** — 画出或描述某事物的大致形状
  - "She **outlined** the system architecture on the whiteboard during the meeting."
- **义项 3: 规划纲要 (v.)** — 给出计划或建议的纲要
  - "The document **outlines** the steps required for the migration."

### 7. sketch
- **义项 1: 草绘 (v.)** — 快速粗略地画出或描述
  - "I **sketched** a rough diagram of the new data flow on a napkin."
- **义项 2: 概述 (v.)** — 简要描述某事物的大致情况
  - "The proposal **sketches** out a high-level plan for the redesign."
- **义项 3: 勾勒轮廓 (v.)** — 画出或描述某事物的轮廓
  - "She **sketched** the user interface layout before writing any code."

### 8. prototype
- **义项 1: 制作原型 (v.)** — 快速制作初步模型以验证想法
  - "We **prototyped** the new feature in two days to test its feasibility."
- **义项 2: 原型 (n.)** — 用作测试的初步版本
  - "The **prototype** demonstrated that the concept was viable."
- **义项 3: 建模 (v.)** — 用原型工具构建交互式模型
  - "The designer **prototyped** the user flow in Figma before development."

### 9. mock-up
- **义项 1: 制作视觉模型 (v.)** — 制作静态设计稿供评审
  - "The designer **mocked up** several variations of the landing page."
- **义项 2: 模拟 (v.)** — 创建视觉替代品以测试外观
  - "We **mocked up** the dashboard to get early stakeholder feedback."
- **义项 3: 搭建模型 (n.)** — 用于演示或测试的实体或数字模型
  - "The **mock-up** helped the team visualize the final product before coding."

### 10. blueprint
- **义项 1: 设计蓝图 (v.)** — 制定详细的行动计划
  - "We **blueprinted** the entire deployment pipeline before writing a single line of code."
- **义项 2: 规划纲领 (n.)** — 详细的计划或指南
  - "The architecture **blueprint** served as the reference for all development teams."
- **义项 3: 设计图 (n.)** — 技术层面的设计图
  - "The system **blueprint** showed every service and its dependencies."

### 11. scaffold
- **义项 1: 搭建脚手架 (v.)** — 创建项目的基本框架或结构
  - "The CLI tool **scaffolds** a new project with all the boilerplate code."
- **义项 2: 搭建骨架 (v.)** — 为系统搭建基础结构
  - "We **scaffolded** the microservice skeleton before implementing business logic."
- **义项 3: 提供支撑 (v.)** — 为学习或开发提供临时的支持结构
  - "The tutorial **scaffolds** the learning process by providing starter code."

### 12. structure
- **义项 1: 组织构造 (v.)** — 以特定方式安排组织某事物
  - "We need to **structure** the codebase so that each module has a clear responsibility."
- **义项 2: 构建 (v.)** — 使某物有结构或条理
  - "The document is **structured** into three main sections."
- **义项 3: 框架 (n.)** — 组织的方式或体系
  - "The team agreed on a folder **structure** for the new project."

### 13. compose
- **义项 1: 构成组成 (v.)** — 某物的组成部分
  - "The system is **composed** of several loosely coupled microservices."
- **义项 2: 编写创作 (v.)** — 写作或创作
  - "She **composed** a detailed incident report after the outage."
- **义项 3: 组合 (v.)** — 将多个元素组合在一起
  - "In React, you **compose** complex UIs from smaller components."

### 14. assemble
- **义项 1: 组装 (v.)** — 将部件组合在一起形成整体
  - "The build pipeline **assembles** all modules into a single deployable artifact."
- **义项 2: 集合召集 (v.)** — 聚集人员或东西到一处
  - "The project manager **assembled** a cross-functional team for the initiative."
- **义项 3: 汇编 (v.)** — 将数据或代码收集汇总
  - "The script **assembles** logs from multiple sources into a unified format."

### 15. integrate
- **义项 1: 集成整合 (v.)** — 将不同部分组合成统一的系统
  - "We need to **integrate** the new payment gateway before the end of the sprint."
- **义项 2: 融入 (v.)** — 使某人或某物融入更大的整体
  - "The new hire **integrated** into the team much faster than expected."
- **义项 3: 合并数据 (v.)** — 将数据从多个来源合并
  - "The API **integrates** data from three different backend services."

### 16. federate
- **义项 1: 联邦化 (v.)** — 将独立系统联合成一个统一的整体
  - "We **federated** the identity systems so users could log in across all services."
- **义项 2: 联合 (v.)** — 多个自治实体形成联盟
  - "The two departments **federated** their data under a single governance model."
- **义项 3: 分布式协作 (v.)** — 在不失自治权的情况下进行协作
  - "The federated architecture allows each team to own its services while sharing a common API gateway."

### 17. consolidate
- **义项 1: 合并整合 (v.)** — 将多个事物合并为一个整体
  - "We **consolidated** three legacy databases into a single data warehouse."
- **义项 2: 巩固加强 (v.)** — 使某事物更稳固
  - "The company **consolidated** its position in the market after the acquisition."
- **义项 3: 汇总 (v.)** — 将信息或数据汇总在一起
  - "The report **consolidates** feedback from all the stakeholders."

### 18. unify
- **义项 1: 统一 (v.)** — 使多个部分成为一个整体
  - "The new design system **unifies** the visual language across all products."
- **义项 2: 使一致 (v.)** — 使不同群体或系统达成一致
  - "The framework **unifies** the development experience across web and mobile."
- **义项 3: 联合 (v.)** — 将分散的事物联合起来
  - "The API gateway **unifies** access to all backend services."

### 19. merge
- **义项 1: 合并代码 (v.)** — 将不同分支的代码合并
  - "Please **merge** your feature branch into main after the review is approved."
- **义项 2: 合并公司 (v.)** — 两家公司合并为一体
  - "The two startups **merged** to form a single company."
- **义项 3: 融合 (v.)** — 不同事物融合在一起
  - "The design **merges** traditional aesthetics with modern functionality."

### 20. diverge
- **义项 1: 分叉偏离 (v.)** — 向不同方向发展
  - "The two codebases **diverged** after the team split into separate product groups."
- **义项 2: 意见分歧 (v.)** — 观点或意见不同
  - "The architects' opinions **diverged** on whether to use event sourcing."
- **义项 3: 偏离标准 (v.)** — 偏离标准或预期路径
  - "The implementation **diverged** from the original specification."

### 21. branch
- **义项 1: 分支 (v.)** — 从主线分出独立的开发线
  - "We **branched** off from the main codebase to experiment with a new approach."
- **义项 2: 分岔 (v.)** — 道路或路径分岔
  - "The discussion **branched** into several tangential topics."
- **义项 3: 分支结构 (n.)** — 树形结构中的分支
  - "The decision tree has three main **branches** representing different outcomes."

### 22. fork
- **义项 1: 复刻 (v.)** — 复制代码仓库以独立开发
  - "We **forked** the open-source library to add custom features."
- **义项 2: 分岔 (v.)** — 系统或进程分裂为两个方向
  - "The project **forked** into two competing versions after the disagreement."
- **义项 3: 分歧点 (n.)** — 需要做关键决定的时刻
  - "The team reached a **fork** in the road — either rewrite or migrate."

### 23. split
- **义项 1: 拆分 (v.)** — 将一个大整体分成小部分
  - "We **split** the monolithic application into several microservices."
- **义项 2: 分担 (v.)** — 将工作或责任分开
  - "The team **split** the workload evenly among the members."
- **义项 3: 分裂 (v.)** — 团体或组织分裂
  - "The team **split** into two groups after disagreeing on the architecture."

### 24. fragment
- **义项 1: 碎片化 (v.)** — 使某物破碎成小块
  - "The hard drive was **fragmented**, causing slow read performance."
- **义项 2: 分割 (v.)** — 将数据或文件分成片段
  - "Large files are **fragmented** into smaller chunks for transmission."
- **义项 3: 碎片 (n.)** — 破碎或分散的小部分
  - "Only a **fragment** of the log file was recoverable after the crash."

### 25. partition
- **义项 1: 分区 (v.)** — 将磁盘或数据库分成独立区域
  - "We **partitioned** the database table by date to improve query performance."
- **义项 2: 分割 (v.)** — 将空间或系统分成独立部分
  - "The network was **partitioned** into separate security zones."
- **义项 3: 划分 (n.)** — 分隔的行为或结果
  - "The **partition** of responsibilities between teams was clearly documented."

### 26. segment
- **义项 1: 细分 (v.)** — 将市场或用户分成细分群体
  - "We **segmented** users based on their usage patterns."
- **义项 2: 分割 (v.)** — 将数据或内容分成片段
  - "The video is **segmented** into five-minute chunks for streaming."
- **义项 3: 划分 (n.)** — 被分割的一部分
  - "Each market **segment** has different requirements for the product."

### 27. layer
- **义项 1: 分层 (v.)** — 按层次组织结构
  - "The application is **layered** into presentation, business, and data tiers."
- **义项 2: 叠加 (v.)** — 将多层事物叠在一起
  - "We **layered** caching strategies at multiple levels of the system."
- **义项 3: 层次 (n.)** — 系统或结构中的一层
  - "Each **layer** in the architecture has a well-defined responsibility."

### 28. tier
- **义项 1: 分层 (v.)** — 按等级或层级组织
  - "The infrastructure is **tiered** into development, staging, and production."
- **义项 2: 等级 (n.)** — 层级或等级系统中的一层
  - "The application follows a three-**tier** architecture."
- **义项 3: 层级 (n.)** — 服务或定价的级别
  - "Enterprise customers are on the premium **tier** with dedicated support."

### 29. stack
- **义项 1: 技术栈 (n.)** — 一组协同工作的技术
  - "Our **stack** includes React, Node.js, and PostgreSQL."
- **义项 2: 堆叠 (v.)** — 将多个事物堆叠起来
  - "The interrupts **stack** up if the handler cannot process them fast enough."
- **义项 3: 堆栈 (n.)** — 计算中的 LIFO 数据结构
  - "The call **stack** shows the sequence of function invocations."

### 30. pipeline
- **义项 1: 流水线 (n.)** — 自动化的处理流程
  - "The CI/CD **pipeline** runs tests and deploys the code automatically."
- **义项 2: 管道 (n.)** — 数据或任务的处理通道
  - "The data **pipeline** processes millions of events every minute."
- **义项 3: 输送渠道 (n.)** — 人才或项目的输送路径
  - "The internship program serves as a **pipeline** for new engineering talent."

### 31. chain
- **义项 1: 链式 (v.)** — 将多个步骤连接成序列
  - "We **chained** together several processing stages in the data pipeline."
- **义项 2: 链 (n.)** — 一系列连接的事件或事物
  - "The **chain** of events leading to the outage was documented in the postmortem."
- **义项 3: 方法链 (v.)** — 编程中将多个方法连续调用
  - "The query builder allows you to **chain** methods for readability."

### 32. flow
- **义项 1: 流程 (n.)** — 工作或数据经过的路径
  - "The data **flow** diagram shows how information moves through the system."
- **义项 2: 流动 (v.)** — 连续平稳地移动
  - "User requests **flow** through the load balancer to the application servers."
- **义项 3: 流程设计 (v.)** — 设计某过程如何运作
  - "We need to **flow** the approval process through the appropriate channels."

### 33. route
- **义项 1: 路由 (v.)** — 按特定路径发送数据或请求
  - "The API gateway **routes** requests to the appropriate backend service."
- **义项 2: 路径 (n.)** — 数据或请求经过的路径
  - "The **route** from the client to the server goes through three proxies."
- **义项 3: 路线规划 (v.)** — 规划交通或通信的路径
  - "We **routed** all traffic through the CDN during the DDoS attack."

### 34. dispatch
- **义项 1: 分派 (v.)** — 发送或分配资源到指定地点
  - "The incident response system **dispatched** the on-call engineer immediately."
- **义项 2: 调度 (v.)** — 将任务分配给适当的人或系统
  - "The scheduler **dispatches** jobs to available worker nodes."
- **义项 3: 迅速处理 (v.)** — 快速完成或处理某事
  - "The team **dispatched** the critical bug fix within an hour."

### 35. relay
- **义项 1: 传递 (v.)** — 将信息从一个地方传到另一个
  - "Could you **relay** the incident details to the security team?"
- **义项 2: 中继 (v.)** — 接收并转发信号或数据
  - "The message broker **relays** events from producers to consumers."
- **义项 3: 传达 (v.)** — 将某人的话转达给另一个人
  - "She **relayed** the client's feedback to the development team."

### 36. broker
- **义项 1: 中介协调 (v.)** — 作为中间人促成协议
  - "The product manager **brokered** a compromise between the design and engineering teams."
- **义项 2: 消息代理 (n.)** — 负责消息传递的中间件
  - "Kafka serves as a message **broker** between microservices."
- **义项 3: 促成 (v.)** — 通过协商达成协议
  - "The senior engineer **brokered** a deal between the two conflicting teams."

### 37. mediate
- **义项 1: 调解 (v.)** — 在双方之间协调解决分歧
  - "The tech lead **mediated** the disagreement between the frontend and backend teams."
- **义项 2: 中介传递 (v.)** — 通过中间媒介传递
  - "The API gateway **mediates** all communication between the client and services."
- **义项 3: 间接作用 (v.)** — 通过中间环节产生影响
  - "The effect of the change was **mediated** by the caching layer."

### 38. negotiate
- **义项 1: 谈判 (v.)** — 通过讨论达成协议
  - "We **negotiated** the SLA terms with the cloud provider for better uptime guarantees."
- **义项 2: 协商 (v.)** — 商议解决分歧
  - "The team **negotiated** a trade-off between delivery speed and code quality."
- **义项 3: 巧妙处理 (v.)** — 成功地应付困难情况
  - "She **negotiated** the complex approval process to get the budget approved."

### 39. coordinate
- **义项 1: 协调 (v.)** — 安排各部门协同工作
  - "The release manager **coordinated** the deployment across five teams."
- **义项 2: 配合 (v.)** — 使各方的行动保持同步
  - "We need to **coordinate** the database migration with the application deployment."
- **义项 3: 调整 (v.)** — 使各部分协调一致
  - "The design and engineering teams **coordinated** their timelines for the launch."

### 40. synchronize
- **义项 1: 同步 (v.)** — 使多个系统或设备数据一致
  - "The mobile app **synchronizes** with the server every time the user goes online."
- **义项 2: 协调时间 (v.)** — 使时钟或时间保持一致
  - "All servers **synchronize** their clocks using NTP."
- **义项 3: 协调行动 (v.)** — 使行动在时间上协调一致
  - "The teams **synchronized** their release schedules to avoid conflicts."

### 41. sequence
- **义项 1: 排序 (v.)** — 按特定顺序排列
  - "We need to **sequence** the deployment steps carefully to avoid downtime."
- **义项 2: 序列 (n.)** — 一连串有序的事件或步骤
  - "The **sequence** of operations must be followed exactly."
- **义项 3: 编排 (v.)** — 确定事件发生的顺序
  - "The algorithm **sequences** the tasks based on their dependencies."

### 42. schedule
- **义项 1: 安排时间 (v.)** — 为某事设定预定时间
  - "We **scheduled** the database migration for 2 AM on Sunday."
- **义项 2: 排程 (v.)** — 将任务排入时间表
  - "The system **schedules** background jobs based on available resources."
- **义项 3: 时间表 (n.)** — 活动的预定时间计划
  - "The release **schedule** depends on the completion of testing."

### 43. orchestrate
- **义项 1: 编排协调 (v.)** — 协调多个服务或系统的工作
  - "Kubernetes **orchestrates** the deployment and scaling of containers."
- **义项 2: 精心策划 (v.)** — 精心安排复杂事件
  - "The product manager **orchestrated** the entire launch campaign."
- **义项 3: 整体调度 (v.)** — 从全局角度调度多个组件
  - "The workflow engine **orchestrates** the execution of distributed tasks."

### 44. choreograph
- **义项 1: 编排协调 (v.)** — 让多个独立服务协同工作但不依赖中央控制器
  - "In an event-driven architecture, services **choreograph** their interactions through events."
- **义项 2: 精心安排 (v.)** — 安排复杂的事件序列
  - "The teams **choreographed** their deployments to minimize conflicts."
- **义项 3: 协同设计 (v.)** — 设计多个部分如何协同工作而不需集中控制
  - "We **choreographed** the microservices so they could operate independently."

### 45. stage
- **义项 1: 分阶段进行 (v.)** — 将过程分成多个阶段
  - "We **staged** the rollout across three regions to reduce risk."
- **义项 2: 暂存 (v.)** — 将变更临时存放准备提交
  - "I **staged** the changes but did not commit them yet."
- **义项 3: 阶段 (n.)** — 过程中的一个阶段
  - "The first **stage** of the migration involves moving the database."

### 46. gate
- **义项 1: 门控 (v.)** — 设置检查点控制某事的进行
  - "The release is **gated** on all tests passing and security approval."
- **义项 2: 控制访问 (v.)** — 控制对资源的访问
  - "The API gateway **gates** access to backend services based on authentication."
- **义项 3: 检查关卡 (n.)** — 过程中的审批或检查点
  - "There is a quality **gate** before any code can be deployed to production."

### 47. promote
- **义项 1: 提升晋升 (v.)** — 将某人升到更高职位
  - "She was **promoted** to senior engineer after leading the successful migration."
- **义项 2: 提升环境 (v.)** — 将代码从低环境推向高环境
  - "We **promoted** the build from staging to production after validation."
- **义项 3: 推广宣传 (v.)** — 宣传或推广某事物
  - "The team **promoted** the new coding standards across the organization."

### 48. demote
- **义项 1: 降级 (v.)** — 将某人降到较低职位
  - "He was **demoted** from tech lead to senior developer after the project failure."
- **义项 2: 降级环境 (v.)** — 将某物降到较低级别
  - "We **demoted** the server to a backup role after the hardware upgrade."
- **义项 3: 降低优先级 (v.)** — 将某事的优先级降低
  - "The feature was **demoted** from critical to nice-to-have in the next release."

### 49. approve
- **义项 1: 批准 (v.)** — 正式同意某事
  - "The tech lead **approved** my pull request after a thorough review."
- **义项 2: 核准 (v.)** — 正式授权某物
  - "The budget for the new server was **approved** by the finance department."
- **义项 3: 认可 (v.)** — 认为某事好或合适
  - "The architecture review committee **approved** the design proposal."

### 50. ratify
- **义项 1: 正式批准 (v.)** — 通过正式程序批准协议或决定
  - "The steering committee **ratified** the decision to adopt a new tech stack."
- **义项 2: 签署确认 (v.)** — 正式签署使某事生效
  - "The contract was **ratified** by both parties after the negotiations."
- **义项 3: 认可追认 (v.)** — 事后正式认可之前的行为
  - "The board **ratified** the emergency measures taken by the engineering team."

---

### Group 2: System Behavior & Operation Verbs（系统行为与操作动词）

---

### 51. initialize
- **义项 1: 初始化 (v.)** — 准备系统或变量使其可用
  - "The application **initializes** the database connection pool on startup."
- **义项 2: 启动 (v.)** — 开始一个过程或系统
  - "We need to **initialize** the replication process before migrating the data."
- **义项 3: 格式化 (v.)** — 准备存储设备以供使用
  - "The script **initializes** the new disk and mounts it to the file system."

### 52. bootstrap
- **义项 1: 自启动 (v.)** — 从一个简单状态启动并自我完善
  - "The system **bootstraps** itself by loading the initial configuration."
- **义项 2: 白手起家 (v.)** — 用很少的资源创建并发展某事物
  - "The startup **bootstrapped** its first product without any external funding."
- **义项 3: 引导加载 (v.)** — 加载并启动操作系统或框架
  - "The framework **bootstraps** the application and mounts it to the DOM."

### 53. instantiate
- **义项 1: 实例化 (v.)** — 创建类的实例或对象
  - "The factory pattern **instantiates** the appropriate handler based on the request type."
- **义项 2: 创建实例 (v.)** — 在云环境中创建资源实例
  - "We **instantiated** a new virtual machine for the load testing."
- **义项 3: 具体化 (v.)** — 用具体事例体现某概念
  - "The design pattern is **instantiated** in several places across the codebase."

### 54. spawn
- **义项 1: 派生进程 (v.)** — 创建新的子进程或线程
  - "The parent process **spawns** a new worker for each incoming request."
- **义项 2: 大量产生 (v.)** — 引发大量某事物的产生
  - "The configuration error **spawned** dozens of related alerts."
- **义项 3: 生成 (v.)** — 产生某物
  - "The API **spawns** a new instance of the report generator for each user."

### 55. fork
- **义项 1: 创建子进程 (v.)** — 操作系统创建子进程
  - "The server **forks** a new process to handle each incoming connection."
- **义项 2: 复刻仓库 (v.)** — 复制代码仓库到自己的账户下
  - "I **forked** the repository to experiment with a different approach."
- **义项 3: 分岔 (v.)** — 一分为二
  - "The execution path **forks** depending on whether the user is authenticated."

### 56. clone
- **义项 1: 克隆仓库 (v.)** — 从远程仓库复制代码到本地
  - "I **cloned** the repository using the SSH URL."
- **义项 2: 复制 (v.)** — 创建某物的精确副本
  - "The system **clones** the virtual machine to create identical environments."
- **义项 3: 克隆技术 (n.)** — 生物或技术上的精确复制
  - "The **clone** of the production database is used for performance testing."

### 57. replicate
- **义项 1: 复制数据 (v.)** — 将数据从一个位置复制到另一个
  - "The database **replicates** data across multiple geographic regions."
- **义项 2: 复现 (v.)** — 重现某种条件或结果
  - "We need to **replicate** the production environment in staging to reproduce the bug."
- **义项 3: 仿效 (v.)** — 复制某人的成功或方法
  - "The team **replicated** the deployment model used by the infrastructure team."

### 58. mirror
- **义项 1: 镜像 (v.)** — 精确地复制或反映
  - "The staging environment **mirrors** the production configuration exactly."
- **义项 2: 镜像站点 (n.)** — 存储副本的服务器
  - "The package is available on multiple **mirror** servers around the world."
- **义项 3: 反映 (v.)** — 反映或展示某事物的状态
  - "The status dashboard **mirrors** the health of all production services."

### 59. sync
- **义项 1: 同步数据 (v.)** — 使数据在不同系统间保持一致
  - "The mobile app **syncs** with the cloud server when the network is available."
- **义项 2: 同步信息 (v.)** — 互通信息以保持一致的理解
  - "Let us **sync** up after the meeting to align on the next steps."
- **义项 3: 同步操作 (v.)** — 协调操作的时间顺序
  - "The threads **sync** their state using a shared mutex."

### 60. flush
- **义项 1: 刷新缓冲区 (v.)** — 将缓冲区中的数据刷出
  - "The system **flushes** the cache to disk before shutting down."
- **义项 2: 清除 (v.)** — 彻底清除某物
  - "We **flushed** the old DNS records and replaced them with the new ones."
- **义项 3: 冲洗 (v.)** — 用水或其他液体冲洗
  - "The script **flushes** the temporary table after each batch job completes."

### 61. drain
- **义项 1: 排空耗尽 (v.)** — 逐步排空连接或资源
  - "The load balancer **drains** active connections from the server before taking it offline."
- **义项 2: 耗尽 (v.)** — 消耗殆尽
  - "The memory leak **drained** all available system resources."
- **义项 3: 逐渐减少 (v.)** — 使某物逐渐变少
  - "We **drained** the queue of pending jobs before the maintenance window."

### 62. purge
- **义项 1: 清除 (v.)** — 彻底删除或移除
  - "We **purged** all expired records from the database to reclaim space."
- **义项 2: 清空 (v.)** — 完全清理某物
  - "The CDN **purges** the cached content after the static assets are updated."
- **义项 3: 清洗数据 (v.)** — 彻底清除不需要的数据
  - "The retention policy **purges** logs older than 90 days."

### 63. evict
- **义项 1: 逐出 (v.)** — 将某物从缓存或内存中移除
  - "The cache **evicts** the least recently used items when memory is full."
- **义项 2: 驱逐 (v.)** — 强制某人离开某地
  - "The user was **evicted** from the session due to inactivity."
- **义项 3: 淘汰 (v.)** — 根据策略移除条目
  - "The system **evicts** idle connections from the connection pool."

### 64. expire
- **义项 1: 过期 (v.)** — 达到有效期的终点
  - "The SSL certificate **expired** causing the HTTPS connection to fail."
- **义项 2: 失效 (v.)** — 某事物的有效期结束
  - "The session token **expires** after 24 hours for security reasons."
- **义项 3: 到期 (v.)** — 时间限制达到
  - "The cache entry **expires** after five minutes and is refreshed automatically."

### 65. invalidate
- **义项 1: 使失效 (v.)** — 使某物不再有效
  - "The updated schema **invalidated** all existing API responses in the cache."
- **义项 2: 使无效 (v.)** — 宣告某物不再可用或合法
  - "A change in the source data **invalidates** the derived calculations."
- **义项 3: 撤销 (v.)** — 使许可或授权失效
  - "The admin **invalidated** the compromised API tokens immediately."

### 66. refresh
- **义项 1: 刷新 (v.)** — 重新加载或更新数据
  - "Press F5 to **refresh** the page and see the latest data."
- **义项 2: 刷新缓存 (v.)** — 使缓存更新为最新状态
  - "We **refreshed** the materialized view to reflect recent database changes."
- **义项 3: 提神 (v.)** — 使人恢复精力
  - "A short break **refreshed** the team before the incident review meeting."

### 67. reload
- **义项 1: 重新加载 (v.)** — 再次加载配置文件或资源
  - "The server **reloads** the configuration file without requiring a full restart."
- **义项 2: 重装 (v.)** — 重新装入弹药或资源
  - "The application **reloaded** the module to pick up the latest changes."
- **义项 3: 重新导入 (v.)** — 再次导入数据
  - "We had to **reload** the dataset after the import script failed."

### 68. restart
- **义项 1: 重启 (v.)** — 停止后再启动系统或服务
  - "The server needs to be **restarted** after the kernel update."
- **义项 2: 重新开始 (v.)** — 从头再来
  - "We decided to **restart** the migration process from scratch."
- **义项 3: 重启流程 (v.)** — 使某过程重新开始
  - "The failed job was **restarted** automatically by the scheduler."

### 69. respawn
- **义项 1: 重生 (v.)** — 进程崩溃后自动重新启动
  - "The supervisor process **respawns** any worker that crashes unexpectedly."
- **义项 2: 重新生成 (v.)** — 在某事物死亡或消失后再次出现
  - "The game **respawns** the player at the last checkpoint after death."
- **义项 3: 重建 (v.)** — 淘汰后重新创建
  - "The orchestrator **respawns** failed containers to maintain the desired state."

### 70. resurrect
- **义项 1: 复活 (v.)** — 重新使用被废弃或停用的项目
  - "The team **resurrected** the old codebase when the new implementation failed."
- **义项 2: 恢复 (v.)** — 使某物重新出现
  - "We **resurrected** the retired service to handle the unexpected traffic spike."
- **义项 3: 重拾 (v.)** — 重新开始做某事
  - "The company **resurrected** the project after a two-year hiatus."

### 71. recover
- **义项 1: 恢复 (v.)** — 从错误或故障中恢复正常
  - "The database **recovered** from the crash within minutes."
- **义项 2: 找回 (v.)** — 重新获得丢失的东西
  - "We **recovered** the deleted files from the backup."
- **义项 3: 痊愈 (v.)** — 身体或系统恢复健康
  - "The system **recovered** fully after the incident and returned to normal operation."

### 72. restore
- **义项 1: 还原 (v.)** — 将系统或数据恢复到之前的状态
  - "We **restored** the database from the most recent backup."
- **义项 2: 复原 (v.)** — 使某物回到原有的状态
  - "The IT team **restored** the deleted user account within an hour."
- **义项 3: 修复 (v.)** — 使破损的东西恢复原状
  - "The snapshot was used to **restore** the virtual machine after the corruption."

### 73. rollback
- **义项 1: 回滚 (v.)** — 撤销最近的变更回到之前的状态
  - "We had to **rollback** the deployment after discovering a critical bug."
- **义项 2: 回退 (v.)** — 将数据恢复到之前的版本
  - "The transaction is **rolled back** automatically if any step fails."
- **义项 3: 撤销 (v.)** — 撤销操作或决定
  - "The committee **rolled back** the policy change after negative feedback."

### 74. revert
- **义项 1: 还原 (v.)** — 将代码或系统恢复到之前的版本
  - "I **reverted** the commit that introduced the regression."
- **义项 2: 恢复原状 (v.)** — 回到之前的状态或行为
  - "The system **reverts** to the default configuration if the custom one fails."
- **义项 3: 回到话题 (v.)** — 回到之前讨论的话题
  - "Let me **revert** to the point I made earlier about test coverage."

### 75. undo
- **义项 1: 撤销 (v.)** — 取消之前的操作
  - "You can **undo** the last change by pressing Control-Z."
- **义项 2: 消除影响 (v.)** — 使某事物的影响消失
  - "The damage caused by the data breach could not be **undone**."
- **义项 3: 取消 (v.)** — 使某个行动或决定失效
  - "The decision to restructure the team was **undone** after the manager left."

### 76. redo
- **义项 1: 重做 (v.)** — 再次做某事
  - "I had to **redo** the entire analysis after discovering the data was corrupted."
- **义项 2: 重复 (v.)** — 重复之前的操作
  - "The system automatically **redoes** the failed operation when the connection is restored."
- **义项 3: 翻新 (v.)** — 重新装修或改造
  - "We **redid** the entire UI to align with the new design system."

### 77. replay
- **义项 1: 重放 (v.)** — 回放日志或事件以重现故障
  - "We **replayed** the production logs in the staging environment to debug the issue."
- **义项 2: 重新处理 (v.)** — 再次处理队列中的消息
  - "The consumer **replays** failed messages from the dead-letter queue."
- **义项 3: 回放记录 (v.)** — 重播录制的数据或操作
  - "The load testing tool **replays** recorded user sessions against the application."

### 78. reprocess
- **义项 1: 重新处理 (v.)** — 再次处理数据或任务
  - "We **reprocessed** the batch of events after fixing the parsing error."
- **义项 2: 重新分析 (v.)** — 用新方法再次分析数据
  - "The team **reprocessed** the historical data using the updated algorithm."
- **义项 3: 重跑 (v.)** — 重新运行某个过程
  - "The pipeline automatically **reprocesses** any failed records before the next batch."

### 79. retry
- **义项 1: 重试 (v.)** — 在失败后再次尝试
  - "The service **retries** the request three times before giving up."
- **义项 2: 重试机制 (n.)** — 自动重试失败的策略
  - "We implemented an exponential backoff **retry** for the API calls."
- **义项 3: 再次尝试 (v.)** — 尝试再试一次
  - "If the deployment fails, **retry** after checking the configuration."

### 80. resume
- **义项 1: 恢复 (v.)** — 暂停后继续
  - "The download **resumed** from where it stopped after the network came back."
- **义项 2: 重新开始 (v.)** — 中断后继续
  - "The meeting **resumed** after a brief break."
- **义项 3: 简历 (n.)** — 个人履历
  - "Please attach your **resume** when applying for the position."

### 81. suspend
- **义项 1: 挂起 (v.)** — 暂时停止某活动或进程
  - "The system **suspends** inactive user sessions after 30 minutes."
- **义项 2: 暂停 (v.)** — 暂停某个流程的进行
  - "We **suspended** the release due to the critical security vulnerability."
- **义项 3: 悬浮 (v.)** — 悬挂或漂浮
  - "The particles are **suspended** in the liquid solution."

### 82. pause
- **义项 1: 暂停 (v.)** — 临时停止正在进行的事
  - "I **paused** the video to take notes on the architecture explanation."
- **义项 2: 暂停执行 (v.)** — 暂停代码或流程的执行
  - "The script **pauses** for five seconds before retrying the connection."
- **义项 3: 停顿 (n.)** — 说话或活动中的短暂停顿
  - "There was a long **pause** after the manager asked who caused the outage."

### 83. halt
- **义项 1: 停止 (v.)** — 突然或彻底停止
  - "Production was **halted** immediately after the data breach was discovered."
- **义项 2: 使停止 (v.)** — 使某事物完全停止
  - "The system **halted** all background jobs to prioritize user requests."
- **义项 3: 中断 (n.)** — 突然的停止
  - "The deployment came to a **halt** when the test suite failed."

### 84. terminate
- **义项 1: 终止 (v.)** — 结束进程或连接
  - "The cloud provider **terminated** the instance after the billing threshold was exceeded."
- **义项 2: 解雇 (v.)** — 正式解除雇佣关系
  - "His employment was **terminated** after the security violation."
- **义项 3: 终结 (v.)** — 使某事到达终点
  - "The SSL connection is **terminated** at the load balancer."

### 85. abort
- **义项 1: 中止 (v.)** — 异常退出正在运行的操作
  - "The script **aborted** execution when it encountered an unexpected error."
- **义项 2: 取消 (v.)** — 在完成前取消
  - "We had to **abort** the deployment when the database migration failed."
- **义项 3: 终止 (v.)** — 中断某过程
  - "The request was **aborted** because the client disconnected."

### 86. cancel
- **义项 1: 取消 (v.)** — 决定某事将不会发生
  - "We **canceled** the release because of the last-minute security issue."
- **义项 2: 抵消 (v.)** — 使某物的影响消失
  - "The positive and negative values **cancel** each other out."
- **义项 3: 作废 (v.)** — 标记为无效
  - "The previous order was **canceled** and replaced with a new one."

### 87. revoke
- **义项 1: 撤销权限 (v.)** — 取消之前授予的权限
  - "The admin **revoked** the user's access to the production database."
- **义项 2: 吊销 (v.)** — 正式撤销证书或许可
  - "The compromised SSL certificate was **revoked** immediately."
- **义项 3: 收回 (v.)** — 撤回某事物
  - "The offer was **revoked** after the candidate failed the background check."

### 88. rescind
- **义项 1: 撤销废除 (v.)** — 正式取消或废除
  - "The company **rescinded** the job offer after the budget cuts."
- **义项 2: 废止 (v.)** — 正式终止法律、协议等
  - "The policy was **rescinded** following complaints from employees."
- **义项 3: 取消决定 (v.)** — 收回之前的决定
  - "The committee **rescinded** its earlier approval of the proposal."

### 89. relinquish
- **义项 1: 放弃 (v.)** — 自愿放弃控制权或所有权
  - "He **relinquished** his role as tech lead to focus on architecture."
- **义项 2: 让出 (v.)** — 让出资源或位置
  - "The process **relinquishes** the lock after the transaction is complete."
- **义项 3: 释放 (v.)** — 不再掌握某事
  - "She **relinquished** control of the project when she moved to a different team."

### 90. release
- **义项 1: 发布 (v.)** — 发布软件或产品
  - "We **released** version 3.0 of the application last quarter."
- **义项 2: 释放资源 (v.)** — 释放被占用的资源
  - "The application failed to **release** the database connections, causing a pool exhaustion."
- **义项 3: 发布版本 (n.)** — 软件的一个发布版本
  - "The latest **release** includes several critical security patches."

### 91. retain
- **义项 1: 保留 (v.)** — 继续拥有或持有
  - "We **retained** the old API endpoint for backward compatibility."
- **义项 2: 保存 (v.)** — 保持记忆或信息
  - "The system **retains** logs for 90 days as per compliance requirements."
- **义项 3: 留住 (v.)** — 留住人才或客户
  - "The company implemented new policies to **retain** senior engineers."

### 92. reclaim
- **义项 1: 回收 (v.)** — 收回已分配的资源
  - "The garbage collector **reclaims** memory that is no longer in use."
- **义项 2: 取回 (v.)** — 拿回被拿走的东西
  - "We **reclaimed** the storage space by deleting unused snapshots."
- **义项 3: 恢复 (v.)** — 使某物恢复原状或重新利用
  - "The team **reclaimed** the abandoned project and turned it into a success."

### 93. recycle
- **义项 1: 循环利用 (v.)** — 重复使用资源或组件
  - "The connection pool **recycles** idle connections instead of creating new ones."
- **义项 2: 回收利用 (v.)** — 将废品加工再利用
  - "We **recycle** paper, plastic, and electronics in our office."
- **义项 3: 重用 (v.)** — 重新使用已经使用过的对象
  - "The framework **recycles** view objects to improve performance."

### 94. dispose
- **义项 1: 释放资源 (v.)** — 清理并释放不再使用的资源
  - "The application **disposes** of the database connection after the query completes."
- **义项 2: 处理掉 (v.)** — 丢弃或处理某物
  - "We need to **dispose** of the old servers in an environmentally friendly way."
- **义项 3: 安排 (v.)** — 倾向于做某事或愿意
  - "The manager was not **disposed** to approve the budget increase."

### 95. finalize
- **义项 1: 最终确定 (v.)** — 完成所有细节并确定下来
  - "We **finalized** the architecture decision after weeks of evaluation."
- **义项 2: 定稿 (v.)** — 完成某物的最终版本
  - "The design document was **finalized** and sent for stakeholder approval."
- **义项 3: 完成收尾 (v.)** — 将某事做完并结束
  - "The team **finalized** the sprint by closing all completed tickets."

### 96. destruct
- **义项 1: 析构 (v.)** — 销毁对象并释放其资源
  - "The class **destructs** itself when the reference count reaches zero."
- **义项 2: 破坏 (v.)** — 有意地破坏某物
  - "The atomic operation either completes fully or **destructs** cleanly."
- **义项 3: 解构 (v.)** — 分解成组成部分
  - "The function **destructs** the input object into individual variables."

### 97. teardown
- **义项 1: 拆除销毁 (v.)** — 销毁测试环境或基础设施
  - "The test suite **tears down** the temporary database after each test run."
- **义项 2: 拆卸 (v.)** — 拆解某物的部件
  - "We **tore down** the old staging environment to reduce costs."
- **义项 3: 清理收尾 (v.)** — 清理过程结束时的状态
  - "The script handles the **teardown** of all cloud resources after the pipeline finishes."

### 98. destroy
- **义项 1: 销毁 (v.)** — 完全摧毁某物
  - "The fire **destroyed** the primary data center."
- **义项 2: 删除资源 (v.)** — 永久删除不能再恢复
  - "We **destroyed** the virtual machines after migrating to the new infrastructure."
- **义项 3: 摧毁 (v.)** — 彻底破坏某事
  - "The incident **destroyed** the team's confidence in the deployment process."

### 99. decommission
- **义项 1: 退役 (v.)** — 正式停止使用老旧系统或设备
  - "We **decommissioned** the legacy mainframe after the migration was complete."
- **义项 2: 报废 (v.)** — 将旧设备报废
  - "The old servers were **decommissioned** and sent for recycling."
- **义项 3: 停用 (v.)** — 正式停止运行
  - "The API endpoint was **decommissioned** six months after being deprecated."

### 100. reconcile
- **义项 1: 调和 (v.)** — 使冲突或差异变得一致
  - "We need to **reconcile** the differences between the two data sources."
- **义项 2: 对账 (v.)** — 核对账目使其一致
  - "The system automatically **reconciles** transactions against bank statements."
- **义项 3: 调解 (v.)** — 使双方和好或达成一致
  - "The manager **reconciled** the conflicting priorities of the two teams."

---

### Group 3: Precision & Nuance Adjectives（精准与微调形容词）

---

### 101. arbitrary
- **义项 1: 任意的 (adj.)** — 基于随机选择而非合理依据
  - "The timeout value seemed **arbitrary** and was not based on any performance data."
- **义项 2: 武断的 (adj.)** — 由个人意志而非规则决定
  - "The decision to use that specific technology felt **arbitrary**."
- **义项 3: 随机的 (adj.)** — 没有特定模式
  - "The failure occurs at **arbitrary** intervals, making it hard to debug."

### 102. deterministic
- **义项 1: 确定性的 (adj.)** — 给定输入总是产生相同输出
  - "The algorithm is **deterministic** — the same input always produces the same result."
- **义项 2: 决定的 (adj.)** — 结果由先前的因素决定了
  - "In a **deterministic** system, there is no randomness in the outcome."
- **义项 3: 因果确定的 (adj.)** — 每个事件都有明确的原因
  - "We need a **deterministic** approach to debugging rather than guesswork."

### 103. stochastic
- **义项 1: 随机的 (adj.)** — 包含随机性的过程或系统
  - "The **stochastic** nature of the network means latency can vary significantly."
- **义项 2: 概率的 (adj.)** — 基于概率模型的
  - "We used a **stochastic** model to simulate traffic patterns on the website."
- **义项 3: 不确定的 (adj.)** — 结果不是完全可预测的
  - "The **stochastic** behavior of the garbage collector makes performance tuning challenging."

### 104. probabilistic
- **义项 1: 概率的 (adj.)** — 基于概率而非确定性的
  - "The **probabilistic** data structure gives approximate results but uses very little memory."
- **义项 2: 可能性的 (adj.)** — 涉及可能性的计算
  - "We used a **probabilistic** approach to estimate system reliability."
- **义项 3: 随机的 (adj.)** — 包含一定程度的随机性
  - "The load balancer uses a **probabilistic** routing algorithm to distribute traffic."

### 105. approximate
- **义项 1: 近似的 (adj.)** — 接近但不完全精确
  - "The **approximate** number of daily active users is 50,000."
- **义项 2: 粗略的 (adj.)** — 不精确但足够用的
  - "We only need an **approximate** estimate of the migration cost."
- **义项 3: 近似值 (v.)** — 接近某数值或状态
  - "The response time **approximates** 200 milliseconds under normal load."

### 106. exact
- **义项 1: 精确的 (adj.)** — 完全准确的
  - "We need the **exact** memory usage before and after the optimization."
- **义项 2: 确切的 (adj.)** — 完全一样的
  - "The **exact** same error occurs every time we run the test."
- **义项 3: 精准的 (adj.)** — 严格准确的
  - "The measurement must be **exact** to ensure the calculations are correct."

### 107. precise
- **义项 1: 精确的 (adj.)** — 细致准确的
  - "The **precise** cause of the crash was identified through log analysis."
- **义项 2: 严谨的 (adj.)** — 重视细节和准确性的
  - "The documentation must be **precise** to avoid misinterpretation."
- **义项 3: 精密的 (adj.)** — 需要高度准确的
  - "**Precise** timing is critical for the distributed consensus algorithm."

### 108. accurate
- **义项 1: 准确的 (adj.)** — 符合事实或标准的
  - "The monitoring system provides **accurate** real-time metrics."
- **义项 2: 正确的 (adj.)** — 没有错误的
  - "The prediction model is 95 percent **accurate** in forecasting traffic spikes."
- **义项 3: 精确的 (adj.)** — 可靠且符合实际情况
  - "We need **accurate** data to make informed architectural decisions."

### 109. granular
- **义项 1: 细粒度的 (adj.)** — 细节级别很高的
  - "We need more **granular** metrics to pinpoint the performance bottleneck."
- **义项 2: 精细的 (adj.)** — 可以分解成小部分的
  - "The system provides **granular** access control at the field level."
- **义项 3: 颗粒状的 (adj.)** — 由小颗粒组成的
  - "The **granular** structure of the data allows for detailed analysis."

### 110. fine-grained
- **义项 1: 细粒度的 (adj.)** — 具有高度细节和精确度的
  - "The **fine-grained** permission model allows access control at the document level."
- **义项 2: 细致的 (adj.)** — 关注细微之处的
  - "A **fine-grained** analysis of the logs revealed the root cause."
- **义项 3: 精细控制的 (adj.)** — 可以精确调节的
  - "The **fine-grained** configuration options let us tune each parameter individually."

### 111. coarse-grained
- **义项 1: 粗粒度的 (adj.)** — 细节级别较低的
  - "A **coarse-grained** estimate is sufficient for the initial planning phase."
- **义项 2: 大粒度的 (adj.)** — 处理较大单位的
  - "**Coarse-grained** locking works well when conflicts are rare."
- **义项 3: 粗略的 (adj.)** — 不追求细节的
  - "The **coarse-grained** model gives a general picture without deep detail."

### 112. high-level
- **义项 1: 高层次的 (adj.)** — 从宏观角度考虑的
  - "We need a **high-level** architecture overview before diving into the details."
- **义项 2: 粗略的 (adj.)** — 不涉及具体细节的
  - "The manager provided a **high-level** summary of the project status."
- **义项 3: 高级的 (adj.)** — 位于较高抽象层次的
  - "**High-level** programming languages abstract away hardware details."

### 113. low-level
- **义项 1: 底层的 (adj.)** — 靠近硬件或实现细节的
  - "The **low-level** network code handles packet transmission and retry logic."
- **义项 2: 细节的 (adj.)** — 涉及具体操作细节的
  - "We need a **low-level** understanding of how the kernel manages memory."
- **义项 3: 低级抽象的 (adj.)** — 接近机器级别的
  - "C is considered a **low-level** language compared to Python."

### 114. abstract
- **义项 1: 抽象的 (adj.)** — 基于概念而非具体实例的
  - "The **abstract** concept of a service mesh is hard to grasp at first."
- **义项 2: 抽象的 (v.)** — 提取出通用概念或模式
  - "We should **abstract** the common logic into a shared library."
- **义项 3: 理论性的 (adj.)** — 不涉及具体实现的
  - "The discussion remained too **abstract** without concrete examples."

### 115. concrete
- **义项 1: 具体的 (adj.)** — 真实存在的、可触摸的
  - "We need **concrete** evidence before making the architecture change."
- **义项 2: 实在的 (adj.)** — 非抽象或理论的
  - "The **concrete** implementation details still need to be worked out."
- **义项 3: 有形的 (adj.)** — 可以感知或测量的
  - "The performance improvement was not **concrete** enough to justify the effort."

### 116. generic
- **义项 1: 通用的 (adj.)** — 普适的、不特化的
  - "We designed a **generic** caching layer that can be used by all services."
- **义项 2: 泛型的 (adj.)** — 编程中可适配多种类型的
  - "The **generic** type parameter allows the function to work with any data type."
- **义项 3: 普通的 (adj.)** — 缺乏特性或特殊性的
  - "The error message was too **generic** to be helpful for debugging."

### 117. specific
- **义项 1: 特定的 (adj.)** — 明确指定的
  - "The bug only occurs under **specific** conditions involving high traffic."
- **义项 2: 具体的 (adj.)** — 详细的、不模糊的
  - "Could you be more **specific** about which part of the system failed?"
- **义项 3: 特指的 (adj.)** — 有特定功能的
  - "Each microservice has a **specific** domain responsibility."

### 118. explicit
- **义项 1: 明确的 (adj.)** — 清楚表达不含糊的
  - "The contract **explicitly** states that the SLA guarantees 99.9 percent uptime."
- **义项 2: 显式的 (adj.)** — 明确写出或声明的
  - "You need to be **explicit** about the type annotation in TypeScript."
- **义项 3: 直白的 (adj.)** — 不隐瞒的
  - "The error message was **explicit** about what went wrong."

### 119. implicit
- **义项 1: 隐含的 (adj.)** — 未明确表达但可以推断的
  - "There is an **implicit** assumption that all services are stateless."
- **义项 2: 隐式的 (adj.)** — 无需显式指定即可生效的
  - "JavaScript has **implicit** type conversion, which can lead to unexpected bugs."
- **义项 3: 不言而喻的 (adj.)** — 不需要说出来的
  - "The trust between team members was **implicit** after years of collaboration."

### 120. tacit
- **义项 1: 默示的 (adj.)** — 不说出来但大家都理解的
  - "There is a **tacit** understanding that we do not deploy on Fridays."
- **义项 2: 心照不宣的 (adj.)** — 不言明的协议或共识
  - "The team had a **tacit** agreement to avoid major changes before the release."
- **义项 3: 默许的 (adj.)** — 通过沉默表示同意的
  - "His silence was taken as **tacit** approval of the plan."

### 121. overt
- **义项 1: 公开的 (adj.)** — 不隐藏的、明显的
  - "There was an **overt** conflict between the two architects about the design."
- **义项 2: 明显的 (adj.)** — 容易被看出的
  - "The **overt** bias toward one technology was concerning to the team."
- **义项 3: 公开行为的 (adj.)** — 有意识表现出来的
  - "**Overt** approval from the manager boosted the team's confidence."

### 122. subtle
- **义项 1: 微妙的 (adj.)** — 难以察觉的、精细的
  - "There is a **subtle** difference between the two caching strategies."
- **义项 2: 细微的 (adj.)** — 程度很轻的
  - "The bug was caused by a **subtle** off-by-one error in the loop."
- **义项 3: 巧妙的 (adj.)** — 需要敏锐洞察力才能欣赏的
  - "The solution is **subtle** but elegant once you understand the reasoning."

### 123. nuanced
- **义项 1: 细致微妙的 (adj.)** — 包含许多细微差别的
  - "The **nuanced** discussion about trade-offs helped the team make a better decision."
- **义项 2: 有层次感的 (adj.)** — 不简单化的
  - "Her **nuanced** understanding of the problem led to a more robust solution."
- **义项 3: 精细的 (adj.)** — 考虑到各种细微因素的
  - "A **nuanced** approach is needed when balancing security with usability."

### 124. profound
- **义项 1: 深远的 (adj.)** — 影响重大的
  - "The migration to microservices had a **profound** impact on the team structure."
- **义项 2: 深刻的 (adj.)** — 含义深远的
  - "Her insights on system design were **profound** and changed how we think about scalability."
- **义项 3: 透彻的 (adj.)** — 知识或理解深入
  - "He has a **profound** understanding of distributed systems theory."

### 125. shallow
- **义项 1: 浅显的 (adj.)** — 不深入、停留在表面的
  - "A **shallow** copy of the object does not duplicate nested structures."
- **义项 2: 肤浅的 (adj.)** — 缺乏深度或思考的
  - "The analysis was too **shallow** to identify the real root cause."
- **义项 3: 浅薄的 (adj.)** — 不深厚的
  - "His **shallow** understanding of the protocol caused the configuration error."

### 126. broad
- **义项 1: 广泛的 (adj.)** — 覆盖范围大的
  - "The incident had a **broad** impact affecting multiple customer-facing services."
- **义项 2: 大概的 (adj.)** — 不详细的大体描述
  - "I need a **broad** overview of the system architecture first."
- **义项 3: 宽泛的 (adj.)** — 包含多种类型或范围的
  - "The term 'cloud computing' is very **broad** and covers many services."

### 127. narrow
- **义项 1: 狭窄的 (adj.)** — 范围或宽度小的
  - "The scope of the investigation was **narrow** to focus on a specific component."
- **义项 2: 狭隘的 (adj.)** — 眼界受限的
  - "A **narrow** focus on one technology can limit career growth."
- **义项 3: 缩小的 (v.)** — 减少范围或差异
  - "We **narrowed** down the possible causes to three candidates."

### 128. holistic
- **义项 1: 整体的 (adj.)** — 从全局综合考虑的
  - "We need a **holistic** view of the system architecture before making changes."
- **义项 2: 全面的 (adj.)** — 考虑到所有方面
  - "A **holistic** approach to security includes people, processes, and technology."
- **义项 3: 综合的 (adj.)** — 将各部件视为互相关联的整体
  - "**Holistic** performance tuning considers the entire request path."

### 129. comprehensive
- **义项 1: 全面的 (adj.)** — 包含所有要素的
  - "The **comprehensive** test suite covers edge cases for every module."
- **义项 2: 详尽的 (adj.)** — 非常全面细致
  - "We conducted a **comprehensive** review of the security architecture."
- **义项 3: 广泛的 (adj.)** — 涵盖范围很大的
  - "The documentation provides a **comprehensive** guide to the API."

### 130. exhaustive
- **义项 1: 穷尽的 (adj.)** — 彻底地覆盖所有可能性
  - "An **exhaustive** search of the log files revealed no anomalies."
- **义项 2: 彻底的 (adj.)** — 极其详尽和充分的
  - "The team performed an **exhaustive** analysis of the performance data."
- **义项 3: 令人筋疲力尽的 (adj.)** — 让人极度疲惫的
  - "The **exhaustive** debugging session lasted for 12 hours."

### 131. selective
- **义项 1: 有选择的 (adj.)** — 经过筛选的
  - "We applied **selective** logging to reduce noise while keeping important events."
- **义项 2: 择优的 (adj.)** — 只选取最好的
  - "The team was **selective** about which technical debts to address first."
- **义项 3: 挑拣的 (adj.)** — 有偏好或偏向的
  - "He was **selective** in choosing which meetings to attend."

### 132. representative
- **义项 1: 代表性的 (adj.)** — 能代表整体的
  - "We sampled a **representative** subset of the data for the analysis."
- **义项 2: 典型的 (adj.)** — 体现某个群体特征的
  - "The bug is **representative** of a larger class of concurrency issues."
- **义项 3: 代表 (n.)** — 代表他人的人
  - "The team sent a **representative** to the architecture review meeting."

### 133. indicative
- **义项 1: 表明的 (adj.)** — 指示或表明某事物的情况
  - "The spike in error rates is **indicative** of an underlying problem."
- **义项 2: 暗示的 (adj.)** — 提供暗示或线索的
  - "The log patterns are **indicative** of a memory leak."
- **义项 3: 指示性的 (adj.)** — 作为指标的
  - "High CPU usage is often **indicative** of insufficient capacity."

### 134. suggestive
- **义项 1: 暗示性的 (adj.)** — 给出暗示但未明确说明的
  - "The data is **suggestive** of a correlation but does not prove causation."
- **义项 2: 启发的 (adj.)** — 引起思考或联想的
  - "The benchmark results are **suggestive** of the need for optimization."
- **义项 3: 挑逗的 (adj.)** — 引起不适当想法的
  - "The inappropriate comments were **suggestive** and unprofessional."

### 135. conclusive
- **义项 1: 结论性的 (adj.)** — 提供决定性的证据
  - "The investigation did not yield **conclusive** evidence of the root cause."
- **义项 2: 确凿的 (adj.)** — 无可辩驳的
  - "The test results were **conclusive** — the new algorithm is three times faster."
- **义项 3: 最终定的 (adj.)** — 结束讨论的
  - "The review was **conclusive** and no further changes were needed."

### 136. definitive
- **义项 1: 决定性的 (adj.)** — 权威且不可改变的
  - "This book is considered the **definitive** guide to distributed systems."
- **义项 2: 最终的 (adj.)** — 最终的版本或答案
  - "We are waiting for the **definitive** decision from the architecture committee."
- **义项 3: 确定的 (adj.)** — 没有疑问的
  - "We need a **definitive** answer on whether to proceed with the migration."

### 137. tentative
- **义项 1: 试验性的 (adj.)** — 尚未最终确定的
  - "We made a **tentative** plan to release next Thursday."
- **义项 2: 试探性的 (adj.)** — 不确定的缺乏信心的
  - "The **tentative** agreement still needs approval from the stakeholders."
- **义项 3: 暂时性的 (adj.)** — 临时采用的
  - "The **tentative** schedule may change depending on the test results."

### 138. preliminary
- **义项 1: 初步的 (adj.)** — 正式之前的初步阶段
  - "The **preliminary** investigation suggests a configuration error."
- **义项 2: 预备的 (adj.)** — 为后续工作做准备的
  - "We completed a **preliminary** analysis of the performance data."
- **义项 3: 初期的 (adj.)** — 尚未完善的
  - "The **preliminary** design needs more work before the review."

### 139. interim
- **义项 1: 临时的 (adj.)** — 过渡期使用的
  - "We implemented an **interim** solution while waiting for the permanent fix."
- **义项 2: 期中的 (adj.)** — 在两个阶段之间的
  - "The **interim** report provided a snapshot of the project's progress."
- **义项 3: 过渡期的 (adj.)** — 临时担任某个角色的
  - "She served as the **interim** tech lead while the position was being filled."

### 140. transitional
- **义项 1: 过渡的 (adj.)** — 处于过渡状态的
  - "The **transitional** period between the old and new systems was carefully planned."
- **义项 2: 转型的 (adj.)** — 从一种状态转变到另一种的
  - "The team is in a **transitional** phase as they adopt the new framework."
- **义项 3: 临时的 (adj.)** — 过渡期使用的
  - "The **transitional** architecture allowed both old and new services to coexist."

### 141. permanent
- **义项 1: 永久的 (adj.)** — 持续存在不会改变的
  - "The database schema change is **permanent** and cannot be easily reverted."
- **义项 2: 终身的 (adj.)** — 持续一生的
  - "The data breach caused **permanent** damage to the company's reputation."
- **义项 3: 固定的 (adj.)** — 非临时的
  - "She was offered a **permanent** position after the six-month trial."

### 142. temporary
- **义项 1: 临时的 (adj.)** — 只在有限时间内存在的
  - "The **temporary** fix allowed the system to stay online while we developed a proper solution."
- **义项 2: 短暂的 (adj.)** — 持续时间很短的
  - "The performance degradation was **temporary** and resolved itself."
- **义项 3: 暂雇的 (adj.)** — 短期雇用的
  - "We hired a **temporary** contractor to help with the migration."

### 143. provisional
- **义项 1: 暂时的 (adj.)** — 正式确定之前使用的
  - "The **provisional** budget was approved pending the final review."
- **义项 2: 临时的 (adj.)** — 提供临时解决方案的
  - "We made **provisional** arrangements for the backup data center."
- **义项 3: 暂定的 (adj.)** — 等待正式确认的
  - "The **provisional** schedule is subject to change based on the feedback."

### 144. conditional
- **义项 1: 有条件的 (adj.)** — 依赖于某条件才成立的
  - "The approval is **conditional** on the completion of security testing."
- **义项 2: 条件的 (adj.)** — 语法中的条件句
  - "The **conditional** statement checks whether the user is authenticated."
- **义项 3: 有前提的 (adj.)** — 以某事为前提的
  - "Their agreement was **conditional** upon receiving additional budget."

### 145. unconditional
- **义项 1: 无条件的 (adj.)** — 不需要任何前提的
  - "The stakeholder gave **unconditional** support for the migration plan."
- **义项 2: 绝对的 (adj.)** — 不附带任何条件的
  - "The **unconditional** guarantee covers all defects for the first year."
- **义项 3: 无保留的 (adj.)** — 完全的没有限制的
  - "The team's **unconditional** commitment to quality was commendable."

### 146. contingent
- **义项 1: 因情况而定的 (adj.)** — 依赖于其他因素的
  - "The release date is **contingent** on the completion of performance testing."
- **义项 2: 应急的 (adj.)** — 作为后备方案准备的
  - "We prepared a **contingent** plan in case the deployment failed."
- **义项 3: 有条件的 (adj.)** — 依赖于某条件
  - "The budget approval is **contingent** on the board's review."

### 147. dependent
- **义项 1: 依赖的 (adj.)** — 需要某物支持的
  - "The application is **dependent** on the database being available at all times."
- **义项 2: 取决于的 (adj.)** — 由其他因素决定的
  - "The deployment strategy is **dependent** on the risk assessment."
- **义项 3: 相关的 (adj.)** — 存在依赖关系的
  - "The dependent services must be deployed in the correct order."

### 148. independent
- **义项 1: 独立的 (adj.)** — 不受他人控制的
  - "Each microservice is **independent** and can be deployed separately."
- **义项 2: 公正的 (adj.)** — 不受影响的
  - "We need an **independent** review of the security architecture."
- **义项 3: 无关的 (adj.)** — 与其他事物无关的
  - "The two failures were **independent** events that happened to occur at the same time."

### 149. autonomous
- **义项 1: 自治的 (adj.)** — 自我管理的
  - "Each team is **autonomous** in making technical decisions for their domain."
- **义项 2: 自主的 (adj.)** — 能独立运作的
  - "The **autonomous** system can handle failures without human intervention."
- **义项 3: 自动化的 (adj.)** — 不需要外部控制的
  - "The **autonomous** scaling policy adjusts resources based on traffic patterns."

### 150. standalone
- **义项 1: 独立的 (adj.)** — 不需要其他支持即可运行的
  - "The **standalone** version of the tool does not require a server."
- **义项 2: 单独的 (adj.)** — 独立存在而非集成的
  - "The **standalone** module can be tested in isolation."
- **义项 3: 自包含的 (adj.)** — 包含所有必要功能的
  - "The script is **standalone** and has no external dependencies."

---

### Group 4: Emotional & Attitudinal Expressions（情绪与态度表达）

---

### 151. apprehensive
- **义项 1: 担忧的 (adj.)** — 对未来可能出事感到不安
  - "The team was **apprehensive** about deploying on a Friday afternoon."
- **义项 2: 忧虑的 (adj.)** — 对某事即将发生感到紧张
  - "I felt **apprehensive** before presenting the architecture proposal to the stakeholders."
- **义项 3: 担心的 (adj.)** — 对未知结果感到担心
  - "She was **apprehensive** about the impact of the organizational changes."

### 152. bewildered
- **义项 1: 困惑的 (adj.)** — 因为事情太复杂或奇怪而感到迷惑
  - "The new developer was **bewildered** by the legacy codebase's structure."
- **义项 2: 不知所措的 (adj.)** — 因为信息太多而不知如何应对
  - "The team was **bewildered** by the conflicting requirements from different stakeholders."
- **义项 3: 茫然的 (adj.)** — 完全搞不清楚状况
  - "I stood **bewildered** as the server continued to crash with no clear error message."

### 153. complacent
- **义项 1: 自满的 (adj.)** — 因为过去的成功而放松警惕
  - "The team became **complacent** after the system ran smoothly for months."
- **义项 2: 沾沾自喜的 (adj.)** — 对自己的成就感到过于满意
  - "A **complacent** attitude toward security led to the data breach."
- **义项 3: 安于现状的 (adj.)** — 不愿意改变或进步
  - "The company grew **complacent** and ignored the changing market trends."

### 154. disgruntled
- **义项 1: 不满的 (adj.)** — 因为待遇或情况不满意而生气
  - "The **disgruntled** employee filed a complaint about the working conditions."
- **义项 2: 心生不快的 (adj.)** — 因为感到被不公正对待而不高兴
  - "The team was **disgruntled** after the bonus cuts were announced."
- **义项 3: 怨气冲天的 (adj.)** — 长期的累积不满
  - "**Disgruntled** customers took to social media to express their frustration."

### 155. dismayed
- **义项 1: 沮丧的 (adj.)** — 因为不好的消息而感到失望
  - "The team was **dismayed** to learn that the release had been postponed."
- **义项 2: 惊愕的 (adj.)** — 因为意外的事而感到震惊和失望
  - "I was **dismayed** by the lack of test coverage in the codebase."
- **义项 3: 苦闷的 (adj.)** — 对某事的状况感到苦恼
  - "The manager was **dismayed** at the slow progress of the project."

### 156. disoriented
- **义项 1: 迷失方向的 (adj.)** — 不清楚自己所在的位置或方向
  - "After the database migration failed, the team felt **disoriented** about what to do next."
- **义项 2: 混乱的 (adj.)** — 因为环境变化而感到困惑
  - "New team members often feel **disoriented** during the first week."
- **义项 3: 失落的 (adj.)** — 因为失去熟悉的东西而感到不安
  - "The team was **disoriented** after the sudden departure of their tech lead."

### 157. elated
- **义项 1: 兴高采烈的 (adj.)** — 因为成功或好消息而极度高兴
  - "The team was **elated** when the deployment completed without any issues."
- **义项 2: 欢欣鼓舞的 (adj.)** — 因为巨大的成就而兴奋
  - "She was **elated** that her architecture proposal was approved."
- **义项 3: 得意洋洋的 (adj.)** — 情绪高涨到极点
  - "The engineers were **elated** after winning the company hackathon."

### 158. exasperated
- **义项 1: 恼怒的 (adj.)** — 因为反复出问题而感到极度烦躁
  - "The on-call engineer was **exasperated** by the recurring false alarms."
- **义项 2: 气恼的 (adj.)** — 因为问题一再发生而失去耐心
  - "The tech lead grew **exasperated** with the team's repeated coding style violations."
- **义项 3: 恼火的 (adj.)** — 被某人的行为彻底惹恼
  - "I was **exasperated** by the third deployment failure of the day."

### 159. flustered
- **义项 1: 慌乱的 (adj.)** — 在压力下表现紧张不安
  - "The junior developer got **flustered** during the incident response."
- **义项 2: 手足无措的 (adj.)** — 在意外情况面前乱了阵脚
  - "She became **flustered** when the demo crashed in front of the client."
- **义项 3: 慌张的 (adj.)** — 因为时间紧或事情多而手忙脚乱
  - "I was **flustered** trying to fix the bug before the deadline."

### 160. indignant
- **义项 1: 愤慨的 (adj.)** — 因为觉得不公正而感到愤怒
  - "The developers were **indignant** about being blamed for the outage."
- **义项 2: 义愤填膺的 (adj.)** — 因为道德上的愤怒而不满
  - "She was **indignant** that her code was rewritten without discussion."
- **义项 3: 愤愤不平的 (adj.)** — 因为认为自己的权利被侵犯而生气
  - "The team was **indignant** when the credit for their work went to another department."

### 161. intrigued
- **义项 1: 好奇的 (adj.)** — 被某事物吸引想要了解更多
  - "I was **intrigued** by the novel approach to handling distributed transactions."
- **义项 2: 感兴趣的 (adj.)** — 对某事物产生兴趣
  - "The senior architect was **intrigued** by the junior engineer's alternative solution."
- **义项 3: 吸引的 (adj.)** — 某事物引起好奇心
  - "She was **intrigued** by the promise of a 10x performance improvement."

### 162. irate
- **义项 1: 暴怒的 (adj.)** — 极度愤怒
  - "The client was **irate** when the system went down during their peak hours."
- **义项 2: 怒不可遏的 (adj.)** — 愤怒到无法控制
  - "**Irate** users flooded the support channel with complaints about the update."
- **义项 3: 震怒的 (adj.)** — 表达强烈的愤怒
  - "The manager was **irate** that the critical bug had been known for weeks but not fixed."

### 163. jaded
- **义项 1: 厌倦的 (adj.)** — 因为经历太多而感到厌倦
  - "After years of failed promises, the team became **jaded** about the new initiatives."
- **义项 2: 疲倦的 (adj.)** — 因为长时间的工作或压力而失去热情
  - "The **jaded** engineer had seen too many rewrites to get excited about another one."
- **义项 3: 麻木的 (adj.)** — 因为反复经历相同的事情而不再敏感
  - "The support team grew **jaded** from dealing with the same complaints every day."

### 164. lukewarm
- **义项 1: 不冷不热的 (adj.)** — 温度适中偏凉
  - "The coffee was **lukewarm** by the time the meeting ended."
- **义项 2: 冷淡的 (adj.)** — 缺乏热情或兴趣
  - "The response to the new proposal was **lukewarm** at best."
- **义项 3: 不温不火的 (adj.)** — 反应或评价不积极也不消极
  - "The stakeholders gave a **lukewarm** reception to the architecture plan."

### 165. mortified
- **义项 1: 羞愧的 (adj.)** — 因为尴尬的事而感到难堪
  - "I was **mortified** when I realized I had deployed to production instead of staging."
- **义项 2: 无地自容的 (adj.)** — 极端尴尬
  - "She was **mortified** when her mistake caused the entire system to crash."
- **义项 3: 窘迫的 (adj.)** — 因为社交失误而感到窘迫
  - "The developer was **mortified** after accidentally pushing credentials to the public repo."

### 166. nonchalant
- **义项 1: 若无其事的 (adj.)** — 表现出不在乎的样子
  - "He remained **nonchalant** despite the severity of the production outage."
- **义项 2: 满不在乎的 (adj.)** — 对重要事情表现出冷漠的态度
  - "Her **nonchalant** attitude toward security protocols worried the team."
- **义项 3: 淡然的 (adj.)** — 刻意表现得轻松不在意
  - "The manager tried to appear **nonchalant** about the missed deadline, but everyone knew he was upset."

### 167. nostalgic
- **义项 1: 怀旧的 (adj.)** — 怀念过去的美好时光
  - "The engineer felt **nostalgic** when talking about the early days of the startup."
- **义项 2: 思旧的 (adj.)** — 倾向于回忆和想念过去
  - "Looking at the old codebase made the team **nostalgic** for simpler times."
- **义项 3: 留恋的 (adj.)** — 对过去的某段经历感到依依不舍
  - "She felt **nostalgic** about the team that built the first version of the product."

### 168. outraged
- **义项 1: 震怒的 (adj.)** — 因为严重的不公正而极度愤怒
  - "The engineering team was **outraged** by the decision to cut QA resources."
- **义项 2: 气愤的 (adj.)** — 对某事感到强烈的愤怒
  - "Customers were **outraged** when the security breach was revealed."
- **义项 3: 愤怒抗议的 (adj.)** — 表达强烈的反对和愤怒
  - "The developers were **outraged** that the code review process was being bypassed."

### 169. overwhelmed
- **义项 1: 不堪重负的 (adj.)** — 因为事情太多而承受不住
  - "The support team was **overwhelmed** by the volume of incident reports."
- **义项 2: 充满感情的 (adj.)** — 被强烈情感冲击
  - "I was **overwhelmed** by the positive feedback on my architecture proposal."
- **义项 3: 被压垮的 (adj.)** — 因为压力太大而无法应对
  - "The junior developer felt **overwhelmed** by the complexity of the codebase."

### 170. perplexed
- **义项 1: 困惑的 (adj.)** — 因为某事难以理解而感到迷惑
  - "The team was **perplexed** by the intermittent test failures."
- **义项 2: 费解的 (adj.)** — 找不到好的解释或原因
  - "The senior engineer was **perplexed** by the performance anomaly."
- **义项 3: 迷茫的 (adj.)** — 因为情况复杂而无法判断
  - "I was **perplexed** about which database technology to choose for the new project."

### 171. perturbed
- **义项 1: 不安的 (adj.)** — 因为某事不正常而感到担心
  - "The manager was **perturbed** by the sudden increase in error rates."
- **义项 2: 烦扰的 (adj.)** — 被持续的问题困扰
  - "She was **perturbed** by the lack of progress on the critical issue."
- **义项 3: 焦虑的 (adj.)** — 隐约感到某事不对
  - "The engineer was **perturbed** that the deployment had taken longer than expected."

### 172. resentful
- **义项 1: 怨恨的 (adj.)** — 因为感到不被公平对待而积怨
  - "The team grew **resentful** of the constant last-minute requirement changes."
- **义项 2: 不满的 (adj.)** — 对他人的成功或待遇感到不平衡
  - "He was **resentful** that his contribution was not recognized in the project summary."
- **义项 3: 耿耿于怀的 (adj.)** — 不能释怀已发生的不快
  - "She remained **resentful** about being passed over for the promotion."

### 173. skeptical
- **义项 1: 怀疑的 (adj.)** — 不相信某事是真的或有效的
  - "The architect was **skeptical** about the feasibility of the proposed timeline."
- **义项 2: 持怀疑态度的 (adj.)** — 倾向于质疑和挑战
  - "The team was **skeptical** of the vendor's performance claims."
- **义项 3: 不轻信的 (adj.)** — 需要看到证据才相信
  - "I remain **skeptical** until the performance benchmarks are confirmed."

### 174. solemn
- **义项 1: 严肃的 (adj.)** — 态度庄重不轻浮
  - "The incident review meeting was a **solemn** affair."
- **义项 2: 郑重的 (adj.)** — 正式且认真的
  - "The manager made a **solemn** promise to address the team's concerns."
- **义项 3: 沉静的 (adj.)** — 沉默且严肃的氛围
  - "A **solemn** silence fell over the team when the outage was announced."

### 175. somber
- **义项 1: 阴郁的 (adj.)** — 心情沉重、不愉快
  - "The mood in the engineering meeting was **somber** after the product launch failure."
- **义项 2: 暗淡的 (adj.)** — 色彩或光线阴暗
  - "The **somber** gray sky matched the team's mood after the bad news."
- **义项 3: 沉痛的 (adj.)** — 因失败或损失而感到悲痛
  - "The **somber** tone of the postmortem reflected the severity of the incident."

### 176. taken aback
- **义项 1: 吃惊的 (phr.)** — 被意外的事情震惊
  - "I was **taken aback** by the sudden decision to shut down the project."
- **义项 2: 猝不及防的 (phr.)** — 被突发情况弄得措手不及
  - "The team was **taken aback** by the severity of the security audit findings."
- **义项 3: 惊愕的 (phr.)** — 被出乎意料的行为或言论震撼
  - "She was **taken aback** when the manager criticized her work publicly."

### 177. torn
- **义项 1: 左右为难的 (adj.)** — 在两种选择之间难以决定
  - "I was **torn** between rewriting the module or patching the existing code."
- **义项 2: 纠结的 (adj.)** — 面对矛盾的感受或需求
  - "The team was **torn** between delivering on time and maintaining quality."
- **义项 3: 分裂的 (adj.)** — 在两个对立的方向之间拉扯
  - "She felt **torn** between her loyalty to the team and her personal career goals."

### 178. unsettled
- **义项 1: 不安的 (adj.)** — 内心感到不确定和不踏实
  - "The team felt **unsettled** by the constant organizational changes."
- **义项 2: 未解决的 (adj.)** — 问题或争议尚未解决
  - "Several **unsettled** questions remain about the future of the project."
- **义项 3: 不稳定的 (adj.)** — 局势或状态不稳定
  - "The **unsettled** market conditions made long-term planning difficult."

### 179. vexed
- **义项 1: 恼火的 (adj.)** — 被持续的问题搞得心烦意乱
  - "The engineer was **vexed** by the recurring connection timeout issue."
- **义项 2: 困扰的 (adj.)** — 被难以解决的问题长期困扰
  - "The **vexed** question of how to scale the database remained unanswered."
- **义项 3: 焦躁的 (adj.)** — 因为反复失败而感到烦躁
  - "I grew **vexed** with the deployment pipeline that kept failing for no apparent reason."

### 180. wary
- **义项 1: 警惕的 (adj.)** — 对潜在的威胁或风险保持警觉
  - "The team was **wary** of adopting a new technology without proper evaluation."
- **义项 2: 谨慎的 (adj.)** — 因为之前的教训而行事小心
  - "After the data loss incident, everyone was **wary** about running database migrations."
- **义项 3: 顾虑的 (adj.)** — 对某事抱有疑虑
  - "I am **wary** of promises that sound too good to be true."

### 181. wistful
- **义项 1: 惆怅的 (adj.)** — 对无法回到的过去感到淡淡忧伤
  - "The engineer felt **wistful** remembering the days when the codebase was small and simple."
- **义项 2: 向往的 (adj.)** — 渴望但不太可能得到
  - "She cast a **wistful** look at the job posting for the role she was passed over for."
- **义项 3: 愁闷的 (adj.)** — 因为失去而若有所思
  - "There was a **wistful** tone in his voice when he talked about the projects he had started."

### 182. zealous
- **义项 1: 热情的 (adj.)** — 对某事业或理念充满激情
  - "The new developer was **zealous** about following every coding standard to the letter."
- **义项 2: 热忱的 (adj.)** — 强烈地相信某事并投入大量精力
  - "The **zealous** advocate for test-driven development convinced the team to adopt it."
- **义项 3: 狂热的 (adj.)** — 过度投入以至于让人不适
  - "His **zealous** enforcement of code style rules sometimes annoyed the team."

### 183. adamant
- **义项 1: 坚决的 (adj.)** — 立场坚定不可动摇的
  - "The architect was **adamant** that the system should use event sourcing."
- **义项 2: 固执的 (adj.)** — 不肯改变自己的意见
  - "She was **adamant** about not deploying until all tests passed."
- **义项 3: 坚持的 (adj.)** — 毫不动摇地坚持某事
  - "The manager was **adamant** that the deadline could not be extended."

### 184. ambivalent
- **义项 1: 矛盾的 (adj.)** — 同时有两种矛盾的感受
  - "I felt **ambivalent** about the migration — it would improve scalability but increase complexity."
- **义项 2: 摇摆不定的 (adj.)** — 在两种感受之间摇摆
  - "The team was **ambivalent** about adopting the new framework."
- **义项 3: 模棱两可的 (adj.)** — 态度不明确的
  - "Her **ambivalent** response to the proposal left the team unsure of her position."

### 185. apathetic
- **义项 1: 冷漠的 (adj.)** — 对某事不关心、没兴趣
  - "The team was **apathetic** about attending yet another meeting about process changes."
- **义项 2: 无动于衷的 (adj.)** — 缺乏情感投入的
  - "The **apathetic** response to the security training was concerning."
- **义项 3: 漠不关心的 (adj.)** — 对重要的事情也不在意
  - "After the third reorganization, employees became **apathetic** about new initiatives."

### 186. candid
- **义项 1: 坦诚的 (adj.)** — 坦率地说出真实想法
  - "I appreciate your **candid** feedback on my performance."
- **义项 2: 直率的 (adj.)** — 不绕弯子的表达
  - "The **candid** conversation about the project's challenges was refreshing."
- **义项 3: 真诚的 (adj.)** — 不虚伪不做作的
  - "Her **candid** assessment of the situation helped the team make a better decision."

### 187. cynical
- **义项 1: 愤世嫉俗的 (adj.)** — 认为别人的动机都是自私的
  - "After years of failed initiatives, he became **cynical** about company-wide announcements."
- **义项 2: 怀疑人性的 (adj.)** — 不相信真诚或善意
  - "The **cynical** view is that the policy change was driven by cost-cutting, not by concern for employees."
- **义项 3: 冷嘲热讽的 (adj.)** — 用嘲讽的态度表达不信任
  - "His **cynical** comments during the meeting dampened the team's enthusiasm."

### 188. earnest
- **义项 1: 认真的 (adj.)** — 态度真诚且专注
  - "The **earnest** junior developer always took feedback seriously and improved quickly."
- **义项 2: 诚挚的 (adj.)** — 真诚有诚意的
  - "She made an **earnest** effort to understand the legacy codebase."
- **义项 3: 热切的 (adj.)** — 对某事情投入真心的
  - "His **earnest** desire to improve the team's processes was evident in every discussion."

### 189. fervent
- **义项 1: 热烈的 (adj.)** — 充满强烈情感的
  - "The developer was a **fervent** advocate for open-source software."
- **义项 2: 热切的 (adj.)** — 强烈的渴望或信念
  - "She had a **fervent** belief that clean code leads to better products."
- **义项 3: 炽热的 (adj.)** — 情感极其强烈的
  - "His **fervent** commitment to the project inspired the entire team."

### 190. flippant
- **义项 1: 轻率的 (adj.)** — 对严肃话题表现得不尊重
  - "His **flippant** remark about the outage angered the on-call team."
- **义项 2: 不当回事的 (adj.)** — 不把重要的事当回事
  - "The **flippant** attitude toward security protocols was unacceptable."
- **义项 3: 戏谑的 (adj.)** — 在不合适的场合开玩笑
  - "Her **flippant** response to the client's concern damaged the relationship."

### 191. forthright
- **义项 1: 直率的 (adj.)** — 说话直接不拐弯
  - "The manager appreciated the engineer's **forthright** assessment of the project's risks."
- **义项 2: 坦诚的 (adj.)** — 直接表达真实观点
  - "She was **forthright** about the challenges the team was facing."
- **义项 3: 坦白的 (adj.)** — 不隐瞒事实
  - "A **forthright** discussion about the budget constraints helped align expectations."

### 192. grudging
- **义项 1: 不情愿的 (adj.)** — 勉强地做某事
  - "The senior developer gave **grudging** approval to the new approach."
- **义项 2: 勉强的 (adj.)** — 虽然同意但心有不甘
  - "She offered a **grudging** apology for her behavior in the meeting."
- **义项 3: 吝啬的 (adj.)** — 勉强给予认可或赞扬
  - "He paid **grudging** respect to the competing team's achievement."

### 193. hesitant
- **义项 1: 犹豫的 (adj.)** — 不确定该不该做
  - "The team was **hesitant** to deploy on a Friday without full test coverage."
- **义项 2: 迟疑的 (adj.)** — 因为担心后果而犹豫不决
  - "I was **hesitant** to raise the issue because I did not want to delay the project."
- **义项 3: 有顾虑的 (adj.)** — 对某事感到不确定或不放心
  - "She was **hesitant** about using a new database without a proper benchmark."

### 194. incredulous
- **义项 1: 难以置信的 (adj.)** — 因为太惊讶而不敢相信
  - "The team was **incredulous** when they heard the project was canceled."
- **义项 2: 怀疑的 (adj.)** — 认为某事不太可能是真的
  - "I was **incredulous** that the fix was as simple as changing one line of code."
- **义项 3: 震惊的 (adj.)** — 因为意外而目瞪口呆
  - "She was **incredulous** at the suggestion that the system had no monitoring."

### 195. noncommittal
- **义项 1: 不表态的 (adj.)** — 拒绝承诺或表明立场
  - "The manager remained **noncommittal** when asked about the promotion timeline."
- **义项 2: 含糊的 (adj.)** — 不愿意给出明确回答
  - "Her **noncommittal** response frustrated the team's planning efforts."
- **义项 3: 回避的 (adj.)** — 故意避免表达明确意见
  - "The stakeholder was **noncommittal** during the requirements review."

### 196. patronizing
- **义项 1: 居高临下的 (adj.)** — 用高人一等的态度说话
  - "His **patronizing** tone during the code review offended the junior developer."
- **义项 2: 屈尊的 (adj.)** — 表现出自己高人一等的优越感
  - "The **patronizing** attitude of treating non-technical stakeholders as less capable was counterproductive."
- **义项 3: 恩赐态度的 (adj.)** — 假装好心实则看不起
  - "Her **patronizing** explanation of the basic concept made everyone uncomfortable."

### 197. condescending
- **义项 1: 傲慢的 (adj.)** — 认为自己比别人高一等
  - "His **condescending** remarks about the team's technical skills damaged morale."
- **义项 2: 贬低人的 (adj.)** — 用轻蔑的态度对待别人
  - "The **condescending** way he explained the simple concept was insulting."
- **义项 3: 居高临下的 (adj.)** — 表现出优越感的不尊重态度
  - "She had a **condescending** habit of finishing other people's sentences."

### 198. sarcastic
- **义项 1: 讽刺的 (adj.)** — 用反话表达批评或嘲笑
  - "His **sarcastic** comment about the 'brilliant' architecture decision was not appreciated."
- **义项 2: 挖苦的 (adj.)** — 带刺的幽默或批评
  - "The **sarcastic** tone of the retrospective made it hard to have a productive discussion."
- **义项 3: 讥讽的 (adj.)** — 用表面赞扬实际批评的方式说话
  - "She made a **sarcastic** remark about how 'well' the deployment went."

### 199. self-deprecating
- **义项 1: 自嘲的 (adj.)** — 拿自己的缺点或失败开玩笑
  - "His **self-deprecating** humor about the deployment failure lightened the mood."
- **义项 2: 自谦的 (adj.)** — 贬低自己来显得亲切
  - "The **self-deprecating** remark about her coding skills was appreciated by the new team members."
- **义项 3: 自我调侃的 (adj.)** — 缓和气氛的自我批评
  - "A **self-deprecating** comment can be an effective way to acknowledge mistakes without being defensive."

### 200. taken aback
- **义项 1: 惊愕的 (phr.)** — 被意外事件震惊
  - "I was **taken aback** by the sudden decision to shut down the project."
- **义项 2: 猝不及防的 (phr.)** — 被突发情况弄得措手不及
  - "The team was **taken aback** by the severity of the security audit findings."
- **义项 3: 惊诧的 (phr.)** — 被出乎意料的行为或言论震撼
  - "She was **taken aback** when the manager criticized her work publicly."

---

### Group 5: Negotiation, Risk & Decision Nouns（谈判风险与决策名词）

---

### 201. trade-off
- **义项 1: 权衡取舍 (n.)** — 在同等的价值之间做出的取舍
  - "There is a **trade-off** between consistency and availability in distributed systems."
- **义项 2: 折中方案 (n.)** — 放弃某物以换取另一物的安排
  - "Every architectural decision involves a **trade-off** between different quality attributes."
- **义项 3: 交换 (n.)** — 用一样东西换另一样
  - "The **trade-off** for higher performance was increased memory usage."

### 202. compromise
- **义项 1: 妥协 (n.)** — 双方让步达成的协议
  - "The team reached a **compromise** between delivery speed and code quality."
- **义项 2: 折中方案 (n.)** — 不完美但双方都能接受的方案
  - "The design was a **compromise** between the frontend and backend teams."
- **义项 3: 损害 (v.)** — 降低标准或安全
  - "We should never **compromise** on security for the sake of convenience."

### 203. concession
- **义项 1: 让步 (n.)** — 在谈判中做出的让步
  - "The vendor made several **concessions** on pricing after extended negotiation."
- **义项 2: 承认 (n.)** — 承认某事属实
  - "The manager's **concession** that the timeline was unrealistic was a relief."
- **义项 3: 特许权 (n.)** — 在特定场所经营的许可
  - "The company was granted a **concession** to operate in the special economic zone."

### 204. leverage
- **义项 1: 杠杆作用 (n.)** — 利用某物来增加影响力的方式
  - "The team used the successful prototype as **leverage** in the budget negotiation."
- **义项 2: 利用 (v.)** — 有效利用资源或优势
  - "We should **leverage** the existing infrastructure rather than building from scratch."
- **义项 3: 影响力 (n.)** — 能影响他人或局势的能力
  - "The scarcity of senior engineers gave the team **leverage** in salary negotiations."

### 205. bargaining power
- **义项 1: 议价能力 (n.)** — 在谈判中影响价格或条件的能力
  - "The company's unique technology gave it significant **bargaining power** in the acquisition talks."
- **义项 2: 谈判筹码 (n.)** — 谈判中可以用来争取利益的优势
  - "Having multiple job offers increases your **bargaining power** during salary negotiations."
- **义项 3: 博弈优势 (n.)** — 在竞争中掌控局面的能力
  - "The open-source community's **bargaining power** forced the company to change its licensing terms."

### 206. deadlock
- **义项 1: 僵局 (n.)** — 双方都不让步的僵持状态
  - "The negotiation reached a **deadlock** when neither side would compromise."
- **义项 2: 死锁 (n.)** — 计算机中两个进程互相等待资源的状况
  - "A database **deadlock** occurred when two transactions each held a lock the other needed."
- **义项 3: 停滞 (n.)** — 完全无法推进的状态
  - "The project was in a **deadlock** due to conflicting architectural opinions."

### 207. stalemate
- **义项 1: 僵局 (n.)** — 双方都无法推进的局面
  - "The debate about microservices versus monolith ended in a **stalemate**."
- **义项 2: 相持不下 (n.)** — 没有任何一方能占上风
  - "The **stalemate** between the design and engineering teams delayed the project."
- **义项 3: 死胡同 (n.)** — 无法继续前进的状态
  - "The negotiation reached a **stalemate** over the intellectual property clause."

### 208. impasse
- **义项 1: 死局 (n.)** — 完全无法解决的困境
  - "The contract negotiation reached an **impasse** over the liability terms."
- **义项 2: 僵局 (n.)** — 无法突破的谈判瓶颈
  - "The team was at an **impasse** — neither architecture option was clearly better."
- **义项 3: 绝境 (n.)** — 没有出路的情况
  - "The project had reached an **impasse** with no clear path forward."

### 209. breakthrough
- **义项 1: 突破 (n.)** — 解决长期问题的重大进展
  - "The team made a **breakthrough** in optimizing the database query performance."
- **义项 2: 突破性发现 (n.)** — 重大的科学或技术发现
  - "The **breakthrough** in chip design led to a tenfold improvement in processing speed."
- **义项 3: 破局 (n.)** — 打破僵局的关键进展
  - "The senior engineer's insight was the **breakthrough** the team needed to solve the bug."

### 210. consensus
- **义项 1: 共识 (n.)** — 团队成员普遍同意的看法
  - "After hours of discussion, the team reached a **consensus** on the architecture approach."
- **义项 2: 一致意见 (n.)** — 集体达成的共同立场
  - "There was a general **consensus** that the project needed more resources."
- **义项 3: 共识算法 (n.)** — 分布式系统中达成一致的算法
  - "The distributed database uses the Raft **consensus** protocol for leader election."

### 211. dissent
- **义项 1: 异议 (n.)** — 与主流意见不同的观点
  - "There was some **dissent** within the team about the adoption of the new framework."
- **义项 2: 反对 (n.)** — 对某决定或政策不同意
  - "The proposal was approved despite several members expressing **dissent**."
- **义项 3: 意见分歧 (n.)** — 对某个话题的不同看法
  - "Healthy **dissent** during the design review led to a better solution."

### 212. unanimity
- **义项 1: 全体一致 (n.)** — 所有人都同意
  - "The decision to delay the release was made with **unanimity**."
- **义项 2: 无异议 (n.)** — 没有任何反对意见
  - "The architecture proposal was approved with remarkable **unanimity**."
- **义项 3: 一致同意 (n.)** — 所有参与者持相同立场
  - "Achieving **unanimity** on the technology stack was easier than expected."

### 213. majority
- **义项 1: 多数 (n.)** — 超过半数的人员或票数
  - "The **majority** of the team voted in favor of the continuous deployment approach."
- **义项 2: 大半 (n.)** — 占总体的大部分
  - "The **majority** of the production incidents were caused by configuration changes."
- **义项 3: 多数派 (n.)** — 投票中的多数群体
  - "The **majority** decided that the sprint should focus on technical debt reduction."

### 214. plurality
- **义项 1: 相对多数 (n.)** — 票数最多但未超过半数
  - "The option to rewrite the system received a **plurality** but not a majority of the votes."
- **义项 2: 多元性 (n.)** — 多种不同的存在
  - "The **plurality** of opinions in the design discussion made the final decision harder."
- **义项 3: 复数状态 (n.)** — 多个而非一个的状态
  - "A **plurality** of approaches was considered before settling on the final design."

### 215. quorum
- **义项 1: 法定人数 (n.)** — 做决定所需的最低出席人数
  - "The architecture review could not proceed because there was no **quorum**."
- **义项 2: 多数节点 (n.)** — 分布式系统中达成决定所需的最少节点数
  - "The database requires a **quorum** of nodes to agree before committing a write."
- **义项 3: 投票基数 (n.)** — 有效投票的最低人数门槛
  - "We need a **quorum** of at least five members to make the decision binding."

### 216. mandate
- **义项 1: 授权 (n.)** — 被授予的权力或职责
  - "The team was given a **mandate** to migrate all services to the cloud by year end."
- **义项 2: 命令 (n.)** — 必须执行的正式指令
  - "The security **mandate** required all passwords to be rotated within 30 days."
- **义项 3: 委任 (v.)** — 授权某人做某事
  - "The board **mandated** a company-wide review of data privacy practices."

### 217. veto
- **义项 1: 否决权 (n.)** — 单方面否决提议的权力
  - "The chief architect has a **veto** over any technology selection."
- **义项 2: 否决 (v.)** — 单方面反对或禁止
  - "The security team **vetoed** the use of the vulnerable library."
- **义项 3: 行使否决 (n.)** — 否决某提议的行为
  - "His **veto** of the proposal surprised the rest of the team."

### 218. sanction
- **义项 1: 制裁 (n.)** — 对违反规则的行为施加的惩罚
  - "The company faced **sanctions** for violating data protection regulations."
- **义项 2: 批准 (v.)** — 正式允许或认可
  - "The committee **sanctioned** the use of the new framework after the trial period."
- **义项 3: 处罚 (n.)** — 针对违规的正式惩罚
  - "The **sanctions** for pushing directly to the main branch include a code review requirement."

### 219. embargo
- **义项 1: 禁运 (n.)** — 禁止某类商品或技术的出口
  - "The technology **embargo** prevented the company from selling its software in certain countries."
- **义项 2: 封锁期 (n.)** — 信息发布前不能公开的期限
  - "The product announcement is under **embargo** until next Monday."
- **义项 3: 禁令 (n.)** — 正式禁止某行为
  - "The company imposed an **embargo** on new feature development until the performance issues were resolved."

### 220. moratorium
- **义项 1: 暂停 (n.)** — 在某前暂停某活动的正式决定
  - "The team declared a **moratorium** on new feature development to focus on technical debt."
- **义项 2: 延期 (n.)** — 暂时搁置某决定
  - "The board called for a **moratorium** on the restructuring plan until the review was complete."
- **义项 3: 冻结 (n.)** — 正式停止某活动一段时间
  - "A **moratorium** was placed on hiring until the budget was finalized."

### 221. ultimatum
- **义项 1: 最后通牒 (n.)** — 要求对方在限期内接受条件否则承担后果的最后声明
  - "The client issued an **ultimatum**: fix the critical bugs within 48 hours or cancel the contract."
- **义项 2: 最后期限要求 (n.)** — 带有威胁意味的最后条件
  - "The manager gave the team an **ultimatum**: meet the deadline or the project would be reassigned."
- **义项 3: 强制要求 (n.)** — 必须接受否则有严重后果的条件
  - "The security team's **ultimatum** was to patch the vulnerability within 24 hours."

### 222. precondition
- **义项 1: 前提条件 (n.)** — 某事发生前必须满足的条件
  - "Successful load testing is a **precondition** for the production release."
- **义项 2: 先决条件 (n.)** — 做某事之前必须达到的状态
  - "A security audit is a **precondition** for deploying the new service."
- **义项 3: 前置条件 (n.)** — 编程中函数调用前必须为真的条件
  - "The function's **precondition** is that the input array must not be empty."

### 223. prerequisite
- **义项 1: 先修课程 (n.)** — 学习高级课程前必须完成的课程
  - "A course in networking is a **prerequisite** for the distributed systems class."
- **义项 2: 必要条件 (n.)** — 做某事前必须具备的条件
  - "Experience with microservices is a **prerequisite** for the senior architect role."
- **义项 3: 必备条件 (n.)** — 必须先行存在的事物
  - "A stable API specification is a **prerequisite** for starting the frontend development."

### 224. stipulation
- **义项 1: 规定条款 (n.)** — 合同或协议中的具体条件
  - "The contract includes a **stipulation** that all code must pass security review."
- **义项 2: 约定条件 (n.)** — 双方同意的具体要求和限制
  - "The **stipulation** that the system must handle 10,000 concurrent users was non-negotiable."
- **义项 3: 明文要求 (n.)** — 明确规定的条件
  - "One **stipulation** of the agreement was that the source code remain open source."

### 225. provision
- **义项 1: 条款 (n.)** — 法律或合同中的具体规定
  - "The **provision** regarding data retention was carefully reviewed by the legal team."
- **义项 2: 供应 (n.)** — 提供必要的资源
  - "The **provision** of adequate testing environments is critical for quality assurance."
- **义项 3: 部署 (v.)** — 配置并提供资源
  - "We **provisioned** new servers to handle the increased traffic."

### 226. clause
- **义项 1: 条款 (n.)** — 合同中的具体条文
  - "The confidentiality **clause** prohibits sharing proprietary information."
- **义项 2: 从句 (n.)** — 语法中包含主语和谓语的句子成分
  - "The sentence contains a dependent **clause** that cannot stand alone."
- **义项 3: 分句 (n.)** — 法律文件中的分别规定
  - "The indemnification **clause** protects the company from liability."

### 227. contingency
- **义项 1: 应急方案 (n.)** — 为应对可能的问题而准备的预案
  - "We have a **contingency** plan in case the primary data center goes offline."
- **义项 2: 应急预算 (n.)** — 为意外情况预留的资金
  - "The project budget includes a 15 percent **contingency** for unforeseen issues."
- **义项 3: 偶发事件 (n.)** — 可能发生但不一定发生的情况
  - "We must prepare for every **contingency** during the deployment."

### 228. liability
- **义项 1: 法律责任 (n.)** — 法律上应承担的责任
  - "The company accepted **liability** for the data breach."
- **义项 2: 负债 (n.)** — 财务报表中的债务
  - "The company's **liabilities** exceeded its assets."
- **义项 3: 不利因素 (n.)** — 对某人或某物不利的条件或特质
  - "The legacy codebase is a **liability** that slows down the development team."

### 229. indemnity
- **义项 1: 赔偿 (n.)** — 对损失或损害的经济补偿
  - "The contract includes an **indemnity** clause that protects against financial losses."
- **义项 2: 免责 (n.)** — 免除责任的法律保护
  - "The software vendor offered **indemnity** against copyright infringement claims."
- **义项 3: 保障 (n.)** — 免受损失的保护
  - "The **indemnity** agreement ensures the contractor is not held liable for project delays."

### 230. warranty
- **义项 1: 保修 (n.)** — 产品在特定期限内免费维修的保证
  - "The server comes with a three-year **warranty** covering hardware failures."
- **义项 2: 保证 (n.)** — 对产品质量或性能的承诺
  - "The software **warranty** guarantees the product will function as documented."
- **义项 3: 担保 (n.)** — 对某事真实性或质量的保证
  - "The **warranty** period for the commercial license is one year."

### 231. guarantee
- **义项 1: 保证 (n.)** — 对某事结果的承诺
  - "There is no **guarantee** that the migration will be completed on time."
- **义项 2: 保修 (n.)** — 对产品质量的明确承诺
  - "The product comes with a money-back **guarantee** if not satisfied."
- **义项 3: 担保 (v.)** — 为某事的结果负责
  - "We cannot **guarantee** that the system will be 100 percent available at all times."

### 232. assurance
- **义项 1: 保证 (n.)** — 为了让别人放心而做出的承诺
  - "The manager gave his **assurance** that the project would receive adequate resources."
- **义项 2: 信心 (n.)** — 对某事的自信或确定
  - "The successful test run gave the team **assurance** that the fix was working."
- **义项 3: 保险 (n.)** — 与保险相关的保障
  - "Quality **assurance** is an essential part of the software development lifecycle."

### 233. safeguard
- **义项 1: 保护措施 (n.)** — 为防止问题而采取的措施
  - "The deployment pipeline includes multiple **safeguards** to prevent human error."
- **义项 2: 保障 (v.)** — 保护某人或某事免受伤害
  - "The security protocol **safeguards** sensitive customer data."
- **义项 3: 安全装置 (n.)** — 物理或逻辑上的安全机制
  - "We implemented a **safeguard** that prevents accidental deletion of production data."

### 234. precaution
- **义项 1: 预防措施 (n.)** — 为防止坏事发生而提前采取的行动
  - "We took the **precaution** of backing up the database before the migration."
- **义项 2: 防范 (n.)** — 为了安全而事先准备的措施
  - "The team took every **precaution** to minimize the risk of data loss."
- **义项 3: 安全措施 (n.)** — 标准的安全规程
  - "As a **precaution**, all external access to the system was temporarily disabled."

### 235. deterrent
- **义项 1: 威慑因素 (n.)** — 阻止某人做某事的因素
  - "The strict code review process served as a **deterrent** against introducing buggy code."
- **义项 2: 遏制物 (n.)** — 用来阻止不良行为的措施
  - "The automatic rollback mechanism is a **deterrent** against deploying untested changes."
- **义项 3: 妨碍 (n.)** — 使某人不敢做某事的东西
  - "The high cost of the tool was a **deterrent** to its adoption."

### 236. incentive
- **义项 1: 激励 (n.)** — 鼓励某人做某事的东西
  - "The company offered a bonus as an **incentive** for completing the project on time."
- **义项 2: 动机 (n.)** — 促使某人采取行动的因素
  - "The **incentive** for adopting the new framework was improved developer productivity."
- **义项 3: 诱因 (n.)** — 刺激某人行动的东西
  - "There is little **incentive** for the team to refactor code that is already working."

### 237. disincentive
- **义项 1: 抑制因素 (n.)** — 阻止某人做某事的因素
  - "The lengthy approval process was a **disincentive** for teams to propose changes."
- **义项 2: 障碍 (n.)** — 让人不想做某事的东西
  - "The lack of proper documentation was a **disincentive** for new contributors."
- **义项 3: 负激励 (n.)** — 鼓励不服从或不作为的因素
  - "The overtime policy created a **disincentive** to work efficiently."

### 238. catalyst
- **义项 1: 催化剂 (n.)** — 加速过程但本身不消耗的物质
  - "The enzyme acts as a **catalyst** in the chemical reaction."
- **义项 2: 推动因素 (n.)** — 加速变化或事件发生的人或事物
  - "The security audit was the **catalyst** for improving the company's security practices."
- **义项 3: 触发点 (n.)** — 引发重大变化的导火索
  - "The hiring of the new CTO was the **catalyst** for the technology transformation."

### 239. impediment
- **义项 1: 障碍 (n.)** — 阻碍进展的事物
  - "The lack of API documentation was a major **impediment** to the integration work."
- **义项 2: 妨碍 (n.)** — 使进程变慢或受阻
  - "The complex approval process is an **impediment** to rapid deployment."
- **义项 3: 言语障碍 (n.)** — 身体上的语言障碍
  - "He has a speech **impediment** but communicates very clearly through writing."

### 240. hindrance
- **义项 1: 阻碍 (n.)** — 妨碍进展的人或物
  - "The outdated hardware was a **hindrance** to improving system performance."
- **义项 2: 干扰 (n.)** — 使人不能专注的因素
  - "Constant context switching was a **hindrance** to the team's productivity."
- **义项 3: 绊脚石 (n.)** — 阻止前进的因素
  - "The lack of a clear ownership model proved to be a **hindrance** to the project."

### 241. obstruction
- **义项 1: 阻塞 (n.)** — 阻挡通道或流动物体
  - "There was an **obstruction** in the network path that caused packet loss."
- **义项 2: 阻碍 (n.)** — 故意阻止进程
  - "The manager's refusal to approve the budget was an **obstruction** to the project's progress."
- **义项 3: 妨碍行为 (n.)** — 法律上妨碍执法或司法的行为
  - "Deleting evidence was considered **obstruction** of justice."

### 242. bottleneck
- **义项 1: 瓶颈 (n.)** — 限制系统吞吐量的环节
  - "The database query was the main **bottleneck** in the request pipeline."
- **义项 2: 制约因素 (n.)** — 限制整体效率的因素
  - "The manual approval process was a **bottleneck** in the deployment pipeline."
- **义项 3: 拥堵点 (n.)** — 交通或流程中的拥堵点
  - "The single-lane road has become a **bottleneck** during rush hour."

### 243. constraint
- **义项 1: 约束 (n.)** — 限制行动或选择的因素
  - "Time is our biggest **constraint** on this project."
- **义项 2: 限制条件 (n.)** — 必须遵守的规则或边界
  - "Budget **constraints** prevented us from hiring additional engineers."
- **义项 3: 制约 (n.)** — 技术上或资源上的局限
  - "The database latency **constraint** influenced our caching strategy."

### 244. limitation
- **义项 1: 局限性 (n.)** — 内在的不足或限制
  - "Every technology has its **limitations** and you need to understand them."
- **义项 2: 限制 (n.)** — 人为设定的界限
  - "There is a **limitation** on the number of concurrent connections."
- **义项 3: 缺陷 (n.)** — 能力或功能上的不足
  - "The **limitation** of the current approach is its inability to handle real-time data."

### 245. restriction
- **义项 1: 限制 (n.)** — 正式或官方的限制规则
  - "There are strict **restrictions** on who can access the production environment."
- **义项 2: 约束 (n.)** — 对行为或选择施加的限制
  - "The licensing **restriction** prohibits using the software in certain ways."
- **义项 3: 限定 (n.)** — 范围或程度上的限定
  - "The **restriction** on data storage locations is driven by regulatory compliance."

### 246. regulation
- **义项 1: 法规 (n.)** — 政府或监管机构制定的规则
  - "The new data privacy **regulation** requires companies to disclose how they use personal data."
- **义项 2: 管理规定 (n.)** — 组织内部的管理规则
  - "The security **regulation** requires all employees to use multi-factor authentication."
- **义项 3: 调节 (n.)** — 调节控制的过程
  - "The **regulation** of traffic through the load balancer ensures no server is overwhelmed."

### 247. compliance
- **义项 1: 合规 (n.)** — 遵守法律法规的行为
  - "The system must pass a security audit to ensure **compliance** with industry standards."
- **义项 2: 遵从 (n.)** — 遵守规则或要求
  - "**Compliance** with the coding standards is enforced through automated linting."
- **义项 3: 服从 (n.)** — 按要求行事
  - "The company's **compliance** with the new regulation was verified by an external auditor."

### 248. adherence
- **义项 1: 遵守 (n.)** — 严格遵守规则或标准
  - "Strict **adherence** to the coding standards improved code quality significantly."
- **义项 2: 坚持 (n.)** — 忠实于某原则或信念
  - "The team's **adherence** to Agile principles helped them deliver consistently."
- **义项 3: 粘附 (n.)** — 物理上的附着
  - "The **adherence** of the coating to the metal surface was tested under extreme conditions."

### 249. enforcement
- **义项 1: 执行 (n.)** — 强制履行规则或法律
  - "The **enforcement** of security policies is the responsibility of the IT department."
- **义项 2: 实施 (n.)** — 确保规则被遵守的过程
  - "Automated **enforcement** of code formatting rules saves time in code reviews."
- **义项 3: 强制 (n.)** — 通过权威强制某事发生
  - "The **enforcement** of the new compliance requirements starts next quarter."

### 250. exemption
- **义项 1: 豁免 (n.)** — 免除某些规则或义务的许可
  - "The legacy system was granted a temporary **exemption** from the security certification."
- **义项 2: 免税 (n.)** — 减免税款的许可
  - "The organization qualifies for a tax **exemption** as a non-profit entity."
- **义项 3: 例外 (n.)** — 排除在规则适用范围之外
  - "The team requested an **exemption** from the mandatory sprint schedule because of the migration."

---

### Group 6: Change, Growth & Progress Expressions（变化成长与进展表达）

---

### 251. evolve
- **义项 1: 进化 (v.)** — 逐渐发展到更高级或更复杂的状态
  - "The architecture **evolved** from a monolith to a microservices-based system over three years."
- **义项 2: 演变 (v.)** — 逐步变化
  - "The team's understanding of the problem **evolved** as they gathered more data."
- **义项 3: 成长 (v.)** — 某人或某事物发展成熟
  - "The startup **evolved** from a garage project into a publicly traded company."

### 252. mature
- **义项 1: 成熟 (v.)** — 变得成熟或完善
  - "The company's DevOps practices **matured** significantly over the last two years."
- **义项 2: 到期 (v.)** — 投资或保险达到可兑现的期限
  - "The bond **matures** in five years and can be redeemed at face value."
- **义项 3: 成熟的 (adj.)** — 已经成熟稳定的
  - "The **mature** framework has a large ecosystem and extensive documentation."

### 253. advance
- **义项 1: 前进 (v.)** — 向前推进
  - "The project **advanced** to the next phase after the design review was approved."
- **义项 2: 进步 (n.)** — 科学或技术上的进步
  - "The **advance** in machine learning has transformed how we approach data analysis."
- **义项 3: 提前 (adj.)** — 事先安排的
  - "We need **advance** notice of any changes to the deployment schedule."

### 254. progress
- **义项 1: 进展 (n.)** — 朝着目标推进的情况
  - "We made significant **progress** on the database migration this week."
- **义项 2: 进步 (v.)** — 逐渐取得进展
  - "The project is **progressing** according to the agreed timeline."
- **义项 3: 发展 (n.)** — 技能或能力的提升
  - "The junior developer has shown remarkable **progress** in learning the system."

### 255. regress
- **义项 1: 倒退 (v.)** — 退回到较不发达或较差的状态
  - "The system **regressed** after the last update and started crashing again."
- **义项 2: 回归 (v.)** — 回到之前的行为模式
  - "The team **regressed** to old habits after the new process was not enforced."
- **义项 3: 退化 (n.)** — 状态或质量的下降
  - "The **regress** in test coverage was concerning to the QA team."

### 256. deteriorate
- **义项 1: 恶化 (v.)** — 情况变得越来越糟
  - "The performance of the application **deteriorated** as the user base grew."
- **义项 2: 退化 (v.)** — 质量或状态持续下降
  - "The codebase **deteriorated** over time due to lack of refactoring."
- **义项 3: 变坏 (v.)** — 关系或状况变差
  - "The relationship between the two teams **deteriorated** after the incident."

### 257. stagnate
- **义项 1: 停滞 (v.)** — 停止进步或发展
  - "The project **stagnated** because no one wanted to make the final architecture decision."
- **义项 2: 不发展 (v.)** — 保持不变不前进
  - "The engineer's skills **stagnated** after years of working on the same legacy system."
- **义项 3: 不流动 (v.)** — 液体或空气静止不动
  - "The water in the pond **stagnated** and became full of algae."

### 258. plateau
- **义项 1: 达到平台期 (v.)** — 增长后进入稳定状态
  - "The team's productivity **plateaued** after the initial efficiency gains."
- **义项 2: 高原 (n.)** — 高海拔的平坦地形
  - "The Tibetan **Plateau** is known as the Roof of the World."
- **义项 3: 停滞期 (n.)** — 增长停顿的时期
  - "After rapid growth, the company hit a **plateau** and needed new strategies to expand."

### 259. peak
- **义项 1: 达到顶峰 (v.)** — 达到最高水平
  - "The server load **peaked** at 3 PM during the flash sale."
- **义项 2: 峰值 (n.)** — 最高点或最大量
  - "We need to ensure the system can handle traffic **peaks** during the holiday season."
- **义项 3: 巅峰的 (adj.)** — 处于最佳状态的
  - "The system was designed to handle **peak** load without degradation."

### 260. surge
- **义项 1: 激增 (v.)** — 突然大幅增加
  - "Traffic **surged** after the marketing campaign went live."
- **义项 2: 涌流 (n.)** — 突然的急剧增加
  - "The **surge** in user registrations overwhelmed the authentication service."
- **义项 3: 冲击 (n.)** — 电力的突然增加
  - "A power **surge** damaged several servers in the data center."

### 261. soar
- **义项 1: 飙升 (v.)** — 快速大幅上升
  - "Cloud computing costs **soared** after the company migrated all workloads."
- **义项 2: 高飞 (v.)** — 在空中高高飞翔
  - "The eagle **soared** above the mountains."
- **义项 3: 高涨 (v.)** — 情绪或信心大幅上升
  - "Team morale **soared** after the successful product launch."

### 262. plummet
- **义项 1: 暴跌 (v.)** — 快速大幅下降
  - "The stock price **plummeted** after the earnings report disappointed investors."
- **义项 2: 骤降 (v.)** — 急剧跌落
  - "The server response times **plummeted** when the caching layer failed."
- **义项 3: 垂直落下 (v.)** — 高速笔直地坠落
  - "The elevator **plummeted** several floors before the emergency brake engaged."

### 263. fluctuate
- **义项 1: 波动 (v.)** — 不规律地上下变化
  - "Database latency **fluctuates** throughout the day depending on the query load."
- **义项 2: 起伏 (v.)** — 在不同状态或水平之间变化
  - "The team size **fluctuated** between five and fifteen members over the course of the project."
- **义项 3: 摇摆 (v.)** — 不确定地变化
  - "The exchange rate **fluctuates** frequently, affecting our cloud hosting costs."

### 264. stabilize
- **义项 1: 稳定 (v.)** — 变得稳定不再波动
  - "The system performance **stabilized** after the database indexes were optimized."
- **义项 2: 使稳定 (v.)** — 使某事物变得稳定
  - "The team worked through the night to **stabilize** the production environment."
- **义项 3: 稳固 (v.)** — 站稳或变得稳固
  - "The patient's condition **stabilized** after the emergency treatment."

### 265. normalize
- **义项 1: 正常化 (v.)** — 使回到正常状态
  - "The error rate **normalized** after the configuration change was rolled back."
- **义项 2: 规范化 (v.)** — 按照标准调整数据或结构
  - "We need to **normalize** the database schema to reduce data redundancy."
- **义项 3: 常态化 (v.)** — 使某事变为正常和可接受的
  - "Remote work has **normalized** across the tech industry since 2020."

### 266. rebound
- **义项 1: 反弹 (v.)** — 从下降中恢复
  - "The stock price **rebounded** after the company announced strong quarterly results."
- **义项 2: 弹回 (v.)** — 撞击后弹回
  - "The ball **rebounded** off the wall and hit the window."
- **义项 3: 回升 (n.)** — 从低谷中的恢复
  - "The **rebound** in user engagement after the redesign was encouraging."

### 267. recover
- **义项 1: 恢复 (v.)** — 从失败或损坏中回到正常
  - "The service **recovered** within minutes after the failover kicked in."
- **义项 2: 康复 (v.)** — 身体恢复健康
  - "The server **recovered** from the crash after the automatic restart."
- **义项 3: 追回 (v.)** — 重新获得失去的东西
  - "We **recovered** the lost data from the daily backup."

### 268. adapt
- **义项 1: 适应 (v.)** — 调整以适应新条件
  - "The team quickly **adapted** to the new development workflow."
- **义项 2: 改编 (v.)** — 为特定目的修改
  - "We **adapted** the open-source library to meet our specific requirements."
- **义项 3: 改造 (v.)** — 将某物改装为其他用途
  - "The algorithm was **adapted** from the research paper for production use."

### 269. adjust
- **义项 1: 调整 (v.)** — 做小的改变以使更合适
  - "We **adjusted** the cache expiration time based on the traffic patterns."
- **义项 2: 调节 (v.)** — 校准或微调
  - "The developer **adjusted** the threshold value to reduce false positives."
- **义项 3: 适应 (v.)** — 逐渐适应新环境
  - "It took the team a few sprints to **adjust** to the new project management tool."

### 270. acclimate
- **义项 1: 适应 (v.)** — 逐渐适应新环境或条件
  - "New team members need time to **acclimate** to the company's coding standards."
- **义项 2: 服水土 (v.)** — 适应新的气候或环境
  - "The servers needed a few days to **acclimate** to the temperature in the new data center."
- **义项 3: 习惯 (v.)** — 逐渐变得习惯某事
  - "She quickly **acclimated** to the fast-paced environment of the startup."

### 271. assimilate
- **义项 1: 吸收 (v.)** — 吸收新知识或信息
  - "It takes time to **assimilate** all the details of a new codebase."
- **义项 2: 同化 (v.)** — 使某物成为整体的一部分
  - "The new tools were quickly **assimilated** into the team's workflow."
- **义项 3: 融入 (v.)** — 融入新的文化或群体
  - "The new hire **assimilated** into the team culture faster than expected."

### 272. integrate
- **义项 1: 整合 (v.)** — 将不同部分合并成整体
  - "We need to **integrate** the new authentication system with the existing user database."
- **义项 2: 融入 (v.)** — 使某人或某事融入更大的整体
  - "The new service must **integrate** seamlessly with the existing infrastructure."
- **义项 3: 集成 (v.)** — 将两个或多个系统连接在一起
  - "The API **integrates** the payment gateway with the e-commerce platform."

### 273. transition
- **义项 1: 过渡 (v.)** — 从一种状态转向另一种
  - "The company is **transitioning** from waterfall to Agile methodology."
- **义项 2: 转型 (n.)** — 从一种状态到另一种的变化过程
  - "The **transition** from monolith to microservices took eighteen months."
- **义项 3: 转换 (v.)** — 逐渐地改变
  - "The team **transitioned** the legacy users to the new platform over several months."

### 274. transform
- **义项 1: 转变 (v.)** — 彻底改变形式或性质
  - "The cloud migration **transformed** how the company delivers software."
- **义项 2: 改造 (v.)** — 使某物发生根本性变化
  - "The new architecture **transformed** the application's scalability."
- **义项 3: 转换 (v.)** — 数据格式或形式的转换
  - "The ETL pipeline **transforms** raw data into a structured format."

### 275. revolutionize
- **义项 1: 革命化 (v.)** — 彻底改变某事物
  - "Containerization **revolutionized** how we deploy and manage applications."
- **义项 2: 颠覆 (v.)** — 带来根本性的变革
  - "The new framework **revolutionized** frontend development."
- **义项 3: 彻底变革 (v.)** — 引起重大改变
  - "The adoption of AI has **revolutionized** the data analysis process."

### 276. disrupt
- **义项 1: 颠覆 (v.)** — 彻底改变某行业的运作方式
  - "The startup **disrupted** the traditional banking industry with its mobile-first approach."
- **义项 2: 中断 (v.)** — 打乱正常秩序或流程
  - "The network outage **disrupted** the company's operations for several hours."
- **义项 3: 破坏 (v.)** — 扰乱某系统的正常运作
  - "The new technology **disrupted** established market dynamics."

### 277. innovate
- **义项 1: 创新 (v.)** — 引入新方法或新思想
  - "The team **innovated** by combining two existing technologies in a novel way."
- **义项 2: 革新 (v.)** — 在现有基础上做出重大改进
  - "The company has consistently **innovated** in the field of distributed databases."
- **义项 3: 发明 (v.)** — 创造新事物
  - "The lab **innovated** a new approach to data compression."

### 278. pioneer
- **义项 1: 开创 (v.)** — 在某领域首先开始某事
  - "The company **pioneered** the use of event-driven architecture in the industry."
- **义项 2: 先驱 (n.)** — 在某领域首先探索的人
  - "She was a **pioneer** in the field of cloud-native application design."
- **义项 3: 开拓者 (n.)** — 开拓新领域的人或组织
  - "The startup was a **pioneer** in applying machine learning to cybersecurity."

### 279. culminate
- **义项 1: 达到顶点 (v.)** — 经过长期发展最终达到最高点
  - "The two-year migration effort **culminated** in the successful shutdown of the legacy system."
- **义项 2: 以……告终 (v.)** — 最终导致某种结果
  - "The disagreement **culminated** in a complete redesign of the architecture."
- **义项 3: 达到高潮 (v.)** — 事件或过程达到最激动人心的阶段
  - "The project **culminated** in a demo attended by the entire executive team."

### 280. manifest
- **义项 1: 显现 (v.)** — 清楚地显示或表现出来
  - "The performance issue **manifested** as slow response times during peak hours."
- **义项 2: 体现 (v.)** — 某种特性或品质的具象化
  - "The company's commitment to quality **manifests** in its thorough testing practices."
- **义项 3: 清单 (n.)** — 货物清单或乘客名单
  - "The **manifest** listed all the components that needed to be deployed."

### 281. emerge
- **义项 1: 出现 (v.)** — 从隐藏或模糊的状态中出现
  - "Several new patterns **emerged** from the analysis of the incident data."
- **义项 2: 新兴 (v.)** — 作为新事物出现
  - "New technologies are **emerging** that promise to solve the scalability problem."
- **义项 3: 显露 (v.)** — 真相或事实逐渐为人所知
  - "It **emerged** that the root cause was a configuration error all along."

### 282. subside
- **义项 1: 减退 (v.)** — 强度或严重程度逐渐降低
  - "The traffic spike **subsided** after the marketing campaign ended."
- **义项 2: 平息 (v.)** — 情绪或风波逐渐平息
  - "The tension in the team **subsided** after the incident was resolved."
- **义项 3: 沉降 (v.)** — 水位或地面下沉
  - "The floodwaters **subsided** after three days of no rain."

### 283. recede
- **义项 1: 退去 (v.)** — 逐渐后退或远离
  - "The floodwaters **receded** as the storm moved away."
- **义项 2: 变少 (v.)** — 记忆或影响逐渐消失
  - "The urgency of the problem **receded** after the temporary fix was applied."
- **义项 3: 撤退 (v.)** — 从某位置后退
  - "The glacier has **receded** significantly over the past decade."

### 284. diminish
- **义项 1: 减少 (v.)** — 变得较少或较小
  - "The performance gap between the two frameworks **diminished** after recent updates."
- **义项 2: 减弱 (v.)** — 强度或重要性降低
  - "The team's enthusiasm **diminished** as the project dragged on."
- **义项 3: 贬低 (v.)** — 降低某事物的价值或重要性
  - "We should not **diminish** the achievement of finishing the project on time."

### 285. amplify
- **义项 1: 放大 (v.)** — 增加某物的强度或大小
  - "The monitoring system **amplifies** the signal when an anomaly is detected."
- **义项 2: 增强 (v.)** — 使效果或影响增强
  - "The caching layer **amplifies** the performance benefit of the database optimization."
- **义项 3: 扩大 (v.)** — 使声音或信号变大
  - "The microphone **amplifies** the speaker's voice so everyone can hear."

### 286. accelerate
- **义项 1: 加速 (v.)** — 使某过程变快
  - "The new CI pipeline **accelerated** the build and test process by 50 percent."
- **义项 2: 促进 (v.)** — 加快某事物的发展和进程
  - "The investment **accelerated** the company's expansion into new markets."
- **义项 3: 增速 (v.)** — 速度增加
  - "The car **accelerated** rapidly when the driver pressed the pedal."

### 287. decelerate
- **义项 1: 减速 (v.)** — 使速度或节奏变慢
  - "The growth in user acquisition **decelerated** after the initial launch surge."
- **义项 2: 放缓 (v.)** — 进展速度降低
  - "The team decided to **decelerate** the release cadence to improve quality."
- **义项 3: 减慢 (v.)** — 物理速度降低
  - "The vehicle **decelerated** as it approached the traffic light."

### 288. taper off
- **义项 1: 逐渐减少 (phr.)** — 缓慢地、逐渐地减少
  - "User engagement **tapered off** after the initial excitement about the new feature."
- **义项 2: 递减 (phr.)** — 逐步变少直到停止
  - "The error reports **tapered off** after the hotfix was deployed."
- **义项 3: 逐渐减弱 (phr.)** — 活动或兴趣逐渐降低
  - "The discussion **tapered off** as the meeting approached its end."

### 289. phase out
- **义项 1: 逐步淘汰 (phr.)** — 分阶段地停止使用某物
  - "The company is **phasing out** the old authentication system over the next quarter."
- **义项 2: 逐步退出 (phr.)** — 有计划地逐步撤出
  - "We will **phase out** support for the legacy API version by the end of the year."
- **义项 3: 渐停 (phr.)** — 逐步停止生产或服务
  - "The manufacturer **phased out** the older model as the new version was launched."

### 290. wind down
- **义项 1: 逐渐结束 (phr.)** — 让某事物慢慢地停止
  - "The project is **winding down** as the team completes the final deliverables."
- **义项 2: 放松 (phr.)** — 从紧张状态中放松下来
  - "After the incident was resolved, the team **wound down** and debriefed."
- **义项 3: 逐步缩减 (phr.)** — 逐渐减少规模或强度
  - "The company **wound down** its operations in the region after the merger."

### 291. ramp up
- **义项 1: 增加 (phr.)** — 增加某事物的数量或强度
  - "We need to **ramp up** our testing efforts before the release."
- **义项 2: 加速 (phr.)** — 提高速度或效率
  - "The team **ramped up** development velocity to meet the deadline."
- **义项 3: 扩大规模 (phr.)** — 增加产能或能力
  - "The company **ramped up** production after the product received positive reviews."

### 292. scale up
- **义项 1: 扩容 (phr.)** — 增加系统容量以应对增长
  - "We **scaled up** the server fleet to handle the holiday traffic."
- **义项 2: 扩大 (phr.)** — 增加规模或范围
  - "The startup **scaled up** its engineering team from 10 to 50 people."
- **义项 3: 放大 (phr.)** — 增加某事物的量级
  - "The operation was **scaled up** to cover all regions."

### 293. scale down
- **义项 1: 缩减 (phr.)** — 减少规模或范围
  - "We **scaled down** the infrastructure after the traffic returned to normal levels."
- **义项 2: 缩小 (phr.)** — 减少影响或覆盖范围
  - "The project scope was **scaled down** to fit within the available budget."
- **义项 3: 降级 (phr.)** — 降低某事物的量级
  - "The operations were **scaled down** during the off-peak season."

### 294. roll out
- **义项 1: 推出 (phr.)** — 分阶段地发布或实施
  - "The company **rolled out** the new software to all employees over a period of two weeks."
- **义项 2: 逐步推广 (phr.)** — 让某事物逐步覆盖更多用户
  - "We **rolled out** the feature to 10 percent of users before the full launch."
- **义项 3: 上线 (phr.)** — 正式启动新产品或服务
  - "The new payment system will be **rolled out** across all regions by year end."

### 295. phase in
- **义项 1: 逐步引入 (phr.)** — 分阶段地开始使用某物
  - "The company is **phasing in** the new security protocols over the next quarter."
- **义项 2: 分期实施 (phr.)** — 有计划地逐步推行
  - "We will **phase in** the new coding standards gradually to avoid disrupting the team."
- **义项 3: 陆续上线 (phr.)** — 随时间逐步推出
  - "The new features will be **phased in** over the next three releases."

### 296. kick off
- **义项 1: 启动 (phr.)** — 正式开始某项目或活动
  - "The team **kicked off** the new sprint with a planning session."
- **义项 2: 开始 (phr.)** — 开始某过程或事件
  - "The project **kicked off** with a meeting that involved all stakeholders."
- **义项 3: 发起 (phr.)** — 发起一个活动或行动
  - "The hackathon was **kicked off** by a keynote from the CTO."

### 297. wrap up
- **义项 1: 结束 (phr.)** — 完成并结束某事
  - "We need to **wrap up** the remaining tasks before the end of the sprint."
- **义项 2: 总结 (phr.)** — 对某事件做最后的总结
  - "Let me **wrap up** the meeting by summarizing the key decisions."
- **义项 3: 收尾 (phr.)** — 完成某项目的最后部分
  - "The team **wrapped up** the release with a post-mortem and a celebration."

### 298. follow through
- **义项 1: 坚持到底 (phr.)** — 将某行动持续到完成
  - "The team **followed through** on their commitment to fix all critical bugs before the release."
- **义项 2: 履行承诺 (phr.)** — 按照承诺做事
  - "The manager **followed through** by providing the resources she had promised."
- **义项 3: 完成 (phr.)** — 将已经开始的事情做完
  - "It is not enough to start a good initiative; you must **follow through** on it."

### 299. carry out
- **义项 1: 执行 (phr.)** — 执行某任务或计划
  - "The team **carried out** the migration according to the plan."
- **义项 2: 实施 (phr.)** — 落实某决定或方案
  - "We **carried out** a thorough investigation of the incident."
- **义项 3: 进行 (phr.)** — 进行某个活动或过程
  - "The security team **carried out** a comprehensive audit of the system."

### 300. carry out
- **义项 1: 执行 (phr.)** — 执行某任务或计划
  - "The team **carried out** the migration according to the plan."
- **义项 2: 实施 (phr.)** — 落实某决定或方案
  - "We **carried out** a thorough investigation of the incident."
- **义项 3: 进行 (phr.)** — 进行某个活动或过程
  - "The security team **carried out** a comprehensive audit of the system."

---

## 3. Sentence-Making Practice

以下 10 个练习结合了本学期词汇和过去时态，要求使用复杂句结构。先自己写，再对照参考答案。

---

### 1. 描述：在进行部署的过程中，你注意到数据库迁移脚本有一个错误。用过去进行时 + when + 一般过去时的"打断"结构。

**参考答案:** "I **was deploying** the release when I **noticed** that the database migration script **had** a syntax error."
> （"was deploying" = 过去进行时，表示正在进行的背景动作；"noticed" = 一般过去时，表示突然发生的中断事件。宾语从句 "that the database migration script had a syntax error" 使用一般过去时 "had"——描述发现时的状态。）

---

### 2. 描述：团队 brainstorm 了几种方案之后，最后就一个兼顾性能和可维护性的方案达成了共识。用 before 从句 + that 定语从句。

**参考答案:** "We **brainstormed** several approaches before we **agreed** on a solution that **balanced** performance **with** maintainability."
> （主句 "We brainstormed" = 一般过去时。before 时间状语从句 "we agreed" = 一般过去时。that 引导的定语从句 "that balanced performance with maintainability" 修饰 "solution"。）

---

### 3. 你在 retro 上说：这个 sprint 最大的问题是团队没有及时同步信息，导致了一个 blocker。用一般过去时否定 + which 定语从句。

**参考答案:** "The biggest issue this sprint was that we **did not sync** early enough, **which caused** a critical **blocker** later in the cycle."
> （"did not sync" = 一般过去时否定。which 引导非限制性定语从句，指代前面整件事——"没有及时同步"这件事导致了 blocker。注意：主句用一般现在时 "is" 是因为"教训是什么"是客观事实。）

---

### 4. 你向经理报告：当用户投诉性能问题时，SRE 团队已经在调查根因了。用过去完成时 + when 时间状语从句。

**参考答案:** "When the customer **reported** the performance issue, the SRE team **had already been investigating** the root cause for two hours."
> （"had already been investigating" = 过去完成进行时，表示在 customer reported 之前就已经在进行了。主句动作发生在从句动作之前。when 从句用一般过去时 "reported"。）

---

### 5. 同事问你为什么没有按 schedule 发版。解释的原因是 scope 变了，而且需要重新跟 stakeholders 确认。用 because 原因状语从句 + 一般过去时。

**参考答案:** "I **did not** release on **schedule** because the **scope** **changed** at the last minute and we **needed** to reconfirm the timeline with the key **stakeholders**."
> （一般过去时否定：did not release。because 引导原因状语从句，内含两个并列的一般过去时动词："changed" 和 "needed"。"reconfirm the timeline with the key stakeholders" 是对"重新确认"的整体表达。）

---

### 6. 描述：在旅行途中，你的行李在转机时丢失了，但机场工作人员帮你找到了。用一般过去时 + but 并列句。

**参考答案:** "My **luggage** **was** lost during the connecting **flight**, but the **airport** staff **helped** me track it **down** and **returned** it to my **hotel**."
> （两个并列主句用 but 连接。第一句 "was lost" = 被动语态的一般过去时。第二句 "helped... and returned" = 两个并列动词，均为一般过去时。注意：track down 是短语动词，意为"追踪找到"。）

---

### 7. 你周末去了一家餐厅，菜品味道很好但价格很贵。用一般过去时 + although 让步状语从句。

**参考答案:** "I **went** to a new restaurant last weekend. The **food** **was delicious**, although the **price** **was** quite **expensive**."
> （"went" = 不规则动词 go 的过去式。although 引导让步状语从句——"虽然价格贵，但是好吃"。描述性的主系表结构 "was delicious" 和 "was expensive"。）

---

### 8. 描述：因为暴风雨，航班延误了三小时，你不得不在机场等待。用 because 原因状语 + 一般过去时。

**参考答案:** "The **storm** **caused** a three-hour **flight** delay, so I **had to wait** at the **airport** for a long time."
> （"caused" = 一般过去时。"had to" = have to 的过去式，表示"不得不"。so 连接因果关系的并列句。注意：delay 既是动词也是名词——这里作名词用。）

---

### 9. 你说：公司上线了一个 recycling 新项目，目标是减少办公室的浪费。用 that 定语从句 + 一般过去时。

**参考答案:** "The company **launched** a new **recycling** initiative that **aimed** to reduce waste in the office."
> （"launched" = 一般过去时。that 引导定语从句修饰 "initiative"。"aimed to" = 以……为目标。注意："reduce waste" = 减少浪费，不需要加冠词。）

---

### 10. 描述：客户反馈说产品质量有问题，但退货流程很麻烦。用 but 转折 + 一般过去时。

**参考答案:** "The customer **reported** that the **product** **quality** **was** poor, but the **return** process **was** too complicated."
> （"reported" = 一般过去时。that 引导宾语从句 "the product quality was poor"。but 连接转折关系。注意："quality" 在这里是名词，"poor quality" = 质量差。）

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
| read | __________ | __________ |
| go | __________ | __________ |
| get | __________ | __________ |

**参考答案：** wrote/written, built/built, sent/sent, made/made, ran/run, took/taken, saw/seen, gave/given, found/found, broke/broken, kept/kept, brought/brought, thought/thought, told/told, spoke/spoken, left/left, lost/lost, spent/spent, led/led, set/set, let/let, cut/cut, read/read, went/gone, got/gotten

**易错提醒：**
- run 的过去分词仍是 **run**（不是 ran）
- read 拼写不变但发音变为 /red/
- lead 的过去式是 **led**（不是 leaded）
- get 美式过去分词是 **gotten**，英式是 **got**

---

### 语法自我检测清单

**一般过去时：**
- [ ] 我知道规则动词三种 -ed 发音的区别（/t/, /d/, /ɪd/）
- [ ] 我记住了至少 25 个不规则动词的过去式
- [ ] 我能正确使用 "didn't + 动词原形"（不犯双重过去标记错误）
- [ ] 我能构建疑问句 "Did + 主语 + 动词原形 + ?"
- [ ] 我看到 yesterday / last week / ago 能条件反射使用一般过去时

**过去进行时：**
- [ ] 我知道 was/were 的搭配（I/he/she/it → was；we/you/they → were）
- [ ] 我能使用 "was/were V-ing + when + 一般过去时" 的打断结构
- [ ] 我能使用 "While + was/were V-ing + was/were V-ing" 的同时结构
- [ ] 我不对状态动词使用进行时（❌ was knowing，✅ knew）

**复杂句分析：**
- [ ] 我能识别 that 引导的宾语从句和定语从句
- [ ] 我能识别 when / while / before / after / because 引导的状语从句
- [ ] 我理解过去完成时（had done）表示"过去的过去"
- [ ] 我能逐词拆解包含 2-3 个从句的复杂句

**词汇 300：**
- [ ] 我至少掌握了 Group 1-2 各 30 个词汇的核心意思
- [ ] 我能理解架构设计、系统操作相关的动词
- [ ] 我能在合适场景中使用精准的形容词和情感表达
- [ ] 我了解谈判决策和时间进展相关的名词与表达

---

### 周末练习建议

**建议用时：** 周六 45 分钟 + 周日 45 分钟

**周六练习：写一段工作日志（30 分钟）**

用英语写一段 5-8 句话的日记，描述你这周某一天的工作和生活。要求：
- 至少使用 3 个一般过去时的句子——❌ "Today I deploy the fix." → ✅ "Today I **deployed** the fix."
- 至少使用 2 个过去进行时的句子——描述你正在做某事时发生了什么
- 使用本周学到的至少 5 个词汇（从 6 组中任选）
- 包含至少 1 个带 that 定语从句的句子

**示例：**
> "Yesterday was a busy day. In the morning, I **was reviewing** a pull request when the manager **asked** me to join an urgent meeting. The meeting was about the budget constraint for our Q3 project. We **brainstormed** several solutions and finally **agreed** on a plan that **balanced** cost with quality. After lunch, I **finished** the review and **left** the office at 6 PM."

写完后逐句检查：
- ✅每个过去时动词形式是否正确？（不规则动词查对照表）
- ✅进行时的句子是否真的需要强调"过程"？
- ✅从句的引导词是否使用正确？（that, when, while, because）

**周日练习：逐词分析挑战（30 分钟）**

从本周的 6 个复杂句拆解中任选 3 个句子：
1. 遮住中文翻译和拆解，自己尝试逐词分析
2. 标出每个词的语法角色（主语、谓语、宾语、定语、状语等）
3. 找出所有从句，说明每个从句的类型（时间状语从句、定语从句、宾语从句等）
4. 对照参考答案检查自己的分析是否正确

**额外挑战（15 分钟）：** 自己写 3 个包含至少两个从句的复杂句，主题为：
- 一个你设计过的系统或功能
- 一个工作中的沟通故事
- 一个你最近观察到的行业变化

写完后用本周学的语法标签（主语、谓语、宾语、状语从句等）标注你的句子。

**下周生存贴士：**
- 描述过去的事 → 条件反射用 Simple Past（90% 情况足够）
- 强调"正在……的时候突然……" → Past Continuous + when + Simple Past
- 想说"已经……之前就……了" → Past Perfect（had done）
- 分析复杂句 → 先找主谓宾主干，再找所有从句的引导词
- 30 个新词一天 → 不要背，要用。用新词写 2 个句子 > 背 10 遍

---

> **下周预告：** Week 4 将学习**将来时态**——be going to vs. will vs. Present Continuous for future，以及更多高频场景词汇。下周见。
