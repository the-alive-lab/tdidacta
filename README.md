# TDidacta

**TDidacta es un sistema de enseñanza y aprendizaje** que busca facilitar experiencias para explorar, experimentar y desarrollar comprensión. Reconoce a quienes enseñan y aprenden como participantes activos, sin imponer una única trayectoria educativa.

Este repositorio conserva las **definiciones canónicas de TDidacta**. Las propuestas, la evidencia y las realizaciones se distinguen de las definiciones vigentes; no adquieren autoridad automáticamente.

## Ramificación conceptual de TDidacta

La siguiente es la **estructura de derivación propuesta** para organizar las definiciones sin duplicarlas. **Orientation, Foundations y Concepts** ya tienen documentos propios; **Escenarios dispone de cinco fichas de cobertura (E01–E05)**; **Responsibilities** se examina como catálogo transversal de labores necesarias; **Roles** y **Actors** se interpretan de manera situada. Las extracciones y sus correspondencias permanecen en revisión. El registro no equivale a adopción de una taxonomía o compromisos de implementación. El esquema no adopta nuevas carpetas ni modifica los fundamentos F01–F10 reconciliados.

| Superficie | Pregunta que responde | Límite de su definición |
| --- | --- | --- |
| **[Orientación](orientation/README.md)** | ¿Qué buscamos? | Expresa los objetivos y remite a fundamentos y escenarios; no los redefine. |
| **[Escenarios](scenarios/README.md)** *(registro candidato)* | ¿Qué situaciones debemos cubrir para cumplir lo que buscamos? | Describe condiciones y casos de cobertura; no repite roles ni responsabilidades. |
| **[Fundamentos](foundations/README.md)** | ¿Qué debemos hacer para cumplir lo que buscamos? | Expresa respuestas constitutivas de TDidacta a la orientación, sin definir exhaustivamente conceptos ni asignar obligaciones a roles. |
| **[Conceptos](concepts/README.md)** | ¿Cómo explicamos lo que hacemos? | Conserva los significados y distinciones semánticas a los que remiten los fundamentos. |
| **Responsabilidades** *(criterio transversal acordado; catálogo por reconciliar)* | ¿Qué labores necesarias identificamos que puedan reaparecer entre escenarios? | Define responsabilidades reutilizables sin presuponer que se asignen o ejecuten en todos los escenarios. |
| **Roles** *(interpretaciones pendientes)* | ¿Cómo interpreta TDidacta la participación de cada actor en este escenario? | Relaciona actores situados con responsabilidades transversales; no constituye identidad permanente ni duplica el catálogo. |

### Derivaciones y contraste de cobertura

```mermaid
flowchart TD
    O["Orientación<br/>¿Qué buscamos?"]
    S["Escenarios (candidato)<br/>¿Qué debemos cubrir?"]
    F["Fundamentos<br/>¿Qué debemos hacer?"]
    C["Conceptos<br/>¿Cómo lo explicamos?"]
    R["Responsibilities<br/>Labores transversales"]
    L["Roles<br/>Interpretación situada"]

    O -->|justifica| F
    O -->|delimita cobertura| S
    F -->|origina o amplía| C
    S -->|evidencia necesidades de labores| R
    S -->|actores situados| L
    R -->|responsabilidades reutilizables| L
    C -.->|vocabulario interpretativo| R
    C -.->|vocabulario interpretativo| L
    R -.->|contrasta suficiencia| F
    S -.->|contrasta suficiencia| F
```

**Regla principal: definir una vez y referenciar después.** Orientación no reproduce el detalle de Fundamentos o Escenarios; Fundamentos remite a Conceptos sin duplicar definiciones; Escenarios aporta contexto para interpretar conjuntamente Roles y Responsibilities. Las conexiones son trazabilidad conceptual, no un proceso obligatorio ni una estructura de directorios adoptada.

**Los escenarios también contrastan los fundamentos.** Si una situación que debemos cubrir revela una omisión, tensión o insuficiencia de algún fundamento, se documenta el hallazgo y se propone una revisión explícita: **no se crea ni modifica automáticamente un fundamento**. De esta forma, los escenarios comprueban cobertura además de contextualizar roles.

