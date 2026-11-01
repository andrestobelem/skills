# Development with coding agents

## English

### Purpose

This workflow turns the repository direction into action. It uses the alignment model from Jim Collins: preserve the purpose and core values, correct misalignments, and create concrete mechanisms that support progress.

### Role of each document

| Document | Role in development | Change policy |
| --- | --- | --- |
| `CONSTITUTION.md` | Defines mandatory governance and resolves conflicts between other guidance. | Change only through an explicit governance change. |
| `MISSION.md` | Defines why the repository exists and the work that it serves. | Keep stable. Change only if the fundamental purpose changes. |
| `VALUES.md` | Defines the timeless principles that guide decisions and behavior. | Do not change to justify a temporary practice. Change only if a value was defined incorrectly. |
| `VISION.md` | Defines the future state that the repository works to create. | Review when the repository reaches the vision or when its environment changes materially. |
| `DEVELOPMENT.md` | Defines the current practices that align daily work with the other documents. | Improve when evidence shows a better practice. |
| `AGENTS.md` | Gives coding agents direct repository instructions and activates this workflow. | Update when agents need a clearer or stronger operating instruction. |

Purpose and values are stable. Practices, tools, structures, and procedures must remain open to change. Do not treat a familiar practice as a core value.

### Alignment workflow

For each change, the coding agent must complete these steps:

1. **Orient:** Read the constitution, mission, values, vision, this workflow, and the applicable skill files.
2. **Frame:** State the requested outcome, the applicable constraints, and the value that the change must support.
3. **Check alignment:** Confirm that the plan supports the mission, moves toward the vision, follows the values, and complies with the constitution.
4. **Implement:** Make the smallest complete change that produces the requested outcome.
5. **Verify:** Run relevant checks and compare the result with the definition of done.
6. **Inspect for misalignment:** Identify any rule, practice, or artifact that obstructs the mission or contradicts a value. Correct it when it is in scope. Otherwise, report it.
7. **Record:** Create an atomic Conventional Commit with a scope. Report the result and the checks that ran.

### Decision order

When guidance conflicts, use this order:

1. Constitution
2. Mission and values
3. Vision
4. Development practices
5. Task-specific conventions

A higher item defines the constraint. A lower item defines how to work within that constraint. A coding agent must not change a higher item only to make a lower-level task easier.

### Alignment mechanisms

The repository uses these concrete mechanisms:

- `AGENTS.md` requires every coding agent to use this workflow.
- Every skill has aligned English and Spanish versions.
- English content follows ASD Simplified Technical English (ASD-STE100).
- Each commit is atomic and uses Conventional Commits with a scope.
- Verification includes tests or checks that are relevant to the change.
- The final report identifies completed checks and unresolved misalignments.

Automate these mechanisms when the repository has a reliable way to do so. Automation supports a value or purpose. It is not a value by itself and can change.

### Definition of done

A change is complete only when:

- It serves the mission and does not conflict with the constitution or values.
- It makes a clear contribution to the requested outcome and the vision.
- English and Spanish skill content has the same intent and requirements.
- Relevant tests and checks pass.
- Documentation reflects changed behavior.
- The commit is atomic, scoped, and does not attribute work to an agent.
- Known misalignments are corrected or reported.

### Alignment review

Review the operating system periodically. Do not rewrite the statements as a routine exercise. Instead, ask:

- Which current practices contradict our values or obstruct our mission?
- Which mechanisms do not produce the intended behavior?
- Which new mechanism would make correct behavior easier to verify?
- Which practice has become obsolete and must change or be removed?
- What evidence shows progress toward the vision?

## Español

### Propósito

Este flujo de trabajo convierte la orientación del repositorio en acciones. Usa el modelo de alineación de Jim Collins: preservar el propósito y los valores fundamentales, corregir desalineaciones y crear mecanismos concretos que impulsen el progreso.

### Función de cada documento

| Documento | Función en el desarrollo | Política de cambio |
| --- | --- | --- |
| `CONSTITUTION.md` | Define el gobierno obligatorio y resuelve conflictos entre otras pautas. | Cambiar solo mediante un cambio de gobierno explícito. |
| `MISSION.md` | Define por qué existe el repositorio y el trabajo al que sirve. | Mantener estable. Cambiar solo si cambia el propósito fundamental. |
| `VALUES.md` | Define los principios atemporales que guían las decisiones y el comportamiento. | No cambiar para justificar una práctica temporal. Cambiar solo si un valor fue definido de forma incorrecta. |
| `VISION.md` | Define el estado futuro que el repositorio busca crear. | Revisar cuando el repositorio alcance la visión o cuando su entorno cambie de manera sustancial. |
| `DEVELOPMENT.md` | Define las prácticas actuales que alinean el trabajo diario con los demás documentos. | Mejorar cuando la evidencia muestre una práctica mejor. |
| `AGENTS.md` | Da instrucciones directas a los agentes de código y activa este flujo de trabajo. | Actualizar cuando los agentes necesiten una instrucción operativa más clara o firme. |

