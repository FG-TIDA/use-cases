# [Use Case] Contextual trust under recursive human–agent escalation

![Robots writing specifications for trust in robots. Proposed, hypothetical individual expert contribution.](assets/cover.png)

**[Start with the short case](FG_TIDA_Issue_Body_Contextual_Trust_v1.0.md)** · **[Read the complete dossier](FG_TIDA_Use_Case_Contextual_Trust_Recursive_Escalation_v1.0.md)** · **[Visual reading edition](FG_TIDA_Visual_Reading_v1.0.html)**

> **For this package, this action and this moment: what can be relied on, what remains unresolved, and what must be reviewed before proceeding?**

| Contribution status | Technical contract | Evaluation status |
|---|---|---|
| Proposed · hypothetical · individual contribution | 26 HAP requirements · versioned profiles | 66 test designs · none executed |

---

First publication edition, version 1.0; hypothetical and implementation-neutral. Submitted to FG-TIDA as an individual expert contribution; no acceptance, pilot execution or adoption is claimed. This summary follows the retained ten-section template and does not replace the dossier's requirements or evaluation designs.

**Reading route:** [FG-TIDA fit](#fg-fit) · [The situation](#situation) · [Requirements](#requirements) · [Assessment](#assessment) · [Duplication](#duplication) · [Complete annex guide](FG_TIDA_Use_Case_Contextual_Trust_Recursive_Escalation_v1.0.md#annex-a)

---

<a id="fg-fit"></a>

**FG-TIDA justification:** This case contributes technical requirements (ToR 4.1), scoped trust metadata (4.4) and falsifiable assessment designs (4.5), addressing trust lifecycle and human oversight (4.3; Annex A.2.2/A.2.4). It tests the receiver's admission decision for a mixed human–agent specification-and-code package. Policy and authority remain external inputs, consistent with the scope exclusions in clause 2. This is a proposed mapping, not institutional acceptance. [Official Terms of Reference](https://www.itu.int/en/ITU-T/focusgroups/tida/Pages/ToR.aspx).

**Neighbors and separation, before the scenario:**

| Neighbor / group | Reused finding | Additional question in this case |
|---|---|---|
| [UC #6](https://github.com/FG-TIDA/use-cases/issues/6); human-oversight Theme #16 | Context applicability and escalation conditions. | Did the required review actually occur, including human subdelegation and capacity limits? |
| [UC #7](https://github.com/FG-TIDA/use-cases/issues/7), [#5](https://github.com/FG-TIDA/use-cases/issues/5), [#12](https://github.com/FG-TIDA/use-cases/issues/12) | Identity/state, provider origin and evidenced lineage. | What do they establish about this contribution, review and shared-source corroboration? |
| [UC #14](https://github.com/FG-TIDA/use-cases/issues/14), [#17](https://github.com/FG-TIDA/use-cases/issues/17), [#4](https://github.com/FG-TIDA/use-cases/issues/4) | Verification/conformance findings and local decision boundaries. | Is evidence sufficient for benign, reversible package admission? Domain verification and incident containment stay with their respective cases. |
| C2PA/IPTC, W3C, IETF, identity/observability groups | Native assertions, provenance, credentials, delegation, appraisal and execution evidence. | Does their selected composition preserve the limitations needed for this decision? |
| NIST, ISO/IEC, JCGM and disclosure/labeling initiatives | Existing risk, quality, measurement and declaration concepts. | Are they applied with the right scope, uncertainty, review function and validity? |

Full source-specific boundaries are at the dossier's opening and Sections 4/7/H.9. The contribution proposes a testable composition question; it does not claim these groups lack the relevant concepts or cannot satisfy the case.

## 1. Identification

**Title:** Contextual trust under recursive human–agent escalation

**Submitting organization:** Individual expert contribution — Iván Abril Palma, The Integral Management Society / Tegrity.AI

**Contact name:** Iván Abril Palma  
**Contact email:** ivan.abril@tegrity.ai

**Sector:**

- [ ] Education
- [ ] Displaced persons / humanitarian
- [ ] Health
- [ ] Financial services
- [ ] Telecom
- [ ] Media and publishing
- [ ] Logistics
- [ ] Energy
- [ ] Critical infrastructure
- [ ] Smart home / IoT
- [x] Other: International IT pre-standardization and collaborative software engineering; downstream industrial variant in the dossier.

<a id="situation"></a>

## 2. The situation

**Plain language description:** An international IT pre-standardization group develops specifications, code and tests for trust between humans and agents through GitHub. FG-TIDA can implement human escalation, but the human on that route can introduce an agent into the escalation pipeline; therefore, “human escalation” does not demonstrate that independent human judgment has occurred. The receiver must decide whether the resulting package has sufficient evidence for admission to a controlled testbed.

**Narrative hook:** Robots writing specifications for trust in robots.

**Actor:** Maintainer organization M; contributor organization S; requirement owner H1, contributor H2 and reviewer H3; drafting/coding agents A1/A2; review assistant A3 in the escalation extension; non-AI tooling T1; identity/authorization providers; evidence issuers; appraiser V; workflow W; auditor Q.

**Action:** Turn comments and sources into clauses, schemas, code, tests and a versioned executable package; review it and decide reversible testbed admission.

**Decision required:** May M rely on this exact package for this action, considering quality, required review, independence, authority, coverage, residual uncertainty and the time available for further evidence?

**Problem encountered:** Accounts, signatures and apparent agreement can conceal different production and review paths. An agent may draft a clause, implement it and generate tests from the same mistaken interpretation. A human-associated response may merely transmit another agent's recommendation. Later changes may invalidate prior review while familiar names and approvals remain visible. These are synthetic conditions, not allegations about actual contributors.

**Current mitigation:** Declarations, source citations, version-bound reviews, identity and delegation records, repository protections, build attestations, independent fixtures and workflow logs.

**Residual gap:** Whether these mechanisms, composed and correctly configured, preserve enough meaning and evidence for the receiver's specified decision. The case does not assume their inadequacy.

**Working definition:** Contextual reliance is the bounded decision to depend on a contribution or review for a specified task, artifact version, context, consequence and validity period, with evidence quality, coverage, independence and residual uncertainty stated. Actor type alone establishes neither superior quality nor adequate oversight.

![The human reviewer may consult A3; a human response does not establish the required judgment. Admission depends on applicable evidence for the exact package.](assets/process.png)

**Open the supporting routes:** [R0/R1/R2 evaluation](FG_TIDA_Use_Case_Contextual_Trust_Recursive_Escalation_v1.0.md#evaluation-paths) · [Measurement and escalation](FG_TIDA_Use_Case_Contextual_Trust_Recursive_Escalation_v1.0.md#annex-i) · [Exact standards gaps](FG_TIDA_Use_Case_Contextual_Trust_Recursive_Escalation_v1.0.md#annex-h)

**Concrete challenge:** C0 requires missing mandatory approval evidence to remain `NOT_ESTABLISHED`. A controlled later change treats that absence as approval satisfied; candidate-derived tests may repeat the same error. Compare behavior against independently fixed C0 outcomes. An earlier approval for D2 does not silently cover D3. Testbed admission produces scoped observations, not a certificate that the trust framework is correct.

## 3. Actors and context

**Taxonomy roles involved:**

- [x] Principal
- [x] Relying party
- [x] Builder
- [x] Deployer / Owner
- [x] Agent instance
- [x] User
- [x] Infra provider
- [x] Attestor
- [x] Other: domain reviewer, evidence appraiser and auditor

**Mandates in this case:**

| Grantor | Grantee | What is conferred | Governing regime / stipulated policy |
|---|---|---|---|
| Group governance owner | H1 | Record C0 and its change procedure. | Group terms and organizational policy. |
| M | S / contributors | Submit scoped proposals. | Contribution rules; no adoption authority. |
| S | H2, A1, A2 | Draft, implement or review. | Versioned tool-use and delegation policy. |
| Review owner | H3 | Review and approve the exact next step. | Group review procedure and mandate. |
| M and S separately | Evidence custodians | Record and disclose permitted evidence. | Access, retention and confidentiality policies. |
| M | V and W | Appraise and apply admission policy. | Local versioned policy; no invented authority. |

These are hypothetical policy relationships; actual jurisdictions and applicable legal regimes must be supplied by pilot owners.

**Cross-border?** [x] Yes — intended international collaboration; jurisdictions/hosting locations remain pilot inputs. [ ] No  
**Embodied?** [ ] Yes [x] No — software/synthetic effects.  
**Agent action type:** [x] Read-only [x] Consequential (reversible) [ ] Irreversible  
**Crosses organisational boundary?** [x] Yes — M, S and evidence providers. [ ] No  
**Risk level:** [ ] Low [x] Medium — stipulated bounded testbed [ ] High

Formal adoption, production deployment and binding external commitments are outside this decision.

<a id="theme-relevance"></a>

## 4. Theme relevance

| Theme | Yes | Primary | Justification |
|---|---|---|---|
| Dynamic Identity | [x] | [x] | Acting subject and continuity across handoffs/revisions. |
| Continuous Trust and Attestation | [x] | [ ] | Scoped evidence appraisal and current applicability. |
| Delegation | [x] | [ ] | Principal, executor and recursive review assistance. |
| Discovery and Cross-Border Trust | [x] | [ ] | Cross-organizational issuers, profiles and policy inputs. |
| Runtime Enforcement (Control Plane) | [x] | [ ] | Receiver-controlled admission of the exact package. |
| Embodied AI Identity and Trust | [ ] | [ ] | No physical actuation in this profile. |

**Related theme proposals:** The opening and dossier Section 4 map the relevant proposals and Terms of Reference. Requirements are stated as case-derived functions, without prescribing a qualification approach. Dynamic Identity remains the base profile's primary theme; no theme reassignment is implied by this editorial summary.

**Scope boundary:** Policies and authority are external inputs. The case proposes technical evidence/appraisal requirements, not general AI governance, a new agentic protocol or national digital-ID content; these boundaries follow ToR clause 2. Submission placement should consider Continuous Trust and Attestation as primary for the evolved framing, without altering the frozen fixture.

<a id="requirements"></a>

## 5. Requirements

The following reproduces the 26 existing requirements from dossier Section 5. “Must” is a proposed case requirement, not an adopted standard.

| # | Type | Requirement description | Criticality |
|---|---|---|---|
| HAP-01 | Technical | Bind each material activity to a process instance, step, action, event time, input/output versions and source record; represent branches, merges and asynchronous ordering. | Must |
| HAP-02 | Technical | Distinguish represented principal, account, human participant, logical agent, execution and automated service. Preserve identifier namespaces and the supported links between them. | Must |
| HAP-03 | Technical | Report claimed actor type separately from appraised actor type and assurance. Human-owned credentials, a personhood proof or successful login shall not by themselves label subsequent actions or content as human-produced. | Must |
| HAP-04 | Technical | Distinguish AI execution, non-AI automation and automation of unknown type where evidence permits. Record hybrid contributions at activity/role level without inventing a hybrid identity. | Must |
| HAP-05 | Technical | Each material claim shall retain issuer, issuer relationship, subject, scope, time, method/profile version, evidence references, appraisal and known limitations. A valid signature shall not be treated as proof of the claim's truth. | Must |
| HAP-06 | Technical | Retain provenance links for generation, transformation, quotation, review, approval and transmission where evidenced. Record inputs made available separately from supported derivation or influence. | Must |
| HAP-07 | Technical | Represent expressed ideas as bounded propositions or design options with source/version references. Distinguish first recorded occurrence, declared origin, supported derivation and independent reconstruction; allow inseparable or unknown origin. | Must |
| HAP-08 | Technical | Bind any human approval to its content/action scope, version or digest, person/role evidence, relevant mandate, time and validity conditions. Approval shall not transfer silently to changed content. | Must |
| HAP-09 | Technical | Distinguish presence/authentication, declared review, observed review activity, approval and demonstrated understanding; only claim the states supported by the selected evidence profile. | Must |
| HAP-10 | Technical | Evaluate continuity separately for each subject level and record supporting transition evidence. A shared name, model, account or key alone shall not establish all continuity claims; key rotation alone shall not disprove logical continuity. | Must |
| HAP-11 | Technical | Retain versioned baselines for material propositions, constraints, purpose and context. Identify additions, omissions, reversals, changes of qualification and changed decision effects within a declared comparison scope. | Must |
| HAP-12 | Technical | Separate semantic change detection from explanation and authority. Distinguish justified revision, unexplained contradiction, changed scope, suspected tampering and unresolved cause without inferring identity change from disagreement alone. | Must |
| HAP-13 | Technical | Preserve unknown, missing, withheld, not-applicable, conflicting and failed-appraisal states; preserve the reason for each. Absence of an AI signal shall not establish human origin, and missing evidence shall not be interpreted as zero contribution. | Must |
| HAP-14 | Technical | Any participation percentage shall identify its numerator, denominator, unit, stage, population, observation window, counting/weighting rules, overlap policy, evidence coverage and uncertainty. A detector confidence score shall not be presented as an AI-contribution percentage. | Must |
| HAP-15 | Technical | Support separate measures for participation, retained content lineage and human approval coverage. Do not produce an exclusive human/AI split where mixed or unknown contributions cannot be allocated defensibly. | Must |
| HAP-16 | Technical | Carry material provenance limitations through transformations and handoffs, with explicit mapping losses. An unsupported incoming claim shall not become established merely by aggregation, signing or relabeling. | Must |
| HAP-17 | Technical | Protect scoped evidence against alteration, replay and approval substitution; check current status/freshness and relevant trust anchors. Preserve original claims and append corrections or superseding assessments. | Must |
| HAP-18 | Technical | Reassess affected conclusions when material actor, version, context, evidence or issuer-status conditions change. Identify dependent steps potentially affected, without requiring global process visibility. | Must |
| HAP-19 | Technical | Separate evidence appraisal and semantic assessment from the receiver's authorized routing decision. Unresolved conditions must invoke the declared policy; they shall not silently satisfy a positive evidence requirement. | Must |
| HAP-20 | Technical | Enable independent replay of deterministic checks from disclosed evidence and pinned policy versions; mark inaccessible or non-reproducible evidence explicitly. Preserve native evidence semantics through adapters. | Must |
| HAP-21 | Technical | Minimize disclosed personal data and confidential content; support role/pseudonymous claims, protected evidence references, retention controls and disclosure logs. No universal biometric registry or full prompt-history disclosure is required. | Must |
| HAP-22 | Business | Present an understandable process-level answer showing who acted, evidenced contribution roles, continuity, changed content and unresolved limits, with drill-down to the supporting records. | Must |
| HAP-23 | Business | Reuse existing identity, PLM/document, workflow and observability systems; measure added delay, integration effort and investigation effort against the baseline. | Should |
| HAP-24 | Technical | Where statistical detectors or semantic models are used, record version, domain, threshold and calibration/test scope, permit abstention, and report errors separately from deterministic evidence failures. | Must |
| HAP-25 | Legal | Represent externally determined disclosure, data-access and retention obligations as versioned policy inputs. A technical provenance finding shall not itself determine copyright, legal authorship, liability or regulatory compliance. | Must |
| HAP-26 | Technical | Assess the profile with positive, negative, boundary and changed-condition cases using independently specified expected outcomes; preserve the possibility that an existing standards-based implementation already satisfies the case. Pin the profile owner, approved version and controlled-change record defined in Annex A.1.1 for each evaluation. | Must |

The complete requirements and traceability remain in dossier Section 5 and its annexes. Its direct-reuse table links each condition to a concrete failure, existing HAP requirements and observable acceptance evidence. Scope/uncertainty, common dependencies, further-review capacity and targeted revalidation are already expressed in the case's own terms. Selected-extension conditions remain explicit; they do not silently change the base profile.

Reuse a native record or requirement directly when its meaning, subject, scope, evidence status and validity match. Do not require a renamed field or a new connector merely to pass. Any genuine semantic mismatch must be declared. All implementations face the same frozen expectations, including compliant positive controls and the possibility that existing mechanisms already suffice.

Function policy distinguishes personally required judgment, human authorization, assigned accountability and permitted automation. These conditions can coexist; independence and reviewability are additional qualifiers. A required human function is more precise than “100% human.”

<a id="assessment"></a>

## 6. Assessment criteria

**Success criteria:** Produce a version-bound, reconstructable decision with supported findings, unknowns and limits. Corrected compliant cases must advance. Always blocking, always trusting a human click or always returning unknown cannot pass.

**Measurable metric:** Unsupported positive review claims; erroneous acceptance and unnecessary holds; qualifier loss between adapters; material-change detection; requalification latency; reviewer effort. Compare human, agent and hybrid task outcomes under fixed rubrics without preselecting a winner. A calibrated probability of correctness cannot replace authority or mandatory review.

| Profile | Function | Evidence status |
|---|---|---|
| `prestandardization-v0.4` | Base P0–P7 | Frozen hypothetical fixture; select applicable tests from the 50-design T-series catalogue. |
| `escalation-context-v0.1` | Recursive escalation | Proposed; eight designs. |
| `measurement-reliance-v0.1` | Scope, uncertainty and further evidence | Proposed; eight designs. |
| Annex F / Annex G | Industrial connector / manufacturing comparison | Conceptual variant / separate comparison. |

**None of the 66 test designs in this use case (T01–T50, ES01–ES08 and MQ01–MQ08) has been executed as part of this publication. This statement concerns this case only and does not characterize execution status elsewhere in the wider reference corpus.** Technical fixture IDs retain their existing suffixes for reproducibility; they are independent of publication version 1.0. Deterministic state checks and statistical performance evaluation are separate campaigns. Each assessment states what further evidence could help, who can obtain and assess it, and whether it can arrive before the intervention deadline. More observations within one branch do not close unobserved branches.

<a id="duplication"></a>

## 7. Duplication check

**Existing standards or SDOs:** C2PA/IPTC, W3C PROV/VC/disclosure work, IETF RATS/SCITT/OAuth, identity/observability ecosystems, NIST risk guidance and JCGM measurement guidance. Industry labeling examples include MIHR and Provenance Label. Exact versions, primary references and limits are in dossier H.9.

**Overlap notes:** Existing work already supports influence relationships, meta-provenance, assertion metadata, appraisal policies and uncertainty-aware decisions. The remaining question is whether the selected composition preserves and appraises review functions, dependencies, quality, coverage and contextual applicability sufficiently for this decision, including recursive human-to-agent delegation. No universal absence of a suitable profile is asserted.

Compare native controls, a strengthened composition and the proposed receiver profile under the same evidence/policy. If the existing composition suffices, report that result. Separate implementation, mapping and evidence gaps from a standards gap; failure in a selected implementation is not proof of a missing standard.

Selected primary references, with analysis in the dossier:

https://www.w3.org/TR/prov-dm/  
https://spec.c2pa.org/specifications/specifications/2.4/specs/C2PA_Specification.html  
https://datatracker.ietf.org/doc/html/rfc9334  
https://airc.nist.gov/airmf-resources/playbook/measure/

## 8. Maturity

**Pilot status:** [x] Hypothetical [ ] Pilot in progress [ ] Deployed in production

**Reference implementation:** N/A for the combined profile. Pilot owners must validate process facts, evidence availability, policies and reversible boundaries; freeze selected extensions and independent expectations; then execute and compare implementations. No performance benefit is yet claimed.

## 9. IP and confidentiality

**Confidentiality level:** [x] Public — proposed synthetic contribution [ ] FG-internal only [ ] Redact before publication

**IP notes:** Public references and synthetic facts; no customer data or private transcript. Later code/data requires its own licensing and disclosure record. Attribution does not imply endorsement.

## 10. Assets

**Link to assets:**

- [ ] Dataset
- [ ] Code
- [ ] Protocol
- [x] Other: [Complete dossier v1.0](FG_TIDA_Use_Case_Contextual_Trust_Recursive_Escalation_v1.0.md), supplied alongside this body. The relative link is for this two-file package; attach or link the dossier at an approved public location before using this body in a public issue.

**IP notes / attribution:** Iván Abril Palma credits Nelson Trasatti's discussion of 29 September 2026 for the motivating observation about agents contributing to trust specifications. The conversation with Larisa Ginosyan, Founder and CEO of MIHR (Machine Intelligence Human Ratio), on 28 September 2026 motivated the labeling inquiry. These personal-conversation attributions, their limits and the separate public references are retained in dossier PC01/PC02. MIHR participation is optional.
