# F13 — Auditabilidad de actuaciones y decisiones

**Estado:** fundamento promovido por autorización expresa del fundador (2026-10-19). Responsabilidad, fronteras, O0–O11→F13 y tres conceptos reconciliados. No acredita implementación ni eficacia.

## 1. Origen y responsabilidad

TDidacta debe hacer posible **reconstruir y examinar, con fiabilidad y proporcionalidad, las actuaciones relevantes de sus dominios y sus condiciones de ejercicio, resultados y cambios asociados, preservando límites de acceso, identificación y conservación**.

Su origen es [O11 — Auditoría general](../orientation/general-auditability.md). La relevancia de una actuación depende del dominio, contexto y riesgo; incluye consultas, accesos, acciones indirectas e intentos fallidos o rechazados cuando corresponda, sin exigir registrar indiscriminadamente todas las interacciones.

## 2. Fronteras y límites

- Auditar una decisión o actuación no equivale a determinar su **validez pedagógica** (F06/F07).
- **Facultad** (F11) expresa habilitación semántica, no una actuación realizada, ni cumplimiento de una responsabilidad contextual.
- Reconocer autoría (F08) no supone evidencia de auditoría automática.
- Conservar recursos públicos (O10) o preservar continuidad semántica (O1) no es conservar historial de actuaciones.
- La información de auditoría puede ser incompleta; sucesión temporal no prueba causalidad y atribución operativa no acredita identidad personal.
- Limitar captura, acceso, identificación, conservación, eliminación y examen de evidencia conforme a privacidad, proporcionalidad y riesgos de vigilancia.
- No prescribe logs exhaustivos, event sourcing, formato técnico, almacenamiento inmutable indefinido, interfaz ni certificación normativa. La preferencia técnica por explorar la auditabilidad de toda acción permanece hipótesis de Design/Mechanisms, no requisito universal del fundamento.

## 3. Conceptos reconciliados

- [Actuación auditable](../concepts/auditable-action.md): ejercicio concreto relevante para reconstrucción o examen.
- [Evidencia de auditoría](../concepts/audit-evidence.md): información examinable que sustenta reconstrucción, con límites e incertidumbres.
- [Contexto de actuación](../concepts/action-context.md): condiciones y relaciones pertinentes al momento de actuar.

Los conceptos tienen identidad semántica independiente, sin exigir tres representaciones técnicas separadas. La evidencia puede sustentar afirmaciones sobre una actuación y su contexto sin crear un cuarto concepto.

## 4. Trazabilidad O→F13 (reconciliada)

| Orientación | Relación aprobada | Motivo |
| --- | --- | --- |
| Orientación | Relación aprobada | Motivo |
| [O0](../orientation/README.md) | **Sin incidencia** | O0 define la orientación principal de enseñanza y aprendizaje, mientras que F13 trata de reconstruir actuaciones relevantes; su origen corresponde a O11. |
| [O1](../orientation/semantic-continuity.md) | **Sin incidencia** | Reconstruir acciones no exige asumir continuidad de significado pedagógico como mismo objeto. |
| [O2](../orientation/technology-enabled-semantic-continuity.md) | **Complemento** | La tecnología facilita captura o examen sin imponer un mecanismo único. |
| [O3](../orientation/human-effort-and-agency.md) | **Condición** | El costo humano de registrar y consultar evidencia debe ser proporcionado. |
| [O4](../orientation/human-pedagogical-authorization.md) | **Sin incidencia** | La autorización pedagógica y la auditabilidad son responsabilidades anexas; examinar una autorización no vincula el fundamento general de auditoría con la orientación de autorización pedagógica. |
| [O5](../orientation/transparent-contribution-recognition.md) | **Sin incidencia** | Reconocer aportes es diferente de reconstruir acciones. |
| [O6](../orientation/effort-inversion.md) | **Condición** | La auditoría no debería desplazar esfuerzo innecesario desde el trabajo educativo. |
| [O7](../orientation/privacy-by-design-and-data-minimization.md) | **Condición** | Minimización de datos personales, conservación justificada y control de exposición. |
| [O8](../orientation/external-personal-identity-recognition.md) | **Condición** | Identidad operativa de una actuación no significa identidad personal verificada. |
| [O9](../orientation/contextual-access-and-educational-reach.md) | **Sin incidencia** | O9 concierne al acceso contextual educativo; el acceso a evidencias de auditoría es una cuestión diferente y no deriva de esa orientación. |
| [O10](../orientation/public-resource-continuity.md) | **Sin incidencia** | Continuidad de recursos públicos no equivale a retención de evidencia de auditoría. |
| [O11](../orientation/general-auditability.md) | **Origen** | La exigencia explícita de reconstrucción y examen de actuaciones relevantes justifica la responsabilidad propuesta. |

## 5. Decisión y procedencia

Promoción autorizada expresamente por el fundador el 2026-10-19 tras reconciliar la responsabilidad, O0–O11 y las tres capas conceptuales. Antecedentes: [evaluación de candidatura](candidate-general-auditability.md), [revisión O→Concept](candidate-f13-concepts-orientation-review-2026-10-19.md) y [revisión transversal O11→F01–F12](../notes/2026-10-19-o11-foundations-impact-review.md).

La definición es conceptual; su realizabilidad y mecanismos deben contrastarse en etapas posteriores.
