# Bootstrap — origen y evolución de TDidacta

**Naturaleza:** registro histórico y de procedencia, no definición normativa vigente ni especificación técnica.  
**Incorporación:** 2026-10-15.  
**Fuente editorial aprobada:** [TDidacta V6, master de preservación integral](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md).

## Continuación operativa — revisión de fundamentos y conceptos

La revisión secuencial de **F01–F07** y el procedimiento unificado para **O0–O10 → Foundations → Concepts** se mantienen en [**Reconciliación de Foundations y Concepts**](foundations-concepts-review.md).

Ese documento funciona como **handoff operativo e inventario de decisiones y pendientes**, no reemplaza las definiciones canónicas ni transforma el origen histórico conservado aquí en una norma universal. Distingue explícitamente la revisión ya realizada, los cierres comprobados, los pendientes puntuales de F01/F03 y la propuesta F08.

## Para qué existe

Este espacio conserva por qué y cómo surgió el sistema hoy llamado **TDidacta**, sin reinterpretar los documentos tempranos como si ya expresaran su identidad presente. Su contenido ayuda a reconstruir decisiones y permite que los antecedentes desafíen definiciones actuales. La autoridad conceptual vigente corresponde al [README principal](../README.md) y a futuras definiciones explícitamente adoptadas, no a este archivo por antigüedad.

La presencia de un antecedente en el bootstrap no convierte una motivación personal, una hipótesis investigativa o una característica de un prototipo en requisito universal.

## Motivación de origen — testimonio del fundador

Según la reconstrucción expresada por Hernán el 15 de octubre de 2026:

- Quería ayudar a su **hermana mayor** a estudiar programación de nivel intermedio y a su **hermana menor** a estudiar fundamentos de programación con **.NET**.
- La preocupación primordial no era únicamente explicarles contenidos personalmente: buscaba que pudieran **estudiar, explorar y avanzar de manera autónoma**, de acuerdo con necesidades diferentes, sin depender de su presencia constante.
- Identificaba también una dificultad de aprendizaje frecuente en experiencias universitarias: perder el foco cuando se introducen conceptos vecinos, abstracciones o conocimientos prematuros antes de comprender el problema que los justifica.
- Estas necesidades impulsaron las exploraciones iniciales de **Teaching** y motivaron el uso de intención pedagógica, límites, exclusiones y variabilidad, inspirándose históricamente en aproximaciones trabajadas en **VSlices**.

**Calidad de esta fuente:** testimonio retrospectivo del fundador, coherente con decisiones técnicas tempranas. No demuestra que las hermanas hayan participado en un estudio ni que la herramienta haya producido ganancias de aprendizaje.

## Antecedentes técnicos fechables

| Fecha | Registro | Alcance de la evidencia |
| --- | --- | --- |
| 2026-10-03 | [Inicialización de Teaching](https://github.com/HernanFAR/teaching/commit/40010e91246965954a797875a3c1e6bbff66b3a5) | Existencia del repositorio |
| 2026-10-03 | [Separación de fuente y realización](https://github.com/HernanFAR/teaching/commit/d14715f1766063147c39518653c7cae23446b218) | Distinción conceptual temprana |
| 2026-10-03 | [Reglas operativas de generación](https://github.com/HernanFAR/teaching/commit/38f6c019e7dcbb223e5c1879a4432dbcea7ff4a1) | Reglas iniciales de enseñanza/generación |
| 2026-10-04 | [Publicación de lección Clean Architecture](https://github.com/HernanFAR/teaching/commit/8c4d7d143c6e3abe25327a8aceab7cd91c148edc) | Existencia de una realización publicada, no culminación de toda la plataforma |

La fuente pedagógica vigente para ese caso se encuentra en [`docs/lessons/clean-architecture/generation-instructions.md`](https://github.com/HernanFAR/teaching/blob/main/docs/lessons/clean-architecture/generation-instructions.md). Explicita qué comprender, qué **no** enseñar todavía, una progresión causal, invariantes, variables, contrafactuales, límites y exploraciones. Su contenido actual no debe atribuirse íntegramente a la primera versión sin reconstruir el historial puntual del archivo.

## De Teaching a TDidacta

Como orientación de lectura histórica, y no como cronología exhaustiva:

```text
necesidad de enseñanza y aprendizaje autónomo
    -> exploraciones pedagógicas delimitadas
    -> primeras fuentes y realizaciones en Teaching
    -> investigaciones sobre continuidad y conformidad
    -> formalización progresiva del sistema TDidacta
```

**Teaching** es un antecedente real de la Platform, pero TDidacta **no equivale** al repositorio técnico ni a la lección de Clean Architecture. El hecho de que la exploración comenzara en programación tampoco restringe el dominio actual del sistema a ingeniería de software.

La V6 aprobada conserva la reconstrucción amplia, incluidos elementos investigativos, vías de autoría, realizaciones, exploraciones, evaluación, acceso, sostenibilidad y límites epistémicos. **No se replica íntegramente aquí**: se enlaza para evitar dos versiones potencialmente divergentes.

## Qué pertenece a otras superficies

- **Canon actual:** propósito, identidad y responsabilidades explícitamente adoptadas en este repositorio.
- **Investigación y evidencia:** [`vslices/research-space`](https://github.com/vslices/research-space), incluyendo la [V6 aprobada](https://github.com/vslices/research-space/blob/main/lines/educational-capacity-under-institutional-constraints/notes/learning-tools-competition-2027/notes/2026-10-15-tdidacta-master-v6-preservation.md), Studies, hipótesis y resultados con su propio estado.
- **Realización histórica:** [`HernanFAR/teaching`](https://github.com/HernanFAR/teaching), donde se consulta el código, contenido publicado e historial de commits.
- **Antecedentes conceptuales:** [`the-alive-lab/vslices`](https://github.com/the-alive-lab/vslices) para sus definiciones autorizadas; su relación histórica con Teaching no transfiere autoridad pedagógica.

## Regla de continuidad y promoción

1. Conservar referencias y fechas originales, distinguiendo testimonio, artefacto y reconstrucción.
2. Identificar la responsabilidad pedagógica que un antecedente podría informar.
3. Contrastar con las definiciones vigentes y con evidencia posterior.
4. Proponer por separado cualquier modificación canónica, con procedencia y aprobación explícita.
5. No transformar automáticamente las cinco superficies propuestas (Method, Design, Docs Standard, Framework, Platform) en estructura física por analogía con VSlices.

**Estado:** bootstrap histórico incorporado. La aprobación editorial de V6 no supone adopción en bloque de todas sus hipótesis como canon.
