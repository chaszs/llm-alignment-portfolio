# Evaluación y alineamiento de modelos LLM (Judge)

Este módulo documenta mi experiencia como evaluador en tareas de alineamiento y evaluación de modelos de lenguaje de gran escala (LLM), dentro de un marco de evaluación estructurado tipo *LLM-as-a-Judge*.

El trabajo se centra en la aplicación rigurosa de criterios formales, escalas binarias y escalas Likert para evaluar precisión factual, razonamiento, cumplimiento de instrucciones, calidad lingüística, control pragmático y seguridad.

Todo el contenido presentado es sintético y no reproduce datos reales del proyecto.

---

## Alcance del módulo

Mi participación se centró en un subconjunto concreto de tareas Judge, asignadas en distintos lotes a lo largo del proyecto.  
Estas tareas requieren evaluación semántica fina, razonamiento estructurado y control del comportamiento del modelo en contextos diversos.

Las tareas evaluadas incluyen:

- Respuestas a preguntas cerradas (escala binaria)
- Generación de instrucciones prácticas (escala Likert)
- Clasificación con justificación (escala binaria y Likert)
- Extracción de datos estructurados a partir de texto (escala binaria y Likert)
- Inferencia en lenguaje natural (NLI) (escala binaria y Likert)
- Reescritura / Parafraseo (escala binaria y Likert)
- Razonamiento en varios pasos (escala binaria)
- Generación de datos a texto (escala binaria)
- Continuación de diálogos con rol (escala Likert)
- Traducción con restricciones o explicaciones (escala binaria y Likert)
- Rechazo de instrucciones no seguras o fuera de alcance (escala binaria y Likert)
- Comprensión y ejecución de instrucciones con lenguaje atípico o mal escrito (escala Likert)

---

## Enfoque metodológico

La evaluación se realiza combinando criterios objetivos y cualitativos, según la naturaleza de la tarea:

- **Escalas binarias (0/1)** para tareas de corrección estricta.
- **Escalas Likert (1–5)** para tareas con gradación de calidad.

Los criterios evaluados incluyen, entre otros:
- Precisión factual
- Cumplimiento de la instrucción
- Coherencia lógica
- Razonamiento explícito
- Fidelidad semántica
- Claridad y estructura
- Naturalidad lingüística
- Control pragmático y de rol
- Seguridad y límites del sistema
- Gestión de lenguaje atípico o mal escrito

La puntuación final refleja una evaluación contextual, ponderada y alineada con la definición de cada tarea.

---

## Estructura del módulo

- `alcance-tareas.md`  
  Descripción precisa de las tareas evaluadas de forma directa.

- `criterios-sinteticos.md`  
  Definición abstracta y generalizable de los criterios de evaluación aplicados.

- `escalas-likert-sinteticas.md`  
  Descripción de las escalas binarias y Likert utilizadas, mapeadas a cada tipo de tarea.

- `ejemplos-sinteticos/`  
  Ejemplos ficticios que ilustran la aplicación práctica de criterios y escalas.

---

## Objetivo del módulo

Este módulo tiene como objetivo mostrar:
- Capacidad para evaluar modelos LLM con rigor metodológico.
- Comprensión profunda de tareas de alineamiento y razonamiento.
- Dominio de rúbricas complejas y criterios de calidad.
- Conciencia de riesgos semánticos, pragmáticos y de seguridad.

El contenido está diseñado como material de portafolio profesional y no expone información confidencial.

