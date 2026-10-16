# Proyección semántica — fundamento transversal

**Estado (2026-10-16):** definición conceptual confirmada por el fundador para la familia PResolver; formalización general en el canon de PResolver y validación entre dominios pendientes.

## Definición

**Proyección semántica** es la acción de convertir **una o varias representaciones intermedias** en elementos o resultados definidos por el dominio de aplicación.

```text
IR individual o IR combinadas -- decode / proyección --> resultados del dominio
```

Esta definición **no incluye** convertir documentación en IR; esa responsabilidad corresponde al fundamento distinto de [abstracción semántica](semantic-abstraction.md). «Decode» no implica reversibilidad literal ni que las proyecciones sean copias de la documentación.

## Especialización pedagógica

En TDidacta, una o más IR especificadas mediante [IR Specification](../products/ir-specification/README.md) pueden servir para generar con apoyo de LLM **exploraciones y realizaciones pedagógicas** que consideren intención, subdivisiones, situaciones aplicables y relaciones con otras intenciones.

El [mecanismo de proyección a dominio](../mechanisms/intermediate-to-domain-projection.md) especificará cómo hacerlo; su operación técnica no está todavía definida. La generación no certifica conformidad, calidad pedagógica ni aprendizaje, ni autoriza automáticamente publicar.

## Arquitectura conceptual distinguida

- **Orientación:** [adaptación a capacidades tecnológicas contemporáneas](../orientation/technology-enabled-semantic-continuity.md), particularmente LLM, conservando responsabilidad y continuidad.
- **Fundamentos:** abstracción semántica (**documentación → IR**) y proyección semántica (**IR → resultados de dominio**).
- **Mecanismos:** operaciones especializadas, potencialmente asistidas por IA.
- **Estructura de dominio:** IR Specification define la IR de TDidacta.

## Cuestiones abiertas

Qué significa combinar varias representaciones sin perder contexto; qué transformaciones y ampliaciones son admisibles; qué garantías se exigen respecto de las intenciones y situaciones; cómo contrastar conformidad (T15); y cómo distribuir en PResolver la autoridad conceptual general. La pertenencia conceptual de ambas facultades a la familia está confirmada por el fundador; eso no demuestra equivalencia técnica entre dominios.

**Relacionados:** [T04](human-pedagogical-contextualization.md) · [Docs Standard](../mechanisms/pedagogical-intent-documentation.md) · [Abstracción T04](../mechanisms/document-to-intermediate-projection.md).
