# Checkpoint — clasificación y descubrimiento de escenarios (2026-10-21)

**Estado: propuesta de investigación y handoff, NO migración adoptada del catálogo.** Antes de cambiar la ficha del E05 actual, sus identificadores, el índice o los enlaces históricos, **contrastar si la métrica propuesta distingue realmente escenarios de características transversales**.

## Motivo

El inventario actual contiene E01 enseñanza particular; E02 aprendizaje autodidacta (independiente y colaborativo); E03 educación institucional; E04 educación en el hogar; E05 aprendizaje orientado a metas (candidato transversal). E03 fue reconciliado funcionalmente N1–N8 y auditado. E02 incluye resultados históricos sobre colaboración comunitaria que no deben perderse.

La discusión identificó ambigüedad: estudiar individualmente para obtener una credencial de arquitectura de software responde a **E02** por organización de enseñanza/aprendizaje, y simultáneamente a la dimensión **orientación por meta externa**. La presencia de meta no distingue un escenario; puede aparecer en E01, E02, E03, E04 y otros. El ejemplo MINEDUC/docente productor y comunidades que mantienen recursos motivó distinguir producción para terceros de educación comunitaria y autoorientación individual.

## Hipótesis de clasificación a validar (no adoptar aún)

Tres dimensiones iniciales, **no exhaustivas ni mutuamente excluyentes**:

| Dimensión | Pregunta | Valores ilustrativos |
| --- | --- | --- |
| Organización del aprendizaje | ¿Quién organiza la experiencia? | Individual, interpersonal, familiar, comunitaria, institucional |
| Distribución de funciones | ¿Cómo se reparten las responsabilidades educativas? | Concentradas, compartidas, especializadas, contextualmente configurables |
| Destinatarios del trabajo pedagógico | ¿Para quién se produce? | Uno mismo, aprendices conocidos, integrantes, terceros independientes, público |

Examinar otras dimensiones independientes (orientación a metas externas, autoridad, relación productor–destinatario, continuidad, acceso/conectividad, privacidad y contexto de aprendizaje). **No asumir** que tres ejes bastan, que su producto cartesiano constituye automáticamente escenarios o que un escenario tiene una sola combinación. Un **objeto de estudio o combinación candidata** no recibe identificador de escenario por sí solo.

### Estados propuestos

- **Candidato:** identificado para posible contraste, no analizado suficientemente.
- **En análisis:** necesidades, límites y suficiencia bajo contraste.
- **Soportado:** análisis terminado y cobertura demostrada conceptualmente por estructuras/configuraciones existentes, sin aportes conceptuales nuevos necesarios.
- **Formativo:** **también soportado**, pero el análisis produjo o reforzó una **propuesta conceptual sustantiva y trazable**, aunque no haya sido promovida al canon.

**Separar:** aporte conceptual *propuesto / reconciliado / adoptado* es una dimensión de madurez propia de la contribución, distinta del estado *formativo* del escenario. Reutilizar un concepto sin modificación, por sí solo, no prueba refuerzo sustantivo. Evitar clasificar por anticipado escenarios aún no analizados.

## Catálogo hipotético tras contrastar la métrica (NO ejecutar renumeración todavía)

| Identificador eventual | Denominación | Diferenciador propuesto | Estado antes de revisión |
| --- | --- | --- | --- |
| E01 | Enseñanza particular | Acompañamiento educativo interpersonal | Existente, con análisis previo |
| E02 | Enseñanza autodidacta | Una persona define y organiza íntegramente su propio aprendizaje | Requiere revisión de frontera vs modalidad colaborativa histórica |
| E03 | Educación institucional | Contexto institucional y distribución contextual de autoridad | Existente, reconciliado funcionalmente |
| E04 | Educación en el hogar | Organización familiar/doméstica | Existente, pendiente contraste de Responsibilities |
| E05 (eventual) | Enseñanza comunitaria | Funciones educativas compartidas en comunidad, sin docente central necesario | Candidato; antes propuesto como E06 |
| E06 (eventual) | Enseñanza especializada | Producción y mantenimiento de recursos pedagógicos para **terceros**, sin necesitar enseñar directamente a usuarios finales | Candidato; antes propuesto como E07 |

