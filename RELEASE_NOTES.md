# 2026.10-rc2 - educational review candidate

> **Educational work by a pre-medical student — not medical advice.** Not a clinical protocol, prescription, or patient handout, and not for patient care. See [DISCLAIMER](DISCLAIMER.md).

Revised 27 October 2026 after the rc1 PRs were merged.

This pass corrects newly identified source and software defects and deliberately narrows unsupported clinical/methodological content. Earlier versions remain recoverable in Git history. See PUBLICATION_REVIEW.md for the precise scope and limitations, PROVENANCE.md for author statements, and RELEASE_MANIFEST.json for current-file hashes.

The candidate is not a clinical protocol, validated controller, systematic/scoping review certification, or legal opinion. No repository visibility change is included.

## Applied example set — 28 October 2026
Added 5 topic-specific male/female case pairs, a local copy of the shared anesthesia-options set, two levels of source mapping and an explicit verification standard. The profiles are entirely synthetic; the source checks are scoped and do not certify clinical validity. Existing clinical/manuscript text and PDF exports are preserved.


## 29 October 2026 — Portfolio presentation and reading path

Added a concise reader’s guide, explicit AI-assistance/authorship scope and review-status notes. Linked the portfolio home and corrected navigation wording. This presentation pass preserves substantive manuscripts, casebooks, code and existing exports. Repository visibility is unchanged.

## November 2026 — accuracy and governance review

Dated 5 November 2026.

- **Withdrawn historical figures:** HISTORICAL_VERSION_NOTICE.md now describes the withdrawn Figure 3 efficacy chart. Its 60–75% "opioid reduction" bars were unsourced, and it mislabelled POFA as "Orthopedic". The notice states that the current record supersedes the chart and every other historical figure. The four figure stub files now say the figures were withdrawn and that the current overview is rc2 and later, not rc1. Filenames are unchanged so links still work.
- **POFA summary (MANUSCRIPT.md, main.tex):** now gives the direction of the primary composite outcome, which was more frequent with the opioid-free regimen (78% vs 67%). It also states that the trial stopped early after five cases of severe bradycardia, and that extubation and PACU discharge were delayed. POFA and Verret are cited by DOI instead of the fragile publisher PDF and PubMed links.
- **APPLIED_CASES.md / EXAMPLE_SOURCE_AUDIT.json:** NOA-02 wording now matches the dexmedetomidine US labeling: consider dose reduction in patients over 65 years and in hepatic impairment. The label was added as source LBL. All registry citations are now complete (title, journal, year, volume, pages, single DOI). Stray software and Smart NOA scope text copied from another repository was removed, and the remaining Smart NOA mention is an explicit link to that separate project.
- **PROVENANCE.md:** removed "ICU author" wording copied from another repository.
- **PUBLICATION_REVIEW.md / PROVENANCE.md:** the prose now states that the repository is public, which matches `public_release` in RELEASE_MANIFEST.json. The Smart NOA, ICU, TKA and breast items are labelled as portfolio-wide notes about other repositories.
- **README / bibliography.bib / main.tex:** the files now say that bibliography.bib is an unused companion file, so MANUSCRIPT.md is the reference list of record. The README states that the main PDF filename is historical and still carries the withdrawn title.
- The PDFs are stale until they are rebuilt from the updated MANUSCRIPT.md. Manifest hashes will be regenerated separately.
