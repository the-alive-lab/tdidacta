# Auditoría transversal de cobertura — E01–E05 × Responsibilities (2026-10-21)

**Estado:** auditoría documental de consistencia funcional, **no** aprobación ni promoción oficial de Responsibilities, Roles o capacidades. Resultado basado en los cinco escenarios y fichas candidatas de `main` revisados el 2026-10-21. Las reconciliaciones posteriores en las fichas prevalecen en la lectura del estado de trabajo sin reescribir sus antecedentes históricos.

## Preguntas, criterio y límites

Se contrastan **30 necesidades vigentes**: E01 (6), E02 (4 tras la separación explícita de antiguas N5/N6 hacia E05), E03 (8), E04 (6), E05 (6). Para cada necesidad se distingue: **finalidad principal**, cooperación contextual, y **reserva**. «Cubierta funcionalmente» significa que existe una finalidad responsable inteligible para la necesidad, **no** que haya software, procedimientos, evidencia de eficacia o garantía jurídica.

Abreviaturas: **01a/b/c** = matizaciones de **T-R01** general; **05a/b** = matizaciones de **T-R05** general; **06/07** candidatas. **O/F** designan orientaciones o Foundations transversales, **no** Responsibilities adicionales.

## Matriz necesidad → finalidad y reserva

