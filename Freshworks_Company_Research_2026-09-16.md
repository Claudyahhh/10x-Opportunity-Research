# Freshworks（NASDAQ: FRSH）公司研究报告
**数据截点：2026-09-16｜仅使用公司官方/SEC 一手资料作为事实依据**

> 研究方法：本文严格区分“事实”和“分析”。带有“公司披露/公司目标/公司估算”的数字来自 Freshworks 官方 IR、SEC 文件、官方产品页或管理层公开材料；“我的判断/情景假设/评分”属于研究分析，不代表公司指引。  
> 由于 Freshworks IR / Nasdaq 官方行情页在本次检索中未能返回 2026-09-16 的可验证实时股价，本文**不使用任何第三方实时行情补洞**。估值部分采用“价格无关的内在价值阈值”+ Freshworks 2026-05-12 官方 Analyst Session 中披露的 $8.50 历史股价作为 dated reference，而不把它当作当前价格。

---

# 一、先用“巴菲特视角”讲明白：Freshworks 到底是一门什么生意？

## 1. 一句话版本

Freshworks 本质上是一家**把企业内部和对外“服务流程”做成云端操作系统，然后按订阅和使用量持续收费的软件公司**。

它卖的不是一张“工单”（ticket），而是企业里一大类每天都会发生、很难停止的工作流：

- 员工电脑坏了，找 IT；
- 新员工入职，要开账号、配电脑、给权限；
- 软件授权到期，要盘点；
- 服务器异常，要报警、找值班人、排查依赖；
- 员工向 HR、财务、法务提交请求；
- 客户发邮件、WhatsApp、网页聊天要求售后；
- AI 先回答、先执行，解决不了再交给真人。

这些流程一旦进入系统，企业会不断积累：

1. 历史工单；
2. 知识库；
3. 员工、设备、软件、资产数据；
4. 审批规则；
5. SLA、权限、审计规则；
6. 第三方集成；
7. 事故和依赖关系；
8. AI 能调用的上下文和工作流。

所以，Freshworks 真正想占据的位置是一个**System of Record + System of Action**：

- **System of Record（记录系统）**：关键运营数据长期沉淀在这里；
- **System of Action（执行系统）**：审批、分配、提醒、自动化、AI Agent 直接在这里执行动作。

这比单纯卖一个“客服聊天框”或者“AI Bot”更有粘性。

Freshworks 2025 年 10-K 把公司产品分成两大类：Employee Experience（EX）与 Customer Experience（CX）；EX 包括 Freshservice、Freshservice for Business Teams、Device42、FireHydrant，CX 以 Freshdesk 系列为核心；Freddy AI Agents / Copilot / Insights 横跨两条产品线。[S1]

---

## 2. 巴菲特会先问的第一件事：客户为什么每年还要继续付钱？

如果一家制造公司停止买某种设备一年，可能只是推迟资本开支；但如果一家有几千名员工的企业把 IT 服务台、设备资产、审批流、事故响应全部迁入 Freshservice，它很难“一年不续费”。

原因不是品牌情感，而是**业务连续性**：

- 工单不能停；
- 员工账号和权限不能停；
- IT 资产盘点不能停；
- 安全与审计不能停；
- 故障响应不能停；
- 客服不能停。

这就是 SaaS 中非常重要的“mission-critical workflow（关键任务工作流）”。

Freshworks 2025 年收入 $838.8m，其中订阅、软件许可和维护收入 $829.4m，专业服务仅 $9.4m；也就是说，它几乎不是靠“人天咨询”赚钱，而是靠高毛利软件持续收费。[S1]

### 对巴菲特最友好的经济特征

2025 年：
- 收入：**$838.8m**
- 毛利：**$712.7m**
- GAAP 毛利率：**85%**
- Free Cash Flow：**$220.9m**
- GAAP Operating Income：**$13.2m**
- Stock-based compensation：**$146.8m**
- 专业服务收入只占约 **1.1%**

Freshworks 的毛利率从 2023 年 83% → 2024 年 84% → 2025 年 85%，公司明确称主要受托管规模效应推动。[S1]

因此，从“资本密集度”看，这是一门非常漂亮的生意：不需要建大量厂房、铺大量库存，收入增长时新增交付成本相对低。

但巴菲特不会直接把 FCF 全部当成“owner earnings（股东真正的经济利润）”，因为 Freshworks 的 SBC 仍然很高。2025 年 SBC 为 $146.8m；2026H1 SBC 仍为 $81.8m，并且 2026-06-30 尚有 $352.6m 未确认的股权激励费用。[S1][S3]

**所以关键问题不是“它有没有现金流”，而是：未来现金流增长能否持续快于股权补偿带来的经济稀释。**

---

## 3. 它真正的商业模式，不是“卖坐席”，而正在从三层收费扩成五层收费

传统 Freshworks 收费主要是：

### 第一层：Seat / Agent based pricing
按使用软件的客服人员、IT 服务人员数量收费。

例如当前官方年付价格：[S6][S7]

| 产品 | 官方起步价格 |
|---|---:|
| Freshservice Starter | $19 / agent / month |
| Freshservice Growth | $49 |
| Freshservice Pro | $99 |
| Freshservice Enterprise | Custom |
| Freshdesk Growth | $19 |
| Freshdesk Pro | $55 |
| Freshdesk Enterprise | $89 |
| Freshdesk Omni Growth | $29 |
| Freshdesk Omni Pro | $79 |
| Freshdesk Omni Enterprise | $119 |
| Freshservice for Business Teams | $49 |
| Freshsales Growth | $9 / user / month |

### 第二层：高阶模块
例如 ITAM、ITOM、ESM、企业安全、Sandbox、审计、CMDB 等。

### 第三层：AI Copilot
例如 Freddy AI Copilot 当前官方价格为 **$29 / agent / month**（适用产品/套餐依官方页面）。[S6][S7]

### 第四层：Usage-based AI
Freshdesk / Omni 等产品当前 Freddy AI Agent 额外 session 的官方价格为 **$49 / 100 sessions**。[S7]

### 第五层：资产、事件、连接器、Agent actions
例如 Freshservice ITAM 使用 Asset Unit 计费，一个 Server/VM/网络设备按 4 个 AU，桌面/移动设备按 1 AU；Freshdesk Omni 还对 connector tasks 和 MCP actions 提供用量型收费。[S8][S7]

这件事非常关键。

因为 AI 会减少“人类客服坐席”的工作量。如果 Freshworks 仍完全按 seat 收钱，AI 越成功，客户需要的人越少，理论上反而会压缩 seat 数量。

Freshworks 正在做的，是把计价单位从：

> 人头

扩展到：

> 人头 + 资产 + 事件 + AI session + workflow/action

