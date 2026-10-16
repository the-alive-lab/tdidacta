# Abstracción semántica — fundamento transversal

**Estado (2026-10-16):** separación conceptual aprobada por el fundador para la familia PResolver. Formalización en el canon de PResolver pendiente; no se afirma validación transversal ni implementación común.

## Definición

**Abstracción semántica:** acción de convertir **semántica documentada** en una **representación intermedia estructurada** que pueda ser utilizada individualmente o en combinación con otras representaciones.

```text
Documentación semántica -- encode / abstracción --> IR
```

«Encode» expresa la transformación conceptual, no exige un códec reversible ni un formato universal. El mecanismo particular debe identificar qué relaciones, restricciones, contexto y significado material debe preservar, y qué ambigüedades o pérdidas requieren revisión.

## Especialización en TDidacta

La entrada es documentación de TDidacta Docs Standard sobre **intenciones pedagógicas, subdivisiones, situaciones válidas y relaciones entre intenciones**. El mecanismo específico es [abstracción documental hacia IR](../mechanisms/document-to-intermediate-projection.md), pendiente de definición completa antes del 31-10-2026. Su salida debe atender a la [IR Specification](../products/ir-specification/README.md), sin asumir un archivo único ni que una situación reescriba silenciosamente la intención.

## Distinciones

- Abstracción **no** equivale a interpretar material educativo original mediante IA (T02).
- Abstracción **no** equivale a clasificar evidencia humana/inferencial (T03).
- Abstracción **no** equivale a generar exploraciones o realizaciones: eso corresponde a la [proyección semántica](semantic-projection.md).
- Una IR obtenida no se considera automáticamente conforme ni autorizada.

**Autoridad:** decisión del fundador sobre el concepto; su generalidad operativa y las garantías técnicas deben contrastarse desde PResolver. [Orientación tecnológica](../orientation/technology-enabled-semantic-continuity.md).
