# E03 — Educación institucional

**Estado:** ficha de cobertura documentada (2026-10-18), con alcance y preguntas pendientes. Los actores son locales a este escenario, no Roles adoptados ni asignaciones de Responsibilities. No se presupone implementación, eficacia ni obligaciones legales universales. [Índice](README.md).

## Contexto

Una organización educativa coordina experiencias en que pueden intervenir personas y equipos distintos, con reglas propias de participación, decisiones, continuidad y restricciones externas. Incluye establecimientos, programas, centros formativos u organizaciones equivalentes; su estructura varía según contexto. **La institución no es automáticamente propietaria del conocimiento ni autoridad absoluta sobre cada intención.**

## Actores observables

- **Aprendiz o participante educativo:** persona que aprende y puede mantener autonomía aun dentro de un programa organizado.
- **Docente o facilitador:** persona que participa en enseñar, acompañar o construir experiencias, sin asumir por ello todas las decisiones.
- **Coordinación pedagógica:** participante o unidad que articula actividades, contribuciones y continuidad entre equipos.
- **Autoridad institucional o curricular eventual:** persona, órgano o entidad que establece límites o toma decisiones en su propio alcance; su presencia no determina automáticamente quién autoriza pedagógicamente cada elemento.
- **Administración y apoyo especializado eventuales:** actores que sostienen condiciones operativas o acompañan necesidades específicas.
- **Familia o representante legal eventual:** actor externo o relacionado con el aprendiz, según edad y jurisdicción.
- **Organismo evaluador, regulador o acreditador externo eventual:** puede definir exigencias ajenas a TDidacta, sin que el sistema otorgue automáticamente acreditaciones.

Los actores son **observaciones del contexto** y pueden superponerse. Ninguno constituye un Role universal de TDidacta.

## Circunstancias diferenciadoras

- Participación de múltiples personas y equipos, con cambios de integrantes y periodos educativos.
- Autoridad pedagógica, coordinación, gobernanza institucional, representación legal y permisos técnicos **potencialmente distintos**.
- Documentos curriculares, programas, evaluaciones y metas externas que no equivalen automáticamente a una intención pedagógica autorizada.
- Recursos públicos o restringidos; condiciones de privacidad, accesibilidad y eventual tratamiento de datos de menores.
- Necesidad de preservar continuidad cuando cambian docentes, equipos, proveedores o versiones de recursos.

## Necesidades de cobertura

1. Admitir **modelos configurables de autorización y funciones situadas**, sin jerarquía universal. Pueden ofrecerse plantillas predeterminadas **editables después de generadas**; no se adopta todavía un esquema de Roles o permisos.
2. Facilitar coordinación, comunicación, deliberación y feedback **en el ámbito educativo**, mediante capacidades propias o externalizadas. La gestión institucional general queda fuera del alcance; evaluar junto con E02 si existen necesidades fundacionales compartidas de apoyo a comunidades educativas.
3. Reconocer aportes y autorías proporcionales a contribuciones, sin equipararlas a autoridad para aprobar.
4. Preservar trazabilidad de intenciones, versiones autorizadas y recursos ante reemplazos de participantes o cambios de condiciones. Una nueva versión no muta autorizaciones históricas.
5. Relacionar necesidades institucionales y referencias curriculares externas con intenciones pedagógicas, sin atribuir a TDidacta la autoridad de origen de esas exigencias.
6. Permitir variaciones por grupos, destinatarios y circunstancias, con revisión y autorización pertinente cuando se preparen versiones nuevas.
7. Distinguir acceso a materiales y privacidad de la autorización pedagógica de su significado.
8. Considerar uso directo, indirecto y continuidad de recursos sin presumir integración tecnológica ni conectividad universal.

## Contraste con Foundations / Orientation

- [F01](../foundations/teaching-and-learning.md), [F08](../foundations/pedagogical-authorship.md) y [F09](../foundations/learner-autonomy.md): cobertura conceptual considerada suficiente en comparación E02/E03 para perspectivas de enseñanza/aprendizaje, autoría y autonomía.
- [F02](../foundations/pedagogical-needs-and-intentions.md) y [F03](../foundations/human-pedagogical-contextualization.md): comprensión de necesidades y contextualización; metas curriculares no se confunden con intención.
- [F06](../foundations/pedagogical-review-and-correction.md) y [F07](../foundations/pedagogical-authorization.md): revisión, versiones y autorización situada; **no establecen por sí solos cómo se gobierna una institución**.
- [F10](../foundations/pedagogical-adaptation.md): especialización de circunstancias, no un modelo universal de estructura educativa.
- [O7](../orientation/privacy-by-design-and-data-minimization.md), [O8](../orientation/external-personal-identity-recognition.md), [O9](../orientation/contextual-access-and-educational-reach.md) y [O10](../orientation/public-resource-continuity.md): restricciones transversales.

