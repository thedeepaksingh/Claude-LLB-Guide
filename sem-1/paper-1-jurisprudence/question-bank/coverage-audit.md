# Paper I · Coverage Audit (K-1001 Jurisprudence – I, Legal Theory)

> **Last updated:** 2026-10-28 (IST) · **Law stated as on:** 2026-10-28 · **Branch:** `paper/01-jurisprudence`
> **What this is.** A line-by-line check of the CCSU syllabus against the question bank: which syllabus line is answered where, at which mark level (4, 10, 20), and with which cases. It also lists what is **not** covered and why. Most of it was produced by a script from the answer files, so the counts and links cannot drift from the answers; the script also checks every past question, every anchor and every word limit.
> **Companion files:** [`README.md`](README.md) (index and past-paper map) · [`source-verification-log.md`](source-verification-log.md) (what was checked) · [`jurists-and-cases-digest.md`](jurists-and-cases-digest.md) · [`answer-review-checklist.md`](answer-review-checklist.md) · [mock exams](mock-exam-1.md)

---

## 1. Your definition of "done", item by item

| # | Requirement | Status | Evidence and honest limits |
|---|---|---|---|
| 1 | Every prescribed syllabus topic and subtopic is covered | **Done** | Section 4 maps all 7 syllabus lines through 29 sub-lines. 28 of 29 have answers at all three levels (4, 10 and 20 marks). The rest are covered as follows: *X Comparison of all the schools (cross-unit)*: no 10-mark answer (a comparison of all the schools is asked at 4 marks, through A-69, A-87 and A-100, and at 20 marks, through C-23). Every answer is assigned to at least one syllabus line (no orphans). |
| 2 | Every question in the question bank has a complete model answer | **Done** | 183 answers: 110 four-mark, 49 ten-mark, 24 twenty-mark. A script confirms every ID has an answer anchor and a printed word count; all Section A answers are 50–73 words (limit 75) and all Section B answers are 179–199 words (limit 200). Section C runs 951–1,539 words as a full reference. |
| 3 | Short, medium and long answers matched to the applicable exam pattern | **Done** | Pattern confirmed on all 20 papers (5 subjects × December 2022–2025): Section A 4 marks / 75 words; Section B 10 marks / 200 words; Section C 20 marks / "in detail". The first version of the Paper I notes used a guessed three-tier pattern; it was replaced on 28 October 2026. |
| 4 | Cases include material facts, issues, holdings, principles and later developments where relevant | **Done, with marked gaps** | [Digest](jurists-and-cases-digest.md): 50 cases and 51 thinker rows. Every entry has a facts, issue, holding and principle line (50, 50, 50 and 50 of 50); for 4 of them the facts line says I could not confirm the facts and left them out. Later developments are given for 21/50 (only where there are any). Gaps: the facts of *Collector of Madura*, *Ramalakshmi Ammal*, *Hurpurshad* and *LIC v. CERC* could not be confirmed and are left out; the facts of *Matovu* and *Madzimbamuto* and the benches are marked †. |
| 5 | Statutory provisions and current law verified against authoritative sources | **Partly done** | Checked: *Dosso*, *Asma Jilani*, *Property Owners Association*, *Balram Singh*, the Labour Codes, the *Puttaswamy* overruling of *ADM Jabalpur*, the *Joseph Shine* citation. **Not** checked: the items in section 4 of the [log](source-verification-log.md), notably the BNS counterparts of ss. 377, 497 and 499–500 IPC, the 2023 modification of the *Common Cause* guidelines, and the thinkers' dates and works. Jurisprudence has few statutes; most of its "authorities" are books. |
| 6 | Previous papers and the actual university marking scheme have been checked | **Papers: done. Marking scheme: not found** | All four Paper I sittings (52 questions) are transcribed and every one is mapped to an answer (section 5). The scheme is not published in the places I could read. Every mark split in the bank is labelled "(mine)". |
| 7 | A full mock examination and answer-review checklist | **Done** | [Mock 1](mock-exam-1.md), [Mock 2](mock-exam-2.md), [Mock 3](mock-exam-3.md) (each 100 marks in the real pattern, with an answer key) and the [checklist](answer-review-checklist.md). |
| 8 | Final coverage audit, source verification and change log updated | **Done** (this file, the log, and `CHANGELOG.md`) | Update the three again whenever the law changes. |

