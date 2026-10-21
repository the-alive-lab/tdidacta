# Extensión del checkpoint — hipótesis para un modelo de clasificación de escenarios de cobertura

**Fecha:** 2026-10-21  
**Estado:** exploración y preservación de hipótesis. **NO es un modelo adoptado, no demuestra suficiencia ni modifica el inventario de escenarios.**  
**Origen:** discusión posterior al [checkpoint de clasificación](2026-10-21-scenario-classification-checkpoint.md), especialmente la distinción funcional especialista–docente–aprendiz y los casos productores de recursos para terceros.  
**Retomar:** al finalizar el bootstrap de TDidacta, decidir si esta línea se resuelve en ese cierre o pasa a investigación posterior. **No bloquear el avance inmediato de E04 y del contraste de Responsibilities** por intentar terminar la taxonomía.

## 0. Síntesis ejecutiva de lo que se preserva

El inventario actual fue elaborado principalmente desde modalidades observables. Al ampliar los ejemplos, aparecen variaciones de *quién organiza*, *quién trabaja*, *quién enseña*, *quién aprende*, *para quién se produce*, *quién utiliza TDidacta* y *bajo qué condiciones*. No toda diferencia en esos atributos amerita un escenario base nuevo.

**Hipótesis principal:** una familia reducida de escenarios base podría servir para clasificar casos concretos mediante **especializaciones, composiciones y características transversales**. Antes de adoptar esa arquitectura debemos encontrar las **relaciones constitutivas** de cada base, reconocer los casos no clasificables y comprobar que esta clasificación explica necesidades de cobertura sin esconder brechas.

**No confundir tres resultados**:

1. **Describir un caso:** somos capaces de escribir sus características en una tabla.
2. **Clasificarlo:** podemos justificar una relación concreta con uno o varios escenarios base.
3. **Declarar soporte:** demostramos cobertura suficiente de sus necesidades y restricciones para el alcance afirmado.

Una descripción completa **no implica** clasificación válida; clasificación plausible **no implica** soporte; soporte conceptual **no implica** implementación, conformidad externa o eficacia educativa.

## 1. Frontera canónica decisiva: dos significados distintos de «escenario»

**[Escenarios de cobertura](../scenarios/README.md)**: fichas E01–E05 que examinan contextos de participación, necesidades y suficiencia del sistema. Este documento trabaja en la clasificación **de esos escenarios**.

**[Escenario pedagógico](../concepts/application-circumstances.md)**: concepto **ya adoptado** bajo F03/[F10](../foundations/pedagogical-adaptation.md) con tipos **base y especializado**. Allí un escenario base describe circunstancias de aplicación de una intención, y el especializado es particularizado durante su uso por el aprendiz, respetando intención y restricciones.

**Advertencia:** las expresiones *escenario base de cobertura* y *especialización de escenario de cobertura* se proponen solo como vocabulario de esta investigación. NO son los tipos canónicos de Escenario pedagógico F10. No trasladar automáticamente:

- quién puede especializar: F10 describe la especialización por quien aprende; la especialización de cobertura puede describir organización, productores, docentes, familias y comunidades;
- qué se preserva: F10 conserva significado de la intención; aquí deben examinarse relaciones constitutivas del **contexto de participación**;
- reglas de autorización: variantes de intenciones, autorización directa/derivada E03-N6 y clasificación de escenarios son operaciones diferentes;
- numeración/identidad, versionamiento o estructura técnica.

**Riesgo terminológico:** si el modelo llega a adoptarse, contrastar nombres menos colisionantes —por ejemplo *familia de cobertura*, *caso particularizado* o *perfil de cobertura*— antes de reutilizar literalmente «escenario especializado». No adoptar un nuevo concepto o archivo solo por esta advertencia.

## 2. Decisiones de dirección ya conversadas, frente a operaciones no hechas

- **E01:** su observación inicial concentraba en una persona la preparación pedagógica y la enseñanza; ahora se considera la separación entre **especialista (prepara materiales), docente (enseña) y aprendiz (aprende)**. Son funciones observables, no necesariamente tres personas ni Roles canónicos.
- **E02:** la dirección acordada es distinguir el autodidactismo en que la propia persona conduce integralmente su aprendizaje de la **enseñanza comunitaria**. Hallazgos comunitarios que hoy constan en E02 deben preservarse con sus referencias originales.
- **E03:** ya pasó auditoría funcional N1–N8. Su variante institucional puede tener combinaciones variables de responsabilidades, autoridad y destinatarios sin imponer jerarquía universal.
- **E04:** educación en hogar conserva su propio contraste pendiente; no reducirla automáticamente a E01 o E02.
- **E05 actual:** «Aprendizaje orientado a metas» se considera mejor **dimensión transversal**: estudiar autónomamente para una credencial corresponde a E02 con meta externa; con comunidad, a la modalidad comunitaria; con institución, a E03. **Su ficha y su identificador siguen intactos físicamente**, pendientes de migración con trazabilidad.
- **E05 eventual:** «Enseñanza comunitaria» después de retirar como escenario el E05 anterior y separar E02, sujeto a la migración documental deliberada.
- **E06 eventual, originalmente «Enseñanza especializada» para terceros:** **se debilita expresamente su candidatura como escenario base**. Producción/mantenimiento de materiales para terceros puede especializar E01, la comunidad o E03. NO reservar obligatoriamente E06 para esto ni inferir que se necesita un escenario base adicional.
- **Estados de investigación propuestos:** candidato → en análisis → soportado **o** formativo. Formativo significa soportado y además produjo/reforzó una propuesta conceptual sustantiva y trazable, aunque la propuesta no haya sido adoptada. Madurez de la propuesta es otra variable. No marcar como formativo un caso aún no soportado solamente porque produjo una idea interesante.

