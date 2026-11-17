# TryHackMe Rooms — Worked On

This file records rooms where meaningful hands-on work was recovered from prior conversations, including partially completed and unresolved rooms. A room appearing here does **not** mean it was completed.

**Public-safety rule:** challenge flags, credentials, passwords, tokens, and sensitive target access details are intentionally omitted. Answers marked uncertain or rejected are not presented as solutions.

## Recovered room notes

| Room | Recovered status | Useful notes recovered |
|---|---|---|
| DSI Cyber 101 | In progress / unresolved | Investigated account `dave.saunders`, the `ShadowFigures` clue, and `/login`. Account-lockout/flag step remained pending. |
| Defensive Security Intro | Partial (75% recorded) | Attack IP recorded as `32.122.195.63`; Task 4 flag was supplied by the user and is intentionally not reproduced here. The Task 3 URL answer was disputed and is excluded. |
| Governance & Regulation | Partial (93% recorded) | Worked through regulation, healthcare, review/update procedures, risk management, PCI/cardholder data, risk treatment and availability. Some Task 6 answers were rejected/uncertain; verify against the room before relying on them. |
| Secure Network Architecture | Partial (about 56–68% recorded) | DHCP snooping concepts discussed: DHCP binding database, DHCPRELEASE handling on an untrusted interface, and MAC address. Other configuration/flag details were uncertain. |
| Rabbit Hole | In progress (about 75% recorded) | Port scan and website investigation completed; second-order SQL injection identified; admin login query captured; SSH attempt made. Remaining work: validate credentials, obtain the authorized lab admin shell, and finish the flag task. |
| Grand Larceny Auto II | Partial (about 50% recorded) | Multi-step investigation and flag tasks discussed. Previously suggested flag was not confirmed; no flag is published. |
| Athens | Attempted / unresolved | JPEG extraction and investigation of the clues `shore` and `KingAegeus` were discussed. A proposed flag was rejected; no flag is published. |
| Operation Reroute | Attempted; completion not established | SSH access/task context was discussed and the hostname answer `sekureapp.thm` was recovered. The room was shown at 0% in the captured progress view, so it is not marked complete. |
| Pyramid of Pain | Partial (5% recorded) | Task 2 filename answer recovered: `Sales_Receipt 5606.xls`. |
| Dead Endpoint | Partial / unresolved | Investigated endpoint `/api/albums/1/export` and cache path `/srv/gallery/.cache/.indexd`. |
| Advent of Cyber 2022 — Task 16 | Partial (42% recorded) | Memory-forensics investigation: Windows build `10.0.18362`, suspicious file `mysterygift.exe`, process ID `2040`, and 16 files were noted. One question remained unresolved. |
| Advent of Cyber 2022 — Task 17 | Partial (44% recorded) | Task was started; exact answers were not reliably recovered. |
| Packed Light (Hacker Holidays 2026, Day 4) | Attempted / unresolved | Investigated a packet capture and a cookie named `hotel_sess_state`; a Base64/XOR hypothesis and packet ordering were discussed. The proposed flag was rejected; exact solution requires the original capture. |
| BreachBlocker Unlocker | Attempted; answers unverified | Three flag prompts (CODE, HOPFLIX, BANK) were worked on. Earlier proposed answers were not independently confirmed and are not published. |
| GameBuzz | Attempted | User/root flag tasks and walkthrough steps were discussed; exact verified answers were not recovered. |
| Different CTF (room title not recovered) | Attempted / unresolved | Port-scan and hidden-directory investigation discussed. Previously suggested flags were not verified and are omitted. |
| Theseus | Mentioned; insufficient recovered detail | Room name appeared in prior history, but no dependable task-level notes were recovered. |
| Hacker Holidays | Mentioned; insufficient recovered detail | Room name appeared in prior history; only the separate Packed Light (Day 4) notes above contain concrete recovered work. |

## Evidence and accuracy policy

