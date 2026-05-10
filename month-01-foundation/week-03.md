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

本周词汇分成 6 组，每组 50 个，涵盖沟通协作、商务名词、购物消费、饮食烹饪、旅行出行和自然环境六大场景。

---

### Group 1: Collaboration & Communication Verbs（协作沟通动词）

---

### 1. align
- **义项 1: 对齐/保持一致 (v.)** — 确保团队对目标有共同理解
  - "We need to **align** on the delivery timeline before the sprint starts."
- **义项 2: 调整一致 (v.)** — 使代码风格或架构保持一致
  - "We should **align** our code style with the team's ESLint rules."
- **义项 3: 与……结盟 (v.)** — 与某人或某团队达成合作共识
  - "The frontend team **aligned** with the design team on the new component library."

### 2. clarify
- **义项 1: 澄清/说明 (v.)** — 解释清楚模糊的内容
  - "Could you **clarify** the requirements for this user story?"
- **义项 2: 阐明观点 (v.)** — 让自己的想法更容易被理解
  - "Let me **clarify** what I meant — I am not saying we should rewrite everything."
- **义项 3: 理清情况 (v.)** — 弄清楚复杂状况
  - "We need to **clarify** the root cause before jumping to a solution."

### 3. escalate
- **义项 1: 升级问题 (v.)** — 将问题上报给更高级别的人
  - "If the incident is not resolved in 30 minutes, **escalate** it to the SRE team."
- **义项 2: 加剧恶化 (v.)** — 问题变得更严重
  - "The production issue **escalated** from a minor bug to a full outage within an hour."
- **义项 3: 扩大范围 (v.)** — 使某事的规模或严重性增加
  - "The scope of the project **escalated** after the client requested additional features."

### 4. prioritize
- **义项 1: 按优先级排序 (v.)** — 决定哪些任务先做
  - "We need to **prioritize** security fixes over new features this week."
- **义项 2: 优先处理 (v.)** — 把某件事放在最重要的位置
  - "The team **prioritized** performance optimization after user complaints."
- **义项 3: 分清主次 (v.)** — 在多个需求中识别真正重要的
  - "It is important to **prioritize** your tasks based on business impact."

### 5. delegate
- **义项 1: 委派任务 (v.)** — 将任务分配给团队成员
  - "As a tech lead, you need to **delegate** tasks instead of doing everything yourself."
- **义项 2: 授权 (v.)** — 将权限或职责交给别人
  - "The manager **delegated** the decision-making authority to senior engineers."
- **义项 3: 委托模式 (v.)** — 编程中将行为委托给另一个对象
  - "In this pattern, the parent component **delegates** event handling to the child."

### 6. brainstorm
- **义项 1: 头脑风暴 (v.)** — 集体自由讨论产生想法
  - "Let us **brainstorm** solutions for the database performance issue."
- **义项 2: 集思广益 (v.)** — 广泛收集各方意见
  - "We **brainstormed** several approaches before settling on the final design."
- **义项 3: 构思产生 (v.)** — 独自思考产生想法
  - "I need some quiet time to **brainstorm** ideas for the system design."

### 7. sync
- **义项 1: 同步信息 (v.)** — 互相更新信息保持一致
  - "Let us **sync** up after the meeting to discuss the next steps."
- **义项 2: 数据同步 (v.)** — 多设备间保持数据一致
  - "The mobile app **syncs** with the server every time the user goes online."
- **义项 3: 对齐进度 (v.)** — 确保各方对进度有共同认识
  - "We should **sync** with the QA team before the release."

### 8. onboard
- **义项 1: 入职引导 (v.)** — 帮助新成员了解团队和项目
  - "I spent the morning **onboarding** the new junior developer."
- **义项 2: 接入系统 (v.)** — 将新用户或客户接入系统
  - "The team is **onboarding** three new clients this quarter."
- **义项 3: 熟悉上手 (v.)** — 学习适应新工具
  - "It took me a week to **onboard** onto the new cloud infrastructure."

### 9. offload
- **义项 1: 分担任务 (v.)** — 将部分工作转移给他人
  - "I need to **offload** some of my tasks to free up time for the architecture review."
- **义项 2: 卸载负载 (v.)** — 将计算任务从主系统转移到其他系统
  - "The CDN **offloads** static asset delivery from the main server."
- **义项 3: 推卸责任 (v.)** — 把责任转给别人（略带负面）
  - "He tried to **offload** the blame for the missed deadline onto the QA team."

### 10. communicate
- **义项 1: 沟通交流 (v.)** — 传递信息或想法
  - "We need to **communicate** the schedule change to all stakeholders."
- **义项 2: 传达感情 (v.)** — 表达态度或情感
  - "She **communicated** her concerns clearly during the team meeting."
- **义项 3: 通信连接 (v.)** — 系统或设备间交换数据
  - "The microservices **communicate** with each other through REST APIs."

### 11. coordinate
- **义项 1: 协调安排 (v.)** — 组织各方协同工作
  - "The project manager **coordinated** the efforts of three different teams."
- **义项 2: 配合行动 (v.)** — 与他人配合完成某事
  - "We need to **coordinate** the deployment schedule with the DevOps team."
- **义项 3: 使协调 (v.)** — 调整使各部分协调一致
  - "The design and engineering teams **coordinated** their timelines for the release."

### 12. collaborate
- **义项 1: 协作合作 (v.)** — 与他人共同工作
  - "The frontend and backend teams **collaborated** closely on the API design."
- **义项 2: 联合创作 (v.)** — 共同创造某作品
  - "We **collaborated** with the design agency on the new landing page."
- **义项 3: 协同合作 (v.)** — 系统之间协同工作
  - "Multiple services **collaborate** to process a single user request."

### 13. negotiate
- **义项 1: 谈判协商 (v.)** — 通过讨论达成共识
  - "We **negotiated** the contract terms with the vendor for two weeks."
- **义项 2: 商议解决 (v.)** — 讨论解决分歧
  - "The team **negotiated** a compromise between delivery speed and code quality."
- **义项 3: 克服障碍 (v.)** — 巧妙通过或处理困难
  - "She **negotiated** her way through the complex approval process."

### 14. persuade
- **义项 1: 说服 (v.)** — 让某人接受你的观点
  - "I **persuaded** the team to adopt the new testing framework."
- **义项 2: 劝导 (v.)** — 通过说理让别人改变主意
  - "She **persuaded** the manager to extend the deadline by one week."
- **义项 3: 促使 (v.)** — 使某人做某事
  - "The data **persuaded** us to reconsider our architecture choice."

### 15. propose
- **义项 1: 提议建议 (v.)** — 正式提出方案
  - "I **proposed** a migration plan during the architecture review meeting."
- **义项 2: 求婚 (v.)** — 请求结婚（日常用法）
  - "He **proposed** to his girlfriend on their trip to Japan."
- **义项 3: 推荐 (v.)** — 提名或推荐人选
  - "She was **proposed** as the new tech lead for the platform team."

### 16. suggest
- **义项 1: 建议 (v.)** — 提出想法供人考虑
  - "I **suggest** we run a load test before the Black Friday sale."
- **义项 2: 暗示 (v.)** — 间接表明某事
  - "The error message **suggests** that the database connection is timing out."
- **义项 3: 推荐 (v.)** — 推荐某人做某事
  - "I **suggest** using TypeScript for this new project."

### 17. recommend
- **义项 1: 推荐 (v.)** — 认为某人/某事物好而推荐
  - "I **recommend** using a managed database service to reduce operational overhead."
- **义项 2: 建议做 (v.)** — 建议采取某个行动
  - "The security audit **recommends** enabling two-factor authentication."
- **义项 3: 推荐人选 (v.)** — 推荐某人担任某职位
  - "My manager **recommended** me for the senior engineer promotion."

### 18. advise
- **义项 1: 建议忠告 (v.)** — 给出专业意见
  - "I **advise** you to review the migration guide before upgrading."
- **义项 2: 通知告知 (v.)** — 正式通知某人（正式用法）
  - "Please be **advised** that the system will be down for maintenance tonight."
- **义项 3: 提供咨询 (v.)** — 以专家身份提供建议
  - "She **advises** several startups on cloud architecture."

### 19. agree
- **义项 1: 同意赞同 (v.)** — 持相同观点
  - "I **agree** with the proposed approach for the database migration."
- **义项 2: 达成一致 (v.)** — 双方就某事达成共识
  - "We **agreed** on a timeline for the project deliverables."
- **义项 3: 适合 (v.)** — 食物或气候适合某人
  - "Spicy food does not **agree** with me."

### 20. disagree
- **义项 1: 不同意 (v.)** — 持不同观点
  - "I **disagree** with the decision to skip unit tests for this module."
- **义项 2: 有分歧 (v.)** — 意见不统一
  - "The team **disagreed** on whether to use microservices or a monolith."
- **义项 3: 不一致 (v.)** — 数据或陈述不相符
  - "The test results **disagree** with the performance projections."

### 21. argue
- **义项 1: 争论辩论 (v.)** — 激烈讨论不同意的事
  - "The engineers **argued** about the best way to handle the edge case."
- **义项 2: 主张论证 (v.)** — 提出理由支持某观点
  - "She **argued** that we should rewrite the legacy module instead of patching it."
- **义项 3: 表明显示 (v.)** — 迹象显示
  - "The log patterns **argue** for a more thorough investigation."

### 22. discuss
- **义项 1: 讨论商议 (v.)** — 交换意见
  - "We need to **discuss** the incident response plan in the next team meeting."
- **义项 2: 详细论述 (v.)** — 深入探讨某个话题
  - "The article **discusses** the trade-offs between consistency and availability."
- **义项 3: 商议决策 (v.)** — 讨论以做出决定
  - "The team **discussed** several options before choosing the best one."

### 23. debate
- **义项 1: 辩论 (v.)** — 正式讨论正反方观点
  - "The architects **debated** the pros and cons of event-driven architecture."
- **义项 2: 反复思考 (v.)** — 内心权衡
  - "I **debated** whether to fix the bug now or wait for the next sprint."
- **义项 3: 争论 (v.)** — 公开争论某事
  - "The community **debated** the best practices for microservice boundaries."

### 24. present
- **义项 1: 演示展示 (v.)** — 向观众展示信息
  - "She **presented** the Q4 roadmap to the entire engineering organization."
- **义项 2: 提交呈交 (v.)** — 正式提交文件或方案
  - "We **presented** our findings to the stakeholders last Friday."
- **义项 3: 呈现表现 (v.)** — 表现出某种状态
  - "The system **presents** a user-friendly interface after the redesign."

### 25. report
- **义项 1: 报告汇报 (v.)** — 向上级或团队报告情况
  - "Please **report** any production issues to the on-call engineer immediately."
- **义项 2: 报道 (v.)** — 新闻或媒体报导
  - "TechCrunch **reported** that the startup raised 50 million dollars."
- **义项 3: 隶属汇报 (v.)** — 在组织架构中向某人汇报
  - "I **report** directly to the VP of Engineering."

### 26. brief
- **义项 1: 简要汇报 (v.)** — 简短告知最新情况
  - "Let me **brief** you on the current status of the incident."
- **义项 2: 作简报 (v.)** — 正式做简短介绍
  - "The PM **briefed** the team on the new feature requirements."
- **义项 3: 简要指示 (v.)** — 给予简短明确的指示
  - "The director **briefed** the security team before the audit."

### 27. summarize
- **义项 1: 总结概括 (v.)** — 将复杂信息简要说清楚
  - "To **summarize**, we need to address three critical issues before the release."
- **义项 2: 总结提炼 (v.)** — 提取要点
  - "She **summarized** the two-hour meeting into five key action items."
- **义项 3: 概述 (v.)** — 简要描述主要内容
  - "The abstract **summarizes** the key findings of the research paper."

### 28. document
- **义项 1: 记录文档 (v.)** — 将信息写入文档
  - "Please **document** the deployment steps in the team wiki."
- **义项 2: 书面记录 (v.)** — 以书面形式记录
  - "We need to **document** the root cause analysis for compliance purposes."
- **义项 3: 用文件证明 (v.)** — 提供证据或文件支持
  - "The test results **document** a 40 percent improvement in response time."

### 29. announce
- **义项 1: 宣布通知 (v.)** — 公开发布消息
  - "The CEO **announced** a company-wide reorganization last Monday."
- **义项 2: 宣告 (v.)** — 正式声明的行为
  - "The team **announced** the completion of the major infrastructure upgrade."
- **义项 3: 发布 (v.)** — 公开发表信息
  - "The company **announced** a new partnership with a cloud provider."

### 30. confirm
- **义项 1: 确认 (v.)** — 核实某事的真实性
  - "Can you **confirm** that the deployment completed successfully?"
- **义项 2: 确认安排 (v.)** — 确认计划不变
  - "Please **confirm** your availability for the sprint review meeting."
- **义项 3: 坚定 (v.)** — 加强信念或决心
  - "The successful test **confirmed** our hypothesis about the root cause."

### 31. verify
- **义项 1: 验证 (v.)** — 检查是否正确
  - "We need to **verify** the checksum before deploying the artifact."
- **义项 2: 核实 (v.)** — 确认某事的真实性
  - "The security team **verified** the identity of all external contractors."
- **义项 3: 证明 (v.)** — 通过证据证实
  - "The load test results **verified** that the system can handle a million concurrent users."

### 32. approve
- **义项 1: 批准同意 (v.)** — 正式同意某方案
  - "The tech lead **approved** my pull request after a thorough review."
- **义项 2: 核准 (v.)** — 官方授权
  - "The budget for the new project was **approved** by the finance department."
