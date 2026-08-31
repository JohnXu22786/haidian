---
title: "元胞智城：京张AI原生新型城市形态（概念）"
author_github: "JohnXu22786"
language: "zh"
proposal_format_version: "2"
bilingual_contract_version: "1"
translation_file: "proposal.en.md"
license: "COMMUNITY-DISPLAY-ONLY"
summary: "以元胞街坊、虚实融合平台、可逆生长庭构成CELL·JZ的三节点原生形态，严格映射任务书三区两翼；十张独立AI场景卡共用三套测试协议，所有阈值均为参与方提议、待专业论证的 provisional 门槛。"
tracks: ["ai-traffic-walkability", "enterprise-services-ecosystem", "civic-agent-governance"]
scenarios: ["ai-traffic-walkability", "enterprise-service-copilot", "public-safety-operations-review"]
iteration: "v3.0-review-3879"
---

# 元胞智城：京张AI原生新型城市形态（概念）

## 设计依据与资料清单

本方案保留“元胞街坊—虚实融合平台—可逆生长庭”的核心创意，以 **CELL·JZ** 作为方案系统名。它不是法定规划、建设承诺、官方背书或已验证的运行结果；所有空间边界、面积、场景阈值和运营主体均按 `provisional`、`participant-proposed` 或 `待核验` 标记。[source:DATA-SRC-OFFICIAL-ANNOUNCEMENT-20260509] [source:DATA-SRC-AGENT-TASKBOOK-20260518]

![三区两翼与 N1-N3 的空间索引关系示意](assets/figures/site-overview.png)
![N1 元胞坊、N2 智纹台、N3 生长庭的差异化平面与剖面](assets/figures/key-areas.png)
![27 个用地要素与绿色空间复算](assets/figures/land-use-structure.png)
![道路、铁路、车站、慢行与蓝绿关系示意](assets/figures/mobility-bluegreen.png)
![十张场景卡、三套协议与证据边界](assets/figures/metrics-evidence.png)

图件均为作者绘制的概念示意；图中的道路、铁路、车站、节点和边界均保留 provisional 标识，不替代官方 GIS、规划红线或工程图纸。

## 三层范围工作框架

项目的任务书地理框架只使用下表五个名称。CELL·JZ 是本方案概念系统名，不替代任务书名称；三节点是设计载体，不把原创节点名当成行政片区名。

| 任务书结构 | 正式中文名称 | English label | 本方案职责 |
| :--- | :--- | :--- | :--- |
| 区域一 | AI原点社区 | AI Origin Community | 生活实验、公共参与、低门槛AI服务 |
| 区域二 | 众智园AI自主创新加速区 | Zhongzhiyuan AI Autonomous Innovation Acceleration Area | 创新孵化、混合研发与试制 |
| 区域三 | 大钟寺AI产业集聚区 | Dazhongsi AI Industry Cluster | 产业转译、展示、商务与消费接口 |
| 翼一 | 中关村科技服务翼 | Zhongguancun Technology Service Wing | 科技服务、研发孵化、成果转化接口 |
| 翼二 | 小月河场景赋能翼 | Xiaoyuehe Scenario Empowerment Wing | 生活场景、绿色公共空间与体验反馈 |

三层范围沿用任务书口径：统筹研究范围约 43.6 km²，整体设计范围约 11.4 km²，本包 provisional polygon 复算为 11,412,825.386 m²，重点区域约 368.4 ha。道路、铁路、车站和地名仅作关系性定位，不构成红线、权属或已批准交通组织。[metric:site_area_sqm] [data:PACKAGE-GEOMETRY]

## 统筹研究范围产业与未来城市研究

统筹层把百年京张文化带、都市 AI 生活体验带和 AI 融合创新带作为研究命题，关注创新要素、人才服务、文化叙事和公共利益之间的关系；区域合作、产业主体、投资、政策和指标均只作待核验的概念机制，不写成已建立承诺。[source:DATA-SRC-AGENT-TASKBOOK-20260518]

