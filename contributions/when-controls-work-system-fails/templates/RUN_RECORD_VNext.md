# VNext — UC-21 — Pre-run objective selection and outcome-to-objective trace in the execution record

> **Única VNext de este documento lógico; auditoría y propuestas, NO modificación incorporada.** La fuente, el paquete v0.9.3, el commit enlazado por FG-TIDA y el manifest SHA256 permanecen sin modificaciones. Estado: **revisión delimitada a trazabilidad de objetivos experimentales; propuesta pendiente de decisión e incorporación**. Fecha: 12 October 2026.

## 1. Fuente, identidad, revisión y límite

- **Documento de origen:** [templates/RUN_RECORD.md](RUN_RECORD.md) — [copia pública congelada](https://github.com/dakleyer/use-cases/blob/aec08fb5b0fac2ee399372370e9ee2a82a2d5779/contributions/when-controls-work-system-fails/templates/RUN_RECORD.md); rama viva de revisión `when-controls-work-system-fails-v0.9.3` del repositorio `dakleyer/use-cases`.
- **Corte del examen:** commit `5171c4a6ce7c1e2838c041a7365bd3698f820b24` en rama de contribución; blob original `be014eb521d0ede16697ad0f37b961c5eb562d63`, idéntico al documento fuente del commit de entrega `aec08fb5b0fac2ee399372370e9ee2a82a2d5779` según el cotejo realizado. No se han alterado estos blobs para elaborar este VNext.
- **Auditoría:** **UC21-OBJ-AUD-006** — realizada por **ChatGPT (GPT-6, OpenAI), AI assistant; not Iván Abril Palma, not Codex, and not an independent human/peer reviewer** el 12 October 2026. Modalidad: lectura y cotejo documental de GitHub, no experimento, no revisión humana independiente, no respuesta del fabricante, no certificación, no aprobación del Focus Group.
- **Alcance:** se revisa exhaustivamente la **relación con objetivos y claims** de UC-21 dentro de este documento y sus consumidores relevantes; no se declara completada una auditoría científica, jurídica o de implementación de todo el corpus.
- **Regla de método:** [procedimiento de auditoría y VNext del corpus](https://github.com/dakleyer/structural-awareness-contributions/blob/main/governance/CORPUS_REVIEW_PROCEDURE_2026-10-06.md) (disciplina de revisión aplicada a este paquete sin pretender sustituir su fuente); [índice canónico de DDS](https://github.com/dakleyer/structural-awareness-contributions/blob/main/research/ecosystem-awareness/DDS_CANONICAL_METHOD_INDEX_v0.1.md) (tres etapas sustantivas independientes de los claims UC-21).

## 2. Instrucción de la persona solicitante y autorización

- **12 octubre 2026:** verificar en el GitHub que verá el revisor externo si UC-21 declara objetivos científicos claros y medibles, no sólo escenarios y gates; identificar exactamente lo que falta y por qué afecta a la trazabilidad.
- **12 octubre 2026, instrucción posterior explícita:** registrar **quién revisó, qué auditó, los problemas y los cambios precisos** en todos los **VNext** correspondientes, sin hacer la incorporación técnica silenciosamente. La aprobación es para **redactar/publicar auditorías y propuestas en VNext**; modificar los fuentes, la Issue FG-TIDA, los freezes, requisitos, oráculos, ensayos o resultados requiere decisión separada.
- **Interpretación operativa del auditor:** los identificadores editoriales **EO-01 a EO-05** propuestos en el VNext del caso son un índice de objetivos ya existentes; no son H7, nuevos requisitos, una ruta R3 de UC-21, especificaciones seleccionadas ni resultados DDS Stage A/B/C.

## 3. Auditoría realizada por ChatGPT (GPT-6) — UC21-OBJ-AUD-006

### Pasada 1 — Fondo, lógica y límites (PARCIAL: objetivos)

La plantilla separa 'Claim' y 'Route', pero no tiene un campo explícito para el objetivo del experimento y su resultado. Se puede cumplir formalmente el formulario y terminar con trazas y gates sin una respuesta inequívoca a la pregunta científica que motivó ese ensayo.

### Pasada 2 — Evidencia y relaciones entre fuentes (PARCIAL: objetivo→claim)

RUN_RECORD filas 9–23 registran claim, route, thresholds y oracle; 'Separate conclusions' enumera resultado de implementación e hipótesis, pero no el par objetivo→observación. El material UC21 principal exige registrar antes de ejecutar variables y controles.

**Documentos cuya relación se ha verificado y VNext de respuesta:** [Main case objectives audit](../USE_CASE_VNext.md) · [Hypotheses audit](../annexes/HYPOTHESES_VNext.md) · [Recurrence audit](../annexes/RECURRENCE_PROTOCOL_VNext.md). Se preservan dos diferencias científicas: un resultado de implementación no es una conclusión causal y un hallazgo positivo del fabricante no es por sí solo una especificación admitida.

### Pasada 3 — Edición y estructura (PARCIAL: punto de inserción)

Insertar un campo objetivo antes de Claim y una línea de conclusión específica tras resultado de implementación, preservando el resto del formulario y el hecho de que no introduce nuevas hipótesis, gates ni rutas.

### Pasada 4 — Lectura humana y destinatario fabricante (PARCIAL)

Cada run card quedaría legible como una prueba de una pregunta concreta: cuál, qué demostraría, qué sucedió, qué sigue sin haber sido probado.

**Hallazgo final UC21-OBJ-AUD-006:** Cambio editor-instrumental propuesto, sin alterar test ni oráculo. Máximo valor de trazabilidad al pasar de objetivos narrativos a registros reproducibles.

**Qué no demuestra esta auditoría:** no se han ejecutado los escenarios S1–S6 ni las 27 posiciones documentales de T01–T09; no se ha establecido HC/HR/HS ni conformidad, superioridad de EA, suficiencia/minimalidad del conjunto de especificaciones o validación por ITU. Las fuentes del repo describen perfiles y propuestas, no resultados nativos de producto.

## 4. Conversación de auditorías y revisión de la respuesta previa

**Auditoría realizada por ChatGPT (GPT-6), 12 October 2026, UC21-OBJ-AUD-006.** Revisión de mi evaluación anterior en esta conversación: la expresión 'objetivos insuficientemente claros' necesitaba acotación. **La investigación sí posee hipótesis explícitas y reglas de apoyo/refutación (HC, HR, HS, H1–H6).** El problema localizado es de **navegación y trazabilidad de los objetivos**, no de inexistencia de teoría científica ni de gates. No se atribuye esta corrección a un revisor humano externo. Respuesta de terceros: **ninguna recibida**. Próximas objeciones deben registrarse aquí sin eliminar esta entrada.

## 5. Instrucciones, estado y decisiones posteriores

- **Registro de la instrucción de Iván:** propuestas de objetivos/criterios en los VNext solamente, antes de cualquier cambio de corpus; no autorización para reescribir el caso ya enlazado por FG-TIDA.
- **Estado de las propuestas UC21-OBJ-AUD-006:** PREPARADAS PARA REVISIÓN; **decisión sobre el texto canónico PENDIENTE**. No se genera test, PR, aprobación institucional, contacto a fabricantes o publicación de hallazgos empíricos por preparar este expediente.
- **Prueba futura que permitiría cerrar la revisión:** Verificar que case-only sigue permitido; que la pregunta se congela antes de la observación y no se reescribe; que HS/HC/HR no se infieran de métricas aisladas, con fallos e inconclusos conservados.

## 6. Propuestas quirúrgicas — ANTES / DESPUÉS (no incorporadas)

### UC21-OBJ-AUD-006-P01 — Inserción localizada

**Documento:** `templates/RUN_RECORD.md` · commit auditado `5171c4a6ce7c1e2838c041a7365bd3698f820b24` · blob `be014eb521d0ede16697ad0f37b961c5eb562d63` · tipo: adición junto al ancla literal siguiente. **Instrucción:** petición del 12 October 2026 para preparar propuestas en VNext.

**ANTES — ancla literal completa:**

```markdown
| Claim: case acceptance / HC / HR / HS / selected H1–H6 | |
```

**DESPUÉS — ancla preservada con adición precisa:**

```markdown
| Objective ID and decision question: EO-01…EO-05 (or declared bounded subquestion; why this run is needed) | |
| Claim: case acceptance / HC / HR / HS / selected H1–H6 | |
```

**Por qué:** La plantilla separa 'Claim' y 'Route', pero no tiene un campo explícito para el objetivo del experimento y su resultado. Se puede cumplir formalmente el formulario y terminar con trazas y gates sin una respuesta inequívoca a la pregunta científica que motivó ese ensayo.

**Verificaciones antes de adoptar:** Verificar que case-only sigue permitido; que la pregunta se congela antes de la observación y no se reescribe; que HS/HC/HR no se infieran de métricas aisladas, con fallos e inconclusos conservados.

### UC21-OBJ-AUD-006-P02 — Inserción/reformulación auxiliar localizada

**Documento:** `templates/RUN_RECORD.md` · mismo blob y autorización; no se ejecuta en fuente.

**ANTES — ancla literal completa:**

```markdown
- **Implementation outcome:** gate results, actual business effect, legitimate-activity control, deadline and burden.
```

**DESPUÉS — adición/sustitución exacta propuesta:**

```markdown
- **Implementation outcome:** gate results, actual business effect, legitimate-activity control, deadline and burden.
- **Objective-specific finding:** EO identifier; prespecified observation that would support, limit/refute or leave the selected goal inconclusive; what was actually observed; whether the stated objective was tested at all; result and scope without promoting a gate pass to HC/HR/HS.
```

**Razón:** al instrumentar el registro y la selección, la pregunta experimental debe quedar fijada antes del ensayo; preservar el contrato completo y no promover los hallazgos.

**Cierre de estado:** propuestas únicamente. Las seis VNext constituyen una auditoría cruzada delimitada; ninguna implica fuente cambiada, resultado demostrado ni adopción. 


---

## Relectura del registro y del resultado — 12 octubre 2026

**Relectura por Codex, asistente de IA, 12 octubre 2026; corte `ee680a019a0cbd7270415f44237c894d370d275c`.** Se conserva la auditoría anterior, atribuida a ChatGPT/GPT-6 según sus propias notas. Esta relectura no autentica ese modelo ni constituye aceptación humana, revisión externa del producto o experimento. Pregunta y resultado son mejoras útiles; ambos viejos son únicos. La plantilla enlaza [Evidence E.6](../annexes/EVIDENCE_AND_PROTOCOL.md#e6--complete-run-record), que ya registra claim/diseño, decisión, métricas y conclusión. Antes de hacer EO obligatorio, decidir compatibilidad con esos grupos y matriz adoptada; no dos contratos de registro incompatibles.

P02 decía refutar el “selected goal”. Se refutan/limitan afirmaciones; las preguntas/objetivos se examinan o responden. La alternativa precisa el objeto de inferencia, sin modificar la plantilla.

## Plan al final — pregunta previa, conclusión por claim

**P01/P02 originales:** impacto esperado Alto; riesgo Medio; esfuerzo Medio; juntos después o con matriz/E.6. El acoplamiento entre significado, campos y congelación impide tratarlos como dos cambios aislados de Bajo riesgo por tener pocas líneas. Sin actualización de corridas históricas.

### Variante textual mínima de P02

**Fuente:** línea del after propuesto P02 de esta VNext, aún no texto de RUN_RECORD.md. **Impacto Medio; riesgo Bajo; esfuerzo Bajo.** Viejo único en ese contexto. Se preserva el P02 anterior; variante pendiente de Iván.

**Texto antes — viejo literal completo**

~~~~markdown
- **Objective-specific finding:** EO identifier; prespecified observation that would support, limit/refute or leave the selected goal inconclusive; what was actually observed; whether the stated objective was tested at all; result and scope without promoting a gate pass to HC/HR/HS.
~~~~

**Texto después — propuesto completo**

~~~~markdown
- **Objective-specific finding:** EO identifier; prespecified observation that would support, limit/refute or leave the selected claim inconclusive; what was actually observed; whether the stated objective was tested at all; result and scope without promoting a gate pass to HC/HR/HS.
~~~~

**Aceptación:** objetivo/claim/route y criterio fijados antes del outcome; separar observación, conclusión y scope. Aceptación de caso sin HC/HR/HS sigue permitida. Resolver matriz y E.6 antes de modificar campos obligatorios. No atribuir el hash de la plantilla a la VNext o refutar una pregunta. [Annex H](../annexes/HYPOTHESES_VNext.md#relectura-de-hipótesis-y-trazabilidad--12-octubre-2026) y [caso](../USE_CASE_VNext.md#relectura-de-la-matriz-de-objetivos--12-octubre-2026) reciben el contraste. Las fuentes y las propuestas originales están intactas.


## Tanda 3 — objetivos, Challenges y escenarios de evaluación · 12 octubre 2026

**Revisión realizada por Codex, mismo asistente.** Iván autoriza las tres adiciones concretas de la tanda2 y pide preparar y continuar la siguiente. Esas adiciones ya están publicadas en Contributions `2ff085688de77938aeaa5a3c0e7edbb607247d58` y la rama UC-21 `285ca77fc4cc5d69f3ea78aeda820777c647d0da`, con todos los bytes anteriores de las fuentes conservados. El PDF y la entrada pública se reservan para el final. Esta tanda publica revisión y cuatro propuestas; su incorporación requiere el GO de esta tanda.

### El formulario actual ya cubre esta selección

Se leyó RUN_RECORD completo: pide claim/scope,S4outcome,route,causalcondition,versiones/grants,basis,X1–X7,R1correction,cambio/adaptación,budget/deadline,oracle/observaciones y conclusiones separadas. No hace falta introducir EO obligatorios, otro nivel de ficha ni nueva campaña. No hay candidato de cambio del formulario en esta tanda. La guía del README y DDS lleva al formulario existente.

Un registro futuro identificará el perfil exacto y sus hechos asumidos; no usará «I2» sin namespace ni tratará una respuestaHOLD como efecto observado. Los blanks son inputs pendientes, nunca hechos por defecto. La lectura del formulario no ejecuta un run.


Relación revisada en ambos extremos: [plan EP](https://github.com/dakleyer/structural-awareness-contributions/blob/2ff085688de77938aeaa5a3c0e7edbb607247d58/architectural-contributions/ecosystem-positioning/README_VNext.md), [DDS VNext](https://github.com/dakleyer/structural-awareness-contributions/blob/2ff085688de77938aeaa5a3c0e7edbb607247d58/research/ecosystem-awareness/DDS_CHALLENGE_TRAJECTORY_PROFILE_v0.1_VNext.md), [baseline VNext](https://github.com/dakleyer/structural-awareness-contributions/blob/2ff085688de77938aeaa5a3c0e7edbb607247d58/research/ecosystem-awareness/baseline/README_VNext.md), [extensiones VNext](https://github.com/dakleyer/structural-awareness-contributions/blob/2ff085688de77938aeaa5a3c0e7edbb607247d58/research/ecosystem-awareness/baseline/reductions/00G-R01/extensions/README_VNext.md) y [caso VNext](https://github.com/dakleyer/use-cases/blob/285ca77fc4cc5d69f3ea78aeda820777c647d0da/contributions/when-controls-work-system-fails/README_VNext.md). Las entradas se atribuyen al mismo asistente; no se inventa consenso ni una revisión independiente.


## Tanda 3 aplicada — GO de Iván, 12 octubre 2026

Iván autoriza continuar después de la entrega de las cuatro propuestas de la tanda3. Se incorporan exactamente sus adiciones a baseline README (sucesor00H), README UC-21 (seis Challenges), DDSIndex (elección del ejercicio) y extensions README (preguntas de trece estudios). Todos los bytes previos de esas cuatro fuentes permanecen íntegros, con sus enlaces. No se modifica otro pasaje ni el PDF.

Las cuatro fichas incorporadas salen de la cola activa; su antes/después completo está en la [preparación publicada](https://github.com/dakleyer/use-cases/blob/1de940f00906c4cea085bf0c4f187e17d51e3a7c/contributions/when-controls-work-system-fails/templates/RUN_RECORD_VNext.md). Auditorías y decisiones anteriores se conservan. Cero archivos nuevos, movidos, renombrados o eliminados y ninguna VNext nueva. Los estudios conservan registros, inputs, resultados, código, freezes y manifiestos. Continúa la tanda4: método, instrumentos, comparadores y oráculo/harness, con propuestas nuevas pendientes del GO correspondiente.


## Tanda 4 — método, instrumentos, comparadores y evidencia · 12 octubre 2026

**Revisión realizada por Codex, mismo asistente.** Iván autoriza la tanda3 y pide preparar la siguiente. Las cuatro adiciones anteriores ya se incorporaron en Contributions `269d60cc478d2756516c631f587efc074e822eed` y la rama UC-21 `5c2a969bfbfc5eb8065537f3fade718e756dcdad`; se conservan los bytes anteriores y sus fichas aplicadas salen de pendientes. Esta tanda publica lectura de contratos y cuatro propuestas nuevas, aún pendientes del GO de la tanda4. PDF y entrada final UC-21 quedan reservados.

El formulario actual conserva versiones, comparadores, fuentes, grants, budget/time, oracle y outcomes separados. El registro DDS/T03 añade sus pins específicos en la campaña propietaria, sin convertir este formulario en otro registro de infraestructura. Al usarlo, los resultados de gate y de hipótesis se vinculan a evidencia y efecto; una declaración de aislamiento o seal no sustituye la prueba del runtime. No candidato al formulario en esta tanda.

La relación se registra en ambos extremos: [plan EP](https://github.com/dakleyer/structural-awareness-contributions/blob/269d60cc478d2756516c631f587efc074e822eed/architectural-contributions/ecosystem-positioning/README_VNext.md), [DDS VNext](https://github.com/dakleyer/structural-awareness-contributions/blob/269d60cc478d2756516c631f587efc074e822eed/research/ecosystem-awareness/DDS_CHALLENGE_TRAJECTORY_PROFILE_v0.1_VNext.md), [oracle VNext](https://github.com/dakleyer/structural-awareness-contributions/blob/269d60cc478d2756516c631f587efc074e822eed/research/ecosystem-awareness/baseline/reductions/00G-R01/oracle/README_VNext.md), [UC4 bridge VNext](https://github.com/dakleyer/structural-awareness-contributions/blob/269d60cc478d2756516c631f587efc074e822eed/research/ecosystem-awareness/baseline/reductions/00G-R01/oracle/UC4_INTEROPERABILITY_PROFILE_VNext.md) y [caso VNext](https://github.com/dakleyer/use-cases/blob/5c2a969bfbfc5eb8065537f3fade718e756dcdad/contributions/when-controls-work-system-fails/README_VNext.md). Se conservan desacuerdos/propuestas anteriores; estas entradas corresponden al mismo asistente.
