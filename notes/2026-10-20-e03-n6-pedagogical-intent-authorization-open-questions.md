# E03-N6 — Cuestiones de intención, variación y autorización (fuera de Responsibilities)

**Estado:** nota de trabajo para investigación y reconciliación posterior; **no es modificación ni adopción** de Foundations, Concepts o mecanismos.  
**Origen:** diálogo del 2026-10-20 al contrastar E03-N6, desde la revisión de E03-N5.  
**Continuidad:** [bootstrap V6](tdidacta-v6-coverage-bootstrap.md), [registro de Responsibilities](2026-10-20-e02-e03-responsibilities-reconciliation.md), [E03](../scenarios/e03-educacion-institucional.md).

## Acuerdos conceptuales expresados por el fundador

1. **Adaptación dentro de la intención:** la adaptación pedagógica usa herramientas y posibilidades de adaptación provistas por la intención; ejercerlas **no modifica** la intención. No clasificar como adaptación F10 una alteración de aquello que la intención permite solo porque conserve aproximadamente el propósito.
2. **Intenciones de mayor alcance:** pueden definir el espacio de modificaciones permitidas para elementos subordinados más pequeños, incluso variaciones que no necesiten una nueva autorización explícita.
3. **Condiciones de autorización declaradas:** las intenciones de mayor alcance **también pueden declarar condiciones de autorización** para cambios en sus elementos internos: qué se puede variar, hasta dónde y bajo qué condiciones se exige autorización posterior.
4. **Granularidad:** actividad, clase, unidad y trayectoria son escalas ilustrativas relevantes, pero el tamaño del cambio por sí mismo no demuestra impacto ni necesidad de reautorización.
5. **Configuraciones:** las configuraciones contextuales deben distinguirse de las posibilidades y condiciones pedagógicas definidas por intenciones. La labor operativa candidata de gestión de configuraciones distinta de accesos se registra como **T-R05b** en el registro de Responsibilities, no como fundamento nuevo.

## Problema conceptual pendiente

Distinguir con precisión:

- **Ejercicio de adaptación ya prevista** por una intención autorizada: no cambia la intención de referencia.
- **Variación/modificación de un elemento subordinado** expresamente permitida por una intención superior: definir cuándo es mera instancia de posibilidades autorizadas y cuándo produce una nueva versión, aun sin exigir autorización humana explícita posterior.
- **Extensión o modificación fuera de condiciones previstas**: definir qué revisión y autorización corresponde, considerando alcance, restricciones, impacto semántico y dependencias.
- **Restricción contextual más estricta:** examinar si una configuración de plataforma puede exigir controles operativos adicionales sin alterar el alcance pedagógico autorizado; diferenciar esos controles de la autorización de T-R02.

## Tensiones que deben examinarse, sin resolverlas aquí

- **Inmutabilidad vs. variación autorizada:** [F07](../foundations/pedagogical-authorization.md) sostiene versiones consolidadas inmutables y candidatas para cambios; precisar cómo convive con autorizaciones que incluyen un espacio de modificación en elementos subordinados.
- **Autonomía vs. protección:** evitar que cambios triviales obliguen a una autorización repetitiva y evitar que la libertad de variación habilite alterar silenciosamente el significado de lo autorizado.
- **Semántica vs. configuración:** no permitir que una configuración administrativa amplíe unilateralmente las posibilidades autorizadas ni que el gestor de configuración se convierta en autoridad pedagógica.
- **Grado del cambio vs. impacto:** diferenciar granularidad estructural (actividad/clase/unidad/trayectoria), dependencias y alteración pedagógica real.

## Superficies candidatas para contraste posterior