这决定了 AI 对 Freshworks 最终是**吞噬 seat revenue**，还是**扩大 ARPA（单客收入）**。

---

# 二、行业词汇表：后文所有关键名词先解释清楚

| 术语 | 含义 | 用 Freshworks 举例 |
|---|---|---|
| SaaS | Software as a Service，软件通过云端提供，客户持续订阅，而不是一次性买断 | Freshservice / Freshdesk |
| ARR | Annual Recurring Revenue，按当前合同折算的未来 12 个月经常性收入 run-rate | 用来观察 SaaS 当前业务规模 |
| NDR | Net Dollar Retention，同一批老客户一年后的 ARR ÷ 一年前 ARR，包含扩容、降配和流失 | 104% = 老客户群总体仍净扩张 4% |
| EX | Employee Experience，员工体验 | IT、HR、财务等内部服务 |
| CX | Customer Experience，客户体验 | 客服、售后、聊天 |
| ITSM | IT Service Management，IT 服务管理 | 报障、请求、变更、问题、知识库 |
| ITAM | IT Asset Management，IT 资产管理 | 电脑、服务器、软件许可证的发现、盘点和生命周期 |
| ITOM | IT Operations Management，IT 运行管理 | 告警、服务健康、云资源、故障响应 |
| ITIM | IT Infrastructure Management，IT 基础设施管理 | 服务器、网络、云、依赖关系可视化 |
| ESM | Enterprise Service Management，把 ITSM 的服务工作流扩到 HR、Finance、Legal、Facilities | “员工要证明/采购/法务审批”也变成可追踪服务请求 |
| CMDB | Configuration Management Database，配置管理数据库 | 记录服务器、应用、设备及它们之间的依赖 |
| Ticket | 工单，一条需要处理的服务请求/问题记录 | “VPN 无法连接”生成一个 ticket |
| SLA | Service Level Agreement，服务等级协议 | “P1 故障 15 分钟响应” |
| ITIL | IT 服务管理的方法论/流程标准 | ITSM 产品常按 ITIL 流程设计 |
| Omnichannel | 全渠道，把邮件、网页聊天、WhatsApp、电话等放在统一工作台 | Freshdesk Omni |
| CRM | Customer Relationship Management，客户关系管理 | Freshsales |
| AI Agent | 能基于上下文主动调用工具、执行工作流、完成任务的 AI | Freddy AI Agent |
| Copilot | 协助真人员工，而不是完全替代真人的 AI 助手 | 摘要、建议回复、查知识、辅助处理工单 |
| Agentic AI | 可以规划、选择工具并多步骤执行动作的 AI | 自动开权限、触发审批、更新系统 |
| MCP | Model Context Protocol，让 AI 与外部数据/工具建立标准化连接的协议 | Freshworks MCP Gateway |
| Attach Rate | 加购率，一笔主产品订单中同时购买某附加模块的比例 | Copilot 在大型新单中的 attach rate |
| Land and Expand | 先在一个部门/小规模落地，再扩坐席、部门、模块 | IT → HR / Finance / Legal |
| ARPA | Average Revenue per Account，平均每客户收入 | 上移大客户后应提高 |
| TAM | Total Addressable Market，理论可服务总市场 | Freshworks 自估 EX TAM ~$45B |
| PLG | Product-led Growth，以产品试用/自助体验驱动获客和转化 | 14-day free trial、透明定价 |
| Upmarket | 从中小企业向更大客户提升 | $100k+ ARR 客户增长 |
| TCO | Total Cost of Ownership，总拥有成本 | 软件费 + 实施 + 运维 + 顾问 + 升级成本 |
| Switching Cost | 切换成本 | 数据迁移、流程重建、集成、培训、审计重做 |
| System of Record | 企业关键数据的权威记录系统 | CMDB、资产、工单、服务记录 |
| System of Action | 直接触发和执行实际业务动作的系统 | workflow + AI Agent |
| FCF | Free Cash Flow，自由现金流 | 经营现金流减资本开支/内部软件资本化 |
| SBC | Stock-Based Compensation，股票薪酬 | 不立即耗现金，但会造成经济稀释 |
| Rule of 40 | SaaS 常用效率指标：增长率 + 某一利润/FCF margin ≈ 40%+ | Freshworks 按公司口径称连续多个季度达成 |
| Gross Margin | 毛利率，扣除直接交付成本后剩余收入比例 | 2025 GAAP 85% |
| Operating Leverage | 经营杠杆，收入增长快于费用增长，利润率随规模上升 | 2025 收入 +16%，opex -6% |
| RPO | Remaining Performance Obligations，已签但尚未确认的合同收入 | 2025 年末 $644.4m |

---

# 三、Freshworks 现在到底有哪些业务？

## A. Employee Experience（EX）——当前核心增长引擎

这是今天研究 Freshworks 最重要的业务。

2026Q2，管理层在官方 earnings transcript 中披露：

- EX ARR：**$567m**
- YoY：**+23% reported / +24% constant currency**
- 约占总 ARR：**59%**
- 公司预计 2026 年末 EX ARR **> $600m**
- 预计全年 EX 增长仍处于 mid-20s
- EX NDR（剔除 legacy Device42）**>111% constant currency**

公司 2026 Analyst Session 进一步给出方向：
- 2021 年 EX 仅约占总 ARR 37%；
- 2026E 约 60%；
- 2028E 目标约 70%；
- Freshservice 目标 2028 年接近 / 超过 **$1B ARR**。[S4][S5]

这说明 Freshworks 已经发生了战略重心迁移：

> 过去：一篮子 SMB SaaS 工具  
> 现在：以 Freshservice 为核心的 AI Service Operations 平台

---

## B. Freshservice：主航道

Freshservice 已经不是简单 helpdesk，而在往四个方向统一：

1. ITSM：服务流程；
2. ITAM：资产；
3. ITOM：运行/告警；
4. ESM：把流程扩展到非 IT 部门。

Freshworks 官方称 Freshservice 已有约 **20,000** 全球客户，过去约五年 ARR 规模增长接近 5 倍。[S5]

### Freshservice ITSM

典型能力：
- Incident Management；
- Service Request；
- Knowledge Management；
- Problem Management；
- Change Management；
- Major Incident；
- Service Catalog；
- SLA；
- Workflow；
- Employee Portal。

**客户买的是：让 IT 从“人肉群聊 + Excel + 邮件”变成可追踪、可自动化、可审计的工作流。**

---

## C. ITAM / Device42：从工单延伸到“企业 IT 的地图”

Freshworks 2024 年以约 **$238.1m** 收购 Device42，其中约 $225.3m 为现金。[S1]

Device42 的核心价值不是再开一个工单，而是回答：