| Necesidad | Finalidad(es) principal(es) | Reserva / prueba discriminadora |
|---|---|---|
| **E01-N1** circunstancia individual y ajustes sin mutación silenciosa | **01b**, **01a**, **02** | Ajustar no equivale a autorizar; decidir qué varía y qué versión se conserva |
| **E01-N2** especializaciones como versiones autorizables | **01b/01a**, **02** | No toda especialización cambia la intención de origen; versionado autorizable sigue con detalle por justificar |
| **E01-N3** acceso vs autoridad pedagógica | **05a**, **02** | Permiso técnico o de consulta no crea autoridad semántica; O7 privacidad |
| **E01-N4** experiencias educativas paralelas | **03**, **01a** según finalidad; **06** solo si hay interdependencias | **Reserva explícita del escenario:** no está justificado requerir compartimentación técnica independiente |
| **E01-N5** uso asincrónico y autonomía | **03**, **05a** disponibilidad administrativa, **01b** adaptación situada | O9; disponibilidad técnica o conectividad universal no garantizadas |
| **E01-N6** minimización y protección de datos | **05a** al administrar acceso; **04** cuando hay apoderado; cada finalidad trata legítimamente sus datos | O7 transversal; no reducir toda protección a T-R05 |
| **E02-N1** formular intenciones sin experto institucional | **01a/01b**, **03**, **02** autorización cuando pertinente | Una persona puede ejercer finalidades distintas; competencia/calidad no garantizadas |
| **E02-N2** orientación directa/asistida, juicio humano | **01c**, **03** | Tecnología no recibe automáticamente facultad para decidir intenciones |
| **E02-N3** exploración, reflexión y autocomprobación | **03**, **01c** si orientación de enseñanza, **07** solo ante examen estructurado | Autocomprobación T-R03 ≠ evaluación profunda T-R07; no inferir estilos fijos |
| **E02-N4** continuar/cambiar/retomar | **03**, **05a** si media acceso | Autonomía sin mutación retroactiva de acuerdos/intenciones; O9/O10 pertinentes |
| **E03-N1** autoridad configurable sin jerarquía universal | **05b** configura, **02** autorización pedagógica, **06** coordinación si hay dependencias | F11: plantillas editables; **no** Roles/permisos universales |
| **E03-N2** coordinación/comunicación deliberativa | **06** si hay dependencias; **01c/03** para interacción educativa; **05b** configuración | Medio propio/externo no atribuye autoridad; gobierno institucional general excluido |
| **E03-N3** contribuciones/autoría ≠ autoridad | **01a/b**, **03/06** según aporte/contexto; **02** solo para autorización | F08/O5: procedencia y derechos **transversales**, no nueva Responsibility de atribución |
| **E03-N4** continuidad, versiones, reemplazos | **01a**, **02**, **06** cuando coordinación real, **05a** acceso | No reautorizar retroactivamente versiones; derechos y trazabilidad |
| **E03-N5** referencias curriculares/metas externas | **01a/01b**, **02** protección de intención | Autoridad de origen externo preservada; **no** certificación institucional por TDidacta |
| **E03-N6** variaciones por grupo/destinatarios | **01b**, **01a/02** ante nuevas versiones | Ajuste situado no implica autorización automática |
| **E03-N7** acceso/privacidad vs autorización | **05a**, **02**, **04** condicional | O7; capacidad de publicar no es legitimidad para hacerlo |
| **E03-N8** uso indirecto/continuidad | **05a**, **01a/b**, **03** aprendizaje, **06** solo si dependencias | O9/O10; no prometer conectividad ni integración técnica |
| **E04-N1** aprendiz, acompañante, apoderado | **03**, **01c**, **04** condicional, **02** si autorización | Autonomía progresiva y representación situada; legislación sin resolver globalmente |
| **E04-N2** enseñanza sin título ni IA obligatoria | **01a/b/c**, **03** | Capacidades/competencias especializadas no garantizadas |
| **E04-N3** orientación, exploración y revisión | **01c**, **01b/01a** ante cambios; **03**, **02** si nueva autorización | No hay pipeline obligatorio ni automatización soberana |
| **E04-N4** recursos materiales/tiempo/acceso/privacidad | **01b** barreras pedagógicas, **05a** accesos administrativos, **04** condicional | O7/O9; disponibilidad técnica y cumplimiento de menores no garantizados |
| **E04-N5** progreso y competencia ≠ certificado | **07** examen estructurado; **03** autocomprobación; **01c** feedback | Validez de instrumento pendiente en Research; autoridad acreditadora externa distinta |
| **E04-N6** continuidad ante cambio de acompañante/material/proveedor | **01a/b/c**, **02**, **03**, **05a/b**, **04** condicional | Elementos pedagógicos ≠ datos personales; portabilidad O13 solo posible orientación, no adoptada |
| **E05-N1** autonomía y compromisos comunitarios | **03**, **06** ante compromisos/dependencias | Usar recurso no crea obligación de participar; sin sanción automática |
| **E05-N2** aportes, autoría y continuidad | **01a/b**, **06** cuando coordinación, **02** autorización | F08/O5: contribución ≠ autoría ≠ autoridad; criterios comunitarios legítimos |
| **E05-N3** comunicación y deliberación modular | **03**, **01c**, **06** cuando dependencias, **05b** configuración | Proveedor externo no autoriza intenciones; módulo propio no prometido |
| **E05-N4** coordinar interdependencias | **06** | Puede decidir operaciones **solo dentro de delegación expresa**, incluso una sola persona; no absorbe 01/02/03/05 |
| **E05-N5** autoría, acceso, distribución, autorización | **02** autorización pedagógica; **05a** ejecución acceso/publicación; **06** coordinación condicional | Autorización de distribuir viene de derechos/facultades contextuales, **no** de T-R02 o permisos técnicos |
| **E05-N6** destinatarios externos indirectos | **01** elaboración, **02** autorización pedagógica, **05a** acceso/distribución operativa | O7/O9/O10; destinatarios no adquieren membresía ni compromisos automáticamente |

## Hallazgos de cobertura

