# LLM Evaluation, Alignment and Language Analysis Portfolio

**Carles Rodríguez** · AI Evaluation Specialist · [LinkedIn](https://www.linkedin.com/in/chaszs)

---

This repository documents applied professional experience in the evaluation, alignment, and qualitative analysis of large language models (LLMs) and speech systems.

The work focuses on evaluation methodology rather than model training: gold-standard definition, rubric design, failure mode analysis, and structured quality assessment across diverse task types.

> Examples and outputs have been anonymized and adapted for public disclosure.
> The evaluation frameworks, rubrics, and methodological decisions reflect applied professional work.

---

## What you will find here

The **Judge** module documents a structured LLM-as-a-Judge evaluation system covering:

- 5 task types with distinct evaluation dimensions
- Binary (0/1) and Likert-scale (1–5) scoring, combined per task
- Anchor justifications at each quality level in Spanish and English
- Challenging examples designed to surface subtle model failure modes
- Coverage of NLI, structured extraction, paraphrase quality, multi-step reasoning, and instruction following

The **Idioms** module documents evaluation of non-literal language handling across Spanish, Catalan, and English — an area with high failure rates in current LLMs.

The **Speech** module documents evaluation of ASR systems under real-world conditions: noise, accent variation, disfluencies, and hallucination detection.

---

## Repository Structure

```
projects/
├── 01-alignment-judge/
│   ├── README.md / README_en.md
│   ├── alcance-tareas.md
│   ├── criterios-sinteticos.md
│   ├── escalas-likert-sinteticas.md
│   └── ejemplos-sinteticos/
├── 02-idioms/
│   ├── README.md / README_en.md
│   ├── scope.md / scope_en.md
│   ├── criteria.md / criteria_en.md
│   └── examples/
└── 03-speech/
    ├── README.md / README_en.md
    ├── scope.md / scope_en.md
    ├── criteria.md / criteria_en.md
    └── context.md / context_en.md
```

Each module includes scope definition, evaluation criteria, methodological approach, and illustrative examples.

---

## Modules Overview

### 1. Judge – LLM Evaluation and Alignment

The **Judge** module documents work within a structured *LLM-as-a-Judge* evaluation framework.

Rigorous application of binary and Likert-scale rubrics to assess:

- Instruction following and step coverage
- Factual accuracy and structured data extraction
- Natural Language Inference (NLI) classification and reasoning quality
- Paraphrase quality: meaning preservation and linguistic fluency
- Multi-step reasoning coherence and logical validity
- Safety boundary handling and rejection of unsafe requests

The module demonstrates end-to-end evaluation design: from task scoping and gold-standard definition to anchor-level justifications and failure mode documentation.

📁 `projects/01-alignment-judge/`

---

### 2. Idioms – Non-Literal Language and Semantic Robustness

The **Idioms** module evaluates LLM behavior when handling idiomatic expressions and non-compositional meaning — a well-documented failure area for current models.

Focus areas:

- Idiomatic meaning recognition and interpretation
- Semantic preservation in paraphrase and reformulation
- Non-literal equivalence in translation (ES / CA / EN)
- Detection of semantic drift caused by literal interpretation
- Cultural and pragmatic adequacy

Work developed in multilingual contexts (Spanish, Catalan, English), within the ALIA and AINA language alignment initiatives.

📁 `projects/02-idioms/`

---

### 3. Speech – ASR and Spoken Language Evaluation

The **Speech** module addresses evaluation of automatic speech recognition (ASR) systems under realistic conditions, beyond clean-audio benchmarks.

Focus areas:

- Audio-to-text fidelity under noise and signal degradation
- Phonetic variation, accent, and dialectal handling
- Disfluency and spontaneous speech processing
- Hallucination detection when signal is insufficient
- Recognition of system operational limits

📁 `projects/03-speech/`

---

## Methodological Approach

Across all modules:

- Clear task scoping and explicit criterion definition
- Context-aware qualitative analysis
- Separation of evaluation from model training concerns
- Awareness of alignment, safety, and user impact
- Documentation of both success and failure patterns

---

## Disclaimer

Examples, datasets, and outputs in this repository have been anonymized and adapted for public disclosure.
No proprietary data, confidential materials, or internal systems are reproduced.