- **义项 3: 认可 (v.)** — 认为某事好或合适
  - "The client **approved** the design mockups on the first review."

### 33. reject
- **义项 1: 拒绝否决 (v.)** — 不同意接受
  - "The reviewer **rejected** my pull request because of insufficient test coverage."
- **义项 2: 驳回 (v.)** — 正式拒绝提议
  - "The architecture committee **rejected** the proposal to use a new database."
- **义项 3: 排斥 (v.)** — 身体或系统排斥外来物
  - "The server **rejected** the connection because the SSL certificate had expired."

### 34. request
- **义项 1: 请求要求 (v.)** — 正式请求某事
  - "I **requested** access to the production logs for the investigation."
- **义项 2: 请求给予 (v.)** — 请求获得某物
  - "The team **requested** additional resources for the upcoming sprint."
- **义项 3: 请求做某事 (v.)** — 请求允许做某事
  - "He **requested** to work remotely during the infrastructure migration."

### 35. assign
- **义项 1: 分配任务 (v.)** — 将任务分给某人
  - "The tech lead **assigned** me the database migration ticket."
- **义项 2: 指派角色 (v.)** — 指定某人担任某角色
  - "She was **assigned** as the incident commander for the outage."
- **义项 3: 赋值 (v.)** — 编程中将值赋给变量
  - "The function **assigns** the return value to a global variable."

### 36. schedule
- **义项 1: 安排时间 (v.)** — 为某事设定时间
  - "We **scheduled** the deployment for 2 AM on Sunday."
- **义项 2: 排期 (v.)** — 计划在某个时间点做某事
  - "The team **scheduled** three rounds of load testing before the launch."
- **义项 3: 预定 (v.)** — 预约或预定服务
  - "I **scheduled** a meeting with the stakeholders for next Wednesday."

### 37. cancel
- **义项 1: 取消 (v.)** — 决定某事不发生
  - "We had to **cancel** the release because of a critical security vulnerability."
- **义项 2: 删除标记 (v.)** — 标记为无效或作废
  - "The previous order was **canceled** and a new one was placed."
- **义项 3: 抵消 (v.)** — 相互抵消作用
  - "The positive and negative charges **cancel** each other out."

### 38. attend
- **义项 1: 参加出席 (v.)** — 参加会议等活动
  - "I **attended** the architecture review meeting yesterday afternoon."
- **义项 2: 关注处理 (v.)** — 关注某事并处理
  - "Please **attend** to the customer complaint as soon as possible."
- **义项 3: 伴随 (v.)** — 伴随某事物发生
  - "The risks **attending** this approach are well documented."

### 39. host
- **义项 1: 主持会议 (v.)** — 作为主持人主持活动
  - "Our manager **hosted** the quarterly review meeting last week."
- **义项 2: 托管服务 (v.)** — 在服务器上托管应用
  - "We **host** our application on AWS EC2 instances."
- **义项 3: 举办活动 (v.)** — 主办或承办活动
  - "The company **hosted** a hackathon for the engineering team."

### 40. facilitate
- **义项 1: 促进推动 (v.)** — 使某事更容易发生
  - "The scrum master **facilitated** the sprint retro discussion."
- **义项 2: 引导讨论 (v.)** — 引导小组讨论而不主导内容
  - "She **facilitated** a workshop on effective code review practices."
- **义项 3: 提供便利 (v.)** — 提供条件或资源使事情顺利
  - "The new tool **facilitates** collaboration between distributed teams."

### 41. moderate
- **义项 1: 主持调节 (v.)** — 主持讨论或辩论
  - "He **moderated** the panel discussion on AI ethics in software engineering."
- **义项 2: 审核管理 (v.)** — 管理在线内容或评论
  - "The system automatically **moderates** user-generated content."
- **义项 3: 使温和 (v.)** — 使某事变得不那么极端
  - "We need to **moderate** our expectations for the first release."

### 42. participate
- **义项 1: 参与参加 (v.)** — 加入某活动
  - "All team members are encouraged to **participate** in the code review process."
- **义项 2: 分担分享 (v.)** — 在某事中扮演角色
  - "Engineers from all teams **participated** in the incident postmortem."
- **义项 3: 投资入股 (v.)** — 以资金形式参与
  - "Several investors **participated** in the startup funding round."

### 43. contribute
- **义项 1: 贡献付出 (v.)** — 为某事做出贡献
  - "Everyone **contributed** ideas during the architecture brainstorming session."
- **义项 2: 投稿 (v.)** — 为开源项目或出版物提交代码/文章
  - "I **contributed** to three open-source projects last quarter."
- **义项 3: 导致促成 (v.)** — 成为某结果的部分原因
  - "Several factors **contributed** to the production outage."

### 44. share
- **义项 1: 分享信息 (v.)** — 分享知识或信息
  - "Could you **share** the meeting notes with the rest of the team?"
- **义项 2: 共用 (v.)** — 多人共同使用某资源
  - "The two teams **share** a staging environment for testing."
- **义项 3: 分担 (v.)** — 共同承担责任或成本
  - "We **shared** the on-call responsibilities across the entire team."

### 45. review
- **义项 1: 审查代码 (v.)** — 审查代码或文档的质量
  - "Could you **review** my pull request before the end of the day?"
- **义项 2: 回顾反思 (v.)** — 回顾过去的表现或事件
  - "The team **reviewed** the sprint outcomes during the retrospective."
- **义项 3: 评论评价 (v.)** — 写评论或以专业眼光评价
  - "The security team **reviewed** the new authentication flow and approved it."

### 46. explain
- **义项 1: 解释说明 (v.)** — 让某人理解某事
  - "Can you **explain** why the latency spiked during the deployment?"
- **义项 2: 阐述 (v.)** — 详细说明某概念
  - "The document **explains** the migration process step by step."
- **义项 3: 解释原因 (v.)** — 给出理由
  - "That **explains** why the error only appears under heavy load."

### 47. describe
- **义项 1: 描述 (v.)** — 用语言描绘某事物
  - "Can you **describe** the exact steps to reproduce the bug?"
- **义项 2: 形容 (v.)** — 说明某事物的特征
  - "The error message **describes** a timeout in the database connection."
- **义项 3: 归类 (v.)** — 将某事物描述为某一类
  - "The architecture can be **described** as event-driven."

### 48. notify
- **义项 1: 通知 (v.)** — 正式告知某人某事
  - "The system **notifies** the on-call engineer when an alert fires."
- **义项 2: 报告 (v.)** — 向某人报告某事
  - "Please **notify** the team if you encounter any unexpected behavior."
- **义项 3: 通告 (v.)** — 公开宣布信息
  - "All employees were **notified** of the new security policy via email."

### 49. inform
- **义项 1: 告知 (v.)** — 提供信息给某人
  - "I will **inform** the stakeholders about the timeline change."
- **义项 2: 影响 (v.)** — 对某人的观点或决策产生影响
  - "The user feedback **informed** our decision to redesign the interface."
- **义项 3: 指责告发 (v.)** — 正式告发（正式用法）
  - "The whistleblower **informed** against the company's data practices."

### 50. remind
- **义项 1: 提醒 (v.)** — 让某人记得某事
  - "Could you **remind** me to update the deployment checklist?"
- **义项 2: 使想起 (v.)** — 让某人联想到某事
  - "This bug **reminds** me of a similar issue we fixed last year."
- **义项 3: 提醒注意 (v.)** — 提醒某人注意某事
  - "I **reminded** the team about the upcoming security audit."

---

### Group 2: Communication & Business Nouns（沟通与商务名词）

---

### 51. agenda
- **义项 1: 议程 (n.)** — 会议讨论事项清单
  - "The **agenda** for the sprint planning meeting is posted in the channel."
- **义项 2: 计划安排 (n.)** — 个人计划或日程
  - "What is on your **agenda** for tomorrow afternoon?"
- **义项 3: 动机目的 (n.)** — 隐藏的政治或商业目的
  - "I suspect he has a hidden **agenda** for pushing this proposal."

### 52. meeting
- **义项 1: 会议 (n.)** — 多人聚集讨论
  - "The standup **meeting** starts at 9:30 AM every day."
- **义项 2: 会面 (n.)** — 两人或多人的碰面
  - "I have a one-on-one **meeting** with my manager this afternoon."
- **义项 3: 集合 (n.)** — 物品或事物的相遇
  - "The API **meeting** point is where the frontend and backend connect."

### 53. conference
- **义项 1: 会议大会 (n.)** — 大型专业会议
  - "I attended a technology **conference** in San Francisco last month."
- **义项 2: 电话会议 (n.)** — 电话或视频会议
  - "We had a **conference** call with the remote team in London."
- **义项 3: 研讨会 (n.)** — 学术或行业研讨活动
  - "The **conference** featured several talks on AI and machine learning."

### 54. presentation
- **义项 1: 演示演讲 (n.)** — 向观众展示信息的活动
  - "She gave an excellent **presentation** on the new architecture."
- **义项 2: 演示文件 (n.)** — PowerPoint 或其他幻灯片文件
  - "I attached the **presentation** to the meeting invite."
- **义项 3: 呈现方式 (n.)** — 事物呈现的外观或形式
  - "The **presentation** of data in the dashboard needs improvement."

### 55. deck
- **义项 1: 幻灯片组 (n.)** — 一组演示幻灯片
  - "I prepared a **deck** for the quarterly business review."
- **义项 2: 甲板 (n.)** — 船或建筑物的平台
  - "The hotel has a rooftop **deck** with a great view."
- **义项 3: 一叠牌 (n.)** — 一副扑克牌
  - "He shuffled the **deck** and dealt the cards."

### 56. slide
- **义项 1: 幻灯片 (n.)** — 演示文稿中的一页
  - "This **slide** shows the timeline for the project milestones."
- **义项 2: 滑梯 (n.)** — 儿童游乐设施
  - "The children were playing on the **slide** at the park."
- **义项 3: 滑行 (n.)** — 在光滑表面上的滑动
  - "The stock price went into a **slide** after the earnings report."

### 57. memo
- **义项 1: 备忘录 (n.)** — 团队或公司内部简短通知
  - "The CEO sent a company-wide **memo** about the new work-from-home policy."
- **义项 2: 便签 (n.)** — 简短的手写记录
  - "I left a **memo** on your desk about the server maintenance."
- **义项 3: 纪要 (n.)** — 会议要点的简要记录
  - "The **memo** from the architecture meeting outlined three key decisions."

### 58. proposal
- **义项 1: 提案方案 (n.)** — 正式提出的计划或建议
  - "The team submitted a **proposal** to migrate from monolith to microservices."
- **义项 2: 投标书 (n.)** — 商业竞标文件
  - "Our company submitted a **proposal** for the government contract."
- **义项 3: 求婚 (n.)** — 结婚请求
  - "She said yes to his marriage **proposal**."

### 59. contract
- **义项 1: 合同 (n.)** — 法律约束力的协议
  - "We signed a **contract** with the cloud provider for three years."
- **义项 2: 承包 (n.)** — 外包或承包关系
  - "They hired a freelance developer on a six-month **contract**."
- **义项 3: 缩约词 (n.)** — 缩写形式（语法术语）
  - "In English, 'cannot' is often shortened to the **contract** 'can't'."

### 60. agreement
- **义项 1: 协议 (n.)** — 双方达成的共识
  - "We reached an **agreement** on the scope of the project."
- **义项 2: 一致性 (n.)** — 意见或观点一致
  - "There is general **agreement** that we need to improve test coverage."
- **义项 3: 合同 (n.)** — 具有法律效力的协议
  - "The service level **agreement** guarantees 99.9 percent uptime."

### 61. deadline
- **义项 1: 截止日期 (n.)** — 必须完成某事的最后时间
  - "The **deadline** for the Q2 release is June 15th."
- **义项 2: 截稿时间 (n.)** — 提交稿件的最后时间
  - "The **deadline** for the incident report is end of business today."
- **义项 3: 最后期限 (n.)** — 无法延期的最终时间
  - "We are working against a tight **deadline** to deliver this feature."

### 62. budget
- **义项 1: 预算 (n.)** — 可用的资金额度
  - "The project **budget** was approved by the finance department."
- **义项 2: 做预算 (v.)** — 计划资金分配
  - "We need to **budget** for the new infrastructure costs."
- **义项 3: 预算量 (n.)** — 可用时间或精力的比喻
  - "I have used up my **budget** for refactoring this sprint."

### 63. resource
- **义项 1: 资源 (n.)** — 人力、资金、设备等可用要素
  - "We need more **resources** to complete the project on time."
- **义项 2: 资料 (n.)** — 学习或参考资料
  - "The team wiki is a valuable **resource** for onboarding new members."
- **义项 3: 系统资源 (n.)** — CPU、内存等计算资源
  - "The application is consuming too many system **resources**."

### 64. priority
- **义项 1: 优先事项 (n.)** — 最重要的事情
  - "Security fixes are our top **priority** this week."
- **义项 2: 优先级 (n.)** — 重要性的排序
  - "This bug has been assigned a high **priority** in the issue tracker."
- **义项 3: 优先权 (n.)** — 先于别人处理的权利
  - "Critical incidents take **priority** over all other work."

### 65. objective
- **义项 1: 目标 (n.)** — 试图达到的结果
  - "The main **objective** of this sprint is to reduce database latency."
- **义项 2: 目的 (n.)** — 做某事的深层原因
  - "The **objective** of the meeting is to align on the architecture decisions."
- **义项 3: 客观 (adj.)** — 基于事实而非情感的
  - "We need an **objective** assessment of the current system performance."

### 66. goal
- **义项 1: 目标 (n.)** — 想要达成的结果
  - "Our **goal** is to achieve 99.99 percent uptime this quarter."
