# Bootstrap operativo — desarrollo progresivo de TDidacta a partir de V6

**Estado:** seguimiento de trabajo; no definición canónica ni investigación concluida.  
**Inicio:** 2026-10-16.  
**Ámbito:** cobertura progresiva de responsabilidades preservadas en V6, contrastadas con TDidacta y la experiencia de organización de VSlices.

## Propósito y autoridad

Permitir retomar el trabajo por tópico sin depender de conversaciones anteriores; registrar qué se examinó, qué se decidió, qué quedó pendiente y dónde está la evidencia. **Completar una revisión no significa adoptar una definición ni probar su eficacia.** No copiar V6 íntegra ni forzar una estructura de productos o carpetas.

- [V6 aprobada como maestro editorial de preservación](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md): inventario y antecedentes, no canon automáticamente incorporado.
- [TDidacta](../README.md), [Orientation](../orientation/README.md), [Governance](../governance/README.md), [AGENTS](../AGENTS.md): autoridad y reglas locales.
- [VSlices](https://github.com/the-alive-lab/vslices): referencia comparativa para criterios de organización, propiedad semántica, mecanismos, relaciones y promoción; **no** transferencia automática de conceptos.
- [Project Generation Rules](https://github.com/the-alive-lab/project-generation-rules): consultar al extender o reorganizar documentación, como referencia compartida no automáticamente normativa.
- [Research](https://github.com/vslices/research-space): fuente de investigación y evidencia con autoridad distinta. No editar retrospectivamente artefactos congelados.

## Estados del seguimiento

- **Pendiente:** no se ha realizado una revisión suficiente de este tópico con el procedimiento de este bootstrap; puede existir documentación previa.
- **En curso:** revisión iniciada con fuentes y preguntas abiertas registradas.
- **Bloqueado:** impide concluir un requisito identificable (decisión, fuente o evidencia); registrar causa.
- **Revisado:** se ha documentado la correspondencia, límites, decisión de tratamiento y referencias de salida. Puede terminar sin cambios, con propuesta candidata o con preguntas abiertas.
- **Cerrado:** el tratamiento acordado quedó realizado o se decidió justificadamente no actuar; están enlazadas las decisiones, archivos y comprobaciones. **No implica estado epistemológico validated o adopted.**

El estado de seguimiento es independiente del estado **candidate / active / stable** (o el que corresponda) de los conceptos y de la **autoridad de adopción**. No inferir progreso únicamente por existencia de archivos. El inventario inicial es **pendiente de revisión sistemática**, aunque varios temas ya tengan definiciones parciales.

## Procedimiento reutilizable por tópico

1. Elegir **un** tópico pendiente. Registrar necesidad concreta, alcance y superficies potencialmente relacionadas, sin presumir que necesita documento propio.
2. Revisar definiciones actuales de TDidacta (desde README, Orientation y Governance, después solo las superficies pertinentes), además del fragmento material de V6. Distinguir definición vigente, candidato, testimonio y evidencia.
3. Contrastar selectivamente con VSlices: `foundations/`, `mechanisms/`, `relationships/`, `lifecycle/`, `products/`, `promotion/` y otras superficies **solo si aportan al caso**. Preguntar qué es reutilizable como criterio, qué es adaptable, qué no aplica y qué sigue incierto. Separar **uso** de **propiedad semántica**.
4. Si la tarea crea o reorganiza documentos, consultar Project Generation Rules y preferir la extensión mínima de estructuras existentes. No reproducir automáticamente la familia Method/Design/Docs Standard/Framework/Platform.
5. Cuando corresponda, revisar Research: estudios, resultados, límites, protocolos y evidencia; no convertir observaciones en resultados de aprendizaje ni inventar validaciones.
6. Preparar una propuesta con: concepto/responsabilidad, correspondencia V6 ↔ TDidacta, lectura comparativa de VSlices, autoridad, límites, alternativas, cambios propuestos y pendientes.
7. Aplicar modificaciones solo cuando la operación esté autorizada. Actualizar enlaces e índices afectados; conservar procedencia, contexto y decisiones. Verificar referencias y navegación.
8. Registrar el resultado en este documento. **Inmediatamente después del cierre de un tópico**, examinar su impacto sobre **todos los demás tópicos, abiertos y cerrados**. Registrar relaciones, decisiones reutilizables, límites y aplazamientos; para los ya cerrados, comprobar coherencia y detectar contradicciones o tensiones con las decisiones previamente adoptadas. **No modificar automáticamente el estado ni las decisiones de otros tópicos**: documentar hallazgos, evidencia y necesidad de revisión.
9. Al iniciar un tópico futuro, leer primero los impactos recibidos de tópicos anteriores, contrastarlos con las fuentes vigentes y evitar reconstruir desde cero lo ya justificado. Escoger entonces el siguiente tópico; **no** marcar `cerrado` por haberlo analizado solamente.

### Registro mínimo de una revisión

```md
#### TNN — Nombre
- Estado de seguimiento: pendiente | en curso | bloqueado | revisado | cerrado
- Fecha y responsable:
- Problema / alcance:
- Fuentes de TDidacta y correspondencia V6:
- VSlices (reutilizable | adaptable | no aplicable | incierto) y por qué:
- Investigación / evidencia disponible y límites:
- Decisión: conservar | extender | proponer | no incorporar | aplazar
- Estado de autoridad: vigente | candidato | pendiente de aprobación | otro (explicar)
- Archivos o decisiones afectados (enlaces):
- Preguntas, bloqueos y siguiente acción:
- Retroalimentación sobre otros tópicos (IDs, tipo de impacto, decisión reutilizable, pendiente y enlace):
```

## Inventario de cobertura (inicial, sin priorización definitiva)

Marcar el estado de cada ítem cuando exista un registro mínimo verificable. No agruparlos en productos antes de contrastar responsabilidades.

| ID | Tópico | Estado de seguimiento | Resultado / enlace |
| --- | --- | --- | --- |
| T01 | Autoría pedagógica | Cerrado | [Autoría](../foundations/pedagogical-authorship.md) y [transparencia](../transparency/README.md); **observación: publicación pendiente de PResolver y The Alive Lab**; [trabajo posterior](../mechanisms/contribution-gradient.md) |
| T02 | Interpretación asistida de fuentes educativas | Cerrado | [Delimitación aprobada](../foundations/assisted-source-interpretation.md): complementa interpretación desde cero; no requiere mecanismo técnico universal |
| T03 | Diferenciación entre fuentes, inferencias de IA e incertidumbre | Cerrado | [Fundamento](../foundations/source-inference-uncertainty.md) y [clasificación de evidencia](../mechanisms/evidence-classification.md); validación de carga diferida |
| T04 | Contextualización pedagógica humana | Revisado | [Propuesta T04](../foundations/human-pedagogical-contextualization.md), pendiente de aprobación humana |
| T05 | Revisión y corrección pedagógica | Pendiente | — |
| T06 | Autoridad y autorización de realizaciones | Pendiente | — |
| T07 | Publicación de realizaciones pedagógicas | Pendiente | — |
| T08 | Procedencia y trazabilidad pedagógica | Pendiente | — |
| T09 | Versionamiento de fuentes, intenciones y realizaciones | Pendiente | — |
| T10 | Continuidad pedagógica entre actores | Pendiente | — |
| T11 | Transferencia de responsabilidades pedagógicas | Pendiente | — |
| T12 | Revisión ante cambios de contexto y dependencias | Pendiente | — |
| T13 | Exportación estable de realizaciones aprobadas | Pendiente | — |
| T14 | Portabilidad de conocimiento y materiales educativos | Pendiente | — |
| T15 | Evaluación de conformidad semántica | Pendiente | — |
| T16 | Evaluación de calidad pedagógica | Pendiente | — |
| T17 | Evaluación de comprensión, transferencia y autonomía del aprendiz | Pendiente | — |
| T18 | Evaluación del esfuerzo humano neto | Pendiente | — |
| T19 | Accesibilidad y diversidad de medios educativos | Pendiente | — |
| T20 | Adaptación a contextos docentes e institucionales | Pendiente | — |
| T21 | Coordinación institucional y sus límites frente a la pedagogía | Pendiente | — |
| T22 | Privacidad, consentimiento y derechos sobre materiales educativos | Pendiente | — |
| T23 | Publicación comunitaria de contenidos | Pendiente | — |
| T24 | Autoalojamiento e interoperabilidad | Pendiente | — |
| T25 | Modalidades de inferencia y exploración asistida | Pendiente | — |
| T26 | Acceso público y sostenibilidad económica | Pendiente | — |
| T27 | Continuidad y recuperación ante cierre del servicio | Pendiente | — |
| T28 | Relación entre TDidacta y la organización operadora de The Alive Lab | Pendiente | — |

## Retroalimentación transversal después de cada cierre

**Regla operativa:** al cerrar un tópico, revisar **todos los demás tópicos, tanto abiertos como cerrados**, y registrar únicamente impactos explicables con decisiones o artefactos concretos. En los abiertos, identificar continuidad aprovechable y pendientes; en los cerrados, **verificar consistencia y buscar contradicciones, tensiones o supuestos invalidados**. Distinguir *decisión reutilizable*, *delimitación de alcance*, *antecedente candidato* y *ausencia de avance directo*. No convertir automáticamente correspondencias en progreso demostrado, ni modificar automáticamente estados o decisiones de tópicos receptores. Un conflicto con un tópico cerrado debe registrarse con enlaces y proponerse para revisión explícita, sin reabrirlo ni corregirlo silenciosamente. Este registro es un **índice de continuidad**, no reemplaza los documentos de cada responsabilidad.

Para cada cierre, consignar: tópico origen, fecha, tabla de tópicos receptores **abiertos y cerrados**, impacto fundado, resultado de verificación de coherencia, posibles contradicciones, qué queda por resolver y fuentes/enlaces. Si nuevos cierres contradicen registros previos, añadir una corrección trazable sin reescribir hechos históricos.

### Precisiones aprobadas al revisar tensiones de T01 — 2026-10-16

- **Clasificación manual ahora:** el profesional humano que crea el recurso declara y selecciona manualmente su clasificación entre las cuatro denominaciones provisionales, visible junto al recurso. La declaración no implica comprobación automática ni validación de calidad. La interfaz y persistencia concretas todavía requieren definición e implementación. **No depende de finalizar el gradiente**; automatización, umbrales y posibles ampliaciones sí permanecen aplazados. Ver [Transparencia](../transparency/README.md) y [gradiente](../mechanisms/contribution-gradient.md).
- **Responsabilidades separadas:** origen de necesidad, formulación de intención, creación, supervisión, autorización y publicación deben distinguirse conceptualmente, **aunque una sola persona desempeñe todas esas funciones**. Ver [Autoría pedagógica](../foundations/pedagogical-authorship.md).
- **Se conserva la tercera observación:** cierre de T01 no promueve automáticamente a universales los mecanismos candidatos ni declara su implementación.
- **Impactos en tópicos abiertos:** T05 y T06 reutilizarán la separación de funciones; T07 distinguirá autorización, clasificación y publicación; T23 y T25 considerarán declaración manual sin atribuirle verificación automática; T15/T16 no confundirán clasificación, autorización y calidad. **Sus estados no cambian**.
- **Consistencia con T01 cerrado:** estas precisiones desarrollan su alcance autorizado; no se identifica necesidad de reabrirlo.

### Retroalimentación de T01 hacia tópicos restantes — 2026-10-16

**Origen:** [T01 autoría pedagógica](../foundations/pedagogical-authorship.md), [transparencia](../transparency/README.md), [gradiente candidato](../mechanisms/contribution-gradient.md), [feedback candidato](../mechanisms/feedback-traceability.md). Cierre autorizado para alcance 31-10-2026; trabajos avanzados aplazados. **Ningún estado receptor cambia**. Los grados siguientes describen solo reutilización cualitativa, no porcentajes completados.

| Tópico receptor | Impacto de T01 | Continuidad aprovechable | Pendiente específico |
| --- | --- | --- | --- |
| T02 | Parcial | Separación entre autor de fuente, intérprete y autorizador; IA no adquiere autoridad | Definir interpretación asistida, manejo de omisiones y revisión |
| T03 | Sustancial | Fuente, interpretación y generación inferencial no son equivalentes; procedencia explícita | Representación y detección de incertidumbre |
| T04 | Sustancial | Una persona responde a necesidad situada para destinatarios distintos; formula intención | Criterios de contextualización y delimitación |
| T05 | Sustancial | Persona que formula intención supervisa su material en el alcance actual | Procedimiento de revisar, corregir o rechazar |
| T06 | Sustancial | La misma persona formula intención y autoriza su material; no hay aprobación institucional multinivel antes del hito | Condiciones y límites de autorización situada |
| T07 | Parcial | Autorizar no equivale a publicar ni tener titularidad | Condiciones de publicación y diferenciación de estados |
| T08 | Parcial | Autoría diferenciada de procedencia; feedback trazable como mecanismo candidato aplazado | Trazabilidad mínima; no exigir mecanismo avanzado antes del hito |
| T09 | Antecedente | Se distinguen aportes según objetos/versiones en propuesta candidata | Identidad y cambios de versiones |
| T10 | Parcial | Necesidad, responsable y destinatarios pueden diferir | Continuidad al cambiar participantes |
| T11 | Parcial | Roles no institucionales y autoridad situada delimitada | Transferencia de contexto/responsabilidad |
| T12 | Antecedente | Retroalimentación puede originar revisión; trazabilidad avanzada aplazada | Revisión de dependencias y cambios |
| T13 | Antecedente | Distinguir material autorizado de generación provisional | Exportación estable |
| T14 | Antecedente | Separación fuente/intención/realización | Qué se transfiere y cómo |
| T15 | Parcial | Autorización humana no demuestra conformidad semántica | Criterios propios de conformidad |
| T16 | Antecedente | Autorización no equivale a calidad | Evaluación pedagógica independiente |
| T17 | Antecedente | La responsabilidad docente no garantiza aprendizaje | Medición de comprensión y autonomía |
| T18 | Sin avance directo | No se derivan métricas del trabajo de autoría | Medición de esfuerzo humano neto |
| T19 | Sin avance directo | No se definieron medios ni accesibilidad | Criterios de accesibilidad y variación de medios |
| T20 | Parcial | Contextualización por un responsable individual, sin aprobación multinivel | Adaptación; institucionalidad avanzada diferida |
| T21 | Delimitación de alcance | Aprobación multinivel fuera del alcance previo a 31-10-2026 | Coordinación institucional sigue pendiente |
| T22 | Parcial | Diferenciar identificación, consentimiento, derechos, privacidad y autorización; no aplazado automáticamente | Salvaguardas y bases jurídicas por contexto antes de tratar datos reales |
| T23 | Antecedente | Autorización del material no equivale a derecho de publicación | Publicación comunitaria y permisos |
| T24 | Sin avance directo | No se establecieron capacidades técnicas | Autoalojamiento e interoperabilidad |
| T25 | Parcial | Declaración manual de IA por profesional responsable entre cuatro denominaciones; la clasificación automática continúa supeditada al gradiente | Modalidades y límites de inferencia; implementación de declaración manual |
| T26 | Sin avance directo | No se definió sostenibilidad | Acceso y modelo económico |
| T27 | Antecedente | Distinción de fuentes y realizaciones podría ayudar a portabilidad | Recuperación tras cierre del servicio |
| T28 | Sin avance directo | No se resolvió autoridad organizacional | Relación operativa con The Alive Lab |

**Procedimiento al retomar uno de estos tópicos:** consultar primero esta fila y sus fuentes de T01, verificar vigencia, y luego estudiar únicamente las brechas restantes. La evidencia de T01 puede reducir reconstrucción, pero no sustituye la evaluación propia del tópico.

## Bitácora de ejecución

### T04 — Contextualización pedagógica humana (2026-10-16)

- **Estado:** Revisado, **no cerrado**; propuesta conceptual pendiente de aprobación humana.
- **Problema:** la fuente o el contenido no se vuelven intención situada automáticamente; hace falta reconocer condiciones de necesidad, destinatarios, materias, tiempo, personas y límites sin imponer una plantilla.
- **Continuidad T01:** quien formula, supervisa y autoriza responde a destinatarios que pueden ser otros, aunque cada responsabilidad se evalúa separadamente.
- **Continuidad T02:** la interpretación desde cero y la asistida son vías disponibles; ninguna sustituye contextualización humana.
- **Continuidad T03:** respaldo, inferencias e incertidumbre deben permanecer distinguibles cuando sean relevantes; no transferir al responsable una carga exhaustiva de clasificación.
- **TDidacta/V6:** [necesidades e intenciones](../foundations/pedagogical-needs-and-intentions.md), [relaciones](../relationships/pedagogical-resolution-relations.md), [V6 editorial](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md).
- **VSlices:** aprovechable distinguir autoridad, definición y realización; no copiar estructura de software como ley pedagógica.
- **Salida:** [propuesta de contextualización humana](../foundations/human-pedagogical-contextualization.md), sin mecanismo técnico universal ni validación empírica.
- **Fronteras:** T05/T06 revisión y autorización; T08/T09 procedencia y versiones; T12 cambios; T15 conformidad; T19 accesibilidad; T20 contextos institucionales; T22 privacidad.
- **Pendiente de cierre:** aprobación del criterio proporcional de contextualización y de sus límites. La retroalimentación con todos los tópicos, incluidos T01–T03 cerrados, se ejecutará tras el cierre.


### Cierre de T03 y retroalimentación transversal — 2026-10-16

- **Decisión del fundador:** T03 **Cerrado** en su alcance conceptual. Se adopta como delimitación del tópico el [mecanismo de clasificación de evidencia](../mechanisms/evidence-classification.md) para evidencia humana e inferencial; se conserva el [fundamento](../foundations/source-inference-uncertainty.md).
- **Límite de cierre:** construir y validar una implementación que **facilite** clasificar y reduzca la carga humana es trabajo posterior; no se presume reducción efectiva de trabajo, clasificación automática fiable ni implementación actual.
- **Relación T02/T03:** [pendiente de revisión](../relationships/assisted-interpretation-evidence-classification.md), no dependencia técnica adoptada. El mecanismo detallado [T02](../mechanisms/assisted-material-interpretation.md) permanece pospublicación de PResolver.
- **Verificación de tópicos cerrados:** T01 y T02 examinados; **sin contradicciones identificadas** en el alcance de las definiciones actuales. La distinción entre clasificación global de recurso (T01) y clasificación de evidencia (T03) debe conservarse. La propuesta de uso por T02 no cambia su cierre.
- **Tópicos receptores:** todos los otros 27 tópicos contrastados; ningún estado cambia. La siguiente tabla recoge continuidad útil, tensiones y límites, no porcentaje realizado.

| Receptor | Resultado | Efecto y continuidad de T03 | Pendiente |
| --- | --- | --- | --- |
| T01 | Cerrado; consistente | La clasificación de evidencia por afirmación no es la declaración global/manual del modo de elaboración, ni autoría ni autorización. | Preservar separación; sin reapertura. |
| T02 | Cerrado; consistente con dependencia candidata | La interpretación asistida puede utilizar clasificación de evidencia de T03, pero su integración técnica y relación `uses` no están aprobadas. | Mantener mecanismo T02 y relación en revisión para después de publicación PResolver. |
| T04 | Directo | Necesidades situadas pueden interpretarse con afirmaciones humanas o de IA cuyo respaldo y límites son distinguibles. | Criterios de contextualización y uso adecuado de incertidumbre. |
| T05 | Directo | Quien supervisa puede aceptar, corregir, rechazar o dejar pendientes clasificaciones; no obligar revisión exhaustiva. | Definir controles de revisión y prioridades proporcionales. |
| T06 | Directo | Clasificar evidencia no autoriza el conocimiento, aunque ambas tareas recaigan en la misma persona. | Condiciones de autorización situada ante dudas relevantes. |
| T07 | Parcial | Publicar requiere no confundir inferencia provisional con afirmación aprobada. | Estados y reglas de publicación. |
| T08 | Directo | La legibilidad sobre origen/respaldo exige reconstrucción proporcional de fuente, interpretación y dudas. | Definir procedencia mínima sin imponer registros exhaustivos. |
| T09 | Parcial | Correcciones en clasificación y evidencia pueden necesitar continuidad entre versiones. | Qué se versiona y bajo qué condiciones. |
| T10 | Parcial | Dudas y apoyos relevantes deben ser legibles para nuevos participantes. | Continuidad pedagógica entre actores. |
| T11 | Parcial | Handoff de material debe distinguir respaldo, inferencia y cuestiones abiertas. | Qué información transferir y con qué responsabilidad. |
| T12 | Directo | Cambios en fuentes o premisas pueden invalidar respaldo y suscitar revisión. | Detección y alcance de revalidaciones. |
| T13 | Parcial | Exportación aprobada puede preservar advertencias relevantes sin presumir que evidencia esté verificada. | Contrato de exportación estable. |
| T14 | Parcial | Portabilidad requiere no borrar procedencia e incertidumbre pertinente. | Modelo de transferencia y derechos. |
| T15 | Directo | Conformidad semántica no equivale a clasificación correcta ni a certeza de la fuente. | Oráculo de conformidad propio. |
| T16 | Directo | Evidencia clasificada no prueba calidad educativa ni corrección material. | Evaluación de calidad separada. |
| T17 | Parcial | Una afirmación respaldada no demuestra comprensión o transferencia del aprendiz. | Evaluación de resultados independiente. |
| T18 | Directo | Riesgo explícito de carga alta por clasificar y revisar; cualquier sistema debe facilitarla. | Medir esfuerzo total, incluidas correcciones y mantenimiento. |
| T19 | Antecedente | La legibilidad de clasificaciones e incertidumbres debe ser comprensible en cada medio. | Accesibilidad de su presentación, sin solución adoptada. |
| T20 | Parcial | La importancia de incertidumbre y evidencia depende del contexto humano, sin exigir jerarquías institucionales. | Adaptación situada y casos institucionales posteriores. |
| T21 | Sin avance directo | No se deduce coordinación institucional de clasificar evidencia. | Coordinar instituciones continúa fuera del alcance inicial. |
| T22 | Directo | Evidencia puede contener datos personales o derechos de terceros; legibilidad no autoriza difundirla. | Salvaguardas y minimización antes de tratamiento real. |
| T23 | Parcial | Publicar material de otros no queda legitimado por citar o clasificar evidencia. | Derechos y criterios de publicación comunitaria. |
| T24 | Sin avance directo | No implica capacidad técnica de autoalojamiento o interoperabilidad. | Definir despliegue e interfaces. |
| T25 | Directo | La clasificación podría asistir exploraciones inferenciales sin ser verificación automática. | Modalidades de inferencia y límites, respetando relación T02/T03 candidata. |
| T26 | Antecedente | El costo de clasificar y revisar puede afectar sostenibilidad. | Costeo separado, aún no definido. |
| T27 | Antecedente | Conservar respaldo y advertencias puede importar al recuperar material. | Recuperación efectiva no garantizada. |
| T28 | Sin avance directo | Clasificación no determina competencia de The Alive Lab como operador. | Gobernanza organizacional independiente. |

**Observaciones transversales:** (a) facilitar la clasificación y comprobar el esfuerzo en uso real es una exigencia de diseño futuro, no eficacia demostrada; (b) ninguna clasificación de evidencia por sí misma aprueba, publica ni garantiza fidelidad, verdad, calidad o aprendizaje; (c) los tópicos cerrados se conservaron sin reapertura automática. **Siguiente:** T04 queda disponible, pendiente de revisión propia.


### Ampliación aprobada de T03 y continuidad T02 — 2026-10-16

- **Decisión sobre T03:** el fundador acepta la clasificación conceptual de evidencia de **origen humano e inferencial**, con una condición operativa: la aplicación puede imponer alta carga al responsable; el sistema deberá **facilitar y simplificar el proceso** en vez de delegarle etiquetado exhaustivo. [Mecanismo T03](../mechanisms/evidence-classification.md); [fundamento T03](../foundations/source-inference-uncertainty.md).
- **No confundir:** clasificación de evidencia por afirmación/aspecto relevante ≠ clasificación manual global de elaboración de recursos acordada en T01.
- **T02:** creado el [archivo de mecanismo de interpretación asistida](../mechanisms/assisted-material-interpretation.md). Su **definición detallada se mantiene pendiente hasta después de publicación de PResolver**; no se reabre T02.
- **Relación candidata:** T02 *utilizaría* el mecanismo T03. Queda **pendiente de revisión**, sin adoptar una dependencia técnica; ver [Relationships](../relationships/assisted-interpretation-evidence-classification.md).
- **T03:** permanece **Revisado** mientras se registre su cierre explícito. La retroalimentación transversal sobre abiertos y cerrados se ejecutará con el cierre, no se declara completada antes.
- **Límites:** no afirmar implementación, reducción de carga comprobada, clasificación automatizada confiable ni métricas validadas.


### T03 — Fuentes, inferencias e incertidumbre (2026-10-16)

- **Estado:** Revisado, **no cerrado**; propuesta conceptual pendiente de aprobación de Hernán.
- **T01/T02 heredados:** autoría y autorización distintas; fuente no equivale a interpretación; IA propone sin asumir autoridad; interpretación humana desde cero es válida y la asistida es complementaria.
- **Problema:** evitar atribuir extrapolaciones, interpretaciones y omisiones a fuentes, o convertir incertidumbre en conocimiento aparentemente autorizado.
- **TDidacta/V6:** [conceptos candidatos](../foundations/concept-candidates.md), [T02](../foundations/assisted-source-interpretation.md), [V6 editorial](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md).
- **VSlices:** aplicable como criterio separar autoridad semántica de realización; no importar esquema de ingeniería.
- **Decisión documental:** [propuesta de T03](../foundations/source-inference-uncertainty.md), delimitando afirmación respaldada, interpretación humana, inferencia de IA, incertidumbre, ambigüedad, omisión y conflicto. Legibilidad proporcional, sin instrumento obligatorio.
- **Autoridad y límites:** solo propuesta; sin validación de detección automática de inferencias, extracción o conformidad. Controles concretos siguen en T04–T09 y T25; el mecanismo IA detallado de T02 sigue aplazado.
- **Preguntas para revisión humana:** aceptar este mínimo de legibilidad como responsabilidad T03 y mantener diseños automáticos detallados para después de publicación.
- **Retroalimentación transversal:** corresponde al cierre de T03; todavía no se ejecuta ni se modifican otros estados.


### Retroalimentación transversal de T02 — 2026-10-16

**Decisión aprobada:** interpretar desde cero es la vía normal disponible para quien asume responsabilidad pedagógica; interpretar fuentes mediante asistencia de IA es una **vía complementaria, opcional**, con revisión humana. No se exige pipeline universal, fuente formal para cada intención ni implementación declarada. Fuente: [T02](../foundations/assisted-source-interpretation.md).

**Control sobre tópico cerrado T01:** **consistente**. La autoría, supervisión y autorización humana siguen diferenciadas, incluso cuando recaen en una persona; la clasificación manual de uso de IA continúa separada del juicio de fidelidad de la interpretación. No se identifica contradicción ni necesidad de reabrir T01.

**Impactos sobre todos los tópicos abiertos** (sin cambios de estado):

| Receptor | Efecto heredado de T02 y límite de continuidad |
| --- | --- |
| T03 | **Directo:** exige separar material fuente, inferencia, ambigüedad y omisión; desarrollar criterios de identificación, representación y revisión |
| T04 | **Directo:** persona contextualiza tanto una interpretación propia desde cero como una propuesta asistida; delimitar criterios |
| T05 | **Directo:** acepta, corrige o rechaza propuestas inferenciales; definir suficiencia de revisión |
| T06 | **Directo:** interpretación asistida no autoriza automáticamente; conservar autorización humana situada |
| T07 | **Parcial:** propuestas interpretativas no equivalen a publicaciones; definir condiciones específicas |
| T08 | **Directo:** origen y distinción fuente/inferencia deben ser reconstruibles proporcionalmente; soporte técnico pendiente |
| T09 | **Parcial:** revisiones de interpretación pueden requerir versiones; no se adopta esquema |
| T10 | **Parcial:** lectura revisable debe ser inteligible para destinatarios distintos; continuidad pendiente |
| T11 | **Parcial:** contexto de la interpretación puede ayudar a transferencia; no se aprueba delegación automática |
| T12 | **Parcial:** fuentes o supuestos cambiantes pueden requerir relectura; detección pendiente |
| T13 | **Parcial:** insumos interpretativos no equivalen a realizaciones aprobadas exportables |
| T14 | **Parcial:** la separación origen/interpretación favorece portabilidad; mecanismos pendientes |
| T15 | **Directo:** fidelidad interpretativa no demuestra conformidad semántica de una realización |
| T16 | **Parcial:** extracción legible no demuestra calidad pedagógica |
| T17 | **Sin resolución:** interpretar fuentes no prueba comprensión ni autonomía de aprendices |
| T18 | **Antecedente:** revisión humana puede incidir en esfuerzo neto; no se presume ahorro |
| T19 | **Sin resolución:** no se fijan medios accesibles ni adaptaciones |
| T20 | **Parcial:** interpretación situada sirve a contextos individuales; coordinación institucional avanzada sigue fuera de alcance previo al hito |
| T21 | **Sin resolución:** no introduce aprobación multinivel ni coordinación institucional |
| T22 | **Directo:** materiales deben tener derechos de uso adecuados y los datos sensibles no transferirse sin autorización; salvaguardas pendientes |
| T23 | **Parcial:** interpretar material ajeno no concede derecho a publicarlo comunitariamente |
| T24 | **Sin resolución:** recorrido conceptual no implica autoalojamiento o interoperabilidad disponible |
| T25 | **Directo:** interpretar con IA es modalidad posible, no obligatoria; proveedor, límites y modalidades por definir |
| T26 | **Sin resolución:** no presupone disponibilidad o gratuidad de inferencia |
| T27 | **Antecedente:** conservar origen e interpretación puede favorecer recuperación; no garantiza continuidad operativa |
| T28 | **Sin resolución:** no asigna autoridad de interpretación a The Alive Lab como organización |

**Resultado de consistencia:** no hay conflictos detectados con T01 en el alcance revisado. **Estados receptores:** sin cambios. Esta matriz registra dependencias documentales, no validación ni ejecución de los restantes tópicos.


### T02 — Interpretación asistida de fuentes educativas (2026-10-16)

- **Estado actualizado por decisión humana:** Cerrado en su alcance conceptual; no implica implementación ni adopción de técnica universal.
- **Continuidad T01:** separa fuente, intérprete, intención y autoridad humana; la clasificación manual de asistencia no demuestra fidelidad.
- **Problema:** lectura asistida de fuentes con uso permitido sin confundir contenido original, propuestas inferenciales, incertidumbre o decisiones de quien enseña.
- **TDidacta y V6:** [necesidades e intenciones](../foundations/pedagogical-needs-and-intentions.md), [exploración/realización](../mechanisms/exploration-and-realization.md), [V6 editorial](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md).
- **VSlices:** separación de autoridad semántica y realización aprovechable como criterio, no modelo técnico importado.
- **Salida documental:** [propuesta T02](../foundations/assisted-source-interpretation.md) y entrada en Foundations. El recorrido es conceptual y flexible; sin validación empírica.
- **Fronteras:** T03 (incertidumbre), T04–T06 (contextualización/revisión/autorización), T08/T09 (procedencia/versiones), T22/T25 (derechos e inferencia).
- **Decisión de cierre:** el fundador acepta sin observaciones el alcance propuesto; interpretación asistida como complemento de la interpretación desde cero. Procedencia detallada y controles concretos siguen en T03/T08. Retroalimentación transversal ejecutada arriba.
- **Precisión posterior del fundador (2026-10-16):** el mecanismo detallado de cómo una IA interpreta fuentes queda como **propuesta pendiente de definición para una versión posterior a la publicación de PResolver**. No cambia el cierre de T02, su alcance conceptual ni la retroalimentación transversal existente; no aplaza automáticamente T03, T08 o T25.


### Cierre autorizado de T01 — 2026-10-16

- **Decisión de Hernán:** T01 — Autoría pedagógica queda **Cerrado** para el alcance documental y operativo acordado.
- **Observación expresa:** **pendiente la publicación de PResolver y de The Alive Lab**. El cierre de T01 no afirma que esa publicación haya ocurrido, ni la convierte en requisito para reabrir la definición conceptual.
- **Continuidad:** el gradiente multidimensional, la evaluación de contribuciones, la trazabilidad avanzada de feedback y las condiciones detalladas de atribución siguen como propuestas para después de la entrega formal de PResolver del 31-10-2026. Privacidad, consentimiento y reutilización mantienen su tratamiento separado (T22) y salvaguardas previas a tratamientos reales.
- **Estado de las definiciones:** el cierre del tópico no promueve automáticamente mecanismos candidatos a normas universales ni declara funcionalidades implementadas.
- **Siguiente tópico:** T02 — Interpretación asistida de fuentes educativas, pendiente.

### Acotación de entrega de PResolver — decisión del fundador (2026-10-16)

- **Hito:** entrega formal de PResolver el **31-10-2026**.
- **Incorporar al alcance actual:** una persona humana formula intenciones pedagógicas y se encarga de planificar, supervisar y autorizar su propio material, para responder a necesidades pedagógicas situadas de destinatarios que pueden ser distintos de quien crea el material (por ejemplo, estudiantes de un profesor particular o familiares que reciben apoyo en informática), aunque use fuentes ajenas. La autoría, la responsabilidad de autorización y el destinatario no deben confundirse. Esta distribución es un **escenario operativo acotado**, no un modelo universal. [Foundations](../foundations/pedagogical-authorship.md).
- **Conservar como distinciones conceptuales:** crear, editar, mediar y retroalimentar; autoría distinta de autorización y distinta de titularidad.
- **Aplazar como exploraciones posteriores al 31-10-2026:** [gradiente multidimensional](../mechanisms/contribution-gradient.md), evaluación de contribuciones, [trazabilidad avanzada de feedback](../mechanisms/feedback-traceability.md) y condiciones detalladas de atribución. No presentarlas como capacidades listas para entrega.
- **Clasificación de IA:** conservar las cuatro denominaciones provisionales en [Transparencia](../transparency/README.md); congelar desarrollo de reglas de asignación hasta completar el gradiente.
- **Privacidad/consentimiento/reutilización:** **NO** se consideran aplazados por esta decisión; requieren revisión separada en T22 y resguardos apropiados antes de cualquier tratamiento de datos personales reales.
- **Fuera de alcance hasta el hito:** autorizaciones institucionales multinivel o diferenciadas por roles. No se niega su relevancia futura.
- **Estado del seguimiento T01:** **Revisado; alcance del 31-10 definido; no cerrado integralmente** porque los trabajos aplazados y las aprobaciones conceptuales generales siguen identificados. T02 no ejecutado.


### Delimitación de clasificación T01 — 2026-10-16

- **Decisión expresa del fundador:** mantener el objetivo original de distinguir recursos elaborados completamente por humanos de recursos con intervención de IA. No ampliar por ahora la clasificación a otros ejes de contribución.
- **Vocabulario provisional único:** elaboración humana, elaboración asistida, transformación asistida y generación supervisada. Las definiciones de trabajo están en [Transparencia](../transparency/README.md).
- **Condición de continuación:** detener la formalización, extensión y reglas de asignación de esta clasificación hasta que el [gradiente de contribución](../mechanisms/contribution-gradient.md) esté completamente definido. Su naturaleza sigue siendo candidata.
- **Estado T01:** Revisado, no cerrado. No se ejecutó T02.

### Ampliación T01 — 2026-10-16

Se incorporaron las precisiones del fundador: crear, editar, mediar y retroalimentar como formas de contribución; autorización humana como principio de responsabilidad; gradiente multidimensional por aporte y objeto; feedback general trazable; transparencia de autoría, anonimato opcional, consentimiento y reutilización como responsabilidades del servicio. Ver [fundamento](../foundations/pedagogical-authorship.md), [gradiente](../mechanisms/contribution-gradient.md), [feedback](../mechanisms/feedback-traceability.md) y [transparencia](../transparency/README.md).

**Estado:** Revisado, no cerrado. Pendientes: terminología de clasificación, parámetros verificables, consentimiento/derechos por contexto, competencia autorizadora. T02 no ejecutado.

### T01 — Autoría pedagógica (2026-10-16)

- **Estado de seguimiento:** Revisado. No cerrado; propuesta candidata redactada, promoción canónica pendiente de decisión humana.
- **Responsable:** Research (revisión documental y propuesta).
- **Problema y alcance:** reconocer contribuciones a fuentes, intenciones y realizaciones sin asumir que crear, interpretar, aprobar, publicar o poseer derechos son la misma responsabilidad.
- **TDidacta / V6:** [Conceptos candidatos](../foundations/concept-candidates.md), [Necesidades e intenciones](../foundations/pedagogical-needs-and-intentions.md), [Enseñanza y aprendizaje](../foundations/teaching-and-learning.md), [Gobernanza](../governance/README.md) y [V6 aprobada](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md). Ya existían participación activa, responsabilidad compartida y autoría ≠ autoridad; faltaba una delimitación enfocada.
- **VSlices:** reutilizable separar titularidad semántica/uso/realización y exigir procedencia para promoción ([Relationships](https://github.com/the-alive-lab/vslices/blob/main/relationships/README.md), [Promotion](https://github.com/the-alive-lab/vslices/blob/main/promotion/README.md)); adaptable la trazabilidad proporcional; no aplicable copiar sin examen roles o categorías de ingeniería; incierto un modelo transversal de atribución.
- **Investigación y límite:** V6 es maestro editorial en Research, no estudio demostrativo de modelos de autoría. No se atribuye eficacia o factibilidad validada a las distinciones.
- **Decisión documental:** proponer una sola nota candidata y enlazarla desde Foundations; no alterar las definiciones vigentes ni institucionalizar un sistema de permisos.
- **Salida:** [Autoría pedagógica — propuesta candidata](../foundations/pedagogical-authorship.md); índice [Foundations](../foundations/README.md).
- **Decisiones pendientes:** si promover y bajo qué alcance la definición de autoría; criterios de atribución en entornos colaborativos o autodidactas; separación de derechos y autorización (T05, T06, T22).
- **Siguiente acción:** revisión humana de T01; siguiente tópico disponible T02, sin ejecutarlo en esta intervención.

- **2026-10-16 — Inicialización:** inventario de 28 tópicos reconstruido desde la conversación sobre V6; contraste de estructura con `the-alive-lab/vslices` incorporado como paso transversal, sin adopción de su taxonomía. No se declara ninguno revisado o cerrado sin aplicar el procedimiento.
- **Siguiente selección sugerida:** T01 — Autoría pedagógica. La sugerencia no es prioridad irrevocable.

## Criterios de cierre del bootstrap completo

El bootstrap puede darse por concluido **solo cuando los 28 tópicos tengan estado `cerrado` con registro y enlaces verificables**, incluidos cierres justificados de «no incorporar» o «aplazar a otra autoridad» cuando exista decisión explícita. Una investigación en curso no bloquea que el tratamiento documental se cierre justificadamente, pero las incertidumbres restantes deben permanecer visibles. La finalización del bootstrap **no** equivale a implementación de TDidacta, adopción global de V6 ni evaluación pedagógica positiva.
