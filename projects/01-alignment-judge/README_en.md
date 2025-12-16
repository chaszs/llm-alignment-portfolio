# Evaluation and Alignment of LLM Models (Judge)

This module documents my experience as an evaluator working on alignment and evaluation tasks for large language models (LLMs), within a structured *LLM-as-a-Judge* evaluation framework.

The work focuses on the rigorous application of formal criteria, binary scales, and Likert scales to assess factual accuracy, reasoning quality, instruction adherence, linguistic quality, pragmatic control, and safety.

All content presented here is synthetic and does not reproduce real project data.

---

## Module Scope

My contribution focused on a specific subset of Judge tasks, assigned across different evaluation batches throughout the project.  
These tasks require fine-grained semantic judgment, structured reasoning, and careful control of model behavior across diverse contexts.

The evaluated tasks include:

- Closed-domain questions (binary scale)
- Practical instruction generation (Likert scale)
- Classification with justification (binary and Likert scales)
- Structured data extraction from text (binary and Likert scales)
- Natural Language Inference (NLI) (binary and Likert scales)
- Rewriting / Paraphrasing (binary and Likert scales)
- Multi-step reasoning (binary scale)
- Data-to-text generation (binary scale)
- Role-based dialogue continuation (Likert scale)
- Translation with constraints or explanations (binary and Likert scales)
- Rejection of unsafe or out-of-scope instructions (binary and Likert scales)
- Understanding and execution of atypical or malformed language instructions (Likert scale)

---

## Methodological Approach

Evaluation is carried out by combining objective and qualitative criteria, depending on the nature of each task:

- **Binary scales (0/1)** are used for tasks requiring strict correctness.
- **Likert scales (1–5)** are used for tasks involving graded quality judgments.

The evaluated criteria include, among others:

- Factual accuracy
- Instruction compliance
- Logical coherence
- Explicit reasoning quality
- Semantic fidelity
- Clarity and structural organization
- Linguistic naturalness
- Pragmatic and role control
- Safety and system boundaries
- Handling of atypical or malformed language

Final scores reflect a contextual, weighted evaluation aligned with the definition of each task.

---

## Module Structure

- `alcance-tareas.md`  
  Description of the tasks directly evaluated.

- `criterios-sinteticos.md`  
  Definition of the evaluation criteria applied.

- `escalas-likert-sinteticas.md`  
  Description of the binary and Likert scales used, mapped to each task type.

- `ejemplos-sinteticos/`  
  Synthetic examples illustrating the practical application of criteria and scales.

---

## Module Objective

This module aims to demonstrate:

- The ability to evaluate LLMs with methodological rigor.
- A deep understanding of alignment and reasoning tasks.
- Mastery of complex evaluation rubrics and quality criteria.
- Awareness of semantic, pragmatic, and safety-related risks.

The content is intended as professional portfolio material and does not expose confidential information.

