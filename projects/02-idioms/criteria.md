# Criterios de evaluación del módulo Idioms

Este documento define los criterios utilizados para evaluar el comportamiento de modelos de lenguaje de gran escala (LLM) ante lenguaje idiomático y no literal, dentro del alcance definido para el módulo Idioms.

Los criterios están orientados a identificar fallos semánticos y pragmáticos que no pueden detectarse mediante evaluaciones literales o puramente sintácticas.

---

## Principios generales de evaluación

La evaluación en este módulo se rige por los siguientes principios:

- Prioridad de la **preservación del significado** sobre la forma superficial.
- Atención a la **intención comunicativa** y no solo al contenido explícito.
- Consideración del **contexto cultural y lingüístico**.
- Distinción entre error literal, error semántico y error pragmático.
- Coherencia entre interpretación, reformulación y traducción.

Los criterios se aplican de forma contextual, en función del tipo de tarea evaluada.

---

## Criterios principales

### 1. Reconocimiento de lenguaje idiomático

Evalúa si el modelo identifica correctamente que una expresión no debe interpretarse de forma literal.

Indicadores:
- Detección explícita o implícita de idiomaticidad.
- Evitación de interpretaciones palabra a palabra.
- Identificación correcta del fenómeno no literal implicado.

---

### 2. Interpretación del significado pretendido

Evalúa si el modelo comprende el significado real de la expresión en su contexto.

Indicadores:
- Correspondencia entre la interpretación y el sentido idiomático esperado.
- Ausencia de ambigüedad indebida.
- Inferencia correcta de la intención implícita.

---

### 3. Preservación semántica

Evalúa si el significado original se mantiene al explicar, reformular o traducir una expresión idiomática.

Indicadores:
- Conservación del contenido esencial.
- Ausencia de deriva semántica.
- No introducción de significados añadidos ni pérdida de información relevante.

---

### 4. Adecuación pragmática

Evalúa si la respuesta es adecuada al contexto comunicativo y cultural.

Indicadores:
- Uso apropiado del registro.
- Naturalidad en la lengua de destino.
- Correspondencia con la situación comunicativa implícita.

---

### 5. Equivalencia no literal en traducción

Evalúa la capacidad del modelo para traducir expresiones idiomáticas utilizando equivalentes funcionales y no literales.

Indicadores:
- Selección de un equivalente adecuado en la lengua de destino.
- Evitación de traducciones literales engañosas.
- Fidelidad al significado y a la intención original.

---

### 6. Calidad de la reformulación

Evalúa la calidad lingüística y semántica al reformular lenguaje idiomático.

Indicadores:
- Claridad y precisión de la reformulación.
- Fluidez y corrección lingüística.
- Mantenimiento de la intención comunicativa original.

---

### 7. Gestión del contexto multilingüe

Evalúa la consistencia del significado cuando la tarea involucra distintas lenguas.

Indicadores:
- Mantenimiento del sentido entre lenguas.
- Adecuación cultural específica en cada idioma.
- Evitación de calcos, interferencias o trasvases literales indebidos.

---

## Nota metodológica

La evaluación del lenguaje idiomático requiere criterios interpretativos y semánticos finos, difíciles de capturar mediante métricas rígidas.

Por este motivo, el módulo Idioms se apoya en análisis cualitativo estructurado, priorizando la fidelidad semántica, la corrección pragmática y la adecuación cultural.

Todos los ejemplos utilizados son sintéticos y se presentan exclusivamente con fines de demostración metodológica.


