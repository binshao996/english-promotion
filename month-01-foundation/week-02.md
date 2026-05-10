# Week 02: 一般现在时 & 现在进行时 + 300 核心词汇 + 复杂句拆解

> 目标：巩固一般现在时和现在进行时的核心用法，重点掌握**复杂句的句法结构**（并列句、复合句、关系从句、状语从句），并系统扩展 300 个高频词汇。本周的训练让你能读懂并写出包含多个从句的工程英语句子。

---

## 1. Grammar: Simple Present & Present Continuous + Complex Sentences

### Part A: Quick Reference — Simple Present & Present Continuous

**Simple Present（一般现在时）—— "一直这样"**
- **客观事实 / 技术真理：** Water **boils** at 100°C. / REST APIs **are** stateless.
- **习惯 / 常规操作：** We **deploy** every Monday. / The team **holds** standup at 9:30.
- **固定时间表：** The sprint **starts** Wednesday. / The release **is** next Friday.
- **当前状态 / 所属：** This **belongs** to the platform team. / The server **has** 64GB RAM.
- **形式：** 主语 + 动词原形（第三人称单数加 -s/-es）
- **否定：** do/does + not + 动词原形
- **疑问：** Do/Does + 主语 + 动词原形?

**Present Continuous（现在进行时）—— "正在发生 / 暂时如此"**
- **此刻进行：** I **'m debugging** the production issue.
- **临时阶段：** We **'re migrating** to a new database this quarter.
- **近期安排：** I **'m meeting** the PM tomorrow.
- **形式：** am/is/are + V-ing
- **否定：** am/is/are + not + V-ing
- **疑问：** Am/Is/Are + 主语 + V-ing?

**状态动词（不用进行时）：** know, understand, believe, think（认为）, belong, own, have（拥有）, like, love, hate, need, seem, look（看起来）, sound, contain, consist, depend

> ❌ I **am knowing** the answer. → ✅ I **know** the answer.
> ❌ This **is belonging** to our team. → ✅ This **belongs** to our team.

---

### Part B: Complex Sentence Breakdowns（复杂句拆解）

下面 6 个句子来自真实的工程场景。每个句子都包含**多个从句**或**连接结构**。我们逐词拆解句法成分，标注中文语法术语，帮助你理解复杂句的骨架。

---

#### Sentence 1

> While the frontend team is working on the new interface, the backend engineers are refactoring the API endpoints to improve performance and reduce latency.

```
完整句法拆解：

While                 连词 — 引导时间状语从句（"当……时"）
the frontend team     主语（名词短语）— 前端团队
is working            谓语（现在进行时，第三人称单数）— 正在工作
on the new interface  介词短语作状语 — 在新的界面上
,                    逗号分隔从句与主句
the backend engineers 主语（名词短语）— 后端工程师
are refactoring       谓语（现在进行时，复数）— 正在重构
the API endpoints     宾语（名词短语）— API 端点
to improve            不定式短语作目的状语 — 为了提高
performance           宾语（名词）— 性能
and                   并列连词 — 连接两个不定式的宾语
reduce latency        不定式短语（省略 to，与 to improve 并列）— 降低延迟

整体结构：
[While 引导的时间状语从句] + [逗号] + [主句]
主句内部：[主语] + [谓语] + [宾语] + [to 不定式目的状语]
目的状语内部：[to improve A and (to) reduce B] — 并列结构

理解技巧：
这个句子描述的是"两个团队同时在做不同的事"。
while 从句用现在进行时表示"正在进行"，主句也用现在进行时。
两个动作同时发生——这是 while 的核心用法。

常见错误：
❌ While the frontend team is working on the new interface, the backend engineers refactor the API endpoints.
（这里用一般现在时 refactor 就变成了"每次前端团队工作时，后端都会重构"——这是反复发生的意思，不是此刻同时发生的事）
✅ 两边都用现在进行时，表示"此刻同时进行"。
```

---

#### Sentence 2

> The database schema that we designed last sprint supports both relational queries and document-based access patterns, which makes the system much more flexible.

```
完整句法拆解：

The database schema   主语（名词短语）— 数据库模式
that                 关系代词（引导定语从句，修饰 schema）— 那个
we                   定语从句中的主语（代词）— 我们
designed             定语从句中的谓语（及物动词，过去时）— 设计了
last sprint          定语从句中的时间状语（名词短语）— 上个 sprint
supports             主句谓语（及物动词，第三人称单数）— 支持
both relational queries   并列宾语第一部分（名词短语）— 关系型查询和
and document-based access patterns  并列宾语第二部分（名词短语）— 基于文档的访问模式
,                    逗号，分隔非限制性定语从句
which                关系代词（指代前面整件事）— 这
makes                定语从句中的谓语（及物动词）— 使得
the system           定语从句中的宾语 — 系统
much more flexible   宾语补足语（形容词短语）— 灵活得多

整体结构：
[主语 + that 定语从句] + [谓语] + [both A and B 并列宾语] + [, which 非限制性定语从句]

关键概念：
1. that 引导的定语从句是限制性的（restrictive）——去掉它，句子的意思就变了。
   如果只说 "The database schema supports..."，读者不知道是哪个 schema。
2. which 引导的是非限制性定语从句（non-restrictive），前面有逗号。
   它修饰的是整句话，而不是某个词——"这（整件事）使得系统更灵活"。
3. "both...and..." 连接两个并列的名词短语作 supports 的宾语。

常见错误：
❌ The database schema that we designed last sprint support both...
（主语 schema 是第三人称单数，谓语 supports 必须加 -s）
✅ The database schema ... supports ...
```

---

#### Sentence 3

> I am currently migrating our pipeline from Jenkins to GitHub Actions because the team needs faster feedback on pull requests and more reliable deployment workflows.

```
完整句法拆解：

I                    主语（代词）— 我
am migrating         谓语（现在进行时）— 正在迁移
currently            副词作状语（表示"当前"）— 目前
our pipeline         宾语（名词短语）— 我们的流水线
from Jenkins         介词短语作状语（迁移的起点）— 从 Jenkins
to GitHub Actions    介词短语作状语（迁移的目标）— 到 GitHub Actions
because              连词（引导原因状语从句）— 因为
the team             原因从句的主语（名词短语）— 团队
needs                原因从句的谓语（及物动词）— 需要
faster feedback      原因从句的宾语第一部分（名词短语）— 更快的反馈
on pull requests     介词短语修饰 feedback — 关于拉取请求
and                  并列连词 — 和
more reliable deployment workflows  原因从句的宾语第二部分（名词短语）— 更可靠的部署工作流

整体结构：
[主句：主语 + 谓语 + 宾语 + 地点状语] + [because 原因状语从句]

复杂之处：
1. because 引导的原因状语从句中有并列宾语：
   "needs [faster feedback on PRs] and [more reliable deployment workflows]"
   两个宾语都是名词短语，共享同一个谓语 needs。
2. "currently" 是现在进行时的标志词——强调"当前这个迁移阶段"。
3. from...to... 结构清晰标示了迁移的方向。

常见错误：
❌ I am currently migrating our pipeline from Jenkins to GitHub Actions because the team need faster feedback.
（team 是集合名词，在美式英语中视为单数，应加 -s → needs）
✅ ...because the team needs...
```

---

#### Sentence 4

> The container orchestration layer automatically scales instances when the CPU threshold exceeds 80 percent, which prevents downtime during traffic spikes.

```
完整句法拆解：

The container orchestration layer  主语（名词短语）— 容器编排层
automatically            副词作方式状语 — 自动地
scales                   谓语（及物动词，第三人称单数）— 伸缩
instances                宾语（名词）— 实例
when                     连词（引导时间状语从句）— 当……时
the CPU threshold        时间从句的主语（名词短语）— CPU 阈值
exceeds                  时间从句的谓语（及物动词，第三人称单数）— 超过
80 percent               时间从句的宾语（名词短语）— 80%
,                        逗号
which                    关系代词（指代前面整件事）— 这
prevents                 定语从句的谓语（及物动词）— 防止
downtime                 定语从句的宾语（不可数名词）— 停机
during traffic spikes    介词短语作时间状语 — 在流量高峰期间

整体结构：
[主句：主语 + 状语 + 谓语 + 宾语] + [when 时间状语从句] + [, which 非限制性定语从句]

三层层级：
1. 主句描述"编排层自动伸缩实例"——这是一般现在时，描述系统的默认行为。
2. when 从句是触发条件——"当 CPU 超过 80% 时"。
3. which 从句补充说明整件事的结果——"这防止了停机"。

关键语法点：
- 主句和 when 从句都用一般现在时（系统行为的条件逻辑）。
- which 从句修饰的是前面整个 "when..." 条件过程，不是某个名词。

常见错误：
❌ ...when the CPU threshold will exceed 80 percent...
（条件/时间从句中用一般现在时表将来，不需要 will）
✅ ...when the CPU threshold exceeds 80 percent...
```

---

#### Sentence 5

> We are seeing increased latency in the payment service, and this is affecting the checkout flow for users in Asia-Pacific who expect sub-second response times.

```
完整句法拆解：

We                    主语（代词）— 我们
are seeing            谓语（现在进行时）— 正在观察到
increased latency     宾语（名词短语）— 增加的延迟
in the payment service  介词短语作定语或状语 — 在支付服务中
,                     逗号
and                   并列连词 — 连接两个并列分句
this                  第二个分句的主语（代词）— 这
is affecting          第二个分句的谓语（现在进行时）— 正在影响
the checkout flow     第二个分句的宾语（名词短语）— 结账流程
for users             介词短语（受益者）— 对用户来说
in Asia-Pacific       介词短语作定语（修饰 users）— 亚太地区的
who                   关系代词（引导定语从句，修饰 users）— 他们
expect                定语从句的谓语（及物动词）— 期望
sub-second response times  定语从句的宾语（名词短语）— 亚秒级响应时间

整体结构：
[分句 1：主语 + 谓语 + 宾语 + 地点状语] + [and] + [分句 2：主语 + 谓语 + 宾语 + 定语从句]

关键语法点：
1. and 连接两个并列分句，两个分句都用现在进行时——表示"正在发生的问题链"。
2. "increased latency"——increased 是过去分词作前置定语，相当于 "latency that has increased"。
3. "who expect..."——who 引导的定语从句修饰 "users"，关系代词 who 在从句中作主语。
4. "sub-second" 是一个复合形容词 = "less than one second"。

语义理解：
这个句子描述了一个因果链：
  我们注意到延迟增加 → 这影响了结账流程 → 用户期望亚秒级响应
用 and 连接两个并列分句，第二个分句的 "this" 指代第一个分句描述的整个情况。

常见错误：
❌ ...users in Asia-Pacific who are expecting sub-second response times.
（这里 expect 是"期望/要求"，是状态动词，一般不用进行时。除非想强调"此刻正在期待"——但通常不这么用）
✅ ...who expect sub-second response times.（一般现在时——"用户期望亚秒级响应"是常态）
```

---

#### Sentence 6

> Every engineer who works on the platform knows that clean code matters, but few people actually have the time to refactor legacy modules that were written years ago.

```
完整句法拆解：

Every engineer        主语（名词短语）— 每一位工程师
who                   关系代词（引导定语从句，修饰 engineer）— 他/她
works                 定语从句的谓语（不及物动词，第三人称单数）— 工作
on the platform       介词短语作状语 — 在这个平台上
knows                 主句谓语（及物动词，第三人称单数）— 知道
that                  连词（引导宾语从句）— 即
clean code            宾语从句的主语（名词短语）— 干净的代码
matters               宾语从句的谓语（不及物动词，第三人称单数）— 重要
,                     逗号
but                   并列连词（表转折）— 但是
few people            第二个并列分句的主语（名词短语）— 很少有人
actually              副词作状语 — 实际上
have                  谓语（及物动词，复数）— 有
the time              宾语 — 时间
to refactor           不定式短语作定语（修饰 time）— 去重构
legacy modules        不定式的宾语（名词短语）— 遗留模块
that                  关系代词（引导定语从句，修饰 modules）— 那些
were written          定语从句的谓语（被动语态，过去时）— 被编写
years ago             时间状语 — 多年前

整体结构：
[主语 + who 定语从句] + [谓语 + that 宾语从句] + [, but] + [主语 + 谓语 + 宾语 + 不定式定语 + that 定语从句]

四个从句嵌套分析：
1. who works on the platform — 定语从句修饰 Every engineer（限制性——不是所有工程师，是"在这个平台上工作的"）
2. that clean code matters — that 引导的宾语从句作 knows 的宾语（"知道……这件事"）
3. but — 并列连词，连接两个并列分句，表转折
4. that were written years ago — 定语从句修饰 legacy modules

语义对比：
前半句（before but）：所有人都"知道"好代码很重要（认知上的共识）
后半句（after but）：但很少有人有"时间"去重构遗留模块（行动上的差距）
这种 "Everyone knows X, but few actually Y" 的结构在工程讨论中非常常见。

常见错误：
❌ Every engineer who works on the platform knows that clean code is mattering.
（matter 是状态动词，不用进行时。is mattering 是错误的）
✅ ...knows that clean code matters.
（一般现在时——"好代码很重要"是一个不变的客观事实）
```

---

## 2. Vocabulary: 300 Core Words

### Group 1: Infrastructure & Networking Nouns（基础设施与网络名词）— 50 词

---

### 1. bandwidth
- **义项 1: 带宽 (n.)** — 网络在单位时间内能传输的最大数据量
  - "Our video conferencing quality dropped because the **bandwidth** was too low during peak hours."
- **义项 2: 处理能力 (n.)** — 系统或个人能同时处理的任务量
  - "I don't have the mental **bandwidth** to review another PR today."
- **义项 3: 频率范围 (n.)** — 通信中使用的频谱宽度
  - "The radio system operates across a 20 MHz **bandwidth** in the 5 GHz spectrum."

---

### 2. cache
- **义项 1: 缓存 (n.)** — 用于加速数据读取的临时存储
  - "We cleared the Redis **cache** to force the application to reload user sessions."
- **义项 2: 缓存区 (n.)** — CPU 或浏览器中的高速暂存区域
  - "The browser **cache** stores static assets so the page loads faster on repeat visits."
- **义项 3: 隐藏存储 (n.)** — 存储临时副本的机制
  - "The DNS **cache** on your laptop might still point to the old server IP address."

---

### 3. CDN
- **义项 1: 内容分发网络 (n.)** — 全球分布的服务器网络，加速内容交付
  - "We use a **CDN** to serve images and videos to users around the world with low latency."
- **义项 2: CDN 服务 (n.)** — 提供 CDN 功能的云服务（如 Cloudflare、Akamai）
  - "Our **CDN** cached the static files at edge locations in 30 cities globally."
- **义项 3: 边缘节点网络 (n.)** — 靠近用户的服务器节点集合
  - "The **CDN** automatically routes users to the nearest edge server for faster downloads."

---

### 4. cluster
- **义项 1: 集群 (n.)** — 一组协同工作的服务器或节点
  - "We deployed the application across a Kubernetes **cluster** with ten worker nodes."
- **义项 2: 数据库集群 (n.)** — 一组数据库服务器，提供高可用和负载分担
  - "The database **cluster** has a primary node and two read replicas for failover."
- **义项 3: 聚集 (n.)** — 在统计或数据分析中的密集区域
  - "The monitoring dashboard shows a **cluster** of errors originating from the same IP range."

---

### 5. data center
- **义项 1: 数据中心 (n.)** — 存放服务器和网络设备的物理设施
  - "Our primary **data center** is located in Virginia, with a backup in Oregon."
- **义项 2: 数据中心服务 (n.)** — 提供计算和存储资源的托管服务
  - "The company shut down its on-premise **data center** and moved everything to the cloud."
- **义项 3: 机房 (n.)** — 企业内部放置服务器的小型空间
  - "The **data center** maintains a temperature of 22 degrees Celsius to prevent overheating."

---

### 6. DNS
- **义项 1: 域名系统 (n.)** — 将域名解析为 IP 地址的系统
  - "The **DNS** resolution failed because the nameserver returned an incorrect A record."
- **义项 2: DNS 服务器 (n.)** — 执行域名解析的服务器
  - "We switched our **DNS** provider to reduce the TTL and speed up propagation."
- **义项 3: 域名配置 (n.)** — 域名的 DNS 记录集合
  - "Make sure the **DNS** has the correct CNAME record pointing to the load balancer."

---

### 7. domain
- **义项 1: 域名 (n.)** — 网站或服务的互联网地址
  - "We registered a new **domain** for the developer portal at dev.example.com."
- **义项 2: 领域 (n.)** — 知识或活动的范围
  - "Microservice architecture is not my strongest **domain** — I specialize in frontend."
- **义项 3: 域 (n.)** — 在网络或系统中的管理边界
  - "The application is deployed across multiple **domains** for security isolation."

---

### 8. firewall
- **义项 1: 防火墙 (n.)** — 控制网络流量的安全系统
  - "The **firewall** blocked all incoming traffic except HTTPS on port 443."
- **义项 2: 防火墙规则 (n.)** — 控制访问权限的策略集合
  - "We updated the **firewall** to allow the new monitoring tool access to the database."
- **义项 3: 心理防线 (n.)** — 用于比喻人际或组织之间的障碍
  - "There's a **firewall** between the dev team and the operations team that we need to break down."

---

### 9. gateway
- **义项 1: 网关 (n.)** — 连接不同网络的入口设备或服务
  - "The API **gateway** routes requests to the appropriate microservice based on the URL path."
- **义项 2: 支付网关 (n.)** — 处理在线支付的服务
  - "We integrated Stripe as our payment **gateway** for processing international transactions."
- **义项 3: 入口 (n.)** — 进入系统的通道
  - "The authentication **gateway** validates the JWT token before forwarding the request."

---

### 10. host
- **义项 1: 主机 (n.)** — 运行应用程序或服务的服务器
  - "The **host** that runs the Jenkins server is running out of disk space."
- **义项 2: 托管方 (n.)** — 提供托管服务的平台
  - "We use AWS as our cloud **host** for all production workloads."
- **义项 3: 宿主 (n.)** — 在虚拟化中运行虚拟机的物理机或操作系统
  - "The hypervisor manages resources across all virtual machines running on the physical **host**."

---

### 11. IP address
- **义项 1: IP 地址 (n.)** — 网络设备的唯一数字标识
  - "The server's **IP address** changed after we migrated to a different subnet."
- **义项 2: 公网/内网 IP (n.)** — 区分内部和外部地址
  - "We assigned a static **IP address** to the load balancer so DNS records don't break."
- **义项 3: IP 定位 (n.)** — 基于 IP 地址的地理位置
  - "The system blocked the **IP address** after detecting 100 failed login attempts."

---

### 12. load balancer
- **义项 1: 负载均衡器 (n.)** — 分发流量的设备或服务
  - "The **load balancer** distributes incoming traffic across three backend servers to prevent overload."
- **义项 2: 负载均衡策略 (n.)** — 路由流量的算法或规则
  - "We configured the **load balancer** to use round-robin scheduling for even distribution."
- **义项 3: 健康检查 (n.)** — 负载均衡器的后端健康监控功能
  - "The **load balancer** automatically removes unhealthy instances from the rotation."

---

### 13. microservice
- **义项 1: 微服务 (n.)** — 独立部署的小型服务
  - "Each **microservice** runs in its own container and communicates via gRPC."
- **义项 2: 微服务架构 (n.)** — 将应用拆分为多个小型服务的架构模式
  - "The team is breaking the monolith into **microservices** to improve deploy frequency."
- **义项 3: 微服务实例 (n.)** — 微服务的一个运行实例
  - "We scaled the payment **microservice** to five replicas to handle the checkout load."

---

