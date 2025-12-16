# Evaluation Criteria for the Idioms Module

This document defines the criteria used to evaluate the behavior of large language models (LLMs) when handling idiomatic and non-literal language, within the scope defined for the Idioms module.

The criteria are designed to identify semantic and pragmatic failure modes that cannot be captured through literal or purely syntactic evaluation.

---

## General Evaluation Principles

Evaluation within this module follows these core principles:

- Priority of **meaning preservation** over surface form.
- Attention to **communicative intent**, not only explicit content.
- Consideration of **cultural and linguistic context**.
- Clear distinction between literal error, semantic error, and pragmatic error.
- Coherence across interpretation, reformulation, and translation.

Criteria are applied contextually, depending on the nature of the task being evaluated.

---

## Core Evaluation Criteria

### 1. Recognition of Idiomatic Language

Evaluates whether the model correctly identifies that an expression should not be interpreted literally.

Indicators:
- Explicit or implicit detection of idiomaticity.
- Avoidance of word-by-word interpretation.
- Correct identification of the non-literal phenomenon involved.

---

### 2. Interpretation of Intended Meaning

Evaluates whether the model correctly understands the intended meaning of an expression in context.

Indicators:
- Alignment between the interpretation and the expected idiomatic meaning.
- Absence of unjustified ambiguity.
- Correct inference of implicit communicative intent.

---

### 3. Semantic Preservation

Evaluates whether the original meaning is maintained when explaining, reformulating, or translating an idiomatic expression.

Indicators:
- Preservation of essential meaning.
- Absence of semantic drift.
- No addition of unintended meanings or loss of relevant information.

---

### 4. Pragmatic Adequacy

Evaluates whether the response is appropriate to the communicative and cultural context.

Indicators:
- Appropriate register selection.
- Linguistic naturalness in the target language.
- Alignment with the implicit communicative situation.

---

### 5. Non-Literal Equivalence in Translation

Evaluates the model’s ability to translate idiomatic expressions using functional, non-literal equivalents.

Indicators:
- Selection of an appropriate equivalent in the target language.
- Avoidance of misleading literal translations.
- Fidelity to meaning and original intent rather than surface form.

---

### 6. Quality of Reformulation

Evaluates the linguistic and semantic quality of reformulations involving idiomatic language.

Indicators:
- Clarity and precision of the reformulation.
- Fluency and linguistic correctness.
- Preservation of the original communicative intent.

---

### 7. Multilingual Context Management

Evaluates consistency of meaning when tasks involve multiple languages.

Indicators:
- Preservation of meaning across languages.
- Language-specific cultural adequacy.
- Avoidance of calques, interference, or inappropriate literal transfer.

---

## Methodological Note

The evaluation of idiomatic language requires fine-grained interpretive and semantic criteria that are difficult to capture through rigid metrics.

For this reason, the Idioms module relies on structured qualitative analysis, prioritizing semantic fidelity, pragmatic correctness, and cultural adequacy.

All examples used are synthetic and intended solely for methodological demonstration purposes.
