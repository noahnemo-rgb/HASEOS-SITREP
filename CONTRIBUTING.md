# Contributing to HASEOS SITREPs

Thank you for reviewing. Adversarial findings are the fuel of this project — the documents here were built to be attacked, and the revision records show every attack that landed.

## What we're looking for

- **Factual challenges:** a claim in a SITREP's verified baseline that is wrong, overstated, understated, or since-superseded — with sourcing.
- **Inferential attacks:** weak links between evidence and conclusion, unstated assumptions, or motivated reasoning in either direction (for *or* against a tested framework).
- **Falsifiability audits:** signposts or disconfirmation conditions that are decorative, unmeasurable, or self-sealing.
- **Omissions:** anything a hostile critic would seize on that the document fails to address.
- **Scoring disputes:** disagreement with how a prior SITREP's predictions were graded against events.

## How to submit

Open a GitHub Issue titled `[FINDING] <document ID> — <short description>` using this structure:

```
**Document & section:** (e.g., HAS-SITREP-20260710-003 v2.2, Section V-B)
**Severity (your assessment):** Fatal / Critical / High / Moderate / Low
**Finding:** What is wrong, weak, or missing — stated plainly.
**Evidence / sourcing:** Links or citations. Bare assertions carry less weight.
**What would fix it:** Optional. Findings without proposed rewrites are welcome.
**Credit preference:** Named / handle / anonymous.
```

## What happens next

1. Findings are independently verified before adjudication — including findings we like.
2. The HASEOS inner circle adjudicates: **accepted**, **accepted in part**, or **rejected**, each with stated reasons.
3. Accepted findings produce a versioned revision; your contribution is credited in the public revision record per your preference.
4. Rejected findings are logged with reasons in the same record. Rejection is an adjudication, not a dismissal — and adjudications can be appealed with new evidence.

Submissions are considered, not auto-incorporated. Editorial accountability remains with the steward.

## Ground rules

- Attack documents, not people.
- Sourcing beats certainty; severity ratings are arguments, not verdicts.
- Reviews of the *method* (governance, disposition protocol, AI-review process) are as welcome as reviews of the analysis.