### 14. network
- **义项 1: 网络 (n.)** — 连接多台计算机的通信系统
  - "The corporate **network** has a strict firewall policy that blocks most peer-to-peer traffic."
- **义项 2: 人际关系网 (n.)** — 有联系的人群
  - "I built a strong **network** of developers through attending tech conferences."
- **义项 3: 网络覆盖 (n.)** — 通信服务的覆盖范围
  - "The Wi-Fi **network** in the office covers all three floors but struggles in the basement."

---

### 15. node
- **义项 1: 节点 (n.)** — 集群或网络中的单个计算单元
  - "One Kubernetes **node** went down, and the pods were automatically rescheduled to other nodes."
- **义项 2: 树节点 (n.)** — 树形数据结构中的元素
  - "Each **node** in the binary tree has a left and right child reference."
- **义项 3: 端点 (n.)** — 区块链或分布式系统中的成员
  - "Every **node** in the blockchain network validates new transactions before adding them to the ledger."

---

### 16. packet
- **义项 1: 数据包 (n.)** — 网络传输的最小数据单元
  - "Each **packet** contains a header with the source and destination IP address."
- **义项 2: 丢包 (n.)** — 数据包在传输过程中丢失
  - "We noticed **packet** loss during the video call, which caused audio dropouts."
- **义项 3: 包捕获 (n.)** — 网络诊断中抓取的数据单元
  - "The engineer analyzed the captured **packets** using Wireshark to find the connection issue."

---

### 17. pod
- **义项 1: Pod (n.)** — Kubernetes 中最小的部署单元，包含一个或多个容器
  - "Each **pod** in the cluster runs a single container instance of the application."
- **义项 2: Pod 组 (n.)** — 共享存储和网络的容器组
  - "The **pod** has two sidecar containers that handle logging and metrics collection."
- **义项 3: 豆荚（生态类比）(n.)** — 用于比喻包含多个单元的容器结构
  - "The design pattern groups related services into a **pod** for easier management."

---

### 18. port
- **义项 1: 端口 (n.)** — 网络通信的出入通道编号
  - "The application listens on **port** 8080 by default, but we mapped it to 80 in production."
- **义项 2: 端口转发 (n.)** — 将流量从一个端口导向另一个端口
  - "We set up **port** forwarding to access the database from our local machine."
- **义项 3: 接口 (n.)** — 硬件上的物理连接口
  - "The server has four USB **ports** and two Ethernet ports on the back panel."

---

### 19. protocol
- **义项 1: 协议 (n.)** — 网络通信的规则和标准
  - "HTTP/2 is a binary **protocol** that supports multiplexing and header compression."
- **义项 2: 交互协议 (n.)** — 不同系统之间的约定和规范
  - "We designed a custom **protocol** using Protocol Buffers for service-to-service communication."
- **义项 3: 行为规范 (n.)** — 人际或团队中的行为准则
  - "The team follows a strict **protocol** for handling security incidents and data breaches."

---

### 20. proxy
- **义项 1: 代理服务器 (n.)** — 代表客户端转发请求的中间服务器
  - "All outbound traffic goes through a corporate **proxy** that logs every request."
- **义项 2: 反向代理 (n.)** — 代表后端接收请求的中间层
  - "Nginx acts as a reverse **proxy** that forwards requests to the application server."
- **义项 3: 代理模式 (n.)** — 设计模式中的代理，控制对对象的访问
  - "The **proxy** pattern adds a layer of indirection between the client and the real service."

---

### 21. registry
- **义项 1: 镜像仓库 (n.)** — 存储和管理 Docker 镜像的服务
  - "We pushed the built image to our private container **registry** with the latest tag."
- **义项 2: 注册中心 (n.)** — 微服务注册与发现的服务
  - "Each service registers itself with the service **registry** on startup and deregisters on shutdown."
- **义项 3: 注册表 (n.)** — 操作系统或软件的配置数据库
  - "Modifying the Windows **registry** incorrectly can cause system instability."

---

### 22. router
- **义项 1: 路由器 (n.)** — 在网络间转发数据包的硬件设备
  - "The office **router** crashed overnight, and nobody had internet access this morning."
- **义项 2: 路由 (n.)** — 前端中根据 URL 切换视图的机制
  - "The Vue **router** navigates between pages without a full browser refresh."
- **义项 3: 路由表 (n.)** — 决定数据包去向的规则表
  - "The **router** maintains a routing table that maps IP prefixes to next-hop addresses."

---

### 23. server
- **义项 1: 服务器 (n.)** — 提供服务的计算机或程序
  - "The **server** is running Ubuntu 22.04 with 32 GB of RAM and 4 CPUs."
- **义项 2: 服务端程序 (n.)** — 在后台运行并响应请求的软件
  - "We restarted the web **server** after updating the SSL certificate."
- **义项 3: 招待员 (n.)** — 餐厅或场合中提供服务的人
  - "The **server** brought our menus and recommended today's special."

---

### 24. service mesh
- **义项 1: 服务网格 (n.)** — 管理微服务间通信的基础设施层
  - "We introduced a **service mesh** to handle service discovery and mutual TLS between microservices."
- **义项 2: 边车代理 (n.)** — 服务网格中的 sidecar 代理
  - "The **service mesh** injects an Envoy sidecar into each pod to intercept traffic."
- **义项 3: 流量管理 (n.)** — 通过服务网格控制请求路由
  - "The **service mesh** allows us to implement canary deployments by splitting traffic percentages."

---

### 25. subnet
- **义项 1: 子网 (n.)** — IP 网络的逻辑分段
  - "We placed the database servers in a private **subnet** that has no direct internet access."
- **义项 2: 子网掩码 (n.)** — 定义网络前缀长度的值
  - "The **subnet** mask 255.255.255.0 allows up to 254 hosts in the same segment."
- **义项 3: 子网划分 (n.)** — 网络分段的设计策略
  - "Our VPC has three public **subnets** and three private subnets across different availability zones."

---

### 26. topology
- **义项 1: 拓扑结构 (n.)** — 网络或系统中节点的连接方式
  - "The network **topology** follows a hub-and-spoke model with the main office at the center."
- **义项 2: 架构拓扑 (n.)** — 系统架构中组件的关系布局
  - "The application **topology** diagram shows how each service connects to the database layer."
- **义项 3: 拓扑学 (n.)** — 数学中研究空间性质的学科
  - "Understanding network **topology** helps you identify single points of failure in the system."

---

### 27. traffic
- **义项 1: 网络流量 (n.)** — 网络上传输的数据量
  - "The server can handle up to 10,000 concurrent requests before **traffic** overwhelms it."
- **义项 2: 访客流量 (n.)** — 访问网站或应用的用户数量
  - "Our **traffic** doubles every Black Friday, so we auto-scale the cluster in advance."
- **义项 3: 交通 (n.)** — 道路上的车辆流动
  - "I was late to the standup because the **traffic** on the highway was backed up for miles."

---

### 28. tunnel
- **义项 1: 隧道 (n.)** — 通过加密在公共网络上建立的安全通道
  - "We use an SSH **tunnel** to securely access the staging database from our laptops."
- **义项 2: VPN 隧道 (n.)** — 虚拟专用网络的加密连接
  - "The VPN **tunnel** ensures that all data sent between the office and the cloud is encrypted."
- **义项 3: 端口隧道 (n.)** — 将本地端口转发到远程服务的机制
  - "I set up a **tunnel** from port 3000 on my machine to the remote development server."

---

### 29. VPC
- **义项 1: 虚拟私有云 (n.)** — 云中的隔离网络环境
  - "We created a **VPC** with a CIDR block of 10.0.0.0/16 for our production environment."
- **义项 2: VPC 对等连接 (n.)** — 两个 VPC 之间的网络连接
  - "The **VPC** peering connection allows the staging and production environments to communicate."
- **义项 3: VPC 安全组 (n.)** — 控制 VPC 内流量的规则
  - "We configured the **VPC** security group to only allow inbound traffic from specific IP ranges."

---

### 30. VPN
- **义项 1: 虚拟专用网络 (n.)** — 通过公网加密连接到私有网络
  - "Employees must connect to the **VPN** before accessing internal company resources."
- **义项 2: VPN 客户端 (n.)** — 用于建立 VPN 连接的软件
  - "I installed the company **VPN** client on my laptop to work remotely."
- **义项 3: 翻墙工具 (n.)** — 用于绕过地理限制的加密通道
  - "Some developers use a **VPN** to access documentation that is blocked in certain regions."

---

### 31. webhook
- **义项 1: Webhook (n.)** — 事件触发时自动发送的 HTTP 回调
  - "We set up a **webhook** that notifies Slack whenever a deployment succeeds or fails."
- **义项 2: Webhook 端点 (n.)** — 接收回调请求的 URL
  - "The GitHub **webhook** sends a POST request to our CI server on every push event."
- **义项 3: 事件通知机制 (n.)** — 基于事件的自动通知系统
  - "The payment system sends a **webhook** to our server when the transaction status changes."

---

### 32. availability zone
- **义项 1: 可用区 (n.)** — 云服务商的一个独立物理区域
  - "We deploy our application across three **availability zones** to ensure high availability."
- **义项 2: 故障隔离区 (n.)** — 一个可用区的故障不影响其他区
  - "If one **availability zone** goes down, the load balancer routes traffic to the remaining zones."
- **义项 3: 数据中心分组 (n.)** — 同一区域内的多个数据中心集合
  - "Each **availability zone** contains one or more data centers with redundant power and networking."

---

### 33. bare metal
- **义项 1: 裸金属服务器 (n.)** — 直接运行在硬件上的物理服务器（无虚拟化层）
  - "We use **bare metal** servers for workloads that require direct hardware access."
- **义项 2: 裸机 (n.)** — 没有安装操作系统的计算机硬件
  - "The IT team deployed the OS image onto the **bare metal** server using PXE boot."
- **义项 3: 高性能计算 (n.)** — 需要充分利用硬件性能的场景
  - "Database performance improved significantly after we migrated from VMs to **bare metal**."

---

### 34. benchmark
- **义项 1: 基准测试 (n.)** — 衡量系统性能的标准化测试
  - "We ran a **benchmark** comparing PostgreSQL and MySQL performance under the same workload."
- **义项 2: 基准 (n.)** — 用于比较的参考标准
  - "The industry **benchmark** for API response time is under 200 milliseconds."
- **义项 3: 标杆 (n.)** — 值得模仿的优秀范例
  - "Google's deployment pipeline serves as a **benchmark** for CI/CD best practices."

---

### 35. client
- **义项 1: 客户端 (n.)** — 请求服务的应用程序或设备
  - "The mobile **client** sends a request to the server every 30 seconds to sync data."
- **义项 2: 客户 (n.)** — 购买产品或服务的个人或公司
  - "We are meeting with a new **client** tomorrow to discuss their cloud migration needs."
- **义项 3: 客户程序 (n.)** — 用于访问特定服务的软件
  - "The Git **client** allows developers to clone, commit, and push changes to the remote repository."

---

### 36. cloud
- **义项 1: 云 (n.)** — 通过互联网提供的按需计算资源
  - "We migrated our entire infrastructure to the **cloud** to reduce maintenance overhead."
- **义项 2: 云服务 (n.)** — 云平台提供的具体服务
  - "The **cloud** automatically scales resources based on the current demand."
- **义项 3: 云端存储 (n.)** — 存储在远程服务器的数据
  - "I backed up all my photos to the **cloud** so I can access them from any device."

---

### 37. compute
- **义项 1: 计算资源 (n.)** — 服务器的 CPU 和内存处理能力
  - "The new instance type provides 4 vCPUs of **compute** and 16 GB of memory."
- **义项 2: 计算服务 (n.)** — 云平台提供的托管计算能力
  - "AWS Lambda is a serverless **compute** service that runs code without provisioning servers."
- **义项 3: 算力 (n.)** — 执行数学或逻辑运算的能力
  - "The machine learning model requires significant GPU **compute** for training."

---

### 38. core
- **义项 1: 核心 (n.)** — CPU 的独立处理单元
  - "This server has 16 **cores** and can run 32 threads simultaneously with hyper-threading."
- **义项 2: 核心功能 (n.)** — 系统或产品的核心部分
  - "The **core** of the application is the real-time messaging engine, everything else is optional."
- **义项 3: 核心价值 (n.)** — 最重要的原则或本质
  - "At the **core** of our engineering culture is the belief in continuous improvement."

---

### 39. dashboard
- **义项 1: 仪表盘 (n.)** — 显示关键指标的监控界面
  - "The monitoring **dashboard** shows CPU usage, memory consumption, and request latency in real time."
- **义项 2: 管理面板 (n.)** — 系统的后台管理界面
  - "Admins can manage user permissions and view activity logs from the **dashboard**."
- **义项 3: 驾驶舱 (n.)** — 汽车或飞机的仪表板
  - "The car's **dashboard** displays the speed, fuel level, and engine temperature."

---

### 40. encryption
- **义项 1: 加密 (n.)** — 将数据转为密文以防止未授权访问
  - "All sensitive customer data is protected with AES-256 **encryption** at rest."
- **义项 2: 加密算法 (n.)** — 执行加密和解密的数学算法
  - "TLS **encryption** ensures that data transferred between the browser and server is secure."
- **义项 3: 加密密钥 (n.)** — 用于加解密数据的密钥
  - "The **encryption** key is stored in a hardware security module and rotated every 90 days."

---

### 41. Ethernet
- **义项 1: 以太网 (n.)** — 最常见的局域网有线网络技术
  - "The office uses Gigabit **Ethernet** for all desktop computers to ensure fast file transfers."
- **义项 2: 以太网电缆 (n.)** — 连接设备的物理网线
  - "I replaced the old **Ethernet** cable with a Cat6 one to get faster network speeds."
- **义项 3: 以太网端口 (n.)** — 设备上的 RJ45 网络接口
  - "Most modern laptops no longer include an **Ethernet** port, requiring a USB adapter."

---

### 42. failover
- **义项 1: 故障切换 (n.)** — 当主系统故障时自动切换到备用系统
  - "The database **failover** process takes less than 30 seconds before the replica becomes the new primary."
- **义项 2: 故障转移配置 (n.)** — 高可用架构中的冗余机制
  - "We tested the **failover** mechanism by killing the primary server to verify the backup takes over."
- **义项 3: 灾备切换 (n.)** — 在灾难恢复场景中的切换操作
  - "The **failover** to the disaster recovery site was successful, and service resumed within five minutes."

---

### 43. firmware
- **义项 1: 固件 (n.)** — 嵌入硬件设备中的软件
  - "The router's **firmware** is outdated and needs to be updated to fix the security vulnerability."
- **义项 2: 固件升级 (n.)** — 更新设备固件以修复问题或增加功能
  - "We scheduled a **firmware** update for all network switches during the maintenance window."
- **义项 3: 设备驱动 (n.)** — 硬件设备的底层控制程序
  - "The SSD **firmware** was patched to address a bug that caused data corruption in rare cases."

---

### 44. hardware
- **义项 1: 硬件 (n.)** — 计算机的物理组件
  - "The new server **hardware** arrived yesterday and needs to be racked and configured."
- **义项 2: 硬件设备 (n.)** — 具体的物理设备
  - "We upgraded the network **hardware** to support 10-gigabit connections between data centers."
- **义项 3: 硬件加速 (n.)** — 使用专用硬件提高性能的技术
  - "Video encoding is much faster with **hardware** acceleration using a dedicated GPU chip."

---

### 45. hypervisor
- **义项 1: 虚拟机监视器 (n.)** — 管理和运行虚拟机的软件层
  - "The **hypervisor** allocates CPU and memory resources to each virtual machine running on the host."
- **义项 2: Type 1 虚拟化 (n.)** — 直接运行在硬件上的裸机型虚拟化
  - "VMware ESXi is a Type 1 **hypervisor** that runs directly on the server hardware without an OS."
- **义项 3: Type 2 虚拟化 (n.)** — 运行在操作系统上的寄居型虚拟化
  - "VirtualBox is a Type 2 **hypervisor** that runs as an application on your desktop OS."

---

### 46. infrastructure
- **义项 1: 基础设施 (n.)** — 运行系统所需的硬件、网络和服务
  - "Our cloud **infrastructure** includes VPCs, load balancers, databases, and compute instances."
- **义项 2: 基础设施即代码 (n.)** — 用代码管理基础设施的实践
  - "We manage our entire **infrastructure** using Terraform with version control and code review."
- **义项 3: 公共基础设施 (n.)** — 社会层面的基础设施（道路、电网等）
  - "The city's internet **infrastructure** needs improvement to support remote work effectively."

---

### 47. log
- **义项 1: 日志 (n.)** — 系统事件的记录文件
  - "I checked the server **log** to find out why the application crashed at 3 AM."
- **义项 2: 日志记录 (n.)** — 记录日志的行为
  - "We centralized all service **logs** in Elasticsearch for easy searching and analysis."
- **义项 3: 原木 (n.)** — 木材砍伐后的段木
  - "The cabin was built from large **logs** that were cut from the surrounding forest."

---

### 48. lock
- **义项 1: 锁 (n.)** — 防止并发访问的资源控制机制
  - "The database **lock** caused a deadlock when two transactions tried to update the same row."
- **义项 2: 同步锁 (n.)** — 编程中防止竞态条件的互斥机制
  - "We use a distributed **lock** with Redis to ensure only one instance runs the scheduled task."
- **义项 3: 物理锁 (n.)** — 用于关闭柜子或门的锁具
  - "The server rack has a **lock** on the door to prevent unauthorized physical access."

---

### 49. heartbeat
- **义项 1: 心跳信号 (n.)** — 系统定期发送的存活信号
  - "The monitoring system expects a **heartbeat** from each service every 30 seconds."
- **义项 2: 心跳检测 (n.)** — 通过心跳信号检查服务健康状态
  - "When the **heartbeat** stops, the orchestrator marks the instance as unhealthy and restarts it."
- **义项 3: 心跳节奏 (n.)** — 人或动物的心跳
  - "My **heartbeat** was racing after the sprint planning session because there were so many tasks."

---

### 50. bus
- **义项 1: 总线 (n.)** — 计算机内部传输数据的通信系统
  - "The PCI Express **bus** connects the GPU directly to the CPU for high-speed data transfer."
- **义项 2: 消息总线 (n.)** — 服务之间传递消息的中间件
  - "We use Kafka as an event **bus** to decouple microservices and enable asynchronous communication."
- **义项 3: 公交车 (n.)** — 公共交通工具
  - "I take the **bus** to the office every morning because it is cheaper than driving."

---

### Group 2: Tech Process & Workflow Nouns（技术流程与工作流名词）— 50 词

---

### 51. sprint
- **义项 1: Sprint (n.)** — Scrum 中的一个开发周期
  - "We completed 30 story points this **sprint**, which is 20% more than last sprint."
- **义项 2: 冲刺 (n.)** — 短时间内全力以赴的努力
  - "The team is in a final **sprint** to get the release ready before the holiday break."
- **义项 3: 短跑 (n.)** — 田径的短距离跑步项目
  - "He won the 100-meter **sprint** at the company sports day."

---

### 52. iteration
- **义项 1: 迭代 (n.)** — 开发流程的一个循环周期
  - "In the second **iteration**, we added input validation and error handling based on user feedback."
- **义项 2: 版本迭代 (n.)** — 产品改进的版本
  - "The first **iteration** of the dashboard was basic, but we improved it significantly in v2."
- **义项 3: 循环 (n.)** — 重复执行的过程
  - "The algorithm converges to a solution after several **iterations** of the training loop."

---

### 53. milestone
- **义项 1: 里程碑 (n.)** — 项目中的关键节点或阶段目标
  - "Reaching the beta release is an important **milestone** in our product development timeline."
