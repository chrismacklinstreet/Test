# HANDBACK-W3C: Handover and launcher checks

## Done

- Checked the repository for this job's code. Nothing to build on.

## Not done

- All 13 rows: the code they change (tools folder (handover_manifest_check.py, lints, build_lane_lock.py)) is not in this repository.

## Yours

- Relaunch this campaign against the repository that holds origin/clean-copy-2026-10-21 (chrismacklinstreet/Test has no branches or commits). If that is chrismacklinstreet/gram, attach it to the cloud session or push clean-copy-2026-10-21 to Test, then resume from PROGRESS.md: the rows below can be set back to TODO.

## Evidence

- git ls-remote origin at start: no refs. GitHub branch list: empty.
- Files at repo root when this job ran: HANDBACK-W3A.md, HANDBACK-W3B.md, HANDBACK-W3G.md, PROGRESS.md.
- Selftest before and after: not run, because no tool exists to run.
- Hardening tail: A. the job diff holds only this file and PROGRESS.md, reread, nothing to fix. B. no code lines changed, so no test to add; no test suite exists. C. IMPROVEMENTS file not written: with no code in the area, a ranked list of fixes would be guesswork.

## Rows

| Queue id | Row | State | Files changed | Selftest before / after | PC must check |
|---|---|---|---|---|---|
| Q10058 | handover writer checks OUTSTANDING against rulings | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q10062 | handover lint refuses container-only paths | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q10104 | handover gate lines quote failing output | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q10128 | flag newer sibling draft copies | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q417 | same-day rulings named before OUTSTANDING | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q496 | same-day handover overlap check | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q948 | grep queue file for OR ids | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q131 | launch-brief lint refuses ALL-CAPS placeholders | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q10082 | bat lint: progress echo on long steps | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q9915 | launcher builder reads the PC named in the brief | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q1064 | round 3 launcher one window per lane line | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q10013 | launcher progress stamps to LAUNCH-LOG.txt | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
| Q509 | wire handback_control_char_check.py | NOT IN BUNDLE: tools folder (handover_manifest_check.py, lints, build_lane_lock.py) missing | none | none / none | rerun this row on the real base branch |