这一层的设计意图是把任务书的三大定位和五大功能转成可讨论的要素流动框架：以中关村科技服务翼组织研发、孵化、成果转译，以小月河场景赋能翼承接居民体验、公共空间和反馈，再把 AI 原点社区、众智园 AI 自主创新加速区、大钟寺 AI 产业集聚区作为不同服务情境而非三个孤立项目。当前 geometry 只提供约 11.4 km² 的 provisional site polygon，不能反推 43.6 km² 统筹研究范围的法定边界；metrics 中的 27 个 land-use 要素、site_area_sqm、green_ratio 和 public_space_ratio 只服务于包内复算，不代表产业规模或公共投入。任务书的正式空间坐标、区域协同主体、产业链数据、人才需求和资金政策尚未提供，故本层输出是研究假设和接口清单，后续须由规划、产业、社区和公共服务主体补充来源、日期、空间范围和权限后再升级。[source:DATA-SRC-OFFICIAL-ANNOUNCEMENT-20260509] [data:PACKAGE-GEOMETRY] [metric:site_area_sqm]

## 总体设计范围城市更新与控规深度城市设计

总体层将 11.4 km² provisional design scope 转译为“任务区—翼接口—节点载体—运营责任”的可复核结构；本包不作容积率、建筑高度、道路红线、拆改留或工程实施结论，待正式控制资料到位后整体复算。[data:PACKAGE-GEOMETRY] [metric:site_area_sqm]

总体设计的目的不是给出未经审批的形态定案，而是把三层范围、三区两翼、三节点、六项 agent 任务和十张场景卡放进同一个可追踪的工作面：空间关系由 GeoJSON 承载，指标由 metrics.json 承载，场景、协议、责任人和退出条件由正文与 risk.json 承载。站点、道路、铁路和车站在本包只表示关系性方向；它们不会自动产生建筑密度、道路断面、轨道保护、消防、市政容量或权属结论。现有 site union 面积 11,412,825.386 m² 是按 provisional polygon 的计算结果，27.3034% 是 land_use 公园绿地分类口径，11.0044% 是另行统计的生态 overlay，二者不可合并。官方 GIS/CAD、控规、道路红线、绿线蓝线、轨道保护、文保、消防、管网、产权和运营许可均为数据缺口，因此中期和远期动作只能写成“待审查后再进入下一门槛”的条件流程。[data:PACKAGE-GEOMETRY] [metric:land_use_green_ratio] [metric:green_ratio]

## 重点区域详细设计

### “三区两翼—三节点—agent.1-agent.6”对照表

下表是全包唯一的结构对照；正文、GeoJSON、图件、HTML 和矩阵均引用相同的节点 ID 与任务区名称。

| 节点 ID / 原创节点 | 主任务区 | 翼接口 | 空间—场景—运营职责 | 主要 agent |
| :--- | :--- | :--- | :--- | :--- |
| N1 元胞坊 / Cellular Block | 众智园AI自主创新加速区 | 中关村科技服务翼 | 混合研发、孵化、社区服务咬合；由创新园区运营与社区服务方共同复核，主体待核验 | agent.1, agent.2, agent.3 |
| N2 智纹台 / Smart-Pattern Terrace | AI原点社区 | 小月河场景赋能翼 | 面向居民、学生和访客的公共平台；轻量数字层只做匿名聚合提示，人工服务台兜底 | agent.1, agent.3, agent.4, agent.5 |
| N3 生长庭 / Growing Court | 大钟寺AI产业集聚区 | 中关村科技服务翼 ↔ 小月河场景赋能翼 | 以存量基座承载可拆卸展示、商务与消费模块；产业方、场地管理方和公众代表分级复核 | agent.1, agent.2, agent.4, agent.6 |

三个节点均为概念点位。`geometry/key_areas.geojson` 的三个 feature 使用 `N1`、`N2`、`N3` 及 `task_area_zh`、`wing_interface_zh`、`agent_refs` 属性；其空间边界是 provisional，不能替代官方 GIS/CAD。[data:PACKAGE-GEOMETRY]

### 核心形态：三种不同的空间原型

### N1 元胞坊：混合功能咬合

元胞坊不是单一“园区盒子”，而是居住支持、研发工位、孵化会谈、共享设备和一层社区服务在同一街坊内以小尺度单元咬合。白天服务研发和试制，晚间保留社区使用；算力、能源和数据接口只表达需求方向，不预设工程容量。可逆组件优先挂接在现有界面，失败时退回人工预约和纸面导视。

### N2 智纹台：公共空间与轻量数字层

智纹台以连续座椅、遮荫、无障碍停留面和可读的纸质导视构成公共底盘，在其上叠加可关闭的预约提示、环境提示和匿名人流聚合显示。数字层不识别人、不留个体轨迹；任何数字功能关闭后，空间仍可由人工服务台、公告板和现场引导独立运行。