---

## 2. Where each answer series lives

| Series | Files | IDs |
|---|---|---|
| Section A (4 marks) | `section-a-part-1-units-1-2.md` · `section-a-part-2-unit-3.md` · `section-a-part-3-units-4-5.md` · `section-a-part-4-units-6-7.md` | A-01…32 · A-33…56 · A-57…87 · A-88…110 |
| Section B (10 marks) | `section-b-part-1-units-1-2.md` · `section-b-part-2-unit-3.md` · `section-b-part-3-units-4-5.md` · `section-b-part-4-units-6-7.md` | B-01…13, B-49 · B-14…24 · B-25…37 · B-38…48 |
| Section C (20 marks) | `section-c-part-1-units-1-2.md` · `section-c-part-2-unit-3.md` · `section-c-part-3-units-4-5.md` · `section-c-part-4-units-6-7-cross.md` | C-01…07 · C-08…12 · C-13…18 · C-19…24 |
| Digest | `jurists-and-cases-digest.md` | thinkers (Part 1), cases 1…50 |
| Mocks | `mock-exam-1.md` · `-2` · `-3` | 3 papers |

A-01…A-110, B-01…B-49 and C-01…C-24 include all 52 past questions (section 5) and fill every other syllabus line.

---

## 3. Counts by unit

Each answer is assigned to one **primary** unit.

| Unit | Syllabus unit | A (4) | B (10) | C (20) | Digest cases |
|---|---|---|---|---|---|
| 1 | Introduction: definition, nature, scope, importance | 15 | 6 | 4 | 1–11 (shared with unit 1) |
| 2 | Natural law; revival (Stammler, Kohler) | 17 | 8 | 3 | 1–11 (shared with unit 2) |
| 3 | Analytical school: Austin, Kelsen, Hart | 24 | 11 | 5 | 12–21 |
| 4 | Historical school: Savigny, Maine | 14 | 6 | 3 | 22–27 |
| 5 | Sociological school: background; Pound; Duguit | 17 | 7 | 3 | 28–40 |
| 6 | American modern realism | 13 | 6 | 2 | 41–43 |
| 7 | Economic approach: Marxist approach | 10 | 5 | 2 | 44–50 |
| X | Cross-unit comparisons (C-23, C-24) | 0 | 0 | 2 | all |
| | **Total** | **110** | **49** | **24** | 50 |

---

## 4. Syllabus line by line

