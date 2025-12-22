# Criterios de evaluación del módulo Speech

Este documento define los criterios utilizados para evaluar el comportamiento de sistemas de reconocimiento del habla (ASR) y procesamiento de speech cuando operan en condiciones reales y no idealizadas.

Los criterios están orientados a identificar fallos funcionales, patrones de error y límites operativos del sistema, más allá de métricas técnicas aisladas.

---

## Principios generales de evaluación

La evaluación en el módulo Speech se rige por los siguientes principios:

- Prioridad de la **comprensión global del contenido** sobre la coincidencia literal palabra a palabra.
- Atención al **impacto funcional del error**, no solo a su forma superficial.
- Consideración explícita de **condiciones reales de uso**.
- Distinción entre error tolerable, error degradante y error crítico.
- Evaluación del comportamiento del sistema ante **incertidumbre o señal insuficiente**.

Los criterios se aplican de forma contextual, teniendo en cuenta el tipo de entrada acústica y el escenario evaluado.

---

## Criterios principales

### 1. Fidelidad entre audio y transcripción

Evalúa en qué medida la transcripción refleja el contenido esencial del audio original.

Indicadores:
- Correspondencia semántica global entre audio y texto.
- Ausencia de alteraciones graves del significado.
- Omisiones o adiciones justificadas o no justificadas.

---

### 2. Robustez ante ruido y degradación de la señal

Evalúa la capacidad del sistema para mantener un comportamiento razonable cuando la señal acústica se ve afectada.

Indicadores:
- Tolerancia a ruido ambiental.
- Estabilidad ante cortes, distorsión o baja calidad de audio.
- Grado de degradación progresiva del output.

---

### 3. Gestión de variación fonética y acento

Evalúa el comportamiento del sistema frente a acentos, dialectos y variación fonética.

Indicadores:
- Reconocimiento consistente de palabras clave.
- Ausencia de sesgos evidentes hacia pronunciaciones estándar.
- Estabilidad semántica pese a variación fonética.

---

### 4. Manejo de disfluencias y habla espontánea

Evalúa la capacidad del sistema para procesar habla no planificada.

Indicadores:
- Gestión de vacilaciones, repeticiones y autocorrecciones.
- Segmentación coherente del discurso oral.
- No introducción de artefactos lingüísticos indebidos.

---

### 5. Detección y gestión de alucinaciones

Evalúa si el sistema evita generar contenido no sustentado por la señal acústica.

Indicadores:
- No invención de palabras o frases inexistentes.
- Reconocimiento explícito o implícito de incertidumbre.
- Comportamiento conservador ante señal insuficiente.

---

### 6. Coherencia y consistencia del output textual

Evalúa la calidad interna del texto transcrito como representación del habla.

Indicadores:
- Coherencia sintáctica mínima.
- Consistencia terminológica.
- Ausencia de fragmentación arbitraria del discurso.

---

### 7. Reconocimiento de límites operativos

Evalúa si el sistema muestra señales de reconocer cuándo no puede procesar adecuadamente la entrada.

Indicadores:
- Respuestas parciales justificadas.
- Marcado implícito de baja confianza.
- Evitación de outputs engañosamente seguros.

---

## Nota metodológica

La evaluación en este módulo no persigue maximizar métricas cuantitativas específicas, sino analizar el comportamiento funcional del sistema en contextos realistas.

Los criterios aquí definidos permiten identificar patrones de fallo relevantes para alineamiento, seguridad y experiencia de usuario, sin necesidad de acceso al entrenamiento ni a la arquitectura del modelo.

Todos los ejemplos utilizados son sintéticos y se presentan exclusivamente con fines de demostración metodológica.
