# O8 — Externalización del reconocimiento de identidades personales

**Estado:** orientación de TDidacta aprobada por el fundador (2026-10-17). La instrumentación y eficacia operativa permanecen pendientes de diseño y contraste.

## 1. Propósito

TDidacta debe separar la gestión y autenticación de cuentas del **reconocimiento de la identidad personal** de quienes las utilizan.

Cuando una capacidad requiera establecer quién es una persona fuera del sistema, ese reconocimiento **debe corresponder a una autoridad o sistema externo pertinente**. TDidacta no asume como responsabilidad propia comprobar o certificar identidades personales.

La finalidad es habilitar capacidades educativas sin identificación personal innecesaria y evitar convertir TDidacta en autoridad central de identidades.

## 2. Identidad personal, identidad operativa y relación contextual

Se distinguen tres conceptos relacionados:

- **Identidad personal:** referencia a una persona cuyo reconocimiento corresponde a una autoridad externa pertinente. Una identidad personal puede estar asociada a **N identidades operativas**.
- **Identidad operativa:** identidad funcional mediante la cual se interactúa con TDidacta, por ejemplo mediante cuenta, identificador o credenciales. Puede existir sin que TDidacta conozca o compruebe la identidad personal correspondiente.
- **Relación contextual:** vínculo de una identidad operativa con un curso, recurso, actividad, institución u otro ámbito de participación. Una identidad operativa puede mantener **N relaciones contextuales**.

**Relación conceptual:** identidad personal → 0..N identidades operativas → 0..N relaciones contextuales por identidad operativa.

La cardinalidad expresa la posibilidad de múltiples asociaciones; **no exige a TDidacta almacenar ni reconstruir un registro global de personas y todas sus cuentas**. La asociación identidad personal–identidad operativa puede permanecer desconocida para TDidacta o limitarse a un contexto específico.

Las relaciones de una identidad operativa **no se propagan automáticamente** a otras identidades operativas que correspondan a la misma persona.

## 3. Cuentas sin identidad personal acreditada

TDidacta puede crear y administrar cuentas, credenciales y sesiones sin verificar la identidad personal de quien las utiliza.

Una identidad operativa puede disponer de seudónimo, identificador generado, uno o varios correos como medios de acceso, contraseña u otros elementos funcionales pertinentes.

**Autenticar una cuenta no equivale a acreditar identidad personal.** Asociar distintos medios de acceso tampoco certifica quién es la persona fuera del sistema.

## 4. Reconocimiento de relaciones contextuales

TDidacta puede gestionar participaciones, accesos y relaciones entre identidades operativas y elementos de su dominio.

Por ejemplo, una **invitación a un curso** puede permitir crear una cuenta o usar una ya existente y establecer el acceso al curso. Una invitación válida acredita el derecho de utilizar ese mecanismo de acceso según sus condiciones, **no la identidad personal de quien la presenta**.

La relación contextual puede ser suficiente sin identificación externa. Cuando un contexto requiera acreditar quién es la persona, esa función corresponde a una autoridad externa.

## 5. Externalización del reconocimiento personal

Cuando sea necesaria la identidad personal —por ejemplo en determinadas actividades de una institución educativa—, TDidacta debe apoyarse en el reconocimiento de la autoridad externa pertinente.

Puede relacionar una identidad operativa con una referencia externa **limitada a la finalidad y contexto necesarios**, sin tener que importar todos los datos personales disponibles ni transformar esa identidad contextual en identidad universal.

Esto **no exige externalizar la autenticación** ni impone un proveedor comercial, institucional o protocolo universal.

## 6. Independencia de identidad, acceso y autorización

Deben permanecer diferenciados:

- La autenticación de una identidad operativa.
- El reconocimiento externo de una identidad personal.
- La vinculación contextual entre ambas cuando corresponda.
- La participación y los permisos de TDidacta.
- La [autorización humana de decisiones pedagógicas](human-pedagogical-authorization.md).

Reconocer externamente quién es una persona puede contribuir a determinar quién actúa dentro de una institución, **pero no otorga por sí mismo autoridad pedagógica**. Esa consecuencia posible no es el propósito de O8.

## 7. Separación contextual y privacidad

Una identidad personal puede asociarse a diversas identidades operativas sin requerir que estas se fusionen o compartan automáticamente datos, permisos, actividades o relaciones.

La vinculación contextual debe justificarse por una necesidad específica. El reconocimiento externo no exime a TDidacta de sus obligaciones sobre los datos que sí trate.

## 8. Límites

Esta orientación:

- No exige acreditar identidad personal para crear una cuenta, iniciar sesión o utilizar recursos públicos.
- No prohíbe cuentas locales sencillas ni autenticación administrada por TDidacta.
- No presupone que un correo demuestre identidad personal.
- No convierte invitaciones o pertenencia a cursos en certificación de identidad.
- No exige un proveedor universal de identidad ni externalizar la autenticación.
- No impone una identidad operativa única por persona ni la propagación de relaciones entre cuentas.
- No convierte identidad personal reconocida en autorización pedagógica.
- No requiere almacenar una correspondencia global de identidades.
- No especifica mecanismos de autenticación, invitación o integración institucional.

## 9. Relaciones con otras orientaciones

- [O7 — Privacidad por diseño](privacy-by-design-and-data-minimization.md): evitar reconocimiento personal y datos asociados cuando no sean necesarios; limitar vínculos externos.
- [O9 — Accesibilidad contextual](contextual-access-and-educational-reach.md): no imponer acreditación de identidad externa para participar cuando basten cuentas sencillas, invitaciones o acceso sin cuenta.
- [O3 — Carga y capacidad humana](human-effort-and-agency.md): evitar trámites de identificación innecesarios.
- [O4 — Autorización humana](human-pedagogical-authorization.md): reconocimiento externo puede facilitar reconocer a quien actúa, pero no crea por sí solo facultades pedagógicas.

Su incidencia en Foundations y posibles tensiones deberá evaluarse fundamento por fundamento.

## 10. Evaluación

Contrastar si TDidacta puede gestionar cuentas sin identificación personal, reconocer relaciones contextuales, utilizar autoridad externa cuando una actividad requiera acreditar a una persona, limitar datos y preservar independencia entre autenticación, identidad personal y autorización.

Publicar la orientación no demuestra eficacia de los mecanismos.
