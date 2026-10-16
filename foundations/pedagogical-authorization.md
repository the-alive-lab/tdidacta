# Autorización de elementos pedagógicos — T06

**Estado:** en curso, pendiente de decisión humana (2026-10-16). No cerrado ni validado.

## Pregunta principal

¿Qué hace que un elemento pedagógico esté autorizado para su uso posterior, sin confundir autorización con revisión, corrección, autoría o publicación?

## Responsabilidad candidata

**Autorizar** es una decisión humana mediante la cual la persona responsable acepta un elemento pedagógico para un uso y alcance reconocibles, estableciendo una referencia semántica estable para el trabajo posterior. Puede ser situada: autorizar para una situación no la aprueba automáticamente para todas. Revisar, crear, corregir y autorizar son responsabilidades diferenciadas aunque puedan recaer en una misma persona (T01 y T05).

## Decisiones del fundador sobre alcance MVP y congelamiento (2026-10-16)

**Quién autoriza:** por ahora una sola persona responsable. La autorización colaborativa, institucional o multinivel se difiere como pregunta abierta hasta después del 31-10-2026. Agentes LLM y otras personas pueden proponer, pero no adquieren autoridad por hacerlo.

**Qué se autoriza:** no solo realizaciones terminadas. La persona puede decir «apruebo este elemento para su uso en el resto del flujo» respecto de una intención pedagógica, planificación en borrador, trayectoria de unidades propuesta por humano o LLM, clase, actividad u otra realización. Se puede autorizar una parte sin autorizar automáticamente todos sus descendientes.

**Qué significa congelar:** antes de la autorización, el espacio admite modificaciones de planificación; después, el **alcance semántico aprobado queda estable** para que personas o agentes exploren sus posibilidades sin modificar silenciosamente sus premisas. Congelar no es bloquear la exploración ni afirmar inmutabilidad técnica de archivos.

**Cómo cambia:** hallazgos durante exploración, cambios curriculares, omisiones o necesidades nuevas pueden conducir a revisión y corrección (T05) del elemento autorizado y a reconsiderar su autorización. No reemplazar silenciosamente la versión o alcance aprobado con la propuesta corregida; el modelo técnico de versiones y propagación se estudia en T09/T12.

**Motivo:** el trabajo de planificación nueva necesita volatilidad y libertad de modificación; una planificación existente y aprobada puede requerir mayor estabilidad y adaptaciones controladas.

**Tensión pendiente T05→T06:** qué revisión resulta suficiente antes de autorizar un elemento, sin procedimiento universal ni examen exhaustivo obligatorio, manteniendo juicio humano material. Las especificaciones de estado, permisos y versionamiento siguen abiertas.

Estas decisiones **sustituyen la interpretación anterior** de autorización limitada a una realización final. Los casos colaborativos e institucionales no son requisito de MVP.

## Precisión: exploración previa a realizaciones y revisión por cambios documentales

**Decisión del fundador (2026-10-16):** una persona puede **autorizar y congelar una intención pedagógica antes de definir sus realizaciones**, precisamente para habilitar exploración y prueba-error de alternativas sin desestabilizar la intención aprobada. Una realización posterior no queda aprobada por extensión.

Cuando **cambia una intención pedagógica autorizada**, deben **revisarse y autorizarse de nuevo los elementos dependientes afectados por ese cambio**. Se requiere examinar todas las dependencias pertinentes; esto no implica aprobar automáticamente cambios ni alterar elementos que no dependan de la intención modificada. La delimitación y detección de dependencias necesita un mecanismo específico, aún no implementado.

**Recorrido de cambio:**
1. Un cambio externo afecta una necesidad pedagógica.
2. La documentación vigente deja de reflejar plenamente el contexto o las intenciones pertinentes.
3. Se actualiza la documentación para reflejar la necesidad y condiciones actuales.
4. La abstracción vuelve a **generar las IR derivadas** desde la documentación actualizada; esto es una operación instrumental prevista como automatizable, no el principal problema de revisión.
5. Se evalúa **si las exploraciones y realizaciones existentes siguen siendo válidas y coherentes** con el mundo semántico actualizado, identificando las dependencias pertinentes.
6. Si la respuesta existente es insuficiente para cubrir la necesidad, se proponen cambios en la documentación y se repite la abstracción, hasta alcanzar una respuesta adecuada sometida a revisión y autorización.

