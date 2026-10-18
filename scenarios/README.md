# Escenarios de cobertura — TDidacta

**Estado:** registro de escenarios propuesto por el fundador y elaborado para contraste; **no es adopción de capacidades, compromisos de release, roles ni responsabilidades canónicas**. Fecha: 2026-10-18.

## Alcance y regla de lectura

Esta superficie pregunta **en qué circunstancias debe poder cumplir TDidacta sus orientaciones**, qué tensiones aparecen y si [F01–F10](../foundations/README.md) son suficientes. La definición del problema y aspiración se mantiene en [Orientation](../orientation/README.md); las soluciones fundamentales en Foundations y los significados en [Concepts](../concepts/README.md). No se duplican.

Un **escenario de cobertura** describe el contexto de quien puede ejercer responsabilidades; no es sinónimo del concepto [Escenario pedagógico](../concepts/application-circumstances.md) (contexto de aplicación de una intención; base/especializado según F10).

Los escenarios **no son excluyentes, ni definen identidades permanentes**. Una persona puede participar de varios y ejercer funciones diferentes. Las referencias a participantes a continuación son **actores observables**, no promoción de Roles ni asignación normativa de responsabilidades.

**Obligación de cobertura ≠ funcionalidad inmediata**: definir un escenario permite rastrear necesidades, límites y brechas. No prescribe prioridad, versión, implementación, interfaz o certificación de resultados. La adopción de compromisos concretos y alcance por release requiere planificación y decisión posterior.

## Fichas individuales de escenarios delimitados

Las fichas siguientes desarrollan **contexto, actores locales, circunstancias, necesidades de cobertura, trazabilidad y preguntas abiertas**, sin asignar Roles ni Responsibilities y sin introducir compromisos de implementación:

- [E01 — Enseñanza particular](e01-ensenanza-particular.md)
- [E02 — Aprendizaje autodidacta (independiente y colaborativo)](e02-aprendizaje-autodidacta.md)
- [E03 — Educación institucional](e03-educacion-institucional.md)
- [E04 — Educación en el hogar](e04-educacion-en-el-hogar.md)
- [E05 — Aprendizaje orientado a metas (transversal candidato)](e05-aprendizaje-orientado-a-metas.md)

Las secciones siguientes preservan el inventario original de cobertura y sus contrastes transversales, como **resumen de navegación**; para detalles del escenario utilizar la ficha individual y evitar crear definiciones paralelas. **E03 y E05 cuentan ahora con fichas propias**, conservando preguntas abiertas; E05 aún requiere decisión sobre su clasificación transversal definitiva.

## Resoluciones posteriores de las fichas E01/E02/E04 (2026-10-18)

Este índice conserva el inventario inicial para trazabilidad; **las fichas enlazadas prevalecen** donde las preguntas de cobertura hayan sido precisadas.

