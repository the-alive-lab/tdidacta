# Contextualización pedagógica humana — propuesta T04

**Estado del tópico T04:** **cerrado conceptualmente** por decisión expresa del fundador (2026-10-16). **Entregables independientes comprometidos antes del 31-10-2026:** documentación mediante Docs Standard, mecanismo de abstracción semántica e IR Specification; no se consideran especificados ni implementados por este cierre.

## Problema y responsabilidad

Una necesidad, contenido o interpretación no se convierte automáticamente en una intención pedagógica adecuada para una situación. **Contextualizar** consiste en que quien asume la responsabilidad de enseñar **interprete las condiciones relevantes de una necesidad situada y decida cómo informan, delimitan o revisan la intención pedagógica**, para destinatarios que pueden ser distintos de esa persona.

Esto vale para una interpretación creada desde cero y para propuestas obtenidas mediante la vía complementaria de interpretación asistida. La contextualización humana no consiste únicamente en ajustar un texto al perfil de un alumno ni en aceptar recomendaciones de IA.

## Resultado de la contextualización y proyección

**Decisión del fundador:** la contextualización humana produce una **intención pedagógica y las subdivisiones pertinentes**. **Docs Standard** debe representar documentalmente la intención y **una o más situaciones válidas**, distinguiendo lo que se pretende enseñar de dónde, para quién y bajo qué condiciones se pretende enseñar. Esta separación debe informar tanto exploraciones como realizaciones.

Se identifican tres artefactos cuyo **diseño debe quedar definido antes del deadline 31-10-2026**, sin desarrollarlos completamente en esta revisión: [Documentación mediante Docs Standard](../mechanisms/pedagogical-intent-documentation.md), [Proyección documental asistible por IA](../mechanisms/document-to-intermediate-projection.md) y [Representación intermedia por intención](../structures/tdidacta-intermediate-representation.md). La representación puede distribuirse en varios archivos y conservar varias situaciones por intención.

**Abstracción semántica y proyección semántica:** el fundador las distingue como **dos fundamentos comunes a la familia PResolver**: [abstracción](semantic-abstraction.md) transforma documentación en IR (*encode*); [proyección](semantic-projection.md) transforma una o varias IR en elementos de dominio (*decode*). La orientación propuesta reconoce las posibilidades habilitadas por tecnologías actuales, especialmente LLM, sin convertirlos en dependencia universal. TDidacta sitúa la especificación de su IR en [tdidacta/ir-specification](../products/ir-specification/README.md).

## Elementos que pueden ser pertinentes

No constituyen un formulario obligatorio ni una lista exhaustiva:

- **Necesidad y destinatarios:** qué se intenta atender, a quiénes y para qué, considerando que quien identifica la necesidad no siempre es quien aprende.
- **Materias y relaciones:** conocimientos, prerrequisitos, conexiones, posibles errores de comprensión y límites disciplinares.
- **Tiempo y progresión:** oportunidades, orden, profundidad y restricciones temporales pertinentes; no implica trayectoria única.
- **Personas y condiciones:** conocimiento previo, circunstancias de grupos o individuos, autonomía y diversidad de apoyos, sin invadir la privacidad para completar un perfil.
- **Recursos y medios:** disponibilidad de material, tiempo, conectividad, medios y apoyos apropiados; accesibilidad detallada corresponde a T19.
- **Límites e incertidumbres:** qué no se pretende abordar, qué requiere verificación, qué puede variar y qué permanece fijo según la intención.

Las tres dimensiones **materias, tiempo, personas** ya aparecen en [Necesidades e intenciones](pedagogical-needs-and-intentions.md) como consideraciones candidatas; aquí se aplican sin convertirlas en ejes métricos o requisitos universales.

## Criterio de suficiencia proporcional (propuesta)

Una contextualización resulta **legible y revisable** cuando la persona responsable puede explicar, en el grado que el caso requiera:

1. qué necesidad concreta intenta atender y para qué destinatarios;
2. qué condiciones o restricciones **influyeron materialmente** en las decisiones pedagógicas;
3. qué decisiones incorpora, excluye o mantiene abiertas al formular o revisar la intención;
4. qué evidencia e incertidumbre relevante sigue sin resolverse, **sin atribuir como hecho confirmado una inferencia no verificada**.