**Antiguo E05:** conservar **el lugar/registro histórico del descubrimiento**, pero **no tratar su contenido como escenario independiente** si el contraste confirma que es la dimensión transversal *orientación hacia metas externas*. El usuario indicó que, en esa eventualidad, la numeración de los propuestos E06/E07 descendería a E05/E06. Hasta entonces, **E05 sigue siendo el identificador de la ficha existente**. No reutilizarlo en archivos, enlaces o títulos canónicos antes de una migración deliberada y trazable.

**Antiguo E02 colaborativo:** separar hipotéticamente la enseñanza autodidacta integral/individual (E02) de enseñanza comunitaria (E05 eventual). Preservar atribución y rastreo de hallazgos originales a E02/E03; no reescribir retrospectivamente resultados ni afirmar que la comunidad no pueda incluir personas autodidactas.

**E07 discutido previamente:** la denominación «enseñanza especializada» se refiere aquí específicamente a **producción/mantenimiento de recursos educativos para terceros**, no a necesidades educativas especiales. Su cobertura puede intersectar E02 colaborativo y E03, y **todavía debe superar la prueba de distintividad** antes de adoptarse como escenario separado.

## Prueba necesaria antes de modificar E05

1. Aplicar los ejes a E01–E04 y a los escenarios comunitario/productor propuestos, con casos límite y contraejemplos.
2. Comprobar que la preparación individual para una credencial cae en E02 con característica meta externa, y que la misma meta con organización grupal/institucional cambia el escenario, sin borrar la meta.
3. Intentar refutar la suficiencia de los tres ejes: situaciones híbridas, múltiples destinatarios, productor externo sin relación docente–aprendiz, autoridad legal vs pedagógica, aprendizaje colectivo sin docente, producción pública sin alumnado identificado.
4. Evaluar si E06 comunitario (propuesto) añade necesidades no cubiertas como simple modalidad E02; evaluar si E07 especializado (propuesto) añade distinción real frente a E02/E03 y no solo otro destinatario. **Rechazar/absorber candidatos redundantes**.
5. Revisar si E05 original debe migrar a **dimensión de clasificación** y qué estructura actual puede albergarla sin crear duplicados. Verificar vocabulario existente antes de definir códigos nuevos.
6. Una vez contrastada la métrica, proponer decisión explícita del fundador sobre taxonomía, estado de cada escenario, migración de nombres y enlaces, y reglas de trazabilidad. **No adoptar por este checkpoint**.

## Escrituras deliberadamente pospuestas

- Modificar `scenarios/README.md` y la matriz `cross-scenario-coverage-2026-10-18.md` para la clasificación nueva **solo después del contraste**.
- Transformar/reubicar contenido de `scenarios/e05-aprendizaje-orientado-a-metas.md` en dimensión transversal sin eliminar su procedencia histórica; renumerar el nuevo comunitario/especializado a E05/E06 **solo tras decisión**.
- Precisar la ficha E02 individual y crear fichas de enseñanza comunitaria/productora para los escenarios que superen la prueba; transferir por enlaces la continuidad histórica de E02 colaborativo y N2 de E03.
- Registrar para cada escenario su estado (candidato/en análisis/soportado/formativo) y las propuestas sustantivas trazables, sin fingir promoción de conceptos.
- Actualizar bootstrap, inventario de necesidades, cross-links y futuros contrastes E04/E05 de manera coherente cuando se decida.

**Continuidad operativa inmediata:** investigar la métrica y sus contraejemplos, **antes de cambiar el E05 existente o comenzar renumeraciones**. El cierre funcional de E03 y las notas N6/N7/N8 permanecen intactos.