- **义项 2: 进球 (n.)** — 体育中的得分
  - "He scored the winning **goal** in the last minute of the match."
- **义项 3: 目的地 (n.)** — 努力要达到的地方
  - "We finally reached our **goal** of migrating all services to the cloud."

### 67. target
- **义项 1: 目标值 (n.)** — 设定的量化指标
  - "Our **target** is to reduce page load time to under 200 milliseconds."
- **义项 2: 对象 (n.)** — 被针对的群体或事物
  - "The new feature's **target** audience is enterprise customers."
- **义项 3: 设定目标 (v.)** — 瞄准某个具体数值
  - "We **target** a 30 percent improvement in test coverage by next quarter."

### 68. KPI
- **义项 1: 关键绩效指标 (n.)** — Key Performance Indicator
  - "System response time is one of our most important **KPIs**."
- **义项 2: 业绩衡量 (n.)** — 用来评估成功与否的量化标准
  - "The team exceeded all **KPI** targets for the quarter."
- **义项 3: 度量标准 (n.)** — 广义上任何重要度量
  - "Developer satisfaction is a qualitative **KPI** that is hard to measure."

### 69. metric
- **义项 1: 度量指标 (n.)** — 可量化的测量标准
  - "We track several **metrics** to monitor system health."
- **义项 2: 衡量标准 (n.)** — 用于评判表现的标准
  - "Code coverage is not the only **metric** for code quality."
- **义项 3: 公制 (n.)** — 度量衡系统
  - "Most countries use the **metric** system for measurements."

### 70. OKR
- **义项 1: 目标与关键成果 (n.)** — Objectives and Key Results
  - "Our **OKRs** for this quarter focus on improving developer productivity."
- **义项 2: 目标管理体系 (n.)** — OKR 管理方法论
  - "The company adopted **OKRs** to align team goals with business strategy."
- **义项 3: 考核工具 (n.)** — 绩效评估的框架
  - "We review our **OKRs** at the end of each quarter."

### 71. strategy
- **义项 1: 策略 (n.)** — 达成目标的长期计划
  - "Our **strategy** is to release early and iterate based on user feedback."
- **义项 2: 战略 (n.)** — 高层次的全局规划
  - "The company's cloud migration **strategy** spans three years."
- **义项 3: 策略方法 (n.)** — 应对特定问题的方案
  - "What is your **strategy** for handling the increasing traffic volume?"

### 72. tactic
- **义项 1: 战术方法 (n.)** — 实现策略的具体操作
  - "Our **tactic** is to use feature flags for gradual rollouts."
- **义项 2: 手段 (n.)** — 达到目的的具体手法
  - "Canary deployment is a common **tactic** for reducing deployment risk."
- **义项 3: 策略性 (adj.)** — 有策略安排的
  - "The decision to delay the release was a **tactic** move to avoid the holiday rush."

### 73. initiative
- **义项 1: 倡议 (n.)** — 新提出的计划或行动
  - "The company launched a new **initiative** to improve code quality."
- **义项 2: 主动性 (n.)** — 主动做某事的精神
  - "She showed great **initiative** by organizing the documentation effort."
- **义项 3: 项目 (n.)** — 公司层面的大型专项工作
  - "The cloud migration **initiative** involves over 50 engineers."

### 74. project
- **义项 1: 项目 (n.)** — 有明确目标的临时性工作
  - "The **project** to migrate the database is scheduled for next quarter."
- **义项 2: 投射 (v.)** — 预测或估算未来数值
  - "We **project** a 20 percent increase in traffic during the holiday season."
- **义项 3: 投射影像 (v.)** — 将影像投射到屏幕上
  - "She **projected** the architecture diagram onto the conference room screen."

### 75. program
- **义项 1: 项目群 (n.)** — 相关项目的集合
  - "The infrastructure modernization **program** includes five sub-projects."
- **义项 2: 程序 (n.)** — 计算机程序或软件
  - "The installation **program** will guide you through the setup process."
- **义项 3: 节目 (n.)** — 电视或广播节目
  - "There is an interesting **program** about AI on TV tonight."

### 76. portfolio
- **义项 1: 项目组合 (n.)** — 公司或部门管理的项目集合
  - "The engineering **portfolio** includes projects across all business units."
- **义项 2: 投资组合 (n.)** — 个人或机构持有的投资集合
  - "He diversified his investment **portfolio** with tech stocks and bonds."
- **义项 3: 作品集 (n.)** — 展示个人作品的文件集
  - "She prepared a **portfolio** of her previous projects for the interview."

### 77. roadmap
- **义项 1: 路线图 (n.)** — 产品或项目的未来计划
  - "The product **roadmap** shows the major features planned for next year."
- **义项 2: 发展规划 (n.)** — 技术或职业发展的长期规划
  - "We need to create a **roadmap** for the legacy system migration."
- **义项 3: 路线图文件 (n.)** — 展示路线图的可视化文档
  - "The team presented the **roadmap** during the quarterly planning session."

### 78. plan
- **义项 1: 计划 (n.)** — 做某事的详细安排
  - "We have a rollback **plan** in case the deployment fails."
- **义项 2: 规划 (v.)** — 安排和准备未来要做的事
  - "We are **planning** the architecture for the new payment system."
- **义项 3: 平面图 (n.)** — 建筑或设计的俯视图
  - "The office **plan** shows the layout of desks and meeting rooms."

### 79. schedule
- **义项 1: 时间表 (n.)** — 活动或任务的预定时间
  - "The deployment **schedule** is posted on the team calendar."
- **义项 2: 课程表 (n.)** — 学习或会议安排
  - "I have a busy **schedule** with back-to-back meetings today."
- **义项 3: 时刻表 (n.)** — 交通系统的发车到达时间
  - "The train **schedule** has changed due to track maintenance."

### 80. calendar
- **义项 1: 日历 (n.)** — 显示日期的工具
  - "Please check my **calendar** before scheduling the meeting."
- **义项 2: 日程表 (n.)** — 记录约会和事件的工具
  - "I added the deadline to my **calendar** so I do not forget."
- **义项 3: 年历 (n.)** — 一年的日期系统
  - "The Chinese lunar **calendar** determines the date of the Spring Festival."

### 81. invite
- **义项 1: 邀请 (n.)** — 会议邀请或活动邀请
  - "I sent you a calendar **invite** for the architecture review."
- **义项 2: 邀请函 (v.)** — 邀请某人参加活动
  - "I will **invite** the QA lead to the design review meeting."
- **义项 3: 招来 (v.)** — 引起或招致某种结果
  - "Pushing directly to main will **invite** trouble in a team environment."

### 82. decision
- **义项 1: 决定 (n.)** — 经过思考后的选择
  - "The **decision** to adopt microservices was made after months of evaluation."
- **义项 2: 决策 (n.)** — 做决定的过程或能力
  - "Good **decision** making requires accurate data and clear criteria."
- **义项 3: 判决 (n.)** — 法律或官方的裁决
  - "The court's **decision** will affect how we handle user data."

### 83. note
- **义项 1: 笔记 (n.)** — 简短文字记录
  - "I took detailed **notes** during the incident review meeting."
- **义项 2: 便条 (n.)** — 简短手写留言
  - "She left a **note** on my desk about the server maintenance."
- **义项 3: 注意 (v.)** — 留意或注意到某事
  - "Please **note** that the deadline has been moved to Friday."

### 84. minute
- **义项 1: 分钟 (n.)** — 时间单位 60 秒
  - "The server was down for 15 **minutes** before we noticed."
- **义项 2: 会议纪要 (n.)** — 会议内容的正式记录（常复数）
  - "Who is responsible for taking the **minutes** during the meeting?"
- **义项 3: 微小的 (adj.)** — 非常小
  - "There is a **minute** difference in performance between the two frameworks."

### 85. summary
- **义项 1: 摘要总结 (n.)** — 主要内容的简洁描述
  - "Can you give me a **summary** of the incident report?"
- **义项 2: 概述 (n.)** — 对复杂事物的简短版本
  - "The executive **summary** highlights the key findings of the audit."
- **义项 3: 总结 (v.)** — 做出总结的行为
  - "To **summary** the discussion, we agreed on the new timeline."

### 86. recap
- **义项 1: 回顾 (n.)** — 对过去事件的简要总结
  - "Let me give you a quick **recap** of what happened in the meeting."
- **义项 2: 概述 (v.)** — 简要重复重要信息
  - "I will **recap** the main points from yesterday's discussion."
- **义项 3: 摘要 (n.)** — 简短版本的故事或事件
  - "The weekly **recap** email summarizes all important announcements."

### 87. announcement
- **义项 1: 公告 (n.)** — 公开发布的重要消息
  - "The **announcement** about the reorganization was sent to all employees."
- **义项 2: 宣布 (n.)** — 正式声明某事
  - "The **announcement** of the new product was made at the conference."
- **义项 3: 通知 (n.)** — 简短的通知或通告
  - "Please wait for the official **announcement** before making any changes."

### 88. update
- **义项 1: 更新 (n.)** — 最新的信息或状态
  - "I will provide a status **update** during the standup meeting."
- **义项 2: 更新 (v.)** — 将信息或系统更新到最新状态
  - "Please **update** the deployment documentation after making changes."
- **义项 3: 升级 (v.)** — 将软件升级到新版本
  - "We need to **update** the server to the latest security patch."

### 89. status
- **义项 1: 状态 (n.)** — 当前的情况或进展
  - "What is the **status** of the database migration?"
- **义项 2: 身份 (n.)** — 社会或职业地位
  - "His **status** as a senior engineer gives him decision-making authority."
- **义项 3: 情形 (n.)** — 法律或正式程序中的状态
  - "The application **status** changed from pending to approved."

### 90. progress
- **义项 1: 进展 (n.)** — 向着目标的推进情况
  - "We have made significant **progress** on the refactoring project."
- **义项 2: 进步 (n.)** — 技能或能力的提升
  - "She has shown great **progress** in learning the new framework."
- **义项 3: 进展 (v.)** — 逐渐取得进展
  - "The work is **progressing** according to the project timeline."

### 91. result
- **义项 1: 结果 (n.)** — 由某行动导致的事件或情况
  - "The test **results** showed a 50 percent improvement in performance."
- **义项 2: 成绩 (n.)** — 考试或评测的分数
  - "The exam **results** will be published next week."
- **义项 3: 导致 (v.)** — 作为结果发生
  - "The misconfiguration **resulted** in a complete system outage."

### 92. outcome
- **义项 1: 成果 (n.)** — 某过程最终的结果
  - "The **outcome** of the incident review was a list of action items."
- **义项 2: 结局 (n.)** — 某事最终的结果
  - "We were satisfied with the **outcome** of the negotiation."
- **义项 3: 影响 (n.)** — 长期的影响或后果
  - "The **outcome** of this decision will affect the team for months."

### 93. impact
- **义项 1: 影响 (n.)** — 对某人或某事的效果
  - "The outage had a significant **impact** on our customers."
- **义项 2: 冲击 (n.)** — 强烈的撞击或影响
  - "The **impact** of the new regulation on data privacy is still unclear."
- **义项 3: 影响 (v.)** — 对某事产生效果
  - "The change in requirements will **impact** our timeline significantly."

### 94. feedback
- **义项 1: 反馈 (n.)** — 对工作或表现的评价
  - "I received positive **feedback** on my code review comments."
- **义项 2: 反馈意见 (n.)** — 客户或用户的意见
  - "The user **feedback** highlighted several usability issues."
- **义项 3: 回授 (n.)** — 系统中输出返回影响输入的机制
  - "The amplifier uses negative **feedback** to stabilize the output."

### 95. concern
- **义项 1: 担忧 (n.)** — 对某事的担心或不安
  - "The team raised **concerns** about the security implications of the change."
- **义项 2: 关注事项 (n.)** — 需要关注的事
  - "Data privacy is a growing **concern** for our customers."
- **义项 3: 涉及 (v.)** — 与某事相关
  - "This issue **concerns** the entire platform, not just one service."

### 96. issue
- **义项 1: 问题 (n.)** — 需要处理的问题
  - "We identified several **issues** during the security audit."
- **义项 2: 议题 (n.)** — 讨论的主题
  - "The team discussed the **issue** of technical debt in the retro."
- **义项 3: 发布 (v.)** — 官方发布或分发
  - "The company **issued** a statement about the data breach."

### 97. risk
- **义项 1: 风险 (n.)** — 可能发生的问题
  - "The main **risk** of this approach is the potential downtime during migration."
- **义项 2: 危险 (n.)** — 受到伤害或损失的可能性
  - "There is a **risk** of data loss if we do not back up the database first."
- **义项 3: 冒险 (v.)** — 冒着……的危险
  - "We cannot **risk** deploying on a Friday without full test coverage."

### 98. assumption
- **义项 1: 假设 (n.)** — 未经证实的假定
  - "Our **assumption** was that the database would handle the load, but we were wrong."
- **义项 2: 预设 (n.)** — 做决策时默认的前提
  - "We need to validate our **assumptions** before proceeding with the design."
- **义项 3: 承担 (n.)** — 承担责任或角色
  - "The **assumption** of the new role came with increased responsibilities."

### 99. constraint
- **义项 1: 约束条件 (n.)** — 限制行动或选择的因素
  - "Time is our biggest **constraint** on this project."
- **义项 2: 限制 (n.)** — 技术上或资源上的限制
  - "The budget **constraint** means we cannot hire additional engineers."
- **义项 3: 制约 (n.)** — 系统设计中的限制因素
  - "Database latency is a **constraint** we need to design around."