1. **30/30 necesidades tienen al menos una finalidad identificable o un soporte normativo transversal.** Este número **no significa 30 funcionalidades realizadas**, cobertura probada ni ausencia de brechas técnicas o jurídicas.
2. **No se identifica una necesidad sin familia funcional** que obligue ya a crear una octava Responsibility. Tampoco se justifica crear una Responsibility independiente para comunicación, publicación, certificación externa, privacidad transversal o autoría por el simple hecho de que existan esas necesidades. Son problemas que atraviesan finalidades y facultades; su implementación puede requerir mecanismos especializados.
3. **E01-N4 no queda resuelta como requisito técnico.** El escenario explícitamente deja por justificar si se necesita separación técnica de procesos paralelos. La matriz solo localiza las finalidades pertinentes a la experiencia.
4. **E04-N6 conserva la candidata O13 de portabilidad**, todavía no adoptada. Esto es deuda de orientaciones/fundamentos y diseño, no prueba de que falte una Responsibility.
5. **E04-N5/T-R07 conserva deuda metodológica:** validez, fiabilidad, accesibilidad, dimensiones confundidas, diferenciación de evidencias y consecuencias. La reconciliación es **semántica**, no medición de competencias demostrada.
6. **Reglas externas** (derechos de autor, privacidad, apoderados, acreditación, autoridad curricular) no se convierten en responsabilidades exclusivas de TDidacta ni se consideran satisfechas automáticamente.

## Auditoría de solapamientos

| Frontera | Discriminador acordado | Resultado |
|---|---|---|
| **01a / 01b / 01c** | estructurar lo relativamente estable / adaptar lo situado / conducir enseñanza | **Matizaciones de T-R01 general**, no fases ni 3 Responsibilities |
| **01a / 06** | coherencia *interna* de intención / interdependencias *entre* trabajos, compromisos o decisiones | Distinguible incluso con un solo participante |
| **01c / 03** | orientar enseñanza / aprender | Una persona puede ejercer ambas finalidades |
| **01c / 07** | feedback para enseñar / caracterizar competencias mediante examen y evidencia | Finalidad diferente; tecnología o evaluador externo no es criterio definitorio |
| **03 / 07** | autocomprobación para aprender / evaluación estructurada de competencias | Puede existir autoevaluación T-R07, no necesariamente validada |
| **01 / 02** | formular, adaptar o enseñar / examinar y autorizar elementos pedagógicos | Una persona con facultades suficientes puede ejercer ambas |
| **02 / publicación** | autorización pedagógica / legitimidad para distribuir | Decisiones distintas, sin Responsibility nueva adoptada |
| **05a / 05b** | acceso y disponibilidad administrativa / configuraciones y flujos | **Matizaciones de T-R05 general** |
| **05 / 01b** | administrar acceso/configuración / responder pedagógicamente a barreras situadas | Frontera posterior prevalece sobre objetivo histórico amplio de T-R05 |
| **04 / 03** | representación legítima condicional / autonomía progresiva del aprendiz | Parentesco no da automáticamente representación |
| **06 / 02 y 05** | coordinación operativa dentro de delegación / autorización y administración según propias facultades | Dependencia urgente no amplía autoridad |
| **07 / decisiones derivadas** | producir evidencia/conclusiones / decidir enseñanza, trayectoria, acreditación o sanciones | Resultados circulan sin trasladar autoridad |

**Dictamen de duplicación:** no se detecta redundancia que justifique fusionar dos de las siete finalidades generales candidatas; tampoco se demuestra todavía que cada acción textual de ficha sea necesaria.

## Incoherencias y deuda editorial localizadas

**D1 — T-R05:** la sección inicial «Objetivo» y acciones iniciales atribuyen a T-R05 accesibilidad **material**; la «Reconciliación posterior — finalidad administrativa» (2026-10-21) redefine su objetivo como administración de recursos/configuraciones y deriva la respuesta pedagógica a barreras principalmente a **T-R01b**. El documento advierte la evolución pero un lector que solo lea arriba se confundirá. **No reescribir retrospectivamente**: preparar una ficha vigente consolidada o cabecera de precedencia tras aprobación.

**D2 — T-R07:** «Base estándar cuando se evalúa» podría sugerir dimensiones universalmente exigidas; precisión posterior la revoca: **la intención elige las obligatorias entre las habilitadas por T-R05b**, T-R03 pide otras habilitadas, T-R07 examina. Igual problema de lectura por secciones y «Estado: pendiente contraste E01–E05» previo al contraste ya realizado.