### N3 生长庭：存量基座与可逆模块

生长庭首先保留可识别的存量建筑/场地基座，再以螺栓连接、可拆卸遮棚、可移动展台和轻量服务柜逐期接入。模块可迁移、缩减或拆除，不把概念形态写成拆改或工程结论；产业展示、商务会谈和日常消费三类使用按时段切换。

三种平面/剖面差异见 `assets/figures/key-areas.png` 与 `assets/figures/key-areas.en.png`：N1 显示混合咬合，N2 显示公共底盘加数字层，N3 显示存量基座加可逆模块，而非同一模板换标题。

## AI 创新生态、人才画像与 AI+ 场景

本包将计数拆开：**独立场景卡固定为 10 张，通用测试协议固定为 3 套，场景—协议关联数为 18 条**。`design_node_count=3` 只表示三个原创空间节点；`scenario_node_count=8` 仅表示 GeoJSON 中的 3 个地标与 5 个关系性场景位置，二者都不等同于场景卡。[metric:scenario_card_count] [metric:common_test_protocol_count] [metric:mapping_count]

| 卡片 | 节点 / 任务区 | 独立场景与空间类型 | 适用协议 |
| :--- | :--- | :--- | :--- |
| S01 | N1 / 众智园AI自主创新加速区 | 共享试制桌；混合研发街坊 | TP-01, TP-03 |
| S02 | N1 / 众智园AI自主创新加速区 | 孵化会谈舱；可变共享室 | TP-01 |
| S03 | N1 / 中关村科技服务翼 | 科技服务匹配台；一层公共界面 | TP-02, TP-03 |
| S04 | N2 / AI原点社区 | 无障碍步行提示；公共路径 | TP-02 |
| S05 | N2 / AI原点社区 | 社区议事/活动编排；开放平台 | TP-01, TP-02 |
| S06 | N2 / 小月河场景赋能翼 | 环境舒适度提示；林荫停留面 | TP-02, TP-03 |
| S07 | N2 / AI原点社区 | 纸面+数字双通道导视；入口节点 | TP-03 |
| S08 | N3 / 大钟寺AI产业集聚区 | 存量基座展示柜；产业展示界面 | TP-01, TP-03 |
| S09 | N3 / 大钟寺AI产业集聚区 | 商务/消费时段切换；可逆服务模块 | TP-01, TP-02, TP-03 |
| S10 | N3 / 双翼接口 | 设施巡检与人工工单；街道/庭院边界 | TP-02, TP-03 |

每张卡只允许使用匿名聚合、公开或经授权的汇总字段；不采集人脸、生物特征或个体轨迹。AI 输出仅作提示，涉及安全、无障碍、内容发布、资源调度的关键判断由人工复核；用户可选择人工/纸面路径并关闭数字层。

## 指标体系、面积复算与合规矩阵

三套协议与两个近期试点把场景、数据、责任人、阈值和失败退出绑定到 `metrics.json`、`assumptions.json`、`risk.json` 与合规矩阵；任何 participant-proposed 数值都不是已测结果。[metric:scenario_card_count] [metric:common_test_protocol_count] [metric:mapping_count]

### 三套通用测试协议与两个近期试点

以下是可复现的概念级协议。所有数值是 `participant-proposed`、`provisional`、**待专业论证**的参与方提议阈值，不代表已测、已验证或官方认可。基线须在 T0 由责任人按同一口径采集；若样本或许可条件不成立，试点不得宣称通过。