### 100. stakeholder
- **义项 1: 利益相关者 (n.)** — 对项目有利益关系的人
  - "We need to present the proposal to all key **stakeholders**."
- **义项 2: 项目干系人 (n.)** — 受项目影响的人
  - "The **stakeholders** include engineering, product, and sales teams."
- **义项 3: 股东 (n.)** — 持有公司股份的人
  - "The CEO updated the **stakeholders** on the company's growth strategy."

---

### Group 3: Daily Life — Money, Shopping & Finance（日常购物与金融）

---

### 101. money
- **义项 1: 钱 (n.)** — 用来交易支付的通货
  - "I need to withdraw some **money** from the ATM."
- **义项 2: 资金 (n.)** — 可用资产
  - "The company raised **money** from venture capitalists."
- **义项 3: 财富 (n.)** — 个人或组织的经济资源
  - "Time is more valuable than **money**."

### 102. cash
- **义项 1: 现金 (n.)** — 硬币和纸币形式的钱
  - "Do you have enough **cash** to pay for the taxi?"
- **义项 2: 兑现 (v.)** — 将支票兑成现金
  - "I need to **cash** this check at the bank."
- **义项 3: 现金支付 (n.)** — 以现金付款的方式
  - "The restaurant only accepts **cash**, not credit cards."

### 103. coin
- **义项 1: 硬币 (n.)** — 金属货币
  - "I found some **coins** in the pocket of my jacket."
- **义项 2: 创造新词 (v.)** — 发明新词或短语
  - "The term 'microservice' was **coined** in the early 2010s."
- **义项 3: 硬币收藏 (n.)** — 作为收藏品的硬币
  - "He has a valuable **coin** collection from ancient Rome."

### 104. bill
- **义项 1: 账单 (n.)** — 需要支付的费用清单
  - "The electricity **bill** was higher than expected this month."
- **义项 2: 纸币 (n.)** — 纸质的钱
  - "Can you break a 100 dollar **bill** into smaller notes?"
- **义项 3: 法案 (n.)** — 立法提案
  - "The **bill** was passed by the parliament last week."

### 105. dollar
- **义项 1: 美元 (n.)** — 美国货币单位
  - "The subscription costs 20 **dollars** per month."
- **义项 2: 元 (n.)** — 其他国家的货币单位
  - "The Australian **dollar** strengthened against the US dollar."
- **义项 3: 一元纸币/硬币 (n.)** — 面值为一元的货币
  - "Can I borrow a **dollar** for the parking meter?"

### 106. cent
- **义项 1: 美分 (n.)** — 百分之一美元
  - "The candy costs only 50 **cents**."
- **义项 2: 分 (n.)** — 百分之一的货币单位
  - "Every **cent** counts when you are on a tight budget."
- **义项 3: 毫无价值 (n.)** — 在否定句中表示"一点也"
  - "I do not care a **cent** about what they think."

### 107. euro
- **义项 1: 欧元 (n.)** — 欧洲联盟的货币单位
  - "The hotel room costs 150 **euros** per night."
- **义项 2: 欧元区 (n.)** — 使用欧元的国家区域
  - "The **euro** has been stable against most major currencies."

### 108. pound
- **义项 1: 英镑 (n.)** — 英国货币单位
  - "The flight to London costs 300 **pounds**."
- **义项 2: 磅 (n.)** — 重量单位，约 454 克
  - "I bought two **pounds** of apples at the market."
- **义项 3: 敲打 (v.)** — 反复敲击
  - "Someone was **pounding** on the door late at night."

### 109. currency
- **义项 1: 货币 (n.)** — 一国使用的通行的钱
  - "You need to exchange your **currency** before traveling abroad."
- **义项 2: 流通 (n.)** — 被广泛接受或通行
  - "The idea gained **currency** among software architects."
- **义项 3: 通用性 (n.)** — 某事物被广泛接受的程度
  - "The term has wide **currency** in the tech industry."

### 110. price
- **义项 1: 价格 (n.)** — 购买某物需支付的金额
  - "The **price** of the new iPhone is too high."
- **义项 2: 定价 (v.)** — 标定价格
  - "The product is **priced** competitively in the market."
- **义项 3: 代价 (n.)** — 获得某物所付出的牺牲
  - "The **price** of success is hard work and dedication."

### 111. cost
- **义项 1: 成本 (n.)** — 购买或生产某物所需的金额
  - "The **cost** of living in this city is very high."
- **义项 2: 花费 (v.)** — 需要付出多少钱
  - "How much does this laptop **cost**?"
- **义项 3: 代价 (n.)** — 损失或牺牲
  - "He learned the hard way that lying has a **cost**."

### 112. fee
- **义项 1: 费用 (n.)** — 专业的服务费用
  - "The lawyer's **fee** is 300 dollars per hour."
- **义项 2: 手续费 (n.)** — 办理业务的费用
  - "There is a 10 dollar processing **fee** for the visa application."
- **义项 3: 会费 (n.)** — 加入组织的定期费用
  - "The annual membership **fee** is 50 dollars."

### 113. charge
- **义项 1: 收费 (v.)** — 要求付款
  - "The hotel **charged** me 50 dollars for late checkout."
- **义项 2: 费用 (n.)** — 需支付的金额
  - "There is a delivery **charge** for orders under 20 dollars."
- **义项 3: 充电 (v.)** — 给电池充入电力
  - "I need to **charge** my phone before the meeting."

### 114. tax
- **义项 1: 税 (n.)** — 政府向收入或消费征收的钱
  - "The price includes 8 percent sales **tax**."
- **义项 2: 税收 (n.)** — 向政府缴纳的款项
  - "You need to file your income **tax** before April 15th."
- **义项 3: 负担 (v.)** — 使承受负担（比喻用法）
  - "The long commute **taxes** my patience every day."

### 115. tip
- **义项 1: 小费 (n.)** — 给服务人员的额外报酬
  - "It is customary to leave a 15 percent **tip** at restaurants."
- **义项 2: 建议 (n.)** — 有用的建议或提示
  - "Here is a **tip** for debugging that type of error."
- **义项 3: 尖端 (n.)** — 物体的末端或顶部
  - "The **tip** of the pen is very fine for detailed drawing."

### 116. discount
- **义项 1: 折扣 (n.)** — 降价的幅度
  - "I got a 20 percent **discount** on the laptop during the sale."
- **义项 2: 打折 (v.)** — 降价出售
  - "The store **discounts** all items during the holiday season."
- **义项 3: 打折处理 (v.)** — 不把某事当真（比喻用法）
  - "Do not **discount** the importance of good documentation."

### 117. sale
- **义项 1: 促销 (n.)** — 特价销售活动
  - "The store is having a **sale** on winter clothes."
- **义项 2: 销售 (n.)** — 出售的行为
  - "The **sale** of the product exceeded our expectations."
- **义项 3: 拍卖 (n.)** — 通过竞价出售
  - "The house was sold at a public **sale**."

### 118. receipt
- **义项 1: 收据 (n.)** — 购物的凭证
  - "Please keep the **receipt** in case you need to return the item."
- **义项 2: 收到 (n.)** — 收到某物的状态（正式用法）
  - "I am writing to acknowledge **receipt** of your payment."
- **义项 3: 凭证 (n.)** — 证明交易的文件
  - "The **receipt** shows the date and amount of purchase."

### 119. invoice
- **义项 1: 发票 (n.)** — 请求付款的正式文件
  - "Please send the **invoice** to the accounting department."
- **义项 2: 开票 (v.)** — 为某人开具发票
  - "We will **invoice** you at the end of each month."
- **义项 3: 账单 (n.)** — 列明商品或服务的收费清单
  - "The **invoice** includes a breakdown of all charges."

### 120. expense
- **义项 1: 开支 (n.)** — 花出去的钱
  - "Travel **expenses** will be reimbursed by the company."
- **义项 2: 报销 (v.)** — 将开支报账（常复数 expenses）
  - "I need to **expense** the client lunch from yesterday."
- **义项 3: 代价 (n.)** — 为某事付出的牺牲
  - "He became successful at the **expense** of his personal life."

### 121. income
- **义项 1: 收入 (n.)** — 个人或公司赚到的钱
  - "Her annual **income** is around 100,000 dollars."
- **义项 2: 收益 (n.)** — 投资或业务产生的利润
  - "The rental **income** from the property covers the mortgage."
- **义项 3: 进账 (n.)** — 定期收到的款项
  - "Freelancers often have variable monthly **income**."

### 122. salary
- **义项 1: 薪资 (n.)** — 雇主定期支付的固定报酬
  - "He negotiated a higher **salary** for the new position."
- **义项 2: 年薪 (n.)** — 按年计算的固定收入
  - "The **salary** for this role ranges from 80,000 to 120,000 dollars."

### 123. wage
- **义项 1: 时薪 (n.)** — 按小时计算的报酬
  - "The minimum **wage** in this state is 15 dollars per hour."
- **义项 2: 工资 (n.)** — 体力劳动者或按工时付薪的收入
  - "The factory workers received a **wage** increase."

### 124. payment
- **义项 1: 付款 (n.)** — 支付的行为或过程
  - "The **payment** was processed successfully through the online system."
- **义项 2: 付款额 (n.)** — 每期支付的金额
  - "The monthly **payment** for the car loan is 400 dollars."
- **义项 3: 报酬 (n.)** — 作为回报的金钱
  - "The consultant received a **payment** for her services."

### 125. debt
- **义项 1: 债务 (n.)** — 欠别人的钱
  - "The company has accumulated significant **debt** over the years."
- **义项 2: 负债 (n.)** — 欠款的总额
  - "She is trying to pay off her student **debt** as quickly as possible."
- **义项 3: 人情债 (n.)** — 受到恩惠而欠的情分（比喻）
  - "I owe him a **debt** of gratitude for his help."

### 126. loan
- **义项 1: 贷款 (n.)** — 银行借出的钱
  - "We took out a **loan** to buy our first house."
- **义项 2: 借出 (v.)** — 借钱给某人
  - "Can you **loan** me 50 dollars until payday?"
- **义项 3: 借贷 (n.)** — 借出的金额
  - "The bank approved the **loan** application within a week."

### 127. credit
- **义项 1: 信用 (n.)** — 可信赖的支付能力
  - "I paid for the laptop using my **credit** card."
- **义项 2: 赊账 (n.)** — 先获得商品后付款的方式
  - "The store offers 30 days of **credit** for new customers."
- **义项 3: 功劳 (n.)** — 对成就或贡献的认可
  - "She deserves **credit** for leading the successful migration."

### 128. bank
- **义项 1: 银行 (n.)** — 存放和借贷款项的金融机构
  - "I opened a savings account at the **bank**."
- **义项 2: 河岸 (n.)** — 河流两侧的陆地
  - "We had a picnic on the **bank** of the river."
- **义项 3: 存储 (v.)** — 存入或依赖
  - "You can **bank** on his experience to guide the team."

### 129. account
- **义项 1: 账户 (n.)** — 银行或系统中的个人记录
  - "I transferred money from my savings **account**."
- **义项 2: 描述 (n.)** — 对事件的叙述
  - "His **account** of the incident differed from hers."
- **义项 3: 解释说明 (v.)** — 解释原因或账目
  - "We need to **account** for the budget variance."

### 130. balance
- **义项 1: 余额 (n.)** — 账户中的可用金额
  - "The **balance** in my checking account is 500 dollars."
- **义项 2: 平衡 (n.)** — 均衡的状态
  - "We need to find a **balance** between speed and quality."
- **义项 3: 权衡 (v.)** — 使相等或稳定
  - "The team **balanced** the business requirements with technical constraints."

### 131. deposit
- **义项 1: 存款 (v.)** — 将钱存入账户
  - "I **deposited** a check into my savings account this morning."
- **义项 2: 押金 (n.)** — 预付的保证金
  - "The landlord requires a one-month rent **deposit**."
- **义项 3: 放置 (v.)** — 将某物放置在特定位置
  - "He **deposited** the documents on my desk."

### 132. withdraw
- **义项 1: 取款 (v.)** — 从账户中取钱
  - "I need to **withdraw** 200 dollars from the ATM."
- **义项 2: 撤回 (v.)** — 收回或取消
  - "We decided to **withdraw** the proposal after receiving negative feedback."
- **义项 3: 退出 (v.)** — 从活动中退出
  - "She **withdrew** from the project due to personal reasons."

### 133. transfer
- **义项 1: 转账 (v.)** — 将钱从一个账户转到另一个
  - "I **transferred** the payment to the vendor's account."
- **义项 2: 转移 (v.)** — 将某人或某物从一个地方移到另一处
  - "He was **transferred** to the Singapore office last year."
- **义项 3: 传输 (v.)** — 传送数据或信息
  - "The system **transfers** the data securely using encryption."

### 134. save
- **义项 1: 储蓄 (v.)** — 留钱以备将来使用
  - "I am **saving** money for a down payment on a house."
- **义项 2: 节省 (v.)** — 减少消耗或浪费
  - "Using public transport **saves** both money and time."
- **义项 3: 保存 (v.)** — 在计算机中存储数据
  - "Remember to **save** your work before closing the editor."

### 135. spend
- **义项 1: 花钱 (v.)** — 支付钱购买商品或服务
  - "I **spent** 200 dollars on groceries this week."
- **义项 2: 花时间 (v.)** — 花费时间做某事
  - "She **spent** the weekend debugging the performance issue."
- **义项 3: 消耗 (v.)** — 使用或耗尽某物
  - "The team **spent** all their energy on the product launch."

### 136. afford
- **义项 1: 负担得起 (v.)** — 有足够的钱购买
  - "We cannot **afford** to buy a new car right now."
