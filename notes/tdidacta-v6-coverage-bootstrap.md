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
| T04 | Contextualización pedagógica humana | Cerrado | [Fundamento T04](../foundations/human-pedagogical-contextualization.md); pendientes independientes antes del 31-10-2026: [Docs Standard](../mechanisms/pedagogical-intent-documentation.md), [abstracción](../mechanisms/document-to-intermediate-projection.md), [IR Specification](../products/ir-specification/README.md) |
| T05 | Revisión y corrección pedagógica | Cerrado | [Fundamento](../foundations/pedagogical-review-and-correction.md); tensión hacia T06; feedback diferido |
| T06 | Autoridad y autorización de realizaciones | En curso | [Propuesta T06](../foundations/pedagogical-authorization.md); resolver tensión de revisión proporcional heredada de T05 |
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

### T06 — autorización individual y congelamiento semántico (2026-10-16)

- **Decisión del fundador para MVP:** autoriza individualmente la persona responsable. Casos colaborativos, institucionales y autorización multinivel **diferidos para después del 31-10-2026**.
- **Objetos autorizables:** intenciones, planificaciones aún en draft, trayectorias de unidades propuestas por humano o LLM, clases y actividades; no limitar autorización a realizaciones finales.
- **Sentido de autorización:** aprobar un elemento para su uso posterior y **congelar su alcance semántico** como base de exploración segura. Espacios sin autorización permanecen modificables; autorizar una parte no aprueba automáticamente el conjunto.
- **Revisión posterior:** la autorización puede reconsiderarse mediante revisión/corrección de T05 si exploración o cambios curriculares revelan problemas. Los detalles de versiones y propagación permanecen en T09/T12.
- **Tensión abierta:** resolver qué revisión es suficiente antes de autorizar sin imponer un procedimiento universal o revisión exhaustiva. **T06 sigue En curso**.
- **Secuencia preservada:** feedback transversal de T06 y revisión de Relationships/Lifecycle solamente después de su cierre.


### Inicio T06 — autorización situada y suficiencia de revisión (2026-10-16)

- T06 **En curso**, no cerrado. [Propuesta](../foundations/pedagogical-authorization.md) distingue autorizar, revisar, corregir, publicar y poseer derechos.
- **Tensión heredada de T05:** decidir suficiencia de revisión sin procedimiento universal ni revisión exhaustiva obligatoria, pero sin convertir autorización en aprobación nominal.
- **Decisiones por resolver:** quién autoriza, qué objeto/situación/versión/alcance, relación con revisión y efectos de cambios materiales. No se adopta todavía la alternativa de autorización situada con revisión proporcional.
- **Orden de trabajo acordado:** después de cierre conceptual de T06 y su feedback transversal, revisar carpetas de Relationships y Lifecycle a la luz de T01–T06.


### Cierre T05 y revisión transversal (2026-10-16)

**Decisión:** cierre conceptual autorizado. Tensión abierta T05→T06: determinar cómo conciliar la obligación de revisar con proporcionalidad, sin imponer revisión exhaustiva ni procedimiento universal. Mecanismo de revisión candidato; mecanismos de feedback y apoyo diferidos. No implica validación ni ejecución técnica.

**Revisión individual de los otros 27 tópicos**, incluyendo cuatro ya cerrados, sin modificar sus estados:

- T01: sin contradicción autoría/revisión/autorización
- T02: sin contradicción interpretación/revisión
- T03: clasificación no sustituye revisión
- T04: Docs/IR/situación revisables; deadline vigente
- T06: tensión revisión proporcional/autorización pendiente
- T07: revisión no publica
- T08: trazabilidad de correcciones distinta de feedback diferido
- T09: versiones de objetos corregidos
- T10: continuidad de revisión entre actores
- T11: traspaso de responsabilidad por revisar
- T12: impacto de cambios sin aprobación automática
- T13: revisión no exige regenerar exportaciones
- T14: portabilidad de decisiones de revisión
- T15: conformidad distinta de juicio de revisión
- T16: revisión distinta de evaluación de calidad
- T17: revisión no demuestra aprendizaje
- T18: medir carga y capacidad por separado
- T19: accesibilidad pertinente a situación
- T20: revisión contextual sin cambiar intención
- T21: no se impone aprobación institucional universal
- T22: privacidad vigente pese al diferimiento de feedback
- T23: feedback no autoriza publicación
- T24: revisión compatible con autoalojamiento
- T25: asistencia inferencial diferida
- T26: costo de revisión afecta sostenibilidad
- T27: recuperabilidad de decisiones según el caso
- T28: revisión no redefine rol del operador