| Syllabus line | A (4) | B (10) | C (20) | Digest cases (no.) |
|---|---|---|---|---|
| **1.1 Meaning and definition of jurisprudence; definition of law** | A-01…09 | B-06 | C-01, C-04 | – |
| **1.2 Kinds of jurisprudence: general and particular, expositorial and censorial** | A-10, 11 | B-04 | C-03 | – |
| **1.3 Nature and scope: science or art; subject-matter** | A-13 | B-05 | C-02 | – |
| **1.4 Importance and utility of the study** | A-14 | B-01, 02 | C-02 | – |
| **1.5 Relation to other disciplines; law and morality** | A-12, A-15 | B-03, B-05 | C-24 | 1–11 |
| **2.1 Classical natural law: Greeks, Stoics, Cicero, Aquinas** | A-16, A-19…22 | B-07, B-11 | C-05 | 1, 2 |
| **2.2 Reason-based natural law and social contract: Grotius, Hobbes, Locke, Rousseau** | A-23, 24 | B-07, B-49 | C-06 | – |
| **2.3 Revival: Stammler and Kohler** | A-25, 26 | B-08…10 | C-07 | 10 |
| **2.4 Later natural law: Fuller, Finnis, Rawls, Radbruch** | A-27…30 | B-08, B-12 | C-07 | 1–3 |
| **2.5 Criticism of natural law; Indian ideas (Manu, dharma)** | A-17, 18, A-31, 32 | B-13 | C-07 | 14, 15 |
| **3.1 Bentham and the rise of positivism** | A-33, 34 | B-19 | C-08 | – |
| **3.2 Austin: command, sovereign, sanction, classification, international law** | A-35…40 | B-17, B-21, 22 | C-08, 09 | 12–14 |
| **3.3 Kelsen: Pure Theory, hierarchy, Grundnorm, validity and efficacy** | A-41…47 | B-14, 15, B-18, B-23 | C-10 | 18–21 |
| **3.4 Hart: primary and secondary rules, recognition, internal point of view, open texture** | A-48…52, A-56 | B-16, B-20, B-24 | C-11 | – |
| **3.5 Hart's debates: with Fuller, Devlin, Dworkin** | A-53…55 | B-12 | C-11, C-24 | 2, 3, 5 |
| **3.6 The analytical school as a whole** | A-33 | B-14 | C-12 | 12–17 |
| **4.1 Precursors and Savigny: Volksgeist, codification controversy, criticism** | A-57…61, A-67 | B-25…27 | C-13 | 22–24 |
| **4.2 Maine: status to contract, stages, fictions, patriarchal theory, village communities** | A-62…66, A-68 | B-28, 29 | C-14, 15 | 25–27 |
| **4.3 Historical school: assessment, comparison with analytical school, India** | A-69, 70 | B-30 | C-12, C-15 | 22–24 |
| **5.1 Background and characteristics: Comte, Durkheim, Jhering, Ehrlich** | A-71…74, A-87 | B-32, 33, B-37 | C-17 | 28, 34 |
| **5.2 Pound: social engineering, interests, jural postulates, criticism, India** | A-79…86 | B-34…36 | C-16 | 28–40 |
| **5.3 Duguit: social solidarity, State, sovereignty, property** | A-75…78 | B-31 | C-18 | 35, 44–46 |
| **6.1 Holmes and Gray: prediction theory, bad man, courts as source of law** | A-88…92 | B-38, 39 | C-19 | 41, 42 |
| **6.2 Llewellyn, Frank and Scandinavian realism** | A-93…97 | B-40 | C-19 | – |
| **6.3 Features, criticism and contribution of realism; India** | A-98…100 | B-41…43 | C-19, 20 | 43 |
| **7.1 Marx and Engels: base and superstructure, class, withering away** | A-101…105 | B-44, 45 | C-21 | 44, 47 |
| **7.2 Lenin, Pashukanis; criticism of the Marxist theory** | A-106…108 | B-46, B-48 | C-21 | 46, 47 |
| **7.3 Economic analysis of law: Coase, Calabresi, Posner** | A-109, 110 | B-47 | C-22 | 48–50 |
| **X Comparison of all the schools (cross-unit)** | A-69, A-87, A-100 | – | C-23 | – |

The digest case numbers are those in Part 2 of the [digest](jurists-and-cases-digest.md); a dash means no case is needed for that line.

---

## 5. Previous papers