- **义项 2: 关键成果 (n.)** — 需要完成的可交付成果
  - "The first **milestone** includes the authentication system and user profile management."
- **义项 3: 历史事件 (n.)** — 人生或历史中的重要事件
  - "Getting my first full-time job as a developer was a major **milestone** in my career."

---

### 54. deliverable
- **义项 1: 可交付物 (n.)** — 项目完成后提交的成果
  - "The main **deliverable** for this quarter is the new reporting module."
- **义项 2: 交付件 (n.)** — 合同中规定的必须交付的产品或文档
  - "All project **deliverables** must be reviewed by the QA team before submission."
- **义项 3: 输出成果 (n.)** — 工作产出的具体形式
  - "The design **deliverable** includes wireframes, prototypes, and a style guide."

---

### 55. roadmap
- **义项 1: 路线图 (n.)** — 产品未来发展的计划安排
  - "The product **roadmap** shows that we will launch the mobile app in Q3."
- **义项 2: 技术路线图 (n.)** — 技术团队的计划安排
  - "The engineering **roadmap** includes migrating to Kubernetes and adopting microservices."
- **义项 3: 路线图（出行）(n.)** — 旅行或行程的计划
  - "We planned a **roadmap** for our road trip with stops at five national parks."

---

### 56. backlog
- **义项 1: 待办事项列表 (n.)** — Scrum 中待处理的任务列表
  - "The product owner prioritized the **backlog** before the sprint planning meeting."
- **义项 2: 积压工作 (n.)** — 累积的未完成工作
  - "The support team has a **backlog** of 50 unresolved tickets that need attention."
- **义项 3: 积压订单 (n.)** — 尚未处理的订单
  - "The manufacturing **backlog** grew because the supplier couldn't deliver raw materials on time."

---

### 57. standup
- **义项 1: 站会 (n.)** — 每日团队短会
  - "In today's **standup**, I mentioned that I'm stuck on the database migration issue."
- **义项 2: 同步会议 (n.)** — 团队成员汇报进度和阻碍的会议
  - "The daily **standup** is held at 9:30 AM and should last no longer than 15 minutes."
- **义项 3: 站立姿势 (n.)** — 直立的状态
  - "My back hurts from sitting all day, so I try to do a **standup** desk for part of the shift."

---

### 58. retrospective
- **义项 1: 回顾会议 (n.)** — Sprint 结束后团队回顾和改进的会议
  - "In the **retrospective**, we identified that unclear requirements caused most of the delays."
- **义项 2: 回顾 (n.)** — 对过去一段时间的总结反思
  - "A personal **retrospective** at the end of each quarter helps me track my growth."
- **义项 3: 回顾展 (n.)** — 回顾艺术或成果的展览
  - "The museum held a **retrospective** of the artist's work spanning 50 years."

---

### 59. velocity
- **义项 1: 速率 (n.)** — 团队每个 Sprint 完成的故事点数
  - "Our team's **velocity** has been stable at around 25 story points per sprint."
- **义项 2: 速度 (n.)** — 事物移动或发展的速度
  - "The **velocity** of code reviews improved after we introduced the pair-review system."
- **义项 3: 速率（物理）(n.)** — 物理学中的矢量速度
  - "The **velocity** of the data packet through the fiber optic cable approaches the speed of light."

---

### 60. burn-down chart
- **义项 1: 燃尽图 (n.)** — 显示剩余工作量的图表
  - "The **burn-down chart** shows that we are slightly behind schedule halfway through the sprint."
- **义项 2: 进度跟踪图 (n.)** — 跟踪工作完成率的可视化工具
  - "Our **burn-down chart** has a flat line this week because the team was at a conference."
- **义项 3: 迭代追踪 (n.)** — 帮助团队判断是否能按时完成冲刺的分析工具
  - "If the **burn-down chart** shows a negative trend, we may need to descope some features."

---

### 61. user story
- **义项 1: 用户故事 (n.)** — 从用户角度描述的功能需求
  - "The **user story** says: 'As a user, I want to reset my password so I can regain access to my account.'"
- **义项 2: 功能描述 (n.)** — 简化的需求描述格式
  - "Each **user story** follows the format: 'As a [role], I want [goal], so that [reason].'"
- **义项 3: 用户场景 (n.)** — 描述用户如何使用系统的场景
  - "The payment **user story** covers the complete checkout experience from cart to confirmation."

---

### 62. epic
- **义项 1: 史诗 (n.)** — 包含多个用户故事的大功能或大需求
  - "The payment system integration is a large **epic** that spans three sprints."
- **义项 2: 大需求 (n.)** — 需要拆分为更小故事的需求
  - "We broke the data migration **epic** into 12 individual user stories."
- **义项 3: 史诗（文学）(n.)** — 长篇叙事诗歌
  - "Homer's **epic** poems, The Iliad and The Odyssey, are still read today."

---

### 63. task
- **义项 1: 任务 (n.)** — 需要完成的单个工作项
  - "My first **task** today is to fix the broken unit test in the authentication module."
- **义项 2: 子任务 (n.)** — 用户故事拆分出的具体操作项
  - "We broke the user story into five smaller **tasks** so multiple people can work on it."
- **义项 3: 任务（日常）(n.)** — 日常需要做的工作
  - "One of my weekly **tasks** is to review the security scan results."

---

### 64. ticket
- **义项 1: 工单 (n.)** — 任务或问题的跟踪条目
  - "I created a Jira **ticket** to track the memory leak investigation."
- **义项 2: 支持请求 (n.)** — 客户或同事提交的需求或问题
  - "The support **ticket** about the login error was escalated to the engineering team."
- **义项 3: 票券 (n.)** — 入场或乘车的凭证
  - "I bought a plane **ticket** to San Francisco for the developer conference."

---

### 65. workflow
- **义项 1: 工作流 (n.)** — 可重复的自动化或人工流程
  - "Our deployment **workflow** includes code review, automated testing, and staged rollout."
- **义项 2: 流程设计 (n.)** — 定义步骤序列的建模方法
  - "The approval **workflow** requires sign-off from both the tech lead and the product manager."
- **义项 3: 工作习惯 (n.)** — 个人的工作方式和顺序
  - "My morning **workflow** involves checking emails, reviewing open PRs, and planning my day."

---

### 66. lifecycle
- **义项 1: 生命周期 (n.)** — 事物从开始到结束的完整过程
  - "The software development **lifecycle** includes planning, coding, testing, deployment, and maintenance."
- **义项 2: 数据生命周期 (n.)** — 数据从创建到删除的整个过程
  - "We implemented a data **lifecycle** policy that archives records older than seven years."
- **义项 3: 产品生命周期 (n.)** — 产品从发布到退市的时间段
  - "The product is in the maturity stage of its **lifecycle**, so the focus is now on optimization."

---

### 67. phase
- **义项 1: 阶段 (n.)** — 项目或过程中的一个特定时期
  - "The first **phase** of the migration moves all developer tools to the new platform."
- **义项 2: 施工阶段 (n.)** — 工程或建设的特定步骤
  - "The testing **phase** will begin after the development team completes the feature implementation."
- **义项 3: 阶段性 (n.)** — 月球或其他天体的相位
  - "The moon's **phase** changes from new moon to full moon over a 28-day cycle."

---

### 68. stage
- **义项 1: 阶段 (n.)** — 流程中的一个步骤
  - "The build pipeline has three **stages**: lint, test, and deploy."
- **义项 2: 预发布环境 (n.)** — 模拟生产的测试环境
  - "All changes must be deployed to the **stage** environment for validation before going to production."
- **义项 3: 舞台 (n.)** — 表演或演讲的平台
  - "The speaker walked onto the **stage** and started the keynote presentation."

---

### 69. approval
- **义项 1: 审批 (n.)** — 正式同意或批准
  - "The deployment requires **approval** from the tech lead before it can proceed."
- **义项 2: 批准流程 (n.)** — 需要正式批准的步骤
  - "Any change to the production database schema needs **approval** from the DBA team."
- **义项 3: 认可 (n.)** — 对某事物的赞许或接受
  - "The architecture proposal received **approval** from all stakeholders in the review meeting."

---

### 70. sign-off
- **义项 1: 签署确认 (n.)** — 正式确认完成的流程
  - "The QA team gave the **sign-off** after all test cases passed."
- **义项 2: 放行 (n.)** — 授权下一步操作的正式确认
  - "We cannot release the product without the product manager's **sign-off**."
- **义项 3: 签收 (n.)** — 收到并确认文件或交付物的行为
  - "The client provided **sign-off** on the project deliverables yesterday."

---

### 71. release
- **义项 1: 发布版本 (n.)** — 软件的一个可交付版本
  - "Version 3.0 is the most stable **release** we have shipped this year."
- **义项 2: 发布过程 (n.)** — 将软件发布到生产环境的操作
  - "The **release** was delayed by two days because of a regression in the payment module."
- **义项 3: 释放 (n.)** — 从限制或束缚中脱离
  - "I felt a great sense of **release** after the project was finally delivered."

---

### 72. rollout
- **义项 1: 上线 (n.)** — 新功能或版本的逐步发布
  - "The **rollout** of the new dashboard will happen gradually over two weeks."
- **义项 2: 部署策略 (n.)** — 分阶段发布的策略
  - "We did a phased **rollout** starting with 10% of users to monitor for issues."
- **义项 3: 推出的行为 (n.)** — 展开或铺开的过程
  - "The **rollout** of the new onboarding流程 went smoothly with minimal user complaints."

---

### 73. canary
- **义项 1: 金丝雀发布 (n.)** — 将新版本发布给一小部分用户的策略
  - "We deployed the new payment service to a **canary** group of 5% of users."
- **义项 2: 金丝雀环境 (n.)** — 用于测试的小规模发布环境
  - "The **canary** ran for 24 hours without any errors before we rolled out to all users."
- **义项 3: 金丝雀（鸟）(n.)** — 一种黄色的小鸟
  - "Miners used to carry a **canary** in a cage to detect toxic gases underground."

---

### 74. feature flag
- **义项 1: 功能开关 (n.)** — 在不部署代码的情况下启用或禁用功能的配置
  - "We use **feature flags** to hide unfinished features from users while deploying continuously."
- **义项 2: 功能标帜 (n.)** — 控制功能可见性的布尔值
  - "The **feature flag** for the dark mode was toggled on for all users after testing."
- **义项 3: 渐进式发布 (n.)** — 使用开关逐步开放功能
  - "We turned on the **feature flag** for the new search engine for internal users first."

---

### 75. A/B test
- **义项 1: A/B 测试 (n.)** — 比较两个版本的差异效果
  - "We ran an **A/B test** comparing the old checkout flow with the new one to measure conversion rates."
- **义项 2: 对比实验 (n.)** — 将用户随机分组进行对比的科学方法
  - "The **A/B test** showed that the redesigned button increased click-through rates by 15%."
- **义项 3: 流量分割 (n.)** — 将用户流量分配到不同版本
  - "We split 50% of traffic to variant A and 50% to variant B for the **A/B test**."

---

### 76. beta
- **义项 1: Beta 版本 (n.)** — 正式发布前的测试版本
  - "The **beta** version of the mobile app is available for internal testing this week."
- **义项 2: Beta 测试阶段 (n.)** — 在有限用户范围内测试的时期
  - "We invited 500 users to join the **beta** program and provide feedback on the new features."
- **义项 3: Beta（希腊字母）(n.)** — 希腊字母表中的第二个字母
  - "The **beta** coefficient measures the volatility of a stock compared to the market."

---

### 77. alpha
- **义项 1: Alpha 版本 (n.)** — 最早期的可用版本，可能包含大量 bug
  - "The **alpha** build is feature-incomplete and not suitable for external testing."
- **义项 2: Alpha 测试阶段 (n.)** — 内部测试的早期阶段
  - "During the **alpha** phase, we focus on verifying core functionality rather than polish."
- **义项 3: Alpha（希腊字母）(n.)** — 希腊字母表的第一个字母
  - "Alpha males are often described as dominant and confident in social hierarchies."

---

### 78. RC
- **义项 1: 发布候选版 (n.)** — 准备正式发布的候选版本
  - "We shipped **RC 1** to the QA team for final validation before the public release."
- **义项 2: 候选版本周期 (n.)** — 从候选版到正式版的验证阶段
  - "If no critical bugs are found in this **RC**, it will be promoted to the production release."
- **义项 3: 评审委员会 (n.)** — 审核项目的监督组织
  - "The **RC** (Release Committee) must approve any changes to the release schedule."

---

### 79. patch
- **义项 1: 补丁 (n.)** — 修复特定问题的小更新
  - "We released a security **patch** to fix the SQL injection vulnerability."
- **义项 2: 补丁版本 (n.)** — 语义版本中的第三位数字（如 1.0.1）
  - "Version 2.1.3 is a hotfix **patch** that addresses the memory leak in the caching layer."
- **义项 3: 补丁/布丁 (n.)** — 缝补衣物的小布片
  - "I sewed a **patch** onto my backpack to cover the hole."

---

### 80. hotfix
- **义项 1: 热修复 (n.)** — 针对生产环境紧急问题的快速修复
  - "We deployed a **hotfix** to resolve the login outage that affected all users."
- **义项 2: 紧急修复版本 (n.)** — 跳过正常发布流程的紧急版本
  - "The **hotfix** bypasses the regular CI pipeline and goes directly to production."
- **义项 3: 快速修复（比喻）(n.)** — 任何需要立即解决的紧急问题
  - "The printer issue was a **hotfix** — the IT guy just restarted it."

---

### 81. upgrade
- **义项 1: 升级 (n.)** — 将系统更新到更新的版本
  - "The database **upgrade** from PostgreSQL 13 to 15 took three hours of downtime."
- **义项 2: 升级包 (n.)** — 用于升级的文件或软件包
  - "We downloaded the **upgrade** and tested it in staging before applying it to production."
- **义项 3: 升舱 (n.)** — 提升到更高级别或更好的状态
  - "I got a free **upgrade** to business class on my flight to the conference."

---

### 82. migration
- **义项 1: 迁移 (n.)** — 从旧系统转移到新系统的过程
  - "The database **migration** involves moving 500 GB of data from MySQL to PostgreSQL."
- **义项 2: 数据迁移 (n.)** — 将数据从一个存储系统移动到另一个
  - "The schema **migration** added three new columns to the users table."
- **义项 3: 移民 (n.)** — 从一个国家迁移到另一个国家的人群
  - "The company supports **migration** from on-premise servers to the cloud."

---

### 83. integration
- **义项 1: 集成 (n.)** — 将不同系统连接起来协同工作
  - "The payment gateway **integration** required us to handle callbacks and webhooks."
- **义项 2: 系统集成 (n.)** — 将散落的系统组合成一个整体
  - "The **integration** between the CRM and the email platform improved sales tracking."
- **义项 3: 融入 (n.)** — 融入群体或社会
  - "The **integration** of new team members is smoother when we have a proper onboarding process."

---

### 84. CI/CD
- **义项 1: 持续集成/持续交付 (n.)** — 自动化构建、测试和部署的实践
  - "Our **CI/CD** pipeline runs tests on every pull request and deploys after merge."
- **义项 2: CI/CD 管道 (n.)** — 实现自动化流程的系统
  - "We migrated our **CI/CD** from Jenkins to GitHub Actions for better developer experience."
- **义项 3: DevOps 实践 (n.)** — 促进开发与运维协作的方法论
  - "Implementing **CI/CD** reduced our deployment time from hours to minutes."

---

### 85. build
- **义项 1: 构建 (n.)** — 编译和打包代码的过程
  - "The **build** failed because of a TypeScript type error in the shared module."
- **义项 2: 构建产物 (n.)** — 构建完成后生成的文件
  - "The **build** output is stored in the `dist` directory for deployment."
- **义项 3: 体格 (n.)** — 人的身材或体形
  - "He has an athletic **build** from years of regular exercise and training."

---

### 86. commit
- **义项 1: 提交 (n.)** — Git 中的一次代码变更记录
  - "The last **commit** introduced a bug that broke the login page."
- **义项 2: 提交信息 (n.)** — 描述提交内容的文字
  - "Write clear **commit** messages that explain why the change was made."
- **义项 3: 承诺 (n.)** — 对某事的保证或承诺
  - "The team made a **commit** to finish the feature before the deadline."

---

### 87. branch
- **义项 1: 分支 (n.)** — Git 中独立的代码线
  - "Create a new **branch** for each feature so you don't disrupt the main codebase."
- **义项 2: 分支策略 (n.)** — 团队使用分支的规范和模式
  - "We follow the GitFlow **branch** strategy with `develop`, `main`, and `feature` branches."
- **义项 3: 树枝 (n.)** — 树的分叉部分
  - "A **branch** of the tree fell on the car during the storm."

---

### 88. merge
- **义项 1: 合并 (n.)** — 将一个分支的变更整合到另一个分支
  - "The **merge** of the feature branch into main caused a conflict in the config file."
- **义项 2: 合并操作 (n.)** — Git 中执行合并的动作
  - "We use squash **merge** to keep the commit history clean."
- **义项 3: 合并（比喻）(n.)** — 两个事物结合
  - "The **merge** of the two design systems was a larger effort than we anticipated."

---

### 89. rebase
- **义项 1: 变基 (n.)** — 将分支的基准点移动到另一个提交
  - "I did a **rebase** to incorporate the latest changes from the main branch."
- **义项 2: 重写历史 (n.)** — 修改提交历史的操作
  - "Use interactive **rebase** to squash multiple small commits into one meaningful commit."
- **义项 3: 基准线调整 (n.)** — 在项目管理中重新设定基准
  - "We had to do a **rebase** of our project timeline after the requirements changed."

---

### 90. revert
- **义项 1: 回退 (n.)** — 撤销之前的提交或变更
  - "The **revert** of the last commit restored the application to its previous working state."
- **义项 2: 回退提交 (n.)** — Git 中创建一个反向提交来撤销变更
  - "We did a **revert** instead of a reset because the branch had already been pushed."
- **义项 3: 回到原状 (n.)** — 恢复到之前的某个状态
  - "The **revert** to the old configuration fixed the connectivity issue."

---

### 91. tag
- **义项 1: 标签 (n.)** — Git 中标记特定提交的引用
  - "We created a **tag** for version 2.0.0 before deploying to production."
- **义项 2: Docker 标签 (n.)** — 容器镜像的版本标识
  - "The image **tag** `latest` points to the most recent stable build."
- **义项 3: 标签（日常）(n.)** — 商品上的价格或说明标签
  - "The price **tag** on the monitor was higher than I expected."

---

### 92. issue
- **义项 1: 问题/议题 (n.)** — 需要讨论或解决的事情
  - "The memory leak is a known **issue** that we plan to fix in the next sprint."
- **义项 2: 问题单 (n.)** — 项目跟踪系统中的记录条目
  - "I created a GitHub **issue** to track the bug report from the customer."
- **义项 3: 期刊/印刷物 (n.)** — 杂志或报刊的一期
  - "The latest **issue** of the engineering blog covers our migration to microservices."

---

### 93. PR/MR
- **义项 1: 拉取请求/合并请求 (n.)** — 请求合并代码变更的流程
  - "I submitted a **PR** for the bug fix and requested a review from the team lead."
- **义项 2: 代码审查请求 (n.)** — 请求同事审阅代码变更
  - "The **MR** has been open for three days without any reviews — can someone take a look?"
- **义项 3: 公关（Public Relations）(n.)** — 与公众和媒体的沟通
  - "The **PR** team drafted a statement about the service outage for customers."

---

### 94. review
- **义项 1: 代码审查 (n.)** — 检查代码质量和正确性的过程
  - "The code **review** caught a potential SQL injection vulnerability in the query."
