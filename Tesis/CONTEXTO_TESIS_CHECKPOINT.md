# Contexto de redacción de tesis (checkpoint)

Fecha: 2026-01-07

## Estado actual

Se consolidó la sección **3.1.1 Fundamentos e importancia de los requerimientos** del marco teórico, con enfoque en:
- Problemas de calidad en requerimientos escritos en lenguaje natural.
- Aporte de LLMs para mejorar la definición de requerimientos.
- Limitaciones de los LLMs (no determinismo y necesidad de revisión).
- Justificación del sistema multiagente **LLM-MA** como capa de evaluación objetiva para requerimientos generados por humanos o IA.

---

## Texto consolidado (sección 3.1.1)

### 3.1.1 Fundamentos e importancia de los requerimientos

La ingeniería de requerimientos (IR) constituye el primer y más crítico elemento en el software Software Development Lifecycle( SDLC). Esta fase, de naturaleza dinámica, comprende la identificación, análisis, documentación y verificación de los requerimientos de un sistema, y funge como fundamento de todas las actividades de diseño, desarrollo y pruebas. Por ello surge la necesidad de contar con requerimientos de alta calidad desde el origen del proceso.

Históricamente, la actividad de análisis y definición de requerimientos ha sido documentada como factor crítico para el éxito o fracaso en proyectos de software. Autores como Kof (2010) sostienen que la omisión o la mala gestión en esta etapa es la principal causa de la mayoría de los fallos en proyectos de software.

Desde la adopción de marcos de trabajo ágil, la importancia de la IR mantiene gran relevancia y se transforma con la necesidad de realizar entregas de valor constante durante ciclos de trabajo cortos denominados Sprints, lo que exige contar con requerimientos de alta calidad desde su origen. Por lo tanto, tener claros los fundamentos de la IR es esencial para delimitar los criterios mínimos de claridad, completitud, consistencia y viabilidad de dichos elementos, y en consecuencia coadyuvar en la correcta planeación de lo que se compromete construir.

Diferentes estudios han demostrado que la deficiencia en la definición de requerimientos se debe, en gran medida, al uso del lenguaje natural. Muhamad et al. (2023) señalan que aproximadamente el 87.7% de la documentación de requerimientos de software se elabora en lenguaje natural, lo cual introduce ambigüedad en las especificaciones y da lugar a interpretaciones diferentes entre los integrantes del proyecto. Esta ambigüedad se manifiesta como una de las causas directas de retrabajos, incremento en los costos de mantenimiento y retrasos en la entrega de proyectos de software.

El lenguaje natural, por su propia naturaleza, carece de la precisión formal que requiere la ingeniería de software. Muhamad et al. (2023) identifican cinco tipos de ambigüedad lingüística que se presentan con frecuencia en los documentos de especificación de requerimientos de software (SRS): la ambigüedad léxica, originada por el uso de términos con múltiples significados; la ambigüedad sintáctica, derivada de estructuras gramaticales que admiten más de una interpretación; la ambigüedad semántica, producida por el empleo de cuantificadores vagos como "todos", "varios" o "algunos"; la ambigüedad de referencia, asociada al uso de pronombres sin referente claro; y la ambigüedad pragmática, generada por el contexto de uso de la expresión. Cada uno de estos tipos puede conducir a interpretaciones erróneas durante el proceso de desarrollo, resultando en un producto que no satisface las necesidades reales del cliente. Las consecuencias de estas deficiencias son cuantificables: de acuerdo con los datos citados por Muhamad et al. (2023), el 82% de las aplicaciones que requieren reelaboración tienen como causa principal errores en los requerimientos.

Ante esta problemática, el surgimiento de los Grandes Modelos de Lenguaje (LLM, por sus siglas en inglés) ha representado un avance significativo en el procesamiento del lenguaje natural aplicado a la ingeniería de requerimientos. Según Pacchiotti et al. (2025) el uso de LLMs en un proceso estructurado de especificación de requerimientos puede alcanzar hasta un 96.78% de cumplimiento de características de calidad definidas por INCOSE, como son la no ambigüedad, completitud y verificabilidad. Sin embargo, los mismos autores advierten que los resultados no son reproducibles con exactitud por la naturaleza no determinística de los LLMs(Pacchiotti et al., 2025). Es importante recalcar que los LLMs, al ser modelos generativos, pueden producir requerimientos que aparentan cumplir criterios de calidad sin que esto sea verificable de forma sistemática y objetiva, y puede depender también de la calidad de insumos que reciban.

Como se vio anteriormente la enorme capacidad de de los LLMS, su adopción en la fase de definición de requerimientos avanza a una velocidad significativamente menor que en otras actividades del SDLC. El estudio paneuropeo de Pashchenko (2025) evidencia que solo el 22% de los expertos utiliza LLMs para gestionar especificaciones de requerimientos, lo que contrasta con el 55% que los emplea en actividades de codificación. Esta brecha marca una importante resistencia al cambio de los roles menos técnicos en las organizaciones.

Por consiguiente, surge la oportunidad de innovar con un sistema multiagente basado en LLMs (LLM-MA) que coadyuve en la entrega de requerimientos de mayor calidad, actuando como una capa de revisión objetiva y sistemática que complementa el proceso de definición independientemente de si los requerimientos fueron redactados por analistas humanos o generados mediante herramientas de inteligencia artificial, generando así un alto valor dentro del equipo de desarrollo ágil.

---

## Referencias clave discutidas en esta sesión

- Muhamad, et al. (2023). (artículo sobre ambigüedad en SRS y porcentaje de uso de lenguaje natural).
- Pacchiotti, M. J., Ale, M., & Ballejos, L. (2025). *Un marco conceptual para la generación de requerimientos de software de calidad*.
- Sanguino-Reyes, M. R., & Cuesta-Quintero, B. (2022). *La inteligencia artificial en la ingeniería de requerimientos: un estudio de mapeo sistemático*. *Mundo Fesc, 12*(23), 8–15.
- Pashchenko (2025). estudio paneuropeo citado para adopción de LLMs en requisitos vs codificación.

---

## Próximo paso sugerido para continuar luego

Redactar la sección 3.1.2 (o siguiente subsección del marco teórico) conectando:
1. Criterios de calidad de requerimientos (INCOSE/IEEE).
2. Brecha entre generación asistida por IA y evaluación formal.
3. Diseño conceptual del sistema multiagente evaluador (roles de agentes y métricas).