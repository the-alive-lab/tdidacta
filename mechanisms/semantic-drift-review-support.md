# Apoyo a detección de drift y alcance de revisión — mecanismo candidato T06

**Estado:** candidato conceptual (2026-10-16), sin implementación, validación ni plazo técnico confirmado. Diferente del apoyo general de T05, diferido.

## Responsabilidad

Reducir el esfuerzo humano necesario para **identificar diferencias semánticas y dependencias potencialmente afectadas** por cambios en necesidades, documentación de intenciones y situaciones, y representaciones intermedias reinterpretadas.

El mecanismo podría comparar resultados anteriores y posteriores de abstracción, localizar riesgos de drift y presentar qué elementos derivados requieren revisión. **No reemplaza el deber de revisar y autorizar nuevamente elementos dependientes afectados** ni confirma automáticamente si existe conformidad.

## Evento de interés

Cambio externo → necesidad cambia → documentación se desincroniza → documentación se actualiza → IR derivada se reinterpreta → se identifican diferencias y dependencias → persona responsable revisa y autoriza lo afectado.

La reinterpretación de IR pertenece al mecanismo de abstracción; este mecanismo se limita a **detectar y comunicar diferencias, dependencias y riesgos relevantes**. El versionamiento y la procedencia corresponden a T08/T09, los impactos a T12 y la conformidad a T15.

## Límites abiertos

No hay algoritmo de diferencias, grafo de dependencias, reglas de propagación, umbrales de riesgo ni garantía de detección completa aprobados. El objetivo es apoyar a la persona para detectar riesgos con menor esfuerzo, no trasladarle trabajo innecesario ni sustituir su autoridad. No se fija aún fecha de especificación o implementación.

[Autorización T06](../foundations/pedagogical-authorization.md) · [Abstracción documental](document-to-intermediate-projection.md) · [Orientación de carga y capacidad](../orientation/human-effort-and-agency.md).
