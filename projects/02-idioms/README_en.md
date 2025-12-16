# Idioms & Non-Literal Language Evaluation

This module focuses on the evaluation of large language models (LLMs) when dealing with **non-literal language**, particularly idiomatic expressions and culturally embedded meanings.

Idiomatic language represents a well-known failure point for LLMs, as meaning cannot be derived compositionally from individual words and often depends on pragmatic, cultural, and contextual knowledge.

This module addresses that gap from an evaluation and alignment perspective.

---

## Problem Statement

LLMs perform reliably when language is literal, explicit, and syntactically transparent.  
However, performance degrades significantly when encountering:

- Idiomatic expressions
- Fossilized metaphors
- Culturally specific phrases
- Non-compositional meaning
- Pragmatic or implicit intent

In these cases, models tend to:
- Translate literally and lose meaning
- Paraphrase while distorting intent
- Preserve form but not function
- Produce semantically plausible but pragmatically incorrect outputs

---

## Evaluation Focus

Rather than testing vocabulary knowledge, this module evaluates whether a model can:

- **Recognize** idiomatic or non-literal language
- **Interpret** the intended meaning correctly
- **Preserve** meaning during paraphrasing
- **Translate** idioms using appropriate non-literal equivalents
- **Maintain** naturalness and cultural adequacy
- **Avoid** misleading literal renderings

The emphasis is on semantic fidelity and pragmatic correctness.

---

## Relation to Alignment and Judge Tasks

While closely related to alignment evaluation, this module does not overlap with the Judge framework.

- **Judge** focuses on correctness, reasoning, instruction compliance, and safety.
- **Idioms** focuses on semantic depth, non-literal meaning, and cultural alignment.

Idiomatic competence directly impacts alignment quality, but requires specialized evaluation criteria, which are addressed here.

---

## Types of Tasks Covered

The module includes evaluation scenarios such as:

- Identification of idiomatic expressions
- Explanation of implicit or non-literal meaning
- Paraphrasing while preserving idiomatic intent
- Translation with non-literal equivalence
- Detection of semantic drift caused by literal interpretation

All tasks are evaluated using clearly defined criteria and, when applicable, binary or Likert-based scales.

---

## Module Goal

The goal of this module is to demonstrate:

- Linguistic awareness beyond surface-level semantics
- Ability to evaluate meaning preservation and cultural adequacy
- Sensitivity to pragmatic and idiomatic failure modes in LLMs
- Structured evaluation of non-literal language handling

All examples and materials are synthetic and intended for professional portfolio use.
