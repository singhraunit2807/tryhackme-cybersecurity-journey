# TryHackMe — Worked-On Rooms & Study Notes

A collection of rooms where meaningful investigation or task-solving work was recorded in earlier study sessions. This is a **working notebook**, not a completion list.

> **Status key**
> - **Partial / in progress** — progress was recorded, but completion was not confirmed.
> - **Attempted / unresolved** — investigation took place, but one or more tasks remained open.
> - **Reference only** — the room was mentioned, but detailed notes were not recovered.

> **Answer key**
> - **Recovered** — answer text was found in earlier discussion.
> - **Unverified** — no clear acceptance confirmation was recovered.
> - **Disputed** — the answer was rejected or challenged; do not rely on it.
> - **Unresolved** — no dependable answer was recovered.

## Contents

- [Room index](#room-index)
- [Recovered answers](#recovered-answers)
- [Investigation notes](#investigation-notes)
- [Accuracy and safety](#accuracy-and-safety)

## Room index

| Room | Historical status | Topics / work recovered |
|---|---|---|
| DSI Cyber 101 | In progress / unresolved | Account investigation, clue analysis, login endpoint |
| Defensive Security Intro | Partial — 75% recorded | Attack IP and defensive-security tasks |
| Governance & Regulation | Partial — 93% recorded | Compliance, healthcare, procedures, risk management, PCI |
| Secure Network Architecture | Partial — about 56–68% recorded | DHCP snooping and network security configuration |
| Rabbit Hole | In progress — about 75% recorded | Port scan, web investigation, second-order SQL injection, SSH |
| Grand Larceny Auto II | Partial — about 50% recorded | Multi-step investigation and flag tasks |
| Athens | Attempted / unresolved | JPEG extraction and clue investigation |
| Operation Reroute | Attempted; completion not established | SSH / hostname task |
| Pyramid of Pain | Partial — 5% recorded | File identification / threat-intelligence task |
| Dead Endpoint | Partial / unresolved | API endpoint and cache investigation |
| Advent of Cyber 2022 — Task 16 | Partial — 42% recorded | Memory forensics and process investigation |
| Advent of Cyber 2022 — Task 17 | Partial — 44% recorded | Task started; exact answers not recovered |
| Packed Light — Hacker Holidays 2026, Day 4 | Attempted / unresolved | Packet capture, cookie analysis, encoding hypothesis |
| BreachBlocker Unlocker | Attempted; answers unverified | CODE, HOPFLIX, and BANK flag prompts |
| GameBuzz | Attempted | User/root flag tasks and walkthrough discussion |
| Different CTF — title not recovered | Attempted / unresolved | Port scan and hidden-directory investigation |
| Theseus | Reference only | Room mentioned; task-level notes not recovered |
| Hacker Holidays | Reference only | Room mentioned; detailed notes are under Packed Light above |

*Percentages are historical snapshots from the conversations, not live TryHackMe progress.*

## Recovered answers

The following answer strings were recovered from earlier assistant messages. They are preserved as study leads, **not guaranteed accepted answers**. Check the original task wording before using them.

### Offensive Security Intro

| Prompt context | Recovered answer | Status |
|---|---|---|
| Name associated with the account | `Sarah` | Unverified |
| Account number | `8881` | Unverified |
| Bank transfer URL | `http://fakebank.thm/bank-transfer` | Unverified |
| Required protection for the transfer page | `Require login` | Unverified |
| Deposit amount discussed | `$2,000` | Unverified |
| Final challenge flag | Not included | Flags are not published |

### DSI Cyber 101

| Prompt context | Recovered answer | Status |
|---|---|---|
| Task 1 | `False` | Unverified |
| Username discovered during investigation | `dave.saunders` | Investigation lead |
| Attacker / clue name | `ShadowFigures` | Unverified |
| Login endpoint | `/login` | Unverified |
| Account-lockout / final flag task | Not recovered | Unresolved |

### Operation Reroute

| Prompt context | Recovered answer | Status |
|---|---|---|
| SSH / hostname answer | `sekureapp.thm` | Recovered; acceptance not confirmed |

### Pyramid of Pain

| Prompt context | Recovered answer | Status |
|---|---|---|
| Task 2 filename | `Sales_Receipt 5606.xls` | Recovered; recheck task wording |

### Advent of Cyber 2022 — Task 16

| Prompt context | Recovered answer | Status |
|---|---|---|
| Windows build | `10.0.18362` | Recovered; recheck task wording |
| Suspicious executable | `mysterygift.exe` | Needs validation; an earlier note also showed `mysterygift.ex` |
| Process ID | `2040` | Recovered; acceptance not confirmed |
| Number of files | `16` | Recovered; acceptance not confirmed |
| Remaining question | Not recovered | Unresolved |

## Investigation notes

### DSI Cyber 101
- Investigated the account name `dave.saunders`, the `ShadowFigures` clue, and the `/login` endpoint.
- Account-lockout / final flag step remained pending.

### Defensive Security Intro
- Attack IP recorded in the earlier discussion: `32.122.195.63`.
- Task 4 flag was supplied by the user; it is intentionally not reproduced here.
- The previously suggested Task 3 URL was disputed and is excluded.

### Governance & Regulation
- Topics covered included regulation, healthcare, review/update procedures, risk management, PCI/cardholder data, risk treatment, and availability.
- Some Task 6 answers were challenged or uncertain; they need checking against the room.

### Secure Network Architecture
- DHCP snooping concepts discussed: DHCP binding database, DHCPRELEASE handling on an untrusted interface, and MAC address.
- Other configuration and flag details were uncertain.

### Rabbit Hole
- Completed investigation steps recorded: port scan, website investigation, second-order SQL injection discovery, admin login query capture, and an SSH connection attempt.
- Remaining work at the last recorded point: validate lab credentials, obtain the authorized admin shell, and finish the flag task.
- No credentials or challenge flag are included.

### Grand Larceny Auto II
- Multi-step investigation and flag tasks were discussed.
- A proposed flag was rejected; another candidate had no acceptance proof. Neither is published.

### Athens
- JPEG extraction and the clues `shore` and `KingAegeus` were investigated.
- A proposed flag was rejected. The clue strings are investigation notes, not verified answers.

### Operation Reroute
- SSH / hostname task context was discussed.
- The room appeared at 0% in the captured progress view; it is not marked complete.

### Dead Endpoint
- Investigated endpoint: `/api/albums/1/export`.
- Cache path discussed: `/srv/gallery/.cache/.indexd`.
- A dependable SHA-256 answer was not recovered.

### Packed Light — Hacker Holidays 2026, Day 4
- Investigated packet capture data and cookie `hotel_sess_state`.
- Base64/XOR decoding and packet ordering were considered as hypotheses.
- The proposed flag was rejected; the exact solution requires the original capture.

### BreachBlocker Unlocker, GameBuzz, and unnamed CTF
- CODE / HOPFLIX / BANK prompts, user/root flag tasks, and port-scan / hidden-directory investigation were discussed.
- Earlier answer candidates were not independently confirmed, so they are not listed as solutions.

## Accuracy and safety

- “Worked on” means meaningful investigation was recorded; it does not mean the room was completed.
- Progress percentages are historical and may no longer reflect the current room state.
- Recovered assistant answers are labelled by confidence; unverified strings must be checked before use.
- Disputed or rejected answers are not presented as correct.
- Challenge flags, passwords, credentials, API keys, access tokens, and other sensitive access details are intentionally excluded.
- Full walkthroughs should be expanded only when the original task prompts, screenshots, or reliable lab notes are available.