La explicación puede ser breve, informal o quedar integrada en la propia intención. No exige completar formularios exhaustivos, registrar cada decisión, disponer de fuente documental formal ni usar IA para interpretar material. **Sin embargo, para el camino de documentación/proyección de T04 se deberán especificar Docs Standard y la representación intermedia antes del deadline**, de modo que esta obligación del sistema no se convierta automáticamente en carga técnica del responsable. Una necesidad pequeña puede ameritar una contextualización mínima; una situación compleja podría necesitar mayor explicitud.

## Límite de responsabilidades

- **T01 cerrado:** roles conceptualmente separados aunque una persona formule, supervise y autorice su material; destinatarios no tienen por qué coincidir con quien lo prepara.
- **T02 cerrado:** contextualizar puede partir de interpretación humana desde cero o de asistencia con fuentes. El mecanismo detallado de interpretación mediante IA sigue pospublicación de PResolver.
- **T03 cerrado:** usar [clasificación de evidencia](../mechanisms/evidence-classification.md) para no borrar origen o incertidumbre pertinente. No exige etiquetar cada oración ni promete ahorro de esfuerzo.
- **T05/T06 pendientes:** revisión/corrección y autorización no se sustituyen por contextualizar; la misma persona puede realizar esas tareas por separado en el alcance actual.
- **T08/T09/T12/T15/T19/T20/T22 pendientes:** procedencia, cambios de contexto, conformidad, accesibilidad, institución y privacidad conservan sus responsabilidades; T04 no las da por resueltas.

## Casos de contraste

- Un profesor particular prepara una actividad para un grupo con conocimientos previos diferentes: debe escoger qué relaciones o prerrequisitos son relevantes sin suponer que todos parten del mismo nivel.
- Un familiar prepara una explicación de informática para apoyar a otra persona: la necesidad y las condiciones materiales pueden ser informales, sin exigir currículo, institución o acreditación profesional.
- Una IA sugiere que un grupo domina un concepto por haberlo practicado: esa afirmación permanece como inferencia, y la persona puede optar por confirmar el punto antes de planificar.
- Un responsable decide **no** introducir una abstracción compleja todavía: la exclusión puede ser una decisión pedagógica válida, no un defecto de cobertura.

Estos son casos ilustrativos, no validación empírica.

## Contraste y procedencia

- [Orientación](../orientation/README.md): enseñanza y aprendizaje como perspectivas activas.
- [Necesidades e intenciones](pedagogical-needs-and-intentions.md): necesidad, intención y dimensiones contextuales.
- [Relaciones de resolución](../relationships/pedagogical-resolution-relations.md): necesidad motiva intención y responsable la formula/revisa, sin secuencia universal.
- [Maestro editorial V6](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md): contexto, objetivos, restricciones, prerrequisitos, exclusiones y variación permisible. Evidencia editorial, no prueba de eficacia.
- **VSlices:** adaptable separar definición/autoridad de realización; no importamos requisitos propios de arquitectura de software ni postulamos universalidad de PResolver.

## Continuidad tras el cierre conceptual — entregables antes del deadline

Reconocer que **la persona responsable contextualiza la necesidad y cualquier interpretación disponible al formular o revisar la intención pedagógica**, haciendo legibles únicamente las condiciones, decisiones e incertidumbres relevantes. Mantener el mecanismo proporcional y no imponer un procedimiento técnico universal. Revisar posteriormente la eficacia y el esfuerzo de aplicar esta responsabilidad, sin convertir esa validación en un prerrequisito conceptual de T04.

## Trazabilidad hacia las orientaciones vigentes

La orientación principal es **transversal** a este fundamento; las orientaciones complementarias se evalúan individualmente y no constituyen requisitos universales. Estas correspondencias son **explicaciones candidatas**, no pruebas de eficacia ni promoción conceptual.

| Orientación | Relación con este fundamento |
| --- | --- |
| [Orientación principal](../orientation/README.md) | Ajustar las intenciones a personas, necesidades y situaciones diversas. |
| [Continuidad semántica](../orientation/semantic-continuity.md) | Preservar distinción entre propósito y condiciones situadas. |
| [Aprovechamiento tecnológico](../orientation/technology-enabled-semantic-continuity.md) | Asistencia puede informar, no definir por sí sola la intención. |
| [Carga y capacidad](../orientation/human-effort-and-agency.md) | Facilitar decisiones situadas sin añadir carga documental excesiva. |

**Regla de mantenimiento:** agregar o modificar una orientación exige revisar esta tabla junto con las de **todos los fundamentos**; una fila de baja relevancia debe explicarlo, no inventar una dependencia.
