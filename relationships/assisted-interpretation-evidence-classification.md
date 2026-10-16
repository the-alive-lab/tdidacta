# Interpretación asistida y clasificación de evidencia — relación candidata

**Estado:** **pendiente de revisión**. Propuesta expresada durante T03 (2026-10-16); no adoptada como contrato obligatorio ni validada empíricamente.

## Relación propuesta

El [mecanismo T02 de interpretación asistida de material](../mechanisms/assisted-material-interpretation.md) **utilizaría** el [mecanismo T03 de clasificación de evidencia](../mechanisms/evidence-classification.md), para que una interpretación con IA no mezcle silenciosamente afirmaciones respaldadas por una fuente con inferencias propias, ambigüedades, omisiones o conflictos.

**Dirección propuesta:** T02 `uses ->` T03. Esta es una **dependencia de responsabilidad candidata**, no una afirmación de dependencia técnica, orden obligatorio de ejecución, composición de clases ni propiedad semántica.

## Qué debe comprobarse

- Que clasificar evidencia sea una responsabilidad reutilizable también en interpretaciones humanas, en lugar de un subsistema exclusivo de la IA.
- Que la interpretación asistida pueda servirse de la clasificación sin **absorber su definición** ni convertirse en autoridad sobre la evidencia.
- Que la clasificación facilite revisar y corregir **sin sobrecargar a la persona responsable**.
- Que el modo de integración preserve la separación entre interpretación provisional, revisión y autorización.
- Que no se confunda con la declaración manual de modalidad de elaboración de recursos de T01.

## Decisión vigente y siguiente revisión

T02 está cerrado en su alcance conceptual. Su mecanismo detallado se estudiará **después de la publicación de PResolver**. El mecanismo T03 queda expresado ahora conceptualmente; **la relación entre ambos permanece pendiente de revisión**, sin impedir el trabajo vigente de T03.

La implementación concreta y la eventual promoción de esta relación requieren revisión explícita y trazabilidad.