**Secuencia:** abrir T06; cuando T06 sea cerrado y retroalimentado, auditar `relationships/` y `lifecycle/`.


### T05 — aplazamiento de ambos mecanismos de feedback (2026-10-16)

- **Decisión expresa:** [generación de feedback](../mechanisms/feedback-generation.md) y [trazabilidad de feedback](../mechanisms/feedback-traceability.md) quedan **ambos diferidos por ahora** como mecanismos candidatos; no se requiere su definición técnica, implementación o validación para la publicación de PResolver del 31-10-2026.
- **No se eliminan:** permanecen separados y documentados. La trazabilidad podrá investigarse con automatización parcial o completa; no se presume fiabilidad.
- **Sin arrastre de plazo:** el mecanismo conceptual de [revisión y corrección](../mechanisms/pedagogical-review-and-correction.md) conserva su estado candidato y el [apoyo a revisión](../mechanisms/pedagogical-review-assistance.md) permanece diferido según decisión anterior.
- **Límites:** tratamiento de datos personales, privacidad y consentimiento no se aplazan automáticamente. T05 continúa **Revisado**, pendiente de cierre humano y retroalimentación transversal.


### T05 — ampliación de mecanismos y orientación humana (2026-10-16)

- **Decisión del fundador:** conservar como **candidatos distinguibles** [revisión y corrección](../mechanisms/pedagogical-review-and-correction.md), [generación de feedback](../mechanisms/feedback-generation.md) y [trazabilidad de feedback](../mechanisms/feedback-traceability.md). El mecanismo de revisión posee delimitación suficiente para estado candidato; no significa implementación o validación.
- **Trazabilidad:** mecanismo ya existente desde T01, **reutilizado y ampliado**, no duplicado. Puede diseñarse con automatización **parcial o completa**; tales vínculos y causalidad no quedan automáticamente confirmados. Su implementación avanzada se mantiene diferida conforme a T01.
- **Mecanismo separado de apoyo a revisión:** [reservado](../mechanisms/pedagogical-review-assistance.md) para **después de publicación de PResolver**; no se suma como requisito para el 31-10-2026.
- **Orientación propuesta:** [reducir carga humana y/o ampliar capacidad de acción](../orientation/human-effort-and-agency.md). Son metas **independientes, no necesariamente simultáneas**. Conecta preocupación de T03 con T18 y mecanismos de T05, sin presumir eficacia.
- **Seguimiento:** T05 continúa **Revisado**, no cerrado. Pendiente decisión de cierre y, tras ella, retroalimentación transversal de los otros 27 tópicos incluidos T01–T04. No se modifican sus estados.


### T05 — Revisión y corrección pedagógica (2026-10-16)

- **Estado:** Revisado; **no cerrado** ni autorizado como procedimiento universal.
- **Continuidad T01–T04:** persona responsable puede supervisar y autorizar su propio material, pero los actos son distintos (T01); interpretación de fuentes asistida no crea autoridad (T02); evidencia e incertidumbre relevantes se distinguen con carga proporcional (T03); intención, situación, Docs Standard, abstracción a IR y proyección desde IR son objetos y fronteras distintas (T04).
- **Problema:** identificar errores, contradicciones, omisiones, extrapolaciones y desajustes pedagógicos sin equiparar revisión con autorización o conformidad técnica.
- **Correspondencia V6:** contextualización, corrección y autorización humanas no eludibles; no exigir documentación de cada decisión trivial. **Estado de evidencia:** antecedente editorial, no validación de eficacia o ahorro.
- **Contraste VSlices:** separaciones entre semántica, realización y verificaciones adaptables, sin importar sus tipos de evidencia ni workflows como norma educativa.
- **Artefactos propuestos:** [fundamento T05](../foundations/pedagogical-review-and-correction.md) y [mecanismo T05](../mechanisms/pedagogical-review-and-correction.md). Examinar, priorizar, mantener/corregir/rechazar/aclarar y revisar efectos como posibilidades no rígidas.
- **Fronteras:** T06 autoriza; T07 publica; T08/T09/T12 trazan y mantienen; T15 comprueba conformidad; T16 calidad y T17 resultados son independientes; T18 debe medir carga real.
- **Pendiente de cierre:** aprobación humana del alcance proporcional de revisión y de su separación respecto de autorización. Retroalimentación transversal a 27 tópicos, incluidos T01–T04, **aún no ejecutada**, según protocolo.