- Progress percentages are historical snapshots, not current live progress.
- “Worked on” means meaningful task investigation was recorded; it is not a completion claim.
- Only answers supported by the user's own confirmation or clearly recovered task evidence are retained as usable notes.
- Disputed, guessed, or unverified answers are explicitly marked and must be rechecked before public use.
- No challenge flags, credentials, passwords, API keys, or access tokens are included.
- Add a full task-by-task walkthrough only when the original prompts, screenshots, or reliable notes are available.

## Recovered assistant-provided answers

The following answer strings were recovered from earlier assistant messages. They are included as historical study notes, not as a guarantee that every answer was accepted by TryHackMe. Items with no user acceptance record should be rechecked against the task wording before relying on them.

### Offensive Security Intro

| Task / prompt context | Recovered answer | Confidence note |
|---|---|---|
| Name associated with the account | `Sarah` | Assistant-provided answer; no acceptance record recovered. |
| Account number | `8881` | Assistant-provided answer; no acceptance record recovered. |
| Bank transfer URL | `http://fakebank.thm/bank-transfer` | Assistant-provided answer; no acceptance record recovered. |
| Required protection for the transfer page | `Require login` | Assistant-provided answer; no acceptance record recovered. |
| Deposit amount discussed | `$2,000` | Assistant-provided answer; no acceptance record recovered. |
| Final challenge flag | Not reproduced | Flags are intentionally excluded from this public repository. |

### DSI Cyber 101

| Task / prompt context | Recovered answer | Confidence note |
|---|---|---|
| Task 1 | `False` | Assistant-provided answer; no explicit acceptance record recovered. |
| Username discovered during investigation | `dave.saunders` | Recovered from prior assistant response; later investigation was still pending. |
| Attacker / clue name | `ShadowFigures` | Recovered from prior assistant response; not independently verified. |
| Login endpoint | `/login` | Recovered from prior assistant response; not independently verified. |
| Account-lockout / final flag task | Unresolved | No answer is asserted. |

### Operation Reroute

| Task / prompt context | Recovered answer | Confidence note |
|---|---|---|
| SSH / hostname answer | `sekureapp.thm` | Recovered from earlier assistant answer. Room completion was not established. |

### Pyramid of Pain

| Task / prompt context | Recovered answer | Confidence note |
|---|---|---|
| Task 2 filename | `Sales_Receipt 5606.xls` | Recovered from earlier assistant answer; room was recorded at approximately 5%, so verify the task answer. |

### Advent of Cyber 2022 — Task 16

| Task / prompt context | Recovered answer | Confidence note |
|---|---|---|
| Windows build | `10.0.18362` | Recovered from earlier analysis; task wording should be checked. |
| Suspicious executable | `mysterygift.exe` | Recovered answer; another earlier note had the shortened form `mysterygift.ex`, so use the full extension only after checking the source task. |
| Process ID | `2040` | Recovered from earlier assistant response. |
| Number of files | `16` | Recovered from earlier assistant response. |
| Remaining question | Unresolved | No answer is asserted. |

### Answers deliberately excluded

- **Grand Larceny Auto II:** one proposed flag was explicitly rejected; a later candidate had no acceptance proof. Neither is published.
- **Athens:** the submitted flag was rejected. The clue strings `shore` and `KingAegeus` are retained only as investigation notes, not verified final answers.
- **Rabbit Hole:** target `10.49.148.122` was recorded in prior notes, but valid admin credentials, shell access, and the final flag remained pending. No credentials or flag are published.
- **Dead Endpoint:** endpoint and cache path are retained above; a dependable SHA-256 answer was not recovered.
- **Defensive Security Intro:** Task 3 URL answer was disputed and is intentionally omitted. The user-provided Task 4 flag is not reproduced.
- **Secure Network Architecture, Governance & Regulation, Packed Light, BreachBlocker Unlocker, GameBuzz, and the unnamed CTF:** previous answer candidates were incomplete, disputed, or not independently confirmed; they are not presented as verified solutions.
