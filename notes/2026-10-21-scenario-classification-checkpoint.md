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
