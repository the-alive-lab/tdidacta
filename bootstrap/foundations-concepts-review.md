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

## Regla transversal — modalidades directa y asistida (aprobada 2026-10-18)

Para cada Foundation, identificar si su responsabilidad admite apoyo tecnológico **de forma conceptual y operacionalmente coherente**. Si admite ambas modalidades, declarar:

- **Vía directa:** cómo se cumple la misma responsabilidad sin exigir asistencia tecnológica.
- **Vía asistida:** cómo una herramienta puede apoyar su cumplimiento sin alterar responsabilidad, autoridad ni alcance; ambas vías pueden combinarse.
- **Frontera:** qué decisiones humanas, distinciones semánticas y condiciones se preservan entre vías. La vía asistida no constituye por sí sola un fundamento diferente.
- **Excepción justificada:** cuando no existe coherencia conceptual u operacional en alguna vía, explicar por qué en lugar de inventar simetría. La asistencia a preparar una decisión **no equivale** a delegar la decisión misma (particularmente F07).

**Tres juicios distintos:** (1) coherencia conceptual: la modalidad preserva la responsabilidad y las fronteras; (2) coherencia operacional: es comprensible qué tareas se realizarían y cómo se relacionarían sus resultados, **sin diseñar el procedimiento técnico**; (3) **viabilidad tecnológica**, rendimiento, precisión y eficacia: deben **verificarse en la implementación de TDidacta**, no se infieren de la regla ni son requisitos para justificar conceptualmente una vía. No introducir herramientas, proveedores, algoritmos, interfaces ni workflows obligatorios en Foundations.

La regla no obliga a convertir F01 (interpretación del fenómeno educativo) en un procedimiento único ni autoriza crear actos tecnológicos de aprobación humana. Aplicarla retrospectivamente **no reclasifica automáticamente O0–O10 ni modifica capas conceptuales previamente aprobadas**.

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
| **F08 — Autoría pedagógica** | [F08](../foundations/pedagogical-authorship.md) | **O0–O10, autoría y contribución reconciliados** (2026-10-18). Autoría humana y tecnológica mediante declaración del responsable, sin auditoría; tensión O5/O7 registrada. | Completado |

**Decisión de no admisión (2026-10-18):** [Interpretación asistida de fuentes educativas](../foundations/denied/assisted-source-interpretation.md) **no se convirtió en Foundation ni recibe numeración**: sus vías directa y asistida se sitúan bajo [F03](../foundations/human-pedagogical-contextualization.md), para traducir contenido de un [documento de referencia pedagógica](../concepts/educational-source.md) (p. ej., mallas y programas MINEDUC) a TDidacta Docs Standard, sin prescribir herramientas ni su uso. El original permanece como referencia. El antecedente T02 permanece preservado. La numeración siguiente sigue libre. **Revisión cerrada por instrucción del fundador (2026-10-18)**: no queda pendiente promover la candidatura denegada; cualquier evaluación del mecanismo técnico es independiente.

**Próximo candidato a examinar (sin adopción):** [Fuentes, inferencias de IA e incertidumbre — T03](../foundations/source-inference-uncertainty.md). Contrastar su responsabilidad con F03 y F08 antes de asignarle F09.

**Candidatura adicional rechazada y archivada (2026-10-18):** [Fuentes, inferencias e incertidumbre — T03](../foundations/denied/source-inference-uncertainty.md). La atribución y distinción de procedencia corresponde a F08; el examen de afirmaciones, incertidumbres, omisiones y conflictos materiales corresponde a F06; su consideración al autorizar una versión y alcance corresponde a F07. El mecanismo de publicación y clasificación de evidencia queda independiente, sin presuponer bloqueos universales ni eficacia verificada. **La numeración F09 sigue libre.**

**Candidatura de recurrencia no promovida (2026-10-18):** [Resolución recursiva de necesidades pedagógicas](../foundations/denied/recursive-pedagogical-resolution.md), reconocida históricamente como fundamento el 2026-10-16, se reclasifica por decisión posterior del fundador: la recurrencia de necesidades e intenciones se desarrolla dentro de [F02](../foundations/pedagogical-needs-and-intentions.md), como manera de abordar el problema pedagógico interpretado en F01; Lifecycle conserva la coordinación de iteraciones posibles. F06 sigue encargado de revisar/corregir intenciones existentes. **No se asigna F09 ni se generan conceptos nuevos.**

**Balance:** F01–F08 están reconciliados en O0–O10 y las capas conceptuales abordadas. F08 fue aprobado el 2026-10-18; no se infiere con ello la eficacia de mecanismos de atribución.

## Condición de salida de cada revisión

Un fundamento está listo para cierre cuando (a) su origen y O0–O10 están clasificados y justificados; (b) el inventario de conceptos y las definiciones acumulativas están sincronizados; (c) cada concepto afectado tiene capa de fundamento con orientaciones incidentes justificadas; (d) el fundamento explica responsabilidades sin repetir definiciones; (e) índices, tensiones, enlaces y procedencia están sincronizados; y (f) el fundador aprueba expresamente las decisiones correspondientes.

## Trazabilidad histórica

- [Auditoría O→F y decisiones por fundamento](../notes/2026-10-16-orientations-foundations-consistency-audit.md): registro **cronológico**, conserva propuestas que después fueron corregidas, no debe leerse como estado final de cada una.
- [Origen histórico de TDidacta](README.md): memoria del surgimiento del proyecto, distinta del procedimiento operativo.
- [Concepts](../concepts/README.md): catálogo y definiciones acumulativas efectivas.
- [Foundations](../foundations/README.md): navegación a responsabilidades de fundamento.