| 协议 | baseline / sample / window | formula 与 numeric threshold | 数据来源、责任人 | 验收 / 失败退出 |
| :--- | :--- | :--- | :--- | :--- |
| TP-01 慢行与到达 | T0 同一路径中位到达时间；≥30 次匿名同行测试，含 ≥6 次轮椅/推车路径；2 个工作日 + 1 个周末，早晚各一窗 | `improvement=(baseline-median_test)/baseline`；提议验收 ≥10%，且任一重点群体 P95 不恶化 >5% | 人工计时表、路线记录；交通与无障碍负责人（待指派） | 连续两窗低于 10% 或 P95 恶化即关闭 AI 建议，恢复人工引导并复盘 |
| TP-02 公共空间与可达 | T0 纸面导视任务完成率；≥60 人次，至少 20 人次为老年/行动不便/低数字能力参与者；3 次同一时段任务窗 | `completion_rate=completed_tasks/valid_tasks`；提议验收 ≥85%，误导率 ≤5% | 去标识任务记录、人工观察、纸面反馈；公共空间与无障碍负责人（待指派） | 完成率 <85%、误导率 >5% 或出现安全事件即停数字层，保留纸面+人工服务 |
| TP-03 工单与人工兜底 | T0 现有设施工单响应中位时间；≥30 条匿名模拟/真实授权工单；连续 14 天 | `timely_close=closed_within_24h/valid_tickets`；提议验收 ≥90%，误报率 ≤10% | 授权工单台账、人工复核日志；场地运营负责人（待核验） | 连续两日低于 90%、误报 >10% 或无法人工接管即停止自动派单，转人工登记 |

### 近期试点 P1：N1 元胞坊共享试制桌（S01）

`baseline`：试点前 T0 记录 2 个工作日和 1 个周末的预约响应中位时间，目标样本不少于 30 次有效预约；`window`：连续 14 天，按日汇总；`formula`：`(T0_median - pilot_median) / T0_median`；`participant-proposed` 验收阈值为响应时间改善 ≥10%、取消/误配率 ≤5%、人工接管请求 100% 可响应。数据来源为授权预约日志与纸面登记，不采集个人画像；owner 为创新园区运营负责人 + 社区服务负责人（均待核验）。任何授权、事实、隐私、排队安全门失败，立即关闭匹配提示，改由人工排班和纸面登记。

### 近期试点 P2：N2 智纹台双通道导视（S04/S07）

`baseline`：T0 以纸面地图完成同一条无障碍路线任务的成功率和 P95 用时为基线；`sample`：≥60 人次，其中至少 20 人次来自老年、行动不便或低数字能力参与者；`window`：3 次现场任务窗，工作日/周末各至少一次；`formula`：`completion_rate=successes/valid_tasks`，`p95_change=(pilot_P95-baseline_P95)/baseline_P95`；`participant-proposed` 验收为完成率 ≥85%、P95 不恶化 >5%、人工求助响应率 100%。数据来源为匿名任务记录、纸面回收表和人工观察；owner 为公共空间与无障碍负责人（待指派）。若阈值未达、出现误导或现场人员不能接管，数字提示下线，继续提供纸面地图、人工服务台和可见求助标识。

## 用地、建筑规模与拆改留方案

`geometry/land_use.geojson` 有 **27 个**要素，六类用地 union 覆盖 provisional site polygon，面积合计 11,412,825.386 m²。正式 land-use category 口径中，公园绿地为 3,116,095.041 m² / site area = **27.3034%**；这取代未定义的“30%”概念比例。[metric:land_use_feature_count] [metric:land_use_green_ratio]

另有 `geometry/green_space.geojson` 的生态绿地 overlay 为 1,255,908.493 m² / site area = **11.0044%**，它不是 land-use category，不与 27.3034% 相加。公共空间 overlay 为 36,150 m² / site area = 0.3167%。三者均是 provisional 结构复算，官方边界、权属和分类发布后按同一公式重算；正文、图件、HTML、PDF 和 metrics.json 只使用上述标注。[metric:green_ratio] [metric:public_space_ratio]

## 交通、轨道、市政与公共服务设施

铁路遗址线、道路、轨道站点和步行网络在 `site-overview`、`mobility-bluegreen` 中均作为关系性线索：铁路/车站用于说明连续性与换乘方向，道路用于慢行与服务接驳，空间类型用于节点功能解释；它们不代表现状调查、交通批复或工程红线。纸面导视、人工服务台和人工工单是数字层失效时的公共服务兜底。

本节的实施意图是建立“关系线索—现场复核—人工服务”的顺序，而不是把示意线直接当作交通或市政方案。慢行链需要在现场核对人行连续性、无障碍坡度、过街安全、夜间照明、铁路及轨道保护边界和公共服务可达性；站点只作为换乘方向提示，车站名称和位置仍须与公开且有日期的来源交叉核查。三套 TP 协议的参与者提议阈值只能验证服务体验，不可替代交通工程、消防、轨道、管线和无障碍专业审查。道路、铁路、站点和公共空间图层的空间范围采用同一 provisional site 作为关系底板，后续若正式边界变化，应重新计算路径覆盖、公共空间比率和节点连接，并在图件和矩阵留下差异记录。任何数字提示失效、误导或触发安全事件时，立即停止自动建议，使用纸面地图、可见求助标识、人工服务台和人工工单；这也是对数字能力不同、行动不便和临时访客群体的最低服务边界。[data:PACKAGE-GEOMETRY] [metric:public_space_ratio] [source:DATA-SRC-MOHURD-URBAN-DESIGN-MEASURES]

