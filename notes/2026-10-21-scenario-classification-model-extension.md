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
| **Especialización** | ¿Sigue siendo reconocible una familia al concretar condiciones y funciones? | E01 con especialista ≠ docente | Heredar pasos accidentales como obligaciones |
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

## 19. Clasificación por explicación, no por parecido superficial

Una similitud («este caso se parece a E01») puede sugerir una hipótesis, pero **no justificarla**. Proponer comparar explicaciones rivales con un registro breve:

| Pregunta | Alternativa A | Alternativa B | Evidencia que discriminaría |
| --- | --- | --- | --- |
| Productor sin docente identificado | E01 especializado | Proceso productor transversal sin escenario de enseñanza clasificable | Existencia o ausencia delimitada de relación particular de enseñanza |
| Familia con tutor externo | E04 con apoyo E01 | E01 dentro de domicilio familiar | Quién organiza y responde por la experiencia, y si hay dos relaciones separables |
| Comunidad abierta de aprendizaje | E02 colaborativo histórico | Nueva familia comunitaria propuesta | Dependencia de decisiones, coordinación y continuidad colectivas |
| Institución que produce para terceros | Especialización E03 | Dos experiencias vinculadas por transferencia de recurso | Organización de trabajo productor vs organización de enseñanza receptora |

**Criterio tentativo de elección:** preferir la explicación que preserve hechos observados, exija menos participantes o relaciones no comprobados, represente mejor las necesidades pertinentes y deje visibles las reservas. Si dos explicaciones permanecen defendibles, **conservar ambas** y la pregunta que las distingue. No seleccionar solo porque una es más fácil de implementar.

### 19.1 Pruebas contrafactuales / metamórficas

Adaptar la idea de pruebas de metamorfismo como **instrumento conceptual**, no como protocolo automatizado aprobado. Una modificación controlada debería preservar ciertas conclusiones **solo cuando no modifica una relación constitutiva**:

| Transformación controlada | Expectativa a contrastar | Falla reveladora |
| --- | --- | --- |
| Una misma persona deja de ser especialista+docente; otra toma el material y enseña al mismo aprendiz | Familia E01 probablemente estable si persiste enseñanza particular | Clasificador basado en identidad o cuenta |
| Material preparado con TDidacta pasa a imprimirse y utilizarse externamente | Contexto educativo reconocible puede persistir | Confundir uso de plataforma y enseñanza |
| E02 autodidacta agrega una meta externa explícita | Debería seguir siendo E02; cambia la dimensión de propósito | Tratar la meta como escenario exclusivo |
| Se añade deliberación y mantenimiento verdaderamente comunitarios al trabajo E02 | Puede cambiar a comunitario o introducir otra relación; **no** exigir estabilidad | Modelo incapaz de reconocer colaboración sustantiva |
| Una institución agrega recursos externos con autoría reconocida | E03 puede persistir, cambiando procedencia y necesidades | Base definida por producción interna exclusivamente |
| Familia incorpora tutor para una actividad concreta | E04 puede persistir con apoyo particular | Exigir que familia cumpla toda función pedagógica |
| Un recurso público se vuelve restringido por razones legítimas | Clasificación educativa quizá persiste, **cobertura de acceso puede cambiar** | Inferir cobertura desde pertenencia taxonómica |
| Docente recibe información sensible de aprendiz sin facultad legítima para divulgarla | Escenario puede persistir; divulgación ya no está cubierta | Clasificador que hace desaparecer límites O7 |
| Grupo de personas estudia en el mismo lugar pero sin contribución mutua | No necesariamente E05 comunitario | Confundir copresencia con organización comunitaria |
| Grupo se coordina y comparte autoridad para orientar aprendizaje | Posible comunidad educativa real | Clasificador que solo mira número de participantes |

**Advertencia:** «expectativa» no es verdad garantizada. Estos cambios pueden revelar fronteras funcionales y semánticas que obliguen a revisar los invariantes hipotéticos, en lugar de corregir el caso para hacerlo encajar.

### 19.2 Prueba de no-colapso

