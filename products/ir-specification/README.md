# TDidacta IR Specification

**Estado:** superficie de producto nombrada explícitamente por el fundador (2026-10-16). **Especificación estructurada pendiente de completar antes del 31-10-2026**. No hay gramática, versión estable, validador ni contrato implementado.

## Responsabilidad propia

Definir **la representación intermedia de TDidacta**: significado y estructura de las intenciones pedagógicas, subdivisiones, situaciones válidas y relaciones entre intenciones, junto con sus restricciones, posibles referencias, condiciones de consistencia y reglas de evolución.

**Unidad preferida:** representación semántica por intención pedagógica, capaz de enlazarse con otras e indicar múltiples situaciones válidas. **Unidad semántica ≠ archivo físico**: un documento o una representación puede distribuirse entre soportes.

## Límites de producto

- **Docs Standard** representa documentalmente intenciones y situaciones para comprensión y revisión humanas.
- **Abstracción semántica** transforma esa documentación hacia IR; IR Specification define **la estructura de destino**, no ejecuta la transformación.
- **Proyección semántica** toma una o varias IR y produce elementos del dominio, como exploraciones o realizaciones asistidas por LLM; IR Specification **no** genera esos resultados.
- No asumir todavía equivalencia completa con la denominación histórica TDIR.
- La ubicación del producto se propone **por responsabilidad expresa de TDidacta**, no únicamente por imitar a VSlices.

## Continuidad con la estructura candidata previa

La [nota estructural de T04](../../structures/tdidacta-intermediate-representation.md) conserva los requisitos conceptuales actuales; esta entrada es la **superficie de producto elegida**, desde la cual se desarrollará su especificación antes del deadline. No duplicar esquemas sin necesidad.

## Referencia comparativa

El fundador menciona `vslices/intermediate-representation` como superficie de VSlices. Su ubicación y contenido actuales **no fueron verificados en esta revisión**; no importar una especificación ni atribuirle obligaciones sin consultar su fuente.
