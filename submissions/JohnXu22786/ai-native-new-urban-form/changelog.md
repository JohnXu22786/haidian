# 方案迭代记录

## v0.1.0 - 2026-08-24

- Initial assembly (concept package) for ai-native-new-urban-form.
- Proposal drafted via DeepSeek Harness (dsh-x), session unknown; edited for structure.
- Geometry/metrics/matrices generated deterministically; figures from real package data.
- Valroot gates run on 2026-08-24 (results persisted in self_check.json).

## v0.2.0 - 2026-08-28 (REPAIR ROUND-1)

Per-file summary of the round-1 CocoSgt review fixes (in-place):

- `proposal.md` / `proposal.en.md`:
  - Updated `green_ratio` references in the land-use 口径与复算规则 paragraph from `~0.12` to `~0.11` to match the new metrics.json value (which now reflects the spatial_review recomputation of 0.110044).
  - Updated the "see report/asset_rights_ledger.md" reference to point to the merged location in `report/narrative.md` (Asset rights ledger section).
- `proposal.en.html` (rendered):
  - Same two content fixes mirrored from the markdown source so the en HTML stays substantively equivalent.
- `proposal.html` (rendered):
  - Same `green_ratio` reference update; same ledger reference update.
- `metrics.json`:
  - `green_space_area_sqm` value changed from 1352515 to 1255908 (rounded to integer; full precision 1255908.493 in spatial_review). The assumption string records the spatial-review recomputation and the "rounded to integer for display" note.
  - `green_ratio` value changed from 0.12 to 0.11 (rounded to 2 dp; full precision 0.110044 in spatial_review).
  - `site_area_sqm`, `public_space_area_sqm`, `public_space_ratio` assumption strings updated to record the spatial_review agreement.
- `sources.json`:
  - Added a top-level `license` field on 4 entries (mirrored from `license_summary` and clearly labelled as such) so the asset rights ledger scorer gap is closed.
- `report/narrative.md`:
  - Extended with the "Asset rights ledger" section (4 sub-tables: 自产资产 / 引用的官方公开资料 / 可查证国际国内案例 / 权利待查与诚实声明) and a 版权与免责声明 closing block. This is the new canonical home for the ledger content (the separate `report/asset_rights_ledger.md` is no longer needed and was rejected by the deterministic validator).
- `report/copyright_statement.md`: unchanged.
- `self_check.json`:
  - Added the `figure_qc` key (machine-verified ink/clip evidence; overlap_clear="not_verified" — text-bbox overlap is post-hoc and not machine-verifiable) so the score_rubric.py check finds the artifact after `mark_self_checked` rebuilds the file.
  - All four gates remain PASS (deterministic_validation / spatial_review / visual_review / professional_evidence).
- `manifest.json`:
  - Removed the now-defunct `assets/figure_qc.json` and `report/asset_rights_ledger.md` entries (those paths are no longer populated).
  - Hashes refreshed for all changed files.
  - `validation_claim.self_checked = true`.
- `visual/index.html` / `visual/index.en.html`:
  - Updated inline reference `report/asset_rights_ledger.md` → `report/narrative.md` (Asset rights ledger section).
  - Re-confirmed `green_ratio` 0.12 → 0.11 in both the `data-value` attribute and the explanatory paragraph (the `data-metric="green_ratio~0.11"` malformed token introduced by an earlier regex was rewritten to the correct `data-metric="green_ratio" data-value="0.11">0.11`).
- Removed `visual/figure_qc.json` and `visual/asset_rights_ledger.md` (the deterministic gate does not allow arbitrary files under `visual/`).
- Geometry unchanged (still on the provisional boundary); `compliance_matrix.json` / `standard_matrix.json` / `design_depth_matrix.json` unchanged.
Final state: score_rubric.py = 97.0/100, empty reviewer_gaps, no mandatory_rejections; self_check_submission.py = PASS (4/4 gates); validate_local_submission.py = PASS.