- **义项 2: 评审会议 (n.)** — 对需求或设计的评审
  - "The architecture **review** concluded that we should adopt a microservice approach."
- **义项 3: 回顾/评价 (n.)** — 对事物的评价或观后感
  - "I wrote a **review** of the conference on the company's internal blog."

---

### 95. diff
- **义项 1: 差异对比 (n.)** — 显示两个文件之间差异的输出
  - "The **diff** showed that only one line changed in the configuration file."
- **义项 2: 变更内容 (n.)** — 代码变更的具体内容
  - "Can you review the **diff** before I push it to the branch?"
- **义项 3: 差异化（数学）(n.)** — 差异或偏差
  - "The **diff** between the two benchmark results is statistically significant."

---

### 96. lint
- **义项 1: 代码检查 (n.)** — 自动化检查代码风格和潜在错误
  - "The **lint** step in our CI pipeline enforces consistent code formatting across the project."
- **义项 2: Lint 规则 (n.)** — 检查代码的配置规则集合
  - "We updated the ESLint **lint** rules to require trailing commas in function calls."
- **义项 3: 棉绒 (n.)** — 衣物上掉落的细小纤维
  - "I used a lint roller to remove the **lint** from my sweater before the presentation."

---

### 97. audit
- **义项 1: 审计 (n.)** — 对系统或流程的正式检查
  - "The security **audit** revealed that several servers still use default passwords."
- **义项 2: 日志审计 (n.)** — 审查系统日志寻找安全或合规问题
  - "We ran an **audit** of all access logs to determine who accessed the sensitive data."
- **义项 3: 财务审计 (n.)** — 对账目和财务记录的检查
  - "The annual financial **audit** confirmed that our expense reports were accurate."

---

### 98. trace
- **义项 1: 链路追踪 (n.)** — 跟踪请求在微服务间的完整路径
  - "The distributed **trace** showed that the payment service was the bottleneck in the request chain."
- **义项 2: 追踪日志 (n.)** — 程序执行的详细记录
  - "Enable debug **trace** logging to capture more details about the error."
- **义项 3: 痕迹 (n.)** — 留下的印记或线索
  - "There was no **trace** of the bug in the code — it was a hardware issue all along."

---

### 99. snapshot
- **义项 1: 快照 (n.)** — 某一时刻的状态副本
  - "We took a **snapshot** of the database before running the migration script."
- **义项 2: 虚拟快照 (n.)** — 虚拟机某一时刻的完整状态
  - "The VM **snapshot** allows us to roll back to a known good state if something goes wrong."
- **义项 3: 照片 (n.)** — 快速拍摄的照片
  - "I took a **snapshot** of the whiteboard after the architecture discussion."

---

### 100. baseline
- **义项 1: 基准线 (n.)** — 用于后续比较的初始测量值
  - "We established a performance **baseline** before applying the optimization changes."
- **义项 2: 配置基准 (n.)** — 系统配置的标准参考
  - "The security **baseline** defines minimum password length and encryption requirements."
- **义项 3: 基线（项目管理）(n.)** — 项目计划的经过审批的基准版本
  - "Any change request after the **baseline** requires formal approval from the steering committee."

---

### Group 3: Daily Life — Time, Date & Frequency（时间、日期与频率）— 50 词

---

### 101. morning
- **义项 1: 早上 (n.)** — 从日出到正午的时间段
  - "I usually check my email first thing in the **morning** before starting any coding."
- **义项 2: 上午 (n.)** — 午夜到正午之间的时段
  - "The standup meeting is every **morning** at 9:30 AM sharp."
- **义项 3: 早晨（文化含义）(n.)** — 比喻新的开始
  - "The **morning** of the project launch felt like a new beginning for the whole team."

---

### 102. afternoon
- **义项 1: 下午 (n.)** — 从正午到傍晚的时间段
  - "I try to schedule code reviews in the **afternoon** because I am more focused then."
- **义项 2: 午后 (n.)** — 午饭后到晚餐前的时段
  - "The deployment window is every Thursday **afternoon** between 2 PM and 4 PM."
- **义项 3: 下午时分 (n.)** — 一天中气温最高的时段（尤指夏季）
  - "We take a short walk every **afternoon** to refresh before the evening standup."

---

### 103. evening
- **义项 1: 傍晚/晚上 (n.)** — 日落到睡觉前的时间段
  - "I attended a coding workshop on Tuesday **evening** after work."
- **义项 2: 晚间的活动 (n.)** — 一般指晚上举办的社交活动
  - "The team is having a dinner **evening** to celebrate the successful release."
- **义项 3: 晚年 (n.)** — 比喻人生的后期阶段
  - "In the **evening** of his career, he transitioned from engineering to teaching."

---

### 104. night
- **义项 1: 夜晚 (n.)** — 天黑后的时间段
  - "The system performs a full backup every **night** at 2 AM."
- **义项 2: 夜间 (n.)** — 从日落到日出的时间
  - "On-call engineers need to respond to alerts even in the middle of the **night**."
- **义项 3: 夜晚活动 (n.)** — 形容夜间的娱乐活动
  - "We had a game **night** with the team to improve collaboration outside of work."

---

### 105. midnight
- **义项 1: 午夜 (n.)** — 夜晚 12 点正，一天的结束和开始
  - "The deployment was scheduled for **midnight** to minimize impact on active users."
- **义项 2: 深夜 (n.)** — 深夜时段
  - "I was still debugging the issue at **midnight** because the production outage was critical."
- **义项 3: 漆黑 (n.)** — 比喻非常黑暗
  - "The room was pitch dark — I couldn't see anything at **midnight** without a flashlight."

---

### 106. noon
- **义项 1: 正午 (n.)** — 中午 12 点
  - "The team usually goes to lunch together around **noon**."
- **义项 2: 中午 (n.)** — 中午前后的时间
  - "The deadline is **noon** Friday — any pull request submitted after that will miss the release."
- **义项 3: 巅峰 (n.)** — 比喻最高点或顶峰
  - "At the **noon** of his career, he was leading a team of 50 engineers."

---

### 107. dawn
- **义项 1: 黎明 (n.)** — 日出前微亮的天光
  - "The maintenance window started at **dawn** when user traffic is at its lowest."
- **义项 2: 破晓 (n.)** — 一天的开始
  - "I worked from **dawn** until dusk to finish the migration before the deadline."
- **义项 3: 开端 (n.)** — 比喻新事物的开始
  - "The **dawn** of the cloud computing era changed how companies build software."

---

### 108. dusk
- **义项 1: 黄昏 (n.)** — 日落后的微光时段
  - "We went for a walk at **dusk** after finishing the sprint review."
- **义项 2: 日暮 (n.)** — 白天和夜晚的交替时间
  - "The outdoor team-building event lasted from **dusk** until late evening."
- **义项 3: 衰落期 (n.)** — 比喻一个时代的结束
  - "The **dusk** of the mainframe era gave way to personal computing."

---

### 109. today
- **义项 1: 今天 (n.)** — 当前这一天
  - "**Today** is the last day of the sprint — we need to finish the remaining tasks."
- **义项 2: 现在 (n.)** — 当前时代
  - "**Today**, most applications are deployed in containers rather than on bare metal servers."
- **义项 3: 当今 (n.)** — 现代
  - "The developers of **today** need to understand both frontend and backend technologies."

---

### 110. tomorrow
- **义项 1: 明天 (n.)** — 今天的下一天
  - "The product demo is **tomorrow** morning — we need to finalize the slides."
- **义项 2: 未来 (n.)** — 比喻未来某个时间
  - "The **tomorrow** of software engineering might be powered entirely by AI assistants."
- **义项 3: 次日 (n.)** — 在特定日期的下一天
  - "If we submit the PR today, the review should be completed by **tomorrow**."

---

### 111. yesterday
- **义项 1: 昨天 (n.)** — 今天的前一天
  - "**Yesterday**, I spent four hours debugging a race condition that turned out to be a cache issue."
- **义项 2: 最近 (n.)** — 不久前的某个时间
  - "It feels like only **yesterday** I joined the company, but it has already been three years."
- **义项 3: 过去 (n.)** — 比喻过往时代
  - "The **yesterday** of waterfall development is very different from today's agile practices."

---

### 112. weekday
- **义项 1: 工作日 (n.)** — 周一至周五
  - "The office is open on **weekdays** from 9 AM to 6 PM."
- **义项 2: 平时 (n.)** — 与周末相对的日子
  - "I prefer to do deep coding work on **weekdays** and save meetings for Tuesdays and Thursdays."
- **义项 3: 每周日（复数）(n.)** — 指每个工作日
  - "On **weekdays**, the cafeteria serves breakfast until 10 AM."

---

### 113. weekend
- **义项 1: 周末 (n.)** — 周六和周日
  - "I spent the **weekend** studying for the AWS certification exam."
- **义项 2: 周末假期 (n.)** — 从周五晚到周日的时间
  - "The company organized a **weekend** hackathon to encourage innovation."
- **义项 3: 休息时间 (n.)** — 指不工作的时间
  - "I try not to check work messages during the **weekend**."

---

### 114. Monday
- **义项 1: 星期一 (n.)** — 一周的第一天（工作日）
  - "We deploy to production every **Monday** after the weekend traffic drops."
- **义项 2: 周一早晨 (n.)** — 比喻忙碌或艰难的开始
  - "The server crashed on **Monday** morning, which made for a stressful start to the week."
- **义项 3: 周一综合症 (n.)** — 比喻对工作周的抗拒感
  - "I had a case of the **Monday** blues until I fixed that challenging bug."

---

### 115. Tuesday
- **义项 1: 星期二 (n.)** — 一周的第二天
  - "The sprint planning meeting is every other **Tuesday** at 10 AM."
- **义项 2: 周二发布 (n.)** — 一些公司选择的发布日
  - "**Tuesday** is our standard release day because it gives us the rest of the week for hotfixes."
- **义项 3: 周二例会 (n.)** — 指固定于周二的活动
  - "**Tuesday** is the day we hold the architecture review meeting."

---

### 116. Wednesday
- **义项 1: 星期三 (n.)** — 一周的第三天
  - "The code freeze starts every **Wednesday** before a release week."
- **义项 2: 周三例行 (n.)** — 周三的常规活动
  - "**Wednesday** afternoons are reserved for team learning and knowledge sharing."
- **义项 3: 周中 (n.)** — 一周的中间点
  - "By **Wednesday**, I have usually finished most of my planned tasks for the week."

---

### 117. Thursday
- **义项 1: 星期四 (n.)** — 一周的第四天
  - "The retrospective meeting is scheduled for **Thursday** at 4 PM."
- **义项 2: 周四冲刺 (n.)** — 为周末前的完成而加紧工作
  - "**Thursday** is our last day for code changes before the Friday release."
- **义项 3: 周四晚 (n.)** — 接近周末的活动时间
  - "We often have team dinner on **Thursday** evening to wrap up the work week."

---

### 118. Friday
- **义项 1: 星期五 (n.)** — 一周的第五天和最后一个工作日
  - "We avoid deploying to production on **Friday** to prevent weekend incidents."
- **义项 2: 周五放松 (n.)** — 工作周结束时的放松氛围
  - "**Friday** afternoons are usually quiet — most people are wrapping up their tasks."
- **义项 3: 发布日 (n.)** — 一些公司的发布日
  - "**Friday** is demo day — each team presents what they shipped this week."

---

### 119. Saturday
- **义项 1: 星期六 (n.)** — 一周的第六天，周末第一天
  - "I attended a coding bootcamp on **Saturday** to improve my skills."
- **义项 2: 周末学习 (n.)** — 利用周六学习或做副业
  - "**Saturday** is when I work on my open-source side project."
- **义项 3: 周末休闲 (n.)** — 休息放松的时间
  - "I slept in on **Saturday** because I was exhausted from the week's on-call duty."

---

### 120. Sunday
- **义项 1: 星期日 (n.)** — 一周的第七天，周末最后一天
  - "I use **Sunday** evening to plan my tasks for the upcoming week."
- **义项 2: 周日准备 (n.)** — 为工作周做准备的时间
  - "**Sunday** is my meal-prep day so I don't have to think about lunch during busy weekdays."
- **义项 3: 休息日 (n.)** — 完全远离工作的日子
  - "I try to keep **Sunday** completely screen-free to recharge."

---

### 121. January
- **义项 1: 一月 (n.)** — 公历的第一个月
  - "The new fiscal year starts in **January**, and so does our Q1 planning."
- **义项 2: 新年 (n.)** — 一年的开始，常与目标设定关联
  - "I set a **January** goal to complete three certifications by March."
- **义项 3: 冬季月份 (n.)** — 北半球的寒冷月份
  - "**January** is the best time for system upgrades because user traffic is lower."

---

### 122. February
- **义项 1: 二月 (n.)** — 公历的第二个月
  - "The performance reviews are scheduled for **February** this year."
- **义项 2: 短月 (n.)** — 一年中最短的月份
  - "**February** always feels shorter, so we adjust our sprint schedule accordingly."
- **义项 3: 冬季末 (n.)** — 冬季的最后一个月
  - "The company ski trip is planned for **February** when the snow conditions are best."

---

### 123. March
- **义项 1: 三月 (n.)** — 公历的第三个月
  - "The Q1 product release is planned for **March** 15th."
- **义项 2: 春季 (n.)** — 北半球春季的开始
  - "**March** usually brings a surge in hiring as companies staff up for the year."
- **义项 3: 财年季 (n.)** — 许多公司财年的最后一个或第一个月份
  - "Budget planning starts in **March** for the next fiscal year."

---

### 124. April
- **义项 1: 四月 (n.)** — 公历的第四个月
  - "The new internship program starts in **April** this year."
- **义项 2: 春季中期 (n.)** — 北半球的春季月份
  - "**April** is conference season — I will attend three tech conferences this month."
- **义项 3: 春季会议 (n.)** — 指四月的各类技术会议
  - "The **April** release includes all the features we have been working on since January."

---

### 125. May
- **义项 1: 五月 (n.)** — 公历的第五个月
  - "The system upgrade is scheduled for **May** to avoid the busy summer season."
- **义项 2: 春末 (n.)** — 春季的结束月份
  - "**May** is a popular month for team offsites because the weather is nice."
- **义项 3: 五月活动 (n.)** — 五月的固定活动
  - "The annual company hackathon is always in **May**."

---

### 126. June
- **义项 1: 六月 (n.)** — 公历的第六个月
  - "We plan to launch the beta version in **June** after three months of development."
- **义项 2: 夏季开始 (n.)** — 北半球夏季的开始
  - "**June** is when many developers take vacations, so we reduce our sprint commitment."
- **义项 3: 年中 (n.)** — 接近一年的中段
  - "The mid-year performance review is conducted in **June**."

---

### 127. July
- **义项 1: 七月 (n.)** — 公历的第七个月
  - "**July** is typically the slowest month for business in the northern hemisphere."
- **义项 2: 夏中 (n.)** — 夏季最热的月份
  - "The data center's cooling system needs extra maintenance in **July**."
- **义项 3: 假期月 (n.)** — 许多员工休假的月份
  - "Coverage is thin in **July** because half the team is on vacation."

---

### 128. August
- **义项 1: 八月 (n.)** — 公历的第八个月
  - "We aim to complete the major refactor by **August** before the holiday season."
- **义项 2: 夏末 (n.)** — 夏季的末尾
  - "**August** is when the team ramps up after summer holidays."
- **义项 3: 冲刺期 (n.)** — 为秋季发布做准备
  - "The **August** push focuses on performance improvements before the Q3 release."

---

### 129. September
- **义项 1: 九月 (n.)** — 公历的第九个月
  - "The fall hiring season starts in **September** with many open positions."
- **义项 2: 秋季开始 (n.)** — 北半球秋天的开始
  - "**September** is when the team returns fully from summer breaks."
- **义项 3: 规划月 (n.)** — 为年度计划做准备
  - "Q4 planning begins in **September** to align resources for the final quarter."

---

### 130. October
- **义项 1: 十月 (n.)** — 公历的第十个月
  - "The annual performance review cycle starts in **October**."
- **义项 2: 秋季中 (n.)** — 秋季较为繁忙的时期
  - "**October** is usually a busy month for e-commerce companies preparing for the holidays."
- **义项 3: 活动月 (n.)** — 十月常见的技术活动
  - "Several major tech conferences take place in **October**, including KubeCon."

---

### 131. November
- **义项 1: 十一月 (n.)** — 公历的第十一个月
  - "The Black Friday traffic spike in **November** requires careful capacity planning."
- **义项 2: 晚秋 (n.)** — 秋季最后一个月
  - "**November** is crunch time for many product teams racing to ship before the holidays."
- **义项 3: 系统强化月 (n.)** — 为应对流量高峰做准备
  - "We always increase monitoring coverage in **November** to handle holiday traffic."

---

### 132. December
- **义项 1: 十二月 (n.)** — 公历的第十二个月
  - "We freeze all production deployments in mid-**December** to ensure stability over the holidays."
- **义项 2: 年末 (n.)** — 一年的末尾
  - "**December** is a quiet month for code changes as most people are on break."
- **义项 3: 假期季 (n.)** — 指圣诞和新年的节日期间
  - "The team had a small celebration in **December** to wrap up the year."

---

### 133. spring
- **义项 1: 春天 (n.)** — 一年中冬季之后的季节
  - "We usually start major new projects in the **spring** when the team is fully staffed."
- **义项 2: 弹簧 (n.)** — 一种可以压缩和回弹的机械零件
  - "The keyboard switch uses a **spring** to provide tactile feedback when typing."
- **义项 3: 泉水 (n.)** — 从地下涌出的水源
  - "There is a natural hot **spring** near the conference venue that I want to visit."

---

### 134. summer
- **义项 1: 夏天 (n.)** — 一年中最温暖的季节
  - "Interns join the team in the **summer**, bringing fresh ideas and energy."
- **义项 2: 暑期 (n.)** — 夏季的假期期间
  - "**Summer** is a good time for refactoring work because fewer features are being shipped."
- **义项 3: 鼎盛时期 (n.)** — 比喻人生或事业的巅峰
  - "The **summer** of the dot-com era was a time of rapid innovation in web technologies."

---

### 135. autumn
- **义项 1: 秋天 (n.)** — 夏季和冬季之间的季节
  - "The company's annual planning retreat happens in **autumn**."
- **义项 2: 秋季 (n.)** — 收获的季节，也用于比喻
  - "**Autumn** is conference season — I have three speaking engagements this year."
- **义项 3: 成熟期 (n.)** — 比喻事物发展到成熟的阶段
  - "The **autumn** of the project was when the architecture truly proved itself under load."

---

### 136. winter
- **义项 1: 冬天 (n.)** — 一年中最寒冷的季节
  - "**Winter** is the best season for infrastructure upgrades because traffic is lower."
- **义项 2: 冬歇期 (n.)** — 年底的休息时期
  - "The team takes turns covering on-call duties during **winter** holidays."
- **义项 3: 低谷期 (n.)** — 比喻不活跃或艰难的时期
  - "The **winter** of the startup's early years required everyone to wear multiple hats."

---

### 137. second
- **义项 1: 秒 (n.)** — 时间的单位
  - "The page must load within three **seconds** — anything slower affects user engagement."
- **义项 2: 瞬间 (n.)** — 非常短的时间
  - "Wait one **second** — let me check the logs before you restart the server."
- **义项 3: 第二名 (adj./n.)** — 排序中的第二位
  - "This is the **second** time this week the CI pipeline has failed."

---

### 138. minute
- **义项 1: 分钟 (n.)** — 时间的单位（60 秒）
  - "The deployment typically completes in about five **minutes**."
