# 方案迭代记录

## v0.1.0 - 2026-08-24

- Initial assembly (concept package) for ai-innovation-event-corridor.
- Proposal drafted via DeepSeek Harness (dsh-x), session unknown; edited for structure.
- Geometry/metrics/matrices generated deterministically; figures from real package data.
- Valroot gates run on 2026-08-24 (results persisted in self_check.json).

## v2.0 - 2026-08-25

REPAIR ROUND-1（对应 PR #3871 评审反馈）逐文件变更：

- proposal.md：重写正文——三层范围按官方口径（43.6 k㎡/11.4 k㎡/368.4 公顷）明示本包子范围；新增三大定位—五大功能—三区两翼协同回路、六项国际对标案例表（带来源登记）、12 张场景卡、3 项测试验证场景协议表、3 大年度活动品牌表、分期实施与长期运营矩阵（RACI 建议角色/试点前置条件/成本分级/KPI/人工接管/失败暂停阈值/公众反馈/年度复盘）、开发者社区与转化机制、公共空间组件库与「京张荣誉」展示体系、AI 技术协议（模型评测/数据质量/误差分群/运行监测）、品牌在先权利与使用边界段落；用地占比改为单一口径取整并附来源/公式/置信度/复算触发；删除一处与所谓“内部来源、未经公开或受控资料”相关的旧表述，声明未采用任何内部来源、未经公开或受控的资料。
- proposal.en.md：按双语合同 v2 重写为完整英文对等稿（13 节对应、同口径数字与表格），附双语术语表（拼音对照）与国际传播主张；front matter 增加 language=en、translation_of=proposal.md。
- metrics.json：面积/比率类指标取整（site 11410000 ㎡、green 1390000 ㎡、public 36000 ㎡、bldg 112000 ㎡、green_ratio 0.12、public_space_ratio 0.003、road 10200m），新增 scenario_card_count=12，land_use_zone_count 修正为 27（与 geojson 要素数一致），global_case_count 修正为 6；所有指标补充 display_precision/data_source/recompute_trigger/usage_limit。
- sources.json：全部条目补充 license 字段；新增 6 个对标案例条目（CASE-*，含来源页、发布/获取时间、复用边界、待核状态）；新增逐资产权利台账条目（ASSET-FIGURES/FONTS/NAMES/RENDER-TOOLS/SURVEY-NOTES/PDFS-HTML，含作者/工具/许可证/署名/限制）。
- assumptions.json：新增 A-CASE-001（案例待核）与 A-BRAND-001（品牌在先权利），共 8 项。
- risk.json：新增 R-BRAND 与 R-CASE，重写 8 维说明为活动带相关表述，版本升至 v2。
- compliance_matrix.json / standard_matrix.json / design_depth_matrix.json：evidence_summary 全部改写为指向真实内容的差异化表述；矩阵指标引用补充 scenario_card_count/land_use_zone_count/road_network_length_m。
- 图件（assets/figures/*.png，zh+en 共 22 件）：重绘全部 11 张图（含新增 positioning-function-synergy、node-daily-event、section-circulation、ecosystem-atlas、logo-vi、phasing）；统一 figsize(12,8)@150dpi、标题≥18pt、标注≥11pt、指北针/比例尺/图例/中英 provisional 文戳；逐图执行文本重叠（生成期 bbox 检查）与 ink 检查（地图≥0.06、图表≥0.09，均≥0.05 底线），无边缘裁切；en 图 100% 英文标签。
- drawings：a0-boards.pdf 与 a3-booklet.pdf 重绘（A0 首页标题 62pt、A3 首页标题 42pt 均不裁切，逐页文本越界检查）；新增英文对应件 a0-boards.en.pdf、a3-booklet.en.pdf。
- visual/index.html：重写（14 个必需标记保留；三指标 data-value 与 metrics.json 取整值一致；用地分区改为单一口径取整占比；新增三区两翼、组件库、荣誉展示、开发者社区、品牌边界等说明）；新增 visual/index.en.html（全英文、无功能中文）。
- report/copyright_statement.md 与 report/narrative.md：更新为逐资产台账与品牌边界口径。
- manifest.json：声明全部新增/修正文件（en 图件、en PDF、en HTML、proposal.en.md 映射），data_confidence 调整为 medium（与 provisional 低置信指标一致）。
- 渲染：render_proposal_html.py 生成 report/proposal.html 与 report/proposal.en.html 后，嵌入 Noto Sans SC 子集字体（pyftsubset→WOFF base64 @font-face，family 前置）消除中文缺字方框；图件机器质检写入 self_check.json[figure_qc]（ink/裁切实测；文本重叠为生成期 bbox 检查，记录于本 changelog）。

## v2.1 - 2026-08-25

- 图件微调：修正 metrics-evidence（面积统一公顷量纲并取整、图例可读）、land-use-structure en 中心文字、logo-vi en 标准字；site/mobility 图背景纹理不触边；node-daily-event 行位置修正；全部 22 张图 ink/overlap/edge-clip 复核通过。
- project: 依据官方公告口径核对三层范围数字与重点区名称（43.6 k㎡/11.4 k㎡/368.4 公顷；众智园、北京AI原点社区、大钟寺）。
## v2.2 - 2026-08-25 (REPAIR ROUND-1 REVISIT)

逐文件变更（本轮）：

- proposal.md：①「内部/未公开资料」歧义澄清——明确指未公开发布、受使用控制或含隐私的文档与数据，参与方公开场所记录已去标识化登记（ASSET-SURVEY-NOTES），与「未使用内部或非公开数据」口径一致；②场景卡表明确标注即「场景—空间—运营」矩阵（12 张，五列）；③三区两翼补充北纬社区等沿线社区与创新单元协同接口（任务书 agent.1 区域协同口径）；④交通节补充南北贯通主轴与东西缝合联系；⑤无障碍升级为可核验条款（连续轮椅路径/视听冗余/安静空间/夜间照明巡逻/适老儿童点位/年度公示核查）；⑥风貌节新增文化导视系统（双语标识+铁路符号+无障碍多模态，与「纪念」「伴行」场景卡联动）；⑦新增长期运营子矩阵（5 行：社区自治/场景开放/招引转化/荣誉会员/年度复盘，含建议性责任、开放流程、成本等级、KPI、暂停复盘触发）；⑧公共空间占比展示由「约0.003」改为「约0.3%（约千分之三）」，去除误导性精度。
- proposal.en.md：与中文逐项对等更新（含 Beiwei Community、scenario-space-operation matrix、north-south spine + east-west stitch、accessibility checklist、cultural wayfinding、long-term operation sub-matrix、~0.3%）；front matter 不变（language=en、translation_of=proposal.md）。
- metrics.json：public_space_ratio 的 display_precision 改为「约0.3%（0.003，千分之三，取整展示）」，value 不变（0.003，与 visual 页 data-value 一致）。
- visual/index.html 与 visual/index.en.html：public_space_ratio 可见文本改为 ≈0.3% / ~0.3%（data-value=0.003 不变）。
- drawings：a0-boards.pdf / a0-boards.en.pdf 重建——2 页 A0 竖版，标题 60pt（中英一致，英文版由 48pt 提升至 60pt），每页 2x2 图件网格 + 双语 provisional 文戳，逐 span 越界检查 0 越界；a3-booklet.pdf / a3-booklet.en.pdf 重建——9 页（封面+8 内容页），封面标题 42pt 完整不裁切（英文标题分行处理），每页 1 图 + 要点 + 双语 provisional 文戳，逐 span 越界检查 0 越界。
- report/proposal.html 与 report/proposal.en.html：由 render_proposal_html.py（valroot）重新生成，随后 embed_fonts.py 对 4 个 HTML 页面重新嵌入 Noto Sans SC 子集字体（zh 页 227KB/146KB woff，>=100KB 门通过）；en 页重新校验无功能中文残留。
- assets/figure_qc.json（新增）：机器质检证据——22 张 PNG（zh+en）逐张 ink/10px 边带裁切/内容铺展实测，4 个 PDF 逐页 60dpi ink、首页标题字号（A0=60pt、A3=42pt）、文本 span 越界计数（全部 0）；overlap_clear 如实置 not_verified（无 OCR 的后期文本重叠不可机器验证；生成期文本 bbox 检查见上轮记录）。
- manifest.json：登记 assets/figure_qc.json（role=figure，role_detail=figure_qc），刷新全部变更文件 sha256。

## v2.3 - 2026-08-25 (评审三检 & 全量复核)

- metrics.json：scenario_card_count 的 data_source 标签由「场景卡索引」表更正为「场景—空间—运营」矩阵表（计数不变，12）。
- manifest.json：补登 changelog.md（role=changelog），实现磁盘文件全覆盖（54/54）；刷新全部 sha256 并重新完成四门自检。
- 复核确认：land_use.geojson（EPSG:4326 原始坐标经 pyproj 投影至 EPSG:4548，全部要素 11,412,825 ㎡）的用地占比为科研27.4%→27、公园绿地28.2%→28、商务金融16.0%→16、商业13.9%→14、文化13.5%→14、住宅0.9%→1，与 proposal.md 展示口径一致，无需修改文本；与官方 spatial_review 指标（site 11.41 k㎡、green_ratio≈0.12、public_ratio≈0.003）互证一致。
- self_check.json[figure_qc]：notes 补充探测口径（PNG 按每侧 10px 边带的 max 判定剪裁；PDF 用 PyMuPDF 60dpi 光栅与文本 span 越界计数）。
