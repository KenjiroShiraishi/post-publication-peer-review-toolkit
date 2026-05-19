# Prompt: Single-Article Post-Publication Review

This prompt is designed to help readers review a single published academic article for responsible post-publication peer review.

The purpose is not to accuse authors or identify misconduct.

The purpose is to support careful human review by examining whether the article contains conceptual ambiguity, meaning or interpretation mismatch, statistical inference problems, or disclosure transparency concerns.

## Intended Use

Use this prompt when you have already identified a specific published article and want to review it carefully.

This prompt may be useful for:

- preparing a letter to the editor
- deciding whether a journal inquiry may be appropriate
- identifying conceptual or interpretive issues
- checking whether conclusions are proportionate to the evidence
- reviewing conflict of interest and funding transparency
- creating a private scholarly reading note

## Input

I will provide one or more of the following:

- Title
- Abstract
- DOI or URL
- Introduction
- Methods
- Results
- Discussion
- Conflict of interest statement
- Funding statement
- Author affiliations
- Data availability statement
- Ethics approval statement
- Any relevant public information

## Prompt

Please review the article using the following framework:

1. Conceptual mismatch
2. Meaning and interpretation mismatch
3. Statistical inference mismatch
4. Conflict of interest, funding, and disclosure transparency

Do not accuse the authors of misconduct.

Do not speculate beyond the text and public information provided.

Do not rely on AI judgment alone.

Your task is to identify possible issues that may deserve human review, not to make final conclusions.

## Review Framework

## 1. Basic Article Information

Extract or summarize:

- Title
- Authors
- Journal
- Publication date
- DOI or URL
- Article type
- Study design
- Main topic
- Main claim or conclusion

If any information is missing, mark it as “not provided.”

## 2. Conceptual Mismatch

Ask whether the central concept is clearly defined and appropriately operationalized.

Key questions:

- What is the main concept being studied?
- Is the concept clearly defined?
- How is the concept measured or represented?
- Does the measurement actually capture the concept?
- Is a screening result treated as a diagnosis?
- Is a proxy variable treated as the phenomenon itself?
- Is a complex clinical, psychological, social, ethical, or cultural concept reduced too quickly to a single score?
- Are different concepts mixed together without clear distinction?

Output:

- Possible conceptual issue: Yes / No / Unclear
- Explanation
- Suggested point for human review

## 3. Meaning and Interpretation Mismatch

Ask whether the authors’ interpretation exceeds what the study can reasonably support.

Key questions:

- Do the conclusions match the study design?
- Is association interpreted as causation?
- Is subjective improvement treated as proof of mechanism?
- Is clinical meaning overstated from limited data?
- Are policy or practice recommendations stronger than the evidence allows?
- Are social, ethical, or cultural meanings added without sufficient support?
- Are limitations adequately acknowledged?
- Would a cautious reader interpret the results differently?

Output:

- Possible meaning or interpretation issue: Yes / No / Unclear
- Explanation
- Suggested point for human review

## 4. Statistical Inference Mismatch

Ask whether the statistical analysis supports the stated claims.

Key questions:

- Is the sample size appropriate for the claim?
- Are confidence intervals, effect sizes, and uncertainty adequately discussed?
- Are subgroup analyses exploratory or confirmatory?
- Are multiple comparisons handled appropriately?
- Is statistical significance treated as clinical importance?
- Are noninferiority, equivalence, or superiority claims aligned with the study design?
- Does the study infer causality from observational or cross-sectional data?
- Are null or negative findings interpreted cautiously?
- Are limitations of statistical power discussed?

Output:

- Possible statistical inference issue: Yes / No / Unclear
- Explanation
- Suggested point for human review

## 5. Conflict of Interest and Disclosure Transparency

Ask whether the disclosure statements provide enough information for readers to interpret the article responsibly.

Key questions:

- What conflict of interest statement is provided?
- What funding statement is provided?
- Are author affiliations clear?
- Is the role of funders clearly described?
- Are commercial, advocacy, political, institutional, or policy roles relevant to the article topic?
- Are relevant organizational relationships disclosed?
- Would a reasonable reader need additional information to interpret the article?
- Is there any mismatch between the topic and the disclosed relationships?

Output:

- Possible disclosure or transparency issue: Yes / No / Unclear
- Explanation
- Suggested point for human review

## 6. Letter or Journal Inquiry Decision

Classify the concern using the following categories:

- No action
- Private reading note
- Potential letter to the editor
- Potential formal journal inquiry
- Needs more information before deciding

Use this distinction:

A letter to the editor may be appropriate when the concern involves:

- conceptual clarity
- measurement
- interpretation
- statistical inference
- clinical or policy overstatement

A formal journal inquiry may be appropriate when the concern involves:

- missing or incomplete conflict of interest disclosure
- unclear funding information
- unclear author affiliation
- unclear funder role
- possible need for correction of the publication record

## 7. Suggested Output Format

Please provide the review in the following structure:

### Summary

Briefly summarize the article and its main claim.

### Conceptual Mismatch

- Finding:
- Reason:
- Human review priority: High / Medium / Low / Unclear

### Meaning and Interpretation Mismatch

- Finding:
- Reason:
- Human review priority: High / Medium / Low / Unclear

### Statistical Inference Mismatch

- Finding:
- Reason:
- Human review priority: High / Medium / Low / Unclear

### Conflict of Interest and Disclosure Transparency

- Finding:
- Reason:
- Human review priority: High / Medium / Low / Unclear

### Possible Action

Classify as one of:

- No action
- Private note
- Possible letter to the editor
- Possible journal inquiry
- Needs further human review

### Draft Neutral Concern Statement

Write a short, neutral statement that summarizes the main concern without accusing the authors.

Example:

> The article raises a possible question about whether the interpretation of the findings exceeds what the study design and measurements can support.

or:

> The article may benefit from clarification regarding whether the published disclosure statement provides sufficient information for readers to interpret the findings.

## Important Limits

AI output is not a final judgment.

AI may miss important details, misunderstand methods, or overstate concerns.

Before preparing a letter, inquiry, institutional communication, or public comment, a human reviewer must read the full article and verify all relevant information.

Do not submit AI-generated concerns without human review.

Do not use this prompt for harassment, public shaming, retaliation, or unsupported allegations.

## Final Reminder

Post-publication peer review is a scholarly activity.

It should improve the accuracy, transparency, and interpretability of the academic record.

The goal is not to target individuals, but to help readers, authors, journals, and the public evaluate published research more responsibly.
