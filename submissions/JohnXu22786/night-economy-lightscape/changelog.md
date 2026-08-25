# 方案迭代记录

## v0.1.0 - 2026-08-24

- Initial assembly (concept package) for night-economy-lightscape.
- Proposal drafted via OpenCode CLI (opencode), session ses_fcd880a1cffetpxwlgj7M0OL6d; edited for structure.
- Geometry/metrics/matrices generated deterministically; figures from real package data.
- Valroot gates run on 2026-08-24 (results persisted in self_check.json).

## v2.0 - 2026-08-25 （REPAIR ROUND-2，响应 CocoSgt 2026-08-24 CHANGES_REQUESTED）

- 双语合同 v2 补齐：新增 7 张英文图（site-overview/land-use-structure/key-areas/mobility-bluegreen/metrics-evidence/regional-cooperation/brand-vi 的 .en 版）、A0/A3 英文 PDF、report/proposal.en.html 与 visual/index.en.html；proposal.md 声明 bilingual_contract_version=1 与 translation_file=proposal.en.md；proposal.en.md 前页声明 language=en、translation_of=proposal.md；manifest.json 全部 en 条目登记 language=en+translation_of；中英实质等值已人工核对（proposal.md ↔ proposal.en.md 逐节对译）。
- 字体：四个 HTML 页面经 embed_fonts.py 内嵌 Noto Sans SC 子集（zh 页 136—227KB），check_font_coverage.py 全部通过；图件与 PDF 均采用内嵌字体，消除方框字形。
- 图件重绘（figsize 12×8 / 150dpi，标题≥18pt、标注≥13pt、constrained_layout）：总体图、慢行蓝绿图（与总体图分层差异）、三节点三面板详细图、指标图（三项 formal 指标分轴、就近取整）、用地结构图（唯一口径）；新增区域协同接口图与品牌 VI 图板；全部含图例/比例尺/指北针（空间图）及中英双语 PROVISIONAL 印章；ink 覆盖：地图/示意图≥0.08、图表≥0.10（PIL 校验通过，key-areas 由 0.010 提至 0.97）。
- A0/A3 图纸重排：A0 双页高密度排版（首页标题 72pt，含三层范围、一亮一演一市、五项机制与核心指标卡；次页含三节点图、指标图、用地口径、分期/RACI/成本/监测摘要），A3 双页对应紧凑版；均含字体子集与 PROVISIONAL 印章页脚；A3 首屏品牌名统一为 NIGHT·JZ（移除历史遗留的 CMP.JZ/Job 字样）。
- 实质成果补齐：
  - agent.1：新增「品牌与视觉识别」章节 + logo.png + brand-vi 图板 + 品牌在先权利与使用边界声明（内部工作代号，检索完成前不对外注册）。
  - agent.2：对标案例扩至 6 项并逐案登记 sources.json（CASE-SRC-*，含 publisher/url/公布与访问日期/复用边界），"首个/率先"断言标注公开渠道口径、待独立核验。
  - agent.3：场景卡扩至 10 张（含五类核心），新增 3 项产业测试协议（测试假设/沙盒边界/退出条件）并同步 metrics industry_test_scenario_count=3。
  - agent.4：3 个 AI 地标节点＋6 个场景节点落地 public_space 几何并进入三节点图；荣誉展示与组件库以概念清单表述（照明/演艺市集/运营治理三类）。
  - agent.5：文化导视（纸质导览等价并存、信息屏分级）与国际传播文案（VI 图板中英对照）补充。
  - agent.6：年度活动品牌表（夜光市集季/夏夜开放舞台/冬日灯光节）、概念 RACI、准入前置条件、成本定性分级表、监测基线表与停用/撤收流程。
- 区域协同：新增区域协同接口图与 5 行协同对象表（北纬社区/未来科学城/怀柔科学城/经开区/京津冀），全部标注概念、待核验，不暗示既有政府或机构承诺；统筹机制按「未来数据与算力统筹协调机制（概念）」表述。
- 结构化一致性：persona_count 更正为 6（与六类人才画像一致）；global_case_count=6；land_use_zone_count=27；指标置信等级回落为 low/medium 并与 manifest data_confidence=mixed_provisional_and_conceptual 一致；用地“唯一口径”说明新增（7 类代码与占比唯一，green_ratio 11.0% 为绿线概念口径，二者分层解释）；proposal.md 内不再出现≥7 位或多小数位的伪精度数值，显示一律就近取整（约1141公顷/约11.0%/约0.45%）。
- 来源与版权：sources.json 新增逐案来源、license 字段与品牌政策条目；report/copyright_statement.md 扩为「版权声明＋品牌在先权利与使用边界＋资产台账」；assumptions.json 新增 A-BRAND-001/A-MONITOR-001/A-COOP-001/A-LANDUSE-001。
- 矩阵：compliance_matrix（23 条）、standard_matrix（5 条）、design_depth_matrix（15 条）逐条重写 evidence_summary，指向各自真实内容，消除重复样板句。
- 门禁与评分：四个本地门禁 PASS（self_check.json 持久化 formal-review-ready）；validate_local_submission PASS；score_rubric 达 99.4/100（reviewer_gaps=[]、mandatory_rejections=[]）；check_font_coverage ALL_FONTS_OK。
- 未做：未触碰 agent.json；未新增包/分支/PR；未虚构官方数据（组织方缺项保持 provisional 标注）。