- [F02 — Necesidades e intenciones pedagógicas](../foundations/pedagogical-needs-and-intentions.md).
- [F06 — Revisión y corrección pedagógica](../foundations/pedagogical-review-and-correction.md).
- [F07 — Autorización pedagógica](../foundations/pedagogical-authorization.md).
- [F10 — Adaptación pedagógica](../foundations/pedagogical-adaptation.md).
- [F11 — Autonomía de organización contextual](../foundations/contextual-organization-autonomy.md) y [F12 — Configuraciones iniciales](../foundations/opinionated-starting-configurations.md).
- [Concepto Intención pedagógica](../concepts/pedagogical-intention.md), [concepto Alcance de autorización](../concepts/pedagogical-authorization-scope.md) y [versionamiento candidato](../mechanisms/pedagogical-element-versioning.md).

## Casos para contrastar posteriormente (ejemplos, no reglas aprobadas)

1. Sustituir ejercicios o ejemplos previstos dentro de una clase sin nueva autorización.
2. Alterar el objetivo de comprensión o una restricción esencial de una unidad.
3. Reordenar clases de una trayectoria sin alterar, o alterando, dependencias pedagógicas.
4. Variar un elemento subordinado dentro de condiciones explícitas definidas por la intención superior.
5. Exigir una revisión contextual adicional para una variación pedagógicamente permitida.

## Límite y continuación

**No editar todavía** definiciones canónicas aprobadas ni inferir una política universal de reautorización. Estas cuestiones se retomarán **después de completar E03–E05**, conforme a la instrucción del fundador. Mantenerlas separadas de la reconciliación de Responsibilities, sin alterar los estados T01–T28.

## Ampliación acordada — organización composicional de intenciones (2026-10-20)

**Decisión de dirección conceptual expresada por el fundador:** no tratar `planificación → unidad → clase → actividad` como jerarquía estructural obligatoria ni restringir TDidacta a esas cuatro denominaciones. Pueden conservarse como **configuraciones iniciales opinionadas** (F12) de ciertos contextos, no como tipos universales.

- **Escalas y etiquetas configurables:** las denominaciones «planificación», «unidad», «clase», «actividad» y otras son posibles interpretaciones contextuales de organizaciones de intenciones, no primitivas pedagógicas universales.
- **Primitivas a investigar (no adoptadas):** `Contenedor` y `Trayectoria`. Como ejemplo de gramática candidata: un contenedor admite contenedores y trayectorias; una trayectoria admite contenedores. T-R05b podría gestionar etiquetas, combinaciones permitidas y validez estructural de las combinaciones en la configuración contextual. **No se ha demostrado que estas dos primitivas sean suficientes ni que sus reglas ejemplificadas deban ser definitivas.**
- **Reutilización sin duplicación:** una misma intención **debe poder participar en varias trayectorias independientes sin duplicar su identidad**. La posibilidad y sus límites dependen tanto de las condiciones estructurales configuradas como de las **condiciones de organización que la propia intención puede declarar para generar nuevas intenciones**.
- **Condiciones de organización propias de la intención:** una intención puede restringir qué nuevas intenciones se originan o relacionan con ella y bajo qué condiciones, además del espacio y condiciones de modificación/autorización ya registrados. El detalle de precedencia, herencia, propagación de restricciones y conflictos sigue abierto.
- **Frontera T-R05b:** configura la organización admitida por el contexto (no los accesos, que corresponden a T-R05a); **no** puede imponer por sí misma restricciones adicionales sobre la autorización pedagógica de una intención ni modificar su alcance autorizado. Validez organizativa no demuestra autorización pedagógica.
- **Relaciones no arbóreas:** investigar composición, secuenciación, dependencia, convergencia y reutilización; la participación en varias trayectorias no debe forzar copias de la intención ni una jerarquía escolar única. No afirmar todavía que cada contenedor/trayectoria sea necesariamente una intención, ni que cada relación esté resuelta por las dos primitivas.

**Contraste pendiente:** confrontar la propuesta con F02/F07/F10/F11/F12, Intención pedagógica, Alcance de autorización y mecanismos de versionamiento, preservando la inmutabilidad de versiones consolidadas y la separación entre adaptación prevista y modificación de la intención. Examinar expresamente si el uso de una intención por varias trayectorias afecta versión, contexto o alcance autorizado. Esta nota no cambia esas definiciones canónicas ni autoriza implementar una gramática fija.

