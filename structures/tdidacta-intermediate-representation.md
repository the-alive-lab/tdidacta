# Representación intermedia de TDidacta — requisitos estructurales candidatos T04

**Estado:** responsabilidad estructural reconocida por el fundador; **especificación pendiente de elaborar antes del 31-10-2026**. No constituye todavía un esquema, estándar de archivos, contrato de compatibilidad ni TDIR estabilizado.

**Superficie de producto elegida:** [TDidacta IR Specification](../products/ir-specification/README.md). Este archivo conserva antecedentes y requisitos de T04, no constituye una especificación paralela ni el destino canónico de un contrato terminado.

## Propósito

Representar de manera estructurada las necesidades de **cada intención pedagógica** y de las **situaciones válidas** en que esa intención puede explorarse o realizarse. La representación sirve de intermediaria entre documentación comprensible mediante Docs Standard y mecanismos que preparan o ejecutan realizaciones y exploraciones.

## Unidades y distinciones acordadas

- **Intención pedagógica:** significado, propósitos, condiciones, restricciones y subdivisiones correspondientes; representa **qué** se pretende favorecer.
- **Situación pedagógica:** contexto/s particulares de uso; representa **dónde, para quién y en qué condiciones** se aplica una intención.
- **Vínculo intención–situaciones:** una intención **puede tener múltiples situaciones válidas**; una situación no debe redefinir silenciosamente la intención.
- **Continuidad entre intenciones:** la unidad estructural preferida es **una representación por intención**, con posibilidad de subdivisiones y referencias entre ellas.
- **Independencia del archivo físico:** una representación no debe confundirse con un archivo único; pueden existir varios archivos u otro soporte.

Los campos, cardinalidades adicionales, referencias, tipos, invariantes, gramática y validaciones quedan **pendientes de especificación**; la relación con el nombre histórico/provisional **TDIR** debe comprobarse, no darse por resuelta.

## Condiciones para especificar antes del deadline

1. Preservar significado y condiciones materiales de la intención documentada.
2. Preservar la diferencia entre intención y cada situación válida, incluidas variaciones permitidas y restricciones.
3. Dar soporte a exploraciones y realizaciones sin imponer una modalidad única.
4. Permitir detectar ambigüedades, pérdidas y conflictos de proyección sin atribuir inferencias de IA a la documentación humana.
5. Evitar multiplicación artificial de documentos y carga de edición para la persona responsable.
6. Proponer pruebas de consistencia y conformidad sin afirmar resultados previos.

## Fronteras

[Docs Standard](../mechanisms/pedagogical-intent-documentation.md) es la superficie documental de intención y situaciones; [Abstracción](../mechanisms/document-to-intermediate-projection.md) transforma esa documentación en estructura; esta definición **no** determina su implementación, almacenamiento o autoridad pedagógica. La revisión humana, autorización, procedencia y validación detallada siguen separadas (T05/T06/T08/T09/T15).

**Situación institucional:** puede representarse como contexto sin exigir aprobaciones institucionales multinivel en el alcance actual.
