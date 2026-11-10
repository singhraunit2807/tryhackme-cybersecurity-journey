# TryHackMe Progress Tracker

This tracker consolidates room names found in the available older ChatGPT conversation history. It is deliberately conservative: solving questions or receiving a suggested flag does not automatically mean the room was completed.

| Room | Recovered status | Evidence / notes |
|---|---|---|
| Offensive Security Intro | Completed | Explicitly recorded as completed in earlier progress review. |
| DSI Cyber 101 (DSICYBER101) | Partial / attempted | User worked through the room; full completion not established. |
| Grand Larceny Auto II | Attempted / unconfirmed | Flags or answers were discussed, but acceptance/completion is not confirmed. |
| Athens | Attempted; unresolved | A flag was reported as rejected. |
| Operation Reroute | Attempted; progress unclear | An answer was recovered; completion not established. |
| Pyramid of Pain | Partial | Partial progress recorded. |
| Rabbit Hole | In progress (~75% at last saved point) | Enumeration, website investigation, second-order SQLi discovery, admin login query capture, and an SSH attempt completed. Admin shell and final flag remained pending. |
| Dead Endpoint | Partial / attempted | Partial evidence recovered; completion not established. |
| Advent of Cyber 2022 | In progress / completion unconfirmed | Multiple later tasks were worked through (including Tasks 19–30); an earlier record showed 42% and Task 16 unresolved. Do not mark the full event complete without checking the platform. |
| Adventure Time | Attempted / unconfirmed | Room page showed 0% when discussed; five candidate flags were supplied but user acceptance was not confirmed. |
| OPSEC | Attempted / partial | OPSEC questions and a flag were discussed; room completion not confirmed. |
| Overheard at Breakfast | Attempted / unconfirmed | Flag discussed, but the room page had shown 0% progress. |
| Crocc Crew | Partial (50%) | Room progress was shown as 50%; five flags were discussed. |
| Handbook for the Recently Compromised | Attempted (0% at the time) | Room page showed 0%; answers were requested. |
| Theseus | Mentioned; status unknown | Appeared in an older list of rooms the user had worked on; no reliable completion evidence recovered. |
| Hacker Holidays | Mentioned; status unknown | Appeared in an older list of rooms the user had worked on; no reliable completion evidence recovered. |
| TryHackMe Onboarding | Mentioned; status unknown | Mentioned among earlier TryHackMe activity; no reliable completion evidence recovered. |

## Status definitions

- **Completed:** Completion was explicitly recorded or shown.
- **In progress / Partial:** There is evidence of active work or a progress percentage below 100%.
- **Attempted / unconfirmed:** Questions, flags, or answers were discussed, but accepted completion was not established.
- **Mentioned; status unknown:** The room name appeared in prior history, but there is not enough evidence to claim it was attempted or completed.

## Important follow-up checks

1. Check the TryHackMe profile's completed-room list and compare it against this tracker.
2. Confirm whether the candidate answers for Athens, Grand Larceny Auto II, Operation Reroute, Adventure Time, and Overheard at Breakfast were accepted.
3. Resume Rabbit Hole from the saved pending step; do not repeat the completed enumeration and SQLi discovery steps.
4. Revisit Advent of Cyber 2022 Task 16 and confirm the overall event completion status.