**Secuencia operativa prioritaria:** avanzar E04, realizar la separación E02/comunitario y la migración del antiguo E05 cuando se decida, continuar Responsibilities/Roles según las puertas vigentes. La validación exhaustiva del modelo de clasificación no debe bloquear ese recorrido.

## 3. Modelo explicativo mínimo hipotético

Evitar exigir desde el comienzo una ontología o un espacio cartesiano exhaustivo. Separar entidades de trabajo:

| Nivel | Para qué sirve | Qué NO asegura |
| --- | --- | --- |
| **Caso observado/propuesto** | Situación concreta con actores, actividades, materiales, contexto y supuestos | No es todavía escenario base ni prueba de cobertura |
| **Escenario base de cobertura (candidato)** | Relaciones contextuales mínimas cuya presencia hace reconocible una familia de experiencias | No implica flujo obligatorio, Rol o producto |
| **Especialización de cobertura** | Caso que conserva relaciones constitutivas de una base e incorpora o precisa condiciones | No hereda ciegamente todas las tareas del caso conductor |
| **Composición de cobertura (hipótesis)** | Caso cuya lectura depende de varias bases y de examinar compatibilidad | No equivale a mezcla libre o cobertura sumada automáticamente |
| **Dimensión/característica transversal** | Propiedad que puede variar dentro de varias bases | No determina por sí sola pertenencia a una familia |
| **Necesidades y fronteras** | Condiciones concretas que deben contrastarse con el conocimiento/capacidades de TDidacta | No equivalen a funcionalidades implementadas |
| **Resultado del contraste** | Cobertura suficiente, brecha, conflicto, incertidumbre o fuera de alcance | No equivale a certificación de aprendizaje/eficacia |

Las relaciones entre niveles todavía requieren prueba. En especial, una propiedad presente en muchos escenarios podría ser **dimensión** o una **restricción transversal**, pero no todo rasgo es necesariamente un nuevo eje primario.

### 3.1 De la tabla de tres ejes a una descripción más cuidadosa

La tabla anterior identificó:

- **D1 Organización:** individual/interpersonal/familiar/comunitaria/institucional.
- **D2 Distribución de responsabilidades:** concentradas/compartidas/especializadas/configurables.
- **D3 Destinatarios:** uno mismo/participantes identificados/terceros/público.

**Evaluación:** útiles como preguntas de entrada, pero sus valores **no son mutuamente excluyentes ni necesariamente del mismo nivel lógico**. Por ejemplo, «institucional» describe un tipo de organización; «interpersonal», una relación; «configurable», una propiedad de la asignación; «especializada», la naturaleza del trabajo; «público», una condición de destinatario/acceso.

No exigir un único valor por eje. Tampoco asumir que cada combinación representa un escenario válido: hay combinaciones incoherentes, redundantes, no observadas o no relevantes para TDidacta.

### 3.2 Descomposición candidata de atributos

| Bloque descriptivo | Pregunta de contraste | Ejemplos | Reserva |
| --- | --- | --- | --- |
| **Organización del contexto** | ¿Qué sostiene y coordina la experiencia o la producción? | Persona, relación particular, comunidad, familia, institución; combinaciones | No equiparar organización jurídica y pedagógica |
| **Relaciones funcionales** | ¿Qué actividades educativas existen y cómo se relacionan? | Preparar, revisar, enseñar, acompañar, aprender, mantener, publicar | No prescribir una secuencia universal |
| **Asignación situada** | ¿Cuántas personas ejercen cada función y cómo se solapan? | Especialista=docente; especialistas distintos; equipos | Funciones observadas ≠ Roles ≠ Responsibilities |
| **Destinatario y mediación** | ¿Quién recibe el material, quién lo aplica y quién aprende? | Docente mediador, aprendiz conocido, público, destinatario futuro | Consumidor del recurso ≠ aprendiz efectivamente enseñado |
| **Relación con TDidacta** | ¿Quién usa el sistema y quién solo aprovecha resultados? | Creador directo, docente indirecto, aprendiz sin cuenta, uso offline | Compatible con O9; no es jerarquía educativa |
| **Autoridad y procedencia** | ¿Quién aporta, decide, autoriza, mantiene o puede compartir? | Autor, autoridad pedagógica, dueño de acceso, entidad certificadora | F07/F08/F11/O7 no se reemplazan por la métrica |
| **Propósito externo** | ¿Qué meta, mandato o necesidad origina la experiencia? | Credencial, interés personal, currículo externo | Hipótesis de dimensión transversal antes E05 |
| **Restricciones contextuales** | ¿Qué condiciones limitan la pertinencia y el uso? | Edad, privacidad, accesibilidad, recursos, jurisdicción, continuidad | No exigir identificación/sensibilidad innecesarias |

**Diseño alternativo más parsimonioso:** tres dimensiones iniciales como vista resumida, acompañadas de un **mapa de relaciones funcionales** y una lista de **condiciones transversales**. Elegirlo solo si explica contraejemplos con menos ambigüedad que agregar ejes innumerables.

## 4. Experimento mental conductor: especialista → docente → aprendiz

Separar por lo menos:

- **Preparación:** especialista crea/adapta material pedagógico.
- **Mediación docente:** docente usa el material para orientar una experiencia.
- **Aprendizaje:** aprendiz interactúa con la experiencia/material en su contexto.