- **义项 2: 片刻 (n.)** — 很短的时间
  - "I'll be with you in a **minute** — I just need to finish reviewing this diff."
- **义项 3: 微小 (adj.)** — 非常小或详细的
  - "The difference in performance between the two approaches is **minute**."

---

### 139. hour
- **义项 1: 小时 (n.)** — 时间的单位（60 分钟）
  - "The batch job runs for about one **hour** every night."
- **义项 2: 工作时间 (n.)** — 指一段工作时间
  - "Core working **hours** are from 10 AM to 4 PM, and the rest is flexible."
- **义项 3: 时刻 (n.)** — 特定的时间点
  - "This is my favorite **hour** of the day — the quiet time before everyone comes online."

---

### 140. day
- **义项 1: 天/日 (n.)** — 24 小时的时间单位
  - "The SLA requires us to respond to critical incidents within one business **day**."
- **义项 2: 白天 (n.)** — 日出到日落的时间
  - "I prefer working during the **day** and relaxing in the evening."
- **义项 3: 时代 (n.)** — 特定的时期
  - "In my **day**, we had to manage servers manually — there was no cloud."

---

### 141. week
- **义项 1: 周 (n.)** — 七天的时间单位
  - "The sprint lasts two **weeks**, with the review on the final day."
- **义项 2: 工作周 (n.)** — 从周一到周五的工作时间
  - "I worked a 50-hour **week** to get the release out on time."
- **义项 3: 周数 (n.)** — 按周计算的时间
  - "The migration will take about six **weeks** from planning to completion."

---

### 142. month
- **义项 1: 月 (n.)** — 约 30 天的时间单位
  - "We run a security audit every **month** to check for vulnerabilities."
- **义项 2: 月份 (n.)** — 日历上的特定月份
  - "The **month** of December is usually quiet for releases due to the holidays."
- **义项 3: 按月计算 (n.)** — 以月为周期的数量
  - "We process over 10 million transactions per **month** on the platform."

---

### 143. year
- **义项 1: 年 (n.)** — 365 天的时间单位
  - "The team shipped over 200 features last **year**."
- **义项 2: 年份 (n.)** — 特定的日历年度
  - "The **year** 2024 was when we completed the full migration to microservices."
- **义项 3: 年龄/年数 (n.)** — 存在或经历的时长
  - "I have been working as a developer for over ten **years**."

---

### 144. decade
- **义项 1: 十年 (n.)** — 十年的时间单位
  - "Over the past **decade**, cloud computing has completely transformed the industry."
- **义项 2: 年代 (n.)** — 以十年划分的特定时期
  - "The **decade** of microservices started around 2014 and continues today."
- **义项 3: 长期的 (n.)** — 泛指很长一段时间
  - "I haven't seen that legacy codebase in a **decade** — it probably still runs on Java 8."

---

### 145. century
- **义项 1: 世纪 (n.)** — 一百年的时间单位
  - "The 21st **century** has been defined by the rise of the internet and mobile computing."
- **义项 2: 百年 (n.)** — 一百年的时间跨度
  - "This programming paradigm has been around for less than a **century**."
- **义项 3: 百年老店 (n.)** — 存在了超过百年的组织
  - "IBM is a company that has survived for over a **century** by adapting to technology changes."

---

### 146. now
- **义项 1: 现在 (adv.)** — 当前的时间点
  - "I am debugging the production issue right **now** — can I call you back?"
- **义项 2: 立刻 (adv.)** — 马上、不拖延
  - "We need to fix this vulnerability **now** before it gets exploited."
- **义项 3: 目前 (adv.)** — 当前的阶段
  - "**Now** that we have automated the deployment, the team can focus on feature development."

---

### 147. then
- **义项 1: 然后 (adv.)** — 表示时间上的顺序
  - "First, we need to update the schema. **Then**, we can deploy the new code."
- **义项 2: 那时 (adv.)** — 过去或将来的某个时间点
  - "I was a junior developer back **then**, and everything seemed overwhelming."
- **义项 3: 那么 (adv.)** — 用于逻辑推理
  - "If the tests pass, **then** we can merge the pull request."

---

### 148. soon
- **义项 1: 很快 (adv.)** — 在不久的将来
  - "The CI build should finish **soon** — it's already past the test stage."
- **义项 2: 及早 (adv.)** — 尽早、尽快
  - "We need to address this performance issue as **soon** as possible."
- **义项 3: 不久之后 (adv.)** — 在某事之后不久
  - "The server crashed **soon** after the deployment went live."

---

### 149. later
- **义项 1: 以后 (adv.)** — 在未来的某个时间
  - "I can't review your PR right now — let me do it **later** this afternoon."
- **义项 2: 稍后 (adv.)** — 不久之后（一会儿）
  - "I will check the error logs **later** when I have more time."
- **义项 3: 后来 (adv.)** — 在某个时间点之后
  - "**Later** in the sprint, we discovered the issue was more complex than we thought."

---

### 150. ago
- **义项 1: 之前 (adv.)** — 在现在之前的某个时间
  - "I submitted that pull request three days **ago**, but it hasn't been reviewed yet."
- **义项 2: ……前 (adv.)** — 从某个时间点往回算
  - "The system was migrated to the cloud two years **ago**."
- **义项 3: 很久以前 (adv.)** — 某个较久远的时间
  - "Long **ago**, deployments were manual processes that took hours."

---

### Group 4: Daily Life — Body, Health & Senses（身体、健康与感官）— 50 词

---

### 151. head
- **义项 1: 头 (n.)** — 身体的顶部（包含大脑的器官）
  - "I have been staring at this bug all day and my **head** is starting to hurt."
- **义项 2: 领导 (n.)** — 团队或组织的负责人
  - "The engineering **head** approved the budget for new hardware."
- **义项 3: 标题 (n.)** — 文档或文章的标题
  - "The section **head** summarizes what the document covers."

---

### 152. hair
- **义项 1: 头发 (n.)** — 从头皮长出的细丝
  - "I found a gray **hair** this morning — debugging must be stressing me out."
- **义项 2: 毛发 (n.)** — 身体其他部位的毛
  - "The cat left **hair** all over my laptop keyboard."
- **义项 3: 细微之物 (n.)** — 极小的数量或距离
  - "The test failed by a **hair** — the response time was 201ms instead of 200ms."

---

### 153. face
- **义项 1: 脸 (n.)** — 头部前面的部分（包括眼睛、鼻子、嘴）
  - "He had a surprised **face** when I told him the deployment was broken."
- **义项 2: 表面 (n.)** — 物体的正面或外表面
  - "The error message was displayed on the **face** of the monitoring dashboard."
- **义项 3: 面对 (v.)** — 直面困难或挑战
  - "We need to **face** the reality that the current architecture is not sustainable."

---

### 154. eye
- **义项 1: 眼睛 (n.)** — 视觉器官
  - "Keep an **eye** on the monitoring dashboard while I check the database logs."
- **义项 2: 眼光 (n.)** — 审美或判断能力
  - "The designer has a good **eye** for color and typography."
- **义项 3: 关注点 (n.)** — 关注或监督
  - "The tech lead has his **eye** on the memory consumption of the new service."

---

### 155. nose
- **义项 1: 鼻子 (n.)** — 嗅觉和呼吸的器官
  - "My **nose** is stuffy because of the air conditioning in the office."
- **义项 2: 嗅觉 (n.)** — 发现或识别事物的能力
  - "A good engineer has a **nose** for potential performance bottlenecks."
- **义项 3: 前端 (n.)** — 突出部位或前端
  - "The **nose** of the aircraft contains the radar system."

---

### 156. mouth
- **义项 1: 嘴巴 (n.)** — 吃饭和说话的器官
  - "Keep your **mouth** closed during the demo if you are nervous."
- **义项 2: 入口 (n.)** — 容器的开口
  - "The **mouth** of the tunnel was blocked by debris."
- **义项 3: 代言 (n.)** — 代表发言
  - "We need a **mouth** piece for the project — someone to communicate with stakeholders."

---

### 157. ear
- **义项 1: 耳朵 (n.)** — 听觉器官
  - "I listen to coding podcasts through my **ear** buds while commuting."
- **义项 2: 倾听能力 (n.)** — 愿意听取意见
  - "The manager has an open **ear** for new ideas from the junior developers."
- **义项 3: 听力 (n.)** — 对声音的敏感度
  - "He has a good **ear** for detecting unusual server noises."

---

### 158. neck
- **义项 1: 脖子 (n.)** — 连接头和身体的部位
  - "I got a stiff **neck** from hunching over my laptop all day."
- **义项 2: 瓶颈 (n.)** — 狭窄的部分
  - "The database query is the **neck** of the bottle — it slows everything down."
- **义项 3: 颈状部位 (n.)** — 物体的细长部分
  - "The **neck** of the bottle is where the label goes."

---

### 159. shoulder
- **义项 1: 肩膀 (n.)** — 连接手臂和躯干的关节部位
  - "I dislocated my **shoulder** playing basketball — I will be out for two weeks."
- **义项 2: 肩负 (v.)** — 承担任务或责任
  - "She **shoulders** the responsibility of maintaining the entire CI/CD pipeline."
- **义项 3: 路肩 (n.)** — 公路两侧的紧急停车区域
  - "The car pulled over onto the **shoulder** when the engine overheated."

---

### 160. arm
- **义项 1: 手臂 (n.)** — 从肩膀到手腕的肢体
  - "I broke my **arm** last year and had to type with one hand for six weeks."
- **义项 2: 分支/部门 (n.)** — 组织或系统的分支
  - "The DevOps **arm** of the company handles all infrastructure concerns."
- **义项 3: 武器 (n.)** — 用于战斗的工具（复数）
  - "The decision-maker relies on data as his primary **arm** for persuasion."

---

### 161. elbow
- **义项 1: 手肘 (n.)** — 手臂中间的可弯曲关节
  - "I hit my **elbow** on the desk while reaching for the power cable."
- **义项 2: 肘形弯管 (n.)** — 管道中的弯头连接件
  - "The network cable was bent at a sharp **elbow** which caused signal loss."
- **义项 3: 挤入 (v.)** — 用手肘推开他人以获得空间
  - "He **elbowed** his way through the crowd to get to the conference booth."

---

### 162. wrist
- **义项 1: 手腕 (n.)** — 连接手和前臂的关节
  - "I wear a **wrist** brace to prevent carpal tunnel syndrome while coding."
- **义项 2: 腕部 (n.)** — 衣袖或手套的腕部位置
  - "The smartwatch measures heart rate from the **wrist**."
- **义项 3: 腕表 (n.)** — 戴在手腕上的表
  - "My fitness tracker on my **wrist** reminds me to stand up every hour."

---

### 163. hand
- **义项 1: 手 (n.)** — 手臂末端用于抓握的部分
  - "Raise your **hand** if you have experience with Kubernetes."
- **义项 2: 协助 (n.)** — 提供帮助
  - "Could you give me a **hand** with debugging this deployment issue?"
- **义项 3: 参与 (n.)** — 在事件或决策中起的作用
  - "The senior engineer had a **hand** in designing the new architecture."

---

### 164. finger
- **义项 1: 手指 (n.)** — 手上的五个细长部位之一
  - "I type with all ten **fingers** to maximize coding speed."
- **义项 2: 指针 (n.)** — 指向某物的东西
  - "Let's not point **fingers** at whose code caused the bug — let's fix it together."
- **义项 3: 指状物 (n.)** — 类似手指形状的物体
  - "The **finger** of the robot arm can grip delicate components."

---

### 165. thumb
- **义项 1: 大拇指 (n.)** — 手上最短但最关键的指头
  - "I accidentally hit my **thumb** with a hammer while setting up the server rack."
- **义项 2: 粗略规则 (n.)** — 经验法则
  - "As a rule of **thumb**, you should never deploy on a Friday."
- **义项 3: 竖起拇指 (n.)** — 赞同或点赞的手势
  - "The demo got a **thumb** up from the product manager."

---

### 166. chest
- **义项 1: 胸部 (n.)** — 脖子和腹部之间的身体部分
  - "He crossed his arms over his **chest** while listening to the architecture proposal."
- **义项 2: 储物箱 (n.)** — 用于存放物品的坚固箱子
  - "We keep backup drives in a fireproof **chest** in the data center."
- **义项 3: 胸襟 (n.)** — 胸怀或内心
  - "He got that off his **chest** by admitting the mistake in the standup."

---

### 167. back
- **义项 1: 背部 (n.)** — 身体后面从脖子到腰的部分
  - "My **back** hurts from sitting in this chair for eight hours."
- **义项 2: 后面 (n.)** — 物体的背面或后部
  - "All the USB ports are on the **back** of the monitor."
- **义项 3: 回退 (v.)** — 返回或支持
  - "We need to **back** up the database before running the migration."

---

### 168. stomach
- **义项 1: 胃/肚子 (n.)** — 消化食物的器官或腹部
  - "I had a **stomach** ache after skipping lunch to fix a production bug."
- **义项 2: 承受力 (n.)** — 对不快事情的容忍能力
  - "I don't have the **stomach** for dealing with legacy PHP code anymore."
- **义项 3: 胃口 (n.)** — 对某事的渴望或兴趣
  - "I have no **stomach** for another meeting about the same topic."

---

### 169. waist
- **义项 1: 腰 (n.)** — 身体最窄的部位，在肋骨和臀部之间
  - "My belt is too tight around the **waist** after sitting at my desk all day."
- **义项 2: 腰围 (n.)** — 腰部的周长
  - "Standing desks help maintain a healthier **waist** measurement."
- **义项 3: 腰部区域 (n.)** — 衣物的腰部位置
  - "The **waist** of these pants is too loose — I need a smaller size."

---

### 170. hip
- **义项 1: 臀部 (n.)** — 身体两侧在腰以下的突出部位
  - "I carry my phone in my **hip** pocket during walks."
- **义项 2: 时髦 (adj.)** — 时尚、前卫
  - "Our new UI design is very **hip** and minimalistic."
- **义项 3: 髋关节 (n.)** — 连接大腿和骨盆的关节
  - "Running puts a lot of stress on your **hip** joints."

---

### 171. leg
- **义项 1: 腿 (n.)** — 支撑身体和行走的肢体
  - "I stretch my **legs** during the lunch break by walking around the block."
- **义项 2: 一段旅程 (n.)** — 路线或行程的一部分
  - "The first **leg** of the deployment is building the Docker image."
- **义项 3: 支柱 (n.)** — 支撑重物的结构
  - "The server rack has adjustable **legs** to level it on uneven floors."

---

### 172. knee
- **义项 1: 膝盖 (n.)** — 大腿和小腿之间的关节
  - "I hurt my **knee** playing football and had to take a week off."
- **义项 2: 膝部 (n.)** — 裤子或袜子的膝盖位置
  - "The **knee** of my jeans wore out after two years of daily wear."
- **义项 3: 膝盖反应 (n.)** — 比喻即时反应
  - "My **knee**-jerk reaction was to blame the database, but it was actually a code issue."

---

### 173. ankle
- **义项 1: 脚踝 (n.)** — 连接脚和腿的关节
  - "I twisted my **ankle** on the stairs and had to work from home."
- **义项 2: 踝部 (n.)** — 裤腿或袜子的脚踝部位
  - "The **ankle** of my sock was too tight and left a mark."
- **义项 3: 踝关节稳定性 (n.)** — 脚踝的健康和稳定
  - "Good **ankle** support is important if you stand for long periods."

---

### 174. foot
- **义项 1: 脚 (n.)** — 腿末端用于站立和行走的部分
  - "I have been on my **feet** all day at the conference — they are killing me."
- **义项 2: 英尺 (n.)** — 长度单位（约 30.48 厘米）
  - "The server room is 20 **feet** long and 15 feet wide."
- **义项 3: 底部 (n.)** — 物体的最下部分
  - "The **foot** of the mountain was covered in fog."

---

### 175. toe
- **义项 1: 脚趾 (n.)** — 脚前端的五个小肢
  - "I stubbed my **toe** on the server rack and it really hurt."
- **义项 2: 尖端 (n.)** — 鞋子或袜子的脚趾部位
  - "There is a hole in the **toe** of my sock."
- **义项 3: 脚尖 (n.)** — 以脚尖站立或行走
  - "I had to stand on **toe** to reach the top shelf of the server cabinet."

---

### 176. skin
- **义项 1: 皮肤 (n.)** — 身体表面的覆盖层
  - "My **skin** gets dry from the air conditioning in the office."
- **义项 2: 表面 (n.)** — 物体的外层
  - "The **skin** of the aircraft is made of lightweight aluminum."
- **义项 3: UI 皮肤 (n.)** — 软件界面的视觉主题
  - "The application has a light **skin** and a dark skin option."

---

### 177. bone
- **义项 1: 骨头 (n.)** — 构成骨骼的硬组织
  - "The X-ray showed no broken **bones** after the fall."
- **义项 2: 核心 (n.)** — 某事的基础或核心
  - "The **bone** of the problem is the outdated authentication mechanism."
- **义项 3: 赤裸 (adj.)** — 最基本的
  - "He gave the **bare**-**bones** explanation of how the system works."

---

### 178. muscle
- **义项 1: 肌肉 (n.)** — 身体中产生力量的纤维组织
  - "I feel **muscle** tension in my shoulders from typing too much."
- **义项 2: 实力 (n.)** — 组织或系统的核心能力
  - "We need more engineering **muscle** to complete this project on time."
- **义项 3: 影响力 (n.)** — 施加力或影响力的能力
  - "The marketing team has the financial **muscle** to run a large campaign."

---

### 179. blood
- **义项 1: 血液 (n.)** — 循环在心血管系统中的液体
  - "High **blood** pressure is common among developers who sit all day."
- **义项 2: 血统 (n.)** — 家族或遗传背景
  - "The code still has **blood** stains from the original developers who wrote it."
- **义项 3: 热血 (n.)** — 比喻激情或强度
  - "The team put **blood**, sweat, and tears into this release."

---

### 180. heart
- **义项 1: 心脏 (n.)** — 泵血的器官
  - "My **heart** was pounding during the production rollout."
- **义项 2: 核心 (n.)** — 最重要的部分
  - "The **heart** of the system is the message queue that connects all services."
- **义项 3: 情感 (n.)** — 同情心或关怀
  - "He put his **heart** into designing the developer experience."

---

### 181. lung
- **义项 1: 肺 (n.)** — 呼吸的器官
  - "Sitting in a meeting room with no windows hurts my **lungs** after two hours."
- **义项 2: 呼吸能力 (n.)** — 肺活量
  - "The smoke from the wildfire affected my **lung** capacity."
- **义项 3: 通风空间 (n.)** — 提供空气流通的区域（比喻）
  - "The open office layout gives the team room to **lung** — it feels less cramped."

---

### 182. brain
- **义项 1: 大脑 (n.)** — 思维和控制的器官
  - "My **brain** is fried after five hours of debugging this race condition."
- **义项 2: 智力 (n.)** — 思考和推理的能力
  - "She is the **brain** behind the new architecture."
- **义项 3: 核心控制器 (n.)** — 比喻系统的中央控制系统
  - "The orchestrator is the **brain** of the container cluster."

---

### 183. nerve
- **义项 1: 神经 (n.)** — 传递信号的纤维
  - "The carpal tunnel compresses a **nerve** in the wrist, causing pain."
- **义项 2: 勇气 (n.)** — 胆量或勇气（复数 nerves / 不可数）
  - "It takes **nerve** to suggest rewriting the entire codebase."
- **义项 3: 紧张 (n.)** — 焦虑或不安（复数 nerves）
  - "I had **nerves** before my first presentation to the executive team."

---

### 184. sick
- **义项 1: 生病的 (adj.)** — 身体不适
  - "I called in **sick** today because I have a fever and a sore throat."
