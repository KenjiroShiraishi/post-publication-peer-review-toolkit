# Screening Sheet Codebook

This codebook explains each column in `templates/screening-sheet.csv`.

The screening sheet is intended for preliminary documentation of post-publication peer review screening.

It is not designed to determine misconduct.  
It is designed to help readers organize human review.

## Column Definitions

| Column | Description | Suggested Values / Notes |
|---|---|---|
| `id` | Unique screening record ID | Example: `001`, `002`, `2026-05-001` |
| `date` | Date of screening | Use `YYYY-MM-DD` format |
| `screening_type` | Type of screening performed | `affiliation`, `topic`, `single_article`, `manual`, `other` |
| `query` | Search query or prompt condition used | Example: `psilocybin therapy last one month` |
| `title` | Article title | Copy from article page |
| `authors` | Article authors | Use abbreviated form if long |
| `journal` | Journal name | Copy from article page |
| `publication_date` | Publication date | Use article page date when available |
| `doi_or_url` | DOI or stable URL | Prefer DOI when available |
| `article_type` | Article category | `original_article`, `review`, `case_report`, `letter`, `commentary`, `protocol`, `editorial`, `other` |
| `study_type` | Study design or method | Example: `RCT`, `cross-sectional`, `cohort`, `case report`, `qualitative`, `commentary`, `not applicable` |
| `topic` | Main topic of the article | Example: `psilocybin therapy`, `acupuncture`, `AI in medicine`, `cannabis policy` |
| `main_claim` | Main claim or conclusion of the article | Short summary in one sentence |
| `conceptual_issue` | Possible conceptual mismatch | `Yes`, `No`, `Unclear` |
| `meaning_issue` | Possible meaning or interpretation mismatch | `Yes`, `No`, `Unclear` |
| `statistical_issue` | Possible statistical inference mismatch | `Yes`, `No`, `Unclear`, `Not applicable` |
| `disclosure_issue` | Possible COI, funding, affiliation, or transparency issue | `Yes`, `No`, `Unclear` |
| `coi_statement` | Conflict of interest statement | Copy or summarize briefly |
| `funding_statement` | Funding statement | Copy or summarize briefly |
| `human_review_priority` | Priority for human review | `High`, `Medium`, `Low`, `Unclear` |
| `recommended_action` | Suggested next step | `No action`, `Private note`, `Human review`, `Possible letter`, `Possible journal inquiry`, `Monitor` |
| `review_note` | Short note explaining why the article was flagged | Keep neutral and factual |
| `final_decision` | Final decision after human review | `No action`, `Letter submitted`, `Journal inquiry sent`, `Monitor`, `Needs more information`, `Other` |

## Issue Coding Guide

## Conceptual Issue

Use `Yes` when there may be a mismatch between the concept and how it is defined or measured.

Examples:

- A screening tool is treated as a diagnosis.
- A proxy variable is treated as the phenomenon itself.
- A complex clinical, social, ethical, or psychological concept is reduced to a single score without sufficient explanation.
- The central concept is unclear or inconsistently used.

Use `No` when the concept appears clearly defined and appropriately operationalized.

Use `Unclear` when more reading is needed.

## Meaning Issue

Use `Yes` when the interpretation may exceed what the article can support.

Examples:

- Association is interpreted as causation.
- Patient-reported improvement is treated as proof of mechanism.
- Small or exploratory findings are used to support broad clinical or policy claims.
- The discussion adds social, ethical, or cultural meaning that is not supported by the data.

Use `No` when the interpretation appears proportionate.

Use `Unclear` when more reading is needed.

## Statistical Issue

Use `Yes` when the statistical interpretation may not support the stated claim.

Examples:

- Small sample size relative to the claim.
- Confidence intervals or uncertainty are under-discussed.
- Subgroup analyses are overinterpreted.
- Multiple comparisons are not adequately addressed.
- Statistical significance is treated as clinical importance.
- Noninferiority, equivalence, or superiority claims are not aligned with the study design.
- Causal language is used for observational or cross-sectional data.

Use `No` when the statistical interpretation appears proportionate.

Use `Not applicable` for commentaries, editorials, narrative essays, or articles without statistical analysis.

Use `Unclear` when more reading is needed.

## Disclosure Issue

Use `Yes` when there may be a relevant transparency concern.

Examples:

- The article states “no conflicts of interest,” but the topic involves commercial, advocacy, political, institutional, or policy relevance.
- Funding is unclear.
- The role of the funder is unclear.
- Relevant affiliations or organizational roles appear important for reader interpretation.
- A reasonable reader may need additional disclosure to interpret the article responsibly.

Use `No` when disclosure appears sufficient.

Use `Unclear` when more information is needed.

## Human Review Priority

Use `High` when:

- the issue may affect reader interpretation substantially
- the article concerns clinical care, public health, regulation, commercial products, or vulnerable populations
- the issue may require a letter or formal journal inquiry

Use `Medium` when:

- the issue is potentially relevant but not urgent
- further reading is needed
- the article may be useful for educational review

Use `Low` when:

- no substantial concern is identified
- the article is mainly being logged for completeness

Use `Unclear` when the reviewer cannot classify the priority yet.

## Recommended Action

Use `No action` when no meaningful concern is identified.

Use `Private note` when the issue is minor or useful only for personal learning.

Use `Human review` when AI or preliminary screening has flagged an issue that needs manual checking.

Use `Possible letter` when the issue concerns:

- conceptual clarity
- measurement
- interpretation
- statistical inference
- clinical or policy overstatement

Use `Possible journal inquiry` when the issue concerns:

- conflict of interest disclosure
- funding transparency
- author affiliation
- institutional relationship
- possible correction of the publication record

Use `Monitor` when the issue may become relevant later but does not require immediate action.

## Neutral Language Examples

Prefer neutral notes such as:

> Possible mismatch between the study design and the strength of the conclusion.

> Funding statement may require human review for clarity.

> COI disclosure appears minimal; relevance to topic should be checked manually.

> Screening result appears to be discussed in diagnostic language.

Avoid accusatory notes such as:

> The authors hid conflicts of interest.

> This paper is fraudulent.

> The authors intentionally misled readers.

## Important Limits

The screening sheet is a documentation tool.

It does not determine misconduct.

AI-generated screening results must be checked by a human reviewer before any letter, journal inquiry, institutional communication, or public comment is prepared.

The goal is to support responsible scholarly reading and improve the accuracy, transparency, and interpretability of the academic record.
