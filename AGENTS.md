# Orientación para agentes — TDidacta

Este archivo orienta a agentes que leen o contribuyen al repositorio canónico **the-alive-lab/tdidacta**. No sustituye ni modifica las definiciones adoptadas.

## Orden de lectura según tarea

1. [README.md](README.md): identidad, estado y mapa general.
2. [orientation/README.md](orientation/README.md): propósito y alcance vigentes.
3. [governance/README.md](governance/README.md): autoridad, procedencia, estados y evolución.
4. Consultar **solo la superficie pertinente**: [foundations](foundations/README.md), [mechanisms](mechanisms/README.md), [relationships](relationships/README.md), [lifecycle](lifecycle/README.md), [products](products/README.md) o [bootstrap](bootstrap/README.md).
5. [llms.txt](llms.txt) ofrece un índice resumido, no una segunda fuente canónica.

## Criterios de trabajo

- Distinguir **definiciones vigentes**, **propuestas/hipótesis**, **evidencia/antecedentes** y **realizaciones**. La mera presencia de una idea en el repositorio no implica adopción.
- Identificar el problema y la responsabilidad antes de introducir conceptos, carpetas o estructuras nuevas. Revisar equivalentes existentes y preservar trazabilidad.
- No asumir que Method, Design, Docs Standard, Framework y Platform son una arquitectura definitivamente validada: son una familia provisional de responsabilidades abiertas.
- No convertir TDIR, un prototipo de Teaching o una lección en requisitos universales del sistema.
- No reconstruir la historia solo desde interpretaciones actuales: consultar [bootstrap](bootstrap/README.md), sus fuentes y el historial cuando importe el origen.
- No editar retrospectivamente evidencia o artefactos históricos para acomodarlos a interpretaciones posteriores.
- Diferenciar una modificación documental, una propuesta de cambio y la **adopción** de una decisión. No declarar aprobado lo que aún requiera autoridad humana.
- Al modificar un documento, revisar su estado y enlaces; actualizar índices afectados y registrar justificación/procedencia cuando corresponda.
- Redactar primordialmente en español, sin excluir otros idiomas, conforme a la orientación vigente.
- Evitar cargar indiscriminadamente todo el repositorio: seleccionar rutas pertinentes a la tarea.

## Extensión y evolución de la estructura documental

Cuando una tarea implique crear, extender significativamente o reorganizar documentos o estructuras de TDidacta, incluso si la solicitud no menciona reglas externas:

1. Reconstruir primero las definiciones, responsabilidades y convenciones existentes en este repositorio.
2. Consultar las [Project Generation Rules](https://github.com/the-alive-lab/project-generation-rules), especialmente las [reglas de fundamentación](https://github.com/the-alive-lab/project-generation-rules/blob/main/rules/project-foundation.md), las [reglas de descubrimiento](https://github.com/the-alive-lab/project-generation-rules/blob/main/rules/human-and-agent-discovery.md) y la [guía de evolución](https://github.com/the-alive-lab/project-generation-rules/blob/main/guides/evolution.md).
3. Preferir extender una superficie existente antes de introducir nuevos conceptos, documentos o carpetas; justificar las responsabilidades realmente diferentes.
4. Preservar procedencia, estados, enlaces y navegación de las superficies afectadas.

**Autoridad:** la consulta es una orientación operativa para descubrir criterios compartidos, no una adopción normativa automática de las Project Generation Rules. Si hubiera diferencias, prevalecen las definiciones canónicas y decisiones explícitas de TDidacta.

## Límites entre repositorios

- **Definiciones de TDidacta:** este repositorio.
- **Investigación y evidencia:** [vslices/research-space](https://github.com/vslices/research-space), con sus protocolos propios.
- **Implementación histórica de Teaching:** [HernanFAR/teaching](https://github.com/HernanFAR/teaching).
- **Referencias editoriales compartidas:** [Project Generation Rules](https://github.com/the-alive-lab/project-generation-rules) y [Visualization Rules](https://github.com/the-alive-lab/visualization-rules). Son referencias, **no normas adoptadas automáticamente**.

No modificar otros repositorios, publicar nuevas definiciones ni promover resultados investigativos sin autorización para la operación concreta.

## Antes de entregar

Comprobar consistencia entre el cambio y la documentación canónica vigente; distinguir claramente lo propuesto de lo adoptado; validar rutas y enlaces modificados, y describir archivos/decisiones afectados. Este repositorio es principalmente documental: no inventar comandos de build, tests o pipelines inexistentes.