- **义项 2: 承担得起 (v.)** — 承受某后果
  - "We cannot **afford** to ignore the security vulnerability."
- **义项 3: 提供 (v.)** — 提供或给予（正式用法）
  - "The new technology **affords** us greater flexibility."

### 137. buy
- **义项 1: 购买 (v.)** — 用钱换取商品
  - "I **bought** a new laptop for work."
- **义项 2: 买通 (v.)** — 通过贿赂获取
  - "They tried to **buy** the support of the committee members."
- **义项 3: 接受相信 (v.)** — 接受某事的真实性
  - "I do not **buy** their explanation for the system failure."

### 138. sell
- **义项 1: 出售 (v.)** — 将商品换为钱
  - "The company **sells** software-as-a-service to enterprise clients."
- **义项 2: 销售量 (n.)** — 销售的数量
  - "The new product had strong **sales** in the first quarter."
- **义项 3: 说服 (v.)** — 使某人接受某想法
  - "She **sold** the team on her vision for the new architecture."

### 139. purchase
- **义项 1: 购买 (v.)** — 正式地购买
  - "We **purchased** a new server to handle the increased traffic."
- **义项 2: 购物品 (n.)** — 已购买的东西
  - "The **purchase** comes with a one-year warranty."
- **义项 3: 收购 (n.)** — 公司收购行为
  - "The company made a large **purchase** of a smaller competitor."

### 140. shop
- **义项 1: 购物 (v.)** — 去商店浏览和购买
  - "I like to **shop** online for clothes."
- **义项 2: 商店 (n.)** — 零售场所
  - "The coffee **shop** around the corner makes great lattes."
- **义项 3: 选购 (v.)** — 四处比较后再买
  - "You should **shop** around before buying a laptop."

### 141. store
- **义项 1: 商店 (n.)** — 零售商店
  - "The grocery **store** is within walking distance from my apartment."
- **义项 2: 存储 (v.)** — 存放某物以备后用
  - "We **store** the backup data in an offsite location."
- **义项 3: 仓库 (n.)** — 存放货物的地方
  - "The company has a large **store** of spare parts."

### 142. online
- **义项 1: 在线的 (adj.)** — 通过互联网进行的
  - "I prefer **online** shopping because it is more convenient."
- **义项 2: 在线地 (adv.)** — 通过互联网的方式
  - "You can track your order **online** using the tracking number."
- **义项 3: 上网的 (adj.)** — 连接到互联网的状态
  - "The system needs to be **online** for users to access it."

### 143. order
- **义项 1: 订购 (v.)** — 要求提供商品或服务
  - "I **ordered** a new keyboard from the online store."
- **义项 2: 订单 (n.)** — 订购的记录
  - "Your **order** has been shipped and will arrive tomorrow."
- **义项 3: 顺序 (n.)** — 事物的排列次序
  - "The events are listed in chronological **order**."

### 144. delivery
- **义项 1: 递送 (n.)** — 商品送达的过程
  - "The **delivery** of the package took three days."
- **义项 2: 交付 (n.)** — 产品或服务的交付
  - "The **delivery** of the new feature is scheduled for next week."
- **义项 3: 分娩 (n.)** — 生孩子的过程
  - "The hospital has a specialized **delivery** unit."

### 145. return
- **义项 1: 退货 (v.)** — 将购买的商品退还
  - "I **returned** the defective product and got a full refund."
- **义项 2: 返回 (v.)** — 回到某个地方
  - "I will **return** to the office after the client meeting."
- **义项 3: 回报 (n.)** — 投资产生的利润
  - "The **return** on investment for this project is estimated at 30 percent."

### 146. refund
- **义项 1: 退款 (n.)** — 退还的付款
  - "I received a full **refund** for the canceled flight."
- **义项 2: 退还 (v.)** — 把钱退还给客户
  - "The store **refunded** my money after I returned the item."
- **义项 3: 报销 (v.)** — 偿还他人代付的费用
  - "The company **refunded** my travel expenses."

### 147. exchange
- **义项 1: 换货 (v.)** — 用购买的商品换另一件
  - "I **exchanged** the shoes for a larger size."
- **义项 2: 兑换 (v.)** — 将一种货币换成另一种
  - "I need to **exchange** dollars for euros before my trip."
- **义项 3: 交流 (n.)** — 相互交换信息或想法
  - "The meeting was a productive **exchange** of ideas."

### 148. brand
- **义项 1: 品牌 (n.)** — 产品的商业名称
  - "This is a well-known **brand** of smartphones."
- **义项 2: 打烙印 (v.)** — 给牲畜烙上印记
  - "Farmers **brand** their cattle to identify ownership."
- **义项 3: 印象 (n.)** — 某事物给人的独特印象（比喻）
  - "Her management style has a distinct **brand** of directness."

### 149. product
- **义项 1: 产品 (n.)** — 制造或提供的物品
  - "The new **product** will launch in the second quarter."
- **义项 2: 产物 (n.)** — 某过程或情况的自然结果
  - "The redesigned interface is the **product** of months of user research."
- **义项 3: 乘积 (n.)** — 数学中相乘的结果
  - "The **product** of 12 and 5 is 60."

### 150. quality
- **义项 1: 质量 (n.)** — 物品的优劣程度
  - "The **quality** of the code has improved since we adopted code reviews."
- **义项 2: 特质 (n.)** — 某人或某物的特性
  - "Patience is an important **quality** for a tech lead."
- **义项 3: 优质的 (adj.)** — 高标准的
  - "We only use **quality** materials for our products."

---

### Group 4: Daily Life — Food, Drink & Cooking（饮食烹饪）

---

### 151. food
- **义项 1: 食物 (n.)** — 吃的物质
  - "The **food** at that restaurant is excellent."
- **义项 2: 食品 (n.)** — 特定类型或类别的食物
  - "Frozen **food** is convenient but not always healthy."
- **义项 3: 精神食粮 (n.)** — 促成思考的材料（比喻）
  - "The workshop gave us a lot of **food** for thought."

### 152. meal
- **义项 1: 餐 (n.)** — 一次进食
  - "I usually have three **meals** a day."
- **义项 2: 一餐的量 (n.)** — 一次餐所吃的食物
  - "The restaurant serves a traditional Italian **meal**."
- **义项 3: 用餐时间 (n.)** — 吃饭的时间
  - "We had a business **meal** to discuss the partnership."

### 153. breakfast
- **义项 1: 早餐 (n.)** — 早晨的第一餐
  - "I had toast and coffee for **breakfast**."
- **义项 2: 吃早餐 (v.)** — 进行早餐
  - "We **breakfast** together every Sunday."

### 154. lunch
- **义项 1: 午餐 (n.)** — 中午的餐
  - "I brought a sandwich for **lunch** today."
- **义项 2: 吃午餐 (v.)** — 进行午餐
  - "Let us **lunch** at the new Italian place."

### 155. dinner
- **义项 1: 晚餐 (n.)** — 晚上的正餐
  - "We had **dinner** at a nice seafood restaurant."
- **义项 2: 宴会 (n.)** — 正式的晚宴
  - "The company hosted a **dinner** for the visiting executives."

### 156. snack
- **义项 1: 零食 (n.)** — 正餐之间吃的小食物
  - "I had a quick **snack** during the break."
- **义项 2: 吃零食 (v.)** — 吃小食
  - "Try not to **snack** too much between meals."

### 157. dessert
- **义项 1: 甜点 (n.)** — 餐后甜的食物
  - "We ordered chocolate cake for **dessert**."
- **义项 2: 甜品 (n.)** — 甜的食品类别
  - "The restaurant has a wide selection of **desserts**."

### 158. drink
- **义项 1: 饮料 (n.)** — 可饮用的液体
  - "Can I get a cold **drink**, please?"
- **义项 2: 饮酒 (v.)** — 饮用液体
  - "I **drank** a glass of water after the workout."
- **义项 3: 酗酒 (v.)** — 过量饮酒
  - "He does not **drink** for health reasons."

### 159. water
- **义项 1: 水 (n.)** — 无色无味的液体
  - "I need to drink more **water** every day."
- **义项 2: 浇水 (v.)** — 给植物供水
  - "Could you **water** my plants while I am away?"
- **义项 3: 水域 (n.)** — 大面积的水体
  - "The hotel is located near the **water**."

### 160. tea
- **义项 1: 茶 (n.)** — 茶叶泡制的饮料
  - "Would you like a cup of **tea**?"
- **义项 2: 下午茶 (n.)** — 下午小餐
  - "We were invited for afternoon **tea** at their house."

### 161. coffee
- **义项 1: 咖啡 (n.)** — 咖啡豆制成的饮料
  - "I need a cup of **coffee** to start my morning."
- **义项 2: 咖啡色 (n.)** — 浅棕色
  - "She wore a **coffee** colored coat."

### 162. milk
- **义项 1: 牛奶 (n.)** — 哺乳动物产的白色液体
  - "I have **milk** with my cereal every morning."
- **义项 2: 植物奶 (n.)** — 植物制成的类似奶的液体
  - "Soy **milk** is a popular alternative to dairy."

### 163. juice
- **义项 1: 果汁 (n.)** — 水果榨出的液体
  - "I ordered a glass of orange **juice**."
- **义项 2: 肉汁 (n.)** — 肉类的汁液
  - "The steak was cooked in its own **juice**."

### 164. beer
- **义项 1: 啤酒 (n.)** — 含酒精的谷物发酵饮料
  - "We went out for **beer** after work on Friday."
- **义项 2: 一杯啤酒 (n.)** — 一杯啤酒的量
  - "I will have a **beer** please."

### 165. wine
- **义项 1: 葡萄酒 (n.)** — 葡萄发酵的含酒精饮料
  - "We opened a bottle of red **wine** for the celebration."
- **义项 2: 品酒 (v.)** — 以品鉴的方式喝酒
  - "They like to **wine** and dine their clients."

### 166. bread
- **义项 1: 面包 (n.)** — 面粉烤制的食品
  - "I bought a loaf of **bread** from the bakery."
- **义项 2: 生计 (n.)** — 赚钱谋生的方式
  - "Writing is how I earn my daily **bread**."

### 167. rice
- **义项 1: 米饭 (n.)** — 煮熟的大米
  - "We had steamed **rice** with the stir-fry."
- **义项 2: 稻谷 (n.)** — 未加工的大米作物
  - "The farmers are planting **rice** in the fields."

### 168. noodle
- **义项 1: 面条 (n.)** — 面食条状食品
  - "I ordered a bowl of beef **noodle** soup."
- **义项 2: 面条类 (n.)** — 意大利面或亚洲面条的通称
  - "The **noodles** were cooked al dente."

### 169. pasta
- **义项 1: 意大利面 (n.)** — 意大利面食
  - "We had **pasta** with tomato sauce for dinner."
- **义项 2: 面食 (n.)** — 面团制成的各种形状的食品
  - "Fresh **pasta** tastes much better than dried."

### 170. meat
- **义项 1: 肉 (n.)** — 动物肌肉作为食物
  - "I do not eat red **meat** very often."
- **义项 2: 核心内容 (n.)** — 某事物的主要部分
  - "The **meat** of the report is in the analysis section."

### 171. chicken
- **义项 1: 鸡肉 (n.)** — 鸡作为食物
  - "I ordered grilled **chicken** with vegetables."
- **义项 2: 鸡 (n.)** — 家禽鸟类
  - "The **chickens** were walking around the farm."
- **义项 3: 胆小鬼 (n.)** — 懦弱的人（俚语）
  - "He is a **chicken** when it comes to public speaking."

### 172. beef
- **义项 1: 牛肉 (n.)** — 牛的肉
  - "We had **beef** stew for dinner last night."
- **义项 2: 抱怨 (n.)** — 不满的意见（俚语）
  - "What is your **beef** with the new scheduling system?"

### 173. pork
- **义项 1: 猪肉 (n.)** — 猪的肉
  - "I ordered the **pork** chop with mashed potatoes."
- **义项 2: 政府拨款 (n.)** — 政治中为地方争取的经费
  - "The senator brought **pork** to his home state."

### 174. fish
- **义项 1: 鱼 (n.)** — 水生动物
  - "We caught several **fish** during the trip."
- **义项 2: 鱼肉 (n.)** — 鱼作为食物
  - "I ordered grilled **fish** with lemon sauce."
- **义项 3: 寻找 (v.)** — 努力找到或搜寻
  - "I had to **fish** through my bag to find my keys."

### 175. egg
- **义项 1: 鸡蛋 (n.)** — 鸡产的蛋
  - "I had scrambled **eggs** for breakfast."
- **义项 2: 卵 (n.)** — 雌性动物产的卵
  - "The turtle laid its **eggs** on the beach."
- **义项 3: 鼓励 (v.)** — 鼓励或鼓动
  - "The team leader **egged** us on to finish the project early."

### 176. cheese
- **义项 1: 奶酪 (n.)** — 奶制品
  - "I put some **cheese** on top of the pasta."
- **义项 2: 芝士 (n.)** — 奶酪的俗称
  - "Swiss **cheese** has large holes in it."

### 177. butter
- **义项 1: 黄油 (n.)** — 从奶中提取的脂肪
  - "I spread **butter** on my toast."
- **义项 2: 涂黄油 (v.)** — 给某物涂黄油
  - "She **buttered** the bread before toasting it."

### 178. oil
- **义项 1: 油 (n.)** — 烹饪用油
  - "Heat some **oil** in the pan before adding the vegetables."
- **义项 2: 石油 (n.)** — 地下开采的燃料
  - "The price of crude **oil** has increased significantly."