- 我到底有哪些服务器/虚拟机/设备？
- 哪个业务依赖哪个服务器？
- 哪些软件许可证闲置？
- 哪个资产影响哪项服务？
- 一个故障发生时，影响链条是什么？

这会使 Freshservice 从“ticket database”向“IT system of record”靠近。

2026Q1，Freshworks 已经把 Device42 的 discovery / dependency mapping 更原生地整合进 Freshservice。[S10]

2026Q2 管理层披露，大型新 EX landing 中约 **1/3** 包含 ITAM，这是一个非常重要的 cross-sell 信号。[S4]

---

## D. ESM / Freshservice for Business Teams：把 IT 的工作流复制到 HR、Finance、Legal

ESM 的逻辑非常直观：

一个公司内部不只有 IT 在“接请求”。

HR 有：
- 入职；
- 离职；
- 调岗；
- 证明；
- 福利申请。

财务有：
- 报销；
- 采购；
- 付款；
- 预算审批。

法务有：
- 合同审核；
- NDA；
- 合规请求。

所以 Freshworks 可以用同一套：
> Portal + Ticket + Workflow + SLA + Knowledge + AI

把“服务管理”扩展到所有部门。

2025 年末 ESM ARR 已超过 **$40m**，接近同比翻倍；2026Q2 官方管理层披露已突破 **$50m ARR、同比 +67%**，且约 **1/5 的新 EX seats 来自 IT 之外**。[S9][S4]

当前 Freshservice for Business Teams 官方年付价为 **$49 / agent / month**。[S8]

这条线的重要性在于：它扩大了同一客户里的 seat ceiling，而不必重新获取一家新公司。

---

## E. ITOM + FireHydrant：向“故障发生前后”的运行环节扩张

Freshworks 2026-01-01 以 **$88.7m cash** 收购 FireHydrant，其中初步确认 goodwill $51.3m。[S3]

FireHydrant 主要做：

- Alert ingestion；
- On-call；
- Escalation；
- Major incident coordination；
- Runbook；
- Post-incident analytics。

这使 Freshworks 从：

> “员工发现问题 → 提 ticket”

向：

> “系统先发现异常 → 告警 → 找人 → 协同处置 → 复盘 → AI 未来甚至提前预防”

推进。

这是 Freshworks 从 ITSM 升级成 **Service Operations** 的关键。

---

## F. Freddy AI：不是一个单独 App，而是整个产品组合的“第二收费层”

### Freddy AI Agent
让 AI 自助解决问题、调用 workflow、跨系统执行动作。

### Freddy AI Copilot
帮助人类 agent：
- 总结；
- 翻译；
- 草拟回复；
- 推荐知识；
- 分析 ticket；
- 建议下一步。

### Freddy AI Insights
帮助管理者：
- 找异常；
- root-cause analysis；
- 对话式查指标；
- 主动预警。

### AI Agent Studio
2026 年推出 no-code Agent Studio，可让管理员构建专用 AI Agent / workflow，不必依赖工程团队。[S11]

### MCP Gateway
让 Freshservice 数据和动作连接外部 AI 系统，并允许 Freddy 调用外部工具。[S11]

### 2026-09-15 最新官方更新
Freshworks 继续把 AI 从“辅助回答”推向更深层执行：
- 用自然语言描述流程后自动生成 executable workflow；
- Email AI Agent 可进行多轮邮件处理；
- Copilot 开始主动推送上下文和建议，而不仅仅等待 prompt；
- 对知识检索增加 filtered search；
- MCP Gateway 继续强化与第三方 AI/系统互操作。[S12]

这说明 Freshworks 并不是只在旧 SaaS 上加一个聊天机器人，而是在重写服务流程的执行层。

---

## G. Customer Experience（CX）：今天不是增长核心，而是“现金牛/稳定器候选”

主要产品：
- Freshdesk；
- Freshdesk Omni；
- Freshchat；
- Freshcaller；
- Freshsales；
- Freshmarketer。

2026Q2 管理层披露：
- CX ARR：约 **$400m**
- YoY：约 **+3% reported / +4% constant currency**
- 2026 全年预期：low-single-digit growth
- >90% Freshdesk 客户已迁移到新平台。[S4]

因此 CX 的投资逻辑已经改变。

过去问：
> Freshdesk 能不能继续高增长？

现在更合理的问题是：
> 在低个位数增长下，CX 能否以更低 GTM 投入贡献高利润，同时让 AI / Freshdesk Omni 重启 ARPA 增长？

Freshworks 2026 Analyst Session 的经营模型明确提出：CX 以 inbound 为主，并目标成为 **30%+ operating margin** 的业务。[S5]

这更像“收割成熟业务利润，给 EX 投资”。

---

# 四、产品数据和财务数据总盘点

## 1. 收入

| 年度 | Revenue | YoY |
|---|---:|---:|
| 2023 | $596.4m | — |
| 2024 | $720.4m | +21% |
| 2025 | $838.8m | +16% |
| 2026Q1 | $228.6m | +16% |
| 2026Q2 | $237.4m | +16% |
| 2026H1 | $466.0m | — |
| 2026E 公司最新指引 | $963.5m-$966.5m | ~15% |

[S1][S2]

增长已经从 20%+ 下行到约 15%-16%，但内部结构发生明显变化：EX 仍在 mid-20s，CX 仅低个位数。

---

## 2. 2025 地区收入

| 地区 | 2025 Revenue | 占比约 |
|---|---:|---:|
| North America | $390.8m | 46.6% |
| EMEA | $324.6m | 38.7% |
| APAC | $100.2m | 11.9% |
| Other | $23.2m | 2.8% |

美国单一市场约 $354.3m，占 42%。[S1]

这意味着 Freshworks 并不是“印度收入型 SaaS 公司”，而是**印度研发成本结构 + 欧美收入结构**。

---

## 3. 大客户上移

2026Q2：[S2]

- >$100k ARR customers：**1,746，+25%**
- >$50k：**4,091，+18%**
- >$5k：**25,356，+6%**
- >$5k 客户贡献总 ARR：**92%**

2026Q1 公司还签下了历史上首个 **>$1m ARR** 的新客户合同。[S10]

这是“Freshworks 能不能摆脱 SMB 工具估值”的最关键验证之一。

---

## 4. NDR：必须拆开看

### 全公司
2026Q2：
- NDR：**104%**
- constant currency：**105%**。[S2][S3]

单看这个数字，不算优秀。

但管理层在 Q2 transcript 中披露：
- EX NDR（剔除 legacy Device42）：**>111% constant currency**
- 多产品 EX 客户此前披露过更高 NDR 水平。

所以公司整体 NDR 被：
1. CX 低增长；
2. legacy Device42 churn；
3. FX
拖低。

