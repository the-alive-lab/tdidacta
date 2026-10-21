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

## Reconciliación funcional de E04-N2 (2026-10-21)

**Resultado de la revisión:** N2 se considera **cubierta conceptualmente para el contraste de necesidades y Responsibilities** por la finalidad general acordada [T-R01 — Enseñanza](../responsibilities/README.md) y sus matizaciones: [T-R01a](../responsibilities/tr-01a-planificacion-contextualizacion-pedagogica.md) estructura componentes relativamente estables; [T-R01b](../responsibilities/tr-01b-contextualizacion-adaptacion-pedagogica.md) contextualiza, ajusta o formula posibilidades situadas; [T-R01c](../responsibilities/tr-01c-conduccion-ensenanza.md) ejerce orientación y acompañamiento durante la experiencia sin exigir adaptación previa. [T-R03](../responsibilities/tr-03-aprendizaje-retroalimentacion.md) conserva la finalidad distinta de aprender; [T-R02](../responsibilities/tr-02-proteccion-autorizacion-pedagogica.md) protege y autoriza elementos cuando corresponde.

**Casos suficientes para distinguir labores:** (a) un acompañante familiar utiliza una intención existente y conduce la experiencia mediante T-R01c; (b) adapta posibilidades por necesidades situadas mediante T-R01b, sin obligarse a conducirlas; (c) prepara o revisa componentes estables mediante T-R01a. Estas finalidades pueden recaer en una persona, distribuirse o coincidir en el tiempo: **no existe pipeline T-R01a → T-R01b → T-R01c**. La [prueba transversal de T-R01c en E01/E02/E03/E05](../notes/2026-10-21-tr01c-cross-scenario-contrast.md) y la reconciliación posterior de la acción 4 de T-R01b sustentan esta delimitación.

**Vías de participación:** directa y asistida, sin hacer obligatoria la IA ni exigir título de docencia profesional como condición universal para acompañar. Esto **no elimina la necesidad de conocimiento disciplinar, juicio pedagógico o apoyo especializado** cuando el caso lo requiere, ni garantiza calidad, eficacia, comprensión o cumplimiento externo. No asigna facultades legales, Roles, ni adopta acciones completas de las fichas candidatas.

**Estado y reservas:** E04-N2 queda **reconciliada funcionalmente** con las matizaciones **candidatas** de T-R01 y otras Responsibilities pertinentes, sin declararla implementada o jurídicamente validada. Permanecen abiertas la evaluación de modalidades directas/asistidas, el acceso a apoyo especializado y la revisión futura de las fichas candidatas. Los apartados de hipótesis anteriores muestran el estado previo al contraste; esta sección es la conclusión vigente. Continuar con E04-N3.

## Reconciliación funcional E04-N3 (2026-10-21)

**Resultado acordado:** N3 queda reconciliada a nivel de Responsibilities, sin afirmar implementación. Orientar y acompañar la enseñanza corresponde a [T-R01c](../responsibilities/tr-01c-conduccion-ensenanza.md); explorar y reconsiderar la propia comprensión a [T-R03](../responsibilities/tr-03-aprendizaje-retroalimentacion.md). **Revisar el desarrollo de la experiencia mientras se enseña es parte de T-R01c** cuando sirve a la conducción; **revisar la adecuación de una intención o propuesta corresponde a T-R01a/b** según su alcance estable o situado. El fundador confirmó expresamente esta frontera.

[F06](../foundations/pedagogical-review-and-correction.md) distingue revisión de corrección; [T-R02](../responsibilities/tr-02-proteccion-autorizacion-pedagogica.md) conserva la protección y autorización pertinentes. Una dificultad observada no implica corregir ni autorizar automáticamente. Las vías directas y asistidas son compatibles con juicio humano situado sin exigir IA ni conferir autoridad automática a herramientas o acompañantes.

**Reservas:** eficacia real, mecanismos, asistencia especializada y condiciones de acceso requieren contraste posterior. Las fichas T-R01a/b/c y demás Responsibilities mantienen su estado candidato; no se adoptan Roles. Continuar E04-N4; N4–N6 permanecen abiertas.

## Contraste E04-N4 — frontera administrativa y pedagógica (2026-10-21)

**Precisión acordada por el fundador:** [T-R05](../responsibilities/tr-05-gestion-acceso-recursos.md) se refiere a administración de recursos y configuraciones: **T-R05a** gestiona acceso legítimo y disponibilidad administrativa de recursos; **T-R05b** configura condiciones operativas o flujos de trabajo. No se atribuye a quien administra la obligación general de resolver por qué una familia no puede aprovechar material o pedagógicamente un recurso.

**T-R01b** interpreta circunstancias como tiempo, materiales, conectividad y barreras funcionales cuando requieren adaptar la propuesta educativa. **T-R01c** acompaña su realización dentro de condiciones existentes. **O9** conserva disponibilidad, utilizabilidad y pertinencia como dimensiones distintas; **O7** condiciona privacidad transversalmente y **T-R04** interviene solo si corresponde una función de apoderado. Habilitar un recurso no garantiza su utilizabilidad ni calidad pedagógica.

**Estado:** frontera T-R05/T-R01b acordada; **N4 aún no reconciliada como necesidad completa**. Falta contrastar la suficiencia de privacidad y protección de menores, así como la distribución de barreras materiales y sus límites. No se adoptan Roles ni mecanismos.

## Reconciliación funcional E04-N4 — acceso, privacidad y resguardo (2026-10-21)

**Acuerdo expreso del fundador:** N4 queda **reconciliada en el contraste de necesidades y Responsibilities**, no como validación jurídica ni implementación.

