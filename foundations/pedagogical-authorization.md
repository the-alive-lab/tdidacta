# F07 — Autorización de elementos pedagógicos

**Estado:** núcleo O0–O6 reconciliado por decisión del fundador (2026-10-17). Revisión O7–O10 y capas conceptuales nuevas **propuestas**, pendientes de aprobación. No implica implementación ni eficacia demostrada.

## 1. Origen y responsabilidad

F07 nace de **O4 — Autorización humana** y establece la responsabilidad de **aceptar bajo autoridad humana pertinente decisiones pedagógicas para usos y alcances semánticos reconocibles**. O0 sitúa su finalidad educativa; O1 exige distinguir significados aprobados de cambios posteriores.

No confunde formular, revisar, corregir, autorizar ni publicar. La autorización puede existir antes de realizar elementos derivados y no se extiende automáticamente a ellos.

## 2. Relaciones del fundamento

- **Decisión situada:** aceptar un elemento para determinados usos no constituye aprobación universal de sus realizaciones, contextos o dependencias.
- **Estabilidad semántica sin inmovilidad:** el significado aprobado permanece identificable, aunque puedan formularse alternativas y propuestas de cambio.
- **Continuidad con F06:** si cambios externos modifican necesidades o circunstancias, revisar la intención puede motivar correcciones. Lo autorizado conserva su alcance hasta que una decisión humana pertinente adopte los cambios materiales.
- **Reautorización por impacto:** distinguir qué elementos y dependencias han cambiado materialmente; conservar vigencia de lo no afectado y reconsiderar solamente lo que cambia de alcance.
- **Autoridad humana contextual:** quien decide debe tener autoridad pertinente, no necesariamente haber creado o editado el elemento. La identidad personal verificada, la identidad operativa y la autoridad no son la misma propiedad.
- **Proporcionalidad:** controles y evidencias deben permitir comprender qué se aprobó sin introducir sobrecarga de gestión innecesaria.

## 3. Conceptos originados o ampliados desde F07

| Concepto | Aporte de F07 | Entrada |
| --- | --- | --- |
| Autorización pedagógica | Amplía la capa F06 con la decisión constitutiva, autoridad, alcance, estabilidad y vigencia. | [Definición acumulativa y capa F07](../concepts/pedagogical-authorization.md) |
| Alcance de autorización pedagógica | Delimita los significados, circunstancias y usos comprendidos en una aprobación. | [Definición y capa F07](../concepts/pedagogical-authorization-scope.md) |
| Reautorización pedagógica | Reconsidera decisiones cuando cambios materiales afectan lo previamente aceptado, sin aprobación global obligatoria. | [Definición y capa F07](../concepts/pedagogical-reauthorization.md) |

Las definiciones viven en Concepts. Las responsabilidades técnicas de impacto, cambios y versionamiento no se convierten automáticamente en fundamentos o conceptos nuevos.

## 4. Condiciones, especialización y tensiones

**O2** puede asistir el reconocimiento de cambios y dependencias sin conceder autoridad. **O3** y **O6** exigen proporcionalidad. **O5** no define quién autoriza: atribuir aportes y disponer de autoridad son cuestiones distintas.

En el MVP de TDidacta la persona titular de una cuenta autoriza en el escenario de profesor particular y evalúa manualmente impactos. Esto es **decisión operativa situada**, no exigencia conceptual de cuenta propia, titular único ni jerarquía universal.

**O7 (propuesta):** privacidad de datos personales en evidencia de decisiones. **O8 (propuesta):** cuando se necesita identidad personal verificada, distinguir reconocimiento externo de titularidad, cuenta y autoridad. **O9 (marginal propuesta):** el alcance puede reconocer usos educativos directos e indirectos. **O10 (marginal propuesta):** aprobar recursos públicos no asegura su preservación ni disponibilidad independiente.

Persisten [O1/O3/O4](../tensions/semantic-continuity-authorization-human-capacity.md), [O3/O6](../tensions/effort-inversion-proportionality.md) y la interacción [O1/O3/O4/O6](../tensions/semantic-continuity-authorization-capacity-effort-inversion.md), esta última candidata. No se presumen resueltas.

## 5. Fronteras

La autorización no equivale a revisión ni corrección (F06), abstracción (F04), proyección (F05), evaluación de calidad, consentimiento, derechos de uso, publicación o permanencia de recursos.

No establece formatos de prueba de autorización, esquema de identidad interno, sistema de versionamiento o automatización del análisis de impacto. Véase [versionamiento candidato](../mechanisms/pedagogical-element-versioning.md) y [gobernanza](../governance/README.md).

## 6. Trazabilidad O→F07

| Orientación | Clasificación | Justificación |
| --- | --- | --- |
| [O0 — Principal](../orientation/README.md) | **Complemento** | Conecta la autorización con la finalidad pedagógica, sin originar la autoridad para aprobar. |
| [O1 — Continuidad semántica](../orientation/semantic-continuity.md) | **Complemento** | El alcance aprobado aporta una referencia semántica reconocible para continuar y reconsiderar cambios. |
| [O2 — Aprovechamiento tecnológico](../orientation/technology-enabled-semantic-continuity.md) | **Complemento** | Tecnología puede simplificar gestión de autorizaciones, impactos y dependencias; no autoriza por sí misma. |
| [O3 — Carga y capacidad humana](../orientation/human-effort-and-agency.md) | **Condición** | Autorización y reautorización introducen trabajo humano; debe considerarse su proporcionalidad. |
| [O4 — Autorización humana](../orientation/human-pedagogical-authorization.md) | **Origen** | Justifica directamente decisiones de aprobación pedagógica bajo autoridad humana responsable. |
| [O5 — Reconocimiento de aportes](../orientation/transparent-contribution-recognition.md) | **Sin incidencia** | Reconocer contribuciones y decidir quién autoriza son responsabilidades distintas. |
| [O6 — Inversión del esfuerzo](../orientation/effort-inversion.md) | **Condición** | Gestionar aprobaciones no debe desplazar desproporcionadamente la comprensión, formulación y documentación. |
| [O7 — Privacidad por diseño](../orientation/privacy-by-design-and-data-minimization.md) | **Condición propuesta** | Acreditar autoría de decisiones o conservar evidencia no exige publicar o retener datos personales innecesarios. |
| [O8 — Reconocimiento externo de identidades](../orientation/external-personal-identity-recognition.md) | **Condición propuesta** | Cuando sea necesario vincular una autorización con identidad personal verificada, esa identificación se reconoce externamente; la autoridad contextual se determina por separado. |
| [O9 — Accesibilidad contextual](../orientation/contextual-access-and-educational-reach.md) | **Incidencia marginal propuesta** | Una autorización puede estar situada para resultados de uso directo o indirecto; garantizar accesibilidad pertenece a contextualización y realizaciones, no a la aprobación misma. |
| [O10 — Continuidad de recursos públicos](../orientation/public-resource-continuity.md) | **Incidencia marginal propuesta** | Autorizar un elemento publicable no equivale a preservar su disponibilidad posterior; la continuidad se debe atender por capacidades de publicación y distribución. |


## 7. Mantenimiento

Las propuestas de O7–O10 y capas F07 requieren reconciliación del fundador. El cierre anterior de T06 no significa que se hayan validado mecanismos o resultados.