**Seguimiento:** mantener esta cuestión separada de la reconciliación de Responsibilities y retomarla después del contraste E03–E05, sin perder el acuerdo de dirección de diseño ni fingir cierre semántico.

## Actualización de continuidad — autorización derivada, evolución y feedback (2026-10-20)

**Estado:** acuerdos de dirección del fundador y modelo candidato; no promoción de F02/F06/F07, versionamiento o Lifecycle. Esta actualización complementa, sin reemplazar, las preguntas previas.

### Autorización directa y derivada

- **Directa:** T-R02 acepta expresamente una versión y su alcance, incluidas las condiciones que permiten crear o modificar elementos derivados.
- **Derivada:** un elemento o variante creado bajo esas condiciones recibe habilitación para **uso situado** sin una nueva intervención explícita de T-R02 por cada derivación. La legitimidad deriva de una autorización directa preexistente; no es consolidación ni aprobación universal.
- **Consolidación posterior opcional:** una variante derivada puede permanecer para usos específicos, desecharse o presentarse para autorización directa y constituir una nueva versión consolidada. No hay obligación de fusionar cada variante.
- **Reutilización entre contextos:** una variante puede utilizarse sucesivamente en varios contextos cuando las condiciones de su origen y las restricciones aplicables a cada contexto lo admitan. La evidencia positiva de uso no produce autorización directa automática.
- **Versiones ilustrativas:** `v1.0.0-A.1`, `v1.0.0-A.2` son etiquetas explicativas de variantes situadas; `v1.1.0` representa una posible consolidación directa. **No adoptar semver, prerelease o sintaxis de IDs como contrato técnico.** Identidad, trazabilidad y versiones consolidadas inmutables deben mantenerse distinguibles.

**Tensión explícita con F07 vigente:** hoy exige autorización propia de nuevas intenciones y versiones. Distinguir derivación autorizada de una intención nueva que requiera aprobación directa; plantear revisión expresa del fundamento y del concepto Alcance de autorización. No modificarlo implícitamente.

### Ciclo candidato de evolución pedagógica — dos períodos, cuatro etapas

**Período de desarrollo situado:** (1) **Contextualización**, formulación y autorización directa de una versión base; (2) **Adaptación acumulativa**, variantes derivadas, refinadas y combinadas por T-R01 conforme a las condiciones de origen, sin promover cada iteración.

**Período de consolidación:** (3) **Pulimiento general**, examen de variantes y feedback justificado de T-R02, recogiendo observaciones y experiencias; (4) **Consolidación selectiva**, decisión de autorizar directamente una nueva versión, solicitar más revisión/evidencia o no incorporar propuestas.

El lifecycle **no está subordinado a años, semestres ni a un calendario escolar**. Sus momentos responden a necesidades y condiciones de quienes ejercen las Responsibilities. Feedback y revisión pueden producirse continuamente en todos los períodos, no solo durante pulimiento. Las dos etapas de revisión/consolidación no implican que T-R02 se apropie del desarrollo especializado de T-R01.

**No consolidar ≠ prohibir uso situado.** Una propuesta no incorporada puede mantener su uso derivado dentro de condiciones vigentes. Una restricción de usos futuros requeriría decisión pertinente distinta, explícita y trazable. Evitar borrar retrospectivamente los usos históricos legítimos.

### Fusiones y linajes de autorización

- **Origen directo compartido:** variantes `v1.0.0-A.1` y `v1.0.0-B.1` pueden fusionarse autónomamente por T-R01 dentro del linaje `v1.0.0`, sin solicitar por defecto otra autorización humana individual. Una comprobación proporcionada debe asegurar que **la combinación también respeta** las condiciones heredadas; que ambas variantes las cumplan separadamente no demuestra automáticamente que la combinación las cumpla.
- **Orígenes directos distintos:** fusionar, p. ej., `v1.0.0-A.1` y `v1.0.1-B.1` requiere reconsiderar compatibilidad de condiciones, significado, dependencias y alcances; la diferencia de identificador por sí sola no prueba incompatibilidad.
- La relación de origen es semántica, no una convención de nombres. Permanecen por definir conflictos de condiciones, ramas, identificación de variantes y derivaciones de derivaciones.