- **义项 2: 厌倦的 (adj.)** — 对某事感到厌烦
  - "I am **sick** of dealing with the same deployment issues every week."
- **义项 3: 想吐的 (adj.)** — 恶心的感觉
  - "The rocking motion of the boat made me feel **sick**."

---

### 185. healthy
- **义项 1: 健康的 (adj.)** — 身体状况良好
  - "I try to eat a **healthy** lunch instead of ordering fast food."
- **义项 2: 健康的（系统）(adj.)** — 系统运行良好
  - "The database connections are **healthy** and the query response times look good."
- **义项 3: 有益的 (adj.)** — 对发展或成长有益的
  - "A **healthy** team culture encourages open feedback and continuous learning."

---

### 186. pain
- **义项 1: 疼痛 (n.)** — 身体上的不适感
  - "I have a sharp **pain** in my lower back from sitting too long."
- **义项 2: 痛苦 (n.)** — 精神上的困扰
  - "Dealing with legacy code is a real **pain** — it takes forever to understand."
- **义项 3: 痛点 (n.)** — 问题或困难点
  - "The biggest **pain** point in our workflow is the manual approval process."

---

### 187. fever
- **义项 1: 发烧 (n.)** — 体温异常的病症
  - "I had a high **fever** last night and decided to work from home today."
- **义项 2: 狂热 (n.)** — 高涨的情绪或兴趣
  - "There was a **fever** of excitement in the office before the product launch."
- **义项 3: 热度（比喻）(n.)** — 对某事的高度关注
  - "AI **fever** has taken over the tech industry this year."

---

### 188. cough
- **义项 1: 咳嗽 (n.)** — 从肺部用力排出空气的动作
  - "I have a dry **cough** that gets worse when I speak for long periods."
- **义项 2: 咳嗽声 (n.)** — 咳嗽发出的声音
  - "A **cough** from the back of the room interrupted the presentation."
- **义项 3: 发出咳嗽声 (v.)** — 发出类似咳嗽的声音
  - "The old server's fan **coughs** and sputters when it starts up."

---

### 189. headache
- **义项 1: 头痛 (n.)** — 头部疼痛
  - "Looking at the screen for eight hours gives me a **headache**."
- **义项 2: 令人头痛的事 (n.)** — 麻烦或棘手的问题
  - "The database migration has been a **headache** all week."
- **义项 3: 持续的困扰 (n.)** — 长期难以解决的问题
  - "The legacy authentication system is a **headache** for the security team."

---

### 190. medicine
- **义项 1: 药物 (n.)** — 用于治疗疾病的物质
  - "I took cold **medicine** before the meeting so I could stop coughing."
- **义项 2: 医学 (n.)** — 医疗科学
  - "Modern **medicine** has made significant progress in treating chronic diseases."
- **义项 3: 良药 (n.)** — 比喻能解决问题的方法
  - "The best **medicine** for a buggy codebase is comprehensive testing."

---

### 191. doctor
- **义项 1: 医生 (n.)** — 治疗疾病的专业人员
  - "The **doctor** recommended that I take a week off to recover from burnout."
- **义项 2: 博士 (n.)** — 学术学位的最高级别
  - "She holds a Ph**D** (Doctor of Philosophy) in Computer Science."
- **义项 3: 修复者 (n.)** — 比喻修理或修复的人
  - "The senior engineer is the **doctor** who diagnoses and fixes production issues."

---

### 192. nurse
- **义项 1: 护士 (n.)** — 协助医生照顾病人的专业人员
  - "The **nurse** checked my blood pressure during the health screening."
- **义项 2: 养育 (v.)** — 精心照料使其成长
  - "We need to **nurse** the startup phase of the project with close attention."
- **义项 3: 哺乳 (v.)** — 给婴儿喂奶
  - "She took a break to **nurse** her baby during the conference lunch."

---

### 193. hospital
- **义项 1: 医院 (n.)** — 提供医疗服务的机构
  - "I went to the **hospital** for a routine checkup last weekend."
- **义项 2: 住院 (n.)** — 在医院接受治疗的状态
  - "He was in the **hospital** for three days after the surgery."
- **义项 3: 团体（比喻）(n.)** — 有大量活动的地方
  - "Our office feels like a **hospital** with everyone wearing masks during flu season."

---

### 194. exercise
- **义项 1: 锻炼 (n.)** — 保持健康的身体活动
  - "Regular **exercise** helps me stay focused when I'm coding."
- **义项 2: 练习 (n.)** — 为了学习或训练而做的任务
  - "This coding **exercise** tests your understanding of recursion."
- **义项 3: 行使 (v.)** — 使用某种权利或能力
  - "It's important to **exercise** caution when deploying to production."

---

### 195. sleep
- **义项 1: 睡眠 (n.)** — 休息的状态
  - "I only got four hours of **sleep** because of the production outage."
- **义项 2: 睡觉 (v.)** — 进行睡眠的行为
  - "I need to **sleep** on this architecture decision before making a final call."
- **义项 3: 休眠 (n.)** — 计算机的省电模式
  - "My laptop went to **sleep** during the long build process."

---

### 196. rest
- **义项 1: 休息 (n.)** — 停止工作恢复精力
  - "Take a **rest** after the deployment — you have been working since 6 AM."
- **义项 2: 剩余 (n.)** — 剩下的部分
  - "I finished the main feature; the **rest** is just polish."
- **义项 3: 放松 (v.)** — 停止活动以恢复精力
  - "Try to **rest** your eyes for five minutes every hour."

---

### 197. tired
- **义项 1: 疲倦的 (adj.)** — 需要休息或睡眠
  - "I am so **tired** after being on call all night."
- **义项 2: 厌倦的 (adj.)** — 对某事感到厌烦
  - "I am **tired** of explaining the same concept in every code review."
- **义项 3: 陈旧的 (adj.)** — 用得太久而失去新鲜感
  - "The design feels **tired** — we need to refresh the user interface."

---

### 198. see
- **义项 1: 看见 (v.)** — 用眼睛感知
  - "I can **see** the error in the code just by looking at it."
- **义项 2: 理解 (v.)** — 明白或认识到
  - "I **see** what you mean about the architecture being over-complicated."
- **义项 3: 会面 (v.)** — 安排见面
  - "I will **see** the client tomorrow to discuss the requirements."

---

### 199. hear
- **义项 1: 听见 (v.)** — 用耳朵感知声音
  - "I can **hear** the server fans spinning loudly in the data center."
- **义项 2: 听说 (v.)** — 通过别人得知
  - "I **hear** that the team is planning a migration to Kubernetes."
- **义项 3: 听取 (v.)** — 正式听取某事
  - "The court will **hear** the case next month."

---

### 200. feel
- **义项 1: 感觉 (v.)** — 通过触觉感知
  - "I can **feel** the laptop getting hot under heavy load."
- **义项 2: 觉得 (v.)** — 主观判断或看法
  - "I **feel** that we should reconsider the database choice."
- **义项 3: 感受 (v.)** — 经历某种情感
  - "I **feel** proud of what the team accomplished this quarter."

---

### Group 5: Daily Life — Emotions, Personality & Mental States（情绪、性格与心理状态）— 50 词

---

### 201. happy
- **义项 1: 开心的 (adj.)** — 感到愉悦或满足
  - "I am **happy** with how the sprint went — we delivered everything on time."
- **义项 2: 满意的 (adj.)** — 对结果感到满足
  - "The client is **happy** with the prototype and approved the next phase."
- **义项 3: 乐意的 (adj.)** — 愿意做某事
  - "I would be **happy** to review your pull request after lunch."

---

### 202. sad
- **义项 1: 难过的 (adj.)** — 感到悲伤或不开心
  - "I was **sad** to hear that the project got canceled."
- **义项 2: 遗憾的 (adj.)** — 对某事感到失望
  - "It is **sad** that we didn't have time to implement the full feature set."
- **义项 3: 可怜的 (adj.)** — 令人同情的
  - "The **sad** state of the legacy codebase made everyone want to rewrite it."

---

### 203. angry
- **义项 1: 生气的 (adj.)** — 感到愤怒
  - "The product manager was **angry** when the release was delayed again."
- **义项 2: 愤怒的（颜色）(adj.)** — 形容强烈的颜色
  - "The error logs were highlighted in **angry** red on the dashboard."
- **义项 3: 激烈的 (adj.)** — 形容风暴或天气恶劣
  - "**Angry** clouds gathered as I walked to the office this morning."

---

### 204. excited
- **义项 1: 兴奋的 (adj.)** — 热情高涨的
  - "The team is **excited** about the new project — everyone wants to contribute."
- **义项 2: 激动的 (adj.)** — 充满期待的
  - "I am **excited** to present our work at the conference next week."
- **义项 3: 活跃的 (adj.)** — 形容状态或气氛热烈
  - "There was an **excited** buzz in the office before the product launch."

---

### 205. nervous
- **义项 1: 紧张的 (adj.)** — 对即将发生的事情感到不安
  - "I always get **nervous** before deploying to production."
- **义项 2: 焦虑的 (adj.)** — 担心后果
  - "She was **nervous** about the performance review results."
- **义项 3: 不安的 (adj.)** — 感到心神不宁
  - "The system was making strange noises, making everyone **nervous**."

---

### 206. calm
- **义项 1: 冷静的 (adj.)** — 不被外界干扰的情绪状态
  - "The tech lead stayed **calm** during the production outage and resolved it quickly."
- **义项 2: 平静的 (adj.)** — 没有风浪或动荡
  - "The office was **calm** because most people were on vacation."
- **义项 3: 使平静 (v.)** — 使情绪恢复正常
  - "Take a deep breath to **calm** your nerves before the demo."

---

### 207. anxious
- **义项 1: 焦虑的 (adj.)** — 因不确定而担忧
  - "I feel **anxious** when the tests take too long to run."
- **义项 2: 急切的 (adj.)** — 非常渴望
  - "The team was **anxious** to hear the results of the A/B test."
- **义项 3: 不安的 (adj.)** — 感到不自在
  - "The **anxious** silence during the meeting meant everyone disagreed but no one spoke up."

---

### 208. afraid
- **义项 1: 害怕的 (adj.)** — 感到恐惧
  - "Don't be **afraid** to ask questions during your first week on the team."
- **义项 2: 担心的 (adj.)** — 忧心不好的事情发生
  - "I am **afraid** that the database migration might cause data loss."
- **义项 3: 遗憾地（口语）(adj.)** — 表示客气的道歉
  - "I am **afraid** I won't be able to attend the meeting this afternoon."

---

### 209. worried
- **义项 1: 担心的 (adj.)** — 为某事感到焦虑
  - "I am **worried** about the server's memory usage — it keeps growing."
- **义项 2: 发愁的 (adj.)** — 长期处于忧虑中
  - "The manager is **worried** that we won't meet the project deadline."
- **义项 3: 牵挂的 (adj.)** — 对某人或某事不放心
  - "She was **worried** about the intern who was debugging alone late at night."

---

### 210. confused
- **义项 1: 困惑的 (adj.)** — 不理解某事物
  - "I am **confused** about why this query returns different results each time."
- **义项 2: 混乱的 (adj.)** — 糊涂、不清醒
  - "The documentation is **confused** — it mixes up two different APIs."
- **义项 3: 搞混的 (adj.)** — 无法区分两个事物
  - "I got **confused** between the staging and production environment variables."

---

### 211. frustrated
- **义项 1: 沮丧的 (adj.)** — 因受阻或失败而感到恼火
  - "I am **frustrated** because the bug only appears in production and I can't reproduce it locally."
- **义项 2: 挫败的 (adj.)** — 感到无法进步
  - "The team felt **frustrated** after the third failed deployment attempt."
- **义项 3: 无耐的 (adj.)** — 对反复出现的问题感到无力
  - "She was **frustrated** with the slow build times that wasted hours every week."

---

### 212. disappointed
- **义项 1: 失望的 (adj.)** — 因为期望没有达到而不开心
  - "I was **disappointed** that the performance optimization only improved speed by 2%."
- **义项 2: 扫兴的 (adj.)** — 因为某事没有成功而失落
  - "The team was **disappointed** when the feature didn't make the release."
- **义项 3: 辜负期望的 (adj.)** — 未能满足别人期望
  - "He was **disappointed** in himself for missing the deadline."

---

### 213. satisfied
- **义项 1: 满意的 (adj.)** — 需求或期望已得到满足
  - "The client is **satisfied** with the performance of the new system."
- **义项 2: 满足的 (adj.)** — 感到知足或充实
  - "I feel **satisfied** after completing a challenging code refactor."
- **义项 3: 可信服的 (adj.)** — 理由充分使人信服
  - "The engineer provided a **satisfied** explanation for the architecture decision."

---

### 214. proud
- **义项 1: 自豪的 (adj.)** — 因成就而感到光荣
  - "I am **proud** of the team for shipping this feature under such a tight deadline."
- **义项 2: 骄傲的 (adj.)** — 自尊心强（可能带负面意味）
  - "Don't be too **proud** to ask for help when you are stuck."
- **义项 3: 引以为傲的 (adj.)** — 对某事物感到骄傲
  - "This codebase is something we are **proud** of — it's clean, tested, and well-documented."

---

### 215. embarrassed
- **义项 1: 尴尬的 (adj.)** — 因犯错而在他人面前感到难堪
  - "I was **embarrassed** when I realized I had deployed to production instead of staging."
- **义项 2: 羞愧的 (adj.)** — 感到不光彩
  - "He felt **embarrassed** about making the same mistake twice."
- **义项 3: 窘迫的 (adj.)** — 不知如何应对的情况
  - "The **embarrassed** silence after the demo failure was deafening."

---

### 216. surprised
- **义项 1: 惊讶的 (adj.)** — 因意外之事而感到吃惊
  - "I was **surprised** that the old server could handle the traffic spike."
- **义项 2: 意外的 (adj.)** — 没有想到的
  - "The test results were **surprising** — the new algorithm was actually slower."
- **义项 3: 惊喜的 (adj.)** — 好的意外
  - "The team was pleasantly **surprised** by the early completion of the project."

---

### 217. shocked
- **义项 1: 震惊的 (adj.)** — 因坏事发生而感到强烈震动
  - "I was **shocked** to see the database was completely unresponsive."
- **义项 2: 触电的 (adj.)** — 因接触电流而受击
  - "He got **shocked** when he touched the exposed cable."
- **义项 3: 惊愕的 (adj.)** — 因极端意外而说不出话
  - "The team was **shocked** when the CTO announced the company restructuring."

---

### 218. bored
- **义项 1: 无聊的 (adj.)** — 对某事提不起兴趣
  - "I was **bored** during the two-hour meeting about compliance."
- **义项 2: 令人厌烦的 (adj.)** — 让人感到乏味
  - "The repetitive task of updating config files is **bored** work."
- **义项 3: 厌倦的 (adj.)** — 因重复而失去兴趣
  - "She got **bored** with the legacy project and requested a transfer to a new team."

---

### 219. interested
- **义项 1: 感兴趣的 (adj.)** — 对某事有好奇心
  - "I am **interested** in learning more about distributed systems."
- **义项 2: 关注的 (adj.)** — 对某事给予注意
  - "The stakeholders are very **interested** in the migration progress."
- **义项 3: 有关系的 (adj.)** — 与某事物相关的
  - "The **interested** parties include the engineering team and the product department."

---

### 220. curious
- **义项 1: 好奇的 (adj.)** — 想了解更多或探索未知
  - "I am **curious** about why the system behaves differently under load."
- **义项 2: 奇怪的 (adj.)** — 不寻常或难以理解
  - "It is **curious** that the error only occurs on mobile devices."
- **义项 3: 求知欲强的 (adj.)** — 渴望学习和了解
  - "A **curious** engineer always asks why things work the way they do."

---

### 221. jealous
- **义项 1: 嫉妒的 (adj.)** — 对别人的成就感到不快
  - "I am a bit **jealous** of the frontend team's new design system."
- **义项 2: 吃醋的 (adj.)** — 在情感关系中的嫉妒
  - "He got **jealous** when his colleague was chosen for the promotion."
- **义项 3: 珍惜的 (adj.)** — 极力维护的
  - "She is **jealous** of her code quality standards and doesn't compromise on them."

---

### 222. grateful
- **义项 1: 感激的 (adj.)** — 对别人的帮助表示感谢
  - "I am **grateful** that my colleague stayed late to help debug the issue."
- **义项 2: 庆幸的 (adj.)** — 对某事没有发生坏结果而感到幸运
  - "We are **grateful** that the backup worked and no data was lost."
- **义项 3: 感恩的 (adj.)** — 长期意识到他人的善意
  - "She is **grateful** for the mentorship she received early in her career."

---

### 223. hopeful
- **义项 1: 有希望的 (adj.)** — 对积极结果持期望
  - "I am **hopeful** that the new caching strategy will reduce latency significantly."
- **义项 2: 抱有希望的 (adj.)** — 对未来抱有信心
  - "The team is **hopeful** about the Q2 roadmap despite the current challenges."
- **义项 3: 乐观的 (adj.)** — 倾向于看到好的一面
  - "Her **hopeful** attitude kept the team motivated during the tough project."

---

### 224. lonely
- **义项 1: 孤独的 (adj.)** — 感觉独自一人
  - "Working remotely can feel **lonely** sometimes without the office buzz."
- **义项 2: 寂寞的 (adj.)** — 缺乏陪伴或交流
  - "The **lonely** on-call shift was quiet until the pager went off at 3 AM."
- **义项 3: 荒凉的 (adj.)** — 形容地方人烟稀少
  - "The **lonely** stretch of road between the office and the data center had no cell service."

---

### 225. depressed
- **义项 1: 沮丧的 (adj.)** — 持续的悲观和低能量状态
  - "He felt **depressed** after the project he worked on for six months was canceled."
- **义项 2: 低落的 (adj.)** — 情绪低落
  - "The failed deployment left the team feeling **depressed**."
- **义项 3: 凹陷的 (adj.)** — 表面下沉或下压
  - "The **depressed** key on the keyboard was not registering any input."

---

### 226. stressed
- **义项 1: 有压力的 (adj.)** — 因工作或生活感到紧张
  - "I feel **stressed** when there are too many open pull requests to review."
- **义项 2: 强调的 (adj.)** — 被重点提出的
  - "The importance of testing was **stressed** in the team meeting."
- **义项 3: 受力的 (adj.)** — 物理上承受压力
  - "The **stressed** metal beam showed signs of fatigue after years of use."

---

### 227. relaxed
- **义项 1: 放松的 (adj.)** — 没有压力或紧张
  - "I feel more **relaxed** now that the deployment is complete."
- **义项 2: 宽松的 (adj.)** — 不严格或随意
  - "The **relaxed** dress code at the startup allows wearing shorts to the office."
- **义项 3: 轻松的 (adj.)** — 不费力的
  - "The **relaxed** pace of the project gave us time to write thorough tests."

---

### 228. love
- **义项 1: 爱 (n.)** — 深厚的感情
  - "I **love** the feeling of shipping a well-tested feature."
- **义项 2: 热爱 (v.)** — 对某事有强烈兴趣
  - "I **love** solving complex performance problems — they are like puzzles."
- **义项 3: 喜爱之物 (n.)** — 最喜欢的事物
  - "Python is my **love** for scripting, but I use Go for production services."

---

### 229. hate
- **义项 1: 讨厌 (v.)** — 强烈不喜欢
  - "I **hate** when the CI pipeline breaks due to flaky tests."
- **义项 2: 憎恨 (n.)** — 极端的反感
  - "His **hate** for legacy code is well-known — he always advocates for rewrites."
- **义项 3: 痛恨 (v.)** — 强烈反对
  - "She **hates** it when people skip code reviews to save time."