## Cuestiones abiertas / límites

- **Autoridad distribuida — orientación de cobertura:** permitir configuración contextual de autorizaciones y funciones, con plantillas iniciales modificables. Cómo se determinan reglas y límites se examinará al diseñar Responsibilities/Roles; no hay jerarquía universal adoptada.
- **Coordinación — alcance acotado:** TDidacta cubre la dimensión educativa, no la administración institucional general. La colaboración puede aprovechar capacidades propias o externas; estudiar con E02 potenciales necesidades comunes de gestión comunitaria.
- **Identidad personal:** conforme a [O8](../orientation/external-personal-identity-recognition.md), su reconocimiento corresponde a autoridades externas pertinentes. TDidacta sí puede gestionar cuentas, autenticación, participaciones y accesos, sin confundirlos con identidad personal ni autoridad pedagógica.
- **Acceso:** los permisos de lectura/participación no equivalen a autorización pedagógica. Brecha candidata compartida con E01.
- **Protección de menores y obligaciones por jurisdicción:** estudio jurídico previo a cada capacidad afectada; no asumir que el repositorio define cumplimiento.
- **Criterios de evaluación externa:** institución, regulador o acreditador pueden requerir evidencia; TDidacta no certifica cumplimiento por sí mismo.
- No se adoptan organigramas, LMS, SIS, SSO, roles administrativos, contratos, integraciones ni calendario de implementación. Las plantillas configurables son orientación de cobertura, no diseño de mecanismos aprobado.

## Contraste con E02 colaborativo

En ambos contextos existen contribuciones múltiples, discrepancias, comunicación, coordinación y continuidad. **La diferencia está en la configuración contextual de autoridad**, no en que uno pueda aprender en comunidad y el otro no. [E02](e02-aprendizaje-autodidacta.md) contempla colaboración sin autoridad docente central necesaria; E03 puede tener autoridades formalmente designadas, pero no impone un reparto universal. La referencia de [gobernanza de PostgreSQL](https://www.postgresql.org/about/governance/) queda como analogía para estudiar estructuras comunitarias, no como regulación que TDidacta deba adoptar.

## Seguimiento posterior de cobertura — E03-N6 (2026-10-20)

**E03-N6 cerrado en contraste funcional de Responsibilities**, no como definición técnica ni formalización de fundamentos. La variación por grupos y circunstancias se atiende mediante T-R03 (uso y especialización de posibilidades ya previstas), T-R01a/b (formulación y evolución pedagógica), T-R02 (examen/autorización pedagógica directa donde corresponda), T-R05a/b (accesos / configuración operativa) y T-R06 cuando haya interdependencias. No se justifica una Responsibility nueva.

**Condiciones de evolución propuestas:** autorización derivada situada bajo condiciones de la intención directamente autorizada; herencia acumulativa en derivaciones sucesivas; combinación solo bajo restricciones compatibles; variante reconciliada para otro origen sin confundir reconciliación y consolidación; validez histórica distinta de aplicabilidad bajo circunstancias actuales. La formalización de estas reglas queda [reservada como cuestión semántica](../notes/2026-10-20-e03-n6-pedagogical-intent-authorization-open-questions.md), especialmente por tensión con F07 vigente. [Registro de Responsibilities](../notes/2026-10-20-e02-e03-responsibilities-reconciliation.md).

**Control de coherencia:** N1 (autoridad contextual vs acceso), N2 (coordinación), N3 (atribución), N4 (continuidad), N5 (referencias externas) y N6 no presentan conflicto funcional detectado en este contraste. F07 **no está formalmente reconciliado** con la autorización derivada; no presumir su adopción. N7 y N8 siguen pendientes, por tanto E03 completo **no está cerrado**. Los ejemplos «planificación/unidad/clase/actividad» no constituyen una jerarquía universal.
