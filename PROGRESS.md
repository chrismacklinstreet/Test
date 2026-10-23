# PROGRESS: W3 foreman campaign, 23 Oct 2026

Branch: cloud/w3-foreman-2026-10-23. Base asked for: origin/clean-copy-2026-10-21.

SESSION NOTE (default taken, no one to ask): origin chrismacklinstreet/Test had no branches and no commits at start, so clean-copy-2026-10-21 does not exist here and this branch was started empty. The tools folder, cockpit_app and bridge-enforcement-hooks are not in this repository. A private repository chrismacklinstreet/gram exists on the account, but the brief says this session sees only this repository, so it was not attached. Every row whose code is missing is NOT IN BUNDLE.

## RULES

1. Work the nine jobs in the order given, and the rows in the order written inside each job (urgent rows come first). One job at a time, never in parallel, because they share one branch.
2. Use one subagent per job if your tools allow it: it gets that job's rows plus the ROW PROCESS and SAFETY wording, works in the same checkout, and reports back in ten lines. That keeps your own context small. If you have no subagents, do the job yourself.
3. After EVERY row (not every 30 minutes): run its tests, commit with the queue id in the message, set the row's line in PROGRESS.md to DONE, PARTIAL, NOT IN BUNDLE or NOT CLOUD with the commit hash and one line of why, and push. The session can be cut off at any moment when the credit ends, so nothing may sit uncommitted.
4. After every job: write HANDBACK-<job code>.md (format below) and run the hardening tail for that job: A. reread the whole diff of the job as a strict reviewer and fix what you find; B. make sure every changed line is covered by a test and run the full test suite; C. write IMPROVEMENTS-<job code>.md listing the next ten most valuable fixes in that area, then do the top three that are safe and testable. Commit and push, update PROGRESS.md, and send both files as download cards if you have a way to. Then start the next job at once.
5. Never ask a question. Never end your turn while any row is TODO. A blocked, missing or unclear row is marked and skipped, never a reason to stop. Do not write a closing summary until every row is closed or you are stopped. Do not try to judge how much credit is left: just keep going in order.
6. If the full test suite breaks because of a change you made, fix or revert that change before the next row.
7. Keep PROGRESS.md a short table you can read in one screen: job code, queue id, state, commit. Put anything longer in the job's HANDBACK file.

## Queue

| Job | Queue id | State | Commit |
|---|---|---|---|
| W3A | Q10095 | NOT IN BUNDLE | see HANDBACK-W3A |
| W3A | Q10105 | NOT IN BUNDLE | see HANDBACK-W3A |
| W3A | Q9911 | NOT IN BUNDLE | see HANDBACK-W3A |
| W3A | Q9976 | NOT IN BUNDLE | see HANDBACK-W3A |
| W3A | Q1156 | NOT IN BUNDLE | see HANDBACK-W3A |
| W3A | Q130 | NOT IN BUNDLE | see HANDBACK-W3A |
| W3A | Q9970 | NOT IN BUNDLE | see HANDBACK-W3A |
| W3A | Q10124 | NOT IN BUNDLE | see HANDBACK-W3A |
| W3G | Q041 | NOT IN BUNDLE | see HANDBACK-W3G |
| W3G | Q10103 | NOT IN BUNDLE | see HANDBACK-W3G |
| W3G | Q1198 | NOT IN BUNDLE | see HANDBACK-W3G |
| W3G | Q438 | NOT IN BUNDLE | see HANDBACK-W3G |
| W3G | Q959 | NOT IN BUNDLE | see HANDBACK-W3G |
| W3G | Q10140 | NOT IN BUNDLE | see HANDBACK-W3G |
| W3B | Q087 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q10034 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q10067 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q10087 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q10126 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q123 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q125 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q169 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q9988 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q9989 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q9990 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q9991 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3B | Q232 | NOT IN BUNDLE | see HANDBACK-W3B |
| W3C | Q10058 | TODO |  |
| W3C | Q10062 | TODO |  |
| W3C | Q10104 | TODO |  |
| W3C | Q10128 | TODO |  |
| W3C | Q417 | TODO |  |
| W3C | Q496 | TODO |  |
| W3C | Q948 | TODO |  |
| W3C | Q131 | TODO |  |
| W3C | Q10082 | TODO |  |
| W3C | Q9915 | TODO |  |
| W3C | Q1064 | TODO |  |
| W3C | Q10013 | TODO |  |
| W3C | Q509 | TODO |  |
| W3D | Q1016 | TODO |  |
| W3D | Q491 | TODO |  |
| W3D | Q988 | TODO |  |
| W3D | Q9908 | TODO |  |
| W3D | Q933 | TODO |  |
| W3D | Q982 | TODO |  |
| W3D | Q173 | TODO |  |
| W3D | Q1160 | TODO |  |
| W3D | Q9994 | TODO |  |
| W3E | Q802 | TODO |  |
| W3E | Q962 | TODO |  |
| W3E | Q963 | TODO |  |
| W3E | Q9936 | TODO |  |
| W3E | Q954 | TODO |  |
| W3E | Q9931 | TODO |  |
| W3E | Q126 | TODO |  |
| W3H | Q10037 | TODO |  |
| W3H | Q10065 | TODO |  |
| W3H | Q10066 | TODO |  |
| W3H | Q10091 | TODO |  |
| W3H | Q10122 | TODO |  |
| W3H | Q103 | TODO |  |
| W3H | Q493 | TODO |  |
| W3H | Q970 | TODO |  |
| W3H | Q984 | TODO |  |
| W3H | Q986 | TODO |  |
| W3H | Q958 | TODO |  |
| W3I | Q1001 | TODO |  |
| W3I | Q1017 | TODO |  |
| W3I | Q199 | TODO |  |
| W3I | Q526 | TODO |  |
| W3I | Q877 | TODO |  |
| W3I | Q920 | TODO |  |
| W3I | Q926 | TODO |  |
| W3I | Q929 | TODO |  |
| W3I | Q931 | TODO |  |
| W3I | Q816 | TODO |  |
| W3F | Q9949 | TODO |  |
| W3F | Q9950 | TODO |  |
