# Checkpoint de Relationships y Lifecycle tras T01–T06

**Fecha:** 2026-10-16. **Estado:** revisión comparativa documentada; **no promoción** de un nuevo ciclo de vida ni adopción de relaciones técnicas. T06 cerrado conceptualmente y retroalimentación transversal registrada.

## Superficies contrastadas

- [Relationships](../relationships/README.md), [mapa de resolución](../relationships/pedagogical-resolution-relations.md) y [relación interpretación/evidencia](../relationships/assisted-interpretation-evidence-classification.md).
- [Lifecycle](../lifecycle/README.md) y [resolución recursiva](../lifecycle/recursive-pedagogical-resolution.md).
- Fundamentos de T01–T06, mecanismos de Docs Standard, abstracción/proyección, revisión, autorización, versionamiento y apoyo de detección de drift.

## Qué sigue funcionando

1. Necesidad **motiva** intención; intención **delimita** espacio; exploración **consulta** y realización **concreta** posibilidades.
2. Las relaciones no son pasos cronológicos obligatorios. Una necesidad puede motivar nuevas intenciones de diferentes escalas, sin imponer un árbol único.
3. Los resultados pueden cuestionar necesidades e intenciones. La recursividad es posible, no forzosa.
4. La relación candidata T02 → T03 sigue pendiente de validación, sin obligación técnica ni urgencia antes del deadline.

## Brechas observadas en Relationships

- **Intención ↔ situación/es válidas:** actualmente no está representada explícitamente en el mapa central; una misma intención puede operar en múltiples situaciones.
- **Intención/documentación ↔ IR:** falta distinguir documentación humana mediante Docs Standard, abstracción a IR, IR combinadas y proyección a exploraciones/realizaciones, sin presentar IR como fin pedagógico.
- **Autorización ↔ alcance semántico:** el mapa no expresa quién autoriza en el MVP (titular de cuenta), qué elementos pueden autorizarse (planificaciones, unidades, clases, actividades e intenciones) ni que autorizar una intención no autoriza sus realizaciones.
- **Revisión, impacto y cambios:** el mapa reconoce revisión genérica, pero no las relaciones entre cambio de necesidad, declaración de impacto, dependencias afectadas, revisión de cambios y reautorización.
- **Dependencias / versiones:** faltan relaciones para identificar el alcance del cambio y los elementos autorizados afectados; las garantías corresponden a mecanismos candidatos y T08/T09/T12, no a la ontología.

## Brechas observadas en Lifecycle

- **Maduración de respuesta:** no distingue formación voluble sin autorizaciones, formalización parcial/progresiva y adaptación focalizada de elementos autorizados. Son *situaciones posibles*, no tres etapas universales.
- **Exploración antes de realizaciones:** debe quedar explícito que autorizar una intención **puede preceder** a definir cualquier realización, para experimentar sin alterar premisas.
- **Cambio externo y sincronización:** el ciclo actual solo muestra hallazgos/observaciones que regresan a intención; falta cambio externo de necesidad → documentación desincronizada → actualización documental → IR regenerada → evaluación de vigencia.
- **Dos responsabilidades de cambio:** declaración de impacto identifica afectados y evalúa si respuesta existente aún satisface necesidad; declaración de cambios/revisión de cambios adapta lo afectado y puede originar nueva iteración.
- **Reautorización focalizada:** según alcance de necesidad modificada, puede ser una actividad, unidad o planificación completa, más sus dependencias pertinentes.
- **Costo de revisión:** actualmente manual; apoyo de detección de drift y versionamiento solo candidatos, sin afirmar automatización lograda.

## Tensiones y riesgos de modelo

1. **Evitar confundir autorización con congelamiento físico o finalización**: estabilidad de alcance semántico, no bloqueo de exploración ni aprobación de descendientes.
2. **Evitar que un diagrama dirigido se interprete como workflow universal**: las tres situaciones de madurez y el proceso de actualización pueden ser iterativos y darse en diversas escalas.
3. **Evitar vincular IR-diff = drift pedagógico**: lo que se juzga es vigencia/coherencia de exploraciones y realizaciones.
4. **Evitar una circularidad documental inconsciente**: el cambio del mundo motiva revisar documentación; declaración de impacto puede revelar insuficiencias que obliguen nuevas modificaciones, no una sola pasada lineal.
5. **No duplicar autoridad:** relaciones pertenecen a Relationships, coordinación a Lifecycle, operaciones a Mechanisms, significado a Foundations. La identidad y persistencia técnica de versiones siguen pendientes.

## Propuestas de cambio, no adoptadas por este checkpoint

- **Relationships:** extender el mapa existente en lugar de crear una ontología nueva. Incorporar vínculos intención–situación, documentación–IR, intención/realización–autorización, cambios–dependencias y revisión–reautorización; conservar en texto el carácter no secuencial.
- **Lifecycle:** extender el documento existente para reconocer construcción, formalización progresiva, exploración segura y adaptación mediante impacto/cambios como modalidades recursivas; revisar después el Mermaid y el experimento SVG, **sin imponer fases universales**.
- **Navegación:** enlazar este checkpoint desde ambos índices para que no se interprete el modelo anterior como cobertura completa. Cualquier promoción o redibujo queda sujeto a decisión posterior.

## No conclusiones

No se adopta lifecycle definitivo, gramática IR, sistema de roles, contrato de versiones, validador de drift, proceso institucional multinivel ni evaluación demostrada. La identificación de estas brechas no reabre por sí sola T01–T06.

[Bootstrap V6](tdidacta-v6-coverage-bootstrap.md) · [Autorización T06](../foundations/pedagogical-authorization.md).
