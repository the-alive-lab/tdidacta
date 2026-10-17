# F04 — Abstracción semántica

**Estado:** núcleo O0–O6 reconciliado (2026-10-16). Revisión O7–O10 y entradas conceptuales **propuestas, pendientes de aprobación**. El fundamento conserva alcance transversal a PResolver, con especialización pedagógica en TDidacta.

## 1. Origen y responsabilidad

F04 surge de **O1 — Continuidad semántica** y **O2 — Aprovechamiento tecnológico**. Establece la responsabilidad de **relacionar significado documental en prosa con representaciones estructuradas aprovechables por tecnología**, manteniendo visibles restricciones, relaciones y posibles pérdidas o ambigüedades.

La abstracción no supone traducción perfecta, equivalencia ni reversibilidad. Tampoco reemplaza necesariamente la documentación de origen. **O0** condiciona su especialización al dominio pedagógico de TDidacta, no la definición general de PResolver.

## 2. Relaciones y condiciones del fundamento

- **Fuente y resultado diferenciados:** una representación estructurada puede contener solo parte del significado de su documentación de origen.
- **Continuidad verificable:** deben poder reconocerse significados y restricciones relevantes, así como ambigüedades y pérdidas significativas.
- **Composición condicionada:** representaciones del mismo o de distintos flavors pueden combinarse únicamente cuando sus significados y relaciones sean compatibles para el objetivo concreto; la compatibilidad no se presume.
- **Frontera de responsabilidad:** abstraer prepara significado para usos posteriores; **proyectar** para producir exploraciones o realizaciones pertenece a F05.
- **Esfuerzo proporcionado:** crear, validar y mantener estructuras introduce costos que O3 y O6 exigen contrastar con sus beneficios reales.

En TDidacta, las fuentes pueden expresar necesidades, intenciones, circunstancias y relaciones pedagógicas. Docs Standard define su representación documental; [IR Specification](../products/ir-specification/README.md) define características técnicas de IR.

## 3. Conceptos originados desde F04

| Concepto | Aporte específico de F04 | Entrada |
| --- | --- | --- |
| Abstracción semántica | Relación entre significado documental y representación estructurada; preservación y pérdidas. | [Definición y capa F04](../concepts/semantic-abstraction.md) |
| Representación intermedia semántica | Resultado conceptual estructurado que puede usarse individualmente o en combinación, sin imponer formato universal. | [Definición y capa F04](../concepts/semantic-intermediate-representation.md) |
| Composición de representaciones semánticas | Posibilidad condicionada por compatibilidad y continuidad de significado. | [Definición y capa F04](../concepts/semantic-representation-composition.md) |

Se preservan las definiciones en Concepts y las fronteras frente a estructuras técnicas y mecanismos. No se presupone que cada concepto nuevo requiera un nuevo producto.

## 4. Hipótesis de utilidad y tensiones

**Hipótesis investigativa, no demostrada:** una IR podría ser más efectiva o eficiente que procesar prosa directamente en determinadas operaciones tecnológicas. La comparación debe incluir construcción, validación, mantenimiento y utilización; compactación no prueba superioridad.

Persisten [O1 ↔ O3](../tensions/semantic-continuity-human-effort.md) y [O3 ↔ O6](../tensions/effort-inversion-proportionality.md). La asistencia O2 podría atenuar esfuerzo pero no garantiza ahorro.

**Nuevas orientaciones propuestas:** O7 condicionaría la minimización de datos personales durante abstracción y composición; O8 no modifica su frontera; O9 podría reforzar marginalmente preservación de circunstancias de acceso en el dominio pedagógico, no las capacidades de distribución; O10 no exige conservar recursos educativos como IR.

## 5. Fronteras

F04 no impone formato universal, reversibilidad, transformación sin pérdidas, compatibilidad automática, conformidad semántica demostrada, autorización pedagógica ni algoritmo concreto de transformación. No produce por sí mismo exploraciones o realizaciones.

La definición documental corresponde a Docs Standard; esquemas de IR corresponden a IR Specification; producción a partir de IR corresponde a [F05 — Proyección semántica](semantic-projection.md).

## 6. Trazabilidad O→F04

| Orientación | Clasificación | Justificación |
| --- | --- | --- |
| [O0 — Principal](../orientation/README.md) | **Condición** | En TDidacta, la especialización debe responder a necesidades pedagógicas; no se impone este dominio al fundamento general PResolver. |
| [O1 — Continuidad semántica](../orientation/semantic-continuity.md) | **Origen** | Justifica conservar significado en la relación entre prosa e IR. |
| [O2 — Aprovechamiento tecnológico](../orientation/technology-enabled-semantic-continuity.md) | **Origen** | Justifica aprovechar capacidades tecnológicas mediante representaciones utilizables, sin exigir una tecnología particular. |
| [O3 — Carga y capacidad humana](../orientation/human-effort-and-agency.md) | **Condición** | Exige considerar el esfuerzo y las capacidades reales introducidas por la abstracción. |
| [O4 — Autorización humana](../orientation/human-pedagogical-authorization.md) | **Sin incidencia** | La autorización de documentación de entrada es una responsabilidad externa a la definición de abstracción. |
| [O5 — Reconocimiento de aportes](../orientation/transparent-contribution-recognition.md) | **Sin incidencia** | Reconocimiento corresponde a otras responsabilidades, aunque pueda haber metadatos significativos que preservar desde O1. |
| [O6 — Inversión del esfuerzo](../orientation/effort-inversion.md) | **Condición** | Debe favorecer concentración humana en comprensión/documentación por sobre gestión o producción repetitiva de realizaciones. |
| [O7 — Privacidad por diseño](../orientation/privacy-by-design-and-data-minimization.md) | **Condición propuesta** | Estructurar y combinar significado no justifica por sí mismo propagar, conservar ni inferir nuevos datos personales innecesarios. |
| [O8 — Reconocimiento externo de identidades](../orientation/external-personal-identity-recognition.md) | **Sin incidencia propuesta** | La abstracción no reconoce ni certifica identidades personales; conservar referencias semánticas justificadas no equivale a acreditarlas. |
| [O9 — Accesibilidad contextual](../orientation/contextual-access-and-educational-reach.md) | **Incidencia marginal propuesta** | En la especialización TDidacta puede ser útil preservar restricciones contextuales de acceso presentes en las fuentes; la utilizabilidad directa o indirecta corresponde a realizaciones y mecanismos posteriores. |
| [O10 — Continuidad de recursos públicos](../orientation/public-resource-continuity.md) | **Sin incidencia propuesta** | La preservación independiente de recursos publicados no define la transformación entre prosa e IR ni exige que todo recurso se almacene como IR. |

**Mantenimiento:** revisar clasificaciones y tensiones cuando cambien las orientaciones; no confundir su relación conceptual con eficacia demostrada.
