# Interpretación asistida de material educativo — mecanismo pendiente T02

**Estado:** mecanismo identificado, **pendiente de definición para una versión posterior a la publicación de PResolver**. No implementado ni validado. **Registro:** 2026-10-16.

## Responsabilidad reconocida

Como complemento del camino normal de interpretación elaborada desde cero por una persona, TDidacta puede utilizar IA para **interpretar material educativo de uso permitido** y producir propuestas que la persona responsable examine, contextualice, corrija y eventualmente incorpore a su intención pedagógica.

La [delimitación conceptual aprobada de T02](../foundations/assisted-source-interpretation.md) constituye la autoridad sobre su alcance. Este archivo **reserva el mecanismo para trabajo posterior**, sin afirmar que su procedimiento, arquitectura, formato o calidad ya estén definidos.

## Relación pendiente de revisión con T03

Se propone que este mecanismo **utilice el [mecanismo de clasificación de evidencia T03](evidence-classification.md)** para mantener distinguibles fuentes, interpretaciones, inferencias e incertidumbres durante su uso. La necesidad y el modo de integración, así como las implicaciones de la carga de revisión humana, **siguen pendientes de revisión** en [Relationships](../relationships/assisted-interpretation-evidence-classification.md).

No confundir esta clasificación de evidencia con la [declaración manual global](../transparency/README.md) sobre elaboración humana/asistida del recurso.

## Preguntas abiertas para después de la publicación

- ¿Qué entradas, formatos y derechos de uso se admiten?
- ¿Cómo localizar y distinguir afirmaciones de fuente frente a interpretaciones o hipótesis propuestas?
- ¿Qué mecanismo de interacción permite revisar y corregir sin imponer carga excesiva?
- ¿Cómo integrar el mecanismo T03 sin afirmar que una sugerencia automática está verificada?
- ¿Qué procedencia mínima conservar, según T08 y T09?
- ¿Cómo contrastar fidelidad, omisiones, errores y esfuerzo real de revisión?

**No definidos:** pipeline, prompts, modelo, componentes, TDIR obligatorio, métricas, validación y automatización. No hay resultados de eficacia del mecanismo.

## Límites

Este trabajo diferido **no reabre T02**, ya cerrado en su responsabilidad conceptual, ni obliga a demorar la interpretación humana desde cero. Tampoco aplaza automáticamente las salvaguardas de derechos, consentimiento o protección de datos (T22).