**Caso conductor original de E01:** una misma persona puede ocupar especialista y docente; otra participa aprendiendo. **Caso extendido propuesto:** especialista utiliza TDidacta y entrega material a docente; docente enseña sin utilizar directamente la plataforma; aprendiz aprende en entorno externo. No se necesita relación informática directa entre esos tres para que la experiencia sea educativa.

Esto permite distinguir **identidad de participante**, **función observada**, **ejercicio de una Responsibility** y **uso de TDidacta**, que nunca deben inferirse unos de otros automáticamente.

**Límite revelador:** la ficha [E01 actual](../scenarios/e01-ensenanza-particular.md) describe explícitamente una persona que proporciona enseñanza particular a otra/grupo. El caso de productor que simplemente publica materiales para destinatarios todavía desconocidos **no prueba por sí solo** que exista esa relación. No expandir E01 de manera silenciosa ni inventar un docente o aprendiz concreto; contrastar si corresponde una especialización, otra base, una actividad transversal o un caso aún no clasificable.

**No confundir** publicar un material con enseñar directamente, ni permitir su uso con demostrar aprendizaje, ni crear su contenido con autorizarlo o publicarlo legítimamente.

## 5. Qué podría ser una especialización de cobertura válida

Propuesta de criterio contrastable:

> Una especialización conserva las **relaciones constitutivas pertinentes** de una familia base y concreta sus variaciones contextuales. Puede añadir, distribuir, omitir actividades *no constitutivas* o alterar medios de interacción, pero no puede suprimir una relación constitutiva y seguir declarándose integrante de la familia sin revisión.

La mayor dificultad es **identificar las relaciones constitutivas sin definirlas circularmente** («E01 es E01 porque se parece a E01»). Un candidato a relación constitutiva exige:

1. **Razonamiento independiente del nombre:** describir qué problema/contexto explica, no quién tiene un título o puesto.
2. **Necesidad discriminadora:** si se elimina, ¿la experiencia permanece en la misma familia? Aplicar contrafactuales.
3. **Invarianza frente a funciones:** sustituir especialista=docente por personas distintas no debería destruir sin explicación la clasificación.
4. **No invención de actores:** las relaciones no observadas deben marcarse como desconocidas.
5. **Trazabilidad:** necesidades/cobertura que pueden trasladarse del caso base, y brechas específicas restantes.
6. **Compatibilidad:** si el caso se relaciona con varias bases, examinar restricciones e incompatibilidades; no sumar garantías sin evidencia.

**Especialización vs composición:** si el caso conserva una sola estructura constitutiva con ajustes, estudiar especialización. Si realmente coexisten dos estructuras reconocibles (por ejemplo, hogar con coordinación comunitaria efectiva), probar composición. No presuponer que toda experiencia híbrida admite un solo padre o que toda coincidencia de rasgos justifica composición.

**Composición no equivale** a autorización derivada N6, herencia transitiva de versiones pedagógicas, árbol escolar obligatorio, ni superposición automática de facultades F11.

## 6. Casos discriminadores para intentar falsar el modelo

Son **ejemplos hipotéticos**, no observaciones empíricas ni certificación de soporte.

| Caso | Lectura inicial | Qué podría refutar |
| --- | --- | --- |
| A. Tutor prepara y enseña a un estudiante | E01 caso conductor | Base que requiere cargos distintos |
| B. Especialista prepara por encargo y otro docente enseña | Especialización E01 plausible | Base dependiente del mismo usuario para producir/enseñar |
| C. Docente utiliza recursos de especialista externo | E01 plausible | Supuesto de autoría propia del docente |
| D. Especialista publica recursos abiertos sin docente/aprendiz observado | **Indeterminado** | Extensión excesiva de E01; productor ≠ enseñanza particular demostrada |
| E. Persona aprende sola para credencial profesional | E02 + meta externa | E05 anterior como escenario independiente |
| F. Comunidad comparte ayuda/feedback para miembros | Comunitario propuesto | E02 individual que se atribuye coordinación colectiva |
| G. Comunidad mantiene biblioteca pública que otros utilizan | Especialización comunitaria o composición | «Destinatario tercero» como escenario base automático |
| H. Institución produce materiales para otra | E03 + destinatario externo | Exigir que uso final ocurra dentro de la organización |
| I. Familia educa en casa con especialista contratado | E04 con componentes E01 | Confusión organización familiar con docencia particular |
| J. Varias familias sostienen una comunidad de aprendizaje | E04 + comunitario por contrastar | Exclusividad artificial de una sola base |
| K. Recurso creado en TDidacta se usa impreso sin cuentas | Caso E01/E03/E04 + O9 | Inferir ausencia de participantes por no usar la plataforma |
| L. Alumno autodidacta publica posteriormente materiales para otros | E02 para su aprendizaje + actividad productora | Suponer que toda producción redefine el escenario de aprendizaje |
| M. Especialista crea recurso, nadie lo enseña/usa aún | Producción futura sin enseñanza observada | Confundir intención de uso, publicación y cobertura efectiva |
| N. Comunidad administra aportes sensibles de menores | Comunitario/hogar/institucional según relación + O7 | Suponer privacidad resuelta por clasificación general |
| O. Un mismo aprendiz participa simultáneamente en escuela, tutoría y autodidactismo | Múltiples experiencias/relaciones coexistentes | Imponer clasificación única por persona |
| P. Institución ofrece programa orientado a licencia externa | E03 + meta externa/certificación ajena | Convertir toda meta externa en E05 antiguo |

