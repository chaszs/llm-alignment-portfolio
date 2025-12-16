# Ejemplos sintéticos de evaluación de lenguaje idiomático (Idioms)

Este documento presenta ejemplos sintéticos destinados a ilustrar la evaluación cualitativa del manejo de lenguaje idiomático y no literal por parte de modelos de lenguaje de gran escala (LLM).

Los ejemplos no reproducen datos reales y se utilizan exclusivamente con fines de demostración metodológica.

---

## Ejemplo 1 — Identificación de expresión idiomática (Español)

### Input (sintético)
“Juan siempre se va por las ramas cuando le hacen una pregunta directa.”

### Output del modelo (sintético)
Juan habla de muchas cosas sin responder directamente a lo que se le pregunta.

### Evaluación cualitativa
El modelo reconoce correctamente que la expresión “irse por las ramas” no debe interpretarse de forma literal y ofrece una interpretación adecuada del significado implícito.

No se observa deriva semántica ni pérdida de intención comunicativa.

---

## Ejemplo 2 — Interpretación no literal en contexto (Catalán)

### Input (sintético)
“Quan li van dir que arribava tard, ja havia tirat la tovallola.”

### Output del modelo (sintético)
Quan li van dir que arribava tard, ja havia renunciat a continuar.

### Evaluación cualitativa
La expresión “tirar la tovallola” es correctamente interpretada como una renuncia o desistimiento, preservando el significado idiomático en catalán.

La reformulación mantiene naturalidad y adecuación contextual.

---

## Ejemplo 3 — Traducción con equivalencia no literal (Español → Inglés)

### Input (sintético)
“No dio pie con bola en toda la reunión.”

### Output del modelo (sintético)
He completely missed the point throughout the meeting.

### Evaluación cualitativa
La traducción evita una equivalencia literal incorrecta y utiliza un equivalente funcional adecuado en la lengua de destino.

Se preserva el significado y la intención comunicativa original.

---

## Ejemplo 4 — Error por interpretación literal (Inglés → Español)

### Input (sintético)
“He finally kicked the bucket.”

### Output del modelo (sintético)
Finalmente le dio una patada al cubo.

### Evaluación cualitativa
El modelo incurre en una interpretación literal incorrecta de una expresión idiomática establecida.

Se pierde completamente el significado no literal (“morir”), lo que constituye un fallo semántico grave en el manejo de idiomaticidad.

---

## Ejemplo 5 — Parafraseo preservando intención idiomática (Español)

### Input (sintético)
“María puso el grito en el cielo cuando se enteró.”

### Output del modelo (sintético)
María reaccionó con gran enfado cuando lo supo.

### Evaluación cualitativa
La reformulación preserva correctamente la intención emocional y pragmática de la expresión idiomática original.

El resultado es claro, natural y semánticamente fiel.

---

## Ejemplo 6 — Gestión multilingüe y adecuación cultural (Catalán → Español)

### Input (sintético)
“Això no té ni cap ni peus.”

### Output del modelo (sintético)
Eso no tiene ni pies ni cabeza.

### Evaluación cualitativa
El modelo selecciona un equivalente idiomático funcional en la lengua de destino, manteniendo el significado y la naturalidad.

No se detecta interferencia lingüística ni calco indebido.

---

## Ejemplo 7 — Deriva semántica en reformulación (Inglés)

### Input (sintético)
“She let the cat out of the bag.”

### Output del modelo (sintético)
Ella contó un secreto sin querer, aunque no fue muy importante.

### Evaluación cualitativa
Aunque el modelo reconoce parcialmente el significado idiomático, introduce una valoración adicional (“no fue muy importante”) no presente en el original.

Se detecta una deriva semántica leve que altera la intención original.

---

## Nota final

Estos ejemplos ilustran distintos modos de éxito y fallo en el tratamiento del lenguaje idiomático por parte de LLM.

La evaluación se basa en análisis cualitativo estructurado, atendiendo a la preservación del significado, la adecuación pragmática y la coherencia cultural en contextos multilingües.