### Cierre conceptual de T04 y retroalimentación transversal — 2026-10-16

- **Cierre expresamente autorizado:** contextualización humana resulta en intención pedagógica, subdivisiones pertinentes y situaciones válidas, que son distinguibles del contenido/intención en sí. Una intención puede corresponder a más de una situación. Estas distinciones informan exploración y realización.
- **Arquitectura acordada:** Docs Standard documenta intenciones y situaciones; [abstracción semántica](../foundations/semantic-abstraction.md) transforma documentación en IR; [proyección semántica](../foundations/semantic-projection.md) transforma IR individual o combinada en resultados del dominio. [Continuidad semántica](../orientation/semantic-continuity.md) y [aprovechamiento de tecnologías](../orientation/technology-enabled-semantic-continuity.md) son orientaciones distintas y complementarias. La especificación de estructura tiene la superficie [TDidacta IR Specification](../products/ir-specification/README.md).
- **Compromisos independientes NO completados por el cierre:** definición del [mecanismo documental Docs Standard](../mechanisms/pedagogical-intent-documentation.md), del [mecanismo de abstracción](../mechanisms/document-to-intermediate-projection.md) y de [IR Specification](../products/ir-specification/README.md) **antes del 31-10-2026**. [Proyección IR→dominio](../mechanisms/intermediate-to-domain-projection.md) queda pendiente de precisión de contrato/plazo, sin convertir automáticamente su implementación integral en prerrequisito de cierre T04.
- **Estado epistemológico:** decisiones conceptuales aprobadas, sin validación de fidelidad automatizada, calidad pedagógica, generación LLM ni adopción general de contratos en PResolver. El mecanismo detallado de interpretación IA de T02 permanece pospublicación.
- **Control retrospectivo de T01–T03:** contrastados contra sus fronteras autorizadas; **no se detectan contradicciones**. Se preserva separación autoría/autorización (T01), interpretación de fuentes vs abstracción de intención (T02), y clasificación de evidencia vs conformidad de IR (T03). Sin reaperturas.
- **Revisión transversal:** 27 receptores examinados, con estados inalterados. Los impactos representan continuidad y preguntas, no cierres ni validación de esos otros tópicos.

