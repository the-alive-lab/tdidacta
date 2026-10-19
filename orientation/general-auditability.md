# O11 — Auditoría general

**Estado:** orientación adoptada por aprobación expresa del fundador (2026-10-19). La revisión de incidencia O11→F01–F12 fue reconciliada; [F13](../foundations/general-auditability.md) y sus tres conceptos se promovieron después por **autorización expresa del fundador (2026-10-19)**. No implica adopción de mecanismos técnicos.

## Propósito

TDidacta debe permitir **reconstruir y examinar de forma fiable, comprensible y proporcional las actuaciones, decisiones y transformaciones relevantes de sus dominios**, incluidas sus condiciones de ejercicio y consecuencias conocidas, para facilitar rendición de cuentas, revisión de irregularidades, corrección y aprendizaje de lo ocurrido.

La orientación es **general y transversal**, no exclusiva de instituciones ni de Platform: cada dominio (pedagógico, organizativo o de los productos de TDidacta) determina qué actuaciones tienen relevancia y qué evidencia se justifica conservar.

## Dimensiones

1. **Reconstrucción de actuaciones:** reconocer qué ocurrió, cuándo, sobre qué y en qué contexto; considerar resultados exitosos, rechazados, fallidos o incompletos si su relevancia lo justifica.
2. **Atribución proporcionada:** reconocer actores, identidades operativas o procesos que intervinieron, preservando incertidumbres y sin imponer identidad personal innecesaria ni atribuir responsabilidad humana a la IA.
3. **Facultades y condiciones de ejercicio:** reconstruir, cuando importe, qué responsabilidades, facultades o condiciones eran aplicables en el momento de actuar. Una habilitación no equivale a autorización pedagógica de F07.
4. **Cambios y consecuencias:** examinar transformaciones en elementos, decisiones y configuraciones particulares, relaciones conocidas y efectos; sucesión temporal no demuestra causalidad.
5. **Examinabilidad y fiabilidad:** información comprensible por quienes estén legítimamente habilitados para examinarla; indicar carencias, incertidumbres o indicios de alteración en lugar de prometer evidencia perfecta.
6. **Proporcionalidad y protección:** justificar granularidad, acceso, tratamiento de datos, retención y eliminación según riesgo, finalidad y contexto; no transformar auditoría en vigilancia educativa generalizada.

## Acciones directas, indirectas y consultas

La relevancia auditable **no depende de que la acción cambie el estado de un elemento**. También puede abarcar consultas, lecturas y accesos relevantes —por ejemplo, a información sensible o a recursos restringidos— y actuaciones indirectas realizadas por procesos o intermediarios.

La determinación concreta de qué se audita se realiza según dominio, riesgo y contexto. **No se impone auditar toda interacción o consulta**, ni identificar personalmente a visitantes de recursos educativos públicos.

**Preferencia técnica del fundador, registrada sin formalizar como orientación:** considera deseable explorar un sistema donde toda acción directa o indirecta pueda auditarse. Esa hipótesis de cobertura exhaustiva queda para Design/Mechanisms y evaluación frente a O7, proporcionalidad y costos; **no es una exigencia canónica de O11**.

## Fronteras

- **O1 — Continuidad semántica:** conserva significado, intenciones y restricciones; O11 reconstruye actuaciones y condiciones de ejercicio, no sustituye la semántica pedagógica.
- **O5/F08 — Reconocimiento de aportes:** atribuir una contribución no es lo mismo que auditar una actuación.
- **F06/F07:** revisión, corrección, versiones inmutables y autorizaciones tienen significado propio; O11 puede examinar sus actuaciones sin redefinirlas.
- **F11:** responsabilidad contextual y facultad indican cometidos y habilitaciones; O11 no los crea ni prueba su cumplimiento.
- **O7/O8:** minimizar datos personales y distinguir identidad operativa de reconocimiento personal externo es obligatorio también para la auditoría.
- **O3/O6/F09:** preservar proporcionalidad del esfuerzo y autonomía de participación; evitar controles intrusivos o burocracia.
- No prescribe event sourcing, logs append-only, blockchain, registros inmutables indefinidos, alertas, formatos, controles criptográficos, ni un plazo universal de conservación.
- No es por sí misma certificación normativa, garantía de detección de todo abuso o demostración de integridad.

## Tensiones explícitas

- **Auditoría ↔ privacidad (O7):** evidencia suficiente versus minimización, anonimato contextual, retención y acceso restringido.
- **Auditoría ↔ esfuerzo (O3/O6):** utilidad de reconstrucción frente al costo de instrumentación, revisión y mantenimiento.
- **Auditoría ↔ autonomía (F09/F11):** rendición de cuentas sin vigilancia desproporcionada ni jerarquía universal.
- **Integridad ↔ rectificación/eliminación:** distinguir fiabilidad histórica de retención indefinida o resistencia a necesidades legítimas de corrección y supresión.

## Seguimiento

La incorporación de O11 requiere contrastar individualmente **F01–F12** e inventarios conceptuales, sin copiar automáticamente clasificaciones O→F a O→Concept. [Registro de contraste](../notes/2026-10-19-o11-foundations-impact-review.md).

La responsabilidad [F13](../foundations/general-auditability.md) y sus tres conceptos fueron promovidos mediante decisión expresa posterior del fundador (2026-10-19); no se han adoptado mecanismos de implementación.