La diferencia y el riesgo de **drift semántico** generan costo humano. Se propone un **mecanismo candidato independiente de apoyo para detectar dependencias y riesgos de drift**, sin sustituir revisión ni autorización humanas. Su diseño y alcance deben decidirse sin presumir eficacia o seguridad de la detección automatizada.

**No se fijan aquí** formatos de diff, algoritmos, grados de transitividad, criterios técnicos ni procedimientos obligatorios de actualización; corresponden a especificaciones posteriores y al contraste con T08/T09/T12/T15.

## Dos declaraciones diferentes durante la actualización

**Declaración de impacto:** establecer si lo ya documentado, explorado y realizado **responde o no a la nueva necesidad**, indicando los efectos y riesgos de incoherencia. Un cambio documental pequeño puede dejar casi todas las realizaciones válidas, aunque exija comprobarlas; no se presume invalidación automática por diferencia de IR.

**Declaración de cambios:** cuando la respuesta existente no es suficiente, determinar y aplicar ajustes a la documentación, intenciones, situaciones o realizaciones necesarios para responder correctamente. Cambios importantes pueden exigir nuevas unidades, intenciones subordinadas o realizaciones; la nueva documentación produce IR regenerada y vuelve a evaluarse el impacto.

Las declaraciones constituyen **responsabilidades conceptuales diferenciadas**, no necesariamente dos formularios, artefactos físicos o etapas rígidas. Puede haber iteración entre impacto y cambios. La comparación material es sobre **vigencia y coherencia de exploraciones y realizaciones con la necesidad y semántica actual**, no una exigencia de aprobar manualmente cada regeneración de IR.

## Tensión abierta recibida de T05

La obligación conceptual de revisar y corregir no implica necesariamente revisión exhaustiva de cada documento, intención, situación, IR o realización ni un procedimiento universal. Sin embargo, tampoco permite una aprobación sin juicio suficiente. **Por decidir en T06:** criterios de suficiencia de revisión según riesgos, intención, situación y alcance; qué evidencias y controles son necesarios, sin imponer una burocracia universal ni atribuir autoridad a un LLM.

## Alternativas abiertas

- Autorización condicionada a flujo rígido de revisión: uniformidad posible, carga elevada en contextos pequeños.
- Autorización sin referencia a revisión suficiente: poco esfuerzo, pero posibilidad de aprobación nominal.
- Autorización situada tras revisión proporcional: equilibrio propuesto, **no adoptado todavía**.

## Fronteras

Autorizar no implica publicación (T07), conformidad técnica verificada (T15), calidad educativa validada (T16), resultados de aprendizaje (T17), derechos de uso ni consentimiento (T22). Los cambios relevantes de la realización o situación pueden afectar el alcance de la autorización (T09/T12). La coordinación institucional (T21) no es universal.

## Cuestiones para decisión humana

1. ¿Cómo abordar más adelante autorización colaborativa, institucional y multinivel, explícitamente fuera del MVP?
2. ¿Cómo identificar el objeto y alcance autorizado sin decidir anticipadamente la tecnología de versiones?
3. ¿Qué revisión es suficiente para autorizar sin imponer un procedimiento universal?
4. ¿Cómo reconsiderar autorización cuando cambia una condición material?

## Secuencia acordada

Cerrar T06 con aprobación humana, ejecutar retroalimentación de los otros 27 tópicos y **después** auditar Relationships y Lifecycle respecto de T01–T06. No anticipar la auditoría.

**Relacionados:** [T05](pedagogical-review-and-correction.md), [T04](human-pedagogical-contextualization.md), [T01](pedagogical-authorship.md).

## Alcance de revisión y reautorización según impacto

**Decisión del fundador:** revisar y reautorizar el punto afectado por un cambio de necesidad pedagógica y sus dependencias. Si el cambio afecta toda la planificación, se revisa y reautoriza toda ella; si afecta solo una unidad, se revisa y reautoriza esa unidad y sus dependencias, sin extender la revisión indiscriminadamente a otras unidades. Los cambios amplios suelen vincularse con intenciones de mayor alcance.

El procedimiento es manual en la actualidad y se aspira a automatizar su apoyo operativo, particularmente la detección de dependencias y riesgos de drift, sin transferir la autoridad humana al sistema. El criterio conceptual de suficiencia heredado de T05 queda precisado por el alcance del impacto; los algoritmos y garantías siguen pendientes.
