# Clasificación de evidencia y aportes interpretativos — mecanismo T03

**Estado:** mecanismo conceptual aceptado para T03; diseño técnico e implementación no validados. **Fecha:** 2026-10-16.

## Responsabilidad

Permitir distinguir, de manera **proporcional y comprensible**, el origen, naturaleza y límites de afirmaciones y aportes utilizados en experiencias pedagógicas, **sean humanos o de IA**. La clasificación no verifica por sí misma veracidad, calidad o autorización, ni reemplaza el juicio de la persona responsable.

Su propósito **no** es puntuar la contribución de cada actor ni clasificar globalmente cómo se elaboró un recurso; esto último tiene un mecanismo de **declaración manual diferente** en [Transparencia](../transparency/README.md).

## Aspectos diferenciables

Conforme a [Foundations T03](../foundations/source-inference-uncertainty.md):

- **Afirmación respaldada por fuente:** contrastable con material identificado, sin presumir que la fuente es verdadera.
- **Interpretación humana:** selección, explicación u organización realizada por una persona.
- **Inferencia de IA:** síntesis, hipótesis, extrapolación o propuesta generada por un sistema inferencial.
- **Incertidumbre:** respaldo o certeza insuficiente, independientemente del origen.
- **Ambigüedad:** múltiples lecturas plausibles.
- **Omisión:** contenido relevante no abordado; no demuestra inexistencia.
- **Conflicto:** afirmaciones aparentemente incompatibles, con contextos o respaldos por contrastar.

No son etiquetas mutuamente excluyentes ni un esquema técnico obligatorio. Una afirmación puede tener procedencia y a la vez incertidumbre, o ser una interpretación humana contrastable con varias fuentes.

## Funcionamiento conceptual

1. Identificar las afirmaciones o decisiones **materialmente relevantes** para comprender, revisar o autorizar un recurso.
2. Distinguir su **origen o carácter interpretativo**, evitando adjudicar a la fuente inferencias propias o de IA.
3. Hacer explícitas incertidumbres, ambigüedades, omisiones y conflictos **cuando afecten de forma significativa** la interpretación o su utilización.
4. Facilitar que la persona responsable confirme, corrija, descarte o mantenga abiertos los elementos pertinentes.
5. Conservar una presentación o registro **proporcional al contexto**; no crear fuentes ficticias, falsos grados de certeza ni un formulario exhaustivo.

La clasificación puede ser realizada o asistida por personas o herramientas; **ninguna propuesta inferencial se considera comprobada automáticamente**. Los controles de autorización siguen en T05/T06 y la procedencia detallada corresponde a T08/T09.

## Restricción esencial: carga sobre la persona responsable

Una clasificación exhaustiva puede resultar demasiado costosa y perjudicar la utilidad del sistema. **Cualquier implementación de este mecanismo debe simplificar la carga del responsable**, facilitando identificar y clasificar evidencia relevante, revisar propuestas y corregir errores; no limitarse a trasladar el esfuerzo de etiquetar manualmente cada afirmación.

Posibles alternativas para estudio, **no decisiones técnicas adoptadas**: sugerencias de clasificación para aceptación o corrección humana; agrupación de elementos semejantes; foco en casos relevantes o inciertos; reutilización de procedencia conocida; presentación progresiva del detalle.

La simplificación debe poder **contrastarse con el esfuerzo real**, incluidos revisión, corrección y mantenimiento. No presumir ahorro por usar IA ni imponer confirmaciones masivas que oculten errores.

## Fronteras y continuidad

- [T01](../foundations/pedagogical-authorship.md): diferenciar autoría, autoridad y contribuciones; **no** desarrollar aquí el gradiente multidimensional aplazado.
- [T02](assisted-material-interpretation.md): mecanismo pendiente de desarrollo **posterior a la publicación de PResolver**. Se propone que utilice esta clasificación, pero la dependencia y el modo de integración **requieren revisión** en [Relationships](../relationships/assisted-interpretation-evidence-classification.md).
- T03 establece distinciones y una responsabilidad de facilitación; **no** promete algoritmo fiable de clasificación, umbrales, métrica ni interfaz implementada.
- T08/T09: procedencia y versionamiento detallados.
- T15/T16: conformidad y calidad son evaluaciones separadas.
- T22: derechos y protección de datos no quedan diferidos por el mecanismo.

**Procedencia:** [T03 — fuentes, inferencias e incertidumbre](../foundations/source-inference-uncertainty.md), precisiones expresas del fundador del 2026-10-16 y [V6 editorial](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md). No existe validación empírica de eficacia ni reducción de carga.
