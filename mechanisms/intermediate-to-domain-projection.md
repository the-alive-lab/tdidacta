# Proyección semántica a resultados pedagógicos — mecanismo candidato T04

**Estado:** responsabilidad diferenciada el 2026-10-16. Definición técnica pendiente; no hay mecanismo validado ni interfaz implementada.

## Responsabilidad

Utilizar **una o más representaciones intermedias** de intenciones pedagógicas, sus situaciones válidas y relaciones pertinentes, para producir **exploraciones o realizaciones** específicas del dominio educativo, potencialmente asistidas por LLM.

Esta acción constituye la especialización operativa del fundamento de [proyección semántica](../foundations/semantic-projection.md): `IR → resultados del dominio`.

## Diferencia esencial

[Abstracción semántica](document-to-intermediate-projection.md) convierte documentación Docs Standard en IR. **Este mecanismo parte de IR ya existente**. La posible composición de varias IR, la selección de situaciones y la incorporación de semántica adicional son problemas de diseño aún abiertos.

Debe preservar la distinción entre propósito de una intención, situación de uso, variaciones permitidas e inferencias nuevas. Proyectar no significa demostrar conformidad ni autorizar una realización.

**Destino estructural:** [TDidacta IR Specification](../products/ir-specification/README.md). **Pendientes:** definición de entradas/salidas, composición, garantías, controles humanos y evaluación T15. No se afirma que las exploraciones o realizaciones generadas sean fieles o pedagógicamente efectivas.
