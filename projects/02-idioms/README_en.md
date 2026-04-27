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
