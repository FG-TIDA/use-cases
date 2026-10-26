# VNext — UC-21 — Primary experimental-objective matrix — scope, hypothesis, discriminating evidence and failure

> **Única VNext de este documento lógico; auditoría y propuestas, NO modificación incorporada.** La fuente, el paquete v0.9.3, el commit enlazado por FG-TIDA y el manifest SHA256 permanecen sin modificaciones. Estado: **revisión delimitada a trazabilidad de objetivos experimentales; propuesta pendiente de decisión e incorporación**. Fecha: 12 October 2026.

## 1. Fuente, identidad, revisión y límite

- **Documento de origen:** [USE_CASE.md](USE_CASE.md) — [copia pública congelada](https://github.com/dakleyer/use-cases/blob/aec08fb5b0fac2ee399372370e9ee2a82a2d5779/contributions/when-controls-work-system-fails/USE_CASE.md); rama viva de revisión `when-controls-work-system-fails-v0.9.3` del repositorio `dakleyer/use-cases`.
- **Corte del examen:** commit `5171c4a6ce7c1e2838c041a7365bd3698f820b24` en rama de contribución; blob original `6e3d299fdb077ef463d6e9b026510cd050eb34b3`, idéntico al documento fuente del commit de entrega `aec08fb5b0fac2ee399372370e9ee2a82a2d5779` según el cotejo realizado. No se han alterado estos blobs para elaborar este VNext.
- **Auditoría:** **UC21-OBJ-AUD-002** — realizada por **ChatGPT (GPT-6, OpenAI), AI assistant; not Iván Abril Palma, not Codex, and not an independent human/peer reviewer** el 12 October 2026. Modalidad: lectura y cotejo documental de GitHub, no experimento, no revisión humana independiente, no respuesta del fabricante, no certificación, no aprobación del Focus Group.
- **Alcance:** se revisa exhaustivamente la **relación con objetivos y claims** de UC-21 dentro de este documento y sus consumidores relevantes; no se declara completada una auditoría científica, jurídica o de implementación de todo el corpus.
- **Regla de método:** [procedimiento de auditoría y VNext del corpus](https://github.com/dakleyer/structural-awareness-contributions/blob/main/governance/CORPUS_REVIEW_PROCEDURE_2026-10-06.md) (disciplina de revisión aplicada a este paquete sin pretender sustituir su fuente); [índice canónico de DDS](https://github.com/dakleyer/structural-awareness-contributions/blob/main/research/ecosystem-awareness/DDS_CANONICAL_METHOD_INDEX_v0.1.md) (tres etapas sustantivas independientes de los claims UC-21).

## 2. Instrucción de la persona solicitante y autorización

- **12 octubre 2026:** verificar en el GitHub que verá el revisor externo si UC-21 declara objetivos científicos claros y medibles, no sólo escenarios y gates; identificar exactamente lo que falta y por qué afecta a la trazabilidad.
- **12 octubre 2026, instrucción posterior explícita:** registrar **quién revisó, qué auditó, los problemas y los cambios precisos** en todos los **VNext** correspondientes, sin hacer la incorporación técnica silenciosamente. La aprobación es para **redactar/publicar auditorías y propuestas en VNext**; modificar los fuentes, la Issue FG-TIDA, los freezes, requisitos, oráculos, ensayos o resultados requiere decisión separada.
- **Interpretación operativa del auditor:** los identificadores editoriales **EO-01 a EO-05** propuestos en el VNext del caso son un índice de objetivos ya existentes; no son H7, nuevos requisitos, una ruta R3 de UC-21, especificaciones seleccionadas ni resultados DDS Stage A/B/C.

## 3. Auditoría realizada por ChatGPT (GPT-6) — UC21-OBJ-AUD-002

### Pasada 1 — Fondo, lógica y límites (PARCIAL: objetivos)

El §1 dice por qué existen los recorridos y distingue HC y HR; el §5 abre con 'Choose one scenario, one technology and one route'. Sin matriz objetivos→afirmaciones→evidencia→resultados, el lector puede confundir cobertura de gates con demostración causal, recurrencia o suficiencia común.

### Pasada 2 — Evidencia y relaciones entre fuentes (PARCIAL: objetivo→claim)

USE_CASE §1 líneas 35–43, §5 120–151, §6 153–227; Annex H §13 y §9A; Annex R §R.4–R.7. Los 37 gates y sus seis resultados específicos ya están en fuentes, no se crean nuevos.

**Documentos cuya relación se ha verificado y VNext de respuesta:** [Package README audit](README_VNext.md) · [Submission audit](SUBMISSION_VNext.md) · [Annex H audit](annexes/HYPOTHESES_VNext.md) · [Annex R audit](annexes/RECURRENCE_PROTOCOL_VNext.md) · [Run-card audit](templates/RUN_RECORD_VNext.md). Se preservan dos diferencias científicas: un resultado de implementación no es una conclusión causal y un hallazgo positivo del fabricante no es por sí solo una especificación admitida.

### Pasada 3 — Edición y estructura (PARCIAL: punto de inserción)

Añadir §1.1 antes de §2 y una frase de registro previo al inicio del §5; preservar la redacción y numeración actuales; no insertar un nuevo requisito, garantía técnica, cuarta ruta, ni adoptar EA por defecto.

### Pasada 4 — Lectura humana y destinatario fabricante (PARCIAL)

A un ingeniero de Microsoft/Anthropic/AWS debe resultarle fácil señalar EO-02 y decir 'nuestra R1 fuerte pasa' o EO-03 y preguntar qué cambio medible activa la hipótesis, sin tratar ese resultado como juicio general del producto.

**Hallazgo final UC21-OBJ-AUD-002:** La formulación científica de base es buena; falta un contrato de lectura unificado para seleccionar objetivo antes de seleccionar prueba. Hallazgo editor-científico, NO corrección de la teoría ni hallazgo de ejecución.

**Qué no demuestra esta auditoría:** no se han ejecutado los escenarios S1–S6 ni las 27 posiciones documentales de T01–T09; no se ha establecido HC/HR/HS ni conformidad, superioridad de EA, suficiencia/minimalidad del conjunto de especificaciones o validación por ITU. Las fuentes del repo describen perfiles y propuestas, no resultados nativos de producto.

## 4. Conversación de auditorías y revisión de la respuesta previa

**Auditoría realizada por ChatGPT (GPT-6), 12 October 2026, UC21-OBJ-AUD-002.** Revisión de mi evaluación anterior en esta conversación: la expresión 'objetivos insuficientemente claros' necesitaba acotación. **La investigación sí posee hipótesis explícitas y reglas de apoyo/refutación (HC, HR, HS, H1–H6).** El problema localizado es de **navegación y trazabilidad de los objetivos**, no de inexistencia de teoría científica ni de gates. No se atribuye esta corrección a un revisor humano externo. Respuesta de terceros: **ninguna recibida**. Próximas objeciones deben registrarse aquí sin eliminar esta entrada.

## 5. Instrucciones, estado y decisiones posteriores

- **Registro de la instrucción de Iván:** propuestas de objetivos/criterios en los VNext solamente, antes de cualquier cambio de corpus; no autorización para reescribir el caso ya enlazado por FG-TIDA.
- **Estado de las propuestas UC21-OBJ-AUD-002:** PREPARADAS PARA REVISIÓN; **decisión sobre el texto canónico PENDIENTE**. No se genera test, PR, aprobación institucional, contacto a fabricantes o publicación de hallazgos empíricos por preparar este expediente.
- **Prueba futura que permitiría cerrar la revisión:** Revisar que EO-04 sea una afirmación existencial acotada por familia, que HR no se infiera de un R1 fallido, que S4 conserve sus dos resultados, que H1–H6 no se asignen uno a uno a seis escenarios y que HS no equivalga a minimalidad universal.

## 6. Propuestas quirúrgicas — ANTES / DESPUÉS (no incorporadas)

### UC21-OBJ-AUD-002-P01 — Inserción localizada

**Documento:** `USE_CASE.md` · commit auditado `5171c4a6ce7c1e2838c041a7365bd3698f820b24` · blob `6e3d299fdb077ef463d6e9b026510cd050eb34b3` · tipo: adición junto al ancla literal siguiente. **Instrucción:** petición del 12 October 2026 para preparar propuestas en VNext.

**ANTES — ancla literal completa:**

```markdown
Each scenario retains its facts, consequences and quality plan and can be reviewed independently.
```

**DESPUÉS — ancla preservada con adición precisa:**

```markdown
Each scenario retains its facts, consequences and quality plan and can be reviewed independently.

### 1.1 Experimental objectives, claims and observable decisions (proposed addition)

The five objective IDs below are **editorial cross-references only**, not new hypotheses, acceptance gates, normative requirements, or a replacement for Annex H/R. Each run declares its objective, exact scenario and outcome before selecting metrics and executing; different claims have different proof burdens. R0/R1/R2 are configuration routes, not scientific goals.

| Objective | Question being investigated | Claim / experiment route | Evidence necessary for an informative result | What a result cannot establish |
|---|---|---|---|---|
| **EO-01 — decision outcome** | Does the selected implementation reach the correct authorised decision and preserve legitimate activity for this case? | **Case acceptance only**, S1–S6 selected gates, positive and negative controls | Independently scored source/authority/decision/effect trace, all applicable gates, deadline and bounded cost | No HC/HR/HS evidence merely because a gate passes |
| **EO-02 — efficacy of existing controls** | Can the strongest competent configuration of the chosen technology correct the original systemic failure? | **R0 → R1** and strongest peer, case outcome | Versioned real/simulated controls, fair resources, defended R1 correction and continuity, successful alternative mechanisms credited | A documentary 'missing feature' is not product failure; a successful R1 is not recurrence |
| **EO-03 — corrected-baseline recurrence** | Can admissible material change cause the *same corrected* failure to recur under unchanged R1 safeguards? | **HR**, R1 baseline correction prerequisite → **frozen R2**, matched unchanged and harmless-change controls | Admitted change, independent failure predicate, timing/causal contrast, R1 correction, retained adaptation, repeatability and risk/uncertainty where needed | A failing R1 or a newly weakened R2 does not support HR; finite no-recurrence does not generally refute existential HR |
| **EO-04 — common causal pathway** | For each admitted failure family, is there a sufficiently evidenced transfer/qualification loss → material change → unjustified reuse mechanism? | **HC** under its predeclared candidate domain; separate **A–D** causal factors and source-dependence controls | Independently registered causal witness, mediator/ordering, matched controls, both S4 outcomes for full claim, reproducibility and scope | A single adverse outcome or HR recurrence does not establish the specific HC mechanism |
| **EO-05 — sufficient response** | Can a common qualified communication-and-processing mechanism prevent the registered harms while allowing timely justified activity? | **HS** plus matched response-component and strong conventional comparator tests; **H1–H6** only if separately chosen | Observed warning/requalification, authorised downstream response, actual effect, continuity, deadline, burden, and cross-case admission | Success is not universal superiority, uniqueness, minimality of a specification set or adoption by FG-TIDA |

**Order of evidence:** declare objective and testable claim → freeze scenario, candidate, comparators, resources, oracle, failure and legitimate-continuity outcomes → select route or A–D/HS contrast → execute/observe if authorised → report both the implementation outcome and the objective-specific inference with its bounded uncertainty. A product satisfying the case and a refutation/no-differential result are informative. Vendor-positive capability or later standards precandidate collection is a possible **research output**, not a substitute for these experimental objectives. DDS Stage A/B/C have separate method semantics; nothing here certifies an implemented product or establishes specification minimality.
```

**Por qué:** El §1 dice por qué existen los recorridos y distingue HC y HR; el §5 abre con 'Choose one scenario, one technology and one route'. Sin matriz objetivos→afirmaciones→evidencia→resultados, el lector puede confundir cobertura de gates con demostración causal, recurrencia o suficiencia común.

**Verificaciones antes de adoptar:** Revisar que EO-04 sea una afirmación existencial acotada por familia, que HR no se infiera de un R1 fallido, que S4 conserve sus dos resultados, que H1–H6 no se asignen uno a uno a seis escenarios y que HS no equivalga a minimalidad universal.

### UC21-OBJ-AUD-002-P02 — Inserción/reformulación auxiliar localizada

**Documento:** `USE_CASE.md` · mismo blob y autorización; no se ejecuta en fuente.

**ANTES — ancla literal completa:**

```markdown
## 5. Select, prepare and run one experiment
```

**DESPUÉS — adición/sustitución exacta propuesta:**

```markdown
## 5. Select, prepare and run one experiment

**Objective-first pre-registration (proposed editorial clarification).** Before selecting a scenario, product and R0/R1/R2, identify the declared EO-01…EO-05 objective (or its explicitly bounded subset), the exact claim to adjudicate, independently observable success/failure, and what contrary result would limit it. For HC, HR and HS use their owning annex protocols; passing gates alone is not an inferential hypothesis test.
```

**Razón:** al instrumentar el registro y la selección, la pregunta experimental debe quedar fijada antes del ensayo; preservar el contrato completo y no promover los hallazgos.

**Cierre de estado:** propuestas únicamente. Las seis VNext constituyen una auditoría cruzada delimitada; ninguna implica fuente cambiada, resultado demostrado ni adopción. 


---

## Relectura de la matriz de objetivos — 12 octubre 2026

**Relectura por Codex, asistente de IA, 12 octubre 2026; corte `ee680a019a0cbd7270415f44237c894d370d275c`.** Se conserva la auditoría anterior, atribuida a ChatGPT/GPT-6 según sus propias notas. Esta relectura no autentica ese modelo ni constituye aceptación humana, revisión externa del producto o experimento. P01 respeta HC como existencia de witness admisible por familia, HR como recurrencia después de corrección R1 demostrada y HS como suficiencia de un candidato común dentro del dominio. Se contrastaron H §§2/6/7/9A/13 y R §§R.2/R.4/R.6/R.7. El soporte HC completo exige ambos resultados S4; HR puede declarar una rama. A–D son condiciones causales, no posiciones epistemológicas A/B/C/D ni etapas DDS. Prevención no prueba causalidad, minimalidad o exclusividad.

EO no está adoptado en la fuente. Los dos viejos P01/P02 son únicos; “preparadas para revisión” no acredita preregistro o admisión. No se hicieron nuevas lecturas completas de los grandes escenarios o baselines nativos.

S3 es histórico y S6 pointer a Contributions en esta rama; la versión experimental no debe depender del valor cambiante de main. Los perfiles Claude/Stripe ya separan H1 aún fallida de H1-L corregida, o equivalente, que admitiría R2. Es concordancia documental, no corrección probada. [README VNext](README_VNext.md#relectura-de-la-auditoría-y-alcance-de-fuentes--12-octubre-2026) documenta snapshots y bindings SHA.

## Plan al final — matriz y conclusiones

**P01:** impacto esperado Alto, riesgo Medio, esfuerzo Medio; primera preparación, conservando dominios y cuantificadores, pins y doble resultado S4. **P02:** impacto Medio, riesgo Bajo, esfuerzo Bajo; junto a P01. Una aceptación de caso no exige declarar HC/HR/HS.

**Compatibilidad:** matriz antes o junto a README/SUBMISSION/H/R y plantilla, con un solo propietario. [Run record](templates/RUN_RECORD_VNext.md#relectura-del-registro-y-del-resultado--12-octubre-2026) conserva pregunta/claim/criterio antes del outcome. [SUBMISSION](SUBMISSION_VNext.md#contraste-de-la-presentación-pública--12-octubre-2026) añade decisión de edición/destino/sectores. Los pares completos anteriores permanecen; ninguna incorporación ni cierre científico se ejecuta.


## UC-21 y DDS: dos entradas enlazadas — 12 octubre 2026

**Revisión por Codex, mismo asistente.** Iván precisa que UC-21 es el caso con objetivos y campañas, y DDS el método de investigación. Se mantiene esta distinción y se ajusta el orden del diseño de consolidación: primero probar la navegación desde UC-21 usando sus ejercicios existentes; después comprobar su generalidad con HF y otra familia. No se crea una nueva campaña S5 ni se mueve el caso al corpus metodológico.

**Relación propuesta:** entrada UC-21 → explicación del caso y objetivos → escenarios/hipótesis → ejercicios existentes → contrato DDS aplicable → runs/evidencia → conclusión para el objetivo UC-21 → posible selección posterior de especificaciones. Desde DDS se recorre la misma relación por método → campañas de distintos casos → fuente del Challenge → evidencia → resultado. El registro futuro debe apuntar a los expedientes reales y sus propietarios, con varias relaciones por campaña; no duplicarlos bajo ambas entradas.

**Asignación de funciones:** UC-21 mantiene su problema, objetivos, HC/HR/HS/H1–H6 y gates. DDS mantiene método y A/B/C. El expediente del estudio mantiene contrato, versión, comparadores, ejecución y conclusión. EA, RA, MSCA y otros componentes conservan fuentes y decisiones de incorporación. Objetivo, R0/R1/R2, Stage A/B/C, modo de evidencia y estado de ejecución son dimensiones separadas. Un resultado del caso no demuestra automáticamente necesidad de EA ni selección de una especificación.

**Preservación:** enlaces actuales, snapshot enviado, anexos, escenarios, figuras, pruebas, denominadores y autoría conservados. Toda relación estructural se revisa en las VNext de README correspondientes; tres niveles EP→Awareness→índices técnicos, con expedientes de campaña como documentos de trabajo. Mantener una sola VNext lógica aunque un registro enlace varias rutas. La copia física posterior sigue pendiente de matriz de versiones/dependencias; no es necesaria para implementar la lectura propuesta.

El puente inicial se propone en [README VNext](https://github.com/dakleyer/use-cases/blob/when-controls-work-system-fails-v0.9.3/contributions/when-controls-work-system-fails/README_VNext.md). Aquí se propone su consecuencia sobre la declaración de estudios: vínculo objetivo→contrato→evidencia→conclusión, conservando el ámbito del caso. Impacto Alto/riesgo Medio/esfuerzo Medio; no añadir campos obligatorios a la plantilla ni interpretar EO-01…05 como aprobados sin conciliar las propuestas anteriores. Los comentarios S5/S4 distinguen ejercicios vigentes y follow-ups opcionales. No se renombra un ejercicio existente como nuevo.

## Aplicación del puente UC-21–DDS — 12 octubre 2026

Iván autoriza continuar con el recorrido UC-21→objetivos→ejercicios existentes→DDS→resultados del caso. Se incorpora exactamente la inserción de trazabilidad al final de §4, antes de §5 propuesta aquí. No se sustituye ni elimina texto previo de la fuente. La aplicación y esta actualización de estado se publican juntas.

La ficha de esta propuesta aplicada, incluidos sus pares antes/después, se retira de la cola activa. Su texto completo queda en la [VNext predecesora](https://github.com/dakleyer/use-cases/blob/3856dfd100e3d124d6a873f198ae1e85a97626e0/contributions/when-controls-work-system-fails/USE_CASE_VNext.md) y en custodia auténtica. Las auditorías y todas las demás propuestas de objetivos/matriz/snapshot se conservan; esas otras propuestas no se incorporaron por este cambio. Las fuentes congeladas y SHA256SUMS.txt conservan su edición anterior; no certifican esta nueva redacción de los dos lectores. No se regeneraron hashes científicos ni se declararon nuevas ejecuciones.

El README y USE_CASE de la rama ya conectan caso, método y corpus arquitectónico. La Issue UC-21 sigue apuntando al envío congelado; su enlace de seguimiento requiere una decisión específica posterior. No se cambia la entrada externa, el snapshot o main use-cases por esta aplicación. Stage A/B/C, R0/R1/R2, criterios del caso, anexos y resultados permanecen iguales.


## Tanda 1: lectura de objetivos con sus protocolos — 12 octubre 2026

**Comprobación terminológica previa.** Se leyeron UC-21 Conventions/Extensionality, DDS A §3/§6/§10A, DDS B/C, R01, el protocolo de extensiones, kernel E1–E7, HEW Technical Report, DBC, 00D, Requirements y los índices RA/MSCA pertinentes. La búsqueda pública de usos complementó esas lecturas; no equivale a leer cada documento histórico. Challenge define problema/familia; el escenario delimitado lo instancia. UC-21 mantiene S1–S6 y sus familias 00E–00J. HEW usa escenario como descripción humana con instancia formal. Campaña de investigación, campaña operativa de S4 y unidad de campaña R01 no son intercambiables. Ejercicio se usa como entrada de lectura para estudios/recorridos existentes, no como nuevo tipo normativo. A/B/C DDS, A–D causales, A/B/C/D epistemológicos, R0/R1/R2 UC-21 y R01-R1/R2/R3 siguen con sus fuentes. La adición inicial que identificaba escenario con problema se corrigió antes de publicarse.

La matriz añadida resume cinco preguntas actuales y sus fuentes. Se selecciona objetivo/claim antes de escenario/route; una conclusión vuelve a ese objetivo. HR conserva R1 corregida antes de R2; HC exige witness admisible por familia y ambos outcomes S4; HS conserva warning/response, continuidad y budget. H1–H6 siguen como contrastes separados. La variante de lectura no obliga a campos EO en la plantilla, no define causalidad exclusiva ni minimalidad. Los anexos y sus fórmulas no cambian. [README VNext](README_VNext.md) y [plan EP](https://github.com/dakleyer/structural-awareness-contributions/blob/main/architectural-contributions/ecosystem-positioning/README_VNext.md) son los extremos de navegación. Estado: autorizado; fuente aún intacta en esta revisión.


**Aclaración de Iván — ruta ratificada:** UC-21→objetivos→Challenges→DDS→campañas→resultados. Dentro de DDS, escenario de evaluación designa la aplicación de una tecnología/configuración a un Challenge. Se conserva la distinción de la fuente entre instancia/base delimitada y technology mapping/profile; no se sustituyen los nombres de los originales ni se transforma la campaña operativa S4 en campaña de investigación.



## Incorporación de la primera tanda de lectura — 12 octubre 2026

Iván autoriza ejecutar la ruta UC-21→objetivos→Challenges→DDS→campañas→resultados. Las adiciones descritas aquí se incorporan conservando todos los bytes previos y vínculos de las fuentes. La terminología de lectura remite a sus propietarios: Challenge, escenario base, escenario de evaluación/perfil tecnológico y campañas/operaciones mantienen sus contextos. No se renombra un archivo, se modifica un contrato o se ejecuta una campaña.

La ficha de esta tanda aplicada se retira de la cola activa; sus textos completos están en la [versión de preparación](https://github.com/dakleyer/use-cases/blob/81d0eb7804ed7b31abb6c7366f64aff91ae46fc2/contributions/when-controls-work-system-fails/USE_CASE_VNext.md). El plan de las tandas 2–6 sigue vigente: inventario de dependencias/versiones, agrupación con unidad explícita, informes de campaña y conciliación. La entrada de Issue se actualiza después de verificar las fuentes publicadas. Sus enlaces de envío se conservan.


## Tanda 3 — objetivos, Challenges y escenarios de evaluación · 12 octubre 2026

**Revisión realizada por Codex, mismo asistente.** Iván autoriza las tres adiciones concretas de la tanda2 y pide preparar y continuar la siguiente. Esas adiciones ya están publicadas en Contributions `2ff085688de77938aeaa5a3c0e7edbb607247d58` y la rama UC-21 `285ca77fc4cc5d69f3ea78aeda820777c647d0da`, con todos los bytes anteriores de las fuentes conservados. El PDF y la entrada pública se reservan para el final. Esta tanda publica revisión y cuatro propuestas; su incorporación requiere el GO de esta tanda.

### Juicio de la selección y de los planes

USE_CASE§1.1 ya reúne cinco objetivos, §5 la selección de escenario/tecnología/route, §6 las37condiciones y §7 nueve perfiles. La coherencia de los núcleos del caso se mantiene; el punto pendiente es hacer accesible la cadena con versiones, fuentes mantenidas y positivos. Cinco planes usan Q0–Q5 y S5 Q0–Q6; S1-Q2 y S4-Q2 son obligaciones distintas. No se trasladan automáticamente a SA-G00–SA-G14. Se propone una guía al final del README propietario y enlace desde DDS; no candidato de modificación del cuerpo USE_CASE.

La comparación con S5 externo registra una corrección local, no AWS-I2/R2. Para HR, Annex R requiere R1 corregido y defences/adaptación retenidos; los controles parcialmente reforzados no cuentan como corrección. Para HC, los factores A–D exigen aislamiento propio: el par del perfil T05 cambia independencia y autoridad juntas y declara ya cómo aislar la dependencia. Se conserva esa precisión.


Relación revisada en ambos extremos: [plan EP](https://github.com/dakleyer/structural-awareness-contributions/blob/2ff085688de77938aeaa5a3c0e7edbb607247d58/architectural-contributions/ecosystem-positioning/README_VNext.md), [DDS VNext](https://github.com/dakleyer/structural-awareness-contributions/blob/2ff085688de77938aeaa5a3c0e7edbb607247d58/research/ecosystem-awareness/DDS_CHALLENGE_TRAJECTORY_PROFILE_v0.1_VNext.md), [baseline VNext](https://github.com/dakleyer/structural-awareness-contributions/blob/2ff085688de77938aeaa5a3c0e7edbb607247d58/research/ecosystem-awareness/baseline/README_VNext.md), [extensiones VNext](https://github.com/dakleyer/structural-awareness-contributions/blob/2ff085688de77938aeaa5a3c0e7edbb607247d58/research/ecosystem-awareness/baseline/reductions/00G-R01/extensions/README_VNext.md) y [caso VNext](https://github.com/dakleyer/use-cases/blob/285ca77fc4cc5d69f3ea78aeda820777c647d0da/contributions/when-controls-work-system-fails/README_VNext.md). Las entradas se atribuyen al mismo asistente; no se inventa consenso ni una revisión independiente.


## Tanda 3 aplicada — GO de Iván, 12 octubre 2026

Iván autoriza continuar después de la entrega de las cuatro propuestas de la tanda3. Se incorporan exactamente sus adiciones a baseline README (sucesor00H), README UC-21 (seis Challenges), DDSIndex (elección del ejercicio) y extensions README (preguntas de trece estudios). Todos los bytes previos de esas cuatro fuentes permanecen íntegros, con sus enlaces. No se modifica otro pasaje ni el PDF.

Las cuatro fichas incorporadas salen de la cola activa; su antes/después completo está en la [preparación publicada](https://github.com/dakleyer/use-cases/blob/1de940f00906c4cea085bf0c4f187e17d51e3a7c/contributions/when-controls-work-system-fails/USE_CASE_VNext.md). Auditorías y decisiones anteriores se conservan. Cero archivos nuevos, movidos, renombrados o eliminados y ninguna VNext nueva. Los estudios conservan registros, inputs, resultados, código, freezes y manifiestos. Continúa la tanda4: método, instrumentos, comparadores y oráculo/harness, con propuestas nuevas pendientes del GO correspondiente.
