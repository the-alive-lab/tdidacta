# Revisión y corrección pedagógica — propuesta T05

**Estado:** tópico T05 revisado, **pendiente de aprobación humana** (2026-10-16). Delimitación candidata; no especificación técnica ni eficacia validada.

## Problema y responsabilidad

Una intención documentada, una situación, una representación intermedia, una interpretación o una realización pueden presentar errores, omisiones, extrapolaciones, contradicciones o diferencias respecto de lo que se desea enseñar. **Revisar** es examinar críticamente su pertinencia y suficiencia para la intención y situación reconocidas; **corregir** es decidir y aplicar o solicitar cambios cuando el examen revela un problema relevante.

Una revisión puede producir correcciones, una solicitud de comprobación, un rechazo o una conservación razonada de lo existente. **Revisar no equivale a autorizar** (T06), ni a publicar (T07), ni a certificar aprendizaje (T17).

## Objetos revisables y fronteras

- **Intención y subdivisiones:** propósitos, inclusiones, exclusiones y relaciones entre intenciones, sin redefinirlas silenciosamente a través de una realización.
- **Situaciones válidas:** destinatarios, medios y condiciones; un ajuste situacional no modifica necesariamente el contenido de la intención.
- **Documentación Docs Standard:** legibilidad, contradicciones, omisiones y coherencia interna respecto de las decisiones humanas.
- **IR derivada mediante abstracción:** diferencias materiales entre documentación e IR; no presumir que una representación estructurada es semánticamente fiel.
- **Exploraciones y realizaciones por proyección:** fidelidad respecto de la intención y situación aplicable, errores factuales, omisiones y ampliaciones no justificadas.
- **Interpretaciones y evidencia:** distinguir afirmaciones respaldadas, elaboración humana, inferencias de IA e incertidumbre relevante según [T03](../mechanisms/evidence-classification.md).

Revisar no tiene que significar revisar exhaustivamente todos estos objetos en cada caso. La selección y profundidad dependen del riesgo, propósito, cambios y consecuencias para quienes aprenden.

## Responsabilidad humana

En el escenario operativo aprobado en T01, una misma persona puede formular, planificar, supervisar y autorizar su propio material, aunque esas responsabilidades sean **conceptualmente distintas**. La persona responsable examina qué aceptar, corregir, rechazar o dejar abierto; no tiene que ejecutar personalmente cada edición si supervisa su resultado.

La IA puede proponer detecciones, explicaciones y correcciones, pero **no se convierte por eso en autoridad humana ni en prueba de conformidad o calidad**. Las sugerencias deben poder ser cuestionadas o rechazadas sin descartar automáticamente las partes respaldadas.

## Criterio conceptual de revisión proporcional

La revisión debe dar al responsable oportunidad real de:
1. identificar el objeto, la intención y la situación pertinentes;
2. reconocer problemas **materiales** y sus respaldos, límites e incertidumbres;
3. decidir si mantener, corregir, rechazar o solicitar aclaración;
4. reconocer el alcance del cambio y qué otras piezas podrían necesitar revisión;
5. distinguir el resultado de revisión de la **autorización** posterior.

No se propone registro por oración, puntuación universal, doble aprobación ni jerarquía institucional obligatoria. Una corrección puntual puede ser suficiente; cambios que alteran intención o situación pueden requerir reconsideración más amplia.

**Condición de carga:** cualquier sistema que instrumente la revisión deberá facilitar detectar, priorizar y corregir problemas con menos esfuerzo innecesario para el responsable. El ahorro neto es algo **por medir**, no un hecho demostrado.

## Ejemplos de contraste

- La fuente dice que estudiantes practicaron fracciones; una realización afirma que dominan sumas: se detecta extrapolación no respaldada y puede corregirse sin desechar la actividad original.
- Una intención se mantiene, pero una situación pierde conectividad: se revisa la realización afectada, no necesariamente todo el conocimiento que se quiere enseñar.
- Una IA añade un prerrequisito no documentado: puede ser hipótesis revisable, no obligación de modificar automáticamente la intención.
- Una realización técnicamente conforme puede tener poca calidad didáctica: el resultado no resuelve automáticamente T16 ni T17.

Son ejemplos conceptuales, no casos empíricos validados.

## Continuidad y límites

- [T01](pedagogical-authorship.md): supervisar, revisar, autorizar y publicar son responsabilidades distintas.
- [T02](assisted-source-interpretation.md): interpretación asistida es opcional; el mecanismo detallado para interpretar fuentes se mantiene pospublicación PResolver.
- [T03](source-inference-uncertainty.md): evidencia humana e inferencial e incertidumbre permanecen distinguibles.
- [T04](human-pedagogical-contextualization.md): intención y situaciones documentadas; abstracción Docs→IR y proyección IR→resultados son **dos fronteras de revisión diferentes**. Los tres entregables Docs Standard, abstracción e IR Specification siguen comprometidos antes del 31-10-2026.
- **T06:** asignación y alcance de autorización humana; **T07:** publicación; **T08/T09/T12:** procedencia, versiones e impacto de cambios; **T15/T16/T17:** conformidad, calidad y aprendizaje como evaluaciones separadas.

[Mechanism candidato de revisión y corrección](../mechanisms/pedagogical-review-and-correction.md) · [Gobernanza](../governance/README.md).

## Propuesta de decisión

Reconocer **revisión y corrección pedagógica** como una responsabilidad humana separada de contextualización y autorización, aplicable proporcionalmente a intenciones, situaciones, documentación, IR, exploraciones y realizaciones; posibilitar asistencia inferencial **sin delegar autoridad ni aumentar innecesariamente la carga**. Los procedimientos concretos, controles y pruebas quedan por especificar en sus fronteras correspondientes.

**Fuentes:** decisiones T01–T04, orientación vigente de TDidacta y [maestro editorial V6](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md), que exige contextualización, corrección y autorización humanas sin imponer el registro de cada decisión trivial. V6 no constituye evidencia empírica.
