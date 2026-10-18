# Barrido profundo: «definir una vez, referenciar después»

**Fecha:** 2026-10-18  
**Ámbito:** orientación O0–O10 (11 documentos, incluido su índice), fundamentos F01–F10 (10 documentos, más índice), y los 24 conceptos enlazados desde `concepts/README.md` (más índice): **48 documentos revisados por lectura y contraste de estructura y marcadores de estado**.  
**Estado:** revisión transversal realizada con saneamiento editorial delimitado; las cuestiones semánticas quedan **no resueltas y no promovidas**. La revisión se basa en documentos indexados; no certifica ausencia de archivos huérfanos o validez de todos los enlaces del repositorio completo.

## Criterio

- **Orientation:** propiedad de objetivos, no replica tablas O→F.
- **Foundations:** propiedad de justificación, compromisos del sistema y trazabilidad O→F, no debe redefinir conceptos ni asignar sin justificación deberes a Roles.
- **Concepts:** propiedad de la única definición canónica acumulativa y de las capas justificativas O→C; las capas no son definiciones normativas paralelas.
- Los índices son navegación y estados de referencia; las explicaciones breves que hacen inteligible una frontera no constituyen automáticamente duplicación normativa.
- No reescribir decisiones reconciliadas ni textos históricos `denied` para simular continuidad.

## Corregido sin cambiar significado (main)

1. [Espacio de posibilidades pedagógico](../concepts/possibility-space.md): «Definición hasta F02» y «Ampliación acumulativa hasta F05» se unificaron en **una definición canónica acumulativa hasta F05**. Se conservaron los aportes semánticos, las capas F02/F05 y todas las clasificaciones O→C. Se corrigió la instrucción de mantenimiento que aún aludía solo a F02.
2. [Representación intermedia semántica](../concepts/semantic-intermediate-representation.md): «Ampliación F05 propuesta» coexistía con la declaración y capa reconciliadas. Se integró el mismo aporte a la definición acumulativa vigente, sin crear ni retirar obligaciones o cambiar O→C.
3. [Índice de Orientation](../orientation/README.md): O3 figuraba como «orientación propuesta», y su referencia a Foundations todavía mencionaba «sus candidatos». Se precisó su estado vigente en TDidacta y se enlazó la superficie reconciliada; la eventual generalización a PResolver sigue pendiente.

## Inventario de decisiones que sí podrían cambiar significado

El orden sugerido sigue las dependencias y reduce el riesgo de repetir decisiones. **No equivale a aprobación, rechazo ni evidencia de defecto efectivo**.