La taxonomía debe distinguir casos cuando **diferir tiene consecuencias de cobertura**. Si las mismas etiquetas sirven para una tutoría con un aprendiz identificado y para un productor editorial sin usuario final conocido, necesitamos explicar si:
- el modelo sí distingue ambos **mediante relaciones o reservas**, aunque compartan facetas; o
- el supuesto escenario E01 fue ampliado hasta perder poder discriminador.

Una clasificación que mapea todas las situaciones a una base universal tendría **máxima cobertura aparente y mínima utilidad analítica**.

### 19.3 Prueba de no-explosión

La solución contraria tampoco sirve: inventar una base nueva cada vez que cambian la edad, el tamaño del grupo, la tecnología, la meta, la procedencia del recurso o la persona que ejerce una función. El modelo debe conservar identidad conceptual cuando una variación se explica adecuadamente por una especialización o una restricción transversal.

**Tensión a evaluar:** poder discriminador vs economía conceptual. No maximizar uno aislado del otro.

## 20. La noción de «soporte» necesita un alcance y un argumento

Hay una diferencia entre poder **representar** una configuración y poder **atender satisfactoriamente sus necesidades**. Incluso «soportado por configuraciones» requiere precisar *qué capacidades están definidas*, *qué está implementado* y *qué condición externa permanece necesaria*.

### 20.1 Evaluar necesidades individuales antes del veredicto global

| Resultado por necesidad (hipótesis documental) | Significado | Ejemplo |
| --- | --- | --- |
| **Cubierta para el alcance indicado** | Existe razón y soporte identificables para atender la necesidad dentro de condiciones expresas | Uso indirecto de materiales previsto en O9; comprobar realización operativa aparte |
| **Cubierta condicionalmente** | Depende de una restricción que puede o no cumplirse | Compartir material solo si acceso/publicación son legítimos |
| **Parcial** | Alguna parte pertinente queda fuera | Impresión posible, reintegración externa no implementada |
| **Pendiente / incierta** | No se ha examinado o no hay evidencia suficiente | Verificación de un recurso externo arbitrario |
| **Contradicha / no cubierta** | Una limitación conocida impide satisfacer la necesidad para ese alcance | Prometer certificación oficial que TDidacta no otorga |
| **No aplicable** | No forma parte de las necesidades de esa experiencia | Representación legal de menores en caso adulto sin menores |

**No declarar el escenario entero soportado mediante una media aritmética** que pueda ocultar una necesidad obligatoria sin cubrir. El resultado global depende de las necesidades pertinentes y de cuáles son **condiciones innegociables** para la afirmación específica.

**Tesis de trabajo:** el soporte pertenece a una pareja *escenario/caso + alcance y condiciones*, no necesariamente a una etiqueta de escenario a perpetuidad. Un escenario puede ser soportado para distribución de materiales y no estarlo para certificación externa, analítica de aprendizaje o privacidad de datos sensibles bajo cierto régimen.

### 20.2 Cuatro planos de evidencia, sin confundirlos

1. **Semántico/conceptual:** fundamentos, conceptos y Responsibilities ofrecen una explicación coherente de la necesidad; puede haber lagunas abiertas.
2. **Operativo/de realización:** existe flujo, material, interfaz, integración o procedimiento que funciona bajo condiciones declaradas; demostrar ejecución concreta.
3. **Normativo o de autorización contextual:** el uso es legítimo, autorizado o permitido donde corresponda; el funcionamiento técnico no suple derechos, políticas, autorizaciones ni certificaciones.
4. **Empírico educativo:** observaciones permiten inferir algo específico sobre uso, acceso, comprensión o resultados, dentro de límites metodológicos; generar una lección no demuestra aprender.

Los planos son relacionados pero **no equivalentes ni necesariamente ordenados linealmente**. Un producto puede funcionar técnicamente y ser pedagógicamente inadecuado o jurídicamente improcedente para cierto contexto. Un caso conceptualmente cubierto puede seguir sin implementación. Una certificación de tercero no se transforma en autorización pedagógica de TDidacta.

### 20.3 Esqueleto mínimo de argumento de cobertura

Para afirmar «TDidacta atiende el caso X para el propósito Y, bajo las condiciones Z» sería útil poder reconstruir:

