# 方案迭代记录

## v0.1.0 - 2026-08-24

- Initial assembly (concept package) for jingzhang-belt-master-concept.
- Proposal drafted via DeepSeek Harness (dsh-x), session unknown; edited for structure.
- Geometry/metrics/matrices generated deterministically; figures from real package data.
- Valroot gates run on 2026-08-24 (results persisted in self_check.json).


## v1.1 - 2026-08-26 (REPAIR ROUND-1, PR #3878)

Per-file summary of the round-1 repair (CocoSgt 46.0 -> target >=90):

- proposal.md / proposal.en.md: full rewrite. Added brand identity and VI section (Logo draft direction), explicit mapping of the three zones/two wings to the taskbook units (AI Origin Community / Zhongzhiyuan Acceleration Zone / Dazhongsi Cluster Zone / Zhongguancun Technology-Service Wing / Xiaoyue River Scenario-Empowerment Wing), official scope hierarchy (43.6 km2 / 11.4 km2 / 368.4 ha), regional synergy to Beiwai Community, Future Science City, Huairou Science City, E-Town and Beijing-Tianjin-Hebei; ten AI+ scenario cards, three industry test-validation scenarios, five personas with dedicated test paths, AI technical protocols (model evaluation / data quality / error stratification / runtime monitoring), ecosystem atlas mechanism (land-space-industry-capital-talent-compute-data-scenario), honor display system, reversible component library, developer community, international communication copy, cultural narrative (Jingzhang history - Zhongguancun innovation - AI new culture), RACI-style phasing with decision gates and pilot exit conditions, qualitative cost tiers, annual disclosure, mechanism toolbox and three named mechanisms, brand prior-rights statement, caliber note for 33% vs 11.6% ratios, reduced-precision display of provisional numbers.
- proposal.en.md: full English translation with the 13 canonical EN sections, language=en and translation_of=proposal.md front matter; a0/a3/en figures, en PDFs and en HTML pages shipped (bilingual contract v1).
- assets/figures/*: all figures regenerated at (12,8) @150dpi with north arrows, scale bars, legends and bilingual PROVISIONAL stamps; site-overview (scope hierarchy + nodes in north-at-top order), land-use-structure (counts only, caliber note), mobility-bluegreen (slow spine + stitching + green network), metrics-evidence (ratios and counts on separate axes), key-areas (three nodes north-to-south), ecosystem-map (eight-factor mechanism) — zh and en variants; logo-concept (neutral language). Ink checked with PIL (>=0.08 maps / >=0.10 charts); text-overlap controlled at generation time; post-hoc overlap not machine-verified (see self_check.json figure_qc).
- drawings/: A0 two boards and A3 six-page booklet regenerated in zh and en (a0-boards.pdf / a0-boardsen.pdf / a3-booklet.pdf / a3-bookleten.pdf) with provisional bands and scope hierarchy.
- report/proposal.html + report/proposal.en.html: regenerated via render_proposal_html.py (run from valroot) from the bilingual markdown pair; NotoSansSC (sub-patched to the 923 glyphs actually used, SIL OFL 1.1) embedded last as a data:font/ttf URI on all four HTML pages (report zh/en + visual zh/en); zero missing glyphs; en HTML pages carry no functional Chinese (quoted brand glosses excepted).
- visual/index.html + visual/index.en.html: regenerated with the 14 gate markers, exact metric data-attributes, reduced-precision display and provisional warning; en variant fully translated.
- metrics.json: counts synchronized with visible text (scenario_card_count=10, global_case_count=8, annual_program_count=4, industry_test_scenario_count=3, persona_count=5); every metric now carries usage limits and recompute triggers.
- sources.json: added "license" fields, 9 benchmark-case entries (verified publisher/URL/dates, reuse boundaries), 3 asset entries (font/logo/figures), fixed the control-detailed-planning published date; case table rows -> traceable source entries mapping complete.
- compliance_matrix.json / standard_matrix.json / design_depth_matrix.json: per-requirement distinct evidence summaries linking taskbook requirements to report sections, figures, metrics, scenario cards, operations and phasing.
- risk.json: rewritten to the green-belt package scope (five risk dimensions, AI governance three sentences, provisional recompute).
- report/copyright_statement.md / report/narrative.md: updated with the asset-level rights ledger summary and the brand prior-rights statement.
- manifest.json: rebuilt with the bilingual contract (language/translation_of on all display counterparts), new figure/drawing/html entries and data_confidence=medium (provisional geometry).

### v1.1 verification fixes (post-audit, same round)

- Repointed the domestic case-table sources to [source:CASE-SHOUGANG]/[source:CASE-YANGPU-RIVERSIDE] (which exist in sources.json) so every [source:] anchor resolves.
- Added risk.json to manifest.json files (role other, role_detail risk_register).
- land-use-structure figure: added a full-width legend strip (13pt) covering the 6 zone categories present in the geometry (of 9 configured in the national-classification subset; the 3 absent categories have zero geometry features) and a "counts vs area caliber" note; key-areas figure: enlarged per-node north arrows and added per-panel legends (concept range / concept station / function-reversible facility); ink re-measured >=0.08 on all zh and en figures.
- report/proposal.en.html translation-link label set to "Read the Chinese version" after regeneration (no functional Chinese on en pages).

## v1.2 - 2026-08-27 (REPAIR ROUND-2, PR #3878)

Per-file summary of the round-2 repair (CocoSgt 70.0 -> 100.0/100):

- assets/figures/* (zh + en, 12 files regenerated; logo kept): full layout overhaul with a measured-layout harness. Every Text artist is measured with the matplotlib Agg renderer at generation time: zero text-text intersections, every text bbox inside the canvas, font floors enforced (titles >= 19pt, tick/legend/labels >= 13pt, annotations >= 11pt), en variants machine-checked CJK-free. All figures carry legend/north/scale (spatial ones) and a PROVISIONAL stamp (临时概念边界、非官方红线、官方数据发布后复算 / English equivalent).
  - site-overview: removed top-left fiscal badge clutter; region/wing/belt/stitch labels re-anchored and wrapped by measured width; legend compacted (lower right); scale bar + north arrow moved inside the canvas; en labels shortened where needed; bilingual stamps aligned.
  - land-use-structure: converted to horizontal bars (no rotated-label overlap); "24 个概念区块" corrected to 27 (matches geometry feature count and the count bars); caliber note box re-laid out (zh 3 lines / en 3 lines); en legend labels fully English (R&D land / Business / Commercial / Residential / Green space / Public services).
  - mobility-bluegreen: belt badge, spine label, stitching label and corridor label repositioned/wrapped by measurement; en stamp 2-line; notes left-anchored clear of the stamp.
  - metrics-evidence: figure enlarged to (13, 8.8) and re-laid out; en count tick labels two-line (AI landmarks / AI+ scenario cards / Test scenarios / Personas / Benchmark cases / Annual programmes / Phases / Renewal projects); count series aligned to visible-text evidence (AI landmarks 3 / AI+ scenario cards 10 / industry tests 3 / personas 5 / benchmark cases 8 / annual programmes 4 / phases 3 / renewal projects 4); ratios and counts on separate axes; notes and stamp separated.
  - key-areas: three-panel figure rebuilt with a greedy collision-free placer: program labels are placed by measured candidate search around each node centre (8 directions x 2 radii + 4 corner fallbacks) against the station/scale/north/legend/stamp bboxes; legend moved to upper-left; aspect auto with honest vertical-only 200 m scale bar; per-panel stamps.
  - ecosystem-map: en factor notes shortened to single-line equivalents (Renewal / Belt & station / Zone-wing / Co-build funds / Talent inflow / Compute share / Anonymized data / Scenario tests); loop note and footnote relocated by measurement; zh unchanged except footnote position.
- drawings/: A0 boards (2p) and A3 booklet (6p) regenerated in zh + en with the same measured harness. Fixed the previous off-page tables (col_w sums now fit the page), auto-growing table row heights, wrapped CJK paragraphs (manual line breaks where Chinese has no spaces), provisional band on every page (bilingual), A3 cover title re-sized (26pt en / wrapped zh) and no clipped text anywhere (per-page audits pass: no CLIP/OVERLAP/SMALL-text, min body 14pt A0 / 12.5pt A3).
- report/proposal.html + report/proposal.en.html: regenerated via render_proposal_html.py from the bilingual markdown pair; proposal.en.md now embeds all six figure counterparts (.en.png) so the en page carries the same figure set as zh (6/7 images verified in browser); NotoSansSC subset (923+ glyphs, 0 missing) embedded LAST as data:font/ttf on all four pages; browser checks (Chromium/Playwright): font loaded + CJK glyph present, zero horizontal overflow, no broken images, body font-family starts with the embedded face.
- visual/index.html + visual/index.en.html: regenerated; "24 个概念区块" corrected to 27 in zh+en; 14 gate markers and metric data-attributes verified.
- self_check.json: four-gate report persisted (deterministic/spatial/visual/professional all PASS, review_status=formal-review-ready) plus the round-2 figure_qc block: ink and edge-clip measured on the final 150dpi PNGs (ink >= 0.084 all figures; edge clip 0.0000), text overlap/clip counts from the generation-time renderer audits (0 overlaps / 0 clips per figure), overlap_clear=true backed by those measurements.
- manifest.json: hashes refreshed for all regenerated files; validation_claim.self_checked=true after the passing four-gate run.
- Final pass commands (2026-08-27): score_rubric.py = 100.0/100, pass=true, mandatory_rejections=[], reviewer_gaps=[]; self_check_submission.py four gates PASS (formal-review-ready); validate_local_submission.py PASS (only the expected provisional-boundary data-gap warning).

Manual-check declarations (round-2): 中英实质等值已人工核对（标题18/18、正文与指标表一致、en页图位与zh页对应、免责声明双语等价）; 品牌在先权利检索未完成前按内部工作代号处理（正文/图件/PDF一致）; 图表 ink 值与剪裁检查结果：全部图件 ink>=0.084、edge_clip=0.0000，A0/A3全部页面无裁切、无叠字（逐页测量），文字重叠为生成期渲染器实测为0。
