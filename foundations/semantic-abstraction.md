# F04 — Abstracción semántica

**Estado:** fundamento conceptual reconocido para la familia PResolver y reconciliado con las orientaciones en TDidacta (2026-10-16). Formalización general y validación operativa entre flavors pendientes.

## 1. Definición

La **abstracción semántica** es el fundamento que establece la relación entre la documentación expresada en prosa y una representación intermedia estructurada de su significado.

Su propósito es permitir que el conocimiento, las decisiones, las relaciones y las restricciones expresadas documentalmente puedan representarse de una forma que facilite su utilización tecnológica posterior.

La representación intermedia resultante puede utilizarse individualmente o en combinación con otras representaciones, tanto del mismo flavor como de otros miembros de la familia PResolver.

Esta capacidad de composición busca facilitar la exploración de posibilidades y la producción de realizaciones mediante tecnologías, sin exigir que cada operación posterior vuelva a interpretar íntegramente la documentación original.

La abstracción semántica no define por sí misma cómo se generan exploraciones o realizaciones. Establece una representación del significado que puede ser utilizada para facilitar esas operaciones posteriores.

## 2. Relación entre documentación y representación

La documentación en prosa permite expresar conocimiento, intenciones, contexto, decisiones y restricciones de manera comprensible para las personas.

La representación intermedia permite organizar parte de ese significado en una estructura que pueda ser interpretada y utilizada por sistemas tecnológicos.

La abstracción relaciona ambas expresiones sin asumir que sean idénticas ni que toda la riqueza de la documentación pueda convertirse automáticamente en una estructura formal.

Para conservar la continuidad semántica, deben poder reconocerse las relaciones, restricciones y significados relevantes, así como las ambigüedades o pérdidas que puedan aparecer durante la transformación.

La representación intermedia no reemplaza necesariamente a la documentación de origen.

## 3. Composición de representaciones

Una representación intermedia puede expresar una parte delimitada del conocimiento documentado.

Varias representaciones pueden combinarse para abordar necesidades o situaciones que requieran considerar distintos elementos relacionados.

Estas representaciones pueden proceder de un mismo flavor o de diferentes flavors de PResolver, siempre que sus significados y relaciones sean compatibles con la composición pretendida.

La posibilidad de combinar representaciones no implica que todas sean universalmente compatibles ni que su combinación produzca automáticamente resultados coherentes.

La compatibilidad y la preservación del significado deben poder examinarse.

## 4. Relación con exploraciones y realizaciones

La abstracción semántica facilita disponer de representaciones estructuradas que puedan utilizarse para explorar posibilidades y producir realizaciones mediante tecnologías.

Esto permite separar dos responsabilidades:

- **Abstracción semántica:** representar estructuradamente significado documentado.
- **Proyección semántica:** utilizar representaciones intermedias para producir exploraciones o realizaciones.

La abstracción no realiza por sí misma las exploraciones o realizaciones posteriores.

Su finalidad es facilitar estas operaciones, incluyendo aquellas que requieran utilizar varias representaciones de manera conjunta.

## 5. Límites

La abstracción semántica:

- No exige un formato universal de representación intermedia.
- No presupone que toda la documentación pueda representarse sin pérdidas.
- No requiere que la transformación sea reversible.
- No garantiza la compatibilidad entre representaciones.
- No demuestra que una representación obtenida sea semánticamente conforme.
- No convierte automáticamente una representación en un elemento pedagógicamente autorizado.
- No define cómo deben implementarse los mecanismos de transformación.
- No ejecuta las operaciones posteriores de exploración o realización.

La utilidad y eficacia de las representaciones deberán contrastarse en sus aplicaciones concretas.

## 6. Hipótesis de utilidad — separada de la definición

Se plantea la **hipótesis investigativa, no demostrada**, de que una representación intermedia estructurada puede ser **más efectiva y/o eficiente que la documentación en prosa** para determinadas operaciones tecnológicas. La prosa contiene explicaciones, redundancias y otros elementos expresivos útiles para comprensión humana que podrían no ser necesarios en igual medida para cada procesamiento tecnológico.

- **Efectividad:** preservar y usar correctamente el significado relevante para las operaciones pretendidas.
- **Eficiencia:** recursos y esfuerzos de obtener resultados, **incluyendo construcción, validación, mantenimiento y uso de la IR**.

La compactación no prueba ninguna ventaja. La hipótesis debe contrastarse frente a procesar directamente la prosa y evaluarse en Research sin definir la identidad del fundamento por el resultado del contraste.

## 7. Nota de especialización — TDidacta

En TDidacta, la documentación de origen puede expresar necesidades, intenciones pedagógicas, subdivisiones, circunstancias de aplicación y relaciones entre intenciones.

La abstracción semántica permite relacionar esa documentación con representaciones intermedias que faciliten exploraciones y realizaciones pedagógicas posteriores.

La definición documental corresponde a TDidacta Docs Standard, mientras que las características concretas de la representación intermedia corresponden a su [IR Specification](../products/ir-specification/README.md).

Esta nota describe la aplicación del fundamento al dominio pedagógico. No modifica su definición general ni incorpora responsabilidades de mecanismos particulares.

## 8. Tensiones aplicables

- **[O1 ↔ O3](../tensions/semantic-continuity-human-effort.md):** preservar significado al abstraer puede exigir trabajo de estructuración, revisión y mantenimiento. O2 puede aportar asistencia, sin garantizar ahorro.
- **[O3 ↔ O6](../tensions/effort-inversion-proportionality.md):** crear o mantener IR puede desviar esfuerzo desde comprender hacia gestionar estructuras. La inversión debe ser proporcionada, sin dar por resuelta la tensión.

Los mecanismos correspondientes deberán responder a ambas y mostrar sus límites. La hipótesis de mayor eficiencia de IR frente a prosa es una pregunta investigativa distinta, no una tercera tensión ya identificada.

## 9. Trazabilidad con las orientaciones

| Orientación | Clasificación | Justificación |
| --- | --- | --- |
| [O0 — Principal](../orientation/README.md) | **Condición** | En TDidacta, la especialización debe responder a necesidades pedagógicas; no se impone este dominio al fundamento general PResolver. |
| [O1 — Continuidad semántica](../orientation/semantic-continuity.md) | **Origen** | Justifica conservar significado en la relación entre prosa e IR. |
| [O2 — Aprovechamiento tecnológico](../orientation/technology-enabled-semantic-continuity.md) | **Origen** | Justifica aprovechar capacidades tecnológicas mediante representaciones utilizables, sin exigir una tecnología particular. |
| [O3 — Carga y capacidad humana](../orientation/human-effort-and-agency.md) | **Condición** | Exige considerar el esfuerzo y las capacidades reales introducidas por la abstracción. |
| [O4 — Autorización humana](../orientation/human-pedagogical-authorization.md) | **Sin incidencia** | La autorización de documentación de entrada es una responsabilidad externa a la definición de abstracción. |
| [O5 — Reconocimiento de aportes](../orientation/transparent-contribution-recognition.md) | **Sin incidencia** | Reconocimiento corresponde a otras responsabilidades, aunque pueda haber metadatos significativos que preservar desde O1. |
| [O6 — Inversión del esfuerzo](../orientation/effort-inversion.md) | **Condición** | Debe favorecer concentración humana en comprensión/documentación por sobre gestión o producción repetitiva de realizaciones. |

**Mantenimiento:** revisar clasificaciones y tensiones cuando cambien las orientaciones; no confundir su relación conceptual con eficacia demostrada.