- **Afirmación precisa:** cuál es el alcance real, qué destinatarios y medios contempla, y qué excluye.
- **Necesidades pertinentes:** qué debe cumplirse para que esa afirmación sea razonable; cuáles son condiciones críticas.
- **Razón de cobertura:** vínculo concreto con principios, Responsibilities, soluciones, capacidades/configuraciones existentes y sus límites.
- **Evidencia:** qué documento, prueba, demostración u observación respalda *cada tramo de la inferencia*.
- **Supuestos y contraevidencia:** qué no se sabe, qué puede refutar la afirmación y qué restricciones siguen abiertas.
- **Estado y fecha:** si se trata de propuesta, contraste conceptual, función probada o eficacia evaluada; qué versión/superficie aplica.

**Ejemplo ilustrativo de afirmación honesta:** «El diseño de TDidacta contempla preparar un recurso que un docente utiliza fuera de la plataforma; la viabilidad de exportar y verificar conformidad de todas las formas de representación no está demostrada». Está respaldada conceptualmente por O9 y E03-N8, **pero no autoriza afirmar soporte universal de cualquier exportación**.

**Anti-ejemplo:** «TDidacta soporta todos los casos E01 y cualquier especialización, por lo tanto todos sus aprendizajes son equivalentes y efectivos». Aquí se infieren realizaciones y eficacia desde pertenencia al catálogo, sin evidencia.

### 20.4 Formativo como propiedad del aprendizaje del proyecto

El estado propuesto **formativo** evalúa lo que el análisis del caso aportó al conocimiento de TDidacta, **no** que se trate de un escenario especialmente bueno para enseñar a alumnos. Para evitar homonimia pedagógica, explicitar esta acepción cuando llegue a documentación pública.

Ejemplo: E03 puede aportar propuestas sobre autorización derivada, trazabilidad y coordinación, **aunque** algunas no hayan sido adoptadas canónicamente. Su contribución es trazable; la reconciliación funcional del escenario y la formalización pendiente de F07 son estados diferentes.

Un caso que descubre un defecto importante **pero aún no tiene cobertura suficiente** puede producir conocimiento valioso sin poder declararse formativo según el criterio elegido por el fundador (formativo ⊆ soportado). No borrar su contribución: registrarla como resultado investigativo sin promover el estado.

## 21. Protocolo de contraste incremental y evidencia de generalización

No iniciar esta investigación exhaustiva ahora. Dejar preparado un protocolo **candidato** para cuando corresponda, sin confundirlo con un Manual/Automated Protocol de Research ya aprobado.

### 21.1 Ciclo iterativo propuesto

1. **Elegir metacaracterística:** ¿clasificamos organización y participación educativa *para estimar cobertura*, no disciplinas, profesiones, plataformas o niveles escolares?
2. **Tomar casos diversos:** E01–E04 y comunitario como ejemplos usados en el descubrimiento, además de casos de borde deliberadamente incómodos.
3. **Contrastar hipótesis de familias y facetas** contra las relaciones registradas, con decisiones y dudas trazables.
4. **Separar casos de diseño y evaluación:** retener algunos que no se hayan utilizado para formular las categorías.
5. **Registrar errores:** falsos encajes, necesidades omitidas, duplicación de familias, casos imposibles de diferenciar y ambigüedad entre revisores.
6. **Refinar lo mínimo necesario:** primero frontera/relación, luego faceta; nueva familia solo si esos recursos siguen siendo insuficientes.
7. **Revisar criterios de cierre:** evaluar si explica los casos pertinentes y si agregar más estructura realmente mejora su utilidad.