**D3 — Metadatos históricamente desactualizados:** `responsibilities/README.md` abre declarando «seis fichas» y «no se ha realizado todavía contraste E02–E05», aunque el contenido posterior registra siete finalidades candidatas y contraste realizado. Mantener trazabilidad, pero facilitar una **cabecera vigente**, sin borrar estados históricos.

**D4 — T-R06 lenguaje:** la ficha inicial caracteriza «experiencia educativa compartida»; la precisión posterior acepta **una sola persona** coordinando trabajos/interdependencias. Ajustar formulación vigente al adoptar, preservando origen de E05.

**D5 — T-R04:** preguntas antiguas sobre transversalidad/validación jurídica permanecen válidas como límites, mientras que la frontera de autonomía progresiva está precisada más abajo. Se requiere distinguir claramente qué quedó resuelto y qué sigue abierto.

**D6 — Estados de escenarios y notas:** textos anteriores pueden decir «E04-N5 abierta», «E05-N4 pendiente» o «T-R07 sin contraste». Son **marcas temporales**, no evidencia de que acuerdos posteriores no existan. Agregar índice vigente de precedencia; no alterar congelados/históricos.

**D7 — Semántica de decisión en T-R07:** la acción de «precisar dimensiones» no debe interpretarse como **imponer requisitos**: T-R07 concreta criterios y métodos para las dimensiones exigidas por intención u optadas por T-R03, siempre habilitadas. Esta ambigüedad requiere ajuste editorial posterior y/o prueba de frontera.

## Propuesta de consolidación, no decisión adoptada

**Catálogo funcional candidato (7 finalidades):** T-R01 enseñanza [a/b/c]; T-R02 protección y autorización pedagógica; T-R03 aprendizaje y autonomía; T-R04 representación y resguardo condicional; T-R05 administración de recursos/configuraciones [a/b]; T-R06 coordinación de interdependencias; T-R07 examen profundo de competencias.

**No adoptar todavía acciones completas ni pasar a Roles.** Orden recomendable: (1) reconocer el resultado de auditoría, (2) solucionar D1–D7 con cabeceras vigentes o ediciones prospectivas, sin borrar evidencia histórica, (3) contrastar la necesidad y suficiencia de cada acción candidata contra su finalidad, (4) solicitar aprobación expresa del catálogo funcional, (5) estudiar Roles situados por escenario.

**Decisiones reservadas al fundador:** promoción formal del catálogo, modificación de definición vigente y creación/adopción de O13. La auditoría no adopta por omisión.

## Material contrastado

- [E01](../scenarios/e01-ensenanza-particular.md), [E02](../scenarios/e02-aprendizaje-autodidacta.md), [E03](../scenarios/e03-educacion-institucional.md), [E04](../scenarios/e04-educacion-en-el-hogar.md), [E05](../scenarios/e05-aprendizaje-comunitario.md).
- [Índice de Responsibilities](../responsibilities/README.md), fichas [T-R01a](../responsibilities/tr-01a-planificacion-contextualizacion-pedagogica.md), [T-R01b](../responsibilities/tr-01b-contextualizacion-adaptacion-pedagogica.md), [T-R01c](../responsibilities/tr-01c-conduccion-ensenanza.md), [T-R02](../responsibilities/tr-02-proteccion-autorizacion-pedagogica.md), [T-R03](../responsibilities/tr-03-aprendizaje-retroalimentacion.md), [T-R04](../responsibilities/tr-04-resguardo-legal-aprendiz.md), [T-R05](../responsibilities/tr-05-gestion-acceso-recursos.md), [T-R06](../responsibilities/tr-06-organizacion-coherencia-pedagogica.md), [T-R07](../responsibilities/tr-07-evaluacion-profunda-competencias.md).
- [Consolidación transversal previa](2026-10-21-e01-e05-responsibilities-transversal-consolidation.md) y [bootstrap](tdidacta-v6-coverage-bootstrap.md).

**Conclusión:** cobertura funcional documental suficiente **con reservas** para preparar una versión candidata consolidada de las siete finalidades; **no** se ha verificado la eficacia, exhaustividad técnica ni cumplimiento, ni se ha aprobado catálogo o Roles.