---

### 230. like
- **义项 1: 喜欢 (v.)** — 觉得某人或某事好
  - "I **like** how the team collaborates on complex problems."
- **义项 2: 类似的 (prep.)** — 与……相似
  - "This architecture is **like** what we used at my previous company."
- **义项 3: 比如 (prep.)** — 用于举例
  - "NoSQL databases, **like** MongoDB and Cassandra, are schema-less."

---

### 231. enjoy
- **义项 1: 享受 (v.)** — 从中获得快乐
  - "I **enjoy** pair programming because I learn from my teammates."
- **义项 2: 喜欢做 (v.)** — 乐于做某事
  - "I **enjoy** writing documentation when the codebase is well-organized."
- **义项 3: 享有 (v.)** — 拥有某种好的状态
  - "The service **enjoys** 99.99% uptime thanks to the robust architecture."

---

### 232. fear
- **义项 1: 恐惧 (n.)** — 对潜在危险的担忧
  - "The developer had a **fear** of breaking production with a bad deployment."
- **义项 2: 害怕 (v.)** — 感到惧怕
  - "I **fear** that if we don't refactor now, the codebase will become unmaintainable."
- **义项 3: 担心 (v.)** — 忧虑可能发生的不好的事
  - "She **fears** that the single database will become a bottleneck as traffic grows."

---

### 233. trust
- **义项 1: 信任 (n.)** — 对某人或某系统的信心
  - "The team has **trust** in the CI/CD pipeline because it rarely fails."
- **义项 2: 相信 (v.)** — 认为可靠或诚实
  - "I **trust** my colleague's code reviews — they always catch edge cases."
- **义项 3: 托付 (v.)** — 将重要事项交给别人
  - "I **trust** the monitoring system to alert us if something goes wrong."

---

### 234. doubt
- **义项 1: 怀疑 (n.)** — 不确定或不相信
  - "There is some **doubt** about whether the new architecture will scale."
- **义项 2: 质疑 (v.)** — 对真实性或有效性有保留
  - "I **doubt** that the performance improvement is worth the complexity."
- **义项 3: 不相信 (v.)** — 不确信
  - "I **doubt** he can finish the refactor before the deadline — it's too large."

---

### 235. respect
- **义项 1: 尊重 (n.)** — 对某人能力或品质的认可
  - "I have great **respect** for senior engineers who take time to mentor juniors."
- **义项 2: 尊敬 (v.)** — 对某人表示敬重
  - "I **respect** my manager's decision to prioritize code quality over speed."
- **义项 3: 遵守 (v.)** — 遵守规则或界限
  - "All team members must **respect** the code freeze during the release week."

---

### 236. admire
- **义项 1: 钦佩 (v.)** — 因优点或成就而尊敬
  - "I **admire** how she can debug complex distributed system issues quickly."
- **义项 2: 欣赏 (v.)** — 对某事物的美或好感到喜欢
  - "I **admire** the clean architecture of this open-source project."
- **义项 3: 赞赏 (v.)** — 表达肯定和赞美
  - "The team **admired** his dedication to fixing the hard bugs."

---

### 237. courage
- **义项 1: 勇气 (n.)** — 面对困难不退缩的品质
  - "It takes **courage** to admit that your architecture design was wrong."
- **义项 2: 胆量 (n.)** — 敢于做艰难决定的魄力
  - "She had the **courage** to say 'no' to feature creep in the sprint."
- **义项 3: 勇敢 (n.)** — 面对危险的能力
  - "The firefighter showed great **courage** when rescuing people from the building."

---

### 238. confidence
- **义项 1: 自信 (n.)** — 对自己能力的信任
  - "I have **confidence** in my ability to debug this issue."
- **义项 2: 信心 (n.)** — 对某事的正面预期
  - "The test results give us **confidence** that the new system is stable."
- **义项 3: 机密 (n.)** — 私下说的话（in confidence）
  - "I told him in **confidence** that the project might be canceled."

---

### 239. brave
- **义项 1: 勇敢的 (adj.)** — 敢于冒险或面对挑战
  - "It was **brave** of him to suggest rewriting the entire module."
- **义项 2: 无畏的 (adj.)** — 不害怕后果
  - "The **brave** engineer volunteered to give the demo to the CEO."
- **义项 3: 英勇的 (adj.)** — 在危险中仍然坚持
  - "She made a **brave** decision to shut down the server before investigating the issue."

---

### 240. shy
- **义项 1: 害羞的 (adj.)** — 在社交场合感到不自在
  - "He was too **shy** to ask questions during his first week on the team."
- **义项 2: 内敛的 (adj.)** — 不张扬的性格
  - "She is **shy** about sharing her accomplishments, even though she does great work."
- **义项 3: 畏惧的 (adj.)** — 对某事感到犹豫
  - "Don't be **shy** about proposing changes to the architecture."

---

### 241. kind
- **义项 1: 善良的 (adj.)** — 关心他人
  - "She is a **kind** mentor who always makes time for junior developers."
- **义项 2: 种类 (n.)** — 类型或类别
  - "What **kind** of database are you using for this project?"
- **义项 3: 亲切的 (adj.)** — 态度温和友善
  - "He gave me **kind** feedback on my presentation that helped me improve."

---

### 242. friendly
- **义项 1: 友好的 (adj.)** — 态度和善的
  - "The team is very **friendly** to new members, making onboarding easy."
- **义项 2: 对……友好的 (adj.)** — 适合某类用户的
  - "This API is developer-**friendly** with clear error messages and good documentation."
- **义项 3: 亲切的 (adj.)** — 容易接近
  - "The **friendly** atmosphere in the office makes collaboration effortless."

---

### 243. polite
- **义项 1: 有礼貌的 (adj.)** — 遵守社交礼仪
  - "It is **polite** to acknowledge code review comments promptly."
- **义项 2: 客气的 (adj.)** — 言辞得体
  - "She sent a **polite** email asking for an update on the pull request."
- **义项 3: 礼节的 (adj.)** — 符合礼节规范
  - "A **polite** disagreement is better than silent resentment in a team."

---

### 244. honest
- **义项 1: 诚实的 (adj.)** — 说实话、不欺骗
  - "Be **honest** about the project timeline — don't promise what you can't deliver."
- **义项 2: 坦诚的 (adj.)** — 直接表达真实想法
  - "I appreciate your **honest** feedback on my code — it helps me grow."
- **义项 3: 真实的 (adj.)** — 不虚假的
  - "An **honest** estimate is better than an optimistic one that misses the deadline."

---

### 245. patient
- **义项 1: 耐心的 (adj.)** — 能等待或容忍
  - "A good tech lead is **patient** when explaining concepts to junior developers."
- **义项 2: 患者 (n.)** — 接受医疗的人
  - "The **patient** was discharged from the hospital after making a full recovery."
- **义项 3: 有耐心的品质 (n.)** — 不急于求成的态度
  - "Debugging requires **patience** — the answer is rarely obvious."

---

### 246. generous
- **义项 1: 大方的 (adj.)** — 乐于给予
  - "He is **generous** with his time, always helping teammates debug issues."
- **义项 2: 慷慨的 (adj.)** — 给予超过预期
  - "The company offered a **generous** bonus for the successful product launch."
- **义项 3: 宽厚的 (adj.)** — 不过分苛求
  - "The **generous** error budget allowed us to deploy without fear of minor issues."

---

### 247. humble
- **义项 1: 谦虚的 (adj.)** — 不夸耀自己
  - "Despite being a senior architect, she remains **humble** and open to feedback."
- **义项 2: 卑微的 (adj.)** — 地位或身份低微
  - "The project started from **humble** beginnings with just two developers."
- **义项 3: 谦逊的 (adj.)** — 不傲慢
  - "A **humble** attitude helps when receiving critical code reviews."

---

### 248. optimistic
- **义项 1: 乐观的 (adj.)** — 预期好的结果
  - "I am **optimistic** that we can finish the migration by the end of the quarter."
- **义项 2: 积极的 (adj.)** — 看到事物光明的一面
  - "Her **optimistic** outlook keeps the team motivated during tough sprints."
- **义项 3: 过高的 (adj.)** — 过于乐观地估计
  - "The timeline was **optimistic** — it took twice as long as estimated."

---

### 249. pessimistic
- **义项 1: 悲观的 (adj.)** — 预期坏的结果
  - "I am **pessimistic** about finishing all tasks before the holiday break."
- **义项 2: 消极的 (adj.)** — 只看到问题而不看到机会
  - "A **pessimistic** view of the architecture ignores the progress made so far."
- **义项 3: 保守的 (adj.)** — 倾向照最坏情况估计
  - "It's better to be **pessimistic** in your time estimates and over-deliver."

---

### 250. serious
- **义项 1: 严肃的 (adj.)** — 不轻浮、认真的
  - "This is a **serious** security vulnerability that needs immediate attention."
- **义项 2: 严重的 (adj.)** — 程度很深的
  - "The memory leak is a **serious** issue that affects all production instances."
- **义项 3: 认真的 (adj.)** — 真心对待
  - "Are you **serious** about switching the entire stack to Rust?"

---

### Group 6: Daily Life — Quantity, Degree & Comparison（数量、程度与比较）— 50 词

---

### 251. all
- **义项 1: 所有的 (adj.)** — 每一个、全部的
  - "**All** the microservices are deployed in Kubernetes clusters."
- **义项 2: 全部 (pron.)** — 指代全部事物
  - "**All** of the tests passed before the deployment."
- **义项 3: 完全地 (adv.)** — 彻底地
  - "The server is **all** set up and ready for production traffic."

---

### 252. some
- **义项 1: 一些 (adj.)** — 不定数量
  - "**Some** of the endpoints return a 503 error under high load."
- **义项 2: 某些 (adj.)** — 特定的未知个体
  - "**Some** developers prefer Vim, while others use VS Code."
- **义项 3: 大约 (adv.)** — 约莫的数量
  - "There were **some** 200 people at the tech conference."

---

### 253. none
- **义项 1: 没有一个 (pron.)** — 零数量的
  - "**None** of the proposed solutions address the root cause."
- **义项 2: 毫无 (pron.)** — 完全没有
  - "**None** of this would have happened if we had tested the migration first."
- **义项 3: 绝不 (adv.)** — 绝不
  - "This approach is **none** the worse for being unconventional."

---

### 254. many
- **义项 1: 许多 (adj.)** — 大量的（可数名词）
  - "**Many** companies are migrating from monoliths to microservices."
- **义项 2: 很多人 (pron.)** — 指代大量的人或事物
  - "**Many** of the junior developers struggle with writing effective tests."
- **义项 3: 多次 (n.)** — 频繁地
  - "I have told you **many** times not to deploy on Friday."

---

### 255. much
- **义项 1: 很多 (adj.)** — 大量的（不可数名词）
  - "There is too **much** technical debt in this codebase."
- **义项 2: 很大程度上 (adv.)** — 程度副词
  - "The new system is **much** faster than the old one."
- **义项 3: 多（疑问/否定）(pron.)** — 大量的（用于否定句或疑问句）
  - "How **much** time do we have before the release deadline?"

---

### 256. few
- **义项 1: 少数 (adj.)** — 不多（可数名词，有具体数量）
  - "A **few** bugs slipped through the review process."
- **义项 2: 几乎没有 (adj.)** — 很少（不带 a 时表否定）
  - "**Few** developers understand the entire system end to end."
- **义项 3: 几个 (pron.)** — 指代少量的几个
  - "Only a **few** of us have access to the production database."

---

### 257. little
- **义项 1: 少量的 (adj.)** — 不多的（不可数名词，带 a 表肯定）
  - "I have a **little** experience with Kubernetes, but not enough to lead the migration."
- **义项 2: 几乎没有 (adj.)** — 很少的（不带 a 表否定）
  - "There is **little** we can do to recover the lost data."
- **义项 3: 小的 (adj.)** — 体积或规模小
  - "The **little** script saved us hours of manual work."

---

### 258. more
- **义项 1: 更多的 (adj.)** — 比之前或比其他的多
  - "We need **more** test coverage for the payment module."
- **义项 2: 更加 (adv.)** — 与形容词连用构成比较级
  - "The new architecture is **more** scalable than the old one."
- **义项 3: 额外的 (n.)** — 更多的数量
  - "I need **more** time to review this pull request properly."

---

### 259. most
- **义项 1: 最多的 (adj.)** — 最高数量或程度
  - "**Most** of the team agrees that we need to refactor the codebase."
- **义项 2: 最 (adv.)** — 与形容词连用构成最高级
  - "This is the **most** critical bug we have seen this quarter."
- **义项 3: 大多数 (pron.)** — 大部分的人或物
  - "**Most** of the legacy code is in the payment module."

---

### 260. less
- **义项 1: 更少的 (adj.)** — 比较少的数量（不可数）
  - "We have **less** disk space available than we expected."
- **义项 2: 不那么 (adv.)** — 与形容词连用表示较低程度
  - "The new server is **less** noisy than the old one."
- **义项 3: 减去 (prep.)** — 数学中的减法
  - "The total cost is the base price **less** the discount."

---

### 261. least
- **义项 1: 最少的 (adj.)** — 数量或程度最小的
  - "Let's focus on the tasks with the **least** amount of risk first."
- **义项 2: 最少 (adv.)** — 程度最低的
  - "The migration was the **least** challenging part of the project."
- **义项 3: 至少 (adv.)** — 最低限度
  - "At the very **least**, we should back up the database before upgrading."

---

### 262. enough
- **义项 1: 足够的 (adj.)** — 满足需求的数量
  - "Do we have **enough** memory to run the new service?"
- **义项 2: 足够地 (adv.)** — 达到必要的程度
  - "The server is fast **enough** to handle the expected traffic."
- **义项 3: 受够了 (n.)** — 不能再容忍
  - "I have had **enough** of these flaky tests — we need to fix them."

---

### 263. plenty
- **义项 1: 大量的 (n.)** — 充足的数量
  - "There is **plenty** of room for improvement in the code review process."
- **义项 2: 充足地 (adv.)** — 足够多地
  - "The office has **plenty** of monitors for developers who need dual screens."
- **义项 3: 丰富 (n.)** — 充足的供应
  - "We live in a time of **plenty** when it comes to open-source tools."

---

### 264. several
- **义项 1: 几个 (adj.)** — 多于两个但不多
  - "There are **several** reasons why the deployment failed."
- **义项 2: 数个 (pron.)** — 指代多个人或事物
  - "**Several** of the team members have experience with the new framework."
- **义项 3: 各自的 (adj.)** — 分别的
  - "Each service has its **several** configuration needs."

---

### 265. both
- **义项 1: 两者都 (adj.)** — 两个中的每一个
  - "**Both** the frontend and the backend need to be updated."
- **义项 2: 两者 (pron.)** — 指代两个人或事物
  - "**Both** of the proposals have merit — we need to pick one."
- **义项 3: 既……又…… (conj.)** — 连接两个并列项
  - "The solution is **both** elegant and performant."

---

### 266. either
- **义项 1: 两者之一 (adj.)** — 两个中的任意一个
  - "**Either** approach will work, but one is more cost-effective."
- **义项 2: 也（否定）(adv.)** — 用于否定句尾
  - "I don't like the legacy code **either** — it needs a rewrite."
- **义项 3: 要么……要么 (conj.)** — 选择其一
  - "**Either** we fix the performance issue now, or we will face a bigger problem later."

---

### 267. neither
- **义项 1: 两者都不 (adj.)** — 两个都不
  - "**Neither** solution is ideal for our use case."
- **义项 2: 也不 (pron.)** — 两个都不选
  - "**Neither** of the candidates has experience with our tech stack."
- **义项 3: 既不……也不 (conj.)** — 两个情况都否定
  - "The system is **neither** fast nor reliable in its current state."

---

### 268. each
- **义项 1: 每个 (adj.)** — 指集体中的每一个个体
  - "**Each** microservice has its own CI/CD pipeline."
- **义项 2: 各自 (pron.)** — 每个事物
  - "**Each** of the containers runs in its own isolated environment."
- **义项 3: 每 (adv.)** — 以每个为单位
  - "The tickets cost $50 **each**."

---

### 269. every
- **义项 1: 每个 (adj.)** — 所有个体中的每一个
  - "**Every** commit to the main branch triggers a deployment."
- **义项 2: 每……（时间）(adj.)** — 以固定的时间间隔
  - "We deploy **every** Monday morning."
- **义项 3: 全部的 (adj.)** — 强调全部
  - "I have read **every** line of the documentation."

---

### 270. any
- **义项 1: 任何 (adj.)** — 不特定的个体
  - "Let me know if you have **any** questions during the deployment."
- **义项 2: 任何（否定/疑问）(pron.)** — 一些（用于否定和疑问句）
  - "I don't have **any** experience with that framework."
- **义项 3: 任意一个 (pron.)** — 任何一个
  - "**Any** of the three solutions would work for this problem."

---

### 271. whole
- **义项 1: 整个的 (adj.)** — 完整的、全部的
  - "The **whole** team is working on the migration this sprint."
- **义项 2: 整体 (n.)** — 事物的全部
  - "The **whole** is greater than the sum of its parts."
- **义项 3: 完全地 (adv.)** — 彻底地
  - "That's a **whole** new approach to the problem."

---

### 272. half
- **义项 1: 一半 (n.)** — 二等分之一
  - "**Half** of the team is on vacation this week."
- **义项 2: 半数的 (adj.)** — 一半数量的
  - "I spent **half** the day debugging a configuration issue."
- **义项 3: 不完全地 (adv.)** — 部分地
  - "The migration is only **half** done — we still need to move the data."

---

### 273. quarter
- **义项 1: 四分之一 (n.)** — 四等分之一
  - "A **quarter** of the budget is allocated to infrastructure costs."
- **义项 2: 季度 (n.)** — 一年的四分之一（三个月）
  - "The Q2 release is scheduled for the end of the **quarter**."
- **义项 3: 一刻钟 (n.)** — 15 分钟
  - "I will be there in a **quarter** of an hour."

---

### 274. percent
- **义项 1: 百分比 (n.)** — 以 100 为基数的比例
  - "CPU usage is at 90 **percent** — we need to scale up."
- **义项 2: 百分之……(n.)** — 比例单位
  - "The new system improved performance by 30 **percent**."
- **义项 3: 百分点 (n.)** — 百分比的具体数值
  - "The error rate dropped from 5 percent to 1 **percent**."

---

### 275. number
- **义项 1: 数字 (n.)** — 抽象的数值概念
  - "The **number** of concurrent users doubled after the feature launch."
- **义项 2: 数量 (n.)** — 可计量的多少
  - "A large **number** of requests are timing out under peak load."
- **义项 3: 编号 (n.)** — 标识序号
  - "What is the ticket **number** for the bug you are fixing?"

---

### 276. amount
- **义项 1: 数量 (n.)** — 不可计量的量
  - "The **amount** of data we process daily has increased tenfold."
- **义项 2: 总额 (n.)** — 总的量
  - "The **amount** of memory used by the application is concerning."
- **义项 3: 达到（v.）** — 等同于
  - "The changes **amount** to a complete rewrite of the module."

---

### 277. total
- **义项 1: 总计 (adj.)** — 全部的、合计的
  - "The **total** cost of the cloud infrastructure this month is $5,000."
- **义项 2: 总数 (n.)** — 所有部分的和
  - "The **total** came to 500 GB of data migrated."
- **义项 3: 完全的 (adj.)** — 彻底的
  - "The deployment was a **total** disaster — everything went wrong."

---

### 278. average
- **义项 1: 平均 (adj.)** — 统计中的中间值
  - "The **average** response time is 150 milliseconds."
- **义项 2: 平均水平 (n.)** — 一般的标准
  - "Our uptime is above the industry **average** of 99.9%."