**Resultados tentativos, no veredictos:** A–C favorecen separar distribución funcional de identidad del escenario; E/P ilustran transversalidad de metas; D/M son contraejemplos fundamentales; J/O prueban composición y pluralidad; K exige independencia entre uso directo e indirecto.

### Contraejemplo crítico D/M

Dos lecturas rivales:

- **H-A:** E01 debe admitir una relación de enseñanza particular *posible*, incluso cuando todavía no exista enseñanza observada. Riesgo: hacer E01 tan amplio que deje de discriminar.
- **H-B:** producir recursos para destinatarios no conocidos constituye una actividad transversal (o una familia base diferente), y no puede clasificarse como E01 sin relación docente–aprendiz identificable. Riesgo: multiplicar bases para variaciones de producción.

La elección no se resuelve declarando que «es obvio». Contrastar qué necesidades de cobertura son propias del caso, qué funciones de T-R01/T-R02/T-R05 se requieren, qué situación educativa se observa y qué promesa pública sería legítima.

## 7. Estados de investigación y aportes conceptuales

| Estado del escenario | Condición de entrada sugerida | Condición de salida sugerida |
| --- | --- | --- |
| **Candidato** | Caso o familia propuestos, con razón para examinarlo | Delimitación suficiente para contraste |
| **En análisis** | Contraste de relaciones, necesidades, fundamentos y Responsibilities abierto | Conclusión defendible de cobertura / no cobertura |
| **Soportado** | Análisis cerrado con cobertura suficiente para alcance definido; sin contribución conceptual sustantiva | Estado final para ese alcance, revisable |
| **Formativo** | Igual que soportado **y** contribución sustantiva trazable, propuesta o reforzada | Estado final para ese alcance, revisable |

**Situaciones que no deben ocultarse:** *no soportado*, *no clasificable todavía*, *brecha abierta* o *fuera de alcance*. Evaluar si son veredictos de contraste (más prudente) o estados adicionales; no imponer un flujo que fuerce todo candidato a soportado/formativo. **Formativo no significa «adoptó un concepto»**; basta la propuesta fundada. Si aparece aporte durante análisis pero soporte sigue incierto, registrar el aporte sin anticipar estado formativo.

Propuesta de trazabilidad mínima: caso → escenario(s) base(s) potencial(es) → características y relaciones → necesidades → fundamento/responsibility existente o brecha → conclusión de alcance → contribución conceptual (si la hay) → decisión de adopción de esa contribución, separadamente.

## 8. Procedimiento liviano de triaje (propuesta)

**Objetivo operativo:** no estudiar exhaustivamente todos los casos futuros; primero decidir si una clasificación existente puede explicar sus necesidades con suficiente confianza.

1. **Describir el caso sin clasificarlo todavía.** Observar participantes, acciones pedagógicas, relaciones, destinatarios, contextos y suposiciones.
2. **Caracterizar:** organización, funciones, destinatarios, uso directo/indirecto y condiciones transversales. Permitir «desconocido», «no aplica», «varios» y «condicional».
3. **Probar bases conocidas:** en cada una identificar una relación constitutiva preservada y una potencial contradicción; no decidir solo por similitud verbal.
4. **Elegir hipótesis:** (a) instancia simple de base; (b) especialización; (c) composición; (d) dimensión transversal; (e) base nueva candidata; (f) aún indeterminado/fuera de alcance.
5. **Hacer contraste de suficiencia incremental:** reutilizar lo ya demostrado por E01–E04 y otros; analizar **solo** diferencias, conflictos y necesidades que podrían quedar fuera.
6. **Registrar incertidumbre y procedencia:** qué se observó, infirió o propuso; quién verificó y qué sigue faltando.
7. **Escalar investigación cuando haya gatillos:** contradicción con definición base, combinación de restricciones incompatible, nueva finalidad funcional, alcance externo delicado, afirmaciones públicas imposibles de justificar o evidencia negativa.

**Principio de carga proporcional:** un caso nuevo no necesita necesariamente una ficha completa ni un identificador permanente. Puede registrarse como ejemplo de especialización/contraste. No se debe forzar la ampliación del catálogo para alcanzar «cobertura total».

## 9. Cómo evaluar la métrica antes de adoptarla

La métrica no debe evaluarse solo por su capacidad de describir los seis casos inicialmente escogidos: eso sería sobreajuste.

**Hipótesis falsables:**

- **H1 — Discriminación:** distingue E02 autónomo de comunidad sin exigir una meta externa como escenario.
- **H2 — Redistribución:** conserva clasificación cuando especialista y docente se separan, si la relación educativa de la base permanece.
- **H3 — No invención:** produce «indeterminado» cuando faltan relaciones constitutivas, sin inventar aprendices.
- **H4 — Composición:** admite experiencias híbridas sin crear jerarquía universal ni declarar automáticamente compatibilidad.
- **H5 — Dimensiones:** metas, acceso indirecto y privacidad pueden atravesar varias familias sin identificadores de base nuevos.
- **H6 — Parsimonia:** incorporar casos nuevos no obliga sistemáticamente a crear bases ni ejes.
- **H7 — Cobertura responsable:** «clasificado» y «soportado» arrojan resultados diferentes cuando hay brechas reales.
- **H8 — Estabilidad:** distintos evaluadores llegan a decisiones parecidas con reglas explícitas y registran desacuerdos.
- **H9 — Trazabilidad:** reclasificar E02/E05 no borra procedencia de contribuciones originales.
- **H10 — Utilidad externa:** una explicación pública puede mostrar ejemplos cubiertos, límites y evidencia sin afirmar validación universal.

