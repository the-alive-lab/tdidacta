# Bootstrap operativo — reconciliación de Foundations y Concepts

**Estado:** procedimiento consolidado para continuar la revisión conceptual de TDidacta (2026-10-17). **Ámbito:** orientaciones O0–O10, fundamentos, conceptos y trazabilidad. No constituye demostración empírica ni una decisión de adoptar mecanismos.  
**Autoridad:** reúne decisiones del fundador registradas en [la auditoría histórica](../notes/2026-10-16-orientations-foundations-consistency-audit.md) y la regla vigente de [Concepts](../concepts/README.md). Las definiciones vigentes están en [Foundations](../foundations/README.md), [Concepts](../concepts/README.md) y [Orientation](../orientation/README.md). En caso de divergencia prevalece la decisión canónica específica más reciente; no convertir este bootstrap en segunda fuente divergente.

## Propósito y secuencia

Revisar **cada fundamento, uno por uno**, identificando de cuáles orientaciones nace, sus responsabilidades, los conceptos que origina o amplía y las relaciones de estos conceptos con las orientaciones. **Reformular el fundamento desde responsabilidades y orientaciones sin repetir las definiciones canónicas de los conceptos**. No avanzar al siguiente fundamento sin decisión del fundador.

Para cada Fₙ:

1. **Reconstruir el estado existente.** Leer el fundamento actual, su tabla de orientaciones, [el inventario de candidatos](../foundations/concept-candidates.md), los conceptos ya existentes que afecta, decisiones pertinentes de auditoría y mecanismos solo cuando una frontera lo requiera. Conservar decisiones previas y distinguir hipótesis, evidencia, propuestas y cierres.
2. **Verificar O→Fₙ para O0–O10.** Justificar individualmente cada orientación como **Origen, Complemento, Condición, Incidencia marginal o Sin incidencia**. Debe haber **al menos un Origen real**. Si no existe, registrar una brecha de justificación, no inventar una relación. La incidencia marginal y la ausencia se explican expresamente. Examinar tensiones relevantes, sin tratarlas como resueltas.
3. **Inventariar conceptos Fₙ→C.** Identificar conceptos **originados**, **ampliados** y términos que no ameritan concepto autónomo. Evitar duplicados, sinónimos que fragmenten el vocabulario y promoción automática de mecanismos, propiedades o candidatos. Mantener en el fundamento una tabla de conceptos con el aporte y vínculo, no copias de definiciones.
4. **Actualizar cada concepto afectado.** Mantener **una única «Definición canónica acumulativa hasta Fₙ»** que integre efectivamente el nuevo aporte (no una definición antigua más una ampliación paralela). Preservar las capas históricas ya aprobadas y añadir **una capa Fₙ** que explique:
   - qué relación tiene el concepto con el fundamento y qué responsabilidad/semántica añade Fₙ;
   - **solo las orientaciones incidentes en ese concepto a través de Fₙ**, con clasificación y justificación propias;
   - las fronteras con otros conceptos, autorizaciones y mecanismos pertinentes.
   
   **O→C no se copia de O→F**: puede diferir en clasificación, excluir orientaciones sin incidencia y requerir una justificación distinta. Si un concepto reaparece en otro fundamento, **ampliar el mismo documento** y su definición acumulativa, no crear un segundo concepto.
5. **Reformular Fₙ desde orientaciones.** Explicar **origen, responsabilidad propia, relaciones/condiciones, tensiones, límites, especificidad TDidacta si corresponde, tabla Fₙ→C y trazabilidad O→Fₙ**. No usar el fundamento como glosario duplicado, ni presentar mecanismos, conformidad, autorización, publicación o resultados empíricos como consecuencias automáticas.
6. **Verificación transversal.** Comprobar consistencia de la definición acumulativa, capas, clasificación O→F frente a O→C, enlaces, índice de Concepts y Foundations, tensiones y decisiones previas. Mantener separación entre estado reconciliado y propuesta, incluido por sección o capa cuando se mezclan aportes.
7. **Decisión del fundador.** Presentar las clasificaciones nuevas y conceptos para revisión. Registrar lo aprobado, lo observado y lo pendiente; **solo marcar reconciliado lo expresamente aprobado**. Actualizar índices y auditoría sin reescribir retrospectivamente el historial. Pasar a Fₙ₊₁ únicamente después de su instrucción.

