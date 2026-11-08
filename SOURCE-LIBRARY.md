# School Mathematics — original source library

**Purpose:** This repository is a teacher-facing collection of source books, not the student-facing Irish school mathematics textbook. No source chapter is automatically assigned to students.

**Our authored PreTeXt book:** [ronandownes/book](https://github.com/ronandownes/book), publishing at https://ronandownes.github.io/book/ when deployed.
**Our interactive Maths apps:** https://ronandownes.github.io/maths/

## Imported PreTeXt source collections

The following five upstream source collections are already preserved under `sources/` with upstream commit records:

| Name | Source folder | Original source | Published edition / variants |
|---|---|---|---|
| Core Mathematics — Katherine Yoshiwara and collaborators | `sources/core-math/` | https://github.com/byoshiwara/core-math | https://yoshiwarabooks.org/core-math/ |
| Elementary Algebra — Katherine and Bruce Yoshiwara | `sources/elem-alg/` | https://github.com/byoshiwara/elem-alg | https://yoshiwarabooks.org/elem-alg/ |
| Intermediate Algebra — Katherine Yoshiwara | `sources/int-algebra/` | https://github.com/byoshiwara/int-algebra | https://yoshiwarabooks.org/int-algebra/ and https://yoshiwarabooks.org/int-algebra-ww/ |
| Modeling, Functions, and Graphs — Katherine Yoshiwara | `sources/mfg/` | https://github.com/byoshiwara/mfg | https://yoshiwarabooks.org/mfg-no-webwork/chap2.html (requested edition), https://yoshiwarabooks.org/mfg/ and https://yoshiwarabooks.org/mfg-ww/ |
| Trigonometry — Katherine Yoshiwara | `sources/trig/` | https://github.com/byoshiwara/trig | https://yoshiwarabooks.org/trig/ |

**ORCCA: Open Resources for Community College Algebra**, Portland Community College faculty:
- Source: https://github.com/PCCMathSAC/orcca
- Target source folder: `sources/orcca/` (added by the import-and-publish workflow on the next successful source import; confirm folder and UPSTREAM-COMMIT.txt before claiming completion)
- Three published parts: https://spot.pcc.edu/math/orcca/ed3/html/part-linear-equations-and-lines.html (Part I, 3rd edition); https://spot.pcc.edu/math/orcca/ed2/html/part-preparation-for-stem.html (Part II, 2nd edition); https://spot.pcc.edu/math/orcca/ed2/html/part-preparation-for-college-algebra.html (Part III, 2nd edition).
- Licence: CC BY 4.0 with specific attribution, readable/accessibly presented maths, and **trademark/cover/branding exclusions**; read its README before adaptation. The upstream 3rd-edition source remains work in progress.

**Applied Discrete Structures** — Alan Doerr and Kenneth Levasseur:
- Source: https://github.com/klevasseur/ads (PreTeXt, upstream default branch `master`).
- Original website: https://faculty.uml.edu/klevasseur/ads/ads.html ; current edition: https://discretemath.org/
- Source import target: `sources/ads/`, with an upstream commit record. The import-and-build workflow will attempt to render its web edition separately.
- Licence: Creative Commons Attribution-NonCommercial-ShareAlike 3.0 United States; preserve attribution and do not treat as unrestricted commercial material.
- Content: 16 chapters, including sets, combinatorics, discrete probability, logic, recursion and graph theory. These are **reference content only** until expressly curated for the authored book.

## External PreTeXt references — not locally imported editable source

- **Discrete Mathematics for Computer Science**, L. J. Miller: https://icsatkcc.github.io/Discrete-Math-for-Computer-Science/section1_2-basic_Set_Operations.html
  - Full reference: https://icsatkcc.github.io/Discrete-Math-for-Computer-Science/
  - Licence: CC BY-NC-SA 4.0 plus separately attributed third-party material and WeBWorK exercise licences; see https://icsatkcc.github.io/Discrete-Math-for-Computer-Science/colophon-1.html
  - Its expected original GitHub source repository is presently unavailable via GitHub API. The published HTML is **not** editable PreTeXt source; retain a bibliographic link until upstream source can be verified.
- **Discrete Mathematics: An Open Introduction**, Oscar Levin: https://discrete.openmathbooks.org/dmoi4.html
  - Upstream source: https://github.com/oscarlevin/discrete-book
  - Licence varies with edition; the fourth edition has a non-commercial provision. Review before any adaptation or merging.
- **Modeling, Functions, and Graphs — Algebra Toolkit**: https://byoshiwara.github.io/MFG-toolkit/ (related supplemental work; source and licence to verify, not a sixth standalone textbook imported here).
- **Yoshiwara editions with WeBWorK:** https://yoshiwarabooks.org/mfg-ww/ and https://yoshiwarabooks.org/int-algebra-ww/ (alternate published editions, not necessarily separate source books).

## What belongs in the student book

Keep **one curated PreTeXt book** at ronandownes/book, ordered by Irish school mathematics topics. In each topic, include only the definitions, short explanations, worked examples, investigations and carefully selected exercises that serve the learning outcomes. Record an upstream source reference for reused material; do not copy every source chapter into a student book. Mark optional Leaving Certificate or teacher enrichment content rather than presenting it to all Junior Cycle pupils.

## Reuse rules

A publicly accessible book is not automatically free to relicense or sell. Licences differ across books and sometimes across assets/exercises within a book. Preserve copyright, licences, source links and author acknowledgements. NC and SA requirements may constrain derivative works or commercial publishing. Do not merge incompatible licensed content as if a single blanket licence applied. Where reuse rights are unclear, link to the original and develop our own explanation instead.

## Build status

Read https://github.com/ronandownes/pretext/blob/gh-pages/build-status.txt for the individual Yoshiwara book build results. A green GitHub Actions workflow alone is not evidence that every book rendered.
