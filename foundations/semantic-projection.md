# F05 — Proyección semántica

**Estado:** fundamento conceptual de la familia PResolver, reconciliado para TDidacta por decisión del fundador (2026-10-16). Formalización transversal y validación operativa pendientes.

## 1. Definición

La **proyección semántica** es el fundamento que relaciona una o varias representaciones intermedias con los procesos de **exploración y realización** que se desarrollan a partir del significado representado.

Permite utilizar significados, relaciones y restricciones expresados en IR para examinar posibilidades o concretar elementos del dominio mediante capacidades tecnológicas. Puede operar sobre una representación o combinar varias, cuando sus significados sean compatibles.

No define los mecanismos que ejecutan esas operaciones ni garantiza la corrección de sus resultados. Es distinta de la [abstracción semántica](semantic-abstraction.md), que relaciona documentación en prosa con IR.

## 2. Exploraciones y realizaciones

El significado concreto de estas operaciones depende del dominio y de la intención representada.

### Realización

Una **realización** concreta elementos cuyo **alcance pedagógico es menor o igual** al de la intención representada. «Alcance» no equivale necesariamente a duración, volumen de material o número de componentes.

Por ejemplo, desde una intención de unidad pueden producirse propuestas de trayectorias de clases. Estas pueden considerarse posteriormente **intenciones pedagógicas candidatas**, pero no adquieren aprobación automática. La proyección genera candidatos; la contextualización, revisión y autorización mantienen sus responsabilidades independientes.

No es obligatorio realizar de una vez el alcance íntegro de la intención.

### Exploración

Una **exploración** efectúa verificaciones específicas sobre significados, posibilidades, restricciones o aplicabilidad de una intención representada.

Puede examinar si el espacio de posibilidades está **suficientemente delimitado para una operación concreta**, buscar alternativas, contrastar condiciones o revelar ambigüedades y contradicciones que informen una futura revisión de la intención.

**Una exploración no garantiza por sí sola** que toda la intención esté bien delimitada, ni equivale necesariamente a una prueba formal o a una realización definitiva.

## 3. Espacio de posibilidades y continuidad

La intención delimita un espacio de posibilidades; la proyección puede explorarlo para verificar propiedades específicas antes de continuar o para producir realizaciones pertinentes.

Los resultados pueden informar la corrección de la intención, **pero no reescriben automáticamente su documentación**.

La continuidad semántica entre intención, representación, exploración y realización debe poder examinarse. No se presume que cualquier combinación de IR sea válida o preserve significado sin pérdida.

## 4. Apoyo directo a quien aprende

Desde la representación de una clase o actividad, exploraciones pueden adaptar explicaciones, ejemplos, enfoques y recorridos a necesidades concretas de quien aprende, manteniendo su relación con la intención pertinente.

Esto no requiere modificar la intención original en todos los casos, ni garantiza aprendizaje por el solo hecho de producir alternativas.

## 5. Límites

La proyección semántica:

- No exige una sola IR ni compatibilidad universal entre representaciones.
- No convierte una exploración particular en garantía general sobre todo el espacio de posibilidades.
- No garantiza calidad pedagógica, conformidad semántica o aprendizaje efectivo.
- No promueve automáticamente realizaciones a intenciones aceptadas o autorizadas.
- No sustituye contextualización, revisión, corrección o autorización humana.
- No implica reversibilidad ni copia literal de documentación.
- No define mecanismos tecnológicos específicos.

## 6. Nota de especialización — TDidacta

En TDidacta, las IR pueden representar intenciones pedagógicas, subdivisiones, circunstancias y relaciones con otras intenciones. Su [IR Specification](../products/ir-specification/README.md) define la representación concreta.

La proyección sirve tanto para explorar la delimitación de intenciones como para producir realizaciones o apoyar experiencias adaptadas a estudiantes. El [mecanismo de proyección a dominio](../mechanisms/intermediate-to-domain-projection.md) es independiente de esta definición y permanece pendiente de especificación operativa.

## 7. Tensiones aplicables

- **[O1 ↔ O3](../tensions/semantic-continuity-human-effort.md):** revisar que exploraciones y realizaciones preserven la intención puede generar una carga de comparación y corrección considerable. O2 puede atenuarla, sin beneficio garantizado.
- **[O3 ↔ O6](../tensions/effort-inversion-proportionality.md):** producir muchas alternativas puede desplazar esfuerzo humano desde comprender hacia seleccionar, corregir y mantener resultados. Generar más no constituye por sí mismo un objetivo.

Los mecanismos de F05 deberán explicar cómo atienden ambas tensiones y cómo pueden contrastarse sus límites.

## 8. Trazabilidad con las orientaciones

| Orientación | Clasificación | Justificación |
| --- | --- | --- |
| [O0 — Principal](../orientation/README.md) | **Condición** | En TDidacta, las exploraciones y realizaciones deben responder a necesidades pedagógicas; no se impone esa especialización al fundamento general PResolver. |
| [O1 — Continuidad semántica](../orientation/semantic-continuity.md) | **Origen** | Justifica mantener relación significativa entre representaciones, exploraciones y realizaciones. |
| [O2 — Aprovechamiento tecnológico](../orientation/technology-enabled-semantic-continuity.md) | **Origen** | Justifica aprovechar tecnología para examinar y concretar alternativas del dominio, sin tecnología específica obligatoria. |
| [O3 — Carga y capacidad humana](../orientation/human-effort-and-agency.md) | **Condición** | Exige considerar esfuerzo de generación, selección, revisión y corrección frente a la capacidad obtenida. |
| [O4 — Autorización humana](../orientation/human-pedagogical-authorization.md) | **Sin incidencia** | Aprobar resultados es una responsabilidad externa a la identidad de la proyección. |
| [O5 — Reconocimiento de aportes](../orientation/transparent-contribution-recognition.md) | **Sin incidencia** | Atribuir contribuciones corresponde a otras responsabilidades, principalmente documentales. |
| [O6 — Inversión del esfuerzo](../orientation/effort-inversion.md) | **Condición** | La proyección debe favorecer concentración del trabajo humano en comprender y documentar, no en producir o administrar realizaciones repetitivas. |

## 9. Mantenimiento

La definición general no presupone eficacia ni equivalencia técnica entre flavors. Reexaminar las orientaciones y tensiones cuando cambien, sin convertir la generación en garantía de conformidad o autorización.
