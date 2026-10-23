# HANDBACK-W3A: Lane watchdogs and runners

## Done

- Checked the repository for this job's code. Nothing to build on.

## Not done

- All 8 rows: the code they change (tools folder, cockpit_app) is not in this repository.

## Yours

- Relaunch this campaign against the repository that holds origin/clean-copy-2026-10-21 (chrismacklinstreet/Test has no branches or commits). If that is chrismacklinstreet/gram, attach it to the cloud session or push clean-copy-2026-10-21 to Test, then resume from PROGRESS.md: the rows below can be set back to TODO.

## Evidence

- git ls-remote origin at start: no refs. GitHub branch list: empty.
- Files at repo root when this job ran: PROGRESS.md.
- Selftest before and after: not run, because no tool exists to run.
- Hardening tail: A. the job diff holds only this file and PROGRESS.md, reread, nothing to fix. B. no code lines changed, so no test to add; no test suite exists. C. IMPROVEMENTS file not written: with no code in the area, a ranked list of fixes would be guesswork.

## Rows

| Queue id | Row | State | Files changed | Selftest before / after | PC must check |
|---|---|---|---|---|---|
| Q10095 | watchdog alarm when runner heartbeat 30+ min past wake time | NOT IN BUNDLE: tools folder, cockpit_app missing | none | none / none | rerun this row on the real base branch |
| Q10105 | lane status readers report DEAD, not sleeping, 30+ min past wake | NOT IN BUNDLE: tools folder, cockpit_app missing | none | none / none | rerun this row on the real base branch |
| Q9911 | spine guard against duplicate case ids in real_spine.json | NOT IN BUNDLE: tools folder, cockpit_app missing | none | none / none | rerun this row on the real base branch |
| Q9976 | weekly_master.py inside 180 s, estate_dir paths, token_meter hang | NOT IN BUNDLE: tools folder, cockpit_app missing | none | none / none | rerun this row on the real base branch |
| Q1156 | overnight boards written twice; make the write single | NOT IN BUNDLE: tools folder, cockpit_app missing | none | none / none | rerun this row on the real base branch |
| Q130 | device shell scan workers: timeout, scratch file, free space | NOT IN BUNDLE: tools folder, cockpit_app missing | none | none / none | rerun this row on the real base branch |
| Q9970 | build tracker never-run panel: mark launcher held | NOT IN BUNDLE: tools folder, cockpit_app missing | none | none / none | rerun this row on the real base branch |
| Q10124 | refuse web mail email card; calendar plus diary clash check | NOT IN BUNDLE: tools folder, cockpit_app missing | none | none / none | rerun this row on the real base branch |