- **义项 3: 润肤油 (n.)** — 用于皮肤护理的油
  - "I use coconut **oil** as a moisturizer."

### 179. salt
- **义项 1: 盐 (n.)** — 调味用的白色晶体
  - "The soup needs a little more **salt**."
- **义项 2: 加盐 (v.)** — 向食物中加入盐
  - "Do not forget to **salt** the pasta water."

### 180. pepper
- **义项 1: 胡椒粉 (n.)** — 辛辣的调味料
  - "Could you pass the **pepper**, please?"
- **义项 2: 甜椒 (n.)** — 大型的甜辣椒
  - "I sliced a red **pepper** for the salad."
- **义项 3: 撒胡椒粉 (v.)** — 撒胡椒粉在食物上
  - "He **peppered** his steak with black pepper."

### 181. sugar
- **义项 1: 糖 (n.)** — 甜味的晶体物质
  - "I take my coffee without **sugar**."
- **义项 2: 加糖 (v.)** — 加入糖使变甜
  - "She **sugared** her tea with two teaspoons."

### 182. sauce
- **义项 1: 酱汁 (n.)** — 液态调味品
  - "The pasta is served with a tomato **sauce**."
- **义项 2: 酱料 (n.)** — 搭配食物的调味汁
  - "I dipped the fries in ketchup **sauce**."

### 183. soup
- **义项 1: 汤 (n.)** — 液体食物
  - "I had a bowl of hot **soup** on the cold winter day."
- **义项 2: 出麻烦 (n.)** — 处在困境中（比喻）
  - "He got himself into **soup** by missing the deadline."

### 184. salad
- **义项 1: 沙拉 (n.)** — 混合的生蔬菜
  - "I ordered a Caesar **salad** with grilled chicken."
- **义项 2: 水果沙拉 (n.)** — 水果混合甜点
  - "The fruit **salad** was the perfect dessert."

### 185. vegetable
- **义项 1: 蔬菜 (n.)** — 作为食物的植物
  - "You should eat more green **vegetables**."
- **义项 2: 植物人的 (adj.)** — 失去意识的状态
  - "He was in a **vegetable** state after the accident."

### 186. fruit
- **义项 1: 水果 (n.)** — 甜的可食植物产品
  - "I eat fresh **fruit** every morning."
- **义项 2: 成果 (n.)** — 劳动或努力的产物
  - "The project is finally bearing **fruit**."

### 187. apple
- **义项 1: 苹果 (n.)** — 一种常见水果
  - "I ate an **apple** for a mid-afternoon snack."
- **义项 2: 苹果公司 (n.)** — Apple Inc.
  - "She works as a software engineer at **Apple**."

### 188. banana
- **义项 1: 香蕉 (n.)** — 黄色长形水果
  - "I added a sliced **banana** to my cereal."
- **义项 2: 疯的 (adj.)** — 疯癫或发狂（俚语）
  - "The constant alerts are driving me **bananas**."

### 189. orange
- **义项 1: 橙子 (n.)** — 柑橘类水果
  - "I peeled an **orange** for breakfast."
- **义项 2: 橙色 (adj.)** — 橙色的颜色
  - "She wore an **orange** dress to the party."

### 190. tomato
- **义项 1: 番茄 (n.)** — 红色多汁的蔬菜/水果
  - "I sliced a **tomato** for the sandwich."
- **义项 2: 番茄酱 (n.)** — 番茄制品
  - "The pasta sauce is made from fresh **tomatoes**."

### 191. potato
- **义项 1: 土豆 (n.)** — 地下茎蔬菜
  - "I baked a **potato** for dinner."
- **义项 2: 沙发土豆 (n.)** — 长期看电视不运动的人（比喻）
  - "He turned into a couch **potato** during the holiday break."

### 192. onion
- **义项 1: 洋葱 (n.)** — 有强烈气味的球形蔬菜
  - "I chopped an **onion** for the stir-fry."
- **义项 2: 洋葱味 (n.)** — 洋葱的气味
  - "My hands smell like **onion** after cutting it."

### 193. garlic
- **义项 1: 大蒜 (n.)** — 有强烈气味的调味用鳞茎
  - "I added two cloves of **garlic** to the sauce."
- **义项 2: 蒜味 (n.)** — 大蒜的气味
  - "The **garlic** bread smelled amazing."

### 194. cook
- **义项 1: 烹饪 (v.)** — 通过加热制作食物
  - "I **cooked** dinner for my family last night."
- **义项 2: 厨师 (n.)** — 以烹饪为职业的人
  - "The **cook** at that restaurant is from Italy."
- **义项 3: 伪造 (v.)** — 篡改数据或账目
  - "They were caught **cooking** the books."

### 195. boil
- **义项 1: 煮沸 (v.)** — 将液体加热到冒泡
  - "**Boil** the water before adding the pasta."
- **义项 2: 煮 (v.)** — 在沸水中烹饪
  - "I **boiled** the eggs for seven minutes."
- **义项 3: 情绪激动 (v.)** — 愤怒到极点（比喻）
  - "He was **boiling** with anger after the argument."

### 196. fry
- **义项 1: 煎/炸 (v.)** — 在热油中烹饪
  - "I **fried** the chicken pieces until they were golden brown."
- **义项 2: 油炸食品 (n.)** — 特别是炸薯条
  - "We ordered a side of **fries** with our burgers."

### 197. bake
- **义项 1: 烘烤 (v.)** — 在烤箱中烹饪
  - "I **baked** a chocolate cake for her birthday."
- **义项 2: 烤硬 (v.)** — 使变干变硬
  - "The sun **baked** the ground after the rain stopped."

### 198. roast
- **义项 1: 烤 (v.)** — 在烤箱或火上烹饪
  - "We **roasted** a chicken for Sunday dinner."
- **义项 2: 吐槽 (v.)** — 善意地开玩笑或嘲弄
  - "They **roasted** him at his retirement party."
- **义项 3: 烤的 (adj.)** — 经过烤制处理的
  - "I love the flavor of **roast** coffee beans."

### 199. grill
- **义项 1: 烧烤 (v.)** — 在烤架上烹饪
  - "We **grilled** burgers and hot dogs at the barbecue."
- **义项 2: 烤架 (n.)** — 烧烤用的金属架
  - "Place the steak on the **grill** and cook for five minutes."
- **义项 3: 盘问 (v.)** — 严厉或详细地提问
  - "The interviewer **grilled** me about my technical skills."

### 200. steam
- **义项 1: 蒸 (v.)** — 用蒸汽烹饪
  - "I **steamed** the vegetables to preserve their nutrients."
- **义项 2: 蒸汽 (n.)** — 水沸腾时产生的气体
  - "**Steam** rose from the hot coffee."
- **义项 3: 释放压力 (v.)** — 发泄压抑的情绪（比喻）
  - "He went for a run to **steam** off his frustration."

---

### Group 5: Daily Life — Travel & Transportation（旅行出行）

---

### 201. travel
- **义项 1: 旅行 (v.)** — 从一个地方到另一个地方
  - "I **travel** to Shanghai for business once a month."
- **义项 2: 旅行 (n.)** — 旅行行为
  - "**Travel** broadens the mind and enriches experience."
- **义项 3: 传播 (v.)** — 光或声音的传播
  - "Light **travels** faster than sound."

### 202. trip
- **义项 1: 旅程 (n.)** — 一次往返的出行
  - "We took a **trip** to the mountains last weekend."
- **义项 2: 绊倒 (v.)** — 被某物绊住
  - "I **tripped** over the cable and almost fell."
- **义项 3: 释放 (v.)** — 触发开关或机关
  - "He **tripped** the alarm when he opened the door."

### 203. journey
- **义项 1: 旅程 (n.)** — 长途旅行
  - "The **journey** from Beijing to London takes about 10 hours."
- **义项 2: 历程 (n.)** — 一段经历或发展过程
  - "Learning a new language is a rewarding **journey**."

### 204. flight
- **义项 1: 航班 (n.)** — 乘坐飞机的旅程
  - "My **flight** to Tokyo departs at 8 AM."
- **义项 2: 飞行 (n.)** — 在空中飞行的行为
  - "The **flight** from New York to London takes about seven hours."
- **义项 3: 逃跑 (n.)** — 为了躲避危险而逃
  - "The thief took **flight** when he heard the police siren."

### 205. bus
- **义项 1: 公交车 (n.)** — 公共汽车
  - "I take the **bus** to work every morning."
- **义项 2: 总线 (n.)** — 计算机内部传输数据的线路
  - "The data **bus** connects the CPU to the memory."

### 206. train
- **义项 1: 火车 (n.)** — 铁轨上行驶的交通工具
  - "We took the **train** from Beijing to Shanghai."
- **义项 2: 训练 (v.)** — 教导技能或知识
  - "The company **trains** new employees on the software."
- **义项 3: 瞄准 (v.)** — 将……指向
  - "He **trained** the camera on the speaker."

### 207. subway
- **义项 1: 地铁 (n.)** — 地下铁路系统
  - "The **subway** is the fastest way to get around the city."
- **义项 2: 地下通道 (n.)** — 行人地下通道
  - "Use the **subway** to cross the busy intersection."

### 208. taxi
- **义项 1: 出租车 (n.)** — 计程车
  - "We took a **taxi** to the airport because we were late."
- **义项 2: 滑行 (v.)** — 飞机在地面缓慢移动
  - "The plane **taxied** to the runway for takeoff."

### 209. car
- **义项 1: 汽车 (n.)** — 四轮机动车
  - "I drive my **car** to work every day."
- **义项 2: 车厢 (n.)** — 火车车厢
  - "The dining **car** is in the middle of the train."

### 210. bike
- **义项 1: 自行车 (n.)** — 两轮人力车
  - "I ride my **bike** to the subway station."
- **义项 2: 骑自行车 (v.)** — 骑自行车出行
  - "We **biked** along the river trail on Saturday."

### 211. walk
- **义项 1: 步行 (v.)** — 走路
  - "I **walk** to the grocery store because it is nearby."
- **义项 2: 散步 (n.)** — 为休闲而走
  - "Let us go for a **walk** in the park after lunch."
- **义项 3: 步行的距离 (n.)** — 步行需时
  - "The hotel is a five-minute **walk** from the station."

### 212. drive
- **义项 1: 开车 (v.)** — 驾驶车辆
  - "I **drove** to the office this morning."
- **义项 2: 驱车旅行 (n.)** — 乘车的行程
  - "It is a two-hour **drive** from the city to the beach."
- **义项 3: 推动 (v.)** — 使某事发生或发展
  - "The demand for faster delivery **drove** the innovation."

### 213. ride
- **义项 1: 骑乘 (v.)** — 骑自行车或摩托车
  - "I **rode** my bike along the mountain trail."
- **义项 2: 搭乘 (v.)** — 乘坐交通工具
  - "We **rode** the ferry across the river."
- **义项 3: 短途行程 (n.)** — 乘车的短暂旅程
  - "It is a short **ride** from here to the station."

### 214. fly
- **义项 1: 飞行 (v.)** — 乘坐飞机
  - "I **flew** to Singapore for the conference last month."
- **义项 2: 放风筝 (v.)** — 在空中飘动
  - "The children were **flying** kites in the park."
- **义项 3: 匆忙 (v.)** — 迅速移动或行动
  - "I had to **fly** out of the office to catch the last train."

### 215. plane
- **义项 1: 飞机 (n.)** — 航空器
  - "The **plane** took off at 8 AM sharp."
- **义项 2: 平面 (n.)** — 平整的表面
  - "The table has a smooth **plane** surface."

### 216. airport
- **义项 1: 机场 (n.)** — 飞机起降的场所
  - "We arrived at the **airport** two hours before departure."
- **义项 2: 空港 (n.)** — 航空交通枢纽
  - "The new **airport** terminal opened last year."

### 217. station
- **义项 1: 车站 (n.)** — 火车或巴士停靠点
  - "The train **station** is in the city center."
- **义项 2: 站 (n.)** — 特定功能的场所
  - "The gas **station** is on the corner of the street."

### 218. gate
- **义项 1: 登机口 (n.)** — 机场的登机入口
  - "Our flight departs from **gate** 23."
- **义项 2: 大门 (n.)** — 建筑物的入口
  - "Please meet me at the main **gate** of the office."
- **义项 3: 逻辑门 (n.)** — 计算机中的逻辑电路
  - "The **gate** in this circuit performs an AND operation."

### 219. platform
- **义项 1: 站台 (n.)** — 火车站的月台
  - "The train departs from **platform** 5."
- **义项 2: 平台 (n.)** — 技术平台或基础架构
  - "We built our application on the AWS **platform**."
- **义项 3: 讲台 (n.)** — 演讲或演出台
  - "The speaker stepped onto the **platform**."

### 220. ticket
- **义项 1: 票 (n.)** — 乘坐交通工具的凭证
  - "I bought a round-trip **ticket** to Paris."
- **义项 2: 罚单 (n.)** — 违规停车的罚款通知
  - "I got a parking **ticket** for parking in a no-parking zone."
- **义项 3: 入场券 (n.)** — 参加活动的凭证
  - "We have two **tickets** to the concert."

### 221. passport
- **义项 1: 护照 (n.)** — 国际旅行所需的官方证件
  - "Make sure your **passport** is valid for at least six months."
- **义项 2: 通行证 (n.)** — 达到某目的必要条件
  - "A university degree is often seen as a **passport** to a good job."

### 222. visa
- **义项 1: 签证 (n.)** — 入境某国的许可
  - "I applied for a tourist **visa** to visit the United States."
- **义项 2: 信用卡品牌 (n.)** — Visa 信用卡
  - "I paid with my **Visa** credit card."

