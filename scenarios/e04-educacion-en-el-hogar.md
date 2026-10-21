# E04 — Educación en el hogar (homeschooling)

**Estado:** ficha de escenario de cobertura formalizada para análisis, **no aprobación de capacidades ni planificación de implementación** (2026-10-18). Los actores son **locales al escenario**, no Roles ni asignaciones normativas de Responsibilities. Las necesidades describen cobertura pretendida, no funcionalidades comprometidas. Véase [índice de escenarios](README.md).

## Contexto

La experiencia educativa se organiza principalmente en un entorno familiar o doméstico y puede combinar exploración autónoma, apoyo familiar, tutorías externas y exigencias de validación de una jurisdicción. No debe presumirse que la persona que acompaña es profesional docente ni que toda educación en el hogar es autodidacta. Es un escenario distinto de E01 y E02 que puede intersectarlos.

## Actores observables

- **Aprendiz:** niño, adolescente o adulto que participa en la experiencia educativa; su autonomía y condiciones cambian según contexto.
- **Familiar o acompañante de aprendizaje:** persona que ayuda a organizar, explorar y sostener actividades; no adquiere por esa descripción autoridad pedagógica o legal universal.
- **Representante legal eventual:** adulto cuya autoridad legal puede ser relevante para decisiones específicas, según jurisdicción; puede coincidir con acompañante.
- **Docente o especialista externo eventual:** participa mediante tutorías, asesoría o apoyo concreto, sin absorber automáticamente la organización familiar.
- **Entidad externa de evaluación/acreditación eventual:** puede examinar o certificar fuera de TDidacta; no es actor necesario de toda experiencia.

## Circunstancias diferenciadoras

- Combinación variable de apoyo humano, autonomía progresiva y conocimiento experto disponible.
- Edad, acceso, recursos y dinámicas familiares diversos, sin imponer un modelo familiar único.
- Posibles exigencias curriculares o de acreditación **externas** a TDidacta, que dependen de la jurisdicción.
- Uso doméstico, asincrónico o desconectado de recursos y continuidad si cambia quien acompaña.

## Necesidades de cobertura

1. Distinguir intereses y decisiones progresivas del aprendiz de acompañamiento educativo y representación legal pertinente.
2. Permitir contextualizar intenciones y circunstancias sin requerir formación docente profesional a los familiares ni hacer obligatoria la IA.
3. Proveer vías directas o asistidas para orientación, exploración y revisión respetando juicio humano situado.
4. Reconocer recursos materiales, tiempo, barreras de acceso y privacidad, particularmente cuando intervienen menores.
5. Distinguir prácticas formativas y evidencia de progreso de **acreditación o certificación externa**: TDidacta no atribuye validez oficial a sus propios resultados.
6. Favorecer continuidad de la experiencia ante cambios de acompañante, material o proveedor.

## Contraste con fundamentos y orientaciones

- [F01](../foundations/teaching-and-learning.md): perspectivas de enseñanza/aprendizaje no necesariamente separadas.
- [F03](../foundations/human-pedagogical-contextualization.md): circunstancias situadas y documentación proporcional.
- [F07](../foundations/pedagogical-authorization.md): autoridad pedagógica contextual, distinta de representación legal y acreditación externa.
- [F09](../foundations/learner-autonomy.md): autonomía compatible con acompañamiento.
- [F10](../foundations/pedagogical-adaptation.md): especialización de circunstancias del aprendiz.
- [O7](../orientation/privacy-by-design-and-data-minimization.md), [O9](../orientation/contextual-access-and-educational-reach.md), [O10](../orientation/public-resource-continuity.md): privacidad, acceso y continuidad de recursos.

## Límites y cuestiones abiertas