## Contraste E01 — distribución de funciones y participación indirecta (2026-10-21)

**Hallazgo propuesto por el fundador, todavía no incorporado a la ficha E01 ni elevado a una taxonomía adoptada.** La relación educativa observada en E01 puede distinguir **especialista → docente → aprendiz**:
- **Especialista:** prepara/desarrolla material pedagógico base.
- **Docente:** utiliza ese material para enseñar y puede contextualizarlo.
- **Aprendiz:** aprende con el material y las experiencias educativas.
Son **funciones observables en un caso**, no obligatoriamente personas diferentes, ni Roles canónicos, ni asignación automática de Responsibilities o autoridad T-R02.

**E01 originalmente observado:** la misma persona ejercía funciones de especialista y docente, enseñando directamente al aprendiz. **Especialización propuesta:** el especialista usa TDidacta para preparar recursos destinados a terceros, mientras docente y aprendiz pueden utilizar/consumir los resultados **sin interactuar directamente con TDidacta**. La enseñanza externa sigue existiendo; no debe inferirse que el especialista enseña directamente al aprendiz. Producción, autoría, autorización pedagógica y publicación continúan diferenciadas conforme a sus fronteras anteriores.

### Hipótesis de escenarios base y especializados

- Un **escenario base** caracteriza relaciones educativas pertinentes sin exigir que todas sus funciones sean ejercidas por una sola persona o que todos los participantes utilicen TDidacta.
- Un **escenario especializado** concreta distribución de funciones, destinatarios, condiciones y modos de uso sobre uno o varios escenarios base potencialmente compatibles; no hereda obligatoriamente cada actividad operativa como paso universal.
- **Estructura** (base/especializado) y **estado de investigación** (candidato/en análisis/soportado/formativo) son ejes diferentes. Un escenario especializado puede ser formativo si produce una propuesta conceptual sustantiva y trazable.
- La **participación educativa** y la **interacción directa con TDidacta** pueden variar independientemente. Examinar si se necesita un cuarto eje explícito o una descomposición de las dimensiones iniciales.
- El anterior candidato «enseñanza especializada para terceros» podría **no justificar escenario base E06**: puede ser especialización de E01, E02, E03 o comunitario; no decidir antes del contraste. «Especialización» no es sinónimo de necesidades educativas especiales.

### Prueba de falsación abierta

1. Determinar qué relaciones mínimas definen E01: ¿necesita efectivamente relación interpersonal docente-aprendiz aunque externa a la plataforma? ¿Qué ocurre con material publicado que nunca se enseña?
2. Examinar otros pares función/persona/usuario directo, incluidos docente usando material externo, tercero que publica material y participante aprendiz que utiliza TDidacta sin intervención del especialista.
3. Comprobar si una especialización puede relacionarse con **más de un escenario base** sin contradicción semántica, o si eso requiere distinguir composición de especialización.
4. No confundir esquema de **funciones observables** con el catálogo de Responsibilities o Roles futuros, ni trasplantar reglas de autorización derivada de intenciones pedagógicas a los escenarios.
5. Actualizar la clasificación E05/E06 y la ficha E01 únicamente si el contraste ulterior lo justifica y hay decisión deliberada.

**Estatus:** checkpoint metodológico; se preservan el E05 existente, numeración y documentos históricos.

## Primera prueba comparativa E01 — variación controlada de funciones (2026-10-21)

**Resultado exploratorio, no adopción.** Mantener separados: (a) organización y relación educativa del caso, (b) asignación de funciones a personas, (c) destinatarios y (d) participantes con interacción directa con TDidacta.