### Restricciones que deben sobrevivir a las revisiones

- **Fundamento no es concepto ni mecanismo**: la responsabilidad y justificación viven en Foundations; la definición semántica acumulativa, en Concepts; implementaciones y procedimientos técnicos, en Mechanisms.
- **Proporcionalidad no obliga a burocracia**: ninguna revisión universal, registro por frase, aprobación por operación o dependencia tecnológica se infiere sin justificación.
- **F06/F07 y versiones inmutables**: al corregir una intención consolidada se prepara y revisa **una nueva versión candidata**, sin mutar la anterior. F07 autoriza **intenciones nuevas o versiones nuevas**; una autorización posterior conserva intactos la versión y el alcance autorizados previamente. Cambiar la versión **publicada vigente** es distinto de cambiarla en sitio y pertenece a publicación/versionamiento.
- **Investigación distinta de canon**: no inferir que IR supera a prosa o que la asistencia reduce esfuerzo sin evidencia. Reutilizar trabajos existentes, especialmente [PIR-STU-001](https://github.com/vslices/research-space/blob/main/lines/pedagogical-intent-realization/studies/stu-001-cross-realizer-semantic-conformance.md), antes de proponer otro estudio.
- **Contexto y evolución**: una orientación nueva no reabre automáticamente todas las decisiones antiguas; sí exige verificar su incidencia. Conservar la procedencia T01–T06 cuando el texto actual se reorganice.

## Formato de entrega para cada nuevo fundamento

Antes de solicitar aprobación y avanzar al siguiente fundamento, presentar una revisión en este orden:

1. **Enlaces:** vínculo directo al fundamento, a cada concepto propuesto o actualizado y a los índices pertinentes.
2. **Orientaciones O0–O10 propuestas:** tabla por orientación con clasificación (Origen, Complemento, Condición, Incidencia marginal o Sin incidencia), relación con el fundamento y justificación específica. Diferenciar propuestas de clasificaciones ya reconciliadas.
3. **Conceptos nuevos propuestos:** por cada concepto, vínculo, definición propuesta, aporte del fundamento y tabla individual de orientaciones que lo afectan mediante ese fundamento, explicando para cada una cómo y por qué. No copiar indiscriminadamente O→F.
4. **Conceptos existentes actualizados:** por cada concepto, vínculo, cambio en su única definición canónica acumulativa, aporte de la nueva capa y tabla individual de orientaciones incidentes con su efecto y justificación. Preservar capas históricas.
5. **Decisiones pendientes con formulario interactivo:** tras el resumen de propuestas a aprobar, tensiones, incertidumbres y fronteras, presentar **un único formulario compacto** que permita responder todas las decisiones del fundamento en una sola entrega. Cada decisión independiente debe tener opciones claras como **Aprobar / Solicitar cambios / Mantener pendiente**, incluyendo un campo de observaciones generales y, cuando sea necesario, observaciones específicas. Separar en la presentación decisiones sobre O→F, conceptos nuevos, conceptos ampliados y tensiones solo cuando sean realmente independientes. No confundir propuesta con reconciliación.

Presentar **conceptos nuevos y conceptos actualizados en apartados distintos**. Si alguno está vacío, indicarlo. Las tablas O→C deben corresponder a cada concepto, no a una matriz global que oculte diferencias. Este formato es obligatorio para futuras entregas y se aplica antes del cierre de cada fundamento.

**Reglas para el formulario:** aprovechar los controles interactivos disponibles en la conversación cuando existan; su envío debe producir una respuesta legible que identifique cada decisión y sus observaciones, sin asumir aprobación por silencio o por campos vacíos. Permitir respuestas parciales y no imponer aprobación global de elementos con estados distintos. Evitar formularios extensos o redundantes: agrupar decisiones equivalentes y ofrecer texto libre para excepciones. Si no hay soporte interactivo, usar una plantilla compacta de respuesta que pueda copiarse y completarse. El formulario **recoge decisiones del fundador**, no modifica por sí solo los estados canónicos: después de la respuesta se registran exclusivamente las aprobaciones explícitas en el repositorio.

## Inventario de avance — 2026-10-17

«Reconciliado» se refiere a aprobación conceptual registrada, **no** implementación ni validación de eficacia. Los estados pueden ser parciales por fundamento, orientación o capa.

| Fundamento | Documento | Estado frente a O7–O10 / conceptos | Próxima acción |
| --- | --- | --- | --- |
| **F01 — Enseñanza y aprendizaje** | [F01](../foundations/teaching-and-learning.md) | **Fundamento O0–O10 y tres capas conceptuales F01 reconciliados** (aprobación expresa 2026-10-17). | Completado |
| **F02 — Necesidades e intenciones** | [F02](../foundations/pedagogical-needs-and-intentions.md) | **Fundamento O0–O10 y tres capas conceptuales F02 reconciliados**. | Completado para esta pasada |
| **F03 — Contextualización humana** | [F03](../foundations/human-pedagogical-contextualization.md) | **O0–O10 y cinco capas conceptuales F03 reconciliados** (aprobación expresa 2026-10-17). | Completado |
| **F04 — Abstracción semántica** | [F04](../foundations/semantic-abstraction.md) | **O0–O10 y conceptos F04 reconciliados**. | Completado |
| **F05 — Proyección semántica** | [F05](../foundations/semantic-projection.md) | **O0–O10 y conceptos/capas F05 reconciliados**. | Completado |
| **F06 — Revisión y corrección** | [F06](../foundations/pedagogical-review-and-correction.md) | **O0–O10 y conceptos/capas F06 reconciliados**; integrado ciclo necesidad–revisión–nueva versión candidata. | Completado |
| **F07 — Autorización** | [F07](../foundations/pedagogical-authorization.md) | **O0–O10 y conceptos/capas F07 reconciliados**, incluidas O8 y O9 por precisión expresa del fundador. | Completado |
| **F08 — Autoría pedagógica** | [Propuesta F08](../foundations/pedagogical-authorship.md) | **Propuesta preparada** desde T01; numeración F08 y análisis O7–O10 aún no adoptados. | **Siguiente fundamento a revisar**, previa confirmación de su identificación |

**Balance:** F01–F07 están reconciliados en O0–O10 y sus capas conceptuales, por aprobación expresa del fundador (2026-10-17). F08 continúa como propuesta y siguiente fundamento a revisar.

## Condición de salida de cada revisión

Un fundamento está listo para cierre cuando (a) su origen y O0–O10 están clasificados y justificados; (b) el inventario de conceptos y las definiciones acumulativas están sincronizados; (c) cada concepto afectado tiene capa de fundamento con orientaciones incidentes justificadas; (d) el fundamento explica responsabilidades sin repetir definiciones; (e) índices, tensiones, enlaces y procedencia están sincronizados; y (f) el fundador aprueba expresamente las decisiones correspondientes.

## Trazabilidad histórica

- [Auditoría O→F y decisiones por fundamento](../notes/2026-10-16-orientations-foundations-consistency-audit.md): registro **cronológico**, conserva propuestas que después fueron corregidas, no debe leerse como estado final de cada una.
- [Origen histórico de TDidacta](README.md): memoria del surgimiento del proyecto, distinta del procedimiento operativo.
- [Concepts](../concepts/README.md): catálogo y definiciones acumulativas efectivas.
- [Foundations](../foundations/README.md): navegación a responsabilidades de fundamento.
