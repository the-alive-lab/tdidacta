# Tensions — tensiones entre orientaciones de TDidacta

**Estado:** superficie candidata propuesta por el fundador (2026-10-16); registro progresivo de tensiones, no lista cerrada ni mecanismo obligatorio ya implementado.

## Responsabilidad

Una tensión explicita un problema de **satisfacer simultáneamente dos o más orientaciones** cuando sus demandas interactúan, compiten o introducen costos y riesgos de implementación. No significa que las orientaciones sean contradictorias o incompatibles. Permite formular qué debe ser atendido por mecanismos sin esconder el costo o dar por resuelta la tensión.

## Regla de aplicabilidad propuesta

1. Registrar las orientaciones involucradas, el conflicto de diseño, posibles riesgos y condiciones de observación.
2. Para cada fundamento, revisar las **clasificaciones realmente adoptadas** de sus orientaciones. Si las orientaciones relevantes de la tensión **inciden materialmente juntas** en ese fundamento, señalar que sus mecanismos deberán **responder explícitamente** a la tensión: tratarla, mitigarla o justificar sus límites. No presumir que el problema se resuelve por citar orientaciones.
3. **Sin incidencia** o **incidencia marginal** no deben activar por sí solas una obligación operativa artificial; evaluar el caso concreto y registrar la razón. La mera aparición de las orientaciones en una tabla preliminar tampoco demuestra aplicabilidad.
4. Responder a una tensión **no equivale a demostrar que quedó resuelta**. Una implementación, evaluación y garantías siguen pendientes de evidencia.
5. Incorporar tensiones **gradualmente**, conforme aparecen al revisar fundamentos y mecanismos. Nuevas tensiones pueden exigir revisar otras correspondencias, sin reabrir automáticamente fundamentos ya aprobados.

## Tensiones registradas

- [Tensión entre continuidad semántica y carga humana](semantic-continuity-human-effort.md): preservar y reconstruir significado puede exigir un esfuerzo elevado; O2 es posible apoyo tecnológico, no polo de la tensión. **Candidata**, especialmente pertinente a F02; pendiente de contraste en sus mecanismos.

- [Tensión O3/O6 — proporcionalidad de la inversión del esfuerzo](effort-inversion-proportionality.md): priorizar comprensión y documentación sin imponer carga desproporcionada. **Aplica a F03**; respuesta de mecanismos aún pendiente.

- [Tensión O4/O3 — autorización humana frente a carga y capacidad](human-authorization-review-burden.md): la aprobación humana introduce una decisión adicional; **candidata** y transversal a fundamentos donde O4 actúe como condición y O3 incida materialmente. Identificada durante F06; eficacia de respuestas pendiente.

## Tensiones compuestas e interacciones candidatas

- [O1/O3/O6 — continuidad, carga e inversión del esfuerzo](semantic-continuity-capacity-effort-inversion.md): interacción entre preservar significado, carga proporcional y dónde se invierte trabajo humano. **Candidata** en F03–F06; no elimina O1/O3 ni O3/O6.
- [O1/O3/O4 — continuidad, carga y autorización](semantic-continuity-authorization-human-capacity.md): interacción entre significado y aprobación material sin sobrecarga. **Candidata** en F06–F07; no elimina O1/O3 ni O3/O4.
- [O1/O3/O4/O6 — interacción cuádruple](semantic-continuity-authorization-capacity-effort-inversion.md): **candidata para F07**, por contraste; todavía no se afirma que constituya tensión autónoma de las dos compuestas anteriores.

**Relación distinta de tensión:** una orientación puede ser **medio de respuesta o atenuación**, no un polo en conflicto. En particular, O2 puede apoyar el tratamiento de O1/O3 mediante tecnologías, sin convertirse en una supuesta tríada conflictiva O1/O2/O3. Evitar convertir esta observación en una taxonomía nueva sin revisión metodológica.

La aplicabilidad debe comprobarse por las exigencias reales en cada fundamento y no por mera coaparición de etiquetas. Registrar una composición no significa duplicar evaluaciones ni afirmar resolución.

## Fronteras

- **Orientations** define compromisos.
- **Foundations** justifica capacidades conceptuales, con su origen y clasificaciones de orientación.
- **Tensions** expresa dificultades al satisfacer conjuntamente orientaciones.
- **Mechanisms** debe responder a tensiones aplicables, sin redefinirlas.
- **Relationships/Lifecycle** no se auditan aquí.

[Bootstrap de continuidad](../notes/tdidacta-v6-coverage-bootstrap.md) · [Auditoría O→F](../notes/2026-10-16-orientations-foundations-consistency-audit.md).