### 223. luggage
- **义项 1: 行李 (n.)** — 旅行时的箱包
  - "My **luggage** was lost during the connecting flight."
- **义项 2: 行李量 (n.)** — 行李的总量
  - "We had too much **luggage** for the weekend trip."

### 224. hotel
- **义项 1: 酒店 (n.)** — 提供住宿的商业场所
  - "We stayed at a five-star **hotel** near the beach."
- **义项 2: 旅馆 (n.)** — 提供住宿和餐饮的地方
  - "The **hotel** offers free breakfast for all guests."

### 225. room
- **义项 1: 房间 (n.)** — 建筑内的隔间
  - "I booked a double **room** at the hotel."
- **义项 2: 空间 (n.)** — 可用的空间
  - "There is enough **room** in the car for everyone."
- **义项 3: 余地 (n.)** — 改变或回旋的余地
  - "There is little **room** for error in this deployment."

### 226. reservation
- **义项 1: 预订 (n.)** — 预先保留的位置
  - "I made a **reservation** at the restaurant for 7 PM."
- **义项 2: 保留意见 (n.)** — 怀疑或不同意
  - "I have some **reservations** about this approach."
- **义项 3: 预留 (n.)** — 保留的状态
  - "The **reservation** is under the name Smith."

### 227. check-in
- **义项 1: 办理入住 (n.)** — 到达酒店或机场时的登记
  - "Online **check-in** saves time at the airport."
- **义项 2: 报到 (v.)** — 通过系统登记到达
  - "Please **check in** at the front desk when you arrive."
- **义项 3: 联系汇报 (v.)** — 定期联系汇报情况
  - "I will **check in** with the team after the meeting."

### 228. map
- **义项 1: 地图 (n.)** — 地理区域的图形表示
  - "I use the **map** app on my phone for navigation."
- **义项 2: 映射 (v.)** — 建立对应关系
  - "The function **maps** user IDs to their profile data."

### 229. direction
- **义项 1: 方向 (n.)** — 前进的方位
  - "We were walking in the wrong **direction**."
- **义项 2: 用法说明 (n.)** — 使用指南
  - "Follow the **directions** on the medicine bottle carefully."
- **义项 3: 管理指导 (n.)** — 领导和指导
  - "Under his **direction**, the team completed the project ahead of schedule."

### 230. left
- **义项 1: 左边 (adj.)** — 方位词，左侧
  - "Turn **left** at the next traffic light."
- **义项 2: 离开 (v.)** — leave 的过去式
  - "She **left** the office early yesterday."
- **义项 3: 左派 (adj.)** — 政治上的左翼
  - "He holds **left** leaning political views."

### 231. right
- **义项 1: 右边 (adj.)** — 方位词，右侧
  - "The bank is on the **right** side of the street."
- **义项 2: 正确 (adj.)** — 符合事实或标准
  - "Your assessment of the situation is **right**."
- **义项 3: 权利 (n.)** — 法律或道德上应得的
  - "Every employee has the **right** to a safe working environment."

### 232. straight
- **义项 1: 直行的 (adv.)** — 不转弯
  - "Go **straight** for two blocks, then turn left."
- **义项 2: 直的 (adj.)** — 没有弯曲
  - "Draw a **straight** line between the two points."
- **义项 3: 直接地 (adv.)** — 不绕弯子
  - "I went **straight** home after the meeting."

### 233. turn
- **义项 1: 转弯 (v.)** — 改变方向
  - "**Turn** right at the next intersection."
- **义项 2: 轮流 (n.)** — 轮到的机会
  - "It is your **turn** to present the status update."
- **义项 3: 转变 (v.)** — 改变状态
  - "The leaves **turn** yellow in autumn."

### 234. street
- **义项 1: 街道 (n.)** — 城市中的道路
  - "The restaurant is located on Main **Street**."
- **义项 2: 街头 (n.)** — 街上的环境
  - "You can find street food vendors on every **street** corner."

### 235. road
- **义项 1: 公路 (n.)** — 连接两地的道路
  - "We drove along a winding mountain **road**."
- **义项 2: 路 (n.)** — 路径或方法（比喻）
  - "There is a long **road** ahead before the system is stable."

### 236. highway
- **义项 1: 高速公路 (n.)** — 高速行驶的大型道路
  - "We took the **highway** to get to the airport quickly."
- **义项 2: 快速路 (n.)** — 城市间的主要交通线
  - "The **highway** was congested during rush hour."

### 237. traffic
- **义项 1: 交通 (n.)** — 路上车辆的数量
  - "The **traffic** was terrible this morning due to an accident."
- **义项 2: 网络流量 (n.)** — 网络传输的数据量
  - "The website experienced heavy **traffic** during the sale."
- **义项 3: 非法交易 (n.)** — 非法买卖
  - "The police are investigating the drug **traffic**."

### 238. parking
- **义项 1: 停车 (n.)** — 停放车辆的行为
  - "**Parking** is very expensive in the city center."
- **义项 2: 停车场 (n.)** — 停车的区域
  - "The hotel has a free **parking** lot for guests."

### 239. distance
- **义项 1: 距离 (n.)** — 两点间的间隔
  - "The **distance** between the two cities is 200 kilometers."
- **义项 2: 远距离 (n.)** — 远处的空间
  - "I could see the mountain in the **distance**."
- **义项 3: 疏远 (v.)** — 保持距离
  - "He tried to **distance** himself from the controversial decision."

### 240. arrive
- **义项 1: 到达 (v.)** — 到达某个地方
  - "We **arrived** at the airport just in time for our flight."
- **义项 2: 到来 (v.)** — 事件或时期的发生
  - "The new technology **arrived** at the perfect time."

### 241. depart
- **义项 1: 出发 (v.)** — 离开去往某地
  - "The train **departs** from platform 3 at 9 AM."
- **义项 2: 离开 (v.)** — 从某地离开
  - "He **departed** from the company after five years."
- **义项 3: 偏离 (v.)** — 不遵循标准或常规
  - "The implementation **departed** from the original design specifications."

### 242. leave
- **义项 1: 离开 (v.)** — 从某地走开
  - "I **leave** the office at 6 PM every day."
- **义项 2: 休假 (n.)** — 放假或请假的期间
  - "I am taking a week of **leave** next month."
- **义项 3: 留下 (v.)** — 将某物留在某处
  - "Please **leave** your feedback in the comments section."

### 243. destination
- **义项 1: 目的地 (n.)** — 前往的地方
  - "Our **destination** is the coastal city of Qingdao."
- **义项 2: 目标 (n.)** — 最终要达到的目标
  - "Profitability is the company's ultimate **destination**."

### 244. route
- **义项 1: 路线 (n.)** — 从一地到另一地的路径
  - "The bus **route** goes through the city center."
- **义项 2: 路由 (v.)** — 按特定路径发送
  - "The system **routes** requests to the nearest server."

### 245. tour
- **义项 1: 游览 (n.)** — 有向导的参观
  - "We took a guided **tour** of the old city."
- **义项 2: 巡回 (n.)** — 一系列访问或演出
  - "The band is on a world **tour**."
- **义项 3: 游览 (v.)** — 参观访问
  - "We **toured** the museum for two hours."

### 246. guide
- **义项 1: 导游 (n.)** — 带领游览的人
  - "The **guide** explained the history of the temple."
- **义项 2: 指南 (n.)** — 提供信息的资料
  - "The user **guide** explains how to configure the software."
- **义项 3: 引导 (v.)** — 带领某人通过或到达
  - "She **guided** the team through the migration process."

### 247. sightseeing
- **义项 1: 观光 (n.)** — 参观著名景点
  - "We spent the day **sightseeing** in the historic district."
- **义项 2: 观光活动 (n.)** — 游览名胜的行为
  - "The **sightseeing** tour included all the major attractions."

### 248. landmark
- **义项 1: 地标 (n.)** — 著名且易识别的建筑或地点
  - "The Eiffel Tower is the most famous **landmark** in Paris."
- **义项 2: 里程碑 (n.)** — 历史或发展中的重大事件
  - "The invention of the internet was a **landmark** in human history."

### 249. beach
- **义项 1: 海滩 (n.)** — 海边沙石覆盖的区域
  - "We spent the afternoon relaxing on the **beach**."
- **义项 2: 沙滩 (n.)** — 形成海滩的沙地
  - "The **beach** was crowded with tourists during the holiday."

### 250. island
- **义项 1: 岛屿 (n.)** — 被水环绕的陆地
  - "We took a ferry to the **island** for a day trip."
- **义项 2: 孤立区域 (n.)** — 与周围隔离的区域
  - "The old town is an **island** of history in the modern city."

---

### Group 6: Weather, Nature & Environment（天气自然与环境）

---

### 251. weather
- **义项 1: 天气 (n.)** — 大气的状态
  - "The **weather** forecast says it will rain tomorrow."
- **义项 2: 经受住 (v.)** — 安全度过困难时期
  - "The company **weathered** the economic downturn successfully."

### 252. climate
- **义项 1: 气候 (n.)** — 长期的天气模式
  - "The **climate** in this region is warm and humid."
- **义项 2: 氛围 (n.)** — 社会或政治环境
  - "The **climate** of innovation attracts top talent to the company."

### 253. temperature
- **义项 1: 温度 (n.)** — 冷热的程度
  - "The **temperature** reached 35 degrees Celsius yesterday."
- **义项 2: 发烧 (n.)** — 体温异常升高的状态
  - "She has a **temperature** and should stay in bed."
- **义项 3: 氛围 (n.)** — 紧张或激动的程度
  - "The **temperature** of the discussion was rising."

### 254. hot
- **义项 1: 热的 (adj.)** — 温度高
  - "It is very **hot** outside today."
- **义项 2: 辣的 (adj.)** — 辛辣的
  - "This curry is very **hot**."
- **义项 3: 热门的 (adj.)** — 受欢迎的或流行的
  - "Python is a **hot** skill in the job market right now."

### 255. warm
- **义项 1: 温暖的 (adj.)** — 温度适中的高
  - "It was a **warm** spring morning."
- **义项 2: 暖心的 (adj.)** — 友好和热情的
  - "We received a **warm** welcome from the team."
- **义项 3: 热身 (v.)** — 使变暖或做准备
  - "I need to **warm** up before the run."

### 256. cool
- **义项 1: 凉爽的 (adj.)** — 温度偏低但舒适
  - "The evening breeze was **cool** and refreshing."
- **义项 2: 酷的 (adj.)** — 时尚或令人印象深刻的
  - "That is a **cool** new gadget you have there."
- **义项 3: 冷静 (v.)** — 使平静或降温
  - "Let us **cool** down and discuss this rationally."

### 257. cold
- **义项 1: 冷的 (adj.)** — 温度低
  - "The water is too **cold** to swim in."
- **义项 2: 感冒 (n.)** — 呼吸道病毒感染
  - "I caught a **cold** and stayed home from work."
- **义项 3: 冷淡 (adj.)** — 不友好的
  - "She gave me a **cold** stare after the argument."

### 258. freezing
- **义项 1: 极冷的 (adj.)** — 非常冷
  - "It is **freezing** outside, so wear a heavy coat."
- **义项 2: 结冰 (v.)** — 水变成冰
  - "The lake **freezes** in winter."
- **义项 3: 冻结 (v.)** — 停止移动或运行
  - "The application **froze** and I had to restart it."

### 259. sunny
- **义项 1: 晴朗的 (adj.)** — 阳光充足的
  - "It is a **sunny** day with clear blue skies."
- **义项 2: 乐观的 (adj.)** — 性格开朗的
  - "She has a **sunny** personality."

### 260. cloudy
- **义项 1: 多云的 (adj.)** — 天空有云
  - "It was a **cloudy** day with no sunshine."
- **义项 2: 模糊的 (adj.)** — 不清晰的
  - "The instructions were **cloudy** and hard to follow."

### 261. rainy
- **义项 1: 下雨的 (adj.)** — 有雨的天气
  - "The **rainy** season lasts from June to August."
- **义项 2: 多雨的 (adj.)** — 降雨频繁的
  - "Seattle is known for its **rainy** weather."

### 262. windy
- **义项 1: 有风的 (adj.)** — 风大的
  - "It was a **windy** day, perfect for flying kites."
- **义项 2: 话多的 (adj.)** — 说话绕弯子的
  - "His speech was long and **windy**."

### 263. snowy
- **义项 1: 下雪的 (adj.)** — 有雪的
  - "We had a **snowy** winter this year."
- **义项 2: 积雪的 (adj.)** — 覆盖着雪的
  - "The **snowy** mountains looked beautiful."

### 264. sun
- **义项 1: 太阳 (n.)** — 恒星，提供光和热
  - "The **sun** rises in the east and sets in the west."
- **义项 2: 晒太阳 (v.)** — 沐浴阳光
  - "We **sunned** ourselves on the beach."
- **义项 3: 日光 (n.)** — 太阳的光
  - "Open the curtains and let the **sun** in."

### 265. rain
- **义项 1: 雨 (n.)** — 从云中落下的水滴
  - "The **rain** started falling in the afternoon."
- **义项 2: 下雨 (v.)** — 降雨
  - "It **rained** all day yesterday."
- **义项 3: 大量涌入 (n.)** — 如雨般到来的大量事物
  - "There was a **rain** of questions after the presentation."

### 266. wind
- **义项 1: 风 (n.)** — 流动的空气
  - "The strong **wind** blew the leaves off the trees."
- **义项 2: 卷绕 (v.)** — 缠绕或转动
  - "Please **wind** the cable after use."
- **义项 3: 结束 (v.)** — 逐渐停止
  - "The meeting **wound** down after two hours."