**研究上绝不能把“公司 NDR 104%”直接翻译成“Freshservice PMF 较弱”。**

真正应该跟踪的是：
> EX NDR / multi-product EX NDR / CX NDR 三者是否持续分化。

---

## 5. 毛利与费用

2025：[S1]

- Gross margin：85%
- R&D：$163.2m，占收入约 19%
- Sales & Marketing：$394.8m，占约 47%
- G&A：$141.1m，占约 17%
- GAAP Operating Income：$13.2m

S&M 仍然很高，这反映了 Freshworks 上移大客户后，不能完全靠 PLG 自然增长。

Freshworks 10-K 也披露，中型/企业客户典型销售周期约 **130-150 天**，而 SMB 约 **30 天**。[S1]

**这就是 upmarket 的反规模重力：**
客单价变高，但销售更慢、RFP 更复杂、实施和售前成本更大。

---

## 6. FCF

| 年 | FCF |
|---|---:|
| 2023 | $77.8m |
| 2024 | $146.0m |
| 2025 | $220.9m |
| 2026E adjusted FCF 公司目标 | ~$265m |
| 2028E FCF 公司目标 | $425m+ |

[S1][S5]

这条曲线是当前 Freshworks 最好看的财务曲线之一。

---

## 7. 现金与资本结构

2026-06-30：[S3]

- Cash & cash equivalents：$494.7m
- Marketable securities：$169.4m
- 合计约：$664.1m
- 加 restricted cash 后公司 Q2 release 披露约：$665.3m
- 未见传统意义上的高杠杆债务负担

现金安全垫非常厚。

---

## 8. 回购

2026 年 2 月董事会批准 **$400m** 回购。[S3]

截至 2026-06-30：
- 已回购 24.04m 股；
- 花费 $204.5m；
- 平均价 **$8.50**；
- 剩余额度 $195.5m。[S3]

2025 年公司已回购约 26.9m 股、花费约 $384.5m，平均约 $14.29。

这是一个重要正面：
> 管理层不再默认“SaaS 就应该不断扩大 share count”。

但也要反过来理解：
> 如果用大量现金回购只是为了抵消 SBC，它并不等于真正给股东创造了同等金额的价值。

因此应该同时看：
**FCF/share + diluted share count + SBC/revenue**，而不是只看 FCF。

---

# 五、【7.8/10，信心：中高】正向思考：Investment Thesis、价值天花板、Upside Surprise

## 核心 Thesis

我的核心判断是：

> Freshworks 正在完成从“价格便宜、易上手的 SMB SaaS 套件”到“中型和 agile enterprise 的统一 AI Service Operations 平台”的二次创业。如果 Freshservice 能将 ITSM、ITAM、ITOM、ESM 和 Agentic AI 真正统一，Freshworks 的竞争维度就会从“便宜版 ServiceNow / Zendesk”切换到“复杂企业软件的更轻量替代方案”。

这条 thesis 有五个支点：

### ① EX 已经不是故事，而是 >$0.5B ARR 业务
2026Q2 EX ARR ~$567m，仍约 +24% constant currency。[S4]

### ② 上移大客户已经被真实合同验证
>$100k ARR 客户 +25%，Q1 出现首个 $1m+ ARR 新单。[S2][S10]

### ③ Freshservice 的扩张单位在变多
ITSM → ITAM → ITOM → ESM → FireHydrant → Freddy AI。

### ④ AI 不只是免费 feature
Copilot、AI Agent session、资产、MCP actions 等已经出现明确 monetization unit。[S6][S7]

### ⑤ 利润并没有因为 EX 继续投入而崩掉
2025 FCF $220.9m；公司 2026E adjusted FCF ~$265m；2028 目标 $425m+。[S1][S5]

---

## 市场价值天花板

Freshworks 在 2026 Analyst Session 自己估算，ITSM + ITAM + ITOM + ESM 合计 EX TAM 约 **$45B**，预计 2025-2028 CAGR 约 **13.4%**；其中约 60% 来自员工规模不超过约 20,000 人的中型/“agile enterprise”客户。

**注意：这是 Freshworks 的公司估算，底层引用 Gartner 并结合内部分析，并不是我独立验证后的客观市场规模。[S5]**

### 用这个 TAM 做一个“天花板思维实验”，不是预测

如果未来 Freshworks 能拿到 EX TAM 的：
- 5% → ~$2.25B EX ARR；
- 再加成熟 CX ~$0.4-0.6B；
- 总收入规模可能接近 ~$2.7-3.0B。

若成熟期 FCF margin 30%-35%，就是约 $0.8-1.0B FCF。

如果一个成熟、仍有中个位数至低双位数增长的软件平台可以获得 18-22x FCF，则潜在 EV 大致在：

> **$15B-$22B**

这不是目标价，只是说明：  
**Freshworks 的理论商业天花板仍明显高于当前 2026 年约 $1B 收入级别。**

如果最终能取得约 10% EX TAM，天花板还会更高，但我不会把这种情况纳入 base case。

---

## Upside Surprises

最可能让市场低估它的不是“总收入突然 30% 增长”，而是以下几个结构性 surprise：

1. **EX 增速在 20%+ 维持得比预期更久**；
2. Freshservice 2028 年真正达到 ~$1B ARR；
3. ESM 从 $50m 继续成长为 $150m-$300m 独立业务；
4. ITAM / ITOM 使大客户 ACV 快速抬升；
5. Agentic AI 的 usage revenue 增长速度超过 seat compression；
6. AI 客户的 NDR 显著高于非 AI 客户，使 EX NDR 走向 115%-120%；
7. CX 在低增长状态下做到 30%+ operating margin；
8. buyback 让 FCF/share 增速持续显著快于公司 FCF；
9. Freshworks 的“部署快、TCO 低”在 ServiceNow 等大型套件日益复杂时成为更强竞争武器。

---

# 六、1.【8.6/10，信心：高】PMF 验证程度

## 正向证据

### 1. 绝对规模已经跨过“产品是否有人要”的阶段
Freshworks 接近 75,000 家客户，Freshservice 约 20,000 客户。[S1][S5]

### 2. 真正重要的 EX 仍在 20%+ 增长
2026Q2 EX ARR ~$567m，cc +24%。[S4]

### 3. 大客户数量继续快于总客户增长
>$100k ARR customers +25%，而 >$5k customers +6%。[S2]

这说明增长不是靠“多注册几个小客户”，而是在拉高单客价值。

### 4. Cross-sell 已经发生
- ESM >$50m ARR；
- 大型 EX 新 landing 中约 1/3 带 ITAM；
- 非 IT 新 seat 约占新 EX seat 的 1/5。[S4]

