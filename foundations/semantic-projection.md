# Proyección semántica — facultad transversal y especialización pedagógica

**Estado (2026-10-16):** **decisión conceptual expresa del fundador** de reconocer la proyección semántica como facultad común a los proyectos derivados de PResolver. **Pendiente de formalización/adopción en el canon de PResolver**, contrastación entre dominios y especificación del mecanismo particular de TDidacta. Esta página preserva la decisión y propone una lectura conceptual; no afirma validación empírica ni compatibilidad entre implementaciones.

## Significado declarado

La **proyección semántica** es la facultad de transformar **semántica documentada** en una **representación intermedia estructurada**, utilizable por sí misma o en combinación con otras representaciones, y de emplearla después en proyecciones especializadas según el dominio.

Esquema explicativo:

```text
Documentación con semántica explícita
            |
      codificación (encode)
            v
Representación/es intermedia/s
            |
  utilización individual o combinada
            |
      decodificación (decode)
            v
Proyecciones del dominio
```

«Encode» y «decode» describen **funciones conceptuales**, no la selección de un códec, formato técnico ni garantía de reconstrucción bit a bit. La salida no necesita reproducir literalmente la entrada. La cuestión crítica es **qué significado, relaciones, condiciones e incertidumbres se preservan, transforman, pierden o incorporan** y cómo pueden revisarse esas diferencias.

## Lectura de responsabilidades por nivel

- **PResolver — facultad transversal confirmada por el fundador:** capacidad general de proyectar semántica documentada mediante representaciones intermedias hacia usos propios de cada dominio. Su pertenencia conceptual a la familia **está expresamente confirmada**; los invariantes generales, límites y pruebas de aplicabilidad aún deben investigarse en el lugar canónico de PResolver.
- **Orientación (lectura propuesta):** favorecer que conocimiento documentado sea transformable, reutilizable y proyectable sin perder silenciosamente su continuidad. La orientación expresa el **para qué / compromiso**, no codifica la operación.
- **Fundamento (lectura propuesta):** definición de la facultad y de las distinciones entre documentación, representación intermedia, combinación y proyecciones del dominio. Expresa el **qué es**.
- **Mecanismos:** operaciones concretas de documentación/codificación, composición y decodificación o realización, potencialmente distintas en cada especialización. Expresan **cómo ocurre** dentro del dominio.
- **Estructuras:** las representaciones intermedias concretas de cada dominio y sus reglas, sin presumir un esquema universal compartido.

Que una idea aparezca en orientación y fundamentos **no es duplicación de su definición**: la orientación puede reconocer un compromiso de continuidad y el fundamento poseer el significado conceptual. Esto es una **propuesta de distribución de autoridad**, no un cambio universal adoptado para todos los flavors.

## Especialización en TDidacta (T04)

- **Entrada:** Docs Standard documenta intenciones pedagógicas, subdivisiones, **situaciones válidas** y relaciones entre intenciones, distinguiendo lo que se pretende enseñar de las condiciones donde se enseña.
- **Codificación:** [proyección documental a representación intermedia](../mechanisms/document-to-intermediate-projection.md), con posible asistencia de IA sin transferir autorización.
- **Representación:** [estructura de TDidacta](../structures/tdidacta-intermediate-representation.md), preferentemente una unidad semántica por intención, asociable a varias situaciones y vinculable con otras intenciones. No requiere archivo único.
- **Proyecciones de salida:** exploraciones y realizaciones pedagógicas, que pueden ser generadas con LLM y deben considerar **tanto las condiciones de la intención como las de la situación aplicable**, además de las relaciones pertinentes entre intenciones.

```text
Docs Standard
  intenciones + subdivisiones + situaciones + relaciones
              |
       encode / proyección
              v
   IR pedagógicas relacionadas
              |
     uso individual o combinado
              |
         decode / uso
              v
  exploraciones y realizaciones según dominio y situación
```

No se presupone que una IR **contenga resultados pedagógicos ya logrados**, que una generación asegure conformidad o aprendizaje, ni que todo uso de la IR requiera LLM.

## Distinciones críticas

1. **Proyección semántica ≠ interpretación asistida de fuentes (T02).** T02 interpreta materiales educativos; T04 proyecta documentación ya formulada de intenciones, situaciones y relaciones hacia IR. El mecanismo detallado de T02 sigue pospublicación de PResolver.
2. **Proyección semántica ≠ clasificación de evidencia (T03).** T03 diferencia respaldo, inferencias e incertidumbre; puede informar la revisión de proyecciones, pero no constituye la transformación misma.
3. **Proyección semántica ≠ conformidad semántica (T15).** Proyectar no demuestra preservar lo exigido; esa comprobación requiere criterios propios.
4. **Composición de IR ≠ fusión indiscriminada.** Combinar representaciones necesita conservar identidad, relaciones y contextos; las reglas de composición aún no están definidas.
5. **Generalidad declarada ≠ contrato técnico universal.** La decisión transversal no demuestra que todos los dominios compartan codificador, formato, decodificador o garantías.

## Cuestiones a investigar y formalizar

- Qué invariantes mínimos hacen reconocible la facultad entre VSlices, TDidacta, REvidentia y otros derivados.
- Si «proyección» denomina el recorrido completo, la operación de codificación, el uso de la IR o las tres cosas en niveles diferentes.
- Cómo distinguir transformación válida, pérdida semántica inevitable, ambigüedad y contenido nuevo aportado por IA.
- Cómo componer representaciones sin confundir una intención pedagógica con sus situaciones.
- Qué operaciones de salida son estrictamente «decode» y cuáles constituyen realización o exploración con elaboración adicional.
- Cómo controlar revisiones, versiones, conformidad y carga de trabajo humano.

**Plazo T04:** las tres especificaciones [documentación Docs Standard](../mechanisms/pedagogical-intent-documentation.md), [proyección documental](../mechanisms/document-to-intermediate-projection.md) e [IR pedagógica](../structures/tdidacta-intermediate-representation.md) deben definirse **antes del 31-10-2026**; esta nota no las sustituye.

**Referencias de autoridad:** [PResolver (ideas, entrada canónica)](https://github.com/vslices/ideas/blob/main/proyectos/p-resolver/README.md) · [PResolver (repositorio operativo)](https://github.com/the-alive-lab/presolver/blob/main/README.md) · [T04](human-pedagogical-contextualization.md). La declaración transversal procede de una decisión humana del fundador, **no de un estudio comparativo concluido**.
