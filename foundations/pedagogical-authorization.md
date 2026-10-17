# F07 — Autorización de elementos pedagógicos

**Estado:** fundamento conceptual reconciliado y cerrado por decisión del fundador (2026-10-17). No implica implementación de mecanismos ni eficacia demostrada.

## 1. Definición

La **autorización de elementos pedagógicos** es el fundamento que establece la responsabilidad humana de aceptar un elemento pedagógico para determinados usos y dentro de un alcance semántico reconocible.

Su propósito es permitir que decisiones pedagógicas aprobadas constituyan referencias estables para el trabajo posterior, sin impedir exploración de alternativas, revisión ni evolución de elementos autorizados.

Reconoce **elemento autorizado**, **alcance de autorización** (significado, condiciones y usos comprendidos) y **responsabilidad humana** (quién tiene autoridad para decidir).

Puede aplicarse a intenciones pedagógicas, elementos derivados y otros elementos del dominio. Autorizar uno no autoriza automáticamente otros relacionados ni todos sus usos y circunstancias. Formular, crear, revisar, corregir, autorizar y publicar son responsabilidades distintas aunque las desempeñe la misma persona.

## 2. Alcance semántico

La autorización establece una referencia semántica reconocible: decisiones, restricciones, relaciones y condiciones aceptadas permanecen identificables en el trabajo posterior.

Puede ser **situada**. Una autorización para una circunstancia no cubre automáticamente las demás. Autorizar una intención tampoco autoriza todas sus realizaciones.

Debe distinguirse qué fue aceptado, qué queda abierto a exploración o modificación y qué requiere nueva decisión. No se exige formato universal ni alcance idéntico en todos los casos.

## 3. Estabilidad y exploración

Antes de autorizar, la planificación puede modificarse. Después, el significado aprobado debe seguir identificable sin imponer inmutabilidad técnica o bloqueo de exploraciones.

Pueden explorarse posibilidades compatibles, generar derivados y alternativas, detectar problemas y proponer modificaciones **sin redefinir silenciosamente el alcance autorizado**.

Una intención puede aprobarse antes de producir realizaciones. Las realizaciones posteriores no quedan aprobadas por extensión.

## 4. Cambios y reconsideración

Nuevas necesidades, cambios de circunstancias, errores o hallazgos pueden justificar modificar elementos autorizados.

Un cambio material no debe sustituir silenciosamente lo aprobado. Según su impacto, corresponde revisar elementos y dependencias afectados, determinar vigencia de autorizaciones, corregir cuando sea necesario y reautorizar lo cuyo alcance cambió.

Una modificación localizada no exige reautorizar elementos no afectados; una amplia puede alcanzar varias dependencias. Una diferencia documental o de IR tampoco invalida automáticamente todos los resultados derivados.

## 5. Responsabilidad humana

La decisión corresponde a una persona con autoridad pertinente al elemento y alcance. Otras personas o tecnología pueden crear, revisar, proponer o ejecutar cambios sin adquirir por ello esa autoridad.

La persona responsable necesita reconocer lo que acepta; no necesita haber creado personalmente cada elemento. Pueden existir esquemas individuales, colaborativos, institucionales o multinivel sin imponer uno universalmente.

## 6. Fronteras

- **Contextualización:** formula y documenta necesidades, intenciones y circunstancias; autorización acepta determinados elementos y usos.
- **Revisión/corrección:** examina o cambia elementos; no autoriza automáticamente.
- **Abstracción:** documentación→IR; estructurar significado no lo autoriza.
- **Proyección:** IR→exploraciones/realizaciones; generar resultados no implica aprobación.
- **Análisis de impacto:** identifica afectados y vigencia; no constituye autorización.
- **Gestión/declaración de cambios:** modifica lo pertinente; ejecutar cambios no los autoriza.
- **Publicación:** disponibiliza elementos; autorizar no necesariamente publica.
- **Conformidad, calidad, aprendizaje, derechos y consentimiento:** responsabilidades diferenciadas, no demostradas ni concedidas por autorización.

## 7. Límites

- No exige una autoridad personal única para todos los contextos ni jerarquía universal.
- No exige autorización previa de toda exploración o propuesta.
- No aprueba automáticamente derivados o circunstancias ajenas al alcance aprobado.
- No impide revisar ni modificar elementos ni exige archivos inmutables.
- No equipara autoría y autoridad ni sugerencias tecnológicas y aprobación humana.
- No exige reautorizar elementos materialmente no afectados.
- No impone versionamiento técnico universal ni garantiza conformidad, calidad o aprendizaje.
- No concede automáticamente publicación, derechos de uso ni consentimiento.

## 8. Nota de especialización — TDidacta