| Caso | Especialista / docente / aprendiz | Interacción con TDidacta | Lectura candidata |
| --- | --- | --- | --- |
| A. Tutor particular prepara y enseña a estudiante | Especialista=docente; aprendiz distinto | Tutor directo; estudiante variable | E01 caso conductor |
| B. Productor elabora por encargo recursos para otro docente que enseña a su alumno | Tres participantes distintos | Productor directo; otros indirectos | Especialización plausible de E01 con enseñanza externa |
| C. Tutor usa material previo de especialista externo | Tres participantes distintos | Tutor directo; productor puede no utilizarlo | E01 plausible: separación de autoría/uso |
| D. Persona publica material abierto sin destinatario ni situación de enseñanza identificable | Productor identificado; docente y aprendiz solo potenciales | Productor directo | **Indeterminado**: no inventar relación docente–aprendiz para forzar E01 |
| E. Comunidad produce y mantiene recursos para terceros | Funciones colectivas; docentes y aprendices pueden estar fuera | Integrantes productores directos | Potencial especialización comunitaria, sin decidir aún escenario base |
| F. Institución encarga materiales a especialistas para docentes de otras instituciones | Producción/uso entre organizaciones; funciones separadas | Interacción parcial | Puede atravesar E03 y producción externa; probar composición vs especialización |

**Hallazgo provisional:** dividir *funciones entre personas* o cambiar *quién interactúa con la plataforma* **no basta por sí solo** para crear escenario base. Pero una producción completamente desacoplada de toda relación de enseñanza observable (D) podría requerir otra interpretación: no asumir por definición que cae en E01.

**Falla posible de los tres ejes originales:** D2 (funciones distribuidas) no describe por sí sola cuáles son las funciones, quién las ejerce ni quién utiliza directamente TDidacta; D3 no distingue receptor del material de aprendiz efectivamente acompañado. Antes de agregar un cuarto eje, comprobar si conviene registrar **relaciones funcionales** y **modo de interacción con la plataforma** como atributos de cada caso.

**Criterio de decisión a contrastar en otros escenarios:** una variación es especialización cuando preserva las relaciones constitutivas pertinentes del escenario base, aunque reasigne funciones u omita pasos operativos no esenciales. Si hay que inventar participantes o relaciones ausentes para clasificarla, la cobertura **no está demostrada**. Una especialización puede revelar brecha acotada sin exigir análisis exhaustivo de todo el escenario base.

**Siguiente contraste:** ejecutar el mismo test con E02 individual, E03 institucional, E04 hogar y comunitario propuesto, incluyendo el caso D, para comprobar si hay escenario base no cubierto. No migrar E05 todavía.


## Extensión de investigación y cambio en el orden de trabajo (2026-10-21)

Se preparó la [extensión de modelo de clasificación de escenarios](2026-10-21-scenario-classification-model-extension.md), con hipótesis, casos discriminadores, riesgos, puntos de falsación y posibles criterios públicos de cobertura. **Es material de investigación, no una definición adoptada.** En particular:

- Diferenciar **escenarios de cobertura** de **Escenarios pedagógicos base/especializados**, que ya están definidos canónicamente en F10.
- El escenario de «producción especializada para terceros» **no debe suponerse base independiente**: la conversación posterior lo considera plausiblemente una especialización o dimensión de otros escenarios. La candidatura E06 previa queda en revisión.
- El criterio de *escenario formativo* es **contribución conceptual sustantiva y trazable** sobre un escenario soportado, independientemente de la adopción posterior de esa propuesta.
- El **trabajo exhaustivo de métrica ya NO es puerta obligatoria previa** al progreso inmediato de escenarios: por instrucción posterior del fundador, priorizar avanzar en la separación E02 autodidacta/comunitaria y en la futura conversión del E05 actual (metas) a dimensión, con trazabilidad deliberada. **Ninguna migración se ejecuta con esta nota.** El debate amplio de clasificación queda para cierre de bootstrap o investigación posterior.

**Recordatorio:** hay un pendiente explícito en el [bootstrap V6](tdidacta-v6-coverage-bootstrap.md) para decidir cuándo resolver o retomar esta línea. Los apartados anteriores permanecen como antecedentes de etapas previas; esta actualización indica la prioridad vigente.