**Dos sentidos distintos de «escenario»:** la superficie candidata *Escenarios* describe **circunstancias o contextos donde se encuentra quien asume una responsabilidad**, y permite verificar qué debe cubrir TDidacta, qué roles aparecen y si los fundamentos son suficientes. En cambio, el concepto vigente [Escenario pedagógico](concepts/application-circumstances.md) describe las circunstancias para **aplicar una intención pedagógica** (tipos base y especializado, reconciliados en F10). Un contexto de ejercicio de responsabilidad no es necesariamente un escenario de aplicación de una intención: pueden relacionarse, pero no son el mismo concepto.

**Responsabilidad contextual no es Responsibilities:** [Responsabilidad contextual](concepts/contextual-responsibility.md) es un concepto del vocabulario aprobado mediante F11. **Responsibilities** registra y reconcilia labores **candidatas transversales** inicialmente extraídas de E01 y pendientes de contraste con otros escenarios; una responsabilidad puede aparecer en unos escenarios y no en otros. **Actors** identifica unidades semánticas participantes de un escenario específico. **Roles** expresa interpretaciones situadas de su participación y puede vincularlas con responsabilidades transversales. El concepto de **responsabilidad contextual** (F11) explica una configuración situada de cometidos y facultades, sin equivaler a una ficha transversal ni exigir una asignación automática a un Rol. Identificar una labor no significa asignarla ni demostrar su cumplimiento. Una extracción candidata no se convierte automáticamente en obligación universal, facultad concedida, hecho externo verificado o definición conceptual nueva.

**Governance no es Responsibilities:** [Gobernanza documental](governance/README.md) trata autoridad, procedencia y evolución de las **definiciones del proyecto**, no asigna por sí misma compromisos pedagógicos a participantes.

Los [escenarios de cobertura documentados](scenarios/README.md) incluyen enseñanza particular, aprendizaje autodidacta (independiente o acompañado), educación institucional, educación en el hogar y el candidato transversal de aprendizaje orientado a metas definidas fuera de TDidacta. Constituyen **registro de cobertura, no un compromiso de implementarlo todo desde el inicio**. Esta propuesta se revisará antes de retomar los [28 tópicos V6](notes/tdidacta-v6-coverage-bootstrap.md). La auditoría Foundations → Mechanisms queda pospuesta y la condición investigativa O3/F10 sigue pendiente. [Antecedentes y decisiones de cobertura](notes/2026-10-18-foundations-candidate-coverage-audit.md).

## Navegación

