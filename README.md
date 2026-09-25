# IASEAI-Foundation Model Policy

**Research themes:** Governance, Proportionality, CIPDA, ROMER, Primers, functional sufficiency, Business Impact Governance Level (BIGL), AI governance, and human–AI reasoning.

This repository contains copyright and original work by Kenneth Tombs, for the IASEAI Paris conference 2026.

All materials are copyright but may be used with clear citation; experimental designs and results from a continuing programme of research into how the structure of human instructions affects the reliability, consistency and inspectability of AI-assisted work.

The travel-booking experiments (Dignum and Dignum), provides a deliberately ordinary but sufficiently complex test environment. An AI is asked to act as a travel-booking assistant while satisfying multiple interacting requirements concerning itinerary, timing, traveller preferences, constraints and decision rules.
# AI Governance and Reliability Research

This repository documents an evolving research programme exploring structured instructions, AI reliability, evidence traceability and proportionate governance.

It includes historical research materials and later experimental reports. Documents are shared to make the research inspectable, support critical review and inform further investigation. Inclusion does not mean that every claim has been independently verified.

## Research focus

The programme examines:

- Whether structured instructions help AI systems follow constraints and produce outputs that can be checked.
- How initial responses differ from outcomes achieved after review, correction or retries.
- Whether AI systems make comparable judgements about the governance required for different activities.
- How those judgements relate to Business Impact Governance Levels (BIGL).
- What evidence, records and assurance are needed to support responsible use.

## Research generations

### Generation 1 — Historical development

The early work explores travel-booking scenarios, structured primers, PDCA, ROMER, CIPDA and evidence-recording approaches.

These materials document the development of the research. They include proposed methods, illustrative examples, AI-generated analysis, partial results and subsequent correction records.

The historical evidence is not a single validated dataset. Known issues include conflicting run identifiers, scenario-label errors, incomplete execution records and scoring methods that can reward response formatting rather than correctness.

Earlier numerical claims should not be reused without consulting the associated correction and evidence-recovery records. In particular, later datasets must not be substituted for the unavailable historical ten-case control/treatment bundle.

### Generation 2

Generation 2 is retained as a separate, closed stage of the research. Its scope and conclusions should be read from its own records rather than inferred from other generations.

### Generation 3

Generation 3 contains distinct experiments:

- **Experiment A:** closed; its findings belong to its own method and evidence.
- **Experiment B:** closed at preparation stage without target submissions. Preparation records are retained for historical reference and possible future revival.
- **Experiment C:** completed descriptive study of AI-assisted pairwise governance judgements.

##Experiment A — Closed. It fcussed on perfomance of unconstrained, PDCA and CIPDA structured prompts and primers. The method, captured outputs, analysis and findings are retained as a separate study. Read its conclusions alongside its documented scope and limitations; its results should not be pooled with other experiments without establishing methodological comparability.

##Experiment C

Experiment C asked participating AI systems to compare five business scenarios using a restricted 1–7 Analytic Hierarchy Processing (AHP) comparison scale. Participants were instructed not to assign predetermined governance levels.

The scenarios concerned:

1. Internal meeting preparation.
2. Management reporting and resource allocation.
3. Credit assessment.
4. Regulatory submissions.
5. Job applicant processing.

The collection contains outputs from 13 user-labelled platforms or services, representing 14 configurations. Sixteen receipts were retained, including a linked pilot and a duplicate submission; these are not 16 independent tests.

The main descriptive synthesis comprises 12 provisional comparison records and 11 distinct matrices. Exclusions and provenance qualifications are explained in the report.

### Principal findings

Independent calculation from every complete comparison matrix produced the same relative ordering:

**Investigation > regulatory submission > credit assessment > management reporting > meeting preparation.**

However:

- Comparison strengths and explanations varied.
- Several reported eigenvectors and consistency figures were incorrect.
- One configuration produced unusable output and was recorded as a usability failure.
- Agreement in ordering did not establish correct absolute governance classifications.

The findings provide preliminary support for eliciting judgements about proportionate governance from the circumstances of the work. They do not validate BIGL’s four levels or boundaries, establish reliable automated allocation, or demonstrate improved human decisions.

Sensitivity to wording remains an open research question. It was not directly tested by systematically varying otherwise equivalent scenarios.

## Reading the evidence

Keep the following distinctions in mind:

| Material | How to interpret it |
|---|---|
| Original AI output | Evidence of the supplied response, including its errors |
| Assessor calculation | A separate check of the response’s mathematical results |
| Method or primer | Instructions or design intentions; not proof of execution |
| Illustrative example | An explanation or proposal, not necessarily an observed result |
| Historical findings draft | Claims requiring assessment against the available evidence |
| Correction or recovery record | Qualifications, contradictions and provenance limitations |
| Final report | A synthesis whose stated scope and limitations remain applicable |

Correctness, consistency, explanation quality, usability and traceability are separate properties. A well-structured explanation is not proof of faithful internal reasoning, and a low consistency ratio is not proof that a governance judgement is substantively correct.

## BIGL status

BIGL is a working research framework for selecting proportionate governance according to credible consequences.

It is not presented here as a government, regulatory or international standard. Relative AHP weights do not provide automatic BIGL thresholds. Activities with different relative priorities may require the same governance level.

## Reproducibility and limitations

Where included, receipt metadata, source hashes, calculation scripts and correction records support inspection and reconstruction.

Historical completeness varies. Exact model versions, session settings, input equivalence and independence are not confirmed for every record. Some scripts are incomplete or belong to later implementations rather than the experiments discussed in earlier manuscripts.

Do not execute historical scripts without reviewing their dependencies, scoring logic and external-service behaviour.

No claim of general AI reliability or deployment readiness follows from these small, selected studies.

## Public release scope

This repository is intended to contain a reviewed public selection, rather than an indiscriminate copy of the private working archive.

Before publication, files should be checked for credentials, personal information, confidential content and third-party redistribution restrictions. Saved conversation exports and browser-support files require particular care.

Any omissions or redactions should be documented without exposing the removed information. A file’s presence in a local research folder does not establish that it is suitable for public distribution.

## Contributions and corrections

Critical review is welcome, particularly concerning:

- Unsupported claims or numerical discrepancies.
- Scenario feasibility and scoring validity.
- Provenance and reproducibility.
- Governance-level boundaries.
- Wording sensitivity and clarification methods.
- Appropriate interpretation of historical evidence.

Please identify the document, section and supporting evidence when reporting a concern. Distinguish proposed methodological improvements from corrections to recorded observations.

## Licensing

See the repository’s licence file, if supplied, for reuse terms. Third-party materials may have separate rights and conditions.

Public availability alone should not be interpreted as permission to redistribute every included item under a common licence.
