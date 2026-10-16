# Fuentes, inferencias de IA e incertidumbre — propuesta T03

**Seguimiento:** T03 **cerrado** por decisión expresa del fundador (2026-10-16); reducción de carga y validación de implementación quedan como trabajo posterior. **Estado epistemológico:** delimitación y mecanismo conceptuales aceptados, sin validación automática ni esquema técnico universal.

## Problema

Una interpretación o realización puede presentar juntas afirmaciones de materiales consultados, elaboraciones de personas, inferencias de IA y aspectos que siguen abiertos. Si se confunden, la aparente autoridad de la fuente puede transferirse indebidamente a una conclusión inventada, a una hipótesis o a una decisión pedagógica. T03 busca que las **diferencias relevantes permanezcan discernibles para revisión humana**, sin imponer etiquetas o registros a cada frase.

T01 distingue origen, autoría y autorización. T02 reconoce dos vías complementarias: interpretación humana desde cero e interpretación asistida de fuentes. **La segunda no modifica la autoridad de la primera ni constituye un requisito para usar TDidacta.**

## Distinciones conceptuales (candidatas)

- **Afirmación respaldada por fuente:** una afirmación que puede contrastarse con material identificado. Estar contenida en una fuente no certifica su verdad; se debe preservar el alcance contextual de lo que expresa.
- **Interpretación humana:** comprensión, selección, organización o juicio aportado por la persona responsable. No es una cita de fuente por haber sido formulada al leerla.
- **Inferencia de IA:** síntesis, relación, hipótesis, extrapolación o propuesta generada mediante inferencia. Puede ser pertinente, pero no se atribuye automáticamente a la fuente ni se considera revisión humana.
- **Incertidumbre:** falta de certeza o evidencia suficiente acerca de una afirmación o de su pertinencia para el contexto. Puede afectar afirmaciones de cualquier origen, incluidas fuentes y decisiones humanas.
- **Ambigüedad:** admite más de una lectura plausible; no obliga a elegir silenciosamente una.
- **Omisión:** información o condición potencialmente relevante que no está presente o no se trató. No equivale por sí misma a prueba de ausencia.
- **Conflicto:** afirmaciones o interpretaciones aparentemente incompatibles que requieren delimitación, contraste o decisión informada. No equivale siempre a que una de ellas sea falsa.

Estas categorías **describen aspectos distintos**, no una taxonomía excluyente de frases, un sistema de puntuación de confianza ni una obligación de instrumentación exhaustiva. Una interpretación de IA puede apoyarse en una fuente y conservar incertidumbre; una afirmación humana puede carecer de respaldo.

## Criterio mínimo de legibilidad para el alcance actual

Cuando importe para comprender o autorizar el recurso, una persona responsable debe poder distinguir de manera proporcional:
1. **Qué viene de una fuente identificada**, incluyendo límites o atribuciones relevantes.
2. **Qué es interpretación o propuesta añadida**, especialmente lo generado por IA y no sostenido directamente por la fuente.
3. **Qué permanece pendiente de comprobar o decidir**, incluyendo incertidumbres, ambigüedades, omisiones y conflictos que afecten la intención o la seguridad del contexto pedagógico.

La señalización puede hacerse mediante lenguaje natural, referencias breves o una revisión manual; **no se fija aquí un formato ni se exige una marca por oración**. Tampoco se obliga a utilizar material fuente documental cuando una persona formula su interpretación desde cero. No inventar una fuente ficticia para completar una estructura.

## Ejemplo ilustrativo (no evidencia)

**Fuente consultada:** «El alumnado practicó fracciones con dibujos». **Interpretación propuesta por IA:** «El alumnado domina suma de fracciones». Lo segundo **no se desprende necesariamente** de lo primero: una actividad realizada no garantiza dominio. Debe quedar señalado como inferencia insuficientemente sustentada o cuestión para comprobar, no como hecho afirmado por la fuente.

Si una fuente no menciona un prerrequisito, no se concluye que el prerrequisito sea inexistente. Si dos fuentes difieren, se conserva el conflicto pertinente y se evita simular una resolución que aún no existe.

## Mecanismo propio y carga de aplicación

La [clasificación de evidencia](../mechanisms/evidence-classification.md) opera sobre afirmaciones, interpretaciones y aspectos inciertos tanto humanos como de IA. **Una implementación debe facilitar esta clasificación y reducir la carga de revisión del responsable**, no exigir etiquetar manualmente cada afirmación. No se presume eficacia ni ahorro sin contrastar esfuerzo real.

Su posible uso por el [mecanismo de interpretación asistida T02](../mechanisms/assisted-material-interpretation.md) tiene una [relación pendiente de revisión](../relationships/assisted-interpretation-evidence-classification.md).

## Fronteras con otros tópicos

- **T01 cerrado:** autoría, responsabilidades separadas, supervisión humana y declaración **manual** del modo de elaboración de recursos. Esa declaración global **no comprueba** la veracidad ni las fuentes de cada afirmación.
- **T02 cerrado:** interpretación asistida opcional y supervisada, complementaria a la interpretación desde cero. El **mecanismo detallado de cómo una IA interpreta materiales** permanece aplazado hasta una versión posterior a la publicación de PResolver.
- **T04–T06:** contextualización, revisión y autorización humana deciden qué utilizar y cuándo; T03 solo establece qué distinciones no deben borrarse.
- **T08–T09:** procedencia técnica, versiones y relaciones entre evidencias siguen pendientes; no imponer TDIR ni grafo obligatorio.
- **T15–T17:** fidelidad semántica, calidad pedagógica y aprendizaje requieren evaluaciones independientes.
- **T22/T25:** derechos, privacidad y condiciones de inferencia; no se autorizan transferencias de datos sensibles por exigir legibilidad.

## Casos límite que falta contrastar

- Una explicación fielmente atribuida a una fuente contiene un error original.
- La IA realiza una paráfrasis correcta junto a una extrapolación no respaldada.
- Una persona desarrolla contenido enteramente propio, sin citar fuentes documentales.
- Dos fuentes confiables expresan conclusiones discordantes o sus contextos no coinciden.
- Un contenido omite una limitación crítica y podría inducir una actividad insegura.
- No existe evidencia suficiente para resolver una ambigüedad antes de generar un borrador.

No hay aquí evaluación experimental de efectividad, precisión de extracción, cobertura curricular ni comportamiento de modelos.

## Procedencia y autoridad

[Autoría T01](pedagogical-authorship.md) · [Interpretación asistida T02](assisted-source-interpretation.md) · [Conceptos candidatos](concept-candidates.md) · [Gobernanza](../governance/README.md).

El [maestro editorial V6 en Research](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md) exige mantener distinguibles afirmaciones fuente e inferencias de IA y hacer visibles omisiones y ambigüedades. Se utiliza como antecedente, no como norma adoptada automáticamente. VSlices aporta, como analogía, la separación entre autoridad semántica y realización, **no** un esquema obligatorio de procedencia.

## Delimitación aceptada y límites posteriores

Aceptar **un requisito conceptual de legibilidad proporcional**: no atribuir inferencias a las fuentes, no ocultar incertidumbre relevante ni convertir ausencia de información en certeza; mantener revisión humana en el contexto que corresponda. Diferir cualquier clasificación automática de afirmaciones, puntajes, algoritmo, representación obligatoria o verificación técnica detallada, sin dar por resueltos T08 ni el mecanismo de IA de T02.