El propósito y los valores son estables. Las prácticas, herramientas, estructuras y procedimientos deben permanecer abiertos al cambio. No se debe tratar una práctica conocida como un valor fundamental.

### Flujo de alineación

Para cada cambio, el agente de código debe completar estos pasos:

1. **Orientarse:** Leer la constitución, la misión, los valores, la visión, este flujo de trabajo y los archivos de habilidades aplicables.
2. **Enmarcar:** Indicar el resultado solicitado, las restricciones aplicables y el valor que el cambio debe respaldar.
3. **Comprobar la alineación:** Confirmar que el plan respalde la misión, avance hacia la visión, siga los valores y cumpla la constitución.
4. **Implementar:** Hacer el cambio completo más pequeño que produzca el resultado solicitado.
5. **Verificar:** Ejecutar las comprobaciones pertinentes y comparar el resultado con la definición de terminado.
6. **Buscar desalineaciones:** Identificar cualquier regla, práctica o artefacto que obstaculice la misión o contradiga un valor. Corregirlo cuando esté dentro del alcance. De lo contrario, informarlo.
7. **Registrar:** Crear un Conventional Commit atómico y con alcance. Informar el resultado y las comprobaciones ejecutadas.

### Orden de decisión

Cuando las pautas entren en conflicto, usar este orden:

1. Constitución
2. Misión y valores
3. Visión
4. Prácticas de desarrollo
5. Convenciones específicas de la tarea

Un elemento superior define la restricción. Un elemento inferior define cómo trabajar dentro de esa restricción. Un agente de código no debe cambiar un elemento superior solo para facilitar una tarea de nivel inferior.

### Mecanismos de alineación

El repositorio usa estos mecanismos concretos:

- `AGENTS.md` exige que cada agente de código use este flujo de trabajo.
- Cada habilidad tiene versiones alineadas en inglés y español.
- El contenido en inglés cumple con el Inglés Técnico Simplificado de ASD (ASD-STE100).
- Cada commit es atómico y usa Conventional Commits con un alcance.
- La verificación incluye las pruebas o comprobaciones pertinentes para el cambio.
- El informe final identifica las comprobaciones completadas y las desalineaciones no resueltas.

Estos mecanismos deben automatizarse cuando el repositorio disponga de una forma confiable de hacerlo. La automatización respalda un valor o propósito. No es un valor en sí misma y puede cambiar.

### Definición de terminado

Un cambio está completo solo cuando:

- Sirve a la misión y no entra en conflicto con la constitución ni con los valores.
- Contribuye de forma clara al resultado solicitado y a la visión.
- El contenido de las habilidades en inglés y español tiene la misma intención y los mismos requisitos.
- Las pruebas y comprobaciones pertinentes se completan correctamente.
- La documentación refleja los cambios de comportamiento.
- El commit es atómico, tiene alcance y no atribuye el trabajo a un agente.
- Las desalineaciones conocidas se corrigen o se informan.

### Revisión de alineación

Revisar periódicamente el sistema operativo. No reescribir las declaraciones como un ejercicio rutinario. En su lugar, preguntar:

- ¿Qué prácticas actuales contradicen nuestros valores u obstaculizan nuestra misión?
- ¿Qué mecanismos no producen el comportamiento previsto?
- ¿Qué mecanismo nuevo facilitaría la verificación del comportamiento correcto?
- ¿Qué práctica quedó obsoleta y debe cambiarse o eliminarse?
- ¿Qué evidencia muestra el avance hacia la visión?

## Reference / Referencia

This workflow adapts the alignment concepts in Jim Collins, “Aligning Action and Values” (June 2000): <https://www.jimcollins.com/article_topics/articles/aligning-action.html>.

Este flujo adapta los conceptos de alineación de Jim Collins, «Aligning Action and Values» (junio de 2000): <https://www.jimcollins.com/article_topics/articles/aligning-action.html>.
