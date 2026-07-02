# Revisión Académica — Sección 2.2 "Problema actual"

**Documento revisado:** Redacción de la sección 2.2 compartida en chat  
**Fecha:** 2026-06-30  
**Enfoque:** Coherencia, claridad y nivel académico

---

## 1) Diagnóstico rápido

Tu texto **sí es entendible** y muestra una mejora clara porque:

- El problema aparece desde el inicio.
- Se explica el contexto operativo del POD.
- Se conecta el problema con efectos en métricas del sprint.

Sin embargo, todavía hay puntos que reducen su calidad académica:

1. Hay **redundancia** entre el primer y último párrafo (repiten casi el mismo enunciado del problema).
2. El párrafo que introduce: *"El proceso de análisis... varía según el tipo de ítem...:"* queda **inconcluso** si no incluyes los subtipos después.
3. Regresa la cita de **Pashchenko (2025)** con una conexión débil al caso específico.
4. Falta al menos un **dato cuantitativo** del equipo para evidenciar el problema.
5. Hay detalles formales: **POD´s** (debe ser **PODs**) y mezcla de términos inglés/español sin criterio uniforme.

---

## 2) Correcciones puntuales recomendadas

### A. Críticas/metodológicas

- **A1. Evitar duplicar el problema en apertura y cierre**  
  - **Qué pasa:** Se repite "considerable pérdida de tiempo... sobre requerimientos no preparados" al inicio y al final.  
  - **Cómo corregir:** Deja el problema en apertura y usa el cierre para sintetizar impacto + pregunta de investigación.

- **A2. Completar o retirar el bloque de tipos de ítems**  
  - **Qué pasa:** El texto anuncia los tipos con dos puntos, pero en esta versión ya no están listados.  
  - **Cómo corregir:** O reincorporas los sub-bloques (Iniciativas, Épicas, etc.) o quitas esa frase para que no quede cortada.

- **A3. Fortalecer evidencia del problema**  
  - **Qué pasa:** Se afirma impacto en velocity/carryover sin cifras internas.  
  - **Cómo corregir:** Agrega un dato real o aproximado de N sprints (porcentaje de carryover, retrabajos, etc.).

- **A4. Revisar el uso de Pashchenko (2025)**  
  - **Qué pasa:** El dato de Europa no justifica por sí mismo el caso de tu POD.  
  - **Cómo corregir:** O elimínalo o acompáñalo de puente argumentativo + evidencia local.

- **A5. Ajustar la pregunta de investigación para que sea medible**  
  - **Qué pasa:** "calidad", "forma adecuada" y "productividad" no están operacionalizadas.  
  - **Cómo corregir:** Define variable de salida (ej. retrabajo, carryover, completitud/coherencia).

### B. Formales/estructurales

- Cambiar **POD´s** → **PODs**.
- Uniformar términos en inglés: primera aparición en cursiva y con traducción.
- Mejorar puntuación de oraciones largas para evitar fatiga de lectura.

---

## 3) Propuesta de redacción mejorada (lista para usar)

> Puedes copiar y pegar esta versión como base.

### 2.2 Problema actual

Este apartado aborda el problema de investigación identificado en el POD analizado: la pérdida considerable de tiempo del equipo al trabajar sobre requerimientos no preparados, lo cual genera retrabajo, atrasos y baja predictibilidad en la ejecución de los sprints. Patito es una empresa dedicada, entre otras actividades, al desarrollo de software a medida. Para atender las necesidades de cada cliente, organiza equipos denominados **Product-Oriented Delivery (POD)**, que operan bajo el marco ágil Scrum. En uno de estos PODs se observan desafíos relevantes durante la fase de análisis y definición del backlog, asociados a la falta de conocimiento técnico y de negocio, la aplicación deficiente de estándares de redacción, la sobrecarga de trabajo y el uso inadecuado de herramientas de inteligencia artificial.

La etapa de análisis del **Software Development Life Cycle (SDLC)** es crítica para determinar la viabilidad de mejoras, correcciones o nuevos desarrollos solicitados por el cliente antes de iniciar su construcción. En esta fase participan el **Business Analyst (BA)**, el **Technical Lead (TL)** y el **Test Lead (QA Lead)**. Los elementos del backlog incluyen requerimientos funcionales, correctivos, perfectivos, preventivos y evolutivos, representados en historias de usuario, épicas, bugs y tareas. Independientemente del tipo de ítem y del rol que lo origine, la calidad del análisis inicial condiciona directamente su nivel de completitud, coherencia y trazabilidad.

Este proceso puede apoyarse en herramientas de inteligencia artificial generativa o realizarse de forma manual. Sin embargo, el uso de IA, por sí solo, no garantiza calidad en la especificación de requerimientos si no existe un proceso de validación estructurado. En consecuencia, se mantiene variabilidad en la calidad de los insumos del backlog, lo que impacta en la ejecución del sprint y en la capacidad de planificación del equipo.

En términos operativos, estas deficiencias se reflejan en ciclos de retrabajo durante el desarrollo, detección tardía de dependencias y desviaciones en métricas como **BurnDown Chart**, **CarryOver** y **velocity**. Desde esta perspectiva, surge la siguiente pregunta de investigación: **¿En qué medida la implementación de un proceso asistido por IA generativa para la especificación de ítems del backlog mejora la completitud y coherencia de los requerimientos, y reduce el retrabajo durante el sprint en el POD analizado?**

---

## 4) Versión breve de pregunta (alternativa)

Si tu asesor pide una pregunta más corta:

**¿Cómo influye el uso estructurado de IA generativa en la calidad de los requerimientos del backlog y en la reducción del retrabajo del POD?**