- **义项 3: 普通的 (adj.)** — 不特别出众
  - "He is an **average** programmer, but an excellent debugger."

---

### 279. maximum
- **义项 1: 最大值 (n.)** — 可能的最高值
  - "The CPU **maximum** was reached during the traffic spike."
- **义项 2: 最高的 (adj.)** — 最大的
  - "The **maximum** number of connections is limited to 100."
- **义项 3: 最大量 (adj.)** — 极限的
  - "We achieved **maximum** throughput after the optimization."

---

### 280. minimum
- **义项 1: 最小值 (n.)** — 可能的最低值
  - "The **minimum** memory requirement for this service is 512 MB."
- **义项 2: 最低的 (adj.)** — 最小的
  - "We need a **minimum** of three replicas for high availability."
- **义项 3: 至少 (adj.)** — 最低限度
  - "The **minimum** we can do is run the tests before deployment."

---

### 281. extra
- **义项 1: 额外的 (adj.)** — 多于平常的
  - "We allocated **extra** compute resources for the holiday traffic."
- **义项 2: 额外费用 (n.)** — 需要多付的钱
  - "The **extra** storage cost us an additional $100 per month."
- **义项 3: 特别地 (adv.)** — 非常
  - "Be **extra** careful when deploying the database migration."

---

### 282. additional
- **义项 1: 附加的 (adj.)** — 在原有基础上增加的
  - "We need **additional** monitoring for the new service."
- **义项 2: 补充的 (adj.)** — 额外补充的
  - "The **additional** documentation helped the new team members get up to speed."
- **义项 3: 进一步的 (adj.)** — 在已有基础上继续
  - "No **additional** changes are required for this release."

---

### 283. different
- **义项 1: 不同的 (adj.)** — 不一样
  - "Each microservice uses a **different** database technology."
- **义项 2: 有区别的 (adj.)** — 相异的
  - "The staging and production environments are **different** in several ways."
- **义项 3: 各种的 (adj.)** — 多种多样的
  - "We tried three **different** approaches before finding the right one."

---

### 284. same
- **义项 1: 相同的 (adj.)** — 一样的
  - "All team members use the **same** coding style guidelines."
- **义项 2: 同样的 (pron.)** — 同一个人或事物
  - "The **same** bug was reported by three different users."
- **义项 3: 仍然 (adv.)** — 虽然变了但仍保持原状
  - "The process remains the **same** even after the team reorganization."

---

### 285. various
- **义项 1: 各种各样的 (adj.)** — 多种不同的
  - "The platform supports **various** authentication methods."
- **义项 2: 多方面的 (adj.)** — 来自不同方面的
  - "We received feedback from **various** stakeholders before finalizing the design."
- **义项 3: 不同的 (adj.)** — 有区别的
  - "There are **various** opinions about which database to use."

---

### 286. common
- **义项 1: 常见的 (adj.)** — 经常出现的
  - "Memory leaks are a **common** issue in long-running applications."
- **义项 2: 共同的 (adj.)** — 共享的
  - "The team has a **common** goal of improving system reliability."
- **义项 3: 普通的 (adj.)** — 平凡的
  - "This is a **common** mistake that many junior developers make."

---

### 287. rare
- **义项 1: 罕见的 (adj.)** — 不常发生的
  - "It is **rare** for the production system to have a complete outage."
- **义项 2: 珍贵的 (adj.)** — 稀缺而有价值的
  - "A developer who can both write code and design architecture is **rare**."
- **义项 3: 未熟的 (adj.)** — 指肉类烹饪程度
  - "I prefer my steak **rare**, cooked just enough to sear the outside."

---

### 288. unique
- **义项 1: 独特的 (adj.)** — 唯一的、非同寻常的
  - "Each container gets a **unique** IP address within the cluster."
- **义项 2: 独一无二的 (adj.)** — 没有其他相同
  - "Every deployment has a **unique** build ID for tracking purposes."
- **义项 3: 特有的 (adj.)** — 特定于某事物的
  - "The **unique** challenges of distributed systems require specialized knowledge."

---

### 289. only
- **义项 1: 唯一的 (adj.)** — 单个的、没有其他
  - "The **only** way to fix this bug is to rewrite the query."
- **义项 2: 仅仅 (adv.)** — 只限于
  - "I **only** need five minutes to review your pull request."
- **义项 3: 反而 (conj.)** — 连接到相反的结果
  - "The optimization not only didn't help, but it **only** made things worse."

---

### 290. single
- **义项 1: 单一的 (adj.)** — 一个的
  - "A **single** database query is causing the performance bottleneck."
- **义项 2: 单身的 (adj.)** — 未婚的
  - "He is **single** and can travel for conferences whenever needed."
- **义项 3: 单程的 (adj.)** — 单向的
  - "The deployment has a **single** point of failure that we need to address."

---

### 291. double
- **义项 1: 双倍 (adj.)** — 两倍的
  - "The traffic **doubled** after the product was featured on the homepage."
- **义项 2: 双重的 (adj.)** — 由两部分组成的
  - "We use **double** encryption for sensitive data in transit."
- **义项 3: 加倍努力 (v.)** — 付出两倍的精力
  - "We need to **double** our testing efforts before the release."

---

### 292. multiple
- **义项 1: 多个的 (adj.)** — 超过一个的
  - "The application runs across **multiple** availability zones."
- **义项 2: 多重的 (adj.)** — 涉及多个方面的
  - "The bug was caused by **multiple** factors, not just one."
- **义项 3: 乘数 (n.)** — 倍数
  - "The throughput increased by a **multiple** of ten after the upgrade."

---

### 293. pair
- **义项 1: 一对 (n.)** — 两个一起使用的事物
  - "I bought a new **pair** of monitors for my home office setup."
- **义项 2: 结对 (v.)** — 两人一起工作
  - "We **pair** program to share knowledge and catch bugs early."
- **义项 3: 配对 (n.)** — 两个不同但一起工作的物
  - "The key-value **pair** is stored in the configuration file."

---

### 294. hundred
- **义项 1: 一百 (num.)** — 数字 100
  - "The system can handle a few **hundred** requests per second."
- **义项 2: 数以百计 (n.)** — 大量的（复数形式）
  - "**Hundreds** of microservices communicate through the message bus."
- **义项 3: 百年 (n.)** — 世纪的量级
  - "This building has stood for over a **hundred** years."

---

### 295. thousand
- **义项 1: 一千 (num.)** — 数字 1,000
  - "We serve over a **thousand** requests per second at peak traffic."
- **义项 2: 数以千计 (n.)** — 大量的（复数形式）
  - "**Thousands** of containers are running across the cluster."
- **义项 3: 极大数量 (n.)** — 比喻数量巨大
  - "There are a **thousand** reasons why the deployment could fail."

---

### 296. million
- **义项 1: 一百万 (num.)** — 数字 1,000,000
  - "The database stores over 10 **million** user records."
- **义项 2: 数百万 (n.)** — 非常大的数量
  - "**Millions** of events are processed by the pipeline every day."
- **义项 3: 巨额 (adj.)** — 比喻极大量
  - "The **million**-dollar question is: should we rewrite or refactor?"

---

### 297. billion
- **义项 1: 十亿 (num.)** — 数字 1,000,000,000
  - "The analytics system processes over a **billion** events daily."
- **义项 2: 数十亿 (n.)** — 极大的数量
  - "**Billions** of API calls are made to the platform each month."
- **义项 3: 巨量（比喻）(n.)** — 不可计数的庞大数量
  - "There are a **billion** things to consider before migrating databases."

---

### 298. first
- **义项 1: 第一 (adj.)** — 排在最前面的
  - "The **first** step in debugging is reproducing the issue."
- **义项 2: 首次 (adv.)** — 第一次
  - "I **first** learned about Kubernetes at a conference in 2018."
- **义项 3: 最初的 (n.)** — 开端的事物
  - "The **first** version of the API was simple but functional."

---

### 299. last
- **义项 1: 最后的 (adj.)** — 在时间或顺序上最后的
  - "The **last** commit before the release was a hotfix for the login bug."
- **义项 2: 上一个 (adj.)** — 最近的过去
  - "**Last** sprint we delivered 30 story points."
- **义项 3: 持续 (v.)** — 维持某个状态一段时间
  - "The deployment took longer than expected — it **lasted** three hours."

---

### 300. next
- **义项 1: 下一个 (adj.)** — 紧随其后的
  - "The **next** sprint starts immediately after the retrospective."
- **义项 2: 接下来 (adv.)** — 在时间或顺序上接着
  - "What is the **next** step after the code review?"
- **义项 3: 紧邻的 (adj.)** — 位置或关系上最近
  - "The backup data center is in the **next** building."

---

## 3. Sentence-Making Practice

以下 10 个练习融合了 300 词中的高频词汇、一般现在时 / 现在进行时、以及复杂句模式。每个练习先自己写，再对照参考答案。

---

### 1. 你正在向一个新同事解释：当前端团队开发新界面时，后端团队正在重构微服务。使用 while 引导的时间状语从句 + 两个现在进行时。

**参考答案:** "While the frontend team **is working** on the new interface, the backend team **is refactoring** the microservices to improve performance."
> (while 从句 + 主句都用现在进行时——表示"此刻同时进行"。主句中的 "to improve performance" 是不定式状语表目的。)

---

### 2. 描述一个系统规则：当 CPU 使用率超过 80% 时，负载均衡器会自动增加实例。使用 when 引导的条件/时间从句。

**参考答案:** "When the CPU usage **exceeds** 80 percent, the **load balancer** automatically **adds** more instances to the cluster."
> (when 从句和主句都用一般现在时——描述系统的默认行为逻辑。从句用 exceeds（第三人称单数 + -s），主句用 adds。)

---

### 3. 解释你目前正在做的工作——把 CI/CD 项目从 Jenkins 迁移到 GitHub Actions，因为团队需要更快的反馈。

**参考答案:** "I **am migrating** our CI/CD pipeline from Jenkins to GitHub Actions because the team **needs** faster feedback on pull requests."
> (主句用现在进行时 am migrating——当前阶段的工作。原因从句用一般现在时 needs——"团队需要"是一个常态需求。)

---

### 4. 描述你们公司的架构——数据库 schema 支持关系查询和文档访问模式，这让系统更灵活。使用 which 引导的非限制性定语从句。

**参考答案:** "The database **schema** supports both relational queries and document-based access patterns, **which** makes the system much more flexible."
> (which 指代前面整件事。both...and... 连接两个并列宾语。makes 是第三人称单数，因为 which 指代的是"整件事"——视为单数。)

---

### 5. 你在和同事讨论一个生产事故——支付服务的延迟正在增加，影响了亚太地区用户的结账流程。使用 and 连接两个现在进行时并列分句。

**参考答案:** "We **are seeing** increased **latency** in the payment service, and this **is affecting** the checkout flow for users in Asia-Pacific."
> (第一个分句用现在进行时 are seeing，第二个分句用 is affecting。this 指代前面的整个情况。increased 是过去分词作定语修饰 latency，意为"已经增加的"。)

---

### 6. 描述一个事实：在这个平台上工作的每位工程师都知道干净代码很重要，但很少有人有时间重构遗留模块。使用 who 定语从句和 but 并列。

**参考答案:** "Every engineer **who** works on the platform knows that clean code matters, **but** few people have the time to refactor legacy modules."
> (who works on the platform 是定语从句修饰 Every engineer。knows 后面接 that 引导的宾语从句。but 连接两个并列分句，表转折。)

---

### 7. 你明天要和产品经理开会，讨论你们刚刚开始的新功能的测试套件。用现在进行时表将来安排 + 一般现在时。

**参考答案:** "I **am meeting** the PM tomorrow to discuss the test suite that we **are building** for the new feature."
> (第一个现在进行时 am meeting 表将来安排。第二个现在进行时 are building 表当前正在进行的工作。that we are building 是定语从句修饰 test suite。)

---

### 8. 描述一个状态：这个微服务没有足够的冗余——它的心跳检查经常失败。用一般现在时否定 + 陈述。

**参考答案:** "This **microservice** **doesn't have** enough **redundancy** — its **heartbeat** check **fails** frequently."
> (doesn't have 是一般现在时否定。因为主语是第三人称单数，加 doesn't 后动词用原形 have。fails 是第三人称单数形式。)

---

### 9. 问你的同事一个问题：他是否同时在处理三个不同的版本分支？用现在进行时疑问句。

**参考答案:** "**Are** you working on three different release **branches** at the same time? That sounds risky."
> (现在进行时疑问句：Are + 主语 + V-ing？at the same time 是介词短语作状语。sounds 是一般现在时——这是你的看法。)

---

### 10. 写一封简短的站会发言：你昨天修复了一个缓存 bug，今天正在做代码审查，明天将检视日志以确认没有回归问题。结合三种时间表达。

**参考答案:** "**Yesterday** I fixed a **cache** bug, today I **am reviewing** the code, and **tomorrow** I **'ll check** the **logs** to make sure there are no regressions."
> (yesterday → 用过去时 fixed。today → 现在进行时 am reviewing，表达"今天这段时期在做"。tomorrow → will check，用 will 表达将来的意图。三种时间状语各搭配对应的时态。)

---

## 4. Weekend Review

### 易混淆词对比

**1. cache vs. buffer（缓存 vs. 缓冲区）**
- "We cleared the Redis **cache** to force the application to reload fresh data."（缓存：存储已读取的数据副本以加速后续访问）
- "The video player uses a **buffer** to store the next 30 seconds of content while you watch."（缓冲区：临时存储尚未处理的数据，平衡速度差异）
- 关键区别：cache 存储的是"已经用过的数据"以加速再次读取，buffer 存储的是"即将处理的数据"以平滑流程。cache 的目的是减少延迟，buffer 的目的是协调速率差异。

**2. cluster vs. node（集群 vs. 节点）**
- "The Kubernetes **cluster** spans three availability zones for high availability."（集群：一组协同工作的计算机集合）
- "One worker **node** went down, and the pods were rescheduled to other nodes."（节点：集群中的单个计算单元）
- 关键区别：cluster = 整体（集合），node = 个体（成员）。一个 cluster 包含多个 node。类比："The team"（团队 = cluster）和 "a team member"（团队成员 = node）。

**3. pair vs. couple（一对 vs. 两三个）**
- "Each key-value **pair** is stored as a separate entry in the configuration file."（一对、一双：严格的两个，互相配合或对应）
- "We need a **couple** of more test cases to cover all the edge cases."（两三个、几个：口语化的少量，不一定是精确的两个）
- 关键区别：pair 强调"两个为一组"的逻辑关系（如 key-value pair），couple 口语中常指"几个、少量"（a couple of days = 两三天，不一定是两天整）。

**4. whole vs. all（整个 vs. 所有）**
- "The **whole** team attended the architecture review meeting."（整个：强调"作为一个整体"，后接单数名词）
- "**All** team members need to complete the security training."（所有：强调"每一个个体"，后接复数名词）
- 关键区别：whole 后面跟单数名词（the whole system），all 后面跟复数名词（all systems）。不能互换：❌ "all system" / ❌ "the whole systems"。

**5. few vs. little（少数 vs. 少量）**
- "**Few** developers understand the entire legacy codebase."（少数 + 可数名词：几乎没有人理解）
- "There is **little** we can do to recover the lost data."（少量 + 不可数名词：几乎没有办法）
- 关键区别：few + 可数名词（few options, few people），little + 不可数名词（little time, little memory）。带上 a 表肯定（a few = 几个，a little = 一点），不带 a 表否定（few = 几乎没有，little = 几乎没有）。

---

### 语法自我检测清单

逐一检查，诚实地标记自己是否掌握：

**一般现在时（Simple Present）：**
- [ ] 我能在第三人称单数主语的句子中正确使用动词的 -s 形式吗？
- [ ] 我能在否定句中正确使用 doesn't + 动词原形吗？（❌ doesn't works）
- [ ] 我能在疑问句中正确使用 Does + 主语 + 动词原形吗？
- [ ] 我能在条件/时间从句中正确使用一般现在时表将来吗？（when the CPU **exceeds**...）
- [ ] 我知道哪些动词是状态动词，不能用于进行时吗？

**现在进行时（Present Continuous）：**
- [ ] 我能在句子中正确使用 am/is/are + V-ing 结构吗？
- [ ] 我能在否定句中正确使用 am/is/are + not + V-ing 吗？
- [ ] 我能在疑问句中将 be 动词提到主语前面吗？
- [ ] 我能区分"此刻进行"、"临时阶段"和"将来安排"三种用法吗？
- [ ] 我能在复杂句中正确组合现在进行时和其他时态吗？

**复杂句结构：**
- [ ] 我能用 while 引导时间状语从句（主句和从句都用进行时）吗？
- [ ] 我能用 when 引导条件/时间从句（都用一般现在时）吗？
- [ ] 我能用 which 引导非限制性定语从句指代前面整件事吗？
- [ ] 我能用 who/that 引导定语从句修饰人或事物吗？
- [ ] 我能用 because 引导原因状语从句吗？
- [ ] 我能用 and/but 连接两个并列分句，且各自使用正确的时态吗？
- [ ] 我能用 both...and... 连接并列的宾语或主语吗？

**词汇：**
- [ ] 我能在工作场景中正确使用 50 个基础设施和网络相关的名词吗？（Group 1）
- [ ] 我能在工作场景中正确使用 50 个技术流程相关的名词吗？（Group 2）
- [ ] 我能在日常场景中正确使用 50 个时间相关的词汇吗？（Group 3）
- [ ] 我能在日常场景中正确使用 50 个身体和健康相关的词汇吗？（Group 4）
- [ ] 我能在日常场景中正确使用 50 个情绪和性格相关的词汇吗？（Group 5）
- [ ] 我能在日常场景中正确使用 50 个数量和比较相关的词汇吗？（Group 6）

---

### 周末练习建议

**建议用时：** 周六 60 分钟 + 周日 60 分钟

**周六练习：语法归档**
选 6 个本周学过的复杂句中的 6 个句子，每个句子做以下操作：
1. 在代码中找到相似的句子结构（例如 GitHub 上的 issue comment、PR 描述、技术博客）
2. 手写拆解该句子的语法成分（主语、谓语、宾语、定语从句、状语从句等）
3. 大声朗读 3 遍，注意连接词（while, when, which, because, but, and, that）的语调
4. 用自己的话改写这个句子，保持结构不变但替换技术词汇

例如你看到一个 PR 描述："The frontend team is implementing the new dashboard while the backend team is optimizing the API." —— 拆解后替换词汇写你自己的版本。

**周日练习：300 词闪卡挑战**
1. 从 6 个组中每组随机选 5 个词（共 30 个）
2. 不看笔记，说出每个词的 3 个义项和中文意思
3. 用每个词造一个工作场景的句子
4. 找出 5 个你最容易忘记的词，记录下来在下周重点复习
5. 和你一起学习的朋友互相测试（一个人说英文词，一个人说 3 个中文义项）

**下周生存贴士：**
- 在 standup 上说 "Today I **am working on**..."（现在进行时描述当日工作）
- 在技术文档中统一用 "The API **returns**..."（一般现在时描述系统行为）
- 在 PR 描述中用 "This PR **fixes** the bug **that** was caused by..."（定语从句）
- 在讨论架构时说 "**which** makes the system more..."（非限制性定语从句）
- 在解释流程时说 "**When** X **happens**, the system **does** Y"（条件/时间从句）
- 在会议中说 "**While** team A **is doing** X, team B **is doing** Y"（while + 并列进行时）

---

> **下周预告：** Week 3 将学习**一般过去时（Simple Past）和现在完成时（Present Perfect）**——中国学生最难区分的两个时态。周末好好复习，下周见。