**Posibles observables para evaluación futura**, no objetivos numéricos adoptados: proporción de casos clasificables sin supuestos inventados; número de ambigüedades justificadas; contradicciones detectadas; estabilidad entre evaluadores; cantidad de nuevas bases exigidas por casos; trazabilidad de necesidades; esfuerzo de clasificación; coherencia de veredictos de cobertura frente a revisión independiente. No proponer puntuación global ni umbral arbitrario antes de tener ejemplos comparables.

**Evaluación por conjuntos separados:** (i) casos usados para diseñar la clasificación; (ii) casos de borde/adversariales; (iii) casos nuevos no usados en su diseño; (iv) revisión por evaluadores distintos, cuando resulte viable. Un modelo que solo explica E01–E04 no demuestra generalidad.

## 10. Consecuencias para demostrar capacidad ante el público

A futuro este trabajo podría permitir demostrar **amplitud de situaciones educativas atendibles** sin enumerar miles de «modalidades» ni prometer soporte universal.

**Escalera de afirmaciones de alcance (candidata):**

1. **Caso descrito:** conocemos características y limitaciones.
2. **Caso clasificado:** hay correspondencia justificada con una familia/dimensiones.
3. **Caso cubierto conceptualmente:** necesidades confrontadas con responsabilidades/fundamentos.
4. **Caso realizable o implementado:** existe mecanismo operativo comprobable para parte o todo su alcance.
5. **Caso evaluado empíricamente:** hay observaciones de uso, utilidad, accesibilidad o aprendizaje, según criterios y límites propios.

No anunciar «100 % compatible», «validado» o «enseña eficazmente» por tener solo una matriz de correspondencia. Permitir mostrar **condiciones y restricciones**, alcance de verificación, medios directos/indirectos y evidencia verificable. Una demostración convincente puede seleccionar **casos contrastantes** que muestren la independencia entre funciones educativas y uso de la plataforma, no únicamente multiplicar filas del catálogo.

**Propuesta de producto de comunicación futuro:** ficha legible por caso con *problema/organización*, *relaciones funcionales*, *destinatarios*, *uso directo/indirecto*, *necesidades*, *qué cubre TDidacta*, *qué no cubre todavía*, *evidencia y fecha*. No adoptar ahora pantalla, API, formato o certificación.

## 11. Conexiones canónicas y límites de autoridad

- [F01](../foundations/teaching-and-learning.md): enseñar y aprender pueden coincidir o distribuirse; no fijar identidades inmutables.
- [F02/F03](../foundations/pedagogical-needs-and-intentions.md): una meta externa puede motivar necesidades e intenciones, pero la clasificación de cobertura no es intención pedagógica.
- [F10 y concepto de escenario pedagógico](../foundations/pedagogical-adaptation.md): **no confundir** sus tipos base/especializado con lo propuesto aquí.
- [F07](../foundations/pedagogical-authorization.md), [F08](../foundations/pedagogical-authorship.md), [F11](../foundations/contextual-organization-autonomy.md) y [F12](../foundations/opinionated-starting-configurations.md): separar autorización humana, contribución, facultades contextuales y configuraciones iniciales.
- [O9](../orientation/contextual-access-and-educational-reach.md) y [E03-N8](2026-10-21-e03-n8-external-use-projections-continuity.md): docentes/aprendices pueden beneficiarse sin TDidacta directo; disponibilidad, utilizabilidad y pertinencia no son lo mismo.
- [E03-N6](2026-10-20-e03-n6-pedagogical-intent-authorization-open-questions.md): las reglas de variantes/linaje/autorización de intenciones están sin reconciliar canónicamente; no aplicarlas a escenarios por analogía.
- [Responsibilities](../responsibilities/README.md): funciones observadas en ejemplos no son el catálogo transversal T-Rxx ni asignación de Roles.
- [Gobernanza](../governance/README.md): investigaciones, propuestas, decisiones y evidencia mantienen estados distintos.

### Inspiraciones externas acotadas, no adopciones

