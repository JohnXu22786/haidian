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