| Receptor | Impacto | Continuidad o delimitación heredada | Pendiente propio |
| --- | --- | --- | --- |
| T01 | Cerrado, consistente | Responsabilidades distintas aunque una sola persona contextualice, planifique y autorice; destinatarios pueden ser otros | Sin reapertura; autoría no sustituye autorización |
| T02 | Cerrado, consistente | Interpretación desde cero o de fuentes asistida puede anteceder a contextualización; mecanismo IA de fuentes sigue pospublicación | No exigir mecanismo T02 para Docs Standard ni encode |
| T03 | Cerrado, consistente | Documentación y abstracción conservan procedencia, inferencias y dudas relevantes; evitar carga de clasificación manual exhaustiva | No equiparar IR con evidencia verificada |
| T05 | Directo | La intención y situaciones documentadas son objetos revisables; corrección humana distinta de encode | Criterios y acciones de revisión |
| T06 | Directo | La formalización en Docs/IR no implica autorización; responsable autoriza conforme a contexto | Alcance de aprobación |
| T07 | Directo | Publicar realización no equivale a publicar intención, situación ni IR | Flujos y condiciones de publicación |
| T08 | Directo | Relacionar documentos, intenciones, situaciones, abstracción e IR demanda procedencia reconstruible | Granularidad mínima |
| T09 | Directo | Cambios en situación no deben redefinir silenciosamente intención; versiones de Docs/IR relacionadas | Versionado y correspondencias |
| T10 | Directo | Intención y contexto explícitos apoyan continuidad entre actores | Qué debe permanecer interpretable |
| T11 | Parcial | Distinguir intención de situación permite entregar contexto a responsable sucesor | Responsabilidades y aceptación de handoff |
| T12 | Directo | Cambios de una situación afectan proyecciones sin necesariamente cambiar intención | Análisis de impacto y reabstracción |
| T13 | Directo | La realización exportada tiene que mantenerse diferenciada de IR e intención, sin regeneración obligatoria | Contrato de exportación |
| T14 | Directo | Docs e IR pueden ser portables en formas distintas | Portabilidad semántica y técnica |
| T15 | Directo | Separar abstracción (Docs→IR) y proyección (IR→resultado) permite contrastes de fidelidad distintos | Oráculos y garantías por frontera |
| T16 | Parcial | Preservar intención/situación no garantiza buena experiencia educativa | Evaluación pedagógica independiente |
| T17 | Sin avance directo | Proyección adecuada no demuestra comprensión o autonomía del aprendiz | Mediciones de resultados |
| T18 | Directo | Documentar, mantener, corregir y proyectar puede aumentar trabajo humano | Evaluación del esfuerzo neto |
| T19 | Parcial | Situaciones incluyen medios disponibles y accesibilidad pertinente a realizaciones | Criterios accesibles específicos |
| T20 | Directo | Una intención puede tener varias situaciones válidas, incluidas docentes e institucionales | Límites de adaptación por contexto |
| T21 | Sin avance directo | Situación institucional no impone coordinación o aprobaciones multinivel | Coordinación institucional sigue separada |
| T22 | Directo | Documentar situaciones personales y usar LLM requiere límites de privacidad, permisos y minimización | Controles previos al tratamiento real |
| T23 | Parcial | Publicar comunitariamente no transfiere por sí mismo derechos sobre fuente o situación | Autorización y licencias |
| T24 | Parcial | IR Specification es estructura conceptual propia; no promete interoperabilidad técnica | Contratos e implementación |
| T25 | Directo | LLM pueden asistir encode y decode; no los hacen obligatorios ni autorizan inferencias añadidas | Modos y controles de inferencia |
| T26 | Antecedente | Costos de IA/documentación pueden incidir en acceso público | Sostenibilidad sin cálculos adoptados |
| T27 | Parcial | Conservar documentación e IR puede facilitar continuidad tras cierre de servicio | Recuperabilidad demostrable |
| T28 | Sin avance directo | Responsabilidad de Docs Standard/IR no redefine al operador The Alive Lab | Separación proyecto/organización |

**Resultado:** T04 **Cerrado** en seguimiento conceptual; quedan **24 tópicos pendientes** de los 28 originales. Siguientes posibilidades: T05 como tópico; entregables de T04 como trabajos separados con deadline obligatorio.


### Dos orientaciones complementarias — precisión T04 (2026-10-16)

- **Decisión del fundador:** reconocer como **dos orientaciones independientes** [continuidad semántica](../orientation/semantic-continuity.md) y [aprovechamiento de tecnologías](../orientation/technology-enabled-semantic-continuity.md). La primera expresa el compromiso sobre la continuidad del significado; la segunda, adaptación a capacidades tecnológicas actuales, especialmente LLM.
- **Convergencia:** su combinación motiva los fundamentos [abstracción semántica](../foundations/semantic-abstraction.md) y [proyección semántica](../foundations/semantic-projection.md), sin reducir orientación a mecanismo o formato.
- **Alcance:** transversal a hijos de PResolver por decisión conceptual del fundador; **formalización en PResolver pendiente**, sin declarar validación general ni forzar implementaciones idénticas.
- **Seguimiento:** T04 continúa en curso; definiciones técnicas comprometidas para antes del 31-10-2026 permanecen pendientes y no se modifican los estados de los otros tópicos.


### Desdoblamiento de abstracción / proyección semántica — T04, 2026-10-16

