# Versionamiento de elementos pedagógicos — mecanismo candidato T06

**Estado:** candidato conceptual (2026-10-16); sin esquema técnico, implementación ni validación. Su especificación de detalle se coordinará con T09 y T12.

## Responsabilidad

Permitir reconocer y conservar la evolución de **planificaciones, unidades, clases, actividades y cualquier elemento representable mediante intenciones pedagógicas**. Debe distinguir el elemento y alcance autorizado, su estado anterior, cambios posteriores y relaciones entre elementos dependientes.

Una autorización se refiere a una **versión identificable y consolidada, inmutable en su contenido y significado autorizado**. Revisar o corregir no la muta: produce una nueva versión candidata, que puede cambiar incluso su nombre y contenidos, manteniendo trazabilidad respecto de la anterior. La nueva versión requiere su propia autorización antes del uso que la exija. Autorizar una versión no autoriza derivados automáticamente.

## Relación con la actualización

- **Declaración de impacto:** interpretar el cambio de necesidad e identificar los elementos dependientes cuya vigencia debe evaluarse.
- **Declaración de cambios o revisión de cambios:** adecuar los elementos afectados y dejar reconocible su evolución.
- **Revisión y nueva autorización:** la persona responsable decide qué nueva versión queda lista para uso posterior; la herramienta puede ayudar sin sustituir esa decisión.
- **Reemplazo de publicación:** si una versión consolidada está publicada, cambiar la versión vigente significa reemplazar su referencia pública por otra autorizada, no sobrescribir la versión histórica. La política de disponibilidad de versiones anteriores queda por definir.

## Pendientes técnicos

Identidad de versiones, granularidad, comparación, historial, reversión, relaciones entre versiones y dependencias, sincronización documental e IR regenerada, así como costo humano. Ninguno queda resuelto por esta nota.

**Relaciones:** [Autorización T06](../foundations/pedagogical-authorization.md) · [Apoyo a detección de impacto y drift](semantic-drift-review-support.md) · [Revisión T05](pedagogical-review-and-correction.md).