## 蓝绿空间、公共空间与城市风貌

三节点的公共空间表达优先采用可达停留、蓝绿连续性、纸面导视和可逆设施；诊断性词语只有在取得逐项来源后才能升级为现状判断。

蓝绿与公共空间的设计意图是形成可停留、可识别、可回退的公共底盘：N2 智纹台优先处理遮荫、座椅、无障碍停留、纸面导视和可关闭的轻量数字层；N3 生长庭通过存量基座和可拆模块控制对既有空间的侵入；N1 元胞坊把共享试制、社区服务和研发界面交界处的公共可达作为混合使用的校核点。当前 1,255,908.493 m² / site union = 11.0044% 只表示 green_space overlay，36,150 m² / site union = 0.3167% 只表示 public_space overlay，不等于法定绿地率、开放空间率或设计达标率。现场植被、排水、热舒适、无障碍、照明、文保和产权资料均未逐项确认；应在 T0 由专业人员按同一边界、同一分类和同一日期补测，并把不确定项留在 assumptions 与 risk 中。若现场不能提供连续安全路径或人工服务，数字层和可逆设施不得进入下一阶段，纸面/人工通道必须先恢复。[metric:green_ratio] [metric:public_space_ratio] [source:DATA-SRC-MOHURD-URBAN-DESIGN-MEASURES]

### 三节点诊断与证据边界

“工业遗存、社区割裂、设施老化、仓储闲置”等未在本包取得逐项现场调查、保护名录或权属档案。除任务书/公告明确的范围信息外，这些词在方案中一律作为 **待验证设计假设 / 概念情景**，不作为现状事实；需在 T0 由规划、文保、交通、权属和社区代表逐项核验，记录 `source_id`、日期、空间范围和照片/测绘许可后才可升级。三节点图中使用“存量基座”“关系性割裂”“设施更新需求”等设计语言，不把未证实诊断写成既成事实。

## 更新项目清单、实施政策与分期计划

| agent | 交付内容与本包证据 |
| :--- | :--- |
| agent.1 | 一带总体概念、三区两翼—三节点结构、任务区与三层范围；`proposal.md §§1-3`、`site-overview`、`key-areas` |
| agent.2 | AI 原生空间/基础设施接口与 N1 试点；`proposal.md §§4-6`、`metrics.json`、`land-use-structure` |
| agent.3 | 十张场景卡、三套协议、匿名聚合与人工兜底；`proposal.md §4-5`、`metrics-evidence`、HTML/visual |
| agent.4 | N2 公共空间、N3 可逆模块和包容性路径；`proposal.md §3,§5`、`key-areas`、`mobility-bluegreen` |
| agent.5 | 京张遗产、中关村服务和 AI 新文化的双语叙事；`proposal.md §7,§9`、`sources.json`、英文交付 |
| agent.6 | 分期、活动、运营责任、退出与人工接管；`proposal.md §8`、`risk.json`、矩阵 |

近期（1–3 年）只建议做可逆、低负荷、人工可接管的 P1/P2 试点；中期（3–5 年）在正式边界、权属、交通、消防、文保和数据许可确认后扩展；远期（5–10 年）是否形成网络取决于前述证据与试点结果。任何阶段都设置停止、回滚、纸面替代和人工服务入口。[source:DATA-SRC-AGENT-TASKBOOK-20260518] [data:PACKAGE-GEOMETRY] [metric:common_test_protocol_count]

### 八个案例：仅作机制参照，逐项 source_id 可追溯

八个国际/国内案例在 `sources.json` 中逐项登记，案例表不使用无法确认复用权的第三方图片；本包图件均为作者绘制的概念图。所有案例条目当前 `review_status=needs_human_verification`、`usable_for_formal=no`，在人工核验页面、发布日期、许可和复用边界后才可升级为 formal 证据。