- **[E01](e01-ensenanza-particular.md):** el ajuste situado puede producir una **nueva versión autorizable**, sin mutar la intención ni la versión autorizada previa. La simplificación de esa experiencia es necesidad de cobertura con posible brecha fundacional, **sin adoptar F11 ni modificar F10**. Los permisos de acceso a recursos constituyen brecha explícita pendiente de fundamentación; «separación de procesos» deja de ser requisito independiente sin justificación.
- **[E02](e02-aprendizaje-autodidacta.md):** se reconoce como **necesidad de cobertura** la comunicación comunitaria y la posibilidad de prestar esta capacidad dentro o fuera de TDidacta. La gobernanza de [PostgreSQL](https://www.postgresql.org/about/governance/) es referente para discusión futura, no especificación adoptada. La comprobación de aprendizaje queda diferida.
- **[E04](e04-educacion-en-el-hogar.md):** la delimitación legal para menores y el trabajo de acreditación/progreso quedan pendientes de investigación y diseño por jurisdicción; no se garantiza cumplimiento multinacional.

## [E01 — Enseñanza particular y aprendizaje acompañado](e01-ensenanza-particular.md)

**Condiciones:** autonomía relativamente alta de quien enseña, relación pedagógica individual o de grupo pequeño y conocimiento progresivo de las necesidades; el aprendiz puede estudiar también en otros procesos educativos. La autonomía es relativa: no presume autoridad ilimitada, permiso para procesar información sensible o dominio absoluto sobre los materiales de otros.

**Cobertura pretendida:**
- Contextualizar y ajustar ayudas y circunstancias con el tiempo, sin modificar silenciosamente una intención autorizada ni tratar la especialización F10 como autorización nueva.
- Reconocer destinatarios diferentes y restricciones de acceso pertinentes a material no público. **El mecanismo** (permisos, grupos, invitaciones) se decidirá posteriormente.
- Separar la continuidad de los distintos procesos de aprendizaje sin obligar a una cuenta distinta por proceso.
- Permitir que el aprendiz consulte recursos disponibles autónomamente sin comunicación constante ni presencia continua del docente.
- Distinguir qué se comparte, qué requiere autorización y qué debe permanecer privado.

**Actores observables:** quien enseña, quien aprende y, cuando corresponda, adulto responsable de un menor. No son roles formalizados.

**Fundamentos a contrastar:** [F03](../foundations/human-pedagogical-contextualization.md), [F07](../foundations/pedagogical-authorization.md), [F09](../foundations/learner-autonomy.md), [F10](../foundations/pedagogical-adaptation.md), [F08](../foundations/pedagogical-authorship.md). **Pregunta abierta:** ¿control de acceso y continuidad multi-proceso resultan suficientemente justificados por estos fundamentos/O7/O9, o requieren explicitación fundacional sin mezclar reglas técnicas?

## [E02 — Aprendizaje autodidacta](e02-aprendizaje-autodidacta.md)

**Condiciones:** funciones de orientar enseñanza y vivir aprendizaje pueden coincidir en una persona; puede existir conocimiento inicial escaso, objetivos inciertos y ausencia de apoyo externo estable. No suponer que todo autodidacta carece de conocimientos o requiere IA.

**Cobertura pretendida:**
- Explorar y formular necesidades/intenciones sin exigir conocimientos expertos iniciales ni autoridad docente institucional.
- Ofrecer vías **directas** y **asistidas** para orientación sin sustituir decisiones humanas, imponer rutas únicas ni garantizar acierto de sugerencias.
- Facilitar la **comprobación por la propia persona** de qué enfoques le sirven mediante práctica, reflexión y contraste de comprensión; no confundir autopercepción, conformidad semántica y aprendizaje demostrado.
- Retomar experiencias, comparar alternativas y mantener continuidad sin dependencia permanente de un tercero.

**Actores observables:** persona que aprende y que en ocasiones orienta su propia enseñanza; apoyos externos eventuales.

**Fundamentos a contrastar:** [F01](../foundations/teaching-and-learning.md), [F02](../foundations/pedagogical-needs-and-intentions.md), [F05](../foundations/semantic-projection.md), [F06](../foundations/pedagogical-review-and-correction.md), [F08](../foundations/pedagogical-authorship.md), [F09](../foundations/learner-autonomy.md), O3/O6. **Pregunta abierta:** ¿cómo habilitar juicio sobre utilidad de estrategias personales sin que TDidacta declare diagnósticos, estilos de aprendizaje fijos o eficacia no verificada?

### Modalidades de autodidacta: independiente y acompañado

- **Autodidacta independiente (standalone):** la persona organiza y evalúa por sí misma sus experiencias, aunque pueda usar materiales o asistencia tecnológica. No presupone aislamiento obligatorio ni ausencia absoluta de orientación externa.
- **Autodidacta acompañado (colaborativo):** la persona aprende y orienta su propio proceso dentro de un esfuerzo compartido, semejante a una comunidad que desarrolla un proyecto de software libre: participantes aportan conocimientos, preguntas, correcciones, recursos o trabajo hacia un propósito compartido, sin que por ello exista un docente propietario del aprendizaje ni una relación obligatoria profesor–alumno. Puede haber coordinación y reglas de contribución sin que una persona sea dueña del conocimiento o ejerza automáticamente autoridad pedagógica sobre las demás. El apoyo entre pares no exige mentoría personal.

**Frontera con E01:** una **mentoría individualizada** o tutoría donde alguien asume orientación docente estable se parece más al escenario particular, incluso cuando el aprendiz conserva autonomía. No clasificarla automáticamente como autodidacta acompañado.

**Contraste:** examinar contribuciones, feedback, coordinación y continuidad compartidas, con posibles reglas de participación y mantenimiento pero sin presumir propiedad del aprendizaje ni una jerarquía pedagógica formal. La colaboración comunitaria es una modalidad de E02, no un escenario distinto. La analogía con proyectos de software libre describe la estructura participativa; no exige que todo grupo adopte una licencia, régimen de gobernanza o modelo de propiedad determinado.

## [E03 — Educación institucional](e03-educacion-institucional.md)

**Condiciones:** existe organización que coordina programas, docentes, aprendices, equipos de apoyo, autorizaciones y continuidad institucional. Pueden intervenir múltiples niveles de autoridad; no debe suponerse que todo establecimiento tiene la misma estructura ni que lo administrativo determina la intención pedagógica.

**Cobertura pretendida:**
- Distinguir quién **formula**, **revisa**, **autoriza**, **publica**, **acompaña** y **utiliza** elementos pedagógicos, con separación de funciones y posibilidad de acumulación.
- Reconocer necesidades curriculares o programáticas externas como **referencias**, no como autorización automática de intención.
- Preservar decisiones y versiones frente a cambios de docentes, grupos, calendarios y dependencias; autorizaciones previas permanecen asociadas a sus versiones.
- Admitir variaciones por grupo, modalidad, accesibilidad y recursos materiales.
- Reducir carga de coordinación y duplicación documental, sin asumir integración técnica universal.
- Delimitar privacidad y acceso a datos, especialmente de menores; interoperabilidad, propiedad/portabilidad de recursos y continuidad ante cambios de proveedor.
- Diferenciar evaluación de conformidad pedagógica, calidad, comprensión y exigencias administrativas externas.

**Actores observables:** aprendiz, docente, coordinador/a pedagógico/a, autoridad curricular o institucional, apoyo especializado, administración, familia/tutor según contexto. **No son roles adoptados** ni deben transformarse en una única jerarquía.

**Fundamentos a contrastar:** [F02](../foundations/pedagogical-needs-and-intentions.md), [F03](../foundations/human-pedagogical-contextualization.md), [F06](../foundations/pedagogical-review-and-correction.md), [F07](../foundations/pedagogical-authorization.md), [F08](../foundations/pedagogical-authorship.md), [F10](../foundations/pedagogical-adaptation.md), O7–O10. **Brechas por investigar:** autoridad distribuida, coordinación y continuidad organizacional, y diferencias entre permisos de plataforma, autoridad pedagógica y autoridad legal.

**Contexto externo (no definición canónica):** la OCDE describe ecosistemas de plataformas de gestión educativa, restricciones de interoperabilidad y privacidad; UNESCO trata liderazgo distribuido. Fuentes: [OECD Digital Education Outlook 2023](https://www.oecd.org/en/publications/2023/12/oecd-digital-education-outlook-2023_c827b81a.html), [OECD interoperabilidad](https://www.oecd.org/en/publications/2023/12/oecd-digital-education-outlook-2023_c827b81a/full-report/interoperability-unifying-and-maximising-data-reuse-within-digital-education-ecosystems_660f8da1.html) y [UNESCO liderazgo educativo](https://www.unesco.org/reports/gem-report/en/2024-leadership-education).

### Contraste E02/E03 — colaboración y coordinación de contribuciones

**Resultado de revisión conceptual del fundador (2026-10-18):** los escenarios comunitario-colaborativo e institucional comparten necesidades de contribución, feedback, continuidad y coordinación. Se diferencian sobre todo por **cómo se distribuyen las funciones y la autoridad**: en una comunidad puede no haber docente central ni autoridad pedagógica permanente; en una institución suele existir alguna estructura de responsables, sin que una sola persona deba ejecutar todas las funciones.

- **[F01 — Enseñanza y aprendizaje](../foundations/teaching-and-learning.md): cobertura conceptual considerada suficiente en este contraste.** Enseñar y aprender son perspectivas o responsabilidades distinguibles, no identidades fijas «profesor» y «alumno». Pueden distribuirse entre participantes o coincidir en una persona. La asignación situada queda para futuras superficies Responsibilities/Roles.
- **[F08 — Autoría pedagógica](../foundations/pedagogical-authorship.md): cobertura conceptual considerada suficiente.** Crear, editar, mediar y retroalimentar pueden generar aportes reconocibles tanto en comunidad como en institución. La atribución es proporcional y se establece por declaración responsable; **no se presume reparto automático o igualitario de autoría, ni que todo feedback conceda coautoría**. Autoría y autoridad de autorización siguen siendo diferentes.
- **[F09 — Autonomía del aprendiz](../foundations/learner-autonomy.md): cobertura conceptual considerada suficiente.** En comunidad, la persona puede explorar por sí misma y consultar a pares sin depender de un docente designado; en institución suele haber referentes a quienes consultar, pero su existencia no elimina exploración ni autonomía personal.

**Decisión de alcance:** estas tres suficiencias son **lecturas de cobertura del escenario**, no nuevas definiciones o cambios de estado de F01/F08/F09. Eventuales ajustes de redacción se estudiarán solo si se identifica ambigüedad concreta; no se reabren los fundamentos por esta comparación.

**Contraste aún abierto:** gobernanza de contribuciones, autoridad sobre intenciones y versiones, resolución de discrepancias, coordinación y continuidad cuando cambian participantes. Esas tensiones pueden requerir explicitación en escenarios y responsabilidades, no necesariamente nuevos fundamentos. No confundir autoridad editorial, pedagógica, legal y permisos técnicos.

## [E04 — Educación en el hogar (homeschooling)](e04-educacion-en-el-hogar.md)

**Condiciones:** aprendizaje organizado predominantemente en el entorno familiar, con acompañamiento variable. No es equivalente a aprendizaje autodidacta puro ni a educación particular; un adulto puede organizar y apoyar sin ser especialista, y un menor conserva participación y autonomía progresiva. Puede combinarse con tutorías, recursos de centros educativos y procesos de acreditación externos.

**Cobertura pretendida:**
- Diferenciar intereses y capacidad progresiva del aprendiz, acompañamiento pedagógico del adulto y representación/autoridad legal cuando corresponda.
- Permitir trabajo guiado y autónomo; aclarar dudas y sugerir rutas sin exigir dominio curricular experto a la familia ni hacer obligatoria la IA.
- Contextualizar materiales, ritmos y circunstancias familiares sin construir perfiles personales exhaustivos.
- Reconocer separadamente el progreso formativo de una posible **certificación externa**; TDidacta no certifica por sí mismo cursos.
- Admitir recursos accesibles fuera de línea y continuidad pese a cambios de tutor o proveedor.
- Identificar cuándo el niño o joven puede explorar y cuándo la autorización para determinados usos corresponde a una persona adulta u otra autoridad, con respeto a la privacidad.

**Actores observables:** aprendiz menor o adulto, familiar acompañante, tutor legal si corresponde, docente o especialista externo eventual, organismo examinador externo.

**Fundamentos a contrastar:** F01, F03, F07, F09, F10; O7/O9/O10. **Preguntas abiertas:** límites entre apoyo familiar y autoridad pedagógica; seguridad y privacidad de menores; particularidades de cada jurisdicción.

**Contexto externo chileno, no requisito universal:** la validación por exámenes libres corresponde al Ministerio de Educación y entidades examinadoras designadas; la inscripción de menores es responsabilidad de padre/madre/tutor legal y no puede hacerla una institución privada de homeschooling. Fuente oficial: [Ayuda Mineduc](https://www.ayudamineduc.cl/ficha/examenes-libres-menores-de-18-anos-11). UNESCO reconoce diversidad de condiciones del homeschooling: [actores no estatales](https://www.unesco.org/en/right-education/non-state-actors). No se adopta flujo legal, certificación ni alcance territorial universal.

## [E05 — Aprendizaje orientado a metas (escenario candidato transversal)](e05-aprendizaje-orientado-a-metas.md)

**Condiciones:** una meta de aprendizaje se define **externamente a TDidacta**, por la persona, su entorno u otra organización: preparar una certificación, adquirir capacidad en un tema, superar una brecha concreta, realizar una tarea o desarrollar una competencia. «Externa» significa que **TDidacta no establece la meta como autoridad originaria**, no que necesariamente la imponga una institución distinta del aprendiz.

**Cobertura pretendida:**
- Recibir o interpretar una meta externa y permitir que las personas formulen necesidades e intenciones pedagógicas relacionadas con ella, **sin confundir meta con intención pedagógica**.
- Facilitar exploración, recursos, práctica y revisión hacia la meta, sin apropiarse de su definición ni garantizar que se alcanzará.
- Diferenciar autoevaluación y evidencia de progreso de una **certificación o evaluación oficial externa**; la plataforma no concede por sí misma credenciales externas.
- Admitir modificaciones de la meta externa y reconsiderar las intenciones vinculadas sin alterar versiones anteriormente autorizadas.
- Mantener continuidad de múltiples metas, incluidas las simultáneas o compatibles con enseñanza particular, autodidacta, hogar e institución.

**Actores observables:** persona que persigue la meta, quien la fija (puede ser la misma persona), eventuales acompañantes y entidades externas que evalúan o certifican. No formaliza Roles ni permisos.

**Fundamentos a contrastar:** [F02](../foundations/pedagogical-needs-and-intentions.md), [F03](../foundations/human-pedagogical-contextualization.md), [F06](../foundations/pedagogical-review-and-correction.md), [F09](../foundations/learner-autonomy.md), O1/O3/O9. **Pregunta abierta:** ¿cómo vincular una meta externa a necesidad e intención sin convertir la meta en un concepto interno adicional ni desplazar su autoridad? **Clasificación candidata:** escenario transversal que puede cruzarse con E01–E04; no es sinónimo de capacitación laboral.

## Variantes transversales para evaluar, no escenarios independientes adoptados

1. **Acceso indirecto/desconectado**: aprendizaje con materiales impresos, de terceros o sin conexión sostenida. Es una condición **transversal** a E01–E05, no necesariamente escenario de alto nivel.
2. **Trayectoria híbrida**: una persona combina centro educativo, tutor particular, estudio autónomo y apoyos familiares, y puede perseguir metas externas. Verifica continuidad sin unificación forzada de permisos y contextos.

El aprendizaje comunitario/grupal no institucional queda como **modalidad acompañada de E02**, y la formación laboral es un **ejemplo posible de E05**, no un escenario universal distinto.

No introducir escenarios separados por cada tecnología, medio, condición médica, identidad, tamaño de grupo o tipo de archivo: esos son factores de contexto o variaciones a contrastar, salvo que aparezca una diferencia real de responsabilidades.

## Matriz de suficiencia preliminar

| Necesidad transversal | Cobertura conceptual observable | Pregunta de suficiencia, no hallazgo definitivo |
| --- | --- | --- |
| Participación activa y superposición de funciones | F01/F09 | ¿Hace falta formalizar Roles para escenarios donde enseñar y aprender coinciden? |
| Contextualización y adaptación | F03/F10 | ¿Cómo cambia la particularización cuando la impulsa docente, tutor familiar o aprendiz, sin alterar autoridad aprobada? |
| Autorización y acceso | F07/O4/O7 | ¿Cómo distinguir autoridad semántica de permisos de consulta, tutela y gobierno institucional? |
| Continuidad de procesos paralelos | O1/F02/F06/O10 | ¿Existe suficiente cobertura para compartimentación de procesos y cambios de responsables? |
| Agencia/autocomprobación | F05/F06/F09/O3 | ¿Qué justifica apoyo a aprender cómo evaluar estrategias propias sin prometer «estilos de aprendizaje» fijos? |
| Institución y hogar | F02/F07/F08/O7–O10 | ¿Qué responsabilidades o fundamentos faltan para coordinación multinivel y protección de menores? |
| Acceso asincrónico e indirecto | O9/O10/F09 | ¿Qué grado de disponibilidad independiente es necesario sin prometer plataforma 24/7? |
| Metas definidas fuera de TDidacta | F02/F03/F06/F09 | ¿Cómo preservar la autoridad externa sobre la meta, distinguirla de la intención pedagógica y reconocer evaluación/certificación ajena? |

## Proceso de promoción y planificación

- **Cobertura declarada:** escenario y necesidades registradas para análisis conceptual.
- **Brecha examinada:** contrastar Fundamentos y Conceptos, documentar suficiente / insuficiente / incierto por necesidad.
- **Compromiso adoptado:** solo tras decisión explícita del fundador.
- **Planificación de implementación:** decide qué parte, mediante qué producto/mecanismo y en qué momento, con criterios de verificación.
- **Evidencia:** experimentos, validaciones o uso observado, sin confundir intención con logro.

**No se crean F11, Roles, Responsibilities o requisitos de producto automáticamente.** Este registro precede a la definición de responsabilidades, a la reconstrucción T01–T28 y a la auditoría Foundations→Mechanisms (pospuesta).