### 5. AI 有付费行为
Q2 管理层披露已有 7,000+ 客户购买 AI SKU，较大新单 Copilot attach 超过 70%。[S4]

---

## 为什么不是 10 分？

### ① 公司整体 NDR 只有 104%
说明整个 portfolio 的自然扩张能力还没有达到一线高质量 SaaS 的极高水平。[S2]

### ② CX 已经进入 low-single-digit growth
说明 Freshworks 并不是每条产品线都有强 PMF 增长。

### ③ AI usage monetization 仍处在早期
“Copilot 高 attach”不等于长期 AI ARPU 已验证。

### ④ upmarket PMF 还需要更多时间
首个 $1m ARR deal 只是证明“能签”，不是证明“大量可复制”。

### 结论
**Freshservice / EX 的 PMF：9/10 左右。  
Freshworks 整体 portfolio PMF：8.6/10。**

---

# 七、2.【6.8/10，信心：中】长期壁垒、规模优势曲线

Freshworks 有壁垒，但不是一个天然 winner-takes-all 生意。

## 壁垒 1：Switching Cost

迁移 ITSM 不只是导出工单。

要迁：
- 数据；
- knowledge base；
- SLA；
- workflow；
- approval；
- integrations；
- CMDB；
- 设备数据；
- 权限；
- audit；
- AI context。

客户规模越大，替换越麻烦。

---

## 壁垒 2：Unified Context

AI Agent 的效果取决于上下文。

如果 Freshservice 同时拥有：
- ticket；
- employee；
- asset；
- dependency；
- incident；
- knowledge；
- workflow；

AI 就比一个外部通用 LLM 更容易“知道该做什么”。

这就是 Freshworks 2026 把 ITSM + ITAM + ITOM 统一的战略意义。[S11]

---

## 壁垒 3：生态和集成

2025 10-K 披露 Freshworks Marketplace 有 **1,200+ plug-and-play apps**。[S1]

不是 Salesforce / ServiceNow 级生态，但已经形成一定扩展成本。

---

## 壁垒 4：成本结构

截至 2025 年底约 4,500 名员工，其中公司大量研发和员工位于印度。[S1][S14]

Freshworks 长期的结构性优势是：
> 在美国/欧洲卖企业软件，但大量研发成本处于印度成本曲线。

如果能保持世界级产品质量，这是一种非常现实的成本壁垒。

---

## 为什么只能给 6.8？

### 1. 没有网络效应
A 公司使用 Freshservice，并不会自动让 B 公司使用它。

### 2. 专利不是核心护城河
Freshworks 在 10-K 里也明确承认，很多软件能力可能被竞争对手独立开发或模仿。

### 3. “简单好用”可以被学习
UX 是优势，但不是不可复制的技术垄断。

### 4. AI 可能降低软件差异化
如果未来通用 Agent 能跨多个 system of record 工作，应用层 UI 的价值可能下降。

### 5. 强敌资金远多于它
ServiceNow、Salesforce、Microsoft、Atlassian 等都有更大研发/渠道能力。

**所以 Freshworks 的 moat 更像“高切换成本 + 统一数据 + 产品速度 + 成本结构”的组合，而不是单一不可逾越护城河。**

---

# 八、3.【8.1/10，信心：高】Scalability、反规模重力、技术周期、资本效率

## 正向：软件天然高度可扩展

2025：
- 85% GAAP gross margin；
- 99% 左右收入来自 subscription/license/maintenance；
- 专业服务 <2%；
- FCF 从 2023 $77.8m → 2024 $146.0m → 2025 $220.9m。[S1]

这是典型的优秀 SaaS scale curve。

---

## 更重要：增长正在变得“更资本有效”

2025 收入 +16%，但总 operating expenses 同比 **下降 6%**；GAAP operating income 从 2024 -$138.6m 改善到 2025 +$13.2m。[S1]

2026Q2：
- revenue +16%；
- non-GAAP operating margin 23.6%；
- adjusted FCF margin 24.3%；
- GAAP net income 转正。[S2]

公司 2028 模型目标：
- revenue $1.3B+；
- FCF $425m+；
- FCF margin 32%-34%；
- non-GAAP operating margin 24%-26%；
- Rule of ~50。[S5]

如果兑现，经营杠杆非常强。

---

## 反规模重力 1：Upmarket 会让销售成本重新上升

10-K：Mid-market / enterprise sales cycle 约 130-150 天，SMB 约 30 天。[S1]

大客户会：
- RFP；
- 安全审计；
- 法务谈判；
- custom integrations；
- implementation；
- discount negotiation。

所以不能简单假设“ACV 越高，利润一定越高”。

---

## 反规模重力 2：产品组合可能再次变复杂

Freshworks 的卖点是 uncomplicated。

但它正在同时扩：
- ITSM；
- ITAM；
- ITOM；
- ESM；
- AI；
- FireHydrant；
- DEX；
- MSP；
- CX。

如果产品变成另一套“大而全 enterprise stack”，它可能亲手破坏自己的核心差异化。

---

## 技术周期风险：AI Seat Deflation

这是我认为最值得跟踪的技术风险。

如果 Copilot / AI Agent 让一个团队从 100 个 agent 变成 60 个 agent：
- seat revenue 下降 40%；
- 只有当 AI session / workflow / asset monetization 补回来，公司才能成为净受益者。

Freshworks 已经在往 usage / asset pricing 迁移，这是对的，但仍需要未来 2-3 年证明。

---

# 九、4.【6.9/10，信心：中】竞争格局、优势劣势与长期胜率

Freshworks 2025 10-K 明确列出的竞争者：[S1]

## EX / ITSM
- ServiceNow
- BMC
- Ivanti
- Atlassian
- 其他中型 ITSM / 新兴平台

## CX
- Salesforce
- Zendesk
- Intercom
- Oracle
- SAP
- HubSpot
- Microsoft Dynamics
- Sage 等

---

## Freshworks 的核心竞争武器

### 1. 更快部署
公司将“weeks, not quarters”作为核心定位，并在 Analyst Session 中强调大多数部署可在较短周期上线。[S5][S11]

### 2. 更透明、更低 TCO
价格公开、14 天 trial、自助产品体验，减少传统 enterprise software 重咨询、重实施。

### 3. 对 mid-market / agile enterprise 更合适
Freshworks 没有必要在最复杂的全球 Fortune 100 场景硬碰 ServiceNow。

更合理 ICP 是：
> “已经复杂到需要 enterprise-grade，但不愿意付出巨型 enterprise suite 的复杂度和成本”的公司。

### 4. EX 的 unified platform 越来越完整
Device42 + FireHydrant 补齐了最明显的 ITAM / incident gaps。

### 5. India engineering economics
产品价格更低时仍有机会维持很高 gross margin。

---

## Freshworks 的弱点