| 案例 | source_id | 可借鉴机制 |
| :--- | :--- | :--- |
| New York High Line | CASE-INT-HIGH-LINE | 线性遗产公共空间与分期运营 |
| Seoul Seoullo 7017 | CASE-INT-SEOULLO-7017 | 车站两侧步行缝合与高架公共层 |
| Paris Promenade Plantée | CASE-INT-PROMENADE-PLANTEE | 旧铁路慢行连续性与植被叠合 |
| Chicago 606 | CASE-INT-CHICAGO-606 | 多社区连接和活动运营 |
| 北京首钢园 | CASE-CN-SHOUGANG-PARK | 工业存量与创新产业/公共空间转译 |
| 上海西岸 | CASE-CN-WEST-BUND | 工业岸线、文化和公共开放界面 |
| 深圳大沙河生态长廊 | CASE-CN-DASHA-RIVER | 线性蓝绿廊道与社区连接 |
| 成都猛追湾 | CASE-CN-MENGZHUIWAN | 小尺度渐进更新与日常运营 |

案例不证明 CELL·JZ 的技术或政策可行性，也不构成合作、授权、绩效迁移或投资承诺。

## 风险、版权与合规说明

完整台账见 `report/copyright_statement.md`：覆盖方案名称/Logo、字体、图片/地图、数据、代码与生成方式、日期、URL、license、允许/禁止用途和待核验项。`CELL·JZ`、元胞坊、智纹台、生长庭为本方案原创概念名称；`CELL·JZ` 不主张为官方品牌。图件为作者使用本地 Noto Sans SC 和 Matplotlib/ReportLab 绘制，案例为文字机制参照，未嵌入第三方案例图片。[source:DATA-SRC-AGENT-TASKBOOK-20260518] [data:PACKAGE-GEOMETRY]

边界声明使用“证据状态与复用边界”语言，不作“引用即不侵权”之类法律结论：未核验来源、权属、许可、隐私、文保、消防、交通或数据条件的内容不得转入实施宣传；发现权利或安全门失败时删除/下线资产，保留人工替代。

### 双语交付与 QA 合约

中文/英文正文、五套核心图、A0、A3、report HTML 与 visual HTML 使用相同编号、节点、指标、警示和证据锚点。英文版不得残留中文；四个 HTML 离线嵌入可再分发 Noto Sans SC 子集，且不依赖网络。交付前检查：

- 图片标题、节点名、任务区名、计数、比例、阈值和 provisional 警示逐项等价；
- `proposal.en.md` 与 `proposal.en.html` 不出现中文残留、方框字符、占位符、断词或越界；
- PDF 可解析，A0/A3 页面尺寸与边距安全，图件无重叠、裁切、拥挤和小到不可读的正文；
- manifest、矩阵、sources/权利台账、`self_check.json` 与实际文件清单一致；
- 四门检查只证明本包的形式/结构约束，不代替 CocoSgt 评审或现场/法定验证。

## 参考资料

任务范围与名称以 `DATA-SRC-OFFICIAL-ANNOUNCEMENT-20260509`、`DATA-SRC-AGENT-TASKBOOK-20260518` 为准；专业方法参考 `DATA-SRC-MOHURD-URBAN-DESIGN-MEASURES`、`DATA-SRC-MOHURD-CONTROL-DETAILED-PLANNING` 和 `DATA-SRC-MNR-LAND-USE-CLASSIFICATION-202311`。八个案例必须使用自身 `CASE-*` source_id，不能用一个总称替代逐项追溯。

这些来源分别承担不同证据职责：公告和任务书只支持项目范围、任务名称、三大定位、五大功能、三区两翼及 agent.1-agent.6 的要求；专业方法来源只用于说明规划设计、无障碍、用地分类和证据表达的工作边界；provisional geometry 仅支持本包的可复算演示；CASE-* 只用于机制参照，当前不作为 formal 事实来源。每条来源的发布日期、获取日期、review_status、usable_for_formal、允许/禁止用途和复用边界在 sources.json 中登记，无法确认的案例发布日期和许可不被写成已核实。后续任何新增事实、图像、地图、模型或数据，都必须先补 source_id、日期、空间范围、生成方法和权利字段，再决定是否进入正文、图件、HTML 或 PDF。[source:DATA-SRC-OFFICIAL-ANNOUNCEMENT-20260509] [source:DATA-SRC-AGENT-TASKBOOK-20260518] [data:PACKAGE-GEOMETRY]