| ID | Superficies | Tensión / pregunta a resolver | Riesgo semántico |
| --- | --- | --- | --- |
| **S1** | [F01](../foundations/teaching-and-learning.md), [F02](../foundations/pedagogical-needs-and-intentions.md), [F09](../foundations/learner-autonomy.md), [Concepts](../concepts/README.md) | ¿Cómo expresar que Foundations define **lo que TDidacta debe hacer posible** y no obligaciones constitutivas de personas, cuando los textos hablan de «responsabilidad del fundamento», «quien enseña» y «quien aprende»? ¿Basta distinguir obligación del sistema vs participación del actor o se deben revisar fragmentos específicos? | Podría alterar la interpretación aprobada de F01–F10 y anticipar Responsibilities/Roles. |
| **S2** | [O4](../orientation/human-pedagogical-authorization.md), [F07](../foundations/pedagogical-authorization.md), [Concepto Autorización](../concepts/pedagogical-authorization.md) | O4 menciona «reautorización» delimitada por necesidad/dependencias mientras F07 adoptó expresamente **otra autorización de una nueva versión**, sin concepto separado de reautorización. ¿Es O4 una formulación histórica compatible o una segunda definición normativa que debe derivar a F07? | Podría cambiar condiciones de autoridad y semántica de versión. |
| **S3** | [F03](../foundations/human-pedagogical-contextualization.md), [Documento de referencia](../concepts/educational-source.md), [Registro asistido histórico](https://github.com/the-alive-lab/tdidacta/blob/893623fc4a8310ee9e8e45bd6b1e93e3deed098b^/concepts/assisted-source-interpretation.md) | La modalidad asistida tiene un documento bajo Concepts con antecedentes F09 **no adoptados**. ¿Debe seguir como registro histórico consultable o su actual ubicación se interpreta equivocadamente como un concepto canónico independiente? | Cambia autoridad/propiedad del concepto y fronteras de la asistencia T02. |
| **S4** | [F04](../foundations/semantic-abstraction.md), [F05](../foundations/semantic-projection.md), [Concepto IR](../concepts/semantic-intermediate-representation.md), [Concepto realización](../concepts/pedagogical-realization.md) | En una lectura «definir una vez» más estricta, ¿hasta dónde debe llegar la explicación de transformaciones encode/decode en Foundations sin invadir definiciones de Conceptos o Mechanisms? | Podría desplazar responsabilidades del sistema y pertenencia semántica entre superficies; **no ejecutar ahora auditoría Foundations→Mechanisms pospuesta**. |
| **S5** | [F10](../foundations/pedagogical-adaptation.md), [Escenario pedagógico](../concepts/application-circumstances.md), [propuesta de Scenarios](../README.md) | ¿Qué enunciados sobre base/especializado pertenecen exclusivamente a Concepts, cuáles justifican F10, y cómo impedir que la superficie candidata «Escenarios» se confunda con el concepto pedagógico? | Puede modificar la frontera entre responsabilidad fundacional, concepto y casos de cobertura; no reabrir F10 por mera coincidencia nominal. |

**Recomendación de navegación:** tratar primero S1, luego S2–S3, y dejar S4–S5 después, de forma individual según decisión del fundador. No alterar ningún documento canónico en estos puntos sin revisar su significado y obtener aprobación.

## Lo que deliberadamente no se «corrigió»

- Las tablas O→F de Foundations y las capas O→C de Concepts no son duplicación trivial: **responden preguntas distintas**.
- Las secciones de propósito y fronteras de F01–F10 pueden resumir conceptos para explicar **por qué TDidacta debe abordarlos**. Reducir todo a hipervínculos podría eliminar la justificación.
- Las menciones «pendiente» sobre investigación, eficacia, implementación y PResolver no son obsolescencia documental.
- El inventario histórico de candidatos y las candidaturas denegadas preservan procedencia; no promoverlos ni limpiar retrospectivamente su historia.
- Las definiciones en Concepts que mencionan funciones humanas son distintas de crear Roles o establecer obligaciones normativas universales.

## Continuidad

**No se ha certificado exhaustividad de la estructura documental**: este barrido abarca los archivos canónicos indexados y controles semánticos/editoriales dirigidos; no ejecutó una validación automatizada de todos los enlaces ni una auditoría de todo `Mechanisms`. La reconstrucción V6 T01–T28, la auditoría Foundations→Mechanisms y la validación investigativa O3/F10 continúan respectivamente futura, pospuesta y pendiente.

## Resolución posterior y priorización del fundador (2026-10-18)

**S1 — Diferido:** examinar en la definición de la futura superficie de **responsables/responsabilidades**, sin reescribir por ahora F01/F02/F09.

**S2 — Resuelto por aclaración explícita:** el fundador rechazó el término normativo «reautorización». Intenciones/versions autorizadas permanecen inmutables y autorizadas para su alcance; corregir exige nueva versión candidata (p. ej., v1.1), revisión y autorización nueva, sin tocar autorización histórica de v1.0, aunque v1.0 quede desactualizada. Se actualizó [O4](../orientation/human-pedagogical-authorization.md) para eliminar su enunciado contradictorio; [F07](../foundations/pedagogical-authorization.md) y [Autorización pedagógica](../concepts/pedagogical-authorization.md) ya sostenían esa semántica y no se modificaron.

**S3 — No resuelto:** [Interpretación asistida de fuentes (antecedente eliminado del catálogo)](../foundations/denied/assisted-source-interpretation.md) conserva expresamente su estado de registro de modalidad con **candidatura F09 no admitida como fundamento**. El fundador solicita primero consultar el documento para decidir si su ubicación en Concepts es meramente histórica. No se mueve, renombra ni promueve.

**S4 — Contraste de frontera concluido sin cambio semántico:** [F04](../foundations/semantic-abstraction.md) explica por qué TDidacta debe poder abstraer significado desde documentación; [F05](../foundations/semantic-projection.md) explica por qué debe poder aprovechar representaciones para exploración/realización. [Abstracción](../concepts/semantic-abstraction.md), [Proyección](../concepts/semantic-projection.md), [IR](../concepts/semantic-intermediate-representation.md) y [Realización](../concepts/pedagogical-realization.md) contienen definiciones acumulativas y capas propias. Las síntesis F04/F05 explican condiciones e implicaciones fundacionales y remiten a Concepts; no constituyen, por sí solas, definiciones normativas alternativas. **No se justifica una reducción que pudiera borrar justificación fundacional.** Queda fuera de alcance revisar límites técnicos de Mechanisms, auditoría pospuesta. Resultado de S4: **sin cambio necesario** en Foundations/Concepts.

**S5 — Distinción aceptada:** la superficie candidata *Escenarios* refiere al **contexto/circunstancias del responsable** y su aparición situada; el [concepto Escenario pedagógico](../concepts/application-circumstances.md) refiere a aplicar una intención pedagógica bajo circunstancias base/especializadas. Se aclaró el [README](../README.md); F10 y su concepto reconciliado permanecen intactos.

**Inventario después de esta revisión:** S2 resuelto; S4 contrastado y cerrado sin cambios; S5 aclarado documentalmente; S1 diferido a superficie de responsables y S3 a evaluación de su registro histórico. No se modifica el alcance pendiente de O3/F10 ni se inicia T01–T28.


## Decisión posterior — S3 descartado como concepto (2026-10-18)

Por decisión expresa del fundador, **Interpretación asistida de fuentes no es un concepto autónomo**: la [vía asistida está cubierta por F03](../foundations/human-pedagogical-contextualization.md) y el desarrollo operativo corresponde al [mecanismo candidato T02](../mechanisms/assisted-material-interpretation.md), que permanece diferido. Se retiró la entrada de [Concepts](../concepts/README.md) y se eliminó `concepts/assisted-source-interpretation.md` de `main`. Su contenido histórico continúa recuperable en el historial Git y en la [candidatura no admitida](../foundations/denied/assisted-source-interpretation.md); **no se promovió ni reescribió el mecanismo**.

**Inventario activo tras esta decisión:** S1 pendiente para la superficie de responsables; **S2, S3, S4 y S5 resueltos o delimitados sin cuestiones pendientes en este control**. La auditoría Foundations→Mechanisms sigue pospuesta.
