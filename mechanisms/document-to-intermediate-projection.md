# Abstracción documental a representación intermedia — mecanismo T04

**Estado:** responsabilidad y deadline definidos por el fundador (2026-10-16); diseño **pendiente de especificación antes del 31-10-2026**. IA como apoyo posible, sin delegación automática de autoridad.

## Responsabilidad

Abstraer la semántica documentada de **intenciones pedagógicas y sus situaciones**, producida mediante Docs Standard, a una **representación intermedia estructurada** que preserve necesidades, condiciones, restricciones y relaciones relevantes para las exploraciones y realizaciones.

Este mecanismo se distingue de:
- **Interpretación de material mediante IA (T02):** extraer/proponer conocimiento pedagógico a partir de fuentes educativas. Ese mecanismo queda para después de la publicación de PResolver.
- **Clasificación de evidencia (T03):** distinguir evidencia, inferencias e incertidumbres de origen humano o inferencial.
- **Contextualización humana (T04):** decidir qué intención y qué situaciones son pertinentes; la proyección no sustituye esas decisiones.

**La proyección no crea autoridad pedagógica nueva**. Una sugerencia inferencial añadida durante la proyección requiere quedar distinguible y estar sujeta a revisión humana. La exactitud semántica de la proyección no está validada.

## Unidad y resultado esperado

La preferencia expresada es **una representación por intención pedagógica**, permitiendo subdivisiones y enlaces entre representaciones. No se exige un archivo único ni se equipara unidad semántica a unidad física de almacenamiento.

Se preserva la distinción entre **intención** y **situación/es**; proyectar una situación nueva no debe alterar silenciosamente lo que la intención pretende enseñar. La relación con TDIR es **provisional**, no se presupone que su formato previo sea el contrato definitivo.

## Preguntas obligatorias de diseño antes del deadline

1. ¿Qué relaciones de Docs Standard se preservan y cuáles son derivaciones inferenciales?
2. ¿Cómo representar varias situaciones sin duplicar o fusionar indebidamente la intención?
3. ¿Cómo identificar ambigüedades, omisiones y contradicciones significativas y presentarlas al responsable sin añadir carga excesiva?
4. ¿Qué necesita revisar la persona antes de declarar utilizable la proyección?
5. ¿Qué pruebas comprueban preservación de significado y permiten comparar documentación e IR?
6. ¿Cómo evoluciona una proyección cuando cambia una intención o situación?

No se fija ahora una técnica de transformación, modelo, prompt, herramienta, pipeline, formato ni automatización.

## Relación con abstracción y proyección semánticas

El fundador separó dos fundamentos comunes de PResolver: [abstracción semántica](../foundations/semantic-abstraction.md) (**documentación → IR**, *encode*) y [proyección semántica](../foundations/semantic-projection.md) (**IR → resultados de dominio**, *decode*). **Este mecanismo corresponde solo a la abstracción documental de TDidacta**; el mecanismo de [proyección a dominio](intermediate-to-domain-projection.md) tiene otra responsabilidad. Su contrato técnico sigue pendiente de definir antes del 31-10-2026. La distribución conceptual entre Orientation, Foundations y Mechanisms, y las garantías generales, requieren investigación adicional.

**Relaciones:** [Documentación mediante Docs Standard](pedagogical-intent-documentation.md) · [IR Specification](../products/ir-specification/README.md) · [T04](../foundations/human-pedagogical-contextualization.md).
