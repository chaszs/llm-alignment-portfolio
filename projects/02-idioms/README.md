# Evaluación de lenguaje idiomático y no literal (Idioms)

Este módulo se centra en la evaluación del comportamiento de modelos de lenguaje de gran escala (LLM) ante **lenguaje no literal**, en particular expresiones idiomáticas y significados culturalmente arraigados.

El lenguaje idiomático constituye uno de los puntos de fallo más habituales en los LLM, ya que el significado no se deriva de forma composicional a partir de las palabras individuales y depende del contexto pragmático, cultural y situacional.

Este módulo aborda ese problema desde una perspectiva de evaluación y alineamiento lingüístico.

---

## Planteamiento del problema

Los LLM muestran un rendimiento sólido cuando el lenguaje es literal, explícito y sintácticamente transparente.  
Sin embargo, su desempeño se degrada de forma notable cuando aparecen:

- Expresiones idiomáticas
- Metáforas fosilizadas
- Frases culturalmente específicas
- Significados no composicionales
- Intención implícita o pragmática

En estos casos, los modelos tienden a:
- Traducir de forma literal y perder el significado
- Parafrasear alterando la intención original
- Conservar la forma superficial pero no la función semántica
- Generar respuestas plausibles pero pragmáticamente incorrectas

---

## Enfoque de evaluación

Este módulo no evalúa conocimiento léxico aislado, sino la capacidad del modelo para:

- **Reconocer** lenguaje idiomático o no literal
- **Interpretar** correctamente el significado pretendido
- **Preservar** el sentido al reformular
- **Traducir** utilizando equivalentes no literales adecuados
- **Mantener** naturalidad y adecuación cultural
- **Evitar** interpretaciones literales engañosas

El foco está en la fidelidad semántica y la corrección pragmática.

---

## Relación con alineamiento y tareas Judge

Aunque está estrechamente relacionado con el alineamiento, este módulo no se solapa con el marco Judge.

- **Judge** se centra en corrección, razonamiento, cumplimiento de instrucciones y seguridad.
- **Idioms** se centra en profundidad semántica, significado no literal y adecuación cultural.

La competencia idiomática impacta directamente en la calidad del alineamiento, pero requiere criterios de evaluación específicos, que se desarrollan en este módulo.

---

## Tipos de tareas abordadas

El módulo incluye escenarios de evaluación como:

- Identificación de expresiones idiomáticas
- Explicación de significados implícitos o no literales
- Parafraseo conservando la intención idiomática
- Traducción con equivalencia no literal
- Detección de deriva semántica causada por interpretaciones literales

---

## Objetivo del módulo

El objetivo de este módulo es mostrar:

- Sensibilidad lingüística más allá de la semántica superficial
- Capacidad para evaluar preservación de significado y adecuación cultural
- Conciencia de los modos de fallo pragmáticos e idiomáticos en LLM
- Aplicación estructurada de criterios de evaluación lingüística

Todos los ejemplos y materiales son sintéticos y se presentan como parte de un portafolio profesional.