El trabajo de [Nickerson, Varshney y Muntermann (2013)](https://doi.org/10.1057/ejis.2012.26) presenta un método iterativo de desarrollo de taxonomías. Es un **precedente metodológico** para definir objeto de clasificación, dimensiones y condiciones de cierre, **no una prueba ni obligación de adoptar una taxonomía estricta**.

### 21.2 Conjunto mínimo de contraste futuro

| Grupo | Ejemplos orientativos | Resultado que buscamos |
| --- | --- | --- |
| **Conductores conocidos** | E01 particular, E02 individual, E03 institucional, E04 familiar | Reproducir fronteras ya fundadas |
| **Cambios controlados** | Especialista/docente separados; material impreso; misma experiencia con meta externa | Probar invariancia frente a atributos no constitutivos |
| **Casos ambiguos** | Productor sin aprendices identificados; familias comunitarias; institución que produce para otra | Conservar explicaciones alternativas, no forzar etiqueta |
| **Casos adversariales** | Comunidad sin colaboración real; publicación sin autoridad; recurso disponible pero inutilizable | Detectar falsos soportes |
| **Casos nuevos** | Situaciones que no participaron en el diseño de ejes | Evaluar generalización, no solo ajuste retrospectivo |

**Medidas descriptivas candidatas:** tiempo humano de clasificación, cantidad de supuestos inventados, proporción de casos aún indeterminados, desacuerdos entre revisores, omisiones de restricciones críticas, modificaciones del catálogo necesarias para absorber casos nuevos. No seleccionar pesos, puntajes ni objetivos numéricos antes de definir un conjunto de validación.

### 21.3 Independencia y error

En una futura revisión con más de un evaluador, documentar no solo acuerdo final sino **desacuerdos fundamentados**. Dos personas pueden coincidir en la etiqueta E01 mientras discrepan sobre si la enseñanza es observada o solamente prevista. Una concordancia superficial de nombres no equivale a concordancia conceptual.

Un caso de frontera puede permanecer «indeterminado» y ser un **resultado correcto** si faltan datos materiales. La taxonomía no debería castigar la incertidumbre honesta incentivando categorías inventadas.

### 21.4 Criterios de parada

Para evitar que la taxonomía se convierta en trabajo infinito, proponer condiciones de cierre **revisables y no numéricas**:

- No hay contradicciones documentales bloqueantes entre las definiciones actuales y los casos ensayados.
- Los casos importantes pueden clasificarse o declararse razonadamente indeterminados.
- Añadir otra faceta o familia no mejora de manera justificable la clasificación o la detección de brechas.
- La documentación de cada decisión puede ser comprendida por otra persona sin la conversación de origen.
- Se pueden expresar límites y evidencias de soporte sin afirmar resultados educativos no probados.
- La operación de triaje resulta proporcional al valor que aporta; no requiere revisar todos los escenarios para registrar un caso pequeño.

**No hay obligación de alcanzar una cobertura universal del espacio de escenarios**, ni de demostrar que se han enumerado todas las formas posibles de enseñar y aprender. La clasificación debe ser extensible y admitir futuras objeciones.

## 22. Representación pública: de «podemos clasificarlo» a «podemos atenderlo»

Esta iniciativa tiene dos usos futuros que no deben mezclarse:

**Uso interno:** detectar necesidades, reutilizar contraste existente, priorizar brechas y gestionar continuidad de decisiones.

**Uso público:** explicar qué tipos de experiencias TDidacta contempla, cómo se beneficia quien no usa la plataforma y qué evidencias justifican cada afirmación.

### 22.1 Ejemplo de ficha pública candidata

**Caso:** especialista independiente prepara material para que otro docente enseñe a un grupo.

| Pregunta del visitante | Respuesta que podría fundamentarse |
| --- | --- |
| ¿Qué experiencia es? | Preparación de recursos con mediación docente externa; E01 especializado como hipótesis de familia |
| ¿Quién necesita usar TDidacta? | Potencialmente solo especialista; uso indirecto amparado conceptualmente por O9 |
| ¿Qué trabajo ayuda a organizar? | Intención, preparación, adaptación, procedencia y restricciones; alcance real por verificar |
| ¿Qué pasa con la autoridad? | Preparar no equivale a aprobar, divulgar ni certificar; F07/F08 permanecen diferenciados |
| ¿Funciona con materiales imprimibles? | Hay dirección conceptual de acceso indirecto; capacidades concretas dependen de formato y mecanismo |
| ¿Está probado que enseña mejor? | No se puede afirmarlo sin investigación empírica situada |
| ¿Qué falta verificar? | Representación externa, restricciones, disponibilidad, adecuación y comportamiento operativo |

**Principio de interfaz futuro:** permitir recorrer casos por contexto, funciones, destinatarios y condiciones; mostrar ejemplos contrastantes en lugar de una cifra grandilocuente de «escenarios soportados».

La **interfaz** es opcional. Una tabla Markdown y ejemplos trazables pueden cumplir la responsabilidad de comunicación sin una nueva Platform ni un «catalogador automático».

### 22.2 Afirmaciones públicas por niveles

| Tipo de afirmación | Ejemplo prudente | Evidencia requerida |
| --- | --- | --- |
| **Intención del diseño** | «TDidacta contempla apoyo a enseñanza indirecta» | Orientación/documento canónico |
| **Cobertura conceptual examinada** | «Este caso tiene necesidades contrastadas con Responsibilities identificadas» | Matriz de correspondencia y reservas |
| **Capacidad disponible** | «Este flujo puede realizarse en la versión X bajo estas condiciones» | Demostración/pruebas de la implementación concreta |
| **Adecuación en un contexto** | «La experiencia fue utilizable para este grupo y estos recursos» | Observación contextual; condiciones de acceso |
| **Resultado educativo** | «Se observó mejora en un indicador definido para esta población» | Diseño evaluativo válido con límites e incertidumbre |

El documento [ISO/IEC/IEEE 29148:2018](https://www.iso.org/standard/72089.html) proporciona un antecedente para distinguir requisitos, necesidades, trazabilidad y verificación/validación. Y los *assurance cases* (p. ej. [SEI/CMU — Toward a Theory of Assurance Case](https://insights.sei.cmu.edu/documents/1222/2012_005_001_28161.pdf)) ofrecen una analogía de **afirmación + argumento + evidencia**, útil para evitar saltar de una ficha a una promesa pública. **No aplicar una certificación o notación de seguridad como estándar educativo adoptado**.

### 22.3 Derecho a decir «todavía no sabemos»

Para una plataforma educativa de acceso público, ocultar desconocimientos sería especialmente problemático cuando se trata de menores, privacidad, discapacidad, recursos limitados o exigencias oficiales.

La documentación debería poder expresar «no examinado», «solo conceptual», «parcial», «requiere autorización externa», «no verificado para este medio», «no cubre certificación» o «hay conflicto pendiente», sin dejar de mostrar qué trabajo educativo es posible.

**Hipótesis de valor público:** una clasificación abierta a excepciones y con trazabilidad de evidencia podría ser más convincente que una lista larga de sectores educativos supuestamente compatibles.

## 23. Riesgos de diseño y antipatrones a vigilar

| Riesgo | Cómo aparece | Control candidato |
| --- | --- | --- |
| **Sobreajuste** | Ejes creados a medida de E01–E04 pero fallan en casos nuevos | Casos retenidos y adversariales |
| **Inflación de familias** | Cada variación gana un E-xx nuevo | Triaje incremental, especializaciones cuando proceden |
| **Colapso de familias** | Todo se denomina E01 o E03 | Pruebas de no-colapso y relaciones constitutivas |
| **Circularidad** | «Es E01 porque es enseñanza particular» | Describir estructura y necesidad antes del nombre |
| **Confusión persona–escenario** | Aprendiz con varias experiencias recibe una sola etiqueta | Unidad de análisis: episodio/relación |
| **Confusión función–Role** | «Docente» o «especialista» se promueven como Role automáticamente | Mantener observación separada de interpretación |
| **Confusión acceso–autoridad** | Publicar/exportar implica permiso pedagógico o legal | Revisar F07/F08/F11/O7 |
| **Clasificar = soportar** | Casos asignados se cuentan como funcionalidades disponibles | Matriz de necesidades y evidencia por alcance |
| **Herencia de garantías** | Base cubierta implica especializaciones cubiertas | Reexaminar diferencias y restricciones |
| **Composición ingenua** | Dos escenarios cubiertos implican combinación cubierta | Examinar conflictos e interdependencias |
| **Homonimia con F10** | Se adoptan dos «escenarios especializados» sin distinguir nivel | Vocabulario separado y enlaces a concepto vigente |
| **Sesgo de plataforma** | Usuarios indirectos son invisibles | O9 y relación con TDidacta como atributo independiente |
| **Sesgo institucional** | Un organigrama explica toda relación educativa | F11: funciones y facultades contextualizadas |
| **Asimilación editorial** | El caso D/M fuerza a inventar aprendices | Conservar fragmento de proceso y desconocimiento |
| **Mercadotecnia sin evidencia** | Matriz de cobertura convertida en promesa de eficacia | Afirmaciones acotadas, contraevidencia y fechas |
| **Carga de clasificación excesiva** | Cualquier ejemplo exige estudio completo | Filtro liviano, profundización por gatillos |
| **Deriva documental** | Antiguo E05 se reutiliza borrando significado original | Mapa de migración, enlaces históricos y decisiones fechadas |

## 24. Conexiones con metodologías externas — analogías verificables, no adopciones

Estas referencias ayudan a estructurar preguntas de investigación; **no validan el modelo de TDidacta ni autorizan agregar fundamentos**:

- **[Nickerson, Varshney y Muntermann, 2013](https://doi.org/10.1057/ejis.2012.26):** la construcción iterativa de una taxonomía debe explicitar objeto, dimensiones y criterios de término. **Tensión:** su enfoque taxonómico no obliga a TDidacta a usar una sola característica por eje si aquí lo apropiado resulta ser un esquema por facetas/relaciones.
- **[W3C PROV Overview](https://www.w3.org/TR/prov-overview/) / [PROV-O](https://www.w3.org/TR/prov-o/):** distinguen entidades, actividades y agentes para describir procedencia; sirve como analogía para impedir que «autor», «recurso», «actividad» y «usuario» se mezclen. No importar PROV ni su clase de Role como Roles de TDidacta.
- **[ISO/IEC/IEEE 29148:2018](https://www.iso.org/standard/72089.html):** antecedente de trazabilidad de necesidades/requisitos y distinciones entre verificación y validación. No sustituye investigación educativa ni certificación legal.
- **[SEI/CMU — Towards a Theory of Assurance Case](https://insights.sei.cmu.edu/documents/1222/2012_005_001_28161.pdf):** propone razonar mediante afirmaciones, argumentos y evidencia. Una clasificación de cobertura no se vuelve una demostración por dibujarla en notación de aseguramiento.
- **[W3C PROV Primer](https://www.w3.org/TR/prov-primer/):** útil para ejemplos narrativos de cadenas de procedencia, manteniendo diferenciado el resultado de una actividad de la persona que participó en ella.

**Límite de verificación de antecedentes:** los enlaces citados respaldan su orientación general y existencia. Las hipótesis sobre E01–E06 y sobre cómo medir cobertura son elaboración exploratoria propia, no resultados extraídos de esas fuentes.

## 25. Entregable mínimo recomendado para una revisión futura

Si el bootstrap vuelve sobre esta idea, en lugar de diseñar inmediatamente un framework de clasificación, preparar **un contraste documental breve y refutable** que responda:

1. ¿Se ha fijado una unidad de análisis inequívoca y compatible con episodios simultáneos?
2. ¿Se conocen relaciones constitutivas mínimas de cada familia candidata?
3. ¿Las facetas explican los casos sin sobreajuste ni proliferación?
4. ¿Los casos D/M se representan honestamente sin inventar enseñanza observada?
5. ¿Se distinguen especialización, composición, intersección y transferencia?
6. ¿Puede una especialización fallar requisitos críticos aunque su base esté cubierta?
7. ¿La división E02/comunitario y migración E05 orientado a metas conservan historia y contribuciones?
8. ¿Se puede publicar una afirmación de alcance con necesidades, evidencia y límites, sin hablar de eficacia no probada?
9. ¿Se justifica mantener esta clasificación como herramienta documental o hace falta una investigación separada con evidencia externa?
10. ¿Qué observación falsaría la elección finalmente recomendada?

**Decisión de continuidad:** no desarrollar ahora el modelo hasta cerrar su semántica completa; conservar esta extensión como espacio de hipótesis, avanzar con las necesidades y Responsibilities del bootstrap y decidir al cierre si corresponde adoptarla parcialmente, investigarla aparte o descartarla. No transformar el anexo en nueva puerta obligatoria del trabajo de escenarios.
