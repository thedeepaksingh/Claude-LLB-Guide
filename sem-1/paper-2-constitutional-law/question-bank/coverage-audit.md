# Paper II · Coverage Audit (K-1002 Constitutional Law of India – I)

> **Last updated:** 2026-10-28 21:08 IST · **Law stated as on:** 2026-10-28 · **Branch:** `paper/02-constitutional-law`
> **What this is.** A line-by-line check of the CCSU syllabus against the question bank: which syllabus line is answered where, at which mark level (4, 10, 20), and with which cases. It also lists what is **not** covered and why. It was produced from the files in this folder by a script that fails if any answer ID is left unassigned, so the counts below are exact.
> **Companion files:** [`README.md`](README.md) (index and past-paper map) · [`source-verification-log.md`](source-verification-log.md) (what was checked) · [`leading-cases-digest.md`](leading-cases-digest.md) · [`answer-review-checklist.md`](answer-review-checklist.md)

---

## 1. Your definition of "done", item by item

| # | Requirement | Status | Evidence and honest limits |
|---|---|---|---|
| 1 | Every prescribed syllabus topic and subtopic is covered | **Done** at 4, 10 and 20 marks, with one exception | Section 4 below maps all 5 syllabus items through 25 sub-lines. The only sub-line without a 10- or 20-mark answer is the **right to property** (A-15 only; it is outside the syllabus text and was set once, as a 4-mark question in Dec 2022). |
| 2 | Every question in the question bank has a complete model answer | **Done** | 227 answers: 151 four-mark, 47 ten-mark, 29 twenty-mark. A script confirms every ID has an answer anchor. Word limits are checked by script: every Section A answer is ≤ 75 words (longest 75), every Section B answer ≤ 200 words (longest 198). |
| 3 | Short, medium and long answers matched to the applicable exam pattern | **Done** | Pattern confirmed on all 20 papers (5 subjects × Dec 2022–2025): Section A 4 marks / 75 words; Section B 10 marks / 200 words; Section C 20 marks / "in detail". Section C answers run from 910 to 1,416 words (see section 6 for any below 900). |
| 4 | Cases include material facts, issues, holdings, principles and later developments where relevant | **Done, with marked gaps** | [Digest](leading-cases-digest.md): 93 cases, each with an issue, holding and principle; facts for 91 (the two without facts, *Basheshar Nath* and *AIIMS Students' Union*, are marked †); later developments wherever there are any. Eight case headings are marked **†** (not checked against a law report). |
| 5 | Statutory provisions and current law verified against authoritative sources | **Partly done** | Checked: Arts. 352, 358, 359 (text), BNS mappings, UCC in Uttarakhand, DPDP Rules, several 2022–2026 judgments. **Not** checked: the items listed as unverified in the [log](source-verification-log.md). The log separates "checked", "changed" and "not checked". |
| 6 | Previous papers and the actual university marking scheme have been checked | **Papers: done. Marking scheme: not found** | All 20 papers read. None was found in the university's published material or on the previous-paper sites I could read. Every "Model rubric" is labelled **(mine)**. |
| 7 | A full mock examination and answer-review checklist | **Done** | [Mock 1](mock-exam-1.md), [Mock 2](mock-exam-2.md), [Mock 3](mock-exam-3.md) (each 100 marks in the real pattern) and the [checklist](answer-review-checklist.md). |
| 8 | Final coverage audit, source verification and change log updated | **Done** (this file, the log, and `CHANGELOG.md`) | Update the three again whenever law changes. |

---

## 2. Where each answer series lives

| Series | Files | IDs |
|---|---|---|
| Section A (4 marks) | `section-a-part-1.md` · `-2` · `-3` · `-4` | A-01…37 · A-38…76 · A-77…139 · A-140…151 |
| Section B (10 marks) | `section-b-part-1.md` · `-2` · `-3` | B-01…16 · B-17…32 · B-33…47 |
| Section C (20 marks) | `section-c-part-1-units-1-5.md` · `-2-units-6-8.md` · `-3-units-9-14.md` · `section-c-part-4-gap-fill.md` | C-01…07 · C-08…17 · C-18…24 · C-25…29 |
| Cases | `leading-cases-digest.md` | 1…93 |
| Mocks | `mock-exam-1.md` · `-2` · `-3` | 3 papers |

A-01…15 are the exact 4-mark questions from Dec 2022–2025; A-16…151 are gap-fill questions for every other syllabus line. B and C answers include the past questions (see the map in the [README](README.md)).

---

## 3. Counts by unit

Each answer is assigned to one **primary** unit (cross-references in the answers themselves).

| Unit | Syllabus unit | A | B | C | Cases |
|---|---|---|---|---|---|
| 1 | [Nature of the Constitution: federal structure; form of government](../unit-1-nature-of-constitution.md) | 17 | 5 | 1 | 4 |
| 2 | [Preamble](../unit-2-preamble.md) | 10 | 3 | 1 | 2 |
| 3 | [Fundamental Rights: general (scheme, who can claim, against whom, suspension)](../unit-3-fundamental-rights-general.md) | 15 | 6 | 4 | 11 |
| 4 | [Article 14](../unit-4-article-14.md) | 5 | 2 | 1 | 6 |
| 5 | [Articles 15–18](../unit-5-articles-15-to-18.md) | 11 | 3 | 2 | 6 |
| 6 | [Article 19(1)(a)](../unit-6-article-19-1-a.md) | 9 | 3 | 3 | 12 |
| 7 | [Article 20](../unit-7-article-20.md) | 4 | 3 | 2 | 5 |
| 8 | [Articles 21 and 21A](../unit-8-article-21-21a.md) | 16 | 6 | 5 | 12 |
| 9 | [Articles 23–24](../unit-9-articles-23-24.md) | 7 | 2 | 1 | 4 |
| 10 | [Articles 25–28](../unit-10-articles-25-28.md) | 13 | 3 | 2 | 8 |
| 11 | [Articles 29–30](../unit-11-articles-29-30.md) | 9 | 2 | 1 | 6 |
| 12 | [Article 32 (writs, PIL)](../unit-12-article-32.md) | 12 | 4 | 3 | 7 |
| 13 | [Directive Principles of State Policy](../unit-13-dpsp.md) | 14 | 4 | 2 | 6 |
| 14 | [Fundamental Duties](../unit-14-fundamental-duties.md) | 9 | 1 | 1 | 4 |
| | **Total** | **151** | **47** | **29** | **93** |

| Unit | A (4 marks) | B (10 marks) | C (20 marks) | Digest cases (no.) |
|---|---|---|---|---|
| 1 | A-07–08, A-10, A-12–13, A-16–22, A-146–150 | B-01–02, B-11–13 | C-01 | 1, 3–5 |
| 2 | A-01, A-06, A-11, A-14, A-23–28 | B-03, B-14–15 | C-02 | 2, 8 |
| 3 | A-03, A-05, A-15, A-29–37, A-140, A-143, A-151 | B-16–21 | C-03–05, C-25 | 6–7, 9–17 |
| 4 | A-38–42 | B-09, B-22 | C-06 | 18–23 |
| 5 | A-43–51, A-144–145 | B-23–25 | C-07, C-26 | 24–29 |
| 6 | A-52–60 | B-26–28 | C-08–10 | 30–41 |
| 7 | A-04, A-61–63 | B-04–05, B-29 | C-11–12 | 42–46 |
| 8 | A-09, A-64–76, A-141–142 | B-06, B-30–33, B-47 | C-13–17 | 47–58 |
| 9 | A-77–83 | B-34–35 | C-18 | 59–62 |
| 10 | A-84–96 | B-36–38 | C-19, C-27 | 63–70 |
| 11 | A-97–105 | B-10, B-39 | C-20 | 71–76 |
| 12 | A-106–117 | B-40–43 | C-21–22, C-29 | 77–83 |
| 13 | A-118–131 | B-07, B-44–46 | C-23, C-28 | 84–89 |
| 14 | A-02, A-132–139 | B-08 | C-24 | 90–93 |

---

## 4. Syllabus line by syllabus line

| Syllabus line | A (4) | B (10) | C (20) | Main cases (digest no.) |
|---|---|---|---|---|
| **1(a) Federal structure**: features, unitary bias, "quasi-federal", cooperative and asymmetric federalism, Union of States, residuary powers, pith and substance, Emergency, Art. 356, Union–State commissions | A-07, 08, 16–20, 146–148, 150 | B-01, 02, 13 | C-01 | 1, 3, 4, 5 |
| **1(b) Form of government**: parliamentary system, rule of law, separation of powers, President | A-10, 12, 13, 21, 22, 149 | B-11, 12 | C-01 | 3 |
| **2 Preamble**: text, objectives, "We, the People", part of the Constitution?, amendability, 42nd Amendment, socialist, secular, democratic, republic | A-01, 06, 11, 14, 23–28 | B-03, 14, 15 | C-02 | 1, 2, 8 |
| **3(a) Scheme of Fundamental Rights**; Art. 12; Art. 13 (eclipse, severability, waiver); amendments; basic structure; Arts. 31A–C and Ninth Schedule; Art. 33 | A-29–36, 140, 143 | B-16, 17, 19, 21 (and B-46) | C-04, 05 | 2, 6, 7, 9, 11–16 |
| **3(a) Who can claim**: citizens and non-citizens | A-37 | B-20 | C-03 | – |
| **3(a) Against whom**: State; private persons | A-03, 29 | B-16 | C-03 | 9, 41 |
| **3(a) Suspension**: Arts. 352, 358, 359; martial law (Art. 34) | A-05, 151 | B-18 | **C-25** | 17 |
| **3(a) Right to property** (history; Art. 300A) | A-15 | – | – | – |
| **3(b) Art. 14**: equality before law; reasonable classification; non-arbitrariness; equal pay | A-38–42 | B-09, 22 | C-06 | 18–23 |
| **3(b) Art. 15**: discrimination; special provision; women and children | A-43, 44, 144 | B-23 | C-07, **C-26** | 24, 28 |
| **3(b) Art. 16**: equal opportunity; reservation; creamy layer; EWS; 50%; sub-classification | A-45–49, 145 | B-24 | C-07, **C-26** | 25–27 |
| **3(b) Arts. 17–18**: untouchability; titles | A-50, 51 | B-25 | **C-26** | 29 |
| **3(b) Art. 19(1)(a)**: scope, press, internet, commercial speech, obscenity, defamation, contempt, restrictions in Art. 19(2) | A-52–60 | B-26, 27, 28 | C-08, 09, 10 | 30–41 |
| **3(b) Art. 20**: ex post facto; double jeopardy; self-incrimination | A-04, 61–63 | B-04, 05, 29 | C-11, 12 | 42–46 |
| **3(b) Art. 21**: procedure established by law; livelihood; privacy; dignity; speedy trial; right to die; death penalty; environment; compensation | A-64–71, 74–76, 141, 142 | B-06, 30, 31, 32, 47 | C-13, 14, 15, 16 | 47–58 |
| **3(b) Art. 21A**: right to education; RTE Act | A-09, 72, 73 | B-33 | C-17 | 54, 75 |
| **3(b) Arts. 23–24**: traffic, forced labour, child labour | A-77–83 | B-34, 35 | C-18 | 59–62 |
| **3(b) Art. 25**: conscience, profession, practice, propagation; essential religious practices; reform | A-84–88, 90, 93–96 | B-36, 37 | C-19 | 63, 64, 66, 67, 69 |
| **3(b) Arts. 26–28**: denominations; no tax for religion; religious instruction | A-89, 91, 92 | B-37, 38 | **C-27** | 63–65, 68, 70 |
| **3(b) Arts. 29–30**: language, script, culture; minorities; AMU | A-97–105 | B-10, 39 | C-20 | 71–76 |
| **3(b) Art. 32**: remedy as a right; writs; Art. 226; compensation; PIL | A-106–117 | B-40–43 | C-21, 22, **C-29** | 77–83 |
| **4 DPSP**: nature, classification, importance | A-118–121, 123–127, 130, 131 | B-44 | **C-28** | 24, 84–89 |
| **4 DPSP v Fundamental Rights**: harmony; Arts. 31C, 39(b) | A-128, 129 | B-07, 46 | C-23 | 7, 24, 87, 89 |
| **4 Uniform civil code (Art. 44)** | A-122 | B-45 | (within C-23, C-28) | 84–86 |
| **5 Fundamental Duties**: origin, text, nature, enforcement, 51A(k) | A-02, 132–139 | B-08 | C-24 | 39, 90–93 |

Bold C numbers are the five answers added in this audit (C-25 to C-29) because the syllabus line had no 20-mark answer.

---

## 5. Past-paper coverage

All **52** Paper II questions of December 2022, 2023, 2024 and 2025 (13 per paper) are mapped to an answer at the tier at which they were set, and several are also covered at other tiers. The map is in the [README](README.md#3-past-questions--the-answer-that-covers-them). Papers after December 2025 were not available to me.

---

## 6. What this audit found, and what I did about it

**Gaps found and filled**

| Gap | Fill |
|---|---|
| Suspension of Fundamental Rights was named in the syllabus and set twice at 4 marks but had no 20-mark answer | C-25 |
| Arts. 15–18 as a whole (not only reservation) had no 20-mark answer | C-26 |
| Arts. 26–28 (Art. 25 alone had C-19) | C-27 |
| Directive Principles: nature, classification and importance (C-23 covers the relationship only) | C-28 |
| The writs (C-22 gave them 5 marks' worth) | C-29 |
| Twelve syllabus-adjacent topics with no short answer (Art. 13, Art. 22, preventive detention, Art. 31A, Art. 15(2), Art. 16(1)–(3), pith and substance, residuary powers, Emergency federalism, parliamentary v presidential, Union–State commissions, Art. 34) | A-140…151 |
| The digest header promised issue and principle for every case, but only 13 and 15 of 93 had them | Added to all 93 |

**Not in the CCSU syllabus text but answered** because they sit next to a named Article and are natural short-note topics: Art. 22 and preventive detention (A-141, A-142), Art. 31A (A-143), Art. 34 (A-151), pith and substance, residuary powers.

**Thin spots that remain (so you know where to read more)**
1. **Right to property:** short answer only (A-15).
2. **No case in the digest** for: Art. 22 (A.K. Roy, D.K. Basu are cited in A-141 and A-142 but not digested), pith and substance, Art. 31A, Art. 15(2), Art. 34, residuary powers, the Sarkaria and Punchhi Commissions. These are statute-led topics at the 4-mark level.
3. **Twenty-mark answers shorter than 900 words:** none. Fourteen answers that ran between 550 and 862 words were lengthened on 28 October 2026; the figures come from the current files. The models are references: a handwritten answer will be shorter, and each Section C file says what to keep.
4. **Pending matters** that can change the answers: the nine-judge Sabarimala reference (reserved May 2026; no judgment found), the hijab case (larger bench), the challenge to the Delhi services amendment of 2023, the AMU regular bench, the 50% ceiling challenges, SC/ST creamy layer, State UCC laws other than Uttarakhand, the Waqf (Amendment) Act challenge. Re-check each before the exam.
5. **Language.** The papers are bilingual; the bank is in English only. Hindi technical terms are in the glossary.
6. **Official marking scheme:** not found. The rubrics are mine.

---

## 7. How this audit was produced

1. Read the syllabus line by line ([`../../../docs/00-syllabus-map.md`](../../../docs/00-syllabus-map.md)).
2. Transcribed all 52 Paper II questions from the four papers and mapped each to an answer.
3. Assigned each of the 227 answers and all 93 digest cases to one primary unit with a script that stops if any ID is missing or duplicated.
4. Counted words by script for every answer (A ≤ 75, B ≤ 200).
5. Looked for syllabus lines with no answer at one of the three tiers (section 6).
6. Checked anchors and cross-links (see the [log](source-verification-log.md#6-link-and-anchor-check)).
