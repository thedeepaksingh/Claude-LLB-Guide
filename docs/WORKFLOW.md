# How This Repository Is Organised and Logged

## Branching

| Branch pattern | Purpose | Merged how |
|---|---|---|
| `main` | Reviewed, stable material only | Merge commits (`--no-ff`) so each major change stays visible in history |
| `setup/<topic>` | Repo structure, docs, tooling | Merged after a read-through |
| `paper/NN-<slug>` | **One branch per paper** (e.g. `paper/01-jurisprudence`) holding all its units, Q&A and revision sheets | Merged to `main` only after you have reviewed it |
| `update/<paper>-<topic>` | Major post-merge change, e.g. a new amendment or a rewritten unit | Merged after review, with a CHANGELOG entry |

Small typo fixes can go straight to the paper branch; anything that changes **law stated, a case's holding, or a section number** is a "major change" and gets its own branch or at least its own CHANGELOG line.

## Time-stamping and logging

1. Every commit carries git's own timestamp.
2. `CHANGELOG.md` records each major change with an **IST timestamp**, the branch, and what changed.
3. Every content file starts with a header: *Last updated*, *Law stated as on*, and a *Verify before exam* flag.
4. Each paper branch is tagged when a review-ready version exists: `sem1-paperN-<slug>-vX.Y`.

## Commit message convention

```
type(scope): short summary

type  = content | fix | law-update | structure | docs
scope = paper-1 … paper-5, or repo
```

Examples: `content(paper-1): add Unit 3 analytical school`, `law-update(paper-4): note BNS s.152 replaces IPC s.124A`.

## File layout (target)

```
sem-1/
  paper-1-jurisprudence/
    README.md            ← unit index + one-page revision sheet
    unit-1-… … unit-7-…  ← background, theory, cases, criticism, current relevance, Q&A
    case-and-quote-bank.md
    glossary.md
  paper-2-constitutional-law/
  paper-3-law-of-torts/
  paper-4-law-of-crimes/
  paper-5-contract/
docs/
  00-syllabus-map.md
  01-gaps-and-open-questions.md
  WORKFLOW.md
CHANGELOG.md
```

## Standard anatomy of a unit file

1. Syllabus mapping and exam note
2. Background and evolution
3. Core concepts and definitions
4. Cases (citation, facts, ratio, which point it proves)
5. Statutory / constitutional link (old section → current section where relevant)
6. Criticism and evaluation
7. Current relevance and recent developments
8. Model Q&A (long, short note, very short)
9. Quick-revision box and examiner keywords
10. Verification checklist