All **52** questions of the four sittings (20 in Section A, 12 in Section B, 20 in Section C) are mapped to a model answer in the [README](README.md#past-map). A script confirmed that: every question exists in the transcription; the mapped answer exists and is in the right section (A, B or C); and 
the answer's own "Asked" line names the sitting and question number in every case.

| Sitting | A | B | C |
|---|---|---|---|
| Dec 2025 | [A-101](section-a-part-4-units-6-7.md#a-101), [A-41](section-a-part-2-unit-3.md#a-41), [A-33](section-a-part-2-unit-3.md#a-33), [A-59](section-a-part-3-units-4-5.md#a-59), [A-76](section-a-part-3-units-4-5.md#a-76) | [B-01](section-b-part-1-units-1-2.md#b-01), [B-15](section-b-part-2-unit-3.md#b-15), [B-38](section-b-part-4-units-6-7.md#b-38) | [C-03](section-c-part-1-units-1-2.md#c-03), [C-14](section-c-part-3-units-4-5.md#c-14), [C-16](section-c-part-3-units-4-5.md#c-16), [C-04](section-c-part-1-units-1-2.md#c-04), [C-06](section-c-part-1-units-1-2.md#c-06) |
| Dec 2024 | [A-17](section-a-part-1-units-1-2.md#a-17), [A-03](section-a-part-1-units-1-2.md#a-03), [A-42](section-a-part-2-unit-3.md#a-42), [A-34](section-a-part-2-unit-3.md#a-34), [A-75](section-a-part-3-units-4-5.md#a-75) | [B-25](section-b-part-3-units-4-5.md#b-25), [B-08](section-b-part-1-units-1-2.md#b-08), [B-16](section-b-part-2-unit-3.md#b-16) | [C-20](section-c-part-4-units-6-7-cross.md#c-20), [C-16](section-c-part-3-units-4-5.md#c-16), [C-10](section-c-part-2-unit-3.md#c-10), [C-01](section-c-part-1-units-1-2.md#c-01), [C-12](section-c-part-2-unit-3.md#c-12) |
| Dec 2023 | [A-17](section-a-part-1-units-1-2.md#a-17), [A-34](section-a-part-2-unit-3.md#a-34), [A-04](section-a-part-1-units-1-2.md#a-04), [A-76](section-a-part-3-units-4-5.md#a-76), [A-06](section-a-part-1-units-1-2.md#a-06) | [B-03](section-b-part-1-units-1-2.md#b-03), [B-14](section-b-part-2-unit-3.md#b-14), [B-02](section-b-part-1-units-1-2.md#b-02) | [C-16](section-c-part-3-units-4-5.md#c-16), [C-09](section-c-part-2-unit-3.md#c-09), [C-02](section-c-part-1-units-1-2.md#c-02), [C-19](section-c-part-4-units-6-7-cross.md#c-19), [C-10](section-c-part-2-unit-3.md#c-10) |
| Dec 2022 | [A-35](section-a-part-2-unit-3.md#a-35), [A-88](section-a-part-4-units-6-7.md#a-88), [A-17](section-a-part-1-units-1-2.md#a-17), [A-34](section-a-part-2-unit-3.md#a-34), [A-36](section-a-part-2-unit-3.md#a-36) | [B-26](section-b-part-3-units-4-5.md#b-26), [B-02](section-b-part-1-units-1-2.md#b-02), [B-31](section-b-part-3-units-4-5.md#b-31) | [C-05](section-c-part-1-units-1-2.md#c-05), [C-08](section-c-part-2-unit-3.md#c-08), [C-21](section-c-part-4-units-6-7-cross.md#c-21), [C-16](section-c-part-3-units-4-5.md#c-16), [C-14](section-c-part-3-units-4-5.md#c-14) |

---

## 6. What is not covered, and why

| Topic | Why not (or how far) |
|---|---|
| Legal concepts: rights and duties, ownership, possession, legal personality, liability | They belong to the second jurisprudence paper, not to this syllabus. |
| Scandinavian realism | Only at 4 marks (A-97): the syllabus names *American* modern realism. |
| Critical legal studies, feminist jurisprudence, Nozick, Gramsci, Althusser | Not in the syllabus. Rawls, Dworkin and Raz appear only where they sharpen a named topic (natural law revival; Hart's debates). |
| Indian jurisprudence (Manu, Kautilya, Ambedkar, Gandhi) | The syllabus does not name them; Manu appears in the past papers, so he is answered at 4 and 10 marks (A-17, A-18, B-13). |
| Hohfeld's analysis and Dias's treatment of sources | Not on this syllabus; they belong with the second paper. |
| The university's own marking scheme | Not found (section 1, item 6). |
| Hindi-medium versions | The questions are bilingual in print; the answers are in English only. |

---

## 7. How this audit was checked

A script (run on the final files) did the following, and stopped at any failure:

1. Parsed every answer anchor and confirmed that A-01…A-110, B-01…B-49 and C-01…C-24 each exist exactly once.
2. Read each printed word count and confirmed A ≤ 75 and B ≤ 200.
3. Confirmed that all 52 past questions are in the transcription and map to an answer of the right section.
4. Confirmed that every answer appears in at least one syllabus line (no orphan answers).
5. Confirmed that the topic-frequency table covers exactly the 52 questions (one question is counted twice, on purpose).
6. Rebuilt this file and the [README](README.md) from those results.

A separate link checker resolves every relative link and anchor in the Paper I folder and in `docs/` (see section 6 of the [log](source-verification-log.md)).

