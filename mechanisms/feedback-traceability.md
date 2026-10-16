# Trazabilidad de feedback — mecanismo candidato

**Estado:** candidate; delimitación T01 (2026-10-16). No exige una implementación o bitácora universal.

## Precisión T05: trazabilidad asistida o automatizada

Este mecanismo candidato es **distinto del mecanismo de [generación de feedback](feedback-generation.md)**. Su responsabilidad es reconstruir vínculos entre el feedback recibido, la interpretación de este, las decisiones tomadas y los cambios efectivamente producidos, cuando existan.

La trazabilidad podrá ser **parcial o completamente automatizada** como posibilidad de diseño. Esto **no** significa que la causalidad inferida sea incuestionable ni que una atribución automática implique decisión autorizada: los vínculos materiales deben poder revisarse y corregirse por responsables humanos. Su grado de automatización y garantías siguen sin especificarse.

## Estado de ejecución y aplazamiento

**La definición técnica avanzada y validación siguen diferidas hasta después de la entrega formal de PResolver del 31-10-2026 (decisión de T01, 2026-10-16). T05 reconoce ahora el mecanismo como candidato conceptualmente delimitado, sin adelantar su implementación.** Se conserva esta formulación candidata como antecedente, sin establecer un requisito de implementación, validación o formalización para la entrega. El alcance vigente de TDidacta está descrito en [Autoría pedagógica](../foundations/pedagogical-authorship.md). Privacidad y protección de datos no se aplazan por esta decisión.

## Alcance

Un feedback de **cualquier participante** —aprendiz, docente, autor, revisor u otro actor humano, o una señal inferencial explícitamente identificada— puede contribuir a revisar intenciones, realizaciones, restricciones y otras decisiones pedagógicas. No es exclusivo de quien aprende ni implica siempre un cambio.

## Relación candidata

`feedback identificado -> interpretación situada -> decisión de cambio -> objeto/versión afectado`

La relación es **posible y reconstruible**, no una secuencia obligatoria para todo comentario. El origen del feedback, su interpretación, el responsable de decidir y el objeto modificado pueden ser actores distintos.

## Casos y límites

- **Feedback atendido:** cuando la relación con un cambio es trazable, reconocer su contribución aunque el aporte original sea corto.
- **Feedback sin cambio:** puede conservarse cuando sea útil, pero no afirmar que originó una modificación.
- **Feedback parcialmente atendido:** explicar la parte considerada y el alcance de la decisión si ello es material.
- **Aportes concurrentes:** reconocer que varias observaciones pueden influir en una sola revisión sin atribuir causalidad exclusiva.
- **Feedback privado o sensible:** preservar evidencia mínima bajo controles de acceso; el crédito público no requiere difundir la frase original ni la identidad.
- **Origen inferencial:** indicar su naturaleza y límites de verificación; una propuesta generada no constituye decisión autorizada.

Las relaciones podrían ser directas, diferidas o múltiples. La trazabilidad debe ser proporcional al efecto y al contexto; no requiere almacenamiento textual exhaustivo, TDIR, grafo de datos ni instrumento de monitoreo de estudiantes.

## Preguntas pendientes

¿Cómo se acredita influencia sin sobreafirmar causalidad? ¿Cómo cuestionar o corregir vínculos atribuidos incorrectamente? ¿Cuándo destruir o anonimizar la evidencia subyacente? ¿Qué obligaciones cambian con menores de edad y contextos institucionales?

**Relacionados:** [Autoría pedagógica](../foundations/pedagogical-authorship.md) · [Gradiente](contribution-gradient.md) · [Transparencia](../transparency/README.md). Los temas de autorización y cambio de intención permanecen en T05/T06/T08/T12.
