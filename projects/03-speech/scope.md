# Alcance del módulo Speech

Este documento define el alcance del módulo **Speech**, especificando qué aspectos del procesamiento automático del habla se evalúan, en qué contextos y bajo qué límites metodológicos.

El objetivo es delimitar con claridad el tipo de evaluación realizada, evitando solapamientos con otros módulos y expectativas incorrectas sobre las capacidades analizadas.

---

## Qué entra en el alcance

El módulo Speech evalúa el comportamiento de sistemas de reconocimiento del habla (ASR) y procesamiento de speech cuando se enfrentan a **habla humana real**, no idealizada.

Se incluyen, entre otros, los siguientes aspectos:

- Transcripción de habla espontánea
- Procesamiento de audio con ruido ambiental o interferencias
- Variación fonética, acento y diferencias dialectales
- Disfluencias, vacilaciones y autocorrecciones
- Omisiones, adiciones o sustituciones indebidas en la transcripción
- Segmentación incorrecta del discurso oral
- Normalización inapropiada del lenguaje hablado
- Comportamiento del sistema ante señal acústica degradada

El foco de la evaluación está en la **comprensión global del contenido**, la **robustez ante variación** y el **reconocimiento de límites** por parte del sistema.

---

## Tipos de tareas evaluadas

Dentro de este alcance, el módulo contempla tareas como:

- Evaluación de la fidelidad entre audio y transcripción
- Análisis de errores recurrentes en condiciones no ideales
- Detección de alucinaciones cuando la señal es insuficiente
- Evaluación de coherencia del texto transcrito
- Identificación de fallos sistemáticos asociados a acento o ruido

Estas tareas se abordan desde una perspectiva de evaluación aplicada, no de optimización del modelo.

---

## Qué queda explícitamente fuera del alcance

Para mantener un marco claro y controlado, el módulo Speech **no incluye**:

- Entrenamiento o ajuste de modelos de ASR
- Comparativas de rendimiento entre arquitecturas o proveedores
- Análisis fonético o fonológico académico
- Evaluación de pronunciación humana individual
- Estudios de prosodia o entonación
- Diseño de datasets de audio
- Medición exhaustiva de métricas técnicas (WER, CER, etc.) como objetivo principal

Estas dimensiones pueden ser relevantes en otros contextos, pero no forman parte de los objetivos de este módulo.

---

## Relación con otros módulos

- **Judge**: Speech no evalúa razonamiento, cumplimiento de instrucciones ni calidad del texto generado, salvo cuando los errores de transcripción afectan directamente a estos aspectos.
- **Idioms**: Speech no evalúa significado no literal, salvo cuando la transcripción incorrecta impide su interpretación posterior.

Cada módulo mantiene un foco específico para garantizar evaluaciones precisas y no redundantes.

---

## Nota metodológica

El alcance definido prioriza el análisis del comportamiento del sistema ante condiciones reales frente a escenarios de laboratorio.

La evaluación se centra en identificar patrones de fallo, límites operativos y degradación de calidad, más que en maximizar métricas aisladas.

Todos los ejemplos y materiales utilizados son sintéticos y se presentan exclusivamente con fines de demostración metodológica.