### 267. snow
- **义项 1: 雪 (n.)** — 从云中落下的冰晶
  - "The children were playing in the **snow**."
- **义项 2: 下雪 (v.)** — 降雪
  - "It **snowed** heavily during the night."

### 268. cloud
- **义项 1: 云 (n.)** — 天空中悬浮的小水滴
  - "Dark **clouds** appeared on the horizon."
- **义项 2: 云计算 (n.)** — 通过互联网提供的计算服务
  - "We migrated our infrastructure to the **cloud**."
- **义项 3: 阴霾 (n.)** — 令人担忧的氛围
  - "A **cloud** of uncertainty hung over the project."

### 269. storm
- **义项 1: 暴风雨 (n.)** — 强烈的天气现象
  - "The **storm** caused widespread power outages."
- **义项 2: 风暴 (n.)** — 激烈的争议或情绪爆发
  - "The decision caused a **storm** of protest."
- **义项 3: 猛烈攻击 (v.)** — 强行冲入
  - "The team **stormed** through the sprint backlog."

### 270. sky
- **义项 1: 天空 (n.)** — 地球之上的空间
  - "The **sky** was clear and blue after the rain."
- **义项 2: 天际 (n.)** — 视野中的天空区域
  - "The stars were shining in the night **sky**."

### 271. air
- **义项 1: 空气 (n.)** — 呼吸的气体
  - "The **air** in the mountains is fresh and clean."
- **义项 2: 航空 (n.)** — 空中运输
  - "We shipped the goods by **air**."
- **义项 3: 气氛 (n.)** — 给人的感觉或印象
  - "There was an **air** of excitement before the product launch."

### 272. water
- **义项 1: 水 (n.)** — 无色透明的液体
  - "We need clean drinking **water**." (same as Group 4 #159 — revisiting for environmental context)
- **义项 2: 水域 (n.)** — 大面积的水
  - "The **waters** of the lake are crystal clear."
- **义项 3: 供水 (v.)** — 向某地供水
  - "This river **waters** the entire valley."

### 273. fire
- **义项 1: 火 (n.)** — 燃烧产生的光和热
  - "We built a **fire** to keep warm at the campsite."
- **义项 2: 解雇 (v.)** — 开除
  - "The company **fired** several employees during the restructuring."
- **义项 3: 激发 (v.)** — 激起热情或灵感
  - "The mentor's words **fired** my ambition to learn."

### 274. earth
- **义项 1: 地球 (n.)** — 我们生活的星球
  - "The **Earth** orbits the sun once every 365 days."
- **义项 2: 土壤 (n.)** — 地面的泥土
  - "The **earth** in the garden is rich and dark."
- **义项 3: 接地 (n.)** — 电路中连接大地的线
  - "Make sure the device is properly **earth** connected."

### 275. ground
- **义项 1: 地面 (n.)** — 固体表面
  - "The leaves fell to the **ground**."
- **义项 2: 依据 (n.))** — 理由或基础
  - "There are strong **grounds** for believing the system is secure."
- **义项 3: 磨碎 (v.)** — 将固体压成粉末
  - "I **ground** the coffee beans before brewing."

### 276. mountain
- **义项 1: 山 (n.)** — 高大的自然地形
  - "We hiked up the **mountain** to watch the sunrise."
- **义项 2: 大量 (n.)** — 巨大的数量
  - "I have a **mountain** of work to finish before the deadline."

### 277. hill
- **义项 1: 小山 (n.)** — 比山低的地形隆起
  - "The house sits on top of a **hill** with a beautiful view."
- **义项 2: 斜坡 (n.)** — 上坡或下坡
  - "I had to push my bike up the steep **hill**."

### 278. river
- **义项 1: 河流 (n.)** — 天然的水道
  - "The **river** flows through the city into the sea."
- **义项 2: 大量流动 (n.)** — 大量的连续流动
  - "A **river** of data flows through the system every second."

### 279. lake
- **义项 1: 湖 (n.)** — 被陆地包围的水体
  - "We went swimming in the **lake** during summer."
- **义项 2: 湖泊 (n.)** — 大面积的静水
  - "The **lake** was frozen over in winter."

### 280. ocean
- **义项 1: 海洋 (n.)** — 巨大的海水体
  - "The **ocean** covers more than 70 percent of the Earth's surface."
- **义项 2: 大量 (n.)** — 巨大的数量或范围
  - "There is an **ocean** of information available on the internet."

### 281. sea
- **义项 1: 海 (n.)** — 海洋的一部分
  - "The **sea** was calm and beautiful at sunset."
- **义项 2: 大量 (n.)** — 大量的某物
  - "We were faced with a **sea** of data to analyze."

### 282. wave
- **义项 1: 波浪 (n.)** — 水面起伏的运动
  - "The **waves** crashed against the rocks."
- **义项 2: 挥手 (v.)** — 举手做出示意
  - "She **waved** goodbye from the platform."
- **义项 3: 浪潮 (n.)** — 一波又一波的事物
  - "There was a **wave** of layoffs across the tech industry."

### 283. coast
- **义项 1: 海岸 (n.)** — 陆地与海洋的交界
  - "We drove along the **coast** for a scenic road trip."
- **义项 2: 沿海地区 (n.)** — 靠近海洋的区域
  - "The **coast** is popular with tourists during summer."
- **义项 3: 惯性滑行 (v.)** — 不费力地移动
  - "The car **coasted** down the hill with the engine off."

### 284. forest
- **义项 1: 森林 (n.)** — 大面积树木覆盖的区域
  - "The **forest** was home to many wild animals."
- **义项 2: 森林般的 (n.)** — 密集的混乱状态
  - "The codebase had become a **forest** of tangled dependencies."

### 285. tree
- **义项 1: 树 (n.)** — 有木本主干的高大植物
  - "We planted a **tree** in the garden."
- **义项 2: 树状图 (n.)** — 层级结构的数据表示
  - "The decision **tree** helps us evaluate all possible outcomes."

### 286. plant
- **义项 1: 植物 (n.)** — 活的生物体
  - "I water my house **plants** every Sunday."
- **义项 2: 工厂 (n.)** — 工业生产设施
  - "The manufacturing **plant** employs over 500 workers."
- **义项 3: 种植 (v.)** — 将种子或植物放入土壤
  - "We **planted** vegetables in the backyard."

### 287. flower
- **义项 1: 花 (n.)** — 植物的繁殖器官
  - "The garden was full of beautiful **flowers** in spring."
- **义项 2: 开花 (v.)** — 植物长出花
  - "The cherry trees **flower** in early April."

### 288. grass
- **义项 1: 草 (n.)** — 绿色覆盖地面的植物
  - "The **grass** needs to be mowed, it is getting too long."
- **义项 2: 草坪 (n.)** — 修剪过的草地
  - "The children were playing on the **grass**."

### 289. leaf
- **义项 1: 叶子 (n.)** — 植物进行光合作用的器官
  - "The **leaves** turn red and yellow in autumn."
- **义项 2: 书页 (n.)** — 书或纸的一张
  - "I tore a **leaf** out of my notebook."
- **义项 3: 翻看 (v.)** — 快速翻看
  - "I **leafed** through the document to find the relevant section."

### 290. seed
- **义项 1: 种子 (n.)** — 植物繁殖的微粒
  - "I planted **seeds** in the garden and waited for them to grow."
- **义项 2: 种子选手 (n.)** — 比赛中被列为种子选手的
  - "He is the top **seed** in the tennis tournament."
- **义项 3: 播种 (v.)** — 引发或开始某事
  - "The early success **seeded** the company's expansion plans."

### 291. animal
- **义项 1: 动物 (n.)** — 非植物的活生物
  - "The zoo has a wide variety of **animals** from around the world."
- **义项 2: 动物的 (adj.)** — 与动物有关的
  - "**Animal** welfare is an important ethical concern."

### 292. bird
- **义项 1: 鸟 (n.)** — 有羽毛和翅膀的动物
  - "A **bird** built a nest in the tree outside my window."
- **义项 2: 飞行物 (n.)** — 各种飞行器或鸟类
  - "The early **bird** catches the worm."

### 293. environment
- **义项 1: 自然环境 (n.)** — 生态系统的总和
  - "We need to protect the **environment** for future generations."
- **义项 2: 工作环境 (n.)** — 工作或生活的条件
  - "The company provides a supportive work **environment**."
- **义项 3: 运行环境 (n.)** — 系统或软件运行的条件
  - "The application runs in a containerized **environment**."

### 294. pollution
- **义项 1: 污染 (n.)** — 对环境的有害物质排放
  - "Air **pollution** in the city has reached dangerous levels."
- **义项 2: 噪声污染 (n.)** — 过多的噪音
  - "Noise **pollution** from the construction site disturbed the neighborhood."

### 295. recycle
- **义项 1: 回收利用 (v.)** — 将废品加工再利用
  - "We **recycle** paper, plastic, and glass in our office."
- **义项 2: 循环使用 (v.)** — 再次使用
  - "The system **recycles** unused connections to improve efficiency."

### 296. season
- **义项 1: 季节 (n.)** — 一年的四个时段之一
  - "Autumn is my favorite **season** because of the cool weather."
- **义项 2: 旺季 (n.)** — 特定活动的繁忙期
  - "The holiday **season** is the busiest time for retailers."
- **义项 3: 调味 (v.)** — 给食物添加味道
  - "She **seasoned** the chicken with salt and pepper."

### 297. spring
- **义项 1: 春天 (n.)** — 一年中冬季之后的季节
  - "**Spring** is a beautiful time when flowers start to bloom."
- **义项 2: 弹簧 (n.)** — 有弹性的螺旋形金属
  - "The **spring** in the mattress needs replacing."
- **义项 3: 泉水 (n.)** — 从地下涌出的水
  - "We drank fresh water from the natural **spring**."

### 298. summer
- **义项 1: 夏天 (n.)** — 一年中最热的季节
  - "We usually go to the beach during **summer**."
- **义项 2: 度夏 (v.)** — 在夏季某地度过
  - "They **summer** in their cottage by the lake."

### 299. autumn
- **义项 1: 秋天 (n.)** — 一年中介于夏冬之间的季节
  - "The leaves change color in **autumn**." (also called fall)
- **义项 2: 秋季 (n.)** — 秋季的时期
  - "The conference is scheduled for this **autumn**."

### 300. winter
- **义项 1: 冬天 (n.)** — 一年中最冷的季节
  - "**Winter** is the coldest season of the year."
- **义项 2: 过冬 (v.))** — 在冬季生活或待在某个地方
  - "The birds **winter** in warmer regions."

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

### 易混淆词对比

**1. salary vs. wage（月薪 vs. 时薪）**
- "She receives an annual **salary** of 120,000 dollars."（年薪制，通常按月发放）
- "The workers are paid an hourly **wage** of 20 dollars."（时薪制，按工作时长计酬）
- 关键区别：salary = 固定年薪（白领），wage = 按小时计算（蓝领/兼职）

**2. refund vs. exchange（退款 vs. 换货）**
- "I requested a **refund** because the product was defective."（退钱）
- "I asked for an **exchange** because the shoes did not fit."（换同款其他尺码）
- 关键区别：refund = 退款（钱退给你），exchange = 换货（换成别的，不退钱）

**3. travel vs. trip（泛指旅行 vs. 具体旅程）**
- "I **travel** frequently for business."（抽象的旅行行为，不可数）
- "We took a **trip** to the beach last weekend."（一次具体的旅程，可数）
- 关键区别：travel = 抽象概念/行为，trip = 具体的某一次出行

**4. weather vs. climate（天气 vs. 气候）**
- "The **weather** today is rainy and cold."（天气——短期的状态）
- "The **climate** of this region is warm and humid throughout the year."（气候——长期的模式）
- 关键区别：weather = 今天/明天怎么样（短期），climate = 常年怎么样（长期）

**5. ocean vs. sea（大洋 vs. 海）**
- "The Pacific **Ocean** is the largest ocean on Earth."（大洋——四大洋之一）
- "The Mediterranean **Sea** is surrounded by Europe, Africa, and Asia."（海——大洋的一部分，通常靠近陆地）
- 关键区别：ocean 比 sea 更大更深，sea 常是 ocean 的边缘部分

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
- [ ] 我能在工作邮件或口语中正确使用商务名词
- [ ] 我能在日常场景中使用购物、饮食、旅行的词汇
- [ ] 我了解自然环境相关词汇的含义

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
> "Yesterday was a busy day. In the morning, I **was reviewing** a pull request when the manager **asked** me to join an urgent meeting. The meeting was about the **budget** **constraint** for our Q3 project. We **brainstormed** several solutions and finally **agreed** on a **plan** that **balanced** cost with **quality**. After lunch, I **finished** the review and **left** the office at 6 PM. The **weather** was nice, so I **walked** to the **subway** **station** instead of taking a **taxi**."

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
- 一个 trip 经历的描述
- 一个工作中的沟通故事
- 一个你最近学到的关于 environment 的知识

写完后用本周学的语法标签（主语、谓语、宾语、状语从句等）标注你的句子。

**下周生存贴士：**
- 描述过去的事 → 条件反射用 Simple Past（90% 情况足够）
- 强调"正在……的时候突然……" → Past Continuous + when + Simple Past
- 想说"已经……之前就……了" → Past Perfect（had done）
- 分析复杂句 → 先找主谓宾主干，再找所有从句的引导词
- 30 个新词一天 → 不要背，要用。用新词写 2 个句子 > 背 10 遍

---

> **下周预告：** Week 4 将学习**将来时态**——be going to vs. will vs. Present Continuous for future，以及更多高频场景词汇。下周见。
