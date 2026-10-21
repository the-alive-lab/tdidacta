# T-R05 — Gestión de acceso a recursos

**Estado:** responsabilidad transversal **candidata**, derivada de E01 (2026-10-19); pendiente de reconciliación con el fundador y de contraste posterior con E02–E05. No asigna Actors ni Roles, ni prescribe implementación.

**Origen:** [E01 — Enseñanza particular y aprendizaje acompañado](../scenarios/e01-ensenanza-particular.md). **Marco:** [índice de Responsibilities](README.md).

## Objetivo

Asegurar que los recursos educativos puedan **accederse legítimamente, mantenerse disponibles y utilizarse bajo las condiciones materiales pertinentes** en cada contexto. Esta finalidad integra autorización de acceso, disponibilidad y accesibilidad material sin imponer un mecanismo técnico único.

## Acciones agrupadas por objetivo (candidatas)

1. **Gestionar las condiciones de acceso:** reconocer destinatarios y restricciones pertinentes, y delimitar cuándo un recurso puede consultarse, utilizarse o compartirse.
2. **Atender la disponibilidad de los recursos:** procurar que quienes deban utilizarlos puedan encontrarlos y consultarlos cuando corresponda, incluyendo situaciones asincrónicas.
3. **Atender la accesibilidad material:** reconocer y responder, de forma pertinente al contexto, a barreras de conectividad, medios o condiciones de uso, sin imponer un modo tecnológico obligatorio.
4. **Respetar los límites de privacidad y divulgación** al gestionar acceso, disponibilidad y modos de consulta.

Son acciones candidatas reconocidas por su **finalidad común**; no se separan en responsabilidades distintas solo por diferencias operativas.

## Necesidades de cobertura E01

- **N3:** Acceso diferenciado a materiales: principal.
- **N5:** Disponibilidad para consulta asincrónica y atención a las condiciones materiales de acceso: principal.
- **N6:** Proteger información personal mediante condiciones legítimas de acceso, consulta, uso y divulgación de recursos: principal en lo relativo al acceso a esa información, sin agotar toda la protección de datos.

## Frontera y cautelas

T-R05 comprende **tres dimensiones de un mismo objetivo**: acceso legítimo, disponibilidad efectiva y accesibilidad material. No equivale a autorización pedagógica de intenciones o versiones (T-R02), ni define ACL, cuentas, permisos técnicos, arquitectura de infraestructura o una función institucional. Las soluciones concretas pueden diferir entre escenarios; reconocer la labor no obliga a resolver toda barrera material ni garantiza disponibilidad absoluta.

## Precisión reconciliada con el fundador (2026-10-19)

El alcance de T-R05 **incluye expresamente las tres dimensiones**: (1) quién puede acceder legítimamente a los recursos; (2) que los recursos estén disponibles cuando deban consultarse; y (3) que las condiciones materiales permitan su uso, incluidas necesidades de consulta sin conexión cuando sean pertinentes. No se reduce a administrar autorizaciones de lectura. La forma de cumplirlo y sus límites operativos deberán contrastarse con otros escenarios.

## Cuestiones pendientes de reconciliación

1. ¿Qué acciones de acceso, disponibilidad y accesibilidad son esenciales en la definición transversal y cuáles son mecanismos específicos de Platform u otros medios?

**Continuidad:** la transversalidad de la definición es un criterio de construcción, todavía **no verificado en otros escenarios**. Las acciones no quedan promovidas como obligaciones universales por aparecer aquí.

## Reconciliación posterior — finalidad administrativa de T-R05 (2026-10-21)

**Criterio confirmado por el fundador:** T-R05 se entiende como **administración de recursos y configuraciones**. Su finalidad general es gestionar las condiciones administrativas y operativas que regulan el acceso legítimo a recursos y la configuración del trabajo en cada contexto, dentro de las facultades y restricciones aplicables. Se distinguen dos **matizaciones candidatas**:

- **T-R05a — Gestión de accesos y disponibilidad administrativa:** administrar quién puede acceder o intervenir legítimamente sobre recursos, y su habilitación, publicación operativa o retirada de disponibilidad en un contexto, según facultades pertinentes. No determina por sí misma autorización pedagógica.
- **T-R05b — Gestión de configuraciones:** administrar configuraciones contextuales y flujos de trabajo distintos de accesos, atendiendo necesidades y feedback legítimos; no reescribe intenciones ni altera unilateralmente sus autorizaciones.

**Frontera acordada:** resolver *por qué una persona no puede aprovechar pedagógicamente un recurso*, considerando tiempo, conectividad doméstica, medios, accesibilidad funcional o contexto, pertenece principalmente a **T-R01b — contextualización y adaptación pedagógica** cuando exige responder pedagógicamente a esas condiciones. T-R05a puede habilitar el acceso legítimo al recurso, pero no queda obligada a resolver barreras materiales o pedagógicas. T-R05b puede reconfigurar legítimamente un flujo operativo, sin asumir esa adaptación pedagógica. La disponibilidad técnica del servicio es una condición operativa que tampoco se atribuye automáticamente a T-R05a ni T-R01b.

**Evolución de criterio:** el objetivo y las acciones originales de esta ficha (2026-10-19), que incluían expresamente disponibilidad y accesibilidad material, y la factorización del 2026-10-20 que todavía preservaba ambas dimensiones en T-R05a, **son antecedentes históricos**. Esta reconciliación posterior restringe expresamente la *responsabilidad administrativa*; no niega O9 ni elimina la obligación transversal de reconocer barreras donde corresponda. El título y la enumeración originales anteriores se conservan como documentación de origen, no como alcance vigente cuando contradicen esta sección.

**Estado:** finalidad general y frontera acordadas; fichas específicas T-R05a/b, acciones completas, facultades, Roles y mecanismos siguen pendientes de formalización. [E04-N4](../scenarios/e04-educacion-en-el-hogar.md) permanece en contraste.