| Superficie | Qué encontrarás |
| --- | --- |
| [Orientación para agentes](AGENTS.md) | Cómo colaborar sin confundir fuentes, estados ni autoridad documental |
| [Índice para LLM](llms.txt) | Descubrimiento rápido de las fuentes canónicas y especializadas |
| [Orientación](orientation/README.md) | Propósito, problema abordado, alcance e idioma |
| [Escenarios de cobertura](scenarios/README.md) | Cinco fichas de cobertura (E01–E05), incluida una transversal candidata; actores locales, necesidades y preguntas pendientes; no es un plan de releases |
| [Foundations](foundations/README.md) | Conceptos reconocidos y definiciones candidatas |
| [Mechanisms](mechanisms/README.md) | Espacios delimitados y operaciones candidatas de exploración/realización |
| [Relationships](relationships/README.md) | Relaciones candidatas entre necesidades, intenciones, espacios y operaciones |
| [Lifecycle](lifecycle/README.md) | Coordinación recursiva candidata para abordar necesidades pedagógicas |
| [Productos](products/README.md) | Familia propuesta y responsabilidades todavía abiertas |
| [Transparencia](transparency/README.md) | Clasificación y atribución de recursos, anonimato y consentimiento; propuesta candidata |
| [Gobernanza documental](governance/README.md) | Autoridad, procedencia, evolución y diferencias entre canon, evidencia y propuestas |
| [Postulaciones y financiamiento](governance/funding-and-applications.md) | Cómo derivar abstracts y solicitudes fieles al canon |
| [Bootstrap](bootstrap/README.md) | Origen histórico en Teaching y evolución inicial |
| [Bootstrap operativo V6](notes/tdidacta-v6-coverage-bootstrap.md) | Seguimiento reutilizable de 28 tópicos, correspondencias y decisiones pendientes |
| [Notas externas](notes/external/2026-10-16-vslices-conceptual-correspondences.md) | Hipótesis de correspondencias con VSlices; no validadas |
| [Reglas de generación de proyectos](https://github.com/the-alive-lab/project-generation-rules) | Referencia transversal para estructura, descubrimiento humano y orientación de agentes; incluye [guía de creación](https://github.com/the-alive-lab/project-generation-rules/blob/main/guides/bootstrap.md) y [reglas de descubrimiento](https://github.com/the-alive-lab/project-generation-rules/blob/main/rules/human-and-agent-discovery.md) |
| [Reglas de visualización compartidas](https://github.com/the-alive-lab/visualization-rules) | Referencia editorial transversal de The Alive Lab; incluye [guía práctica](https://github.com/the-alive-lab/visualization-rules/blob/main/guides/application.md) y [entrada para agentes](https://github.com/the-alive-lab/visualization-rules/blob/main/AGENTS.md) |

## Estado

La estructura conceptual sigue **en elaboración**. Las definiciones candidatas de Foundations y Relationships, la familia de productos propuesta y posibles representaciones como TDIR no constituyen una arquitectura ni una metodología universal adoptadas.

Las revisiones deben respetar las fuentes, sus estados y las decisiones de promoción. Para detalles, consultar [gobernanza documental](governance/README.md).

## Visualización documental

Las [Visualization Rules de The Alive Lab](https://github.com/the-alive-lab/visualization-rules) sirven como **referencia compartida** para representar conceptos, relaciones, mecanismos y ciclos con claridad y fidelidad semántica. Incluyen [reglas editoriales](https://github.com/the-alive-lab/visualization-rules/blob/main/rules/document-visualizations.md), una [guía de aplicación](https://github.com/the-alive-lab/visualization-rules/blob/main/guides/application.md) y superficies para agentes ([AGENTS.md](https://github.com/the-alive-lab/visualization-rules/blob/main/AGENTS.md) y [llms.txt](https://github.com/the-alive-lab/visualization-rules/blob/main/llms.txt)).

Este enlace **no constituye una adopción normativa automática** ni cambia las definiciones canónicas de TDidacta. Cualquier aplicación concreta debe respetar la autoridad y el estado de los documentos de este repositorio, así como sus decisiones de promoción.

## Generación y evolución documental del proyecto

**Para extender o reorganizar este repositorio:** comenzar por [AGENTS.md](AGENTS.md), revisar las responsabilidades existentes y consultar las [Project Generation Rules](https://github.com/the-alive-lab/project-generation-rules) antes de proponer nuevas estructuras. Son referencias compartidas y no se adoptan automáticamente como normas de TDidacta.

Las [Project Generation Rules de The Alive Lab](https://github.com/the-alive-lab/project-generation-rules) son una **referencia transversal** para organizar proyectos, facilitar su reconocimiento por personas y agentes y conservar continuidad cuando evolucionan. Incluyen [reglas de fundamentación](https://github.com/the-alive-lab/project-generation-rules/blob/main/rules/project-foundation.md), [criterios de descubrimiento](https://github.com/the-alive-lab/project-generation-rules/blob/main/rules/human-and-agent-discovery.md), [guía de evolución](https://github.com/the-alive-lab/project-generation-rules/blob/main/guides/evolution.md) y entradas para agentes ([AGENTS.md](https://github.com/the-alive-lab/project-generation-rules/blob/main/AGENTS.md) y [llms.txt](https://github.com/the-alive-lab/project-generation-rules/blob/main/llms.txt)).

El vínculo constituye una **referencia, no una adopción normativa automática** ni una reestructuración de TDidacta. Las definiciones canónicas, la gobernanza y las decisiones específicas de este proyecto conservan su autoridad. TDidacta dispone de entradas propias para agentes ([AGENTS.md](AGENTS.md)) y descubrimiento por LLM ([llms.txt](llms.txt)); ambas enlazan las fuentes existentes sin duplicar ni redefinir el canon.