### 1. Enterprise feature depth 历史上落后成熟巨头
这是向大客户进攻必须持续补齐的部分。

### 2. Partner / SI ecosystem 规模不及最大竞争者
复杂大型项目里，生态本身就是销售武器。

### 3. CX 差异化变弱
Freshdesk 面对 Zendesk、Intercom、Salesforce，以及 AI-native support entrants，增长已明显放慢。

### 4. AI 容易被平台型对手捆绑
Microsoft / Salesforce / ServiceNow 都可以把 AI 作为大合同 bundle 的一部分。

### 5. “40% win rate”等竞争数据来自公司自己的披露
不能当作独立第三方验证。

---

## 长期胜率怎样看？

我不会把“胜率”理解成“打败 ServiceNow 成为第一”。

Freshworks 更现实的胜利条件是：

> 在 mid-market + agile enterprise 服务管理市场成为长期独立的 Top-tier 平台，同时维持 15%-20% 级增长和 25%-35% FCF margin。

按当前证据，我对这个结果的主观概率估计约 **60%-65%**。

这不是公司数据，是我的 underwriting judgment。

---

# 十、5.【7.4/10，信心：中高】长期外部生存环境

## 正向

### 1. 服务管理不是可选消费
企业 IT、HR、客户服务必须存在。

### 2. AI 反而让系统级上下文更重要
Agent 要安全地执行动作，需要权限、审计、CMDB、workflow、knowledge 和 system-of-record。

### 3. 市场仍碎片化
Freshworks 自估的 EX 市场并没有单一厂商拿到压倒性份额。[S5]

### 4. 融资风险低
截至 Q2 有约 $665m cash/securities，且持续产生 FCF。[S2][S3]

Freshworks 已经是上市公司，因此传统 VC/IPO “退出环境”不是核心变量。

---

## 外部风险

### 1. 隐私、AI、安全和跨境数据规则
Freshworks 在全球约 170 个国家服务客户，监管复杂度只会提高。[S1]

### 2. AWS 集中
Freshworks 10-K 明确称 AWS 提供其绝大部分 cloud infrastructure；切换供应商需要显著时间和费用。[S1]

这是一个真实的基础设施 concentration risk。

### 3. 印度人才/汇率集中
印度成本结构是优势，也形成地域和 FX 集中。

### 4. 企业 IT 预算周期
upmarket 后更容易受到 CFO 审批、宏观预算、采购周期影响。

---

# 十一、6.【8.0/10，信心：中】创始人学习、思考与决策能力

这里必须先更新一个事实：

**Founder Girish Mathrubootham 已经不是 Freshworks 的现任经营者。**

- 2024-05-01：Girish 从 CEO 转为 Executive Chairman，Dennis Woodside 接任 CEO。[S13]
- 2025-12-01：Girish 正式退休退出 Executive Chairman 和 Board，以全职投入 Together Fund；公司 SEC 文件称离任并非源于对公司运营、政策或实践的分歧。[S14]

因此，今天买 Freshworks，实际是在押：

> Dennis Woodside + 当前 Board + 新经营团队

而不是继续押创始人日常运营。

---

## 对 Girish 的历史判断

### 正面 1：有“更新观点”的明确一手案例

Girish 2016 年官方文章坦言，他两年前曾认为：
> CRM 已经是 solved problem，没有新进入者空间。

但 Freshworks 自己在使用多个 CRM/营销/销售工具时遭遇高成本、集成复杂、数据割裂，于是他反转判断并推出 Freshsales。[S15]

这是很有价值的 founder signal：

> 不是为了维护过去观点，而是根据一线使用事实更新 belief。

---

### 正面 2：CEO 继任不是被动救火

Girish 在 2024 官方信中说：
- 数年前已与董事会讨论长期安排；
- 希望把精力放在长期产品、AI 和印度；
- 招聘 Dennis 时就希望其最终接班；
- 两人合作超过 18 个月后完成交接。[S13]

这体现：
- 对自己优势边界有一定认识；
- 使用董事会做 sounding board；
- succession planning 有提前量。

---

## 不能证明的部分

用户要求判断：
> 是否存在阻碍正常决策的性格缺陷？

仅靠官方一手材料，**没有足够证据做人格诊断**。

因此此项我不推断。

这也是为什么我不会给创始人 9-10 分。

---

# 十二、7.【7.6/10，信心：中】组织建设能力、核心团队、动力系统

今天更值得研究 Dennis Woodside。

## Dennis 的履历与接班

Freshworks 官方披露：
- 2022 年加入 Freshworks；
- 此前任 Dropbox COO；
- 更早有 Google、Motorola 等管理经历；
- 也曾任 ServiceNow Board 成员。[S13]

这不是 founder-style CEO，而是典型 scale operator。

---

## 当前组织动作非常清晰：减少矩阵、把责任合并

### 1. Sales 统一
2026-03，公司把 global sales organization 统一到 Ian Tickle，晋升其为 CRO。[S16]

### 2. Product + Technology 统一
2026-07，Ryan Manning 出任 Chief Product and Technology Officer，把 product 和 technology strategy 统一到一个 leader；CTO Murali Swaminathan 向其汇报。[S17]

### 3. 2026 restructuring
公司 2026-05 启动重组，目标明确写为：
- streamline organizational efforts；
- streamline product development；
- increase leverage of AI and automation。[S3]

### 4. CX GTM 更集中
CX 业务向更低成本、更多 inbound 的模式迁移。

这些动作与 Dennis 对“simplicity / speed”的管理理念一致。[S18]

---

## 激励机制

2025 高管 cash bonus：
- 70% 权重：Net New ARR；
- 30%：non-GAAP operating margin。[S19]

长期 PRSU：
- 70% revenue；
- 30% FCF；
- 2025 实际 payout 105.4% target。[S19]

2026 年，公司又把高管年度 equity 中 performance-based PRSU 占比从 30% 提高到 **40%**。[S19]

这说明董事会正在把高管报酬更强地绑定：
> 增长 + 盈利/现金流

这是正面。

---

## 一个需要警惕的治理细节

2025 Q4 原 non-GAAP operating margin bonus target 是 19.2%。

由于公司前三季度花费低于计划，并希望把节省额重新投入 EX，Compensation Committee 把 Q4 target 一次性改到 15.3%，而其他目标没有改变。[S19]

两种解释都合理：

### 正面解释
董事会不希望短期 bonus target 阻止高 ROI 再投资。

### 负面解释
事后改 KPI 会弱化激励制度可信度。

我目前把它视为**黄色信号，而不是红旗**。

---

## 组织风险

2024-2026 有：
- restructuring；
- founder 完全退出；
- 销售整合；
- 产品高管更替；
- product/tech 再统一。