- **Complejidad regulatoria reconocida:** la frontera entre decisiones pedagógicas familiares, representación legal, privacidad y obligaciones de protección de menores varía por país y contexto. Se considera una de las áreas de implementación más delicadas; **no adoptar flujos legales universales ni asumir cumplimiento multinacional**. Resolver mediante análisis jurídico y de diseño por jurisdicción antes de activar capacidades afectadas.
- ¿Cómo apoyar necesidades educativas y progresos sin transformarlos en certificados oficiales ni garantizar calidad o cumplimiento curricular? **Pendiente para trabajo posterior**; distinguir evidencia formativa de títulos y certificados oficiales sin prometer que TDidacta los otorgará.
- Validación chilena mediante exámenes libres se cita solo como **ejemplo contextual**, no como requisito universal: [Ayuda Mineduc](https://www.ayudamineduc.cl/ficha/examenes-libres-menores-de-18-anos-11).
- No se prescriben interfaces familiares, perfiles infantiles, control parental, currículos, verificaciones, ni calendario de implementación.

## Contraste E04-N1 — reconciliación funcional (2026-10-21)

**Resultado acordado:** N1 queda reconciliada **solo en la frontera conceptual entre necesidades y Responsibilities**. Las labores existentes permiten distinguir autonomía del aprendiz, acompañamiento y representación; no se justifica por N1 una Responsibility adicional.

- **T-R03:** aprendizaje y autonomía progresiva de la persona, sin exigir dirección total de un tercero.
- **T-R01a/b:** preparación, contextualización y adaptación cuando esa sea la finalidad de la ayuda; acompañar no confiere autoridad universal.
- **T-R04:** representación y resguardo propios de un apoderado o figura equivalente **cuando corresponda**, con límites aplicables; no equivale a cuidado familiar genérico ni exige condición jurídica universal.
- **T-R02:** protección y autorización pedagógica de elementos e intenciones pertinentes, distintas de acompañamiento y representación.

Una persona puede ejercer varias funciones, o estas distribuirse entre participantes; los actores E04 no se convierten por ello en Roles canónicos. No se presume que el adulto tome todas las decisiones educativas ni que cada decisión del aprendiz requiera aprobación.

**Reservas abiertas:** conflictos de decisiones, límites de facultades, protección y requisitos por edad, jurisdicción y contexto. El contraste funcional **no demuestra cumplimiento jurídico ni implementación**; no adopta permisos ni flujos universales. Continuar con E04-N2 conservando estos límites.

**Fuentes:** [T-R03](../responsibilities/tr-03-aprendizaje-retroalimentacion.md), [T-R01a](../responsibilities/tr-01a-planificacion-contextualizacion-pedagogica.md), [T-R01b](../responsibilities/tr-01b-contextualizacion-adaptacion-pedagogica.md), [T-R04](../responsibilities/tr-04-resguardo-legal-aprendiz.md), [T-R02](../responsibilities/tr-02-proteccion-autorizacion-pedagogica.md), [F09](../foundations/learner-autonomy.md), [F07](../foundations/pedagogical-authorization.md), [F11](../foundations/contextual-organization-autonomy.md).

## Contraste E04-N2 — hipótesis T-R01c (2026-10-21)

La necesidad N2 («contextualizar intenciones y circunstancias sin requerir formación docente profesional a familiares ni IA obligatoria») motivó la candidatura [T-R01c — Conducción de la enseñanza](../responsibilities/tr-01c-conduccion-ensenanza.md), como matización de la finalidad general T-R01.

**Distinción provisional:** T-R01a estructura componentes relativamente estables; T-R01b contextualiza/adapta o formula posibilidades situadas; **T-R01c orienta y facilita la enseñanza efectiva** aun utilizando una propuesta ya suficiente; T-R03 expresa la finalidad de aprender. Un acompañante familiar puede ejercer T-R01c sin tener que preparar todas las intenciones, adaptar cada experiencia o poseer título profesional. Las vías directas y asistidas no exigen IA obligatoria, pero tampoco prueban suficiencia disciplinar o calidad garantizada.

**Estado:** hipótesis conceptualmente defendible, **N2 aún no reconciliada definitivamente**. Pendientes: probar T-R01c en E01/E02/E03/E05, delimitar la acción 4 de T-R01b y examinar apoyos especializados cuando se requieran. No se asignan Roles ni facultades, no se promueve la nueva matización y no se reabre E04-N1.