- **Decisión expresa del fundador:** separar dos fundamentos comunes a los hijos de PResolver: **[abstracción semántica](../foundations/semantic-abstraction.md)**, documentación → IR (*encode*), y **[proyección semántica](../foundations/semantic-projection.md)**, una o varias IR → resultados del dominio (*decode*). El esquema conjunto no debe atribuirse íntegramente al segundo concepto.
- **Orientación propuesta:** [adaptación a ventajas tecnológicas actuales](../orientation/technology-enabled-semantic-continuity.md), motivada especialmente por LLM, sin obligatoriedad de que cada operación use IA. Su adopción general en PResolver aún requiere formalización.
- **Mecanismos diferenciados:** [abstracción documental T04](../mechanisms/document-to-intermediate-projection.md) y [proyección IR a resultados](../mechanisms/intermediate-to-domain-projection.md); permanecen pendientes sus contratos técnicos.
- **Producto específico escogido:** [TDidacta IR Specification](../products/ir-specification/README.md), destino de la especificación estructurada. [Nota anterior de estructuras](../structures/tdidacta-intermediate-representation.md) preservada como antecedente, sin esquema duplicado. El referente declarado de VSlices es `vslices/intermediate-representation`, no verificado documentalmente en esta revisión.
- **T04 sigue en curso** y las especificaciones comprometidas para antes del 31-10-2026 continúan pendientes. No se cierran T04 ni otros tópicos ni se promueve automáticamente un contrato universal de PResolver.


### Aclaración conceptual de proyección semántica — T04, 2026-10-16

- **Confirmación expresa del fundador:** la proyección semántica es una **facultad común a todos los proyectos derivados de PResolver**. Se trata de una afirmación adoptada por decisión conceptual, **no de una generalidad validada empíricamente** ni de un contrato técnico adoptado por PResolver.
- **Esquema:** semántica documentada → *encode* → representación/es intermedia/s (utilizables individual o conjuntamente) → *decode* → proyecciones especializadas por dominio. La conservación exacta, los límites y la semántica de encode/decode siguen sujetos a diseño y contraste.
- **TDidacta:** documentación de intenciones, subdivisiones, situaciones y relaciones mediante Docs Standard; proyección a IR, idealmente una por intención, con situaciones aplicables; LLM pueden utilizar IR individual o combinada para exploraciones y realizaciones. La interpretación IA de fuentes T02 es un mecanismo diferente.
- **Distribución conceptual propuesta:** orientación expresa compromiso de continuidad; fundamento define facultad; mecanismos realizan transformaciones especializadas; estructura define IR. Ubicación definitiva **pendiente de evaluación**. [Análisis conceptual](../foundations/semantic-projection.md).
- **Estado y deadline:** T04 sigue en curso; permanecen sin completar las tres especificaciones comprometidas antes del 31-10-2026. No se modifican estados de otros tópicos ni se registra cierre de T04.


### Ampliación de T04 — decisión del fundador (2026-10-16)

- **Estado:** En curso; el alcance recibió una decisión concreta que introduce **tres entregables de definición necesarios antes del deadline del 31-10-2026**. No se diseñan íntegramente en esta conversación y T04 **no queda cerrado**.
- **Resultado de contextualización humana:** **intención pedagógica con subdivisiones pertinentes**, documentada junto a **una o más situaciones válidas**, sin confundir *qué se desea enseñar* con *dónde, a quiénes y bajo qué condiciones*. Las situaciones influyen en exploración y realización; pueden coexistir para una intención.
- **Superficie Docs Standard:** se asigna la responsabilidad específica de documentación a [mecanismo de documentación de intención y situaciones](../mechanisms/pedagogical-intent-documentation.md), sin declarar automáticamente validada la familia completa de productos.
- **Proyección con apoyo de IA:** [mecanismo de proyección documental a IR](../mechanisms/document-to-intermediate-projection.md) distinto del mecanismo T02 de interpretación inferencial de fuentes y distinto de la clasificación de evidencia T03.
- **Especificación estructurada:** [Representación intermedia de TDidacta](../structures/tdidacta-intermediate-representation.md), **preferentemente una unidad por intención**, capaz de referir a varias situaciones, sin exigir que una unidad sea un solo archivo.
- **Pregunta por investigar:** qué significa «proyección semántica» y si pertenece a Orientation, Foundations o Mechanisms. Registrar sin promocionarla antes de contrastar el concepto.
- **Diferencia temporal material:** los tres entregables nuevos **sí** deben definirse antes del 31-10-2026; el mecanismo detallado de interpretación IA de T02 se mantiene **después de publicación de PResolver**. Son problemas distintos.
- **Continuidad:** T01–T03 continúan cerrados y sus decisiones mantienen autoridad dentro de su alcance; no se ejecuta todavía retroalimentación transversal de cierre de T04.
- **Pendiente:** profundizar las tres especificaciones en ejecuciones posteriores y revisar expresamente el concepto proyección semántica, coherencia, representación, carga humana y pruebas de continuidad.


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