这可能是效率提升，也可能说明组织仍在持续重构。

因此，组织能力我给 7.6，不给 9。

---

# 十三、8.【8.3/10，信心：高】Bottom Line Protection

这里的 bottom line protection，我理解为：

> 如果增长不及预期，股东有多厚的“生存底”和现金流底？

Freshworks 在这项上很强。

## 保护 1：高毛利
85% GAAP gross margin。[S1]

## 保护 2：经常性收入
2025 约 $829.4m / $838.8m 收入来自订阅、license、maintenance。[S1]

## 保护 3：预收模式
订阅通常按月、年或多年合同，并通常提前开票。[S1]

## 保护 4：客户集中度低
2023-2025 没有单一客户超过收入 10%。[S1]

## 保护 5：现金多
2026Q2 cash + marketable securities 约 $664m。[S3]

## 保护 6：已经有真实 FCF
2025 FCF $220.9m，不再是“等未来盈利”的 SaaS。[S1]

## 保护 7：费用可调
CX GTM、headcount、G&A 已经证明可压缩。

---

## 但 Bottom Line 不是无风险

### SBC
2026H1 $81.8m，未确认 SBC $352.6m。[S3]

### M&A
Device42 $238.1m + FireHydrant $88.7m，说明 EX 补能力需要资本，而且 FireHydrant 初步 goodwill $51.3m。[S1][S3]

### AWS
基础设施集中。[S1]

### Buyback
回购只有在价格低于内在价值时创造价值；如果只是“用 cash 抵消 SBC”，经济意义会缩水。

---

# 十四、9. 概率与赔率计算

## 先说限制

我没有用 Yahoo、Google Finance、TradingView 等第三方实时行情，因为你要求**一手官方数据**。

本次搜索时：
- Freshworks IR / Nasdaq 官方行情页面可访问；
- 但检索接口没有返回 2026-09-16 可验证的实时 quote。

所以我不会伪造“当前股价”。

我提供两个东西：

1. **2028 情景内在价值模型**
2. **你可以直接对照当前股价的赔率阈值**

---

## 情景模型

以下全部是**我的假设**，只有公司 2028 target 那一行借用了管理层目标做锚。

| 情景 | 主观概率 | 2028 FCF | 2028 diluted shares | FCF/share | 终值倍数 | 2028 价值/股 |
|---|---:|---:|---:|---:|---:|---:|
| Thesis break / 明显失速 | 25% | $200m | 300m | $0.67 | 10x | **$6.67** |
| 部分成功 | 35% | $330m | 300m | $1.10 | 14x | **$15.40** |
| 接近公司 2028 目标 | 30% | $425m | 295m | $1.44 | 18x | **$25.93** |
| Upside surprise | 10% | $520m | 285m | $1.82 | 22x | **$40.14** |

概率加权 2028 value：

> **约 $18.85 / share**

这里不是 price target，而是：
> 在一套明确概率和终值倍数假设下的 underwriting expected value。

---

## 折现回 2026-09-16

从 2026-09-16 到 2028-12-31 约 2.29 年。

以不同 required return 折现：

| 要求年化回报 | 概率加权现值 |
|---:|---:|
| 10% | **~$15.15** |
| 12% | **~$14.54** |
| 15% | **~$13.68** |

因此我认为，研究上最实用的不是“目标价 $X”，而是：

### 赔率区间
- **显著低于 ~$13.5**：我的模型开始出现明显 margin of safety；
- **~$13.5-$15**：接近合理 underwriting 区间，需更依赖 EX 持续兑现；
- **明显高于 ~$15**：仍可能赚钱，但更多依赖 company-plan / bull case，赔率变差；
- **~$20+**：需要给 Freshworks 更高的 2028 达标概率或更高终值倍数才能合理化。

这些阈值会随着 Q3/Q4 EX ARR、NDR、AI monetization 和 share count 更新。

---

## 一个有用的历史参考，而不是当前价

Freshworks 2026-05-14 Analyst Session 使用 **2026-05-12 股价 $8.50** 作为官方 valuation slide 的参考。[S5]

另外，截至 2026H1 公司自己实际回购 24.0m 股的平均价格也恰好约 **$8.50**。[S3]

如果当时以 $8.50 为成本，对我的概率加权 2028 value $18.85：
- 终值倍数约 2.22x；
- 从 2026-05-12 到 2028 年末的隐含年化约 **35%**。

**但这只是历史赔率复盘，绝不代表 2026-09-16 仍有同样赔率。**

---

# 十五、【总体 7.8/10，信心：中高】投资判断

## 我认为 Freshworks 最值得研究的地方

它不是“AI 概念 SaaS”。

它已经有：
- ~$1B revenue run-rate；
- ~$0.57B EX ARR；
- 20k 左右 Freshservice 客户；
- 85% gross margin；
- $200m+ annual FCF；
- ~$665m cash/securities；
- 大客户持续上移；
- AI 已经开始付费；
- ITAM / ITOM / ESM 形成扩张矩阵。

同时，估值历史上曾经被压到一个成熟低增长 SaaS 的水平，而 EX 业务本身仍接近 mid-20s 增长。

这就是潜在错价来源：

> **市场看的是 Freshworks consolidated ~15% growth；真正的增长资产是 EX ~24%，而 CX 正在被经营成利润业务。**

如果 EX 占比从约 59%-60% 继续走向 70%，公司的 consolidated growth / NDR / margin profile 有机会自然改善。

---

## 为什么我仍然不给 9 分？

最重要的四个未解问题：

### 1. AI 到底是 ARPA expansion，还是 seat destruction？
这是第一大变量。

### 2. Upmarket 后，“简单、快速、便宜”的差异化会不会被自己破坏？
企业客户越大，功能和实施越复杂。

### 3. EX NDR 能否从 ~111% 进一步提高？
如果长期只有 108%-112%，说明 expansion ceiling 没有想象中强。

### 4. SBC + buyback 的真实 owner economics
2026 share count 确实在下降，是好事；但要持续观察“回购金额 - SBC”的净经济效果。

---

# 十六、未来每个季度我只需要盯这 12 个指标

这是我认为研究 Freshworks 最有效的一张表。

| 指标 | 好信号 | Thesis 变差信号 |
|---|---|---|
| EX ARR growth | ≥20%-25% | <18% |
| EX ARR absolute | 2026E >$600m，持续向 $1B 走 | 路径明显延后 |
| EX NDR | >111%，向 115%+ | <108% |
| Multi-product EX NDR | 维持显著高于单产品 | 收敛到公司平均 |
| CX ARR growth | 低个位数稳定 | 明显转负 |
| CX margin | 向 30%+ | 为保收入重新加大费用 |
| >$100k ARR customer growth | >20% | <10%-15% |
| ESM ARR | >50m 后继续高速 | 快速降到 <30% 增长 |
| ITAM attach | 大型新单 ~1/3 或更高 | 下降 |
| AI paid penetration | >22% eligible EX 继续升 | 停滞 |
| Overall NDR | 从 104%-105% 回升 | 跌破 100% |
| FCF/share | ≥20% CAGR 路径 | FCF 增但 share/SBC 抵消 |