La autorización puede aplicarse a intenciones, planificaciones, unidades, clases, actividades y realizaciones. Puede preceder a realizaciones para permitir exploración bajo premisas estables.

### Alcance de MVP

La **persona titular de la cuenta**, en escenario de profesor particular, autoriza elementos y determina manualmente cambios y dependencias que necesitan revisión y reautorización. Esto es **especialización operativa**, no principio universal. Colaboración institucional y autorización multinivel quedan diferidas.

### Alcance del impacto

Si cambia toda la planificación, se reconsidera lo afectado en su conjunto. Si cambia una unidad, se reconsidera esa unidad y dependencias pertinentes, sin extenderse indiscriminadamente a otras. La tecnología puede asistir la detección de dependencias y drift, sin presumir completitud ni reemplazar autoridad humana.

## 9. Responsabilidades operativas relacionadas

- **Declaración de impacto:** ¿qué afecta el cambio y qué permanece válido? Identifica elementos, dependencias y vigencia frente a la necesidad actual.
- **Declaración o revisión de cambios:** ¿cómo adecuamos lo afectado? Determina y aplica cambios para responder a la necesidad.
- **Versionamiento:** conserva referencias identificables entre elementos, cambios y alcances autorizados; [mecanismo candidato](../mechanisms/pedagogical-element-versioning.md).
- **Asistencia tecnológica:** puede ayudar a detectar dependencias, riesgos y consecuencias, con eficacia pendiente de contraste.

Estas responsabilidades pueden iterar y no necesariamente implican formularios, artefactos separados o pasos rígidos. No definen por sí mismas la autorización.

## 10. Tensiones y relación entre ellas

- **[O1/O3/O4 — continuidad, carga y autorización](../tensions/semantic-continuity-authorization-human-capacity.md):** tensión compuesta candidata aplicable; preservar significado de modificaciones y autoridad humana sin sobrecarga de análisis y reautorización. Integra aspectos de las binarias [O1/O3](../tensions/semantic-continuity-human-effort.md) y [O4/O3](../tensions/human-authorization-review-burden.md), sin eliminarlas.
- **[O3/O6 — carga e inversión del esfuerzo](../tensions/effort-inversion-proportionality.md):** aplicable; administrar autorizaciones no debe desplazar desproporcionadamente la comprensión y documentación.
- **[O1/O3/O4/O6 — interacción cuádruple](../tensions/semantic-continuity-authorization-capacity-effort-inversion.md):** candidata específica para F07. Examinar si agrega dificultades conjuntas no cubiertas por las tensiones anteriores antes de promoverla a tensión autónoma.

Los mecanismos deben responder a las tensiones materialmente aplicables y a sus límites, sin asumir que formularlas prueba su resolución.

## 11. Trazabilidad con las orientaciones

| Orientación | Clasificación | Justificación |
| --- | --- | --- |
| [O0 — Principal](../orientation/README.md) | **Complemento** | Conecta la autorización con la finalidad pedagógica, sin originar la autoridad para aprobar. |
| [O1 — Continuidad semántica](../orientation/semantic-continuity.md) | **Complemento** | El alcance aprobado aporta una referencia semántica reconocible para continuar y reconsiderar cambios. |
| [O2 — Aprovechamiento tecnológico](../orientation/technology-enabled-semantic-continuity.md) | **Complemento** | Tecnología puede simplificar gestión de autorizaciones, impactos y dependencias; no autoriza por sí misma. |
| [O3 — Carga y capacidad humana](../orientation/human-effort-and-agency.md) | **Condición** | Autorización y reautorización introducen trabajo humano; debe considerarse su proporcionalidad. |
| [O4 — Autorización humana](../orientation/human-pedagogical-authorization.md) | **Origen** | Justifica directamente decisiones de aprobación pedagógica bajo autoridad humana responsable. |
| [O5 — Reconocimiento de aportes](../orientation/transparent-contribution-recognition.md) | **Sin incidencia** | Reconocer contribuciones y decidir quién autoriza son responsabilidades distintas. |
| [O6 — Inversión del esfuerzo](../orientation/effort-inversion.md) | **Condición** | Gestionar aprobaciones no debe desplazar desproporcionadamente la comprensión, formulación y documentación. |

## 12. Continuidad

T06 fue cerrado conceptualmente el 2026-10-16. Esta reconciliación separa la definición general de las decisiones del MVP y de los mecanismos. Versionamiento, colaboración institucional, detección asistida de impacto y coordinación de ciclo de vida siguen pendientes.

**Mantenimiento:** revisar correspondencias y tensiones si cambian orientaciones, sin deducir eficacia del cierre conceptual.
