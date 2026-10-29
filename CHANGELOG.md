# Changelog

All times are **IST (UTC+05:30)**. Newest first.

## 2026-10-28

### 22:10 — `paper/01-jurisprudence` (question bank)
- Added `sem-1/paper-1-jurisprudence/question-bank/`: **183 model answers in the real CCSU pattern** (confirmed on all 20 papers, Dec 2022–2025): Section A, 4 marks, ≤ 75 words, **110 answers** (A-01 to A-110, 50–73 words); Section B, 10 marks, ≤ 200 words, **49 answers** (B-01 to B-49, 179–199 words); Section C, 20 marks, in detail, **24 answers** (C-01 to C-24, 951–1,539 words). Every answer prints its word count; a script checks the limits.
- **All 52 previous questions** (Dec 2022, 2023, 2024, 2025) are mapped to answers in the question-bank `README.md`; a script confirmed that each mapped answer's own "Asked" line names the right sitting and question number. The README has a topic-frequency table: Austin, the definition of jurisprudence, Pound, Duguit and American realism came up in every sitting.
- Added `jurists-and-cases-digest.md` (51 thinker rows and 50 cases, each with facts, issue, holding and principle), three full mock papers, `answer-review-checklist.md`, `coverage-audit.md` (29 syllabus sub-lines) and `source-verification-log.md` (9 checked groups, 24 corrections, an unchecked list).
- The coverage audit found one gap (no 10-mark answer on Grotius, Hobbes, Locke and Rousseau); added B-49.
- Corrections after checking or re-reading: Austin's positive morality (no master-and-servant example); Hart's "no vehicles in the park" examples (the war-memorial lorry is Fuller's) and the source of "nightmare" and "noble dream"; Bentham's remunerative sanctions; Kelsen's basic norm of international law; Stammler's four principles; an unsupported Kohler quotation; *Dosso* and *Asma Jilani* expanded after a check; Bentham's *Of Laws in General* (published 1970, not 1945).
- Unit files 1–7: the guessed three-tier Q&A (10–15, 5 and 2 marks) was replaced by links to the real answers, and each "how this unit is examined" paragraph by the list of past questions that came from that unit. Paper I `README.md`: exam pattern marked confirmed; guessed "high-probability topics" replaced by a pointer to the frequency table.
- **No official marking scheme was found.** Every rubric is marked "(mine)". Dates and works of the thinkers, and the details of several foreign cases, are from memory (marked † in the digest; listed in the log).
- Status: **draft for review.** Not merged to `main`.

## 2026-10-27

### 23:31 — `paper/01-jurisprudence` (draft, awaiting review; branch head `4e18dc6`)
- **Added Paper I (Jurisprudence – I, K-1001), all seven units**, one file each: introduction; natural law (Stammler, Kohler); analytical school (Austin, Kelsen, Hart); historical school (Savigny, Maine); sociological school (Pound, Duguit); American realism; Marxist economic approach.
- Each unit has: background, concepts, cases, criticism, current developments, comparison tables, quick-revision box, model Q&A (long / short note / very short) and a verification checklist.
- Added `case-and-quote-bank.md` (36 Indian cases, foreign cases, safe-quotation table), `glossary.md`, and the paper `README.md` with a thinker revision sheet and answer-writing template.
- **Law-currency checks done today (web-verified):** Uttarakhand UCC in force 27 Jan 2025; Jallikattu Constitution Bench 18 May 2023; *Davinder Singh* 1 Aug 2024 (2024 INSC 562); *Property Owners Association* 5 Nov 2024; *Dr. Balram Singh* 25 Nov 2024; *Janhit Abhiyan* 7 Nov 2022; four Labour Codes in full force 21 Nov 2025 (replacing 29 laws, including the Minimum Wages Act 1948 and Industrial Disputes Act 1947).
- **Unresolved, flagged in the files:** Sabarimala nine-judge reference (reserved 14 May 2026; could not confirm whether pronounced); SCC citations for *Janhit Abhiyan*, *Property Owners Association*, *Balram Singh* and *Jallikattu*.
- **Corrections made during drafting:** a misquoted Austin line; an unsupported claim about Austin and Indian codification; Duguit's title list; a stale reference to labour laws replaced by the Labour Codes.
- **Not done:** exam-pattern calibration and past-paper frequency analysis (waiting on question papers; see `docs/01-gaps-and-open-questions.md`, A1).

### 23:12 — `setup/repo-structure`
- Added `docs/00-syllabus-map.md`: official CCSU LL.B. Semester I syllabus (papers K-1001 to K-1005) mapped unit by unit, with source URL and retrieval date.
- Added `docs/01-gaps-and-open-questions.md`: items still needed from the student (question-paper pattern, syllabus version for session, internals, medium), currency issues in the syllabus (IPC → BNS, sedition, adultery, Consumer Protection Act 2019), and honest limits.
- Added `docs/WORKFLOW.md`: branching, logging, commit-message convention, file layout.
- Rewrote `README.md` with the paper status table.
- Plan: **one paper at a time**, one branch per paper, merged to `main` only after review.

### Papers in progress
| Paper | Branch | Status |
|---|---|---|
| I — Jurisprudence – I | `paper/01-jurisprudence` | Draft complete, awaiting review |
| II — Constitutional Law – I | `paper/02-constitutional-law` | Not started |
| III — Law of Torts | `paper/03-law-of-torts` | Not started |
| IV — Law of Crimes – I | `paper/04-law-of-crimes` | Not started |
| V — Contract – I | `paper/05-contract` | Not started |
