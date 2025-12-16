# Alcance de tareas realizadas como evaluador LLM-as-a-Judge

Este documento describe de forma precisa el conjunto de tareas que evalué como parte de un marco de alineamiento y evaluación de modelos de lenguaje de gran escala (LLM).  
El alcance que se detalla a continuación corresponde exclusivamente a los lotes que me fueron asignados durante el proyecto y no pretende cubrir la totalidad del catálogo de tareas existente en el sistema Judge.

---

## Tareas evaluadas

### Preguntas cerradas (dominio factual)
Evaluación de respuestas a preguntas de dominio cerrado, con criterios binarios estrictos basados en precisión factual, adecuación al contexto y ausencia de información inventada o no justificada.

### Generación de instrucciones prácticas
Análisis de respuestas que describen procedimientos o pasos a seguir, evaluando cobertura completa de las acciones necesarias, orden lógico, claridad expresiva y ausencia de ambigüedades.

### Clasificación con justificación
Evaluación de tareas que requieren asignar una etiqueta o categoría específica, junto con una justificación coherente, alineada con el contenido del input y con los criterios definidos.

### Extracción de datos estructurados a partir de texto
Verificación de la correcta identificación y extracción de información explícita del texto, garantizando fidelidad a los datos originales y ausencia de omisiones o añadidos no presentes en la fuente.

### Inferencia en lenguaje natural (NLI)
Evaluación de la relación lógica entre una premisa y una hipótesis, determinando si existe implicación, contradicción o neutralidad, así como la solidez del razonamiento que sustenta la clasificación.

### Reescritura / Parafraseo
Análisis de la capacidad del modelo para reformular un texto conservando su significado original, manteniendo fluidez, corrección gramatical y adecuación estilística.

### Razonamiento en varios pasos
Evaluación de tareas que requieren una secuencia explícita de razonamiento, revisando la coherencia de cada paso intermedio y la validez de la conclusión final.

### Generación de datos a texto
Análisis de textos generados a partir de información estructurada, valorando fidelidad al contenido proporcionado, claridad expresiva y naturalidad lingüística.

### Continuación de diálogos con rol
Evaluación de respuestas generadas dentro de un contexto conversacional con rol definido, teniendo en cuenta coherencia pragmática, consistencia del personaje y adecuación del tono.

### Traducción con restricciones o explicaciones
Evaluación de traducciones automáticas que incluyen restricciones adicionales o requerimientos explicativos, verificando fidelidad semántica y cumplimiento estricto de las instrucciones.

### Rechazo de instrucciones no seguras o fuera de alcance
Análisis de respuestas destinadas a rechazar solicitudes inapropiadas, inseguras o fuera del ámbito permitido, evaluando corrección del rechazo, claridad del mensaje y tono adecuado.

### Comprensión y ejecución de instrucciones con lenguaje atípico o mal escrito
Evaluación de la capacidad del modelo para interpretar correctamente la intención del usuario en textos con errores, ambigüedades o lenguaje no estándar, y generar una respuesta útil y corregida.

---

## Tareas no incluidas en mi alcance

Las siguientes tareas forman parte del marco general de evaluación, pero no estuvieron incluidas en los lotes que me fueron asignados:

- Resumen
- Preguntas abiertas
- Generación de código
- Relleno de plantillas
- Otras tareas no incluidas en los lotes específicos asignados

---

## Nota final

El alcance descrito refleja mi experiencia directa como evaluador y se enmarca dentro de un sistema de evaluación más amplio, del cual comprendo la estructura general, las rúbricas y los principios metodológicos, aunque no todas las tareas formaron parte de mi asignación directa.