- **T-R01b:** interpreta limitaciones de tiempo, medios, conectividad o accesibilidad y prepara respuestas **pedagógicas** pertinentes; no garantiza la eliminación material de la barrera. **T-R01c** conduce la experiencia dentro de las condiciones reales.
- **T-R05a:** administra el acceso legítimo y la disponibilidad **administrativa** de recursos; **T-R05b** configura flujos y condiciones operativas. Administrar el acceso no atribuye autoridad ilimitada sobre los datos ni resuelve por sí solo barreras materiales.
- **O7:** privacidad y minimización de datos personales como condición transversal, aun sin apoderado; **O9:** distinguir disponibilidad, utilizabilidad y pertinencia.
- **T-R04:** representación y resguardo de intereses del aprendiz **cuando corresponde** una función de apoderado; no equivale a familiaridad ni concede control irrestricto sobre la información.
- **F11:** distribuir facultades contextuales no crea legitimidad de divulgación por sí mismo. La autoridad pertinente para divulgar puede ser distinta de quien configura o concede técnicamente acceso; un flujo T-R05b tampoco la sustituye.

**Principio reconciliado:** administración de accesos, autoridad legítima sobre información y representación de intereses del aprendiz son funciones diferentes aunque coincidan en una misma persona. Ninguna sustituye O7. Tratándose de menores, no presumir que cualquier familiar accede a todos sus datos.

**Reservas:** requisitos jurídicos según edad y jurisdicción, autoridad de divulgación, bases de tratamiento/consentimiento cuando apliquen, salvaguardas, controles, evaluaciones de accesibilidad y eficacia operativa. No se crean Responsibilities ni Roles; las matizaciones continúan candidatas. Los contrastes preliminares anteriores quedan como historia; **N5 es la siguiente necesidad abierta**.

## E04-N5 — apertura de T-R07 candidata (2026-10-21)

La distinción de prácticas formativas, **evidencia revisable de capacidades y comprensión**, juicio evaluativo, certificación y reconocimiento oficial motivó la [candidatura T-R07 — Evaluación profunda y desafío de competencias](../responsibilities/tr-07-evaluacion-profunda-competencias.md). T-R01 evalúa para mejorar la enseñanza; T-R07 busca examinar actuaciones con finalidad propia; T-R03 conserva elecciones autónomas y T-R02 autoriza elementos pedagógicos, no conocimientos de la persona.

[Primer contraste E01–E05](../notes/2026-10-21-tr07-evaluacion-profunda-contraste-inicial.md): plausibilidad funcional condicional, con contraejemplos. Se proponen evidencia y matrices interpretativas revisables, criterios de profundidad y transferencia, dimensiones base y extensiones inicialmente deshabilitadas; su habilitación es contextual T-R05b y las solicitudes optativas del aprendiz se vinculan con T-R03 y privacidad pertinente. No se atribuyen personalidad, valor moral, eficacia demostrada ni reconocimiento oficial a resultados.

**Estado:** T-R07 candidata; **E04-N5 abierta** mientras se contrastan criterios, eficacia y autoridad de evaluación/acreditación. No se adoptan Roles, mecanismos ni reforma de O0/F01. N6 permanece abierta.

## Continuidad investigativa de E04-N5 (2026-10-21)

La distinción funcional T-R01/T-R07 permanece como **candidatura**, y la suficiencia de las evaluaciones requiere evidencia metodológica externa al catálogo. Se abrió [intake investigativo provisional en research-space](https://github.com/vslices/research-space/blob/main/lines/pedagogical-intent-realization/notes/2026-10-21-tdidacta-tr07-research-intake.md), sin iniciar una RQ ni Study y sin considerar probada la validez de las evaluaciones. **E04-N5 no queda cerrada por registrar el handoff.** La investigación futura podrá revisar la propuesta, sin alterar retrospectivamente los acuerdos de E04-N1–N4.

## Reconciliación funcional E04-N5 — evaluación, aprendizaje y acreditación (2026-10-21)

**Acuerdo del fundador:** la **intención pedagógica** especifica las dimensiones que exige examinar, sujetas a habilitación contextual explícita de **T-R05b**; **T-R03** puede escoger dimensiones adicionales habilitadas no obligatorias y decidir legítimamente si comparte sus resultados voluntarios. **T-R07**, Responsibility todavía candidata, **recibe ambos alcances**, realiza desafíos y produce hechos revisables y matrices de interpretación por dimensión; no modifica unilateralmente la intención ni la habilitación. Si se solicita una dimensión deshabilitada, la incompatibilidad se comunica y se puede requerir intervención de quien tiene facultad de habilitarla. El supuesto «conjunto base» no establece dimensiones universalmente obligatorias.

**Frontera de finalidades:** T-R01 observa y evalúa para orientar/adaptar enseñanza; T-R03 aprende y decide sus exploraciones; T-R07 examina competencias y actuaciones con finalidad propia, aun si no deriva en una nueva intervención pedagógica; T-R02 autoriza elementos pedagógicos, no certifica competencias individuales. Evaluar **no equivale** a acreditar, certificar o conferir validez oficial; estas últimas facultades dependen de autoridades externas/contextuales legítimas y no surgen de T-R07.

**Estado actualizado:** **E04-N5 reconciliada funcionalmente**, no acreditada jurídicamente ni implementada. Se mantiene T-R07 **candidata**, sujetas a investigación sus dimensiones, métodos, validez, fiabilidad y modalidades de datos personales. Los registros anteriores que decían «N5 abierta» conservan su procedencia temporal y son superados **solo en la frontera funcional** por esta decisión. **E04-N6 continúa abierta.**