---

# 十七、最关键的反方论证：什么情况下这笔投资逻辑彻底错？

## Bear Case 1：Freshservice 最终只是“便宜版 ServiceNow”
如果它始终只能靠低价赢，而无法在数据深度、AI、ITAM/ITOM/ESM 建立差异化：
- upmarket 会遇到 feature ceiling；
- pricing power 弱；
- 长期 margin / multiple 都受限。

## Bear Case 2：Agentic AI 绕过传统 ITSM UI
如果员工直接与通用 AI 入口交互，而底层系统变成 interchangeable database：
Freshworks 的 application layer 价值可能被压缩。

## Bear Case 3：Seat compression 快于 usage monetization
AI 自动处理 50% ticket，但 AI 收费不足以替代消失的 agent seat。

## Bear Case 4：大客户化摧毁 PLG economics
sales cycle 拉长、implementation 变重、S&M 永远下不来。

## Bear Case 5：并购让产品重新碎片化
Device42、FireHydrant 如果不能真正原生融合，只是形成多个 SKU，Freshworks 的“uncomplicated”品牌会被削弱。

---

# 十八、最终 Bottom Line

如果只看 2026 年 consolidated revenue growth ~15%，Freshworks 很容易被看成一个进入成熟期的二线 SaaS。

但把公司拆开后，真实结构是：

> **一个 ~$567m ARR、仍在 mid-20s 增长的 EX 核心资产**  
> +  
> **一个 ~$400m ARR、低增长但可被经营成高利润的 CX 资产**  
> +  
> **一个刚开始 monetization 的 AI layer**  
> +  
> **高毛利、净现金、快速提升的 FCF**

因此，我给它：

- PMF：**8.6/10**
- 壁垒：**6.8/10**
- Scalability：**8.1/10**
- 竞争位置：**6.9/10**
- 外部环境：**7.4/10**
- Founder historical decision quality：**8.0/10**
- Organization：**7.6/10**
- Bottom-line protection：**8.3/10**
- **综合业务/投资 Underwriting：7.8/10**

真正决定它能不能从“好公司”变成“非常好的股票”的，不是 2026Q3 多赚几百万美元，而是：

> **到 2028 年，Freshservice 是否真的接近 $1B ARR，同时 AI 把 NDR 和 ARPA 往上推，而不是把 seat revenue 吃掉。**

这是 Freshworks 当前最关键的一条验证链。

---

# 十九、一手官方资料索引

**[S1] Freshworks FY2025 Form 10-K — SEC**  
https://www.sec.gov/Archives/edgar/data/1544522/000154452226000036/frsh-20251231.htm

**[S2] Freshworks Q2 2026 Results — Official IR**  
https://ir.freshworks.com/news/news-details/2026/Freshworks-Reports-Record-Second-Quarter-2026-Results/default.aspx

**[S3] Freshworks Q2 2026 Form 10-Q — SEC**  
https://www.sec.gov/Archives/edgar/data/1544522/000154452226000137/frsh-20260630.htm

**[S4] Freshworks Q2 2026 Earnings Call Transcript — Freshworks IR-hosted PDF**  
https://s21.q4cdn.com/987526491/files/doc_financials/2026/q2/Freshworks_Q2_2026_Earnings_Call_Transcript.pdf

**[S5] Refresh 2026 Financial Analyst Session, Exhibit 99.1 — SEC**  
https://www.sec.gov/Archives/edgar/data/1544522/000119312526224188/d14719dex991.htm

**[S6] Freshservice Pricing — Official Product Page**  
https://www.freshworks.com/freshservice/pricing/

**[S7] Freshdesk / Freshdesk Omni Pricing — Official Product Pages**  
https://www.freshworks.com/freshdesk/pricing/  
https://www.freshworks.com/freshdesk/omni/pricing/

**[S8] Freshservice ITAM / Business Teams Pricing — Official Product Pages**  
https://www.freshworks.com/freshservice/itam/pricing/  
https://www.freshworks.com/freshservice/business-teams/pricing/

**[S9] Freshworks 2026 Proxy Statement — SEC**  
https://www.sec.gov/Archives/edgar/data/1544522/000154452226000075/frsh-20260409.htm

**[S10] Freshworks Q1 2026 Results — SEC / Official release**  
https://www.sec.gov/Archives/edgar/data/1544522/000154452226000088/q126quarterlyearningsrelea.htm

**[S11] Freshworks May 2026 Product Launch / AI Service Operations — Official**  
https://www.freshworks.com/theworks/company-news/may-2026-launch/

**[S12] Freshworks September 2026 Product Update — Official**  
https://www.freshworks.com/theworks/company-news/september-2026-freshworks-innovation-update/

**[S13] CEO Transition / Founder Message — Official**  
https://ir.freshworks.com/news/news-details/2024/Freshworks-Announces-CEO-Transition-05-01-2024/default.aspx  
https://www.freshworks.com/theworks/company-news/a-message-from-our-founder/

**[S14] Girish Mathrubootham retirement — SEC 8-K**  
https://www.sec.gov/Archives/edgar/data/1544522/000154452225000078/frsh-20250903.htm

**[S15] Founder: Why We Built Freshsales — Official Freshworks**  
https://www.freshworks.com/theworks/company-news/why-we-built-freshsales/

**[S16] Global Sales Unification / Ian Tickle CRO — Official IR**  
https://ir.freshworks.com/news/news-details/2026/Freshworks-Unifies-Global-Sales-Organization-to-Accelerate-Growth/default.aspx

**[S17] Ryan Manning appointed Chief Product & Technology Officer — Official IR**  
https://ir.freshworks.com/news/news-details/2026/Freshworks-Appoints-Ryan-Manning-as-Chief-Product-and-Technology-Officer/default.aspx

**[S18] Dennis Woodside: One Year Reflections — Official Freshworks**  
https://www.freshworks.com/theworks/company-news/dennis-woodside-one-year-reflections/

**[S19] Executive compensation / incentive design — 2026 Proxy, SEC**  
https://www.sec.gov/Archives/edgar/data/1544522/000154452226000075/frsh-20260409.htm

---

## 免责声明
本文用于研究与信息整理，不构成个性化投资建议。所有情景概率、估值倍数和内在价值区间均为研究假设，应随最新季度数据和可验证市场价格更新。