- **W3C [PROV-Overview](https://www.w3.org/TR/prov-overview/) y [PROV Primer](https://www.w3.org/TR/prov-primer/):** la separación entre entidades, actividades y agentes ofrece una **analogía** útil para registrar procedencia de casos, funciones y aportes sin confundirlos. No significa adoptar PROV como modelo de TDidacta o asumir coincidencia entre su noción de *role* y Roles de TDidacta.
- **Modelado de variabilidad en familias de software:** el artículo [*Local features: Enhancing variability modeling in software product lines* (2024)](https://doi.org/10.1016/j.jss.2024.112035) distingue variabilidad general y particularizable. Las opciones y restricciones entre características inspiran preguntas sobre especialización/composición, **pero los escenarios educativos no son automáticamente configuraciones de productos software**.
- **Estudios de modelado de variabilidad:** [*Software product lines and variability modeling: A tertiary study* (2019)](https://doi.org/10.1016/j.jss.2018.12.027) documenta variedad de modelos y límites de evidencia industrial: razón adicional para no asumir que un diagrama de características basta como verificación.
- **Diseño basado en escenarios:** [resumen de scenario-based design y Carroll](https://www.sciencedirect.com/topics/computer-science/scenario-based-design) como antecedente para usar casos situados y contraejemplos; es analogía de método, no autoridad para redefinir el concepto canónico de escenarios.

Estas referencias no demuestran que la clasificación propuesta funcione ni que se requiera un nuevo Framework, un IR de escenarios o una representación automatizable.

## 12. Preguntas decisionales pendientes (registro, NO respuesta aprobada)

1. ¿Cuál es la propiedad constitutiva mínima de E01 cuando especialista y docente son personas distintas, y qué ocurre si no hay enseñanza observable?
2. ¿La enseñanza comunitaria merece una base diferenciada del autodidactismo independiente por estructura de cooperación/autoridad, o podría representarse como composición? La dirección elegida por el fundador es **separarla**; examinar implicaciones, no deshacerla por nomenclatura.
3. ¿Cuándo la producción para terceros es especialización, actividad transversal o familia distinta? Tratar el viejo E06 como hipótesis debilitada, no como requisito.
4. ¿Qué base debe prevalecer en casos simultáneamente familiares, comunitarios e institucionales, si acaso debe haber una base principal?
5. ¿Qué rasgos se consideran ejes de clasificación y cuáles son restricciones, propiedades de interacción o resultados investigativos?
6. ¿Qué estructura y nombres evitarán colisionar con *Escenario pedagógico base/especializado* ya aprobado en F10?
7. ¿Cómo cuantificar públicamente amplitud de cobertura sin prometer resultados educativos ni ocultar casos desconocidos?
8. ¿La clasificación es prioritariamente un método de investigación/documentación, una funcionalidad para organizar propuestas públicas, o ambas? No derivar un producto nuevo sin motivación independiente.
9. ¿Qué evidencia de campo, casos adversariales o evaluación por terceros sería suficiente para declarar la métrica útil?
10. ¿Debe cerrarse esta investigación durante la revisión final del bootstrap o abrirse una línea/Study posterior en Research? **Decidir la ubicación y autoridad metodológica cuando se retome, no ahora.**

## 13. Punto de reanudación explícito

**Al finalizar el bootstrap**, leer esta extensión junto con su [checkpoint principal](2026-10-21-scenario-classification-checkpoint.md). Registrar una decisión sobre:

- **Resolver dentro del bootstrap:** si basta una clasificación documental mínima, contrastada con ejemplos y con E01–E05 ya ajustados, sin bloquear otras tareas.
- **Continuar después como investigación autónoma:** si se necesitan contraejemplos externos, pruebas sistemáticas, evidencia de uso, evaluación por terceros o una semántica formal de clasificación.
- **Rechazar/simplificar:** si al contrastar los casos no añade capacidad explicativa real frente a las fichas de escenarios y sus necesidades.

Mientras tanto, la instrucción de continuidad es **preservar estas hipótesis, no convertirlas en canon**, no renumerar ahora desde esta nota, no alterar F10/F07/F11 ni las pruebas congeladas, y avanzar con los escenarios y Responsibilities pendientes.

---

# Anexo II — profundización del modelo explicativo (2026-10-21)

**Estado del anexo:** hipótesis nuevas y refinamientos de las secciones 0–13, todos **pendientes de validación**. Este anexo no sustituye las posiciones históricas de arriba, no cambia E01–E05 y no es adopción de nuevos Concepts, Foundations, Roles, Responsibilities, formatos ni mecanismos. Se agrega porque el modelo puede resultar útil para demostrar alcance educativo públicamente, pero necesita distinguir con rigor descripción, clasificación, cobertura y evidencia.

## 14. Primera corrección epistemológica: ¿qué unidad estamos clasificando?

Una misma narración suele mezclar cuatro unidades que conviene distinguir antes de asignar identificadores:

| Unidad candidata | Qué delimita | Ejemplo | Error si se confunde |
| --- | --- | --- | --- |
| **Situación / caso particular** | Una configuración observada, prevista o hipotética en cierto contexto | Ana produce una guía que Luis utilizará con Carla | Concluir que existe una familia nueva por cada variación |
| **Relación / experiencia educativa** | Una interacción o trayectoria de enseñanza/aprendizaje, que puede existir fuera de TDidacta | Luis acompaña a Carla utilizando la guía | Exigir que todas las personas usen la plataforma |
| **Proceso de contribución a recursos** | Preparación, mantenimiento, revisión, publicación o distribución con posible destinatario futuro | Ana publica una guía sin que se conozca aún un docente | Inventar una relación directa de enseñanza que no existe en la observación |
| **Familia o escenario de cobertura** | Conjunto de casos que conservan relaciones constitutivas pertinentes y necesidades comparables | E01 particular, E02 autodidacta, E03 institución | Tratar el nombre de la familia como descripción exhaustiva de cada caso |

**Hipótesis:** clasificar un proceso de producción no es automáticamente lo mismo que clasificar la experiencia educativa que se realizará con sus resultados. Pueden estar conectados por procedencia, pero tener participantes, tiempos y contextos diferentes.

### 14.1 Caso completo frente a fragmento del caso

La pregunta «¿a qué escenario pertenece una guía pública cuyos usuarios aún se desconocen?» puede estar mal formada. Se observa **un fragmento de la trayectoria educativa** (la producción) sin disponer de los otros tramos. El fragmento es real como actividad, aunque la experiencia futura no sea observable.

Proponer tres situaciones epistemológicas distintas:

- **No observado / desconocido:** no sabemos si existe docente o aprendiz; no inventarlos ni negar su existencia.
- **Futuro o condicional:** se prevé que alguien pueda enseñar/aprender, pero no hay una experiencia concreta todavía.
- **Ausencia positivamente establecida:** el caso delimitado excluye expresamente cierta relación; aun así, no puede inferirse imposibilidad de usos futuros.

El resultado «aún no clasificable como experiencia E01» **no equivale** a «TDidacta no soporta el flujo de producción». Puede haber cobertura de una parte del trabajo y alcance incierto de la experiencia total. Este parece el núcleo del contraejemplo D/M.

### 14.2 Tiempo y límites de la observación

Una persona que hoy aprende autónomamente (E02), mañana prepara materiales para otros y después acompaña a un estudiante (E01) **no transforma retrospectivamente** el primer episodio en E01. Un mismo recurso puede participar en varios episodios. Una clasificación debería poder señalar **qué momento, relaciones y alcance** está describiendo, sin exigir que una persona tenga una identidad de escenario permanente.

**Riesgo:** si el identificador de escenario se asigna a la persona o a su cuenta, el modelo clasifica individuos en vez de contextos, induce falsas exclusividades y confunde aprendizaje paralelo con cambio de identidad.

## 15. Taxonomía estricta frente a clasificación por facetas y relaciones

La primera tabla D1/D2/D3 mezclaba tipos de propiedad y valores superpuestos. Hay al menos tres caminos:

1. **Taxonomía estricta:** dimensiones con características bien delimitadas, destinadas a asignaciones consistentes; necesita especificar exclusividad, exhaustividad y manejo de casos híbridos.
2. **Clasificación facetada:** varias propiedades independientes pueden coexistir en un caso; un caso puede ocupar múltiples valores y registrar desconocidos.
3. **Modelo relacional de casos:** las personas o grupos, acciones, recursos, destinatarios y relaciones se describen explícitamente; las etiquetas de escenario se **derivan razonadamente** de ese registro.

**Hipótesis preferida para contrastar:** *facetas como vista ligera + relaciones educativas constitutivas como argumento de clasificación*. El modelo relacional solo será necesario si las facetas no discriminan correctamente; no adoptar un grafo formal ni una ontología por anticipado.

Una faceta puede ser verdaderamente un **atributo de caso** y no una dimensión taxonómica en sentido estricto. Por ejemplo, «institucional» y «comunitario» podrían coexistir, mientras «autodidacta» expresa un modo de organización personal y «tercero desconocido» un vínculo con destinatarios. Forzar exclusividad produciría decisiones arbitrarias.

**Criterio de parsimonia:** añadir una dimensión solo si resuelve un error de clasificación o de cobertura que no se resuelve registrando mejor una relación o restricción existente.

### 15.1 No toda combinatoria tiene sentido educativo

El conjunto hipotético de valores no implica que su producto cartesiano sea un catálogo de casos válidos. Distinguir:

- combinación **lógicamente incompatible** con las definiciones de sus atributos;
- combinación **posible pero no observada**;
- combinación **observada pero ajena al alcance definido de TDidacta**;
- combinación **pertinente pero no cubierta todavía**;
- combinación **cubierta conceptualmente** para ciertas necesidades;
- combinación **demostrada operativamente** bajo condiciones explícitas.

Estas diferencias deben estar documentadas, no escondidas bajo una celda vacía ni una cruz verde.

### 15.2 E05 orientado a metas como prueba de independencia

La misma meta «aprobar una credencial de arquitectura de software» puede coexistir con E02, un programa institucional E03, tutoría E01 o comunidad colaborativa. Si cambiar únicamente la fuente de una meta externa cambia la familia de escenario, la métrica está **mezclando propósito con organización**. La meta es un buen ejemplo de dimensión transversal candidata porque **no decide por sí sola la relación educativa**.

**Matiz:** una meta puede cambiar necesidades, plazos, evidencia o restricciones de evaluación; «transversal» no significa «irrelevante para cobertura». Una meta regulada puede agregar una exigencia externa que TDidacta no está autorizado a satisfacer.

## 16. Semántica mínima de las relaciones: no tratar títulos como predicados

El esquema especialista → docente → aprendiz es útil para pensar funciones, pero podría dar lugar a una falsa linealidad. Puede existir:

- especialista que produce para varios docentes;
- docentes que adaptan materiales de varias fuentes;
- aprendices que estudian sin docente;
- una persona que combina producción, mediación y aprendizaje;
- aportes de una comunidad sin titular único;
- aprendiz que contribuye a mejorar el material;
- medios de aplicación externos donde TDidacta no puede observar uso o aprendizaje.

Por eso la flecha no debe entenderse como **pipeline obligatorio**, sino como relaciones posibles que conviene distinguir.

### 16.1 Vocabulario analítico provisional

| Relación candidata | Describe | No debe inferirse automáticamente |
| --- | --- | --- |
| **produce/prepara** | Participante desarrolla un material o propuesta | Que tiene autorización pedagógica o facultad de publicación |
| **revisa/transforma** | Participante aporta cambios o evaluación | Que ejerce T-R02, que todo cambio constituye coautoría |
| **media/enseña** | Participante acompaña una experiencia mediante recursos o acciones | Que creó los recursos o accedió a TDidacta |
| **aprende/participa** | Participante toma parte en aprendizaje | Que alcanzó el resultado pretendido |
| **distribuye/facilita acceso** | Hace llegar recursos o experiencias a destinatarios | Que el acceso es legítimo, suficiente o pedagógicamente adecuado |
| **autoriza pedagógicamente** | Decisión humana válida para intención/versión/alcance | Que equivale a autoría, acceso a datos o certificación |
| **coordina/mantiene** | Atiende coherencia, relaciones o continuidad | Que es dueño del contenido, de los datos o de toda la organización |
| **interactúa con TDidacta** | Utiliza directamente alguna superficie del sistema | Que necesariamente ejerce docencia |
| **aprovecha resultado** | Se beneficia de recursos producidos con TDidacta | Que accede al sistema, conformidad automáticamente verificada o aprendizaje efectivo |

Estas son **distinciones de análisis**, no predicados formales ni catálogo de facultades. Comparar con F01/F07/F08/F11/O9/Responsibilities al retomar. Especialmente, «especialista» puede significar experiencia disciplinar, función de preparación, producción editorial u otra cosa: su **nombre no constituye evidencia** de qué hizo.

### 16.2 Relaciones constitutivas frente a relaciones accidentales

La identidad de E01 no debe deducirse del hecho de que haya exactamente dos cuentas, ni de que un docente haga clic en publicar. Un posible núcleo es **enseñanza/acompañamiento particular con destinatario o grupo delimitado**, compatible con mediación y producción por terceros. Pero esto **no está adoptado** y enfrenta el caso de un especialista que produce por encargo sin conocer a los alumnos.

Para proponer una relación constitutiva sin circularidad:

1. Formular la situación educativa que la relación explica.
2. Identificar necesidades que aparecerían aun sin TDidacta.
3. Quitar contrafactualmente la relación: ¿desaparece la diferencia con otras familias?
4. Cambiar quién ejerce cada función sin alterar la relación; comprobar estabilidad.
5. Buscar un caso vecino en que dos familias predicen consecuencias diferentes.
6. Registrar **qué evidencia distingue** «pertenece», «no pertenece» e «indeterminado».

Las relaciones constitutivas no necesariamente son condiciones universales fijadas una vez para siempre: deben ser revisables si los casos revelan contradicciones reales.

## 17. Especialización, composición, intersección y sucesión: cuatro operaciones distintas

| Operación hipotética | Pregunta discriminadora | Ejemplo | Riesgo |
| --- | --- | --- | --- |
| **Especialización** | ¿Sigue siendo recognoscible una familia al concretar condiciones y funciones? | E01 con especialista ≠ docente | Heredar pasos accidentales como obligaciones |
| **Composición** | ¿Hay dos relaciones educativas con dependencias que interactúan y requieren reconciliación conjunta? | Red entre familias que enseña en hogares y comparte decisiones comunitarias | Sumar garantías sin compatibilizar límites |
| **Intersección de características** | ¿Coinciden simplemente propiedades sin crear una relación nueva? | Tutor particular + meta de credencial | Tratar cualquier etiqueta adicional como escenario nuevo |
| **Sucesión/continuidad** | ¿Una experiencia cambia de contexto o los resultados pasan a otra? | Recurso creado individualmente, adoptado luego por institución | Reescribir la procedencia del primer episodio |

**Hipótesis:** composición no debe activarse porque una persona aparezca en dos escenarios. Requiere **interacción material entre las relaciones**, por ejemplo decisiones o recursos compartidos con restricciones cruzadas. Dos actividades educativas paralelas pueden mantenerse independientes.

**Subtipo problemático: transferencia:** una organización produce una realización que otra utiliza. Puede ser un vínculo entre actividades o escenarios distintos, no una «composición» de ambas instituciones. Registrar dependencia del recurso y condiciones de uso quizá explique el caso mejor que una genealogía de escenarios.

### 17.1 Composición no monotónica

La cobertura de cada componente por separado **no garantiza** la cobertura de su combinación. Ejemplo hipotético: un recurso utilizable en casa y compartible en una comunidad puede dejar de ser legítimamente compartible si contiene una observación sensible. También una autorización pedagógica válida en un alcance no se amplía por acumular escenarios.

Esto no significa importar las reglas de fusión/autorización derivada de E03-N6. Es una **analogía de riesgo**: las restricciones de las relaciones participantes deben revisarse conjuntamente.

## 18. Esquema mínimo de registro para experimentar sin infraestructura nueva

No crear un formato, carpeta o IR ahora. Una fila de nota o ficha Markdown puede bastar:

| Campo candidato | Valor ilustrativo | Interpretación |
| --- | --- | --- |
| **Caso y procedencia** | «Especialista por encargo»; ejemplo propuesto en conversación | Procedencia y estado de observación |
| **Unidad observada** | Producción del material + enseñanza futura separada | Limita el alcance de la inferencia |
| **Participantes conocidos** | Productor externo, docente destinatario | No implica conocer al aprendiz |
| **Relaciones comprobadas** | Productor prepara recurso; docente lo recibirá | Distinguir *previsto* de *observado* |
| **Relaciones desconocidas** | Uso final y aprendizaje logrado | No completar con ficción |
| **Uso de TDidacta** | Productor directo; docente/aprendiz indirectos posibles | Independiente de funciones |
| **Familia candidata** | E01 | Hipótesis, no veredicto |
| **Alternativa competitiva** | Trabajo productor transversal previo a experiencia E01 | Reduce sesgo de encaje |
| **Necesidades nuevas o diferentes** | Entrega, continuidad, autorización, atribución | Vincular a artefactos existentes |
| **Contradicción o reserva** | E01 actual describe enseñanza particular efectivamente organizada | Impide afirmar clasificación cerrada |
| **Conclusión provisional** | Especialización plausible, soporte total por comprobar | No es adopción |
| **Siguiente prueba** | Preguntar si existe docente-aprendiz delimitado; contrastar uso sin intervención de productor | Investigación proporcional |

**Dato mínimo sobre incertidumbre:** distinguir *hecho descrito por la fuente*, *supuesto para el experimento*, *inferencia razonada* y *pregunta abierta*. Para una afirmación pública añadir fecha/versión de TDidacta y evidencia. Evitar tratar notas de exploración como hechos empíricos sobre usuarios reales.

**Valor práctico:** este formato permitiría clasificar casos nuevos con poco trabajo, comparar decisiones previas y registrar por qué dos analistas discrepan **sin diseñar todavía un motor automático de taxonomía**.