### Feedback transversal, multidisciplinar y multinivel

TDidacta debe **facilitar cuestionamiento, observaciones y mejora** desde perspectivas pedagógicas, disciplinares, de accesibilidad, psicológicas, técnicas y desde quienes aprenden, aplicables a elementos y relaciones de distintas escalas (actividades, trayectorias, intenciones, organización y experiencia).

Distinguir **feedback general para mejorar** de **feedback de autorización** emitido por T-R02: el segundo debe identificar objeto/alcance examinado, aspectos aceptados, rechazados o pendientes, razones/evidencia/incertidumbre y condiciones para reconsideración. Las justificaciones deben ser navegables, suficientes y proporcionadas, sin burocracia universal. T-R02 puede rechazar incorporación directa sin convertir cada variante rechazada en prohibición general.

No inferir una Responsibility adicional solo por existir feedback; confrontar F06, F08/F09, Relationships, Lifecycle y mecanismos, preservando la finalidad de cada Responsibility.

### Pendientes explícitos

Contrastar versiones consolidadas inmutables y nuevas variantes con F07; qué autoriza exactamente el origen, revocación/restricción de usos futuros, reutilización entre contextos, composición y linajes, feedback/procedencia proporcional y reglas de consolidación. No declarar validación experimental o adopción formal. Mantener E03-N6 en curso y retomar conciliación canónica después de E03–E05.

## Cierre del contraste funcional E03-N6 — decisión del fundador (2026-10-20)

**Criterio confirmado:** una autorización derivada conserva su validez histórica asociada a su versión de origen, pero cada uso concreto debe satisfacer las condiciones y restricciones pertinentes en el contexto actual. Si cambian las circunstancias y deja de satisfacerlas, el uso ya no se presume cubierto; no se invalidan retroactivamente usos legítimos anteriores.

**Herencia acumulativa reconciliada como regla candidata:** una variante directamente derivada (p. ej. `v1-A`) puede declarar condiciones más específicas para nuevas derivaciones, sin adquirir autorización directa ni extender la autoridad de `v1`. Una variante posterior (`v1-A-B`) debe cumplir las condiciones de `v1-A` y, transitivamente, las de `v1`. Generar derivaciones requiere cobertura de autorización derivada válida, no meras facultades de edición.

**Fusiones:** las restricciones aplicables de cada origen deben ser compatibles y satisfechas por el resultado. Restricciones incompatibles impiden atribuir autorización derivada automáticamente: reformular una alternativa que cumpla las condiciones o presentar a autorización directa pertinente. En fusiones con mismo origen, T-R01 puede operar con autonomía sin solicitar por defecto autorización explícita para cada merge; esta autonomía no prueba automáticamente la conformidad de cualquier combinación.

**Reconciliación entre versiones ≠ consolidación:** `v1.0.0-A` permanece ligada a `v1.0.0` aunque se autorice directamente `v1.0.1`. Para trasladar su propuesta a `v1.0.1` corresponde examinar las condiciones nuevas y producir una variante reconciliada identificable (ej. `v1.0.1-A`), sometida a revisión según lo pertinente. Esto **no** convierte automáticamente la variante en nueva versión directamente autorizada; la consolidación es otra decisión de T-R02.

**Estado de cobertura:** el fundador declaró suficiente el criterio funcional de E03-N6 y confirmó la distinción autorización histórica / aplicabilidad presente. **E03-N6 queda cerrado solo en el contraste de Responsibilities y necesidades del escenario**. Autorización derivada, herencia, lifecycle y modelo de linajes siguen propuestas conceptuales por reconciliar expresamente con F02/F06/F07/F10 y sus Concepts. El cierre funcional no equivale a modificar F07, a adoptar un mecanismo de versionamiento ni a validar eficacia.
