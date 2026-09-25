# MYCO V3.2 — FINAL LAUNCH-READY, SCALE-READY IMPLEMENTATION-LOCKED PRODUCTION DESIGN AND BUILD PLAN

**Version:** 3.2 Final — Launch-Ready / Scale-Ready Implementation-Locked Edition  
**Owner:** Richard Curley  
**Status:** Authoritative Production Design and Construction Specification  
**Research/design freeze:** 25 September 2026  
**Primary commercial competitor set:** Lovable, Replit, Factory, Cognition/Devin, Cursor  
**Adjacent platform benchmarks:** GitHub Copilot/Agent HQ, OpenAI Codex  
**Build authority:** This document supersedes all earlier MYCO v1/v2/v3 drafts, including V3.0 and V3.1, where they conflict.  
**Launch principle:** scale architecture is built ahead of demand; scale infrastructure is activated only after a defined evidence/business gate.

# 0. AUTHORITY RULES

This specification defines both **what MYCO is** and **how it is built**.

There are four levels of authority, in this order:

1. **This V3.2 specification** — product behaviour, architecture, security, autonomy, launch scope, deferred-scale scope and completion rules.
2. **Phase Execution Contract** — exact files, schemas, routes, events, tools, tests and commands for one build phase.
3. **Architecture Decision Record (ADR)** — only for a genuinely new implementation fact not already fixed here.
4. **Source code** — must implement the three authorities above.

If source code conflicts with this specification, source code is wrong.

If Claude Code encounters a contradiction, impossible dependency, unavailable API, licence restriction, or an implementation fact that is genuinely undefined, it must **stop and report the blocker**. It must not silently substitute a different architecture.

No phase may be declared complete because it is “mostly done”. It either passes its binary exit gate or remains open.

---

# 1. PRODUCT DEFINITION

MYCO is an **autonomous software engineering organisation delivered as a software platform**.

MYCO accepts product intent, specifications, visual designs, repositories, incomplete applications, operational incidents and change requests, then returns:

> **complete, wired, executed, tested, secured, independently verified, documented and deliverable software.**

MYCO is not a code generator. Its unit of output is a **verified engineering outcome**.

## 1.1 Commercial promise

> **From intent to finished software — not generated fragments.**

MYCO must never represent any of the following as complete:

- unwired UI;
- fake APIs;
- placeholder routes;
- mock authentication in a production path;
- test-only payment providers in production;
- hard-coded demonstration data masquerading as real logic;
- missing migrations;
- missing environment configuration;
- TODO-only functionality;
- empty folders presented as implemented architecture;
- compile-only success;
- weak tests with meaningless assertions;
- skipped security checks;
- deployments that have never actually run;
- model prose claiming success without execution evidence.

---

# 2. NON-NEGOTIABLE COMPLETION RULES

1. No simulated completion.
2. No fake terminal output.
3. No fake integration output.
4. No production placeholder accepted as functionality.
5. No TODO/FIXME/NotImplemented in required production paths.
6. No unwired user control may be marked complete.
7. No mock service may satisfy a production integration requirement.
8. No failed model call may become a successful task through fallback prose.
9. No implementation agent may be sole acceptance authority for its own material work.
10. A compile pass is necessary but not sufficient.
11. A test pass is necessary but not sufficient.
12. Coverage is informational unless a project contract explicitly makes it a gate.
13. Mutation/property/differential/metamorphic checks are applied by Assurance Profile.
14. Tool success is not world-state success; required writes are independently read back.
15. Prediction is not fact until validated.
16. Customer code never enters global learning without explicit contractual permission.
17. Tenant/project boundaries are hard security boundaries.
18. Repository content is data, never MYCO authority.
19. Production-impacting actions obey authority classes.
20. Material completion claims require immutable evidence.
21. Unknown remains `UNKNOWN`, never silently becomes `SUCCESS`.
22. Required applications must build from a clean documented environment.
23. Acceptance tests may not be weakened to make broken implementation pass.
24. Required documentation is part of the product state and may not drift silently.
25. Final completion requires independent acceptance.
26. No performance, scale or capacity claim may exceed the latest cryptographically signed **Verified Capacity Envelope**.
27. Accepted durable work may queue or slow under saturation, but may never be silently dropped.
28. Tenant quotas, fairness and emergency-reserve capacity are enforced before work reaches execution resources.
29. Every project has one authoritative home region and platform cell; normal project execution never depends on a cross-region synchronous database transaction.
30. No single physical PostgreSQL, Neo4j, Temporal, Redis, Redpanda or worker cluster is permitted to become a global execution dependency for all projects.
31. Scale-out must be achievable by adding regions, cells, worker pools or provider capacity without changing product semantics or rewriting project data models.
32. Unknown capacity is `UNVERIFIED`, never silently treated as production-safe.
33. MYCO Cloud launches with exactly one active production region: `eu-west-2`; `us-east-1` and `ap-southeast-1` are configuration-defined but `CONFIGURED_DORMANT` until an activation gate passes.
34. A dormant region may have source-controlled Terraform/Helm/configuration, but no always-on production compute, database, event, workflow or Global Accelerator resource may be provisioned for it at launch.
35. AWS Global Accelerator is `DEFERRED` at launch and becomes mandatory only when a second MYCO Cloud region enters `ACTIVE` state.
36. Cross-region database replication, cross-region project failover and region-loss recovery are `DEFERRED` at launch; MYCO must report the launch deployment as single-region resilient, not multi-region recoverable.
37. A deferred capability is not a missing launch feature when its activation contract is implemented and its state is explicitly `DEFERRED_BY_SCALE_GATE`; it becomes mandatory immediately when its gate is approved.
38. No pre-launch acceptance test may imply that a dormant region is active or that multi-region failover has been verified.
39. The Design Envelope is an architecture target, never a requirement to pre-provision equivalent infrastructure.
40. Launch admission is bounded by the current signed Verified Envelope even when the configured Provisioned Envelope is higher.

---

# 3. AUTHORITATIVE PRODUCT LIFECYCLE

INTENT  
→ SOURCE INTAKE  
→ SOURCE PRESERVATION  
→ REPOSITORY TRUST SCAN  
→ PROJECT UNDERSTANDING  
→ AUTONOMY READINESS  
→ REQUIREMENT EXTRACTION  
→ CLARIFICATION  
→ REQUIREMENTS CONTRACT  
→ ARCHITECTURE  
→ SOFTWARE WORLD MODEL  
→ PROJECT DIGITAL TWIN  
→ BUILD PLAN  
→ ADAPTIVE WORKFORCE FORMATION  
→ ENGINEERING CELL FORMATION  
→ TASK FORKS  
→ SOFTWARE CONSTRUCTION  
→ INTEGRATION  
→ WIRING TRUTH  
→ EXECUTION  
→ TESTING  
→ TEST ADVERSARY  
→ SECURITY  
→ FORMAL ASSURANCE WHERE TRIGGERED  
→ AUTOMATIC REPAIR  
→ INDEPENDENT ACCEPTANCE  
→ DELIVERY PACKAGE  
→ OPTIONAL DEPLOYMENT  
→ DEPLOYMENT PROOF  
→ OPTIONAL OPERATIONS MODE  
→ STANDING GOALS  
→ INCIDENT RESPONSE  
→ MAINTENANCE  
→ ENGINEERING OUTCOME LEDGER  
→ CONTROLLED LEARNING.

---

# 4. SUPPORTED PROJECT MODES

MYCO must support:

1. New Product Build
2. Existing Repository Completion
3. Repository Repair
4. Feature Development
5. Refactoring
6. Modernisation
7. Framework Migration
8. Database Migration
9. Cloud Migration
10. Authentication Migration
11. Payment Provider Migration
12. API Migration
13. Monolith Decomposition
14. Security Audit and Remediation
15. Performance Optimisation
16. Accessibility Remediation
17. Dependency Modernisation
18. Production Incident Repair
19. UI Reproduction from Designs
20. Mobile Application Development
21. Infrastructure Remediation
22. Continuous Product Operations

---

# 5. AUTHORITATIVE PLATFORM ARCHITECTURE

All interfaces use the same backend Project Digital Twin.

MYCO uses a **global-edge-capable + regional platform-cell architecture**. At launch, exactly one MYCO Cloud region (`eu-west-2`) is active and all production projects are placed there. The region-router abstraction exists from day one, but multi-region routing is dormant until the scale-activation contract enables a second region. Global services perform only routing, identity bootstrap and small routing-directory duties. Project engineering state and execution remain inside the project's authoritative home region and cell.

**Global request path:**

MYCO Interfaces  
→ Global Edge / Region Router  
→ Regional API Gateway  
→ Authentication  
→ Global Directory lookup  
→ Home-region / cell resolution  
→ Tenant Boundary Enforcement  
→ Policy & Authority Engine  
→ Project Service  
→ Intake Service  
→ Requirements Service  
→ Architecture Service  
→ Autonomy Readiness Service  
→ MYCO Engineering Brain  
→ Software World Model  
→ Project Digital Twin  
→ Admission & Capacity Controller  
→ Build Supervisor  
→ Adaptive Agent Topology Controller  
→ Temporal Durable Workflow Engine  
→ 13 Permanent Departments  
→ Temporary Specialist Workforce  
→ Five-Model Gateway  
→ Provider Capacity Manager  
→ Context Intelligence Layer  
→ Tool Gateway  
→ Engineering Cell Service  
→ microVM Task Fork Scheduler  
→ Execution Engine  
→ Wiring Truth Engine  
→ Test Intelligence Engine  
→ Security Engine  
→ Verification Kernel  
→ Repair Engine  
→ Delivery Service  
→ Deployment Service  
→ Operations Service  
→ Standing Goal Engine  
→ Engineering Outcome Ledger  
→ Evidence Store  
→ Memory / ReasoningBank  
→ Learning Factory  
→ Billing / Entitlements  
→ Audit / Observability.

**Placement rules:**

- `tenant_id` is globally unique.
- `project_id` is globally unique and permanently resolves through the Global Directory to `home_region` + `cell_id`.
- A normal request concerning a project is executed in that project's home region.
- Project source, Digital Twin state, World Model state, task state, evidence and runtime state never require a synchronous cross-region write.
- Cross-region replication is architecturally supported but disabled at launch. It is activated only by the §39A scale-activation contract and only for data/residency policies that permit the destination region.
- Adding a new region or platform cell is configuration + infrastructure work, not an application-code fork.
- Every service that can scale horizontally is stateless or stores authoritative state only through its owning regional data service.
- Every responsibility has one production authority.

# 6. MYCO ENGINEERING BRAIN

The Engineering Brain is not an LLM.

It is composed of:

- Software World Model;
- Project Digital Twin;
- Requirements Graph;
- Architecture Graph;
- Code Intelligence Graph;
- Dependency Graph;
- Test Graph;
- Runtime State;
- Deployment State;
- Security Graph;
- Project Memory;
- Engineering ReasoningBank;
- Skills Registry;
- Engineering Pack Registry;
- Build Planning Engine;
- Adaptive Agent Topology Controller;
- Admission & Capacity Controller;
- Provider Capacity Manager;
- Context Broker;
- Context Optimizer;
- Model Gateway;
- Tool Intelligence Layer;
- Wiring Truth Engine;
- Verification Kernel;
- Evidence Engine;
- Standing Goal Engine;
- Engineering Outcome Ledger;
- Learning Factory.

Foundation models are replaceable reasoning workers inside MYCO.

---

# 7. SOFTWARE WORLD MODEL

Every project has one canonical World Model representing verified state for:

- requirements;
- assumptions;
- unresolved decisions;
- architecture;
- ADRs;
- repositories;
- branches;
- commits;
- files;
- packages;
- symbols;
- components;
- API routes;
- database schemas;
- migrations;
- events;
- queues;
- caches;
- external services;
- auth paths;
- permissions;
- UI screens;
- user journeys;
- dependencies;
- tests;
- infrastructure;
- deployments;
- logs;
- traces;
- metrics;
- findings;
- incidents;
- technical debt;
- documentation.

Every World Model fact records provenance and confidence class. Verified code/runtime facts outrank model inference.

---

# 8. PROJECT DIGITAL TWIN

The Digital Twin contains:

## 8.1 Desired state

Approved Requirements Contract + architecture + constraints + acceptance criteria.

## 8.2 Actual state

What source/runtime evidence proves currently exists.

## 8.3 Difference state

What is:

- absent;
- incomplete;
- unwired;
- broken;
- inconsistent;
- vulnerable;
- unverified;
- stale;
- undocumented.

The Build Supervisor reduces required **desired state − verified actual state** to zero.

---

# 9. REQUIREMENTS CONTRACT

Classification values are fixed:

- `CONFIRMED_REQUIREMENT`
- `INFERRED_REQUIREMENT`
- `ASSUMPTION`
- `RECOMMENDATION`
- `UNRESOLVED_DECISION`
- `EXCLUDED_SCOPE`
- `CONTRADICTION`
- `DEPENDENCY`
- `ACCEPTANCE_CRITERION`

Every requirement contains:

- `requirement_id` UUIDv7;
- wording;
- type;
- priority;
- source asset ID;
- exact source locator;
- provenance hash;
- affected components;
- dependencies;
- assurance profile;
- acceptance criteria;
- validation method;
- evidence requirement;
- approval state;
- version.

Assumptions never silently become requirements.

## 9.1 Progressive execution

Confirmed requirement slices may execute while unrelated decisions remain unresolved. No task may consume an unresolved requirement as if it were confirmed.

---

# 10. ASSURANCE PROFILES

Every project is assigned one of four Assurance Profiles.

## AP1 — Standard

Ordinary low-risk application.

Required:

- build;
- normal unit/integration/E2E;
- Wiring Truth;
- standard security;
- independent acceptance.

## AP2 — Business Critical

Meaningful business data, payments, customer operations.

Adds:

- mutation threshold ≥80%;
- property testing for applicable invariants;
- cross-model verification of material changes;
- rollback proof;
- stronger security.

## AP3 — High Integrity

Finance, permissions, sensitive enterprise systems.

Adds:

- mutation threshold ≥90%;
- differential/metamorphic tests where applicable;
- offensive security;
- formal-method assessment for trigger classes;
- stricter approval.

## AP4 — Regulated/Critical

Safety-sensitive, regulated or highly consequential systems.

Adds:

- mandatory formal-method assessment;
- maximum independent validation;
- restricted production autonomy;
- explicit specialist/management release authority;
- project-specific proof obligations.

Architecture/Security may raise a profile. It may not silently lower it.

---

# 11. COMPLETION THRESHOLDS

Unless a project sets a stricter rule:

- confirmed requirements satisfied: **100%**;
- required Wiring Truth paths: **100% proven**;
- required user journeys: **100% pass**;
- required migrations from clean DB: **100% pass**;
- required builds: **100% pass**;
- required integration tests: **100% pass**;
- required E2E tests: **100% pass**;
- required scanners execute: **100%**;
- unresolved critical findings: **0**;
- unresolved high findings: **0 unless explicit authorised risk acceptance**;
- production placeholder/stub findings: **0**;
- undocumented required secrets: **0**;
- known broken required functionality: **0**;
- required deployment health checks: **100%**;
- required documentation: **100% current**.

Mutation default:

- AP1 ≥70%;
- AP2 ≥80%;
- AP3 ≥90%;
- AP4 ≥90%, with critical-domain modules subject to project-specific higher threshold.

Mutation score never compensates for missing functionality.

---

# 12. AUTONOMY READINESS

Weighted readiness score: 0–100.

- R0: `<40` or hard blocker
- R1: `40–54`
- R2: `55–69`
- R3: `70–84`
- R4: `85–94`
- R5: `95–100` and no hard blocker

Hard blockers:

- non-reproducible build;
- unresolved repository trust failure;
- exposed secrets;
- critical exploitable vulnerability in required engineering path;
- inability to reconstruct environment;
- inability to establish tenant/security boundary;
- production mutation requested without tested backup/rollback;
- production deployment requested without health/rollback path.

Readiness dimensions and weights:

- build reproducibility 15;
- tests 15;
- environment reproducibility 10;
- observability 10;
- security 15;
- documentation 10;
- deployment repeatability 10;
- rollback/backup 10;
- architecture legibility 5.

Autonomy cannot exceed verified readiness.

---

# 13. ENGINEERING QUALITY SCORE

Evidence-based only.

- requirement satisfaction 15;
- Wiring Truth 15;
- test strength 15;
- security 15;
- architecture integrity 10;
- maintainability 10;
- performance 5;
- accessibility 5;
- dependency health 5;
- observability/deployability 5.

Total: 100.

Hard completion gates override score.

---

# 14. DATA CLASSIFICATION

- `D0_PUBLIC` — any organisation-approved provider.
- `D1_INTERNAL` — approved managed providers.
- `D2_CONFIDENTIAL` — only providers satisfying tenant region/retention/privacy policy.
- `D3_RESTRICTED` — private/local/self-hosted providers only unless explicit exception.

The Model Gateway rejects routing that violates classification.

---

# 15. FIVE-LLM ARCHITECTURE

MYCO must maintain five distinct model families/providers in the active intelligence pool. Every seat is adapter-driven and replaceable.

**Research-frozen defaults on 19 September 2026:**

1. **Anthropic Claude Opus 5** — lead architecture, difficult debugging, deep design critique.
2. **OpenAI GPT-6 Astra** — hardest end-to-end implementation/reasoning and independent review.
3. **Google Gemini 3.8 Flash** — fast long-horizon multimodal engineering, screenshots/video, large-context work.
4. **DeepSeek V4.1 Flash (`deepseek-flash`)** — economical high-volume specialist work.
5. **Qwen3-Coder-480B-A35B-Instruct** — self-hosted/private coding and sovereign fallback.

Specific model IDs live only in `config/models/manifest.yaml`; engineering logic refers to logical capability seats, never hard-coded vendor names.

## 15.1 Required logical seats

- `LEAD_REASONER`
- `IMPLEMENTATION_LEAD`
- `INDEPENDENT_VERIFIER`
- `FAST_EFFICIENT_WORKER`
- `PRIVATE_SOVEREIGN_WORKER`

Any one provider may occupy more than one capability ranking internally, but five distinct families/providers must remain available to the router unless a sovereign deployment explicitly substitutes five approved local families.

## 15.2 Routing objective

MYCO optimises, **after policy, residency and provider-capacity eligibility are satisfied**:

> probability of verified completion / total cost / elapsed time

Total cost includes retries, repair, verifier work, compute, failed trajectories and human intervention.

A provider/model with no permitted remaining capacity is not a routing candidate; the task queues rather than degrading the completion contract.

## 15.3 Cross-model rule

For AP2+ material changes, producer and independent verifier use different model families when two permitted families are available.

---

# 16. 13 PERMANENT ENGINEERING DEPARTMENTS

The permanent departments are locked:

1. Orchestrator
2. Planner
3. Architecture
4. Backend
5. Frontend
6. Infrastructure
7. Integration
8. Security
9. Validation
10. Deployment
11. Monitoring
12. Optimisation
13. Documentation

They are departments, not prompt personas. Each has workload identity, typed input/output, tools, policies, budgets and evidence duties.

Temporary specialists are spawned beneath departments and terminated after the bounded task unless the specialist is an approved Operations-mode service.

---

# 17. AGENT CAPABILITY CONTRACT

Every permanent agent and temporary worker has:

- unique type/version/instance IDs;
- department;
- supported task types;
- input schema;
- output schema;
- memory access;
- knowledge access;
- exact allowed tools;
- prohibited tools;
- filesystem scope;
- database scope;
- network scope;
- credential scope;
- authority level;
- compute budget;
- model budget;
- timeout;
- retry policy;
- evidence contract;
- verification contract;
- rollback/compensation policy;
- escalation path.

No unrestricted universal worker exists.

---

# 18. ADAPTIVE AGENT TOPOLOGY

Before execution the Topology Controller calculates:

- decomposability;
- dependency depth;
- shared-state contention;
- uncertainty;
- tool density;
- context coupling;
- verification cost;
- expected token cost;
- expected parallel gain.

Permitted topologies:

- single specialist;
- specialist + verifier;
- sequential chain;
- manager/worker tree;
- parallel swarm;
- competing independent teams;
- evolutionary candidate search.

Parallelism is never assumed to be automatically better.

---

# 19. ENGINEERING CELLS + TASK FORKS

Each project owns a persistent Engineering Cell containing:

- verified dependencies;
- compiler/runtime toolchain;
- development services;
- development database;
- emulators;
- package caches;
- framework tooling;
- optional GPU resources.

Consequential task workflow:

verified Engineering Cell snapshot  
→ immutable/copy-on-write microVM task fork  
→ Git task branch  
→ implementation  
→ task tests  
→ verification  
→ merge proposal  
→ integration checks  
→ merge or discard.

Database state is never “merged”. Schema/data changes are represented by migrations and seed fixtures, then reapplied to the integration environment.

---

# 20. GIT AND MERGE MODEL

Authoritative source control: Git + GitHub reference implementation.

Protected branch: `main`.

Build branch:

`integration/<build_id>`

Task branch:

`task/<task_id>`

Repair branch:

`repair/<task_id>-<attempt>`

Release branch:

`release/<version>`

Workers never write directly to `main`.

Integration Agent performs three-way merge. Any conflict creates a durable Integration task. After merge, affected integration/E2E/wiring/security scopes rerun.

Every passed build phase receives an annotated Git tag:

`v3.2-phase-XX-<slug>`

---

# 21. WIRING TRUTH ENGINE

Every required user journey receives immutable `journey_id`.

Example:

`JNY-AUTH-LOGIN-001`

Browser/client injects:

`X-MYCO-Journey-ID: JNY-AUTH-LOGIN-001`

OpenTelemetry propagates the same journey across spans.

Required trace can include:

browser action  
→ frontend handler  
→ request client  
→ API route  
→ authentication/policy  
→ domain handler  
→ database/external provider  
→ persisted/read-back state  
→ response  
→ frontend state update  
→ visible required outcome.

Mandatory node missing = `WIRING_FAILED`.

A static route existing is not sufficient; required paths must be executed at runtime.

---

# 22. PRODUCTION STUB DETECTOR

Mandatory scan rules include:

- TODO;
- FIXME;
- XXX;
- `NotImplemented`;
- placeholder response;
- hard-coded demo data;
- fake auth;
- fake payment state;
- mock provider in production config;
- test fixture imported by production code;
- dead route;
- empty success callback;
- unconditional success return;
- dummy secret;
- dev-only bypass;
- disabled permission check;
- disabled scanner/test gate.

Mocks are permitted in tests and dedicated local-development fixtures only.

---

# 23. TEST INTELLIGENCE ENGINE

Supported modes:

- unit;
- integration;
- API;
- contract;
- database;
- migration;
- browser E2E;
- mobile E2E;
- visual regression;
- accessibility;
- performance/load;
- mutation;
- property-based;
- differential;
- metamorphic;
- security;
- deployment;
- formal verification where triggered.

## 23.1 Independent Acceptance Vault

Verifier-owned cases are generated from approved requirements but are not necessarily exposed to implementing workers. Hidden tests may not contain hidden product requirements.

---

# 24. FORMAL ASSURANCE TRIGGERS

Formal-method assessment is mandatory for code controlling:

- monetary ledger integrity;
- irreversible financial calculation;
- authorisation/permission inheritance;
- tenant isolation invariant;
- exactly-once financial processing;
- distributed consensus/state coordination;
- cryptographic state machine;
- safety-critical workflow;
- explicit regulated integrity requirement.

Primary tools:

- TLA+/TLC for distributed/state-machine models;
- Z3/SMT for constraints/invariants;
- Dafny for verified executable logic where suitable;
- Lean for highest-assurance mathematical proof obligations.

For AP3/AP4, declining a triggered formal method requires an ADR and independent Validation approval.

---

# 25. SECURITY ARCHITECTURE

Security pipeline:

intake risk  
→ threat model  
→ architecture review  
→ dependency policy  
→ secure implementation  
→ secret scan  
→ static analysis  
→ dependency vulnerability scan  
→ container/IaC scan  
→ supply-chain provenance  
→ runtime attack testing  
→ exploit verification  
→ remediation  
→ independent revalidation.

Security findings states:

- `SUSPECTED`
- `REPRODUCED`
- `CONFIRMED`
- `REPAIRED`
- `REVERIFIED`
- `ACCEPTED_RISK`

---

# 26. TOOL FABRIC

Protocol responsibilities are fixed:

- **MCP** — Agent ↔ Tool/Data.
- **A2A** — Agent ↔ Agent interoperability.
- **Temporal** — durable workflow/time/state.
- **MYCO Engineering Brain** — intelligence, governance and project truth.

Tool classes:

- T0 Public read
- T1 Project read
- T2 Analyse/calculate
- T3 Workspace write
- T4 Repository mutation
- T5 External dev-system write
- T6 Cloud/infrastructure mutation
- T7 Production deployment
- T8 Destructive/high-impact production action
- T9 Prohibited

---

# 27. ACTION VERIFICATION

Dangerous action pipeline:

proposal  
→ task-scope check  
→ identity check  
→ OPA policy  
→ authority  
→ blast-radius analysis  
→ dry run/simulation where possible  
→ approval if required  
→ execute  
→ independent read-back verification  
→ evidence  
→ World Model update.

---

# 28. LIFECYCLE HOOKS

Supported hook points:

- BeforeTask
- AfterTask
- BeforeModel
- AfterModel
- BeforeTool
- AfterTool
- BeforeWrite
- AfterWrite
- BeforeMerge
- AfterMerge
- BeforeDeployment
- AfterDeployment
- OnValidationFailure
- OnIncident

Hook execution format:

- signed OCI/WASI artifact;
- Wasmtime sandbox;
- declared permissions;
- no implicit filesystem/network access;
- hard timeout;
- typed input/output;
- immutable version;
- audit record.

Cosign verifies signatures.

---

# 29. ENGINEERING PACKS

Pack format is a signed OCI artifact containing:

- `pack.yaml`
- `skills/`
- `workers/`
- `knowledge/`
- `validators/`
- `tools/`
- `policies/`
- `tests/`
- `sbom.json`

Install pipeline:

signature  
→ licence  
→ compatibility  
→ vulnerability scan  
→ permission review  
→ evaluation suite  
→ registry install.

Semantic Versioning is mandatory.

---

# 30. STANDING ENGINEERING GOALS

Goal contract fields:

- goal ID;
- metric;
- evidence source;
- threshold;
- evaluation frequency;
- assurance profile;
- authority level;
- repair policy;
- escalation rule;
- verification method.

Violation pipeline:

DETECT  
→ INVESTIGATE  
→ PLAN  
→ REPAIR  
→ VERIFY  
→ DEPLOY IF AUTHORISED  
→ VERIFY RECOVERY.

---

# 31. ENGINEERING OUTCOME LEDGER

Required engineering-outcome metrics:

- time per verified requirement;
- cost per verified requirement;
- time per finished feature;
- cost per finished feature;
- first-pass acceptance;
- human-intervention rate;
- autonomous completion ratio;
- repair success rate;
- regression escape rate;
- security escape rate;
- mutation score;
- production defect rate;
- deployment success rate;
- incident MTTR;
- model cost;
- compute cost;
- cost/time to finished application.

Required platform-economics metrics:

- infrastructure cost per verified requirement;
- infrastructure cost per completed build;
- infrastructure cost per active project-hour;
- model cost per verified requirement;
- microVM utilisation;
- worker-slot utilisation;
- model/provider utilisation;
- warm-capacity idle cost;
- event-stream cost per project;
- storage cost per project;
- cost at each Verified Capacity Envelope;
- marginal cost of the next 1,000 concurrent engineering tasks;
- marginal cost of the next 100 concurrent builds;
- cost change at 2×, 10× and 100× workload where a Verified Capacity Envelope exists.

Primary commercial metric:

> **Cost and elapsed time to independently verified finished software.**

Primary scale-economic metric:

> **Marginal infrastructure + model cost per additional independently verified engineering outcome at the current Verified Capacity Envelope.**

No extrapolated capacity or cost figure may be presented as measured. Extrapolation must be labelled `MODELLED`, include assumptions, and remain separate from `VERIFIED` results.

# 32. CONTROLLED SELF-LEARNING

No production experience directly rewrites production behaviour.

Observation  
→ Pattern  
→ Learning Candidate  
→ Evidence  
→ Offline Evaluation  
→ Regression  
→ Adversarial Evaluation  
→ MYCO-Bench  
→ Version  
→ Canary  
→ Monitoring  
→ Promotion or Rollback.

Learning may improve:

- skill;
- retrieval strategy;
- context compression;
- model routing;
- tool workflow;
- planning policy;
- repair strategy.

Learning may not silently expand authority, weaken security, disable logging, cross tenants or ingest unapproved customer source.

---

# 33. SOVEREIGN DEPLOYMENT MODES

1. MYCO Cloud
2. MYCO Hybrid — MYCO control plane + customer compute/data plane
3. MYCO Private Cloud/BYOC
4. MYCO On-Prem
5. MYCO Air-Gapped

All five deployment modes preserve the same Project Digital Twin, evidence, verification, admission and Platform Cell semantics. Sovereign deployments may use `home_region=local` and one or more local cells.

Air-gapped mode must operate with:

- local model pool;
- offline OCI registry;
- offline package mirrors;
- local databases/object storage;
- no mandatory runtime internet dependency.

---

# 34. MYCO EVERYWHERE

Control surfaces:

- Web
- Desktop
- CLI
- VS Code
- JetBrains
- Mobile
- Slack
- Teams
- Jira/Linear actions
- REST API
- MCP/A2A integrations

All surfaces are remote controls into the same backend Project Digital Twin. Interface conversation state is never authoritative project truth.

---

# 35. USER EXPERIENCE RULE

> **Simple by default, powerful on demand.**

Non-technical users primarily see:

- create project;
- upload/specify requirements;
- clarification;
- approvals;
- progress;
- preview;
- evidence;
- delivery.

Developers can expand:

- repository tree;
- IDE;
- terminal;
- architecture graph;
- agent workforce;
- model routing;
- diffs;
- tests;
- Wiring Truth;
- security;
- runtime logs;
- deployment;
- costs.

The supplied MYCO visual reference remains authoritative for aesthetic direction: bright futuristic glass panels, white/light work surfaces, blue/purple/cyan accents, premium space/future background, large natural-language creation area, persistent navigation.

Initial executable design tokens are fixed as:

- page-light: `#ECECF7`
- primary-blue: `#77A8DC`
- secondary-blue: `#ADC1E5`
- soft-pink: `#E7CCD2`
- primary-purple: `#7B6ECB`
- accent-magenta: `#D692B8`
- deep-indigo: `#44499E`
- positive-lime: `#A4BC56`
- glass-background: `rgba(255,255,255,0.58)`
- glass-border: `rgba(255,255,255,0.72)`
- glass-blur: `20px`
- card-radius: `24px`
- control-radius: `14px`

These are starting tokens extracted from the authoritative visual reference and may only change through an approved design ADR, not ad hoc screen-by-screen styling.

---

# 36. DATA OWNERSHIP, REGIONAL CELLS AND SERVICE BOUNDARIES

## 36.1 Logical relational authority and PostgreSQL physical topology

`apps/api` remains the sole authority for platform relational writes and Drizzle migrations.

The logical schemas remain:

- `identity`
- `projects`
- `requirements`
- `architecture`
- `build`
- `agents`
- `models`
- `tools`
- `runtime`
- `testing`
- `security`
- `deployment`
- `operations`
- `knowledge`
- `learning`
- `billing`
- `governance`
- `memory`

Physical deployment is **not** one global PostgreSQL instance.

MYCO Cloud uses three PostgreSQL authority classes:

1. one **Keycloak identity database cluster** owned only by Keycloak;
2. one **Global Control PostgreSQL authority** for low-volume global application metadata and routing; and
3. one or more **Regional Platform Cells**, each with an independent PostgreSQL HA cluster for project engineering state.

The Global Control PostgreSQL authority stores:

- organisation records;
- application membership/role metadata;
- subscription/entitlement authority;
- `tenant_id`;
- `project_id`;
- `home_region`;
- `cell_id`;
- residency policy ID;
- cell lifecycle state;
- migration state;
- region/cell health summary;
- routing version.

It does not store project source, prompts, World Model data, Digital Twin data, task payloads, evidence bodies or project secrets.

Keycloak owns its internal user/session database. `apps/api` does not write Keycloak tables.

MYCO Cloud launch identity topology:

- active production region: `eu-west-2` only;
- Keycloak application replicas: minimum 3 in `eu-west-2`, spread across three failure domains where available;
- Keycloak PostgreSQL: CloudNativePG PostgreSQL 18.6 HA cluster inside `eu-west-2`;
- no cross-region Keycloak database or application standby is provisioned at launch;
- access tokens are verified by active-region APIs locally using cached/pinned OIDC issuer/JWKS data;
- ordinary authenticated API requests do not synchronously call Keycloak or the Keycloak database;
- login, token refresh, logout and identity administration use the identity authority;
- identity-authority outage may block new authentication/refresh but does not invalidate already-issued tokens before their normal expiry;
- in-region identity recovery follows §39;
- cross-region identity DR becomes mandatory only at scale stage `S3_MULTI_REGION_DR`.

Schema/table placement is fixed:

- global `identity` application organisation/membership authority lives in Global Control PostgreSQL;
- global `billing` subscription/entitlement authority lives in Global Control PostgreSQL;
- global project-placement and residency records live in Global Control `governance`;
- project-scoped `projects`, `requirements`, `architecture`, `build`, `agents`, `models`, `tools`, `runtime`, `testing`, `security`, `deployment`, `operations`, `knowledge`, `learning` and `memory` records live in the project's Platform Cell;
- project/audit rows in `governance` live in the project's Platform Cell;
- regional services may keep read-only membership/entitlement projections, but projections are never write authority;
- usage events are written regionally and aggregated idempotently into global billing authority.

Each Regional Platform Cell uses:

- PostgreSQL 18.6;
- CloudNativePG 1.30.1;
- three PostgreSQL instances across three availability zones in MYCO Cloud;
- one writable primary;
- two replicas;
- CloudNativePG-managed PgBouncer pooler;
- PITR;
- WAL archiving to regional object storage;
- exact image digests pinned in infrastructure manifests.

For single-datacentre sovereign deployments, the same logical contract applies; the number of failure domains may be reduced only through an explicit deployment profile and acceptance of the resulting availability limitation.

High-volume relational tables are partitioned from their first production migration:

- `build.tasks` — hash by `project_id`;
- `runtime.tool_calls` — hash by `project_id`, then range by month;
- `runtime.command_runs` — hash by `project_id`, then range by month;
- `models.usage` — hash by `tenant_id`, then range by month;
- `governance.audit_events` — hash by `tenant_id`, then range by month;
- `testing.results` — hash by `project_id`, then range by month;
- `security.findings` — hash by `project_id`;
- `operations.incidents` — hash by `tenant_id`, then range by month;
- `learning.trajectory_index` — hash by `tenant_id`, then range by month.

Initial partition count for every hash-partitioned high-volume table is **64 partitions per cell**. Partition count changes require an ADR plus migration/load evidence.

A cell is closed to new project placement when any of these remain above threshold for 30 consecutive minutes:

- PostgreSQL primary CPU >65%;
- pooled database connections >70% of configured safe maximum;
- persistent volume utilisation >70%;
- write-ahead-log/archive lag violates RPO;
- p95 database query latency >100 ms for platform-owned indexed control queries.

Closing a cell to new placement does not interrupt existing projects.

No request path may perform a cross-cell SQL join.

### 36.1.1 Project placement

The Cell Allocator places a new project into the least-loaded eligible cell satisfying:

1. tenant residency policy;
2. required sovereign mode;
3. required model/data classification;
4. cell health;
5. Verified Capacity Envelope;
6. Provisioned Capacity Envelope;
7. tenant entitlement.

The resulting `home_region` and `cell_id` are durable routing facts.

### 36.1.2 Project migration between cells

Project migration is a durable state machine:

`REQUESTED`  
→ `VALIDATE_TARGET`  
→ `BLOCK_NEW_MUTATING_WORK`  
→ `DRAIN_OR_CHECKPOINT_RUNNING_WORK`  
→ `SNAPSHOT_SOURCE`  
→ `REPLICATE_RELATIONAL_STATE`  
→ `REPLICATE_GRAPH_JOURNAL`  
→ `VERIFY_OBJECT/EVIDENCE DIGESTS`  
→ `VERIFY_COUNTS + REFERENTIAL INTEGRITY`  
→ `ACTIVATE_TARGET_READ_ONLY`  
→ `RUN ACCEPTANCE CHECKS`  
→ `ATOMIC_DIRECTORY_CUTOVER`  
→ `ACTIVATE_TARGET_WRITES`  
→ `OBSERVE`  
→ `RETIRE_SOURCE`.

There is no dual-write period. At launch, migration targets are restricted to cells inside `eu-west-2`; cross-region project migration is disabled until `S2_SECOND_REGION_ACTIVE`.

Before `ATOMIC_DIRECTORY_CUTOVER`, rollback returns to the source cell. After cutover, rollback is a new migration in the opposite direction.

Python AI services never write PostgreSQL directly. They use authenticated internal APIs/events.

## 36.2 World Model / Neo4j

The World Model Service remains the sole graph-mutation authority.

There is no global mutable Neo4j graph shared by every project.

Each Platform Cell owns one or more graph shards. Every node and relationship carries:

- `tenant_id`;
- `project_id`;
- provenance ID;
- confidence class;
- graph schema version.

Normal graph queries are always scoped to one `tenant_id` + `project_id`.

Before acknowledging a material graph mutation, the World Model Service persists an idempotent mutation journal record containing:

- `mutation_id` UUIDv7;
- `tenant_id`;
- `project_id`;
- previous graph version;
- target graph version;
- mutation payload digest;
- source evidence IDs;
- timestamp.

The journal is stored durably in the cell PostgreSQL `knowledge` schema. Neo4j is rebuilt by replay if required.

A graph shard is closed to new project placement when p95 project-scoped query latency exceeds 200 ms or safe storage/CPU thresholds are exceeded for 30 minutes. New graph shards are added without changing project semantics.

Cross-project learning never performs unrestricted live graph joins. It consumes privacy-filtered derived learning artifacts.

## 36.3 Redis

Redis is regional and cell-scoped.

Permitted only for:

- cache;
- rate limiting;
- transient coordination;
- short-lived presence;
- non-authoritative capacity counters.

Redis is never authoritative durable workflow, routing, task, approval, evidence or billing state.

Loss of Redis may reduce performance but may not lose committed engineering work.

## 36.4 Object storage

S3 API is authoritative for large immutable objects.

- Local development: MinIO.
- MYCO Cloud: regional S3-compatible object storage.
- Sovereign mode: customer-approved S3-compatible object storage.

Object key prefix is:

`/<tenant_id>/<project_id>/<object_class>/<sha256-or-object-id>`

Required:

- versioning;
- SHA-256 digest;
- server-side encryption;
- object retention lock for immutable evidence where supported;
- lifecycle policy;
- regional placement matching residency policy.

Cross-region object replication is disabled at launch. At scale stage `S3_MULTI_REGION_DR` or later it may be enabled only when the tenant's residency policy permits the destination region.

## 36.5 Event stream / Redpanda

Each region owns an independent Redpanda cluster using Kafka protocol and CloudEvents 1.0 envelopes.

Partition key for project events:

`<cell_id>|<tenant_id>|<project_id>`

Partition key for tenant-wide events:

`<cell_id>|<tenant_id>`

No single partition may carry all platform work.

Partition count is capacity-managed. A topic must scale out before either of these remains true for 15 minutes:

- busiest partition >60% of measured safe throughput;
- consumer lag p95 >5 seconds for control-plane topics.

Ordering is guaranteed only inside a partition key where the event contract requires ordering.

Cross-region event replication is disabled at launch. If later activated for disaster recovery, it remains asynchronous disaster-recovery plumbing and never becomes the normal synchronous execution path.

## 36.6 Temporal durable workflow topology

Temporal is regional.

Each Platform Cell has a dedicated Temporal namespace:

`myco-<region>-<cell_id>`

Task Queue naming:

`<service>.<cell_id>.<work_class>`

Examples:

- `build.c001.interactive`
- `build.c001.background`
- `verification.c001.interactive`
- `operations.c001.incident`

Workflow IDs contain immutable project/task identity and must be idempotent.

A workflow uses `Continue-As-New` before either:

- 10,000 history events; or
- 10 MiB serialized workflow history;

whichever occurs first.

A single parent workflow may create at most 500 concurrently open child workflows. Larger task graphs are partitioned into supervisor sub-workflows.

Worker poller autoscaling is enabled where the SDK supports it. Worker execution slots use resource-based tuning unless a benchmark proves a fixed slot allocation is superior for that work class.

Temporal workflow state may not contain large source files, repository archives, model transcripts or evidence bodies; it stores references to authoritative objects.

## 36.7 Global Directory availability rule

The Global Directory is a routing authority, not a project execution database.

Each active region holds a read replica/cache of project placement records. At launch the only active-region copy is in `eu-west-2`; dormant-region copies do not run.

If the Global Directory writer is unavailable:

- existing routed projects continue using their last verified placement record;
- new tenant creation, new project placement and project migration pause;
- existing regional engineering workflows continue;
- no project is silently reassigned.

A directory record change is accepted only after durable commit and routing-version increment.

# 37. INTERNAL API RULES

- External/public API prefix: `/api/v1`.
- Internal service API prefix: `/internal/v1`.
- OpenAPI is mandatory for synchronous JSON APIs.
- RFC 9457 Problem Details is mandatory for error responses.
- UUIDv7 is mandatory for new business identifiers.
- UTC is mandatory internally.
- RFC3339 timestamps are mandatory externally.
- Service-to-service identity uses SPIFFE mTLS.
- Human identity uses OIDC/OAuth2 through Keycloak reference IdP.
- OPA makes policy decisions.
- External clients may request an allowed region preference at project creation but may never supply authoritative `cell_id`.
- `home_region` and `cell_id` used for execution come only from the Global Directory / local sovereign directory.
- Cross-region internal forwarding is disabled at launch. When scale stage `S2_SECOND_REGION_ACTIVE` or later is active, forwarding uses SPIFFE mTLS and a signed routing context containing `tenant_id`, `project_id`, `home_region`, `cell_id`, `routing_version`.
- A request with routing metadata that disagrees with the current directory record is rejected or re-routed before mutation.

---

# 38. SECURITY DEFAULTS

- TLS 1.3 where supported for service transport.
- Secrets in Vault; never plaintext in application DB.
- Sensitive credentials are never returned to clients.
- Agent credentials are short-lived.
- Evidence/release digests use SHA-256.
- Release/Pack signatures use Cosign.
- Workload identity uses SPIFFE/SPIRE.
- Production CORS uses explicit allowlist.
- Debug/dev users are forbidden in production startup.

---

# 39. DISASTER RECOVERY DEFAULTS

MYCO Cloud launch recovery is intentionally **single-region, multi-AZ**. The launch system must survive ordinary node, pod, worker, database-instance and availability-zone failures inside `eu-west-2`, but it does not claim recovery from total `eu-west-2` regional loss.

## 39.1 Launch recovery boundary — `S0_LAUNCH_SINGLE_REGION`

**Global Directory / Global Control PostgreSQL:**

- writer authority: `eu-west-2`;
- CloudNativePG HA inside the active region;
- continuous WAL archive to versioned regional object storage;
- PostgreSQL PITR enabled;
- in-region RPO target: ≤5 minutes;
- in-region RTO target: ≤60 minutes;
- no cross-region standby is provisioned;
- total-region outage state: `REGION_UNAVAILABLE`, not automatic failover.

**Keycloak identity authority:**

- application replicas across active-region failure domains;
- CloudNativePG HA inside `eu-west-2`;
- PITR + WAL archive;
- no cross-region standby at launch;
- already-issued valid access tokens continue to be verified locally while the relevant active-region services remain available.

**Every launch Platform Cell:**

- PostgreSQL PITR enabled;
- WAL archive monitored against RPO;
- object storage versioning enabled;
- World Model mutation journal backed up with PostgreSQL;
- Neo4j backup/rebuild path tested;
- Temporal persistence recovery tested;
- Redpanda retention/replication configured within the active region;
- Vault recovery material protected separately;
- full restore rehearsal before production launch and quarterly after commercial launch.

Backup existence alone is insufficient; restore must be executed and evidenced.

## 39.2 Region-wide outage contract at launch

If `eu-west-2` becomes unavailable while the deployment stage is `S0_LAUNCH_SINGLE_REGION` or `S1_SINGLE_REGION_HORIZONTAL_SCALE`:

1. new project/task admission stops;
2. existing connections fail with explicit regional-unavailable state rather than being silently routed elsewhere;
3. no project data is moved to a dormant region;
4. committed state remains subject to the durability guarantees of the active-region services and backups;
5. status surfaces report `SINGLE_REGION_OUTAGE`;
6. recovery resumes in `eu-west-2` when the region/services recover;
7. MYCO may not claim a multi-region RTO for that event.

## 39.3 Deferred multi-region disaster recovery

Cross-region standby databases, object replication, identity standby, Global Directory standby, regional failover orchestration and project failover are authoritative future capabilities but are marked `DEFERRED_BY_SCALE_GATE` at launch.

They become mandatory at scale stage `S3_MULTI_REGION_DR` and must then pass the deferred acceptance contract in §39A before any multi-region recovery claim is made.

If tenant policy permits no DR region, MYCO reports that tenant/project as **single-region only** even after platform-wide multi-region DR exists.

# 39A. PLATFORM SCALE, CAPACITY, LAUNCH AND DEFERRED GLOBAL DELIVERY CONTRACT

This section is a hard production contract.

> **Scale architecture is built ahead of demand. Scale infrastructure is provisioned and verified only when demand, contract, residency or resilience requirements justify it.**

> **MYCO must have no architectural ceiling below the Design Capacity Envelope that requires a product-semantic rewrite, global database replacement, tenant-data remodel or abandonment of the Project Digital Twin / verified-outcome architecture.**

Capacity is represented by three authoritative envelopes. They must never be conflated.

## 39A.1 Capacity envelope types

### `DESIGN_ENVELOPE`

The architecture target. It defines what MYCO must be able to reach by adding cells, worker pools, storage, provider capacity and regions without redesigning product semantics or the project data model.

A Design Envelope is not a throughput claim.

### `VERIFIED_ENVELOPE`

The highest capacity actually demonstrated by a reproducible MYCO-Bench run with immutable evidence.

Every Verified Envelope records:

- Git commit;
- benchmark version;
- deployment stage;
- active region/cell count;
- infrastructure manifests and digests;
- machine/resource classes;
- service replica counts;
- database configuration;
- worker-slot configuration;
- model/provider configuration;
- workload definition;
- run duration;
- achieved throughput/concurrency;
- p50/p95/p99 latency;
- error rate;
- saturation point;
- failure/recovery results;
- infrastructure/model cost;
- evidence artifact digests.

### `PROVISIONED_ENVELOPE`

The maximum capacity the currently deployed infrastructure and configured autoscaling limits are permitted to supply without changing the deployment manifest.

Provisioned does **not** mean all capacity is running idle. Autoscaled resources may be cold until demand requires them.

Admission capacity for a workload dimension is always:

> `min(VERIFIED_ENVELOPE, PROVISIONED_ENVELOPE, PROVIDER_CAPACITY, TENANT_ENTITLEMENT)`

No UI, sales material, benchmark report, due-diligence package or acquisition material may describe the Design Envelope as Verified or Provisioned.

## 39A.2 Design Capacity Envelope

The architecture target remains:

| Dimension | Design target |
|---|---:|
| user accounts | 10,000,000 |
| organisations / tenants | 1,000,000 |
| stored projects | 10,000,000 |
| simultaneously active projects | 100,000 |
| concurrent active builds | 10,000 |
| runnable/running engineering tasks | 100,000 |
| concurrent microVM task forks | 25,000 |
| simultaneous model/tool operations in scheduler state | 100,000 |
| open/dormant durable workflow executions | 5,000,000 |
| sustained public/control API traffic | 20,000 requests/second |
| one-minute API admission spike | 60,000 requests/second |
| sustained internal event production | 200,000 events/second |
| object/evidence namespace | 5 PB addressable |
| active regions architecture can support without product rewrite | ≥3 |
| availability zones per active MYCO Cloud region | 3 where provider supports 3 |

These are architectural constraints, not launch infrastructure requirements and not measured claims.

## 39A.3 Launch deployment stage — `S0_LAUNCH_SINGLE_REGION`

MYCO Cloud launches with:

- cloud provider: AWS reference implementation;
- active production region: `eu-west-2`;
- active production Platform Cells: `eu-west-2-c0001` only;
- `us-east-1`: `CONFIGURED_DORMANT`;
- `ap-southeast-1`: `CONFIGURED_DORMANT`;
- AWS Global Accelerator: `DEFERRED_BY_SCALE_GATE` and not provisioned;
- cross-region PostgreSQL replication: disabled;
- cross-region object replication: disabled;
- cross-region event replication: disabled;
- cross-region identity standby: disabled;
- cross-region project failover: disabled.

Launch ingress is:

DNS / TLS endpoint  
→ `eu-west-2` regional load balancer  
→ regional Kubernetes ingress  
→ regional API/web services.

The region-router abstraction still resolves every project from the Global Directory. At S0 every MYCO Cloud project resolves to `eu-west-2` and an active `eu-west-2-*` cell.

`us-east-1` and `ap-southeast-1` must exist in configuration and Terraform/Helm modules must plan successfully, but production resources for those regions are not created.

## 39A.4 Launch Provisioned Envelope

The initial MYCO Cloud Provisioned Envelope is a configured autoscaling ceiling, not an expected customer count:

| Dimension | S0 provisioned target |
|---|---:|
| user accounts | 10,000 |
| organisations / tenants | 2,000 |
| stored projects | 25,000 |
| simultaneously active users | 1,000 |
| simultaneously active projects | 500 |
| concurrent active builds | 100 |
| runnable/running engineering tasks | 1,000 |
| concurrent microVM task forks | 250 |
| simultaneous model/tool operations in scheduler state | 1,000 |
| open/dormant durable workflows | 100,000 |
| sustained public/control API traffic | 500 requests/second |
| one-minute API admission spike | 1,500 requests/second |
| sustained internal event production | 5,000 events/second |
| active regions | 1 |
| active Platform Cells | 1 |

Object storage is usage-metered and elastic; it is not preallocated to a fixed byte count. The Provisioned Envelope records the current provider/account quota and cost guardrail instead of inventing a storage ceiling.

The launch envelope may be raised only by changing `config/capacity/scale-envelope.yaml`, generating a new infrastructure plan, and producing new applicable capacity evidence before admission limits are raised.

## 39A.5 Warm baseline versus provisioned ceiling

MYCO must not keep the S0 Provisioned Envelope running idle.

The launch warm baseline is:

- critical regional control services: minimum 3 replicas spread across failure domains where practical;
- P0/P1 worker classes: minimum 1 ready worker replica for each required launch work class;
- P2 interactive worker classes: minimum 1 ready worker replica for each required launch work class;
- P3/P4 worker classes: minimum 0; scale from durable queue demand;
- microVM warm spare target: `max(2, ceil(0.10 × p95_concurrent_forks_over_previous_15_minutes))`, capped by the Provisioned Envelope;
- cold worker/microVM capacity: autoscaled only when queue/capacity rules require it.

`WARM_BASELINE` is an operational cost setting and is never presented as a fourth capacity envelope.

## 39A.6 Platform Cell

A Platform Cell is the unit of horizontal project-state scaling.

A cell contains:

- PostgreSQL HA cluster;
- World Model graph shard(s);
- cell Temporal namespace;
- cell-scoped worker task queues;
- cell Redis namespace/cluster;
- cell event partitions;
- project routing records;
- project services;
- Engineering Cell metadata;
- evidence indexes.

A cell does not own global identity bootstrap or Global Directory authority.

Cell IDs are immutable:

`<region>-c<four-digit-ordinal>`

Launch cell:

`eu-west-2-c0001`

A project belongs to exactly one cell at a time. No normal engineering transaction spans two Platform Cells.

Additional same-region cells are allowed at scale stage `S1_SINGLE_REGION_HORIZONTAL_SCALE` without activating another region.

## 39A.7 Region and cell allocation

New projects are placed by the Cell Allocator.

Eligible cells are filtered by:

1. deployment stage;
2. region state = `ACTIVE`;
3. residency policy;
4. sovereign deployment policy;
5. data classification;
6. cell health;
7. Verified Envelope remaining headroom;
8. Provisioned Envelope remaining headroom;
9. tenant entitlement.

Among eligible cells, choose the lowest value of:

`max(cpu_ratio, memory_ratio, db_connection_ratio, db_cpu_ratio, storage_ratio, worker_slot_ratio, microvm_ratio, event_lag_ratio)`

Ties are broken by lowest active-project count, then lexicographic `cell_id`.

No random placement is permitted.

At S0, the only eligible MYCO Cloud region is `eu-west-2`. A `CONFIGURED_DORMANT` region is never eligible for project placement.

## 39A.8 Admission control and priority

Priority classes are fixed:

- `P0_SECURITY_INCIDENT`
- `P1_PRODUCTION_INCIDENT`
- `P2_INTERACTIVE_ENGINEERING`
- `P3_BACKGROUND_ENGINEERING`
- `P4_MAINTENANCE_LEARNING`

At least 20% of provisioned worker/microVM execution capacity is reserved for P0/P1 combined.

Weighted fair queuing is enforced per tenant inside each priority.

A work request becomes **accepted** only after:

1. authentication;
2. policy;
3. quota check;
4. capacity check against the applicable Verified + Provisioned + Provider envelopes;
5. durable Task/Build record commit;
6. durable Temporal workflow start acknowledgement.

Before step 6, overload may return `429 Too Many Requests` with `Retry-After`.

After step 6, the platform may queue work but may not discard it.

At ≥80% of any hard provisioned capacity dimension:

- P4 may be delayed;
- new P4 may be rejected before acceptance.

At ≥90%:

- new P3 may be delayed/rejected before acceptance;
- P0/P1 reserve remains protected.

At ≥95%:

- only P0/P1 and already-accepted work are guaranteed admission;
- P2 not yet accepted receives explicit saturation response.

Existing accepted P2/P3/P4 work is never deleted to make room.

## 39A.9 Kubernetes service autoscaling

Stateless API/control services use Horizontal Pod Autoscaling.

Defaults:

- CPU target: 60%;
- memory target: 70%;
- scale-up evaluation: every 30 seconds;
- maximum scale-up: 2× current replicas per evaluation;
- scale-down requires 15 consecutive minutes below 50% of both target CPU and memory;
- minimum replicas for critical S0 regional control services: 3 across failure domains where practical.

Custom backlog/latency metrics override CPU/memory when they require more replicas.

No service may use local process memory as authoritative durable state.

## 39A.10 Worker autoscaling

For each work class:

`required_slots = ceil((arrival_rate_5m_tasks_per_second × p95_task_duration_seconds) / 0.70)`

`required_replicas = ceil(required_slots / benchmarked_slots_per_worker)`

`benchmarked_slots_per_worker` comes from the latest applicable Verified Envelope for that worker image and machine class. It is never guessed.

Scale-up begins when either:

- calculated required replicas exceed current replicas; or
- oldest eligible queue item >5 seconds while Provisioned capacity remains.

Scale-down begins only after 15 minutes below 50% measured slot utilisation.

Worker images are immutable and digest-pinned.

## 39A.11 microVM capacity manager

Every active region has:

- scheduler;
- warm-host pool;
- cold autoscale pool;
- per-tenant quota;
- per-task resource class;
- cleanup/reaper;
- host health monitor.

S0 warm spare target is defined in §39A.5.

Resource classes are fixed:

- `S1`: 2 vCPU / 4 GiB RAM;
- `S2`: 4 vCPU / 8 GiB RAM;
- `S3`: 8 vCPU / 16 GiB RAM;
- `S4`: 16 vCPU / 32 GiB RAM;
- `G1`: project-defined GPU class.

Default task class is `S2`; the planner must justify a higher class through task metadata.

Targets:

- warm microVM ready p95 ≤10 seconds;
- cold-capacity microVM ready p95 ≤60 seconds;
- failed host detected and removed from scheduling ≤30 seconds.

A destroyed fork leaves no reusable writable project state.

## 39A.12 Provider Capacity Manager

Every model/provider route tracks separately by provider, model and active region:

- RPM hard limit;
- TPM hard limit;
- concurrent-request hard limit;
- reserved capacity;
- burst capacity;
- current in-flight calls;
- rolling p50/p95 latency;
- rolling error rate;
- health;
- permitted data classifications;
- permitted tenant regions;
- cost.

A routing candidate is ineligible if it would violate:

- data policy;
- tenant provider policy;
- hard quota;
- concurrency limit;
- regional availability;
- circuit breaker.

Circuit breaker opens when either, over a rolling 60-second window:

- provider call failure rate ≥20% with at least 20 calls; or
- p95 latency exceeds 3× the provider/model trailing-24-hour p95 for 5 consecutive minutes.

Circuit breaker enters half-open after 60 seconds and permits 5 probe calls.

If no eligible model has capacity, work queues. MYCO does not convert provider saturation into false task success.

## 39A.13 Launch regional failure and residency behavior

At S0/S1 there is no automatic regional failover.

If the active region is unavailable:

- new admission stops;
- accepted state remains durable to the extent guaranteed by the active-region persistence layer;
- users receive explicit region-unavailable state;
- dormant regions remain dormant;
- no project is silently reassigned;
- no residency rule is bypassed.

A tenant may restrict placement to `eu-west-2` at launch. A requirement for a different MYCO Cloud residency region is a scale-activation trigger, not permission to create an ad hoc deployment.

Multi-region failover behavior becomes applicable only at `S3_MULTI_REGION_DR`.

## 39A.14 MYCO-owned platform SLOs

These are internal engineering SLOs, not automatically a customer contractual SLA.

Measured monthly for MYCO-owned services, excluding time spent inside external model/tool providers unless MYCO accepted the call and then failed to handle provider failure correctly:

- active-region control-plane availability target: ≥99.95%;
- public/control API availability target: ≥99.95%;
- API p95 latency: ≤300 ms;
- API p99 latency: ≤750 ms;
- project/cell routing lookup p95: ≤100 ms;
- accepted-work durable loss: 0;
- cross-tenant data leakage: 0;
- accepted evidence digest mismatch: 0;
- task admission p95: ≤2 seconds when entitlement/capacity are available;
- eligible queued-task dispatch p95: ≤5 seconds when execution capacity is available;
- warm microVM availability p95: ≤10 seconds;
- worker crash detection/reassignment initiation: ≤60 seconds;
- provider circuit-breaker reaction: ≤30 seconds after threshold becomes true;
- control-plane error rate under current Verified Envelope: <0.1%, excluding valid 4xx client/policy responses.

The 99.95% target does not create a multi-region recovery claim. At S0/S1 a total `eu-west-2` outage is explicitly outside the launch multi-region capability because no second active region exists.

External provider latency is recorded separately and never hidden inside MYCO-owned latency.

## 39A.15 Capacity and activation source files

Required source-controlled files:

`config/capacity/scale-envelope.yaml`  
`config/capacity/scale-activation.yaml`  
`config/capacity/admission-policy.yaml`  
`config/capacity/resource-classes.yaml`  
`config/capacity/provider-capacity.schema.json`  
`config/regions/regions.yaml`

Generated artifacts:

- `artifacts/capacity/verified-envelope.json`
- `artifacts/capacity/verified-envelope.sig`
- `artifacts/capacity/cost-report.json`
- `artifacts/capacity/scale-stage-report.json`
- `artifacts/capacity/scale-stage-report.json`

`verified-envelope.json` is produced only by MYCO-Bench and may not be hand-edited.

MYCO Cloud signs its SHA-256 digest with Cosign using a Vault-backed key. Sovereign deployments use a customer-approved key. `task capacity:verify` validates digest, signature, benchmark commit and infrastructure digest.

## 39A.16 Canonical `scale-envelope.yaml`

```yaml
version: 2
design:
  user_accounts: 10000000
  organisations: 1000000
  stored_projects: 10000000
  active_projects: 100000
  concurrent_builds: 10000
  engineering_tasks_in_system: 100000
  concurrent_microvm_forks: 25000
  concurrent_model_tool_operations: 100000
  open_workflows: 5000000
  api_sustained_rps: 20000
  api_spike_rps: 60000
  event_sustained_eps: 200000
  object_namespace_bytes: 5000000000000000
  active_regions_supported_without_product_rewrite: 3
launch_provisioned:
  deployment_stage: S0_LAUNCH_SINGLE_REGION
  user_accounts: 10000
  organisations: 2000
  stored_projects: 25000
  simultaneously_active_users: 1000
  active_projects: 500
  concurrent_builds: 100
  engineering_tasks_in_system: 1000
  concurrent_microvm_forks: 250
  concurrent_model_tool_operations: 1000
  open_workflows: 100000
  api_sustained_rps: 500
  api_spike_rps: 1500
  event_sustained_eps: 5000
  active_regions: 1
  active_platform_cells: 1
slo:
  availability_percent_target: 99.95
  api_p95_ms: 300
  api_p99_ms: 750
  route_lookup_p95_ms: 100
  task_admission_p95_ms: 2000
  dispatch_p95_ms_when_capacity_available: 5000
  accepted_work_loss: 0
  cross_tenant_leakage: 0
  evidence_digest_mismatch: 0
launch_recovery:
  in_region_rpo_seconds: 300
  in_region_rto_seconds: 3600
  total_region_failover_enabled: false
```

## 39A.17 Canonical `regions.yaml`

```yaml
version: 2
cloud_reference_provider: aws
deployment_stage: S0_LAUNCH_SINGLE_REGION
global_control:
  writer_region: eu-west-2
  standby_region: null
identity:
  primary_region: eu-west-2
  dr_region: null
global_accelerator:
  enabled: false
  state: DEFERRED_BY_SCALE_GATE
regions:
  - id: eu-west-2
    state: ACTIVE
    availability_zones: 3
    allow_new_projects: true
  - id: us-east-1
    state: CONFIGURED_DORMANT
    availability_zones: 3
    allow_new_projects: false
  - id: ap-southeast-1
    state: CONFIGURED_DORMANT
    availability_zones: 3
    allow_new_projects: false
```

Allowed region states:

- `ACTIVE`
- `CONFIGURED_DORMANT`
- `ACTIVATING`
- `DRAINING`
- `DISABLED`

A dormant region may have validated configuration and infrastructure modules, but `terraform apply` for production regional resources is forbidden unless a scale-activation record authorises the transition.

Application-code conditionals such as `if region == "eu-west-2"` are forbidden unless genuinely provider/region-specific and covered by an ADR.

## 39A.18 Canonical `scale-activation.yaml`

```yaml
version: 1
current_stage: S0_LAUNCH_SINGLE_REGION
stages:
  S0_LAUNCH_SINGLE_REGION:
    active_region_count: 1
    global_accelerator: false
    cross_region_replication: false
    cross_region_failover: false
  S1_SINGLE_REGION_HORIZONTAL_SCALE:
    active_region_count: 1
    global_accelerator: false
    cross_region_replication: false
    cross_region_failover: false
  S2_SECOND_REGION_ACTIVE:
    active_region_count: 2
    global_accelerator: true
    cross_region_replication: false
    cross_region_failover: false
  S3_MULTI_REGION_DR:
    active_region_count_min: 2
    global_accelerator: true
    cross_region_replication: true
    cross_region_failover: true
  S4_THIRD_REGION_ACTIVE:
    active_region_count: 3
    global_accelerator: true
    cross_region_replication: true
    cross_region_failover: true
  S5_DESIGN_ENVELOPE_VALIDATION:
    purpose: validate selected or complete Design Envelope dimensions
approval:
  required_authority_for_S1: A4
  required_authority_for_S2_or_higher: A6
activation_reasons:
  - CAPACITY_PRESSURE
  - RESIDENCY_CONTRACT
  - BUSINESS_CONTINUITY_REQUIREMENT
  - ACQUIRER_OR_ENTERPRISE_REQUIREMENT
  - VERIFIED_SCALE_PROGRAMME
```

## 39A.19 Scale-stage activation gates

### `S0 → S1_SINGLE_REGION_HORIZONTAL_SCALE`

S1 becomes required when either:

- any active cell enters `CLOSED_TO_NEW` because a §36.1 threshold remains breached for 30 minutes; or
- trailing 7-day p95 consumption is ≥70% of the current S0 Provisioned Envelope for any two of: active projects, concurrent builds, engineering tasks, microVM forks, API RPS, event EPS.

S1 actions:

1. create A4-approved ScaleActivation record;
2. provision another `eu-west-2` Platform Cell or expand worker/service pools as indicated by the bottleneck;
3. keep all other regions dormant;
4. rerun applicable MB20 capacity tests;
5. sign a new Verified Envelope;
6. raise admission limits only after verification.

### `S1 → S2_SECOND_REGION_ACTIVE`

S2 is activated only for one of these recorded reasons:

- `RESIDENCY_CONTRACT`: signed requirement for a supported region outside `eu-west-2`;
- `CAPACITY_PRESSURE`: single-region verified/provisioned capacity is insufficient after horizontal cell expansion;
- `BUSINESS_CONTINUITY_REQUIREMENT`: management/enterprise requirement that justifies a second active region;
- `ACQUIRER_OR_ENTERPRISE_REQUIREMENT`: explicit integration/deployment requirement.

S2 actions are fixed:

1. A6 approval;
2. choose the eligible dormant region from residency/business requirement;
3. change state `CONFIGURED_DORMANT → ACTIVATING`;
4. provision regional Kubernetes, data services and at least one Platform Cell from the same modules;
5. run regional acceptance suite;
6. enable AWS Global Accelerator;
7. validate active-region routing and residency;
8. mark region `ACTIVE` only after acceptance;
9. do **not** enable cross-region project/database failover merely because the region is active;
10. generate new scale-stage report and applicable Verified Envelope.

### `S2 → S3_MULTI_REGION_DR`

S3 requires an explicit `BUSINESS_CONTINUITY_REQUIREMENT`, `ACQUIRER_OR_ENTERPRISE_REQUIREMENT`, or contractual availability/resilience obligation.

S3 actions:

1. A6 approval;
2. define permitted DR pairs by residency policy;
3. provision Global Control and identity cross-region standby;
4. provision eligible cell PostgreSQL replica clusters;
5. enable permitted object/evidence replication;
6. configure asynchronous event recovery plumbing;
7. implement old-writer fencing and promotion workflow;
8. run region-loss/failover tests;
9. measure RPO/RTO;
10. only then permit a `MULTI_REGION_RECOVERABLE` claim.

### `S3 → S4_THIRD_REGION_ACTIVE`

Activate the remaining configured dormant region using the same S2 regional acceptance process, then include it in S3 DR policy only where residency permits.

### `S4 → S5_DESIGN_ENVELOPE_VALIDATION`

S5 is a deliberate scale-validation programme, not a launch requirement. It may verify selected dimensions progressively. A Design target remains `UNVERIFIED` until the corresponding benchmark proves it.

## 39A.20 Deferred-scale acceptance contract

The following are authoritative but **not pre-launch completion requirements**:

- second/third always-on MYCO Cloud region;
- AWS Global Accelerator resource;
- cross-region Global Control standby;
- cross-region Keycloak standby;
- cross-region Platform Cell database standby;
- cross-region object/evidence replication;
- region-loss automatic/manual failover workflow;
- cross-region project migration;
- multi-region load distribution;
- 3-region MYCO-Bench execution;
- full Design Envelope validation.

At S0 these items must satisfy all of the following instead:

- architecture/config contract exists;
- production module is source-controlled;
- `terraform validate` / static plan checks pass without applying resources;
- feature state is `DEFERRED_BY_SCALE_GATE`;
- UI/API does not advertise it as active;
- acceptance documentation names its activation stage;
- no production resource is accidentally created in a dormant region.

A deferred item becomes mandatory in the same release that changes the relevant scale stage.

## 39A.21 Canonical admission policy

`config/capacity/admission-policy.yaml`:

```yaml
version: 1
reserved_capacity:
  p0_p1_percent: 20
priorities:
  P0_SECURITY_INCIDENT: { rank: 0 }
  P1_PRODUCTION_INCIDENT: { rank: 1 }
  P2_INTERACTIVE_ENGINEERING: { rank: 2 }
  P3_BACKGROUND_ENGINEERING: { rank: 3 }
  P4_MAINTENANCE_LEARNING: { rank: 4 }
thresholds:
  delay_p4_percent: 80
  delay_p3_percent: 90
  incident_only_new_admission_percent: 95
accepted_boundary:
  require_task_commit: true
  require_temporal_start_ack: true
overload_response:
  http_status: 429
  include_retry_after: true
fairness:
  algorithm: weighted_fair_queue
  key: tenant_id
```

## 39A.22 Canonical resource classes

`config/capacity/resource-classes.yaml`:

```yaml
version: 1
classes:
  S1: { vcpu: 2, memory_gib: 4 }
  S2: { vcpu: 4, memory_gib: 8 }
  S3: { vcpu: 8, memory_gib: 16 }
  S4: { vcpu: 16, memory_gib: 32 }
  G1:
    gpu_required: true
    vcpu: 8
    memory_gib: 32
default_class: S2
```

GPU make/model is deployment capacity, not an application invariant. Any G1 implementation records exact GPU type/driver/runtime in the Verified Envelope.

## 39A.23 Provider-capacity contract

Every provider/model/active-region capacity record conforms to `config/capacity/provider-capacity.schema.json` and includes:

- `provider_id`;
- `model_id`;
- `region`;
- `rpm_limit`;
- `tpm_limit`;
- `concurrent_limit`;
- `reserved_rpm`;
- `reserved_tpm`;
- `burst_rpm`;
- `current_inflight`;
- `health_state`;
- `circuit_state`;
- `p50_latency_ms`;
- `p95_latency_ms`;
- `error_rate`;
- `allowed_data_classes`;
- `updated_at`;
- `source` (`contract | provider_api | self_hosted_measurement | operator_override`);
- `expires_at`.

Expired provider-capacity data makes the route ineligible unless the provider contract defines a safe static quota that remains current.

## 39A.24 Scale evidence rule

A scale benchmark is invalid if:

- synthetic work is reported as real model/software-completion proof;
- a dormant region is counted as active capacity;
- deferred multi-region behavior is reported as verified;
- required failures are disabled;
- tenant isolation is bypassed;
- assertions are weakened;
- saturation/error data is omitted;
- warm-up time is silently excluded where material;
- failed requests are removed from denominator;
- infrastructure/model cost is omitted;
- tested commit or infrastructure digest is missing.

Control-plane synthetic load and real end-to-end autonomous-engineering load are reported as separate scoped Verified Envelopes.

The launch deck/diligence wording permitted by this design is:

> **MYCO is architected around a 10-million-user Design Envelope with horizontally extensible cells and evidence-backed capacity claims. Its launch deployment is intentionally single-region and demand-scaled.**

The wording `MYCO supports 10 million users` is forbidden until an applicable Verified Envelope supports that claim.

# 40. RESEARCH-VERIFIED DEPENDENCY BASELINE — 19 SEPTEMBER 2026

The previous draft contained several now-outdated baselines. This table is the new Phase-0 freeze target.

## 40.1 Runtime/platform

| Component | Locked baseline | Decision |
|---|---:|---|
| Node.js | 24.21.0 LTS | Use LTS, not Node 26 Current |
| Python | 3.14.7 | Replaces older 3.13.15 baseline |
| PostgreSQL | 18.6 | Do not use PostgreSQL 19 beta |
| Redis Open Source | 8.10 | Current stable line |
| Neo4j | 2026.08.1 | Current production release |
| PydanticAI | 2.45.0 | Replaces 2.44.0 |
| Temporal Python SDK | 1.33.0 | Replaces 1.32.0 |
| OPA | 1.20.2 | Current stable |
| SPIRE | 1.15.3 | Current stable |
| Vault | 2.1.1 | Current stable |
| E2B Runtime | 2026.30 | Replaces 2026.29 |
| OpenTelemetry Collector | 0.161.0 | Current release line |
| Keycloak | 26.7.4 | Includes September security fixes |
| Kubernetes | 1.37.0 | Current stable |
| CloudNativePG | 1.30.1 | Scale-hardening addition verified 25 September 2026; PostgreSQL HA operator |
| AWS Global Accelerator | managed service — deferred at S0 | Required when `S2_SECOND_REGION_ACTIVE` begins; not provisioned for single-region launch |
| Terraform | 1.16.3 | Do not use 1.17 beta |
| Helm | 4.3.0 | Current stable |

## 40.2 Development/build

| Component | Locked baseline |
|---|---:|
| pnpm | 12.5.1 |
| Turborepo | 2.10.6 stable |
| uv | 0.12.17 |
| Task | 3.52.0 |
| TypeScript | 7.0.2 |
| React | 19.3 |
| Vite | 8.1 stable line; exact patch pinned by lockfile at Phase 0 |
| React Router | 8.4.0 |
| TanStack React Query | 5.103.1 |
| Zustand | 5.0.15 |
| Tailwind CSS | 4.3.3 |
| xterm.js | 6.0.0 |
| Tauri | 2.11.3 stable; never Tauri 3 alpha in production |
| Expo | SDK 57 stable; never SDK 58 beta in production baseline |
| React Native | 0.86.x through Expo 57 |
| Fastify | 5.12.5 stable; never Fastify 6 alpha in production |
| Drizzle ORM | 0.45.2 stable; never 1.0 RC as production baseline |
| Neo4j JS driver | 6.2.0 |
| node-redis | 6.1.0 |
| Biome | 2.5.14 |

## 40.3 AI/self-hosted model stack

| Component | Locked baseline |
|---|---:|
| vLLM | 0.29.0 |
| Transformers | 5.17.0 |
| TRL | 1.13.0 |

## 40.4 Verification/security

| Component | Locked baseline |
|---|---:|
| Semgrep | 1.177.0 |
| OSV-Scanner | 2.6.0 |
| Trivy | 0.74.0 |
| Syft | 1.52.0 |
| Cosign | 3.1.3 |
| OWASP ZAP | 2.17.0 stable; weekly builds excluded from production baseline |
| Vitest | 5.0.1 |
| StrykerJS | 9.6.1 |
| pytest | 9.1.1 |
| Hypothesis | 6.164.0 |
| mutmut | 3.7.0 |
| k6 | 2.2.0 |
| axe-core | 4.13.0 |
| Maestro | 2.7.0 |
| Z3 | 5.0.0 |
| Dafny | 4.11.0 |
| Lean | 4.34.0 stable; 4.35 RC excluded |
| TLA+ tools | 1.7.2 stable; 1.8 pre-release excluded |

## 40.5 Stable-only admission rule

For every top-level dependency not explicitly listed above, Phase 0 applies this deterministic rule:

1. Official project/package source only.
2. Latest **stable** release compatible with locked runtimes.
3. No alpha/beta/RC/nightly in production unless an ADR explicitly authorises it.
4. No unresolved known critical vulnerability applicable to MYCO usage.
5. Licence must be recorded and commercially compatible.
6. Exact version, checksum/source digest and source URL recorded in `config/dependencies/baseline.yaml`.
7. Exact package version pinned in `pnpm-lock.yaml`, `uv.lock`, Cargo lockfiles, Terraform provider lockfiles and container digests.
8. Dependabot/Renovate may propose updates; they never auto-promote to production without tests.

This rule removes dependency-choice guesswork while avoiding stale prose when leaf packages release patch updates.

---

# 41. SOURCE-CONTROLLED DEPENDENCY, REGION AND CAPACITY FILES

Required root/config files:

- `.node-version` = `24.21.0`
- `.python-version` = `3.14.7`
- `package.json` with `packageManager: pnpm@12.5.1`
- `pnpm-workspace.yaml`
- `pnpm-lock.yaml`
- `turbo.json`
- `pyproject.toml`
- `uv.lock`
- `Taskfile.yml`
- `rust-toolchain.toml`
- `.terraform-version` = `1.16.3`
- `config/dependencies/baseline.yaml`
- `config/models/manifest.yaml`
- `config/security/assurance-profiles.yaml`
- `config/policy/authority-levels.yaml`
- `config/readiness/readiness-policy.yaml`
- `config/design/tokens.css`
- `config/regions/regions.yaml`
- `config/capacity/scale-envelope.yaml`
- `config/capacity/scale-activation.yaml`
- `config/capacity/admission-policy.yaml`
- `config/capacity/resource-classes.yaml`
- `config/capacity/provider-capacity.schema.json`
- `config/temporal/task-queues.yaml`

Generated benchmark artifacts are not hand-edited:

- `artifacts/capacity/verified-envelope.json`
- `artifacts/capacity/verified-envelope.sig`
- `artifacts/capacity/cost-report.json`
- `artifacts/capacity/scale-stage-report.json`

No caret/range is permitted for top-level production dependencies. Exact versions only.

Region IDs, region lifecycle states, deployment stage, cell resource classes, scale targets, queue classes and provider-capacity schema values may not live as duplicated magic constants inside application code.

# 42. REPOSITORY STRUCTURE

```text
myco/
├── apps/
│   ├── web/
│   ├── desktop/
│   ├── mobile/
│   ├── api/
│   ├── cli/
│   ├── vscode-extension/
│   └── jetbrains-plugin/
├── services/
│   ├── engineering-brain/
│   ├── global-directory/
│   ├── region-router/
│   ├── cell-manager/
│   ├── admission-control/
│   ├── capacity-manager/
│   ├── provider-capacity/
│   ├── world-model/
│   ├── project-digital-twin/
│   ├── intake/
│   ├── requirements/
│   ├── architecture/
│   ├── readiness/
│   ├── build-supervisor/
│   ├── topology-controller/
│   ├── orchestrator/
│   ├── model-gateway/
│   ├── context-broker/
│   ├── context-optimizer/
│   ├── engineering-cells/
│   ├── workspace-runtime/
│   ├── execution/
│   ├── tool-gateway/
│   ├── wiring-truth/
│   ├── validation/
│   ├── test-intelligence/
│   ├── security/
│   ├── formal-verification/
│   ├── repair/
│   ├── evidence/
│   ├── memory/
│   ├── reasoning-bank/
│   ├── skills/
│   ├── engineering-packs/
│   ├── learning/
│   ├── delivery/
│   ├── deployment/
│   ├── operations/
│   ├── standing-goals/
│   ├── outcome-ledger/
│   ├── identity/
│   ├── policy/
│   ├── billing/
│   └── observability/
├── agents/
│   ├── orchestrator/
│   ├── planner/
│   ├── architecture/
│   ├── backend/
│   ├── frontend/
│   ├── infrastructure/
│   ├── integration/
│   ├── security/
│   ├── validation/
│   ├── deployment/
│   ├── monitoring/
│   ├── optimisation/
│   └── documentation/
├── packages/
│   ├── contracts/
│   ├── domain/
│   ├── auth/
│   ├── policy/
│   ├── tools/
│   ├── hooks/
│   ├── connectors/
│   ├── telemetry/
│   ├── evidence/
│   ├── design-system/
│   └── evals/
├── schemas/
│   ├── json-schema/
│   ├── openapi/
│   └── events/
├── models/
│   ├── providers/
│   ├── routing/
│   ├── datasets/
│   ├── training/
│   ├── tool-intelligence/
│   └── evaluations/
├── knowledge/
│   ├── manifests/
│   ├── framework-packs/
│   ├── security/
│   ├── compliance/
│   └── ingestion/
├── engineering-packs/
├── templates/
├── benchmarks/
│   ├── swe-bench/
│   ├── swe-smith/
│   ├── vibench/
│   └── myco-bench/
├── config/
│   ├── dependencies/
│   ├── models/
│   ├── policy/
│   ├── readiness/
│   ├── security/
│   ├── design/
│   ├── regions/
│   ├── capacity/
│   └── temporal/
├── infra/
│   ├── docker/
│   ├── terraform/
│   ├── kubernetes/
│   ├── helm/
│   ├── temporal/
│   ├── cloudnative-pg/
│   ├── global-ingress/
│   ├── cells/
│   ├── chaos/
│   ├── opa/
│   ├── spire/
│   ├── vault/
│   ├── observability/
│   └── runtime/
├── scripts/
│   ├── bootstrap/
│   ├── verify/
│   └── release/
├── tests/
│   ├── unit/
│   ├── integration/
│   ├── agent/
│   ├── security/
│   ├── adversarial/
│   ├── mutation/
│   ├── metamorphic/
│   ├── benchmark/
│   ├── load/
│   ├── soak/
│   ├── spike/
│   ├── chaos/
│   ├── e2e/
│   └── acceptance/
├── artifacts/
│   └── capacity/
├── docs/
│   ├── design/
│   ├── adr/
│   ├── operations/
│   └── phases/
└── MYCO_V3_SPEC.md
```

No directory counts as implemented until code + tests + phase evidence exist.

---

# 43. CANONICAL ROOT COMMANDS

`Taskfile.yml` must expose these stable commands from Phase 0 onward:

- `task bootstrap`
- `task infra:up`
- `task infra:down`
- `task format`
- `task lint`
- `task typecheck`
- `task test:unit`
- `task test:integration`
- `task test:e2e`
- `task test:security`
- `task test:mutation`
- `task test:load`
- `task test:spike`
- `task test:soak`
- `task test:chaos`
- `task capacity:verify`
- `task capacity:report`
- `task scale:status`
- `task scale:plan -- <target-stage>`
- `task launch:verify`
- `task build`
- `task verify`
- `task sbom`
- `task phase -- <phase-number>`

`task verify` is the root acceptance command and must fail on any mandatory gate.

Before Phase 50, `task capacity:verify` returns an explicit `UNVERIFIED` state when no signed envelope exists; that is valid for development but not a production-release pass. From Phase 50 onward, production-release verification requires a valid signed envelope for the current benchmark commit. `task launch:verify` also fails if launch stage is not `S0_LAUNCH_SINGLE_REGION`, if any dormant region contains active production resources, or if Global Accelerator/cross-region replication is enabled without a valid ScaleActivation record.

---

# 44. PHASE EXECUTION CONTRACT TEMPLATE

Every phase file under `docs/phases/PHASE-XX.md` must contain:

1. Phase ID/name
2. Objective
3. Preconditions
4. V3.2 sections implemented
5. Scope
6. Explicit out-of-scope
7. Files/directories created
8. Files/directories modified
9. Database migrations
10. APIs
11. Events
12. Agents/workers
13. Tools/permissions
14. Security rules
15. Failure states
16. Unit tests
17. Integration tests
18. Negative tests
19. E2E tests
20. Commands to execute
21. Evidence produced
22. Manual acceptance steps
23. Audit checklist
24. Binary exit gate
25. Rollback tag
26. Required completion report format
27. Capacity/scale impact
28. SLO impact
29. Region/cell impact
30. Admission/backpressure impact
31. Capacity evidence required
32. Deployment-stage impact
33. Deferred-scale impact
34. ScaleActivation record required (`yes/no` + reason)

Claude Code is not allowed to implement the phase until this contract exists.

---

# 45. CLAUDE CODE BUILD DIRECTIVE

Every phase prompt begins with this immutable instruction:

> The MYCO V3.2 specification and the current Phase Execution Contract are authoritative. You may not change architecture, substitute required production behaviour with mocks/stubs, defer mandatory phase scope, weaken acceptance tests, remove required validation, expand permissions, or declare completion without executing all required evidence-producing commands. Inspect the complete current repository state relevant to this phase before editing. If a required dependency, API or design rule is contradictory or unavailable, stop and report the exact blocker instead of inventing an alternative architecture. You may not bypass the regional-cell model, weaken capacity/SLO gates, hard-code region IDs, replace durable backpressure with dropped work, or claim scale beyond the latest Verified Capacity Envelope. At launch you may not provision dormant regions, Global Accelerator or cross-region DR merely because modules exist. Deferred-scale capabilities become build scope only when the authoritative ScaleActivation stage requires them.

---

# 46. PHASE-BY-PHASE ZERO-GUESS BUILD PLAN

## PHASE 0 — AUTHORITATIVE TRUTH BASELINE

**Objective:** create a reproducible empty MYCO V3.2 monorepo with construction, launch-stage, capacity, deferred-scale and evidence rules locked before product code.

**Create:**

- repository structure from §42;
- `MYCO_V3_SPEC.md` containing this exact V3.2 specification;
- `Taskfile.yml`;
- `package.json`;
- `pnpm-workspace.yaml`;
- `turbo.json`;
- `pyproject.toml`;
- `.node-version`;
- `.python-version`;
- `.terraform-version`;
- `rust-toolchain.toml`;
- dependency/model/security/readiness manifests;
- `config/regions/regions.yaml` exactly from §39A.17;
- `config/capacity/scale-envelope.yaml` exactly from §39A.16;
- `config/capacity/scale-activation.yaml` exactly from §39A.18;
- `config/capacity/admission-policy.yaml`;
- `config/capacity/resource-classes.yaml`;
- `config/capacity/provider-capacity.schema.json`;
- `config/temporal/task-queues.yaml`;
- CloudNativePG 1.30.1 infrastructure manifest baseline;
- dormant-region Terraform/Helm modules with apply disabled by stage guard;
- Global Accelerator Terraform module with `enabled=false` at S0;
- ADR template;
- phase-contract template including capacity/SLO/deferred-scale fields;
- GitHub Actions skeleton;
- CODEOWNERS;
- branch protection documentation;
- Renovate/Dependabot proposal-only configuration.

**Commands:**

`corepack enable`  
`pnpm install --frozen-lockfile`  
`uv sync --frozen`  
`task scale:status`  
`task verify`

**Negative tests:**

- no floating top-level versions;
- no prerelease package without ADR;
- no source file containing placeholder success implementation;
- no application source hard-codes active/dormant behavior from raw region strings;
- no missing scale/capacity/activation manifest;
- `regions.yaml` must contain exactly one `ACTIVE` launch region (`eu-west-2`);
- `us-east-1` and `ap-southeast-1` must be `CONFIGURED_DORMANT`;
- Global Accelerator must be disabled;
- cross-region replication flags must be false;
- generated `verified-envelope.json` must be absent before a benchmark produces it;
- production Terraform plan must create zero resources in dormant regions at S0.

**Evidence:** dependency inventory, licence inventory, initial SBOM, configuration-schema validation, dormant-resource plan proof, successful clean bootstrap.

**Exit:** fresh clone runs `task bootstrap && task verify`; `task scale:status` reports `S0_LAUNCH_SINGLE_REGION`; launch configuration has one active region and no multi-region resources.

**Tag:** `v3.2-phase-00-truth-baseline`.

## PHASE 1 — CONTRACTS AND CORE DOMAIN SCHEMAS

**Objective:** establish machine-readable cross-language authority before services.

**Create:**

- `packages/contracts/`;
- JSON Schemas for Project, Requirement, Architecture, Task, Agent, Model, Tool, Evidence, Approval, Usage, Deployment;
- JSON Schemas for Region, PlatformCell, ProjectPlacement, CellMigration, CapacityEnvelope, AdmissionDecision, ProviderCapacity, ResourceClass;
- OpenAPI root contract;
- CloudEvents schemas;
- generated TypeScript/Python models.

**Required enum/state contracts:**

- priority: `P0_SECURITY_INCIDENT | P1_PRODUCTION_INCIDENT | P2_INTERACTIVE_ENGINEERING | P3_BACKGROUND_ENGINEERING | P4_MAINTENANCE_LEARNING`;
- capacity evidence: `DESIGN | VERIFIED | PROVISIONED | UNVERIFIED`;
- region state: `ACTIVE | CONFIGURED_DORMANT | ACTIVATING | DRAINING | DISABLED`;
- deployment stage: `S0_LAUNCH_SINGLE_REGION | S1_SINGLE_REGION_HORIZONTAL_SCALE | S2_SECOND_REGION_ACTIVE | S3_MULTI_REGION_DR | S4_THIRD_REGION_ACTIVE | S5_DESIGN_ENVELOPE_VALIDATION`;
- deferred capability state: `DEFERRED_BY_SCALE_GATE | ACTIVATING | ACTIVE | DISABLED`;
- cell state: `ACTIVE | CLOSED_TO_NEW | DRAINING | MIGRATING | DEGRADED | OFFLINE`;
- migration states from §36.1.2.

**Rule:** generated models are never hand-edited.

**Tests:** schema round-trip, TS/Python compatibility, UUIDv7/RFC3339 validation, Problem Details schema, invalid region/cell/capacity state rejection, design-envelope cannot deserialize as verified evidence without benchmark fields.

**Exit:** same canonical fixtures validate in TypeScript and Python, including all capacity/region contracts.

**Tag:** `v3.2-phase-01-contracts`.

## PHASE 2 — DURABLE DATA FOUNDATION AND REGIONAL CELL BASE

**Objective:** bring up authoritative persistence before any feature depends on identity, tenancy, routing or project state.

**Build:**

- PostgreSQL 18.6;
- CloudNativePG 1.30.1;
- Keycloak dedicated PostgreSQL database authority;
- Global Control PostgreSQL authority;
- first Platform Cell `local-c0001` for local development;
- PgBouncer pooler;
- Redis 8.10;
- Neo4j 2026.08.1;
- MinIO local object store;
- Temporal;
- Redpanda;
- OpenTelemetry Collector;
- region/cell routing repository;
- cell health/capacity records;
- PITR/WAL archive configuration;
- 64-way initial partitions for high-volume tables defined in §36.1;
- World Model mutation journal table.

**Database ownership:**

- Keycloak alone owns/writes its internal database.
- Drizzle migrations are sole schema-migration authority for MYCO application PostgreSQL databases.
- No service writes across a foreign Platform Cell database connection.

**Local-development mapping:**

- region: `local`;
- cell: `local-c0001`;
- Keycloak DB, Global Control DB and cell DB are separate logical databases even when one local PostgreSQL server process hosts them;
- availability profile: single-machine development only;
- no production availability claims may be derived from local mode.

**Tests:**

- restart persistence;
- PITR rehearsal;
- object checksum;
- graph persistence;
- graph-journal persistence;
- Temporal workflow restart;
- Redpanda replay;
- project placement lookup;
- invalid cross-cell SQL request rejection;
- cell-close threshold state transition;
- Global Directory outage with already-routed workflow continuation.

**Exit:** service restart and host restart do not lose committed state; the three database authorities are separated; project placement resolves deterministically; no normal request requires cross-cell SQL.

**Tag:** `v3.2-phase-02-durable-data-cells`.

---

## PHASE 3 — AUTHENTICATION, TENANCY, RESIDENCY AND AUTHORITY

**Objective:** establish identity, tenancy, residency and authority boundaries on top of the durable Phase-2 foundation.

**Build:**

- Keycloak reference IdP against the Phase-2 Keycloak database;
- OIDC login/session/refresh flow;
- organisations/memberships/roles in Global Control PostgreSQL;
- regional JWT verification using cached issuer/JWKS material;
- PostgreSQL RLS for application-owned relational data;
- SPIFFE/SPIRE service identities;
- OPA decision service;
- Vault integration;
- approval levels A0–A6/AX;
- immutable audit events;
- tenant residency policy object;
- tenant entitlement projection contract.

**MYCO Cloud launch identity topology contract:**

- active identity region: `eu-west-2` only;
- minimum 3 Keycloak replicas across active-region failure domains where practical;
- CloudNativePG HA database in `eu-west-2`;
- no cross-region identity standby at S0/S1;
- ordinary API authorization validates access tokens locally and does not synchronously depend on Keycloak;
- Keycloak outage blocks only operations requiring new identity/session authority after existing token validity expires;
- cross-region identity standby is deferred to `S3_MULTI_REGION_DR`.

**APIs:** `/api/v1/auth/*`, `/api/v1/organisations/*`, `/api/v1/memberships/*`, `/api/v1/approvals/*`, `/api/v1/residency-policies/*`.

**Negative tests:** forged user ID, cross-tenant resource ID, expired token, revoked session, worker with wrong SPIFFE identity, tool request above authority, forged region/cell routing metadata, entitlement projection tampering, residency-policy bypass.

**Exit:** automated breakout suite proves no cross-tenant read/write path; valid access token is verified in a regional API without a synchronous Keycloak call; invalid/revoked credentials fail closed according to token/session contract.

**Tag:** `v3.2-phase-03-identity-tenancy`.

---

## PHASE 4 — PROJECT INTAKE AND REPOSITORY TRUST FIREWALL

**Objective:** safely ingest files/repos while preserving provenance.

**Build:** upload service, repository importer, MIME/type detection, SHA-256 provenance, archive extraction sandbox, lifecycle-script scanner, symlink/path escape protection, secrets scan, agent-instruction classification.

**APIs:** `/api/v1/projects`, `/api/v1/projects/{id}/assets`, `/api/v1/projects/{id}/repositories/import`.

**Negative tests:** zip-slip, symlink escape, malicious package postinstall, secret in repo, repository prompt injection.

**Exit:** malicious fixture repository cannot execute before trust decision.

**Tag:** `v3.2-phase-04-intake-trust`.

---

## PHASE 5 — REQUIREMENTS ENGINE

**Objective:** convert source intent into a versioned Requirements Contract.

**Build:** requirement classifier, source links, contradiction detection, clarification queue, acceptance criteria, versioning, progressive slices, change impact.

**APIs:** `/api/v1/projects/{id}/requirements/*`.

**Tests:** assumption cannot become confirmed without approval; changed requirement creates new version and impact record.

**Exit:** every confirmed requirement has source + validation method + evidence rule.

**Tag:** `v3.2-phase-05-requirements`.

---

## PHASE 6 — ARCHITECTURE ENGINE

**Objective:** generate a machine-readable technical architecture tied to requirements.

**Build:** architecture entities/relations, service boundaries, API/data/event contracts, security boundaries, ADR workflow, architecture rules.

**Exit:** intentionally violating architecture rule is detected mechanically.

**Tag:** `v3.2-phase-06-architecture`.

---

## PHASE 7 — SOFTWARE WORLD MODEL

**Objective:** build canonical project knowledge graph that remains project-scoped and horizontally partitionable.

**Build:**

- Neo4j entity types;
- relation types;
- graph ingestion from source/requirements/architecture;
- provenance links;
- read API;
- mandatory `tenant_id`/`project_id` graph scope;
- World Model mutation journal;
- idempotent journal replay;
- graph-version sequence;
- graph-shard allocator tied to Platform Cell.

**Negative tests:**

- cross-project graph traversal without explicit governed learning path;
- missing `tenant_id` or `project_id`;
- duplicated journal replay;
- graph store loss followed by journal rebuild.

**Exit:** MYCO answers “what exists?”, “what depends on it?”, “which requirement owns it?” using evidence-backed project-scoped graph queries; destroyed fixture graph is rebuilt to identical verified graph version from journal.

**Tag:** `v3.2-phase-07-world-model`.

## PHASE 8 — PROJECT DIGITAL TWIN

**Objective:** compute desired/actual/difference state.

**Build:** desired-state projector, actual-state projector, difference classifier, evidence links, drift events.

**Exit:** seeded missing API or migration appears as explicit difference state.

**Tag:** `v3.2-phase-08-digital-twin`.

---

## PHASE 9 — AUTONOMY READINESS ENGINE

**Objective:** implement R0–R5 scoring and remediation.

**Build:** weighted rubric from §12, hard blockers, remediation task generator, authority cap by readiness.

**Exit:** poor fixture repo scores below R3, repairs are generated, repaired repo rescored upward with evidence.

**Tag:** `v3.2-phase-09-readiness`.

---

## PHASE 10 — PERSISTENT ENGINEERING CELLS

**Objective:** create reusable project environments.

**Build:** cell manifests, dependency/toolchain installation, persistent dev services, health checks, cache management, snapshot source point.

**Reference execution host:** Linux KVM worker nodes. Local Windows development does not attempt Firecracker directly.

**Exit:** cell survives worker/service restart and returns identical toolchain/version manifest.

**Tag:** `v3.2-phase-10-engineering-cells`.

---

## PHASE 11 — microVM TASK FORKS AND REGIONAL CAPACITY SCHEDULER

**Objective:** safe isolated parallel task execution with deterministic quotas, resource classes and autoscaling.

**Build:**

- E2B/Firecracker runtime adapter;
- snapshot/fork;
- resource classes `S1/S2/S3/S4/G1` from §39A.9;
- per-tenant fork quotas;
- regional scheduler;
- warm-host pool;
- cold autoscale pool;
- host health monitor;
- cleanup/reaper;
- quotas;
- network classes N0–N5;
- copy-on-write workspace;
- isolated task DB;
- destroy/cleanup;
- immutable capacity events.

**Reference execution host:** Linux KVM worker nodes. Local Windows development does not attempt Firecracker directly.

**Negative tests:** path escape, host secret access, cross-project mount, privileged container, Docker socket access, quota bypass, scheduling into unhealthy host, destroyed-fork state reuse.

**Scale tests:** warm and cold-start timing, scheduler saturation, tenant fairness, host-loss rescheduling.

**Exit:**

- concurrent forks can edit the same parent project without cross-contamination;
- quota bypass is impossible;
- failed host is removed from scheduling within 30 seconds;
- warm/cold readiness meets §39A.9 in the tested environment;
- scheduler emits measurable capacity evidence rather than assumed capacity.

**Tag:** `v3.2-phase-11-microvm-forks-capacity`.

## PHASE 12 — REAL EXECUTION ENGINE

**Objective:** execute actual engineering commands.

**Build:** command API, xterm stream, stdout/stderr/exit/duration/resource accounting, process kill/timeout, dev server supervisor.

**Rule:** non-zero exit is failure unless command contract explicitly defines accepted codes.

**Exit:** build/test/migration/server commands run in fork and produce immutable evidence.

**Tag:** `v3.2-phase-12-execution`.

---

## PHASE 13 — TOOL REGISTRY AND GATEWAY

**Objective:** governed real tool use.

**Build:** ToolDefinition/Grant/Call/Verification tables, MCP adapter, credential broker, OPA checks, read-back verifiers.

**Exit:** unauthorised tool cannot be discovered/invoked; authorised write is independently verified.

**Tag:** `v3.2-phase-13-tool-gateway`.

---

## PHASE 14 — LIFECYCLE HOOK RUNTIME

**Objective:** signed deterministic extension hooks.

**Build:** OCI/WASI hook packaging, Cosign verification, Wasmtime sandbox, permissions, typed I/O, timeouts.

**Exit:** malicious hook fixture cannot access undeclared filesystem/network.

**Tag:** `v3.2-phase-14-hooks`.

---

## PHASE 15 — FIVE-MODEL GATEWAY AND PROVIDER CAPACITY STATE

**Objective:** one provider-independent gateway for five model families with explicit capacity, health and policy state.

**Build:**

- provider adapters;
- model manifest;
- BYOK;
- managed keys;
- self-hosted Qwen/vLLM;
- data-class routing;
- health/fallback;
- usage records;
- Provider Capacity Manager;
- per-provider/model/region RPM;
- TPM;
- concurrent-request limit;
- reserved/burst capacity;
- circuit-breaker state;
- provider-capacity audit events.

**Exit:** common contract suite passes against all five families; one provider can be disabled without platform failure; a provider at hard quota is not selected; capacity exhaustion queues work instead of fabricating success.

**Tag:** `v3.2-phase-15-five-model-gateway-capacity`.

## PHASE 16 — MODEL PERFORMANCE AND CAPACITY ROUTER

**Objective:** route by verified outcome, total cost, elapsed time, policy and real available provider capacity.

**Build:**

- capability scores;
- task history;
- expected total-cost estimator;
- producer/verifier diversity rule;
- benchmark registry;
- provider-capacity eligibility;
- circuit-breaker handling;
- queue decision;
- reserved-capacity awareness.

**Routing order:**

1. data/tenant policy;
2. provider health;
3. hard quota and concurrency capacity;
4. required producer/verifier diversity;
5. measured verified-completion probability;
6. expected total cost;
7. elapsed-time estimate.

**Exit:** every routing decision includes auditable reason and measured historical evidence; saturated or circuit-open provider is excluded; no fallback weakens assurance profile.

**Tag:** `v3.2-phase-16-model-router-capacity`.

## PHASE 17 — CONTEXT INTELLIGENCE

**Objective:** retrieve only decision-relevant context.

**Build:** hybrid lexical/vector/code retrieval, tenant/project filters, Context Broker, compression service, context provenance.

**Exit:** retrieval benchmark returns required files/requirements without cross-project contamination.

**Tag:** `v3.2-phase-17-context`.

---

## PHASE 18 — SKILLS AND REASONINGBANK

**Objective:** reusable verified engineering expertise.

**Build:** Skill schema, ReasoningLesson schema, evaluation score, versioning, promotion pipeline.

**Exit:** one lesson learned from fixture A improves fixture B without copying proprietary source.

**Tag:** `v3.2-phase-18-skills-reasoningbank`.

---

## PHASE 19 — AGENT HARNESS

**Objective:** bounded runtime contract for every worker.

**Build:** identity, objective, context, model, tools, workspace, network, budget, evidence, heartbeat, termination.

**Exit:** one bounded specialist completes and proves a real engineering task with no out-of-scope writes.

**Tag:** `v3.2-phase-19-agent-harness`.

---

## PHASE 20 — 13 PERMANENT DEPARTMENTS

**Objective:** implement every permanent department as tested real capability.

**Build:** typed agent definitions, department-specific tool grants, outputs, tests and handoffs.

**Rule:** prompt-only agent is incomplete.

**Exit:** each department passes department acceptance suite on a real fixture.

**Tag:** `v3.2-phase-20-departments`.

---

## PHASE 21 — TEMPORARY SPECIALIST WORKFORCE AND FAIR-SHARE SCALING

**Objective:** elastic worker spawning with tenant fairness and evidence-based slot capacity.

**Build:**

- worker lifecycle;
- concurrency;
- heartbeat;
- stale detection;
- reassignment;
- duplicate prevention;
- cleanup;
- resource limits;
- work-class queues;
- per-tenant weighted fairness;
- benchmarked slots-per-worker manifest;
- autoscaling formula from §39A.8;
- P0/P1 reserve enforcement.

**Negative tests:** one tenant floods queue, killed worker, duplicate delivery, stale heartbeat, resource exhaustion, priority spoofing.

**Exit:** killed worker task is recovered exactly once at effect level; flooding tenant cannot starve unrelated tenants; worker replica target is calculated from measured slot capacity rather than a hard-coded guess.

**Tag:** `v3.2-phase-21-temporary-workforce-scale`.

## PHASE 22 — ADAPTIVE TOPOLOGY CONTROLLER

**Objective:** select single/sequential/swarm/competitive execution scientifically.

**Build:** feature extraction, topology policy, cost/parallel gain estimation, outcome logging.

**Exit:** sequential benchmark selects sequential path; parallel benchmark selects parallel path; decision recorded.

**Tag:** `v3.2-phase-22-topology`.

---

## PHASE 23 — BUILD SUPERVISOR, ADMISSION CONTROL AND BACKPRESSURE

**Objective:** orchestrate complete multi-phase engineering work without losing work under overload.

**Build:**

- requirement loading;
- difference-state planning;
- task graph;
- department assignment;
- topology call;
- budget control;
- checkpoints;
- blocker handling;
- Admission & Capacity Controller;
- priority classification;
- tenant quota enforcement;
- weighted fair queue;
- durable acceptance boundary;
- `429 + Retry-After` pre-acceptance saturation path;
- capacity-reserve accounting.

**Hard rule:** a build/task is not reported as accepted until its durable record and Temporal workflow start are both acknowledged.

**Negative tests:**

- overload before acceptance;
- overload after acceptance;
- tenant quota exhaustion;
- P4 flooding while P0 incident arrives;
- capacity service restart;
- duplicate admission request;
- provider-capacity exhaustion.

**Exit:** one multi-service fixture is planned/executed without manual task-by-task prompting; overload never silently drops accepted work; P0/P1 reserve remains available under background saturation.

**Tag:** `v3.2-phase-23-build-supervisor-admission`.

## PHASE 24 — WIRING TRUTH ENGINE

**Objective:** prove end-to-end product wiring.

**Build:** journey registry, OpenTelemetry journey propagation, static flow map, runtime span correlation, required-node policy, WiringTrace evidence.

**Exit:** seeded disconnected button and seeded fake backend success both fail completion.

**Tag:** `v3.2-phase-24-wiring-truth`.

---

## PHASE 25 — BASE TEST ENGINE

**Objective:** normal correctness coverage.

**Build:** Vitest/pytest, API/integration DB harness, Playwright, Maestro, axe-core, k6, visual baseline store.

**Exit:** deliberately broken business logic, permission and migration fixtures are detected.

**Tag:** `v3.2-phase-25-base-testing`.

---

## PHASE 26 — TEST ADVERSARY

**Objective:** test the tests.

**Build:** StrykerJS, mutmut, mutant classification, surviving-mutant task creation, assertion weakening detection.

**Exit:** intentionally weak test suite fails mutation threshold until strengthened.

**Tag:** `v3.2-phase-26-test-adversary`.

---

## PHASE 27 — PROPERTY / DIFFERENTIAL / METAMORPHIC TESTING

**Objective:** find broad edge cases and migration regressions.

**Build:** fast-check, Hypothesis, differential runner, metamorphic relation schema.

**Exit:** seeded invariant violation and seeded migration behaviour drift are detected.

**Tag:** `v3.2-phase-27-advanced-testing`.

---

## PHASE 28 — COMPUTER-USE VERIFICATION

**Objective:** prove running software through real user interaction.

**Build:** browser session service, DOM/accessibility/network capture, screenshots/video, mobile emulator integration.

**Exit:** MYCO can execute required user journey and attach machine-readable + visual evidence.

**Tag:** `v3.2-phase-28-computer-use`.

---

## PHASE 29 — INDEPENDENT VERIFICATION KERNEL

**Objective:** make acceptance independent from production agents.

**Build:** Requirements Verifier, Behaviour Verifier, Wiring Verifier, Mergeability Verifier, cross-model critic, Acceptance Vault.

**Exit:** deliberately false producer completion claim is rejected.

**Tag:** `v3.2-phase-29-verification-kernel`.

---

## PHASE 30 — FORMAL VERIFICATION

**Objective:** machine-check critical invariants.

**Build:** formal trigger classifier, TLA+/TLC runner, Z3 service, Dafny adapter, Lean adapter, proof evidence.

**Exit:** selected distributed/permission fixture has machine-checkable proof/model-check evidence; seeded invariant failure is found.

**Tag:** `v3.2-phase-30-formal-verification`.

---

## PHASE 31 — DEVSECOPS ENGINE

**Objective:** continuous secure development.

**Build:** Semgrep, Gitleaks, OSV-Scanner, Trivy, Syft, Cosign, ZAP integration, threat model schema, ASVS mapping.

**Exit:** scanners run from CI and task runtime; seeded secret/dependency/IaC vulnerability is detected.

**Tag:** `v3.2-phase-31-devsecops`.

---

## PHASE 32 — OFFENSIVE SECURITY SWARM

**Objective:** authorised runtime attack verification.

**Build:** auth attacker, tenant attacker, API attacker, business-logic attacker, exploit verifier; safe target allowlist.

**Exit:** seeded authorised vulnerability is reproduced, repaired and reverified.

**Tag:** `v3.2-phase-32-offensive-security`.

---

## PHASE 33 — AUTOMATIC REPAIR ENGINE

**Objective:** bounded autonomous failure recovery.

**Build:** failure classifier, root-cause candidate generation, repair task, before/after evidence, no-progress/oscillation detector, rollback.

**Exit:** seeded failure repairs without weakening tests; oscillating repair fixture stops safely.

**Tag:** `v3.2-phase-33-repair`.

---

## PHASE 34 — DESIGN SYSTEM AND DESIGN STUDIO

**Objective:** implement the locked MYCO visual direction and visual product-building tools.

**Build:** design tokens from §35, shared component library, creation screen, canvas, responsive frames, screenshot import, variants, visual diff, component extraction.

**Exit:** screenshot-to-working-screen fixture matches visual acceptance threshold and all controls remain wired.

**Tag:** `v3.2-phase-34-design-studio`.

---

## PHASE 35 — CONNECTOR FABRIC

**Objective:** deterministic external engineering-system integrations.

**Initial connectors:** GitHub, GitLab, Jira, Linear, Slack, Teams, Sentry, Datadog/Grafana adapter, AWS, Azure, GCP, OCI registry, deployment providers.

**Exit:** connector read/write actions use scoped credentials and read-back verification.

**Tag:** `v3.2-phase-35-connectors`.

---

## PHASE 36 — ENGINEERING PACK PLATFORM

**Objective:** safe extension ecosystem.

**Build:** pack manifest, OCI registry, signatures, permission review, SBOM, install/update/revoke, Pack Factory test harness.

**Exit:** signed fixture pack installs; modified unsigned fixture is rejected.

**Tag:** `v3.2-phase-36-engineering-packs`.

---

## PHASE 37 — DELIVERY AND PROVENANCE

**Objective:** independently rebuildable final package.

**Build:** artifact manifest, source export, SBOM, SLSA provenance, test/security/wiring evidence index, documentation package, known-risk register.

**Exit:** clean reference machine rebuilds product using delivery docs only.

**Tag:** `v3.2-phase-37-delivery`.

---

## PHASE 38 — LAUNCH DEPLOYMENT ENGINE AND DEFERRED REGION MODULES

**Objective:** deploy MYCO safely into one production region while proving that additional regions can be activated from the same source-controlled modules later without pre-provisioning them now.

**Build active launch path:**

- OCI image pipeline;
- Terraform/Helm adapters;
- provider credentials;
- health/smoke/read-back verification;
- release digest;
- rollback;
- `eu-west-2` regional load balancer;
- regional Kubernetes ingress;
- active-region health endpoints;
- Global Directory routing;
- cell provisioning module;
- production cell `eu-west-2-c0001`;
- residency checks;
- launch-stage guard enforcing S0.

**Build but do not provision:**

- `us-east-1` regional module;
- `ap-southeast-1` regional module;
- AWS Global Accelerator module;
- cross-region standby/replication modules;
- regional activation workflow from §39A.19.

**Required S0 states:**

- `eu-west-2 = ACTIVE`;
- `us-east-1 = CONFIGURED_DORMANT`;
- `ap-southeast-1 = CONFIGURED_DORMANT`;
- Global Accelerator = `DEFERRED_BY_SCALE_GATE`;
- cross-region replication = disabled;
- cross-region failover = disabled.

**Tests:**

- staging deploy in `eu-west-2`;
- bad release detection;
- rollback;
- project routes to `eu-west-2` and the correct cell;
- dormant region cannot receive project placement or traffic;
- dormant-region Terraform modules validate and produce a plan without application-code changes;
- S0 guard rejects production apply for dormant-region resources;
- S0 guard rejects Global Accelerator creation;
- S0 guard rejects cross-region replication creation;
- residency policy requiring an unavailable dormant region returns explicit `REGION_NOT_ACTIVE`/activation-required result, never silent relocation;
- a second same-region cell can be planned from the same module without product-code modification.

**Exit:** production/staging deploy and rollback work in `eu-west-2`; one launch Platform Cell is live; both dormant-region modules validate but have zero production resources; Global Accelerator and cross-region DR resources are absent; `task launch:verify` passes.

**Tag:** `v3.2-phase-38-launch-deployment`.

## PHASE 39 — OPERATIONS MODE, PLATFORM SLOs AND CAPACITY OBSERVABILITY

**Objective:** persistent engineering ownership after delivery plus measurable operation of MYCO itself.

**Build:**

- alerts;
- incidents;
- SLOs;
- dependency maintenance;
- vulnerability response;
- controlled production repair;
- MYCO platform SLO dashboards from §39A.12;
- deployment-stage + region-state dashboard;
- region/cell health dashboards;
- admission saturation dashboards;
- worker-slot utilisation;
- microVM utilisation;
- database headroom;
- graph-shard latency;
- Temporal backlog/history;
- Redpanda partition lag;
- provider quota/circuit-breaker health;
- Verified vs Provisioned Envelope comparison;
- capacity forecast alerts.

**Required alerts:**

- any SLO burn rate projected to breach monthly target;
- cell close-to-new-placement threshold;
- provisioned capacity <120% of trailing 7-day p95 demand;
- provider reserved capacity <120% of trailing 7-day p95 demand;
- RPO lag breach;
- event consumer lag breach;
- evidence integrity failure;
- cross-tenant access anomaly;
- S0/S1 activation-gate threshold reached;
- any production resource detected in a `CONFIGURED_DORMANT` region;
- Global Accelerator or cross-region replication enabled without matching ScaleActivation authority.

**Exit:** seeded production fault becomes isolated repair, verified release and healthy redeployment under policy; seeded saturation produces correct backpressure/scale action and never fake success.

**Tag:** `v3.2-phase-39-operations-slo-capacity`.

## PHASE 40 — STANDING ENGINEERING GOALS

**Objective:** continuous objective enforcement.

**Build:** GoalContract, evaluator schedule, violation events, remediation policy, escalation.

**Exit:** seeded latency/security goal violation creates correct bounded workflow and verified recovery.

**Tag:** `v3.2-phase-40-standing-goals`.

---

## PHASE 41 — ENGINEERING OUTCOME AND PLATFORM ECONOMICS LEDGER

**Objective:** quantify real autonomous engineering value and its marginal cost at scale.

**Build:**

- outcome metrics from §31;
- cost attribution;
- human-intervention tracker;
- feature/requirement cycle time;
- defect escape metrics;
- infrastructure cost allocation by region/cell/project;
- model/provider cost allocation;
- microVM/worker utilisation;
- Verified Envelope association;
- modelled-vs-measured flag;
- marginal cost calculations.

**Exit:** proof build produces auditable cost/time-to-verified-completion report and infrastructure/model cost attribution; no modelled capacity/cost is labelled verified.

**Tag:** `v3.2-phase-41-outcome-ledger-economics`.

## PHASE 42 — ENGINEERING TELESCOPE

**Objective:** full trajectory observability for improvement.

**Build:** trajectory records, model/tool/context links, failure clustering inputs, privacy filters.

**Exit:** repeated seeded failure trajectories cluster into one root pattern without leaking another tenant's source.

**Tag:** `v3.2-phase-42-telescope`.

---

## PHASE 43 — CONTROLLED LEARNING FACTORY

**Objective:** safe measurable self-improvement.

**Build:** candidate creation, offline evaluation, regression, security/adversarial suite, canary, rollback.

**Exit:** one routing/skill candidate is promoted only after benchmark improvement; failing candidate is rejected.

**Tag:** `v3.2-phase-43-learning-factory`.

---

## PHASE 44 — TOOL INTELLIGENCE

**Objective:** owned specialist models for routine tool orchestration.

**Build:** verified tool-chain dataset generator, training manifest, TRL training pipeline, vLLM serving, tool benchmark.

**Exit:** self-hosted specialist meets defined success/cost threshold on bounded tool workflows.

**Tag:** `v3.2-phase-44-tool-intelligence`.

---

## PHASE 45 — EVOLUTIONARY ENGINEERING

**Objective:** objective search over candidate implementations.

**Build:** candidate population, benchmark function, selection, iteration budget, final regression/security verification.

**Exit:** optimisation benchmark beats first-pass solution while preserving behaviour.

**Tag:** `v3.2-phase-45-evolutionary-engineering`.

---

## PHASE 46 — MYCO EVERYWHERE

**Objective:** common project control from every surface.

**Build:** web, Tauri desktop, CLI, VS Code extension, JetBrains plugin, Expo mobile, Slack, Teams, API.

**Exit:** same task can be created on one surface, observed on another, approved on a third, with identical backend task/evidence IDs.

**Tag:** `v3.2-phase-46-everywhere`.

---

## PHASE 47 — SOVEREIGN DEPLOYMENT AND CELL SCALING

**Objective:** deploy whole MYCO in customer-controlled environments without dependence on MYCO Cloud and without changing MYCO semantics.

**Build:**

- Cloud;
- Hybrid;
- BYOC;
- On-Prem;
- Air-Gap packaging;
- local model manifest;
- offline registry/mirror documentation;
- local Global Directory profile;
- local/regional Platform Cell profile;
- capacity manifest;
- sovereign admission policy;
- customer-approved object storage;
- customer-approved regional/failure-domain mapping.

**Rules:**

- sovereign mode uses the same Project/Digital Twin/verification contracts;
- `home_region=local` is valid for single-region sovereign deployments;
- additional cells scale horizontally without a schema fork;
- missing multi-region infrastructure is surfaced as an availability limitation, never hidden.

**Exit:** at least one fully customer-controlled deployment passes platform acceptance without MYCO Cloud data-plane dependency; a second cell can be added without product code changes; capacity is reported through a sovereign Verified Envelope.

**Tag:** `v3.2-phase-47-sovereign-scale`.

## PHASE 48 — BILLING AND ENTITLEMENTS

**Objective:** secure commercial controls.

**Build:** Stripe Billing reference integration, subscriptions, usage aggregation, entitlements, overages, portal, billing audit.

**Rule:** frontend never determines entitlement.

**Exit:** tampered client cannot unlock paid capability; usage reconciles to server records.

**Tag:** `v3.2-phase-48-billing`.

---

## PHASE 49 — COMPLETE PRODUCT UI

**Objective:** wire every production capability to the premium V3 UX.

**Required screens:** Home, Projects, Design Studio, Requirements, Architecture, Readiness, Digital Twin, Build, Workforce, IDE, Terminal, Preview, Wiring Truth, Tests, Security, Evidence, Deployments, Operations, Standing Goals, Outcomes, Billing, Settings.

**Exit:** route/button/permission/error/empty-state sweep finds zero fake or disconnected production controls.

**Tag:** `v3.2-phase-49-product-ui`.

---

## PHASE 50 — MYCO-BENCH, LAUNCH CAPACITY AND SCALE AUTHORITY

**Objective:** create repeatable evidence for engineering quality/autonomy and the actual single-region launch capacity, without spending pre-launch time or money proving dormant multi-region capacity.

**Bench classes:** MB01–MB21 from §47.

**Build:**

- benchmark manifests;
- immutable workload fixtures;
- control-plane load generator;
- real end-to-end autonomous-engineering workload runner;
- cost collector;
- saturation detector;
- fault injector;
- signed scoped Verified Envelope generator;
- scale-stage report generator;
- reproducibility bundle.

**Required separation:**

- synthetic control-plane load may verify control-plane capacity only;
- real model/tool/microVM/software workflows verify end-to-end autonomous-engineering capacity;
- single-region evidence may not be reported as multi-region evidence;
- dormant-region infrastructure plans are design evidence only, not capacity evidence.

**S0 required evidence:**

- MB20 passing evidence for the launch single-region envelope;
- MB21 passing 24-hour single-region multi-tenant evidence;
- `artifacts/capacity/verified-envelope.json`;
- signature;
- cost report;
- `scale-stage-report.json` proving S0 and no active deferred resources.

**Exit:** reproducible report records quality, speed, cost, security, autonomy, human intervention, saturation and failure recovery for S0; capacity claims are scoped to what was actually tested; no second region or Global Accelerator is required.

**Tag:** `v3.2-phase-50-myco-bench-launch-scale`.

## PHASE 51 — REAL INTERNAL PROOF BUILDS

**Objective:** prove MYCO on substantial owned products, not toy demos.

**Rule:** manual coding used to fix a MYCO-declared-complete result invalidates that run.

**Exit:** multiple real end-to-end builds pass independent finished-software test.

**Tag:** `v3.2-phase-51-proof-builds`.

---

## PHASE 52 — LONGITUDINAL AND MULTI-TENANT PRODUCT TEST

**Objective:** prove software remains evolvable while MYCO serves unrelated projects concurrently.

**Build:**

- apply at least 50 sequential approved changes to one MYCO-built product;
- concurrently run unrelated fixture projects under at least 10 separate tenants;
- inject one tenant quota exhaustion;
- inject one worker failure;
- inject one provider degradation.

**Measure:**

- regression;
- architecture drift;
- cost;
- manual intervention;
- test health;
- cross-tenant leakage;
- queue fairness;
- capacity isolation.

**Exit:** product remains inside defined architecture/security/quality limits; no unrelated tenant is corrupted or starved by the noisy tenant; every accepted workflow remains recoverable.

**Tag:** `v3.2-phase-52-longitudinal-multitenant`.

## PHASE 53 — COMPETITOR PROOF

**Objective:** evidence-based differentiation against the current autonomous software-engineering / software-creation competitive set.

**Required comparison set at release freeze:**

- Lovable;
- Replit;
- Factory;
- Cognition/Devin;
- Cursor.

Adjacent benchmarks are documented separately where equivalent workflows can be tested:

- GitHub Copilot/Agent HQ;
- OpenAI Codex.

**Method:** equivalent requirements and acceptance criteria, same starting assets where the competitor supports them, recorded costs and elapsed time, no hidden easier MYCO requirements, and explicit `NOT_SUPPORTED/NOT_COMPARABLE` rather than invented results.

**Measure:** first preview, independently verified finished time, human intervention, missing requirements, wiring, test strength, security, deployment, repair, existing-repository performance, long-running work, provider/model dependence, sovereign deployment where testable.

**Primary metric:** cost/time to independently verified finished software.

**Exit:** comparative evidence package exists; results are reported honestly whether favourable or not; every competitor claim includes source/version/date or reproducible run evidence.

**Tag:** `v3.2-phase-53-competitor-proof`.

## PHASE 54 — CONTROLLED AUTONOMY ROLLOUT

**Objective:** enable action classes only after evidence.

Sequence:

T0–T3  
→ T4  
→ T5  
→ T6  
→ T7  
→ T8 under explicit policy.

**Exit:** each class meets project-defined reliability threshold before next is enabled.

**Tag:** `v3.2-phase-54-controlled-autonomy`.

---

## PHASE 55 — FINAL LAUNCH SYSTEM, SCALE AND ADVERSARIAL HARDENING

**Objective:** prove production MYCO V3.2 at the S0 launch stage under adversarial failure, saturation and long-duration load without pretending multi-region capabilities are active.

**Required fault tests:**

- tenant breakout;
- malicious repository;
- prompt injection;
- secret theft attempt;
- provider outage;
- provider hard-quota exhaustion;
- one of five LLMs removed;
- worker crash;
- Temporal worker restart;
- Temporal backlog saturation;
- PostgreSQL primary failover/recovery inside `eu-west-2`;
- Redis loss;
- Redpanda interruption;
- Redpanda consumer lag;
- Neo4j restart;
- graph rebuild from journal;
- object-store interruption;
- model timeout;
- tool timeout;
- intra-region network partition;
- corrupted task attempt;
- deployment failure;
- rollback;
- backup restore;
- overload/rate limit;
- 3× API admission spike relative to the candidate S0 Verified Envelope;
- one noisy tenant consuming full entitlement;
- cell closed to new placement;
- ephemeral same-region second-cell creation and project migration test;
- malformed event;
- malicious Engineering Pack;
- malicious lifecycle hook;
- active-region ingress instance/pod failure;
- dormant-region traffic rejection;
- dormant-region placement rejection;
- attempted unauthorised activation of Global Accelerator;
- attempted unauthorised cross-region replication;
- simulated `eu-west-2` total-region-unavailable state proving explicit pause/no silent reroute behavior.

**Not required at S0:**

- actual second active production region;
- live Global Accelerator;
- cross-region database replication;
- cross-region project failover;
- real region-loss recovery;
- 3-region load test;
- Design Envelope validation.

Those tests become mandatory only at their §39A scale stage.

**Required scale/failure run:**

Run at ≥70% of the candidate **S0 Verified Envelope** while simultaneously injecting:

1. one worker-pool loss;
2. one model-provider outage;
3. one Redis loss;
4. one event-stream interruption;
5. one PostgreSQL replica loss.

No accepted durable work may disappear. No tenant boundary may weaken. Recovery must remain inside the applicable single-region SLO/RPO/RTO contract.

**Exit:**

- no unresolved critical defect;
- Final Acceptance Mission passes;
- MB20 and MB21 have current passing S0 evidence for this release commit;
- Verified Envelope is signed and references this exact commit/infrastructure manifest;
- `task launch:verify` passes;
- scale-stage report proves exactly one active region and zero unauthorised deferred resources;
- system never claims the Design Envelope or multi-region recovery is Verified.

**Tag:** `v3.2.0-production-accepted`.

# 47. MYCO-BENCH DEFINITIONS

- MB01 Zero-to-One full-stack build
- MB02 Existing Repository Completion
- MB03 Cross-stack Feature
- MB04 Bug Reproduction/Repair
- MB05 Security Remediation
- MB06 Framework/DB Migration
- MB07 Visual Reproduction
- MB08 Deployment
- MB09 Production Incident
- MB10 50-Change Longitudinal Stability
- MB11 Service Restart Recovery
- MB12 Model Provider Loss
- MB13 Tool Loss
- MB14 Adversarial Repository
- MB15 Unwired UI Trap
- MB16 Weak Test Trap
- MB17 Readiness Remediation
- MB18 Standing Goal Violation/Recovery
- MB19 Full Finished-Software Mission
- MB20 Launch Scale, Saturation and Recovery
- MB21 Multi-Tenant Long-Duration Engineering Load

External component benchmarks may include SWE-bench, SWE-smith and ViBench, but none replaces MB19, MB20 or MB21 for MYCO's own completion/launch-capacity claims.

## MB20 — Launch Scale, Saturation and Recovery

**Purpose:** produce scoped Verified Capacity Envelopes for the S0 single-region deployment and prove that overload degrades through queues/backpressure rather than false success or lost work.

**Deployment under test:**

- stage `S0_LAUNCH_SINGLE_REGION`;
- active region `eu-west-2`;
- at least one active Platform Cell;
- `us-east-1` and `ap-southeast-1` dormant;
- Global Accelerator disabled;
- cross-region replication disabled.

**Workload layers:**

1. **Control-plane load** — deterministic benchmark workers; verifies API, PostgreSQL, Temporal, Redpanda, routing, admission, queue and evidence-metadata capacity.
2. **Real engineering load** — real model providers, tools, microVMs, builds, tests, verification and repair; verifies end-to-end autonomous-engineering capacity.

They are reported as separate scoped envelopes.

**Control-plane workload mix:**

- 10% authentication/routing/project reads;
- 10% requirements/architecture reads;
- 20% build/task admission;
- 20% task/workflow state transitions;
- 10% evidence metadata writes;
- 10% model/tool usage accounting;
- 10% audit events;
- 10% operations/standing-goal events.

**Control-plane candidate target:** up to the S0 Provisioned Envelope from §39A.4. The benchmark records the actual saturation point even if lower.

**Real-engineering minimum launch proof:**

- 25 concurrent active builds;
- 250 runnable/running engineering tasks;
- 64 concurrent microVM forks;
- 128 simultaneous real model/tool operations in scheduler state;
- representative mix of new-build, existing-repo, repair, verification, security and deployment tasks;
- minimum 2 continuous hours at the candidate end-to-end load.

These are S0 launch proof minima, not the Design Envelope. If the system safely verifies more, the signed envelope records the higher measured result.

**Run sequence:**

1. 30-minute warm-up.
2. 4 hours sustained candidate control-plane load.
3. 30 minutes at 150% admission rate.
4. 10 minutes at 300% admission rate.
5. Return to candidate load for 30 minutes and prove backlog recovery.
6. Run the real-engineering minimum workload for ≥2 hours.
7. While at ≥70% of each candidate scope, inject the applicable Phase-55 failures.
8. Verify dormant regions remain unused.
9. Generate signed scoped Verified Envelope(s).

**Pass conditions:**

- MYCO-owned SLOs pass during sustained candidate load;
- overload produces documented backpressure rather than silent loss;
- accepted-work loss = 0;
- cross-tenant leakage = 0;
- evidence integrity failure = 0;
- queue returns to pre-spike steady state within 30 minutes after the 300% spike;
- no lower-priority tenant consumes protected P0/P1 reserve;
- no unbounded DB connection, workflow-history, memory or event-lag growth;
- infrastructure/model cost recorded;
- saturation point reported honestly;
- no production resources exist in dormant regions;
- no multi-region claim is emitted.

A failed launch target remains a benchmark finding. The report may not be edited to claim a pass.

## MB21 — Multi-Tenant Long-Duration Engineering Load

**Purpose:** expose memory/resource leaks, drift, noisy-neighbour failure, long-running workflow defects and cleanup problems in the S0 single-region system.

**Minimum duration:** 24 continuous hours.

**Tenant population:** at least 25 independent benchmark tenants and at least 50 concurrent/overlapping benchmark projects over the run.

**Workload mix by accepted engineering task count:**

- 20% new-build/architecture;
- 25% implementation;
- 15% integration/test;
- 10% verification;
- 10% security;
- 5% deployment;
- 5% repair;
- 10% operations/standing-goal/maintenance.

**Required perturbations:**

- one tenant driven to 100% of entitlement;
- one worker pool killed/recreated;
- one provider circuit breaker opened;
- one database replica recycled;
- one Redis loss;
- one event-consumer restart;
- one active cell temporarily closed to new placement;
- one **ephemeral same-region** second cell created from the production module;
- one project migrated between the two same-region cells and verified;
- ephemeral second cell destroyed after migration/recovery evidence is complete;
- attempted dormant-region placement rejected.

**Pass conditions:**

- accepted-work loss = 0;
- cross-tenant leakage = 0;
- unrelated-tenant p95 control-plane latency increase from noisy tenant ≤20%;
- memory/connection/file-descriptor use has no unbounded positive trend after warm-up;
- oldest eligible queue item returns below SLO after perturbations;
- same-region migration hashes/counts/acceptance checks pass;
- dormant regions remain unprovisioned/unselected;
- no capacity claim exceeds measured results;
- cost per verified engineering outcome is produced.

**Deferred benchmark rule:** multi-region MB20/MB21 variants are created and made mandatory only when stage `S2` or `S3` activates. They are not launch gates.

# 48. FINAL ACCEPTANCE MISSION

MYCO must autonomously prove all of the following in one substantial project plus the applicable S0 platform tests:

1. account creation;
2. organisation creation;
3. project creation;
4. project assignment to `eu-west-2` + authoritative Platform Cell;
5. multimodal intake;
6. repository trust scan;
7. source provenance;
8. readiness assessment;
9. requirement extraction;
10. clarification;
11. Requirements Contract;
12. architecture;
13. ADRs;
14. Software World Model;
15. World Model mutation journal;
16. Project Digital Twin;
17. build graph;
18. topology selection;
19. admission/priority decision;
20. permanent departments;
21. temporary workers;
22. five-model routing;
23. provider-capacity eligibility;
24. cross-model verification;
25. persistent Engineering Cell;
26. microVM forks;
27. real file changes;
28. dependency install;
29. migrations;
30. real build;
31. real runtime;
32. frontend/backend/data wiring;
33. Wiring Truth traces;
34. browser operation;
35. tests;
36. mutation testing;
37. property testing;
38. differential/metamorphic tests where applicable;
39. seeded implementation defect;
40. autonomous repair;
41. security scan;
42. seeded authorised exploit;
43. vulnerability repair;
44. formal verification where triggered;
45. SBOM;
46. SLSA provenance;
47. service restart mid-build;
48. workflow recovery;
49. one model provider removed;
50. continued work;
51. worker killed;
52. worker recovery;
53. delivery package;
54. `eu-west-2` staging deployment;
55. health verification;
56. bad deployment;
57. rollback;
58. documentation verification;
59. Engineering Outcome Ledger;
60. platform economics attribution;
61. Standing Goal evaluation;
62. tenant quota enforcement;
63. saturation/backpressure without accepted-work loss;
64. active-cell close-to-new-placement behavior;
65. ephemeral same-region second-cell creation + verified project migration;
66. S0 routing proves all production MYCO Cloud projects resolve only to active `eu-west-2` cells;
67. residency-policy enforcement;
68. dormant-region placement/traffic is rejected and no cross-region failover is falsely claimed;
69. Global Accelerator/cross-region replication remain absent at S0;
70. independent final acceptance;
71. truthful final report;
72. current MB20 S0 capacity evidence;
73. current MB21 24-hour evidence;
74. signed Verified Capacity Envelope tied to exact release commit/infrastructure manifest;
75. signed Scale Stage Report proving `S0_LAUNCH_SINGLE_REGION`;
76. production Terraform/state evidence proves zero active resources in configured dormant regions.

The Final Acceptance Mission passes only when all applicable items are supported by immutable evidence. A Design target not benchmarked remains `UNVERIFIED`. A deferred multi-region capability is not applicable at S0, but its configuration/module/activation-contract evidence must exist.

# 49. ULTIMATE FINISHED-SOFTWARE TEST

After MYCO declares completion, an independent engineering team receives only the delivery package.

They must be able to:

clone  
→ configure from documentation  
→ install  
→ provision local dependencies  
→ migrate  
→ build  
→ test  
→ run  
→ exercise every required feature  
→ deploy.

MYCO fails if any required feature:

- is broken;
- is unwired;
- uses fake data;
- requires undocumented manual repair;
- lacks required migration;
- fails deployment;
- was reported complete without evidence.

---

# 50. PHASE ACCEPTANCE WORKFLOW

Every phase follows exactly:

1. Checkout last verified phase tag.
2. Read current V3.2 spec.
3. Read current Phase Execution Contract.
4. Claude Code audits relevant current repository files.
5. Claude Code lists intended edits before implementation.
6. Implement only current phase scope.
7. Run formatter/linter/type checks.
8. Run phase unit tests.
9. Run phase integration/negative tests.
10. Run required security checks.
11. Run `task phase -- XX`.
12. Repair all failures.
13. User launches/tests the feature manually where applicable.
14. Independent repo audit against phase contract.
15. Scan TODO/FIXME/stub/mock/unwired production paths.
16. Verify immutable evidence.
17. Commit.
18. Annotated phase tag.
19. Only then begin next phase.

If any gate fails, remain on the same phase.

---

# 51. PRODUCTION STARTUP FAIL-CLOSED RULES

Production startup must fail if:

- authentication is disabled;
- development user is enabled;
- required encryption/signing keys absent;
- insecure default secret exists;
- database migrations incomplete;
- mandatory service unavailable;
- CORS wildcard used for credentialed production route;
- debug mode active;
- stub model selected for real production task;
- in-memory durable store selected;
- required policy engine unavailable;
- required scanner unavailable for a release that mandates it;
- tenant policy cannot load;
- model manifest invalid;
- region manifest invalid;
- scale-activation manifest invalid;
- capacity/admission manifest invalid;
- current cell identity is missing or ambiguous;
- a Verified Capacity Envelope is configured for admission but its signature/digest is invalid;
- S0/S1 declares more than one ACTIVE region;
- a CONFIGURED_DORMANT region is selected for new project placement;
- Global Accelerator or cross-region replication is active without a matching authorised scale stage;
- unsigned required Engineering Pack loaded;
- schema/version compatibility check fails.

---

# 52. EVIDENCE OBJECTS

Evidence types:

- source hash;
- diff;
- command record;
- test result;
- mutation report;
- property counterexample;
- browser trace;
- screenshot/video;
- API response;
- DB read-back;
- migration result;
- security report;
- exploit proof;
- formal proof/model-check artifact;
- benchmark result;
- SBOM;
- provenance statement;
- deployment response;
- health check;
- Wiring Trace;
- region/cell placement record;
- capacity benchmark result;
- load/soak/spike report;
- chaos/failure-under-load report;
- provider-capacity snapshot;
- cost report;
- signed Verified Capacity Envelope;
- signed Scale Stage Report;
- dormant-region infrastructure plan/zero-resource proof;
- deferred-capability activation-state evidence.

Evidence is immutable and SHA-256 addressed.

---

# 53. DELIVERY PACKAGE

Every complete project includes:

- complete source;
- repository history/export;
- Requirements Contract;
- architecture;
- ADRs;
- environment template;
- exact dependency manifests;
- setup guide;
- schema/migrations;
- API docs;
- build commands;
- test suite;
- test evidence;
- mutation/property/differential evidence where applicable;
- Wiring Truth report;
- security findings/remediation;
- SBOM;
- SLSA provenance;
- performance evidence;
- accessibility evidence where required;
- deployment configuration;
- rollback;
- observability configuration;
- current docs;
- known limitations;
- accepted risks;
- final acceptance report.

AP3/AP4 add formal assurance artifacts where triggered.

---

# 54. FINAL SYSTEM DEFINITION

MYCO V3.2 is an autonomous software engineering organisation that takes responsibility for the finished engineering outcome.

Its Engineering Brain owns state and governance.

Its Software World Model understands the complete product.

Its Project Digital Twin continuously compares desired state with verified reality.

Its Autonomy Readiness Engine decides how much autonomy is safe and repairs weak engineering foundations.

Its 13 permanent departments form the stable engineering organisation.

Its temporary specialists provide elastic capacity.

Its five-model pool gives complementary intelligence, provider diversity, cost control and independent verification.

Its persistent Engineering Cells provide speed.

Its isolated microVM task forks provide safe parallel execution.

Its Wiring Truth Engine proves that required software is actually connected.

Its Test Intelligence Engine tests the software and attacks its tests.

Its Verification Kernel prevents self-certification.

Its Formal Assurance layer proves critical invariants where required.

Its Security Swarm attacks authorised systems before external attackers do.

Its Repair Engine fixes bounded failures autonomously.

Its Operations Mode can remain responsible after launch.

Its Standing Engineering Goals keep products inside defined SLO/security/cost/quality boundaries.

Its Outcome Ledger measures engineering value.

Its ReasoningBank and Skills convert verified experience into reusable engineering capability.

Its Tool Intelligence system progressively moves routine execution intelligence into MYCO-owned models.

Its Learning Factory improves the platform under governed evaluation rather than uncontrolled self-modification.

Its sovereign deployment architecture supports cloud, hybrid, BYOC, on-prem and air-gapped operation.

Its launch deployment deliberately starts with one active MYCO Cloud region while its regional Platform Cell architecture lets project execution scale by adding same-region cells, worker pools, provider capacity and later regions without rewriting product semantics.

Its Global Directory keeps routing metadata small while project source, World Model, Digital Twin, workflows and evidence remain inside an authoritative home region/cell. At launch every hosted project resolves to `eu-west-2`; dormant regions cannot receive work.

Its Admission & Capacity Controller provides quotas, fair sharing, priority reserve and durable backpressure so saturation does not become lost engineering work.

Its Provider Capacity Manager makes model/provider availability and quotas part of routing instead of assuming infinite upstream capacity.

Its Design/Verified/Provisioned Envelopes separate architecture targets, measured proof and configured operational ceilings. Its Scale Activation Contract prevents expensive multi-region infrastructure from being deployed before demand or a contractual requirement justifies it.

Its interfaces remain simple for non-technical users while exposing deep engineering control to professional developers.

The final governing promise is:

> **MYCO does not give the customer most of an application. MYCO gives the customer the finished software.**

---

# 55. RESEARCH NOTES AND V3.2 LAUNCH-EFFICIENCY CHANGES

## 55.1 V3.2 launch-ready / scale-ready changes — 25 September 2026

V3.2 preserves every core MYCO product/verification capability from V3.1 while removing an unnecessary pre-launch infrastructure burden.

The governing correction is:

> **Architect for the Design Envelope now; provision and verify scale in response to real demand or an explicit contract/resilience gate.**

V3.2 therefore locks:

- the existing Design / Verified / Provisioned Envelope distinction;
- the 10M-user / 1M-tenant / 10M-project Design Envelope;
- regional Platform Cells and partitionable project/tenant state;
- deterministic admission, backpressure, fair queues and provider-capacity controls;
- one active launch region: `eu-west-2`;
- `us-east-1` and `ap-southeast-1` as `CONFIGURED_DORMANT`;
- no live AWS Global Accelerator at launch;
- no cross-region DB/object/event/identity standby at launch;
- a realistic S0 launch Provisioned Envelope rather than Design-Envelope pre-provisioning;
- a low-cost warm baseline distinct from the autoscaling ceiling;
- exact scale stages S0–S5 and activation reasons/authority;
- same-region horizontal cell scaling before another region is required;
- Global Accelerator activation when the second region becomes active;
- cross-region disaster recovery only at `S3_MULTI_REGION_DR`;
- MB20 rewritten to prove launch scale, saturation and recovery;
- MB21 retained as a 24-hour single-region noisy-neighbour/long-duration proof;
- ephemeral same-region second-cell migration proof instead of idle second/third production regions;
- Phase 38 rewritten as launch deployment + dormant region modules;
- Phase 55 rewritten so multi-region failure tests are deferred, not deleted;
- Final Acceptance updated so no multi-region capability can be implied at launch.

This change does not lower the Design Envelope or weaken MYCO's engineering differentiators. It moves pre-launch spend and test effort toward the Verification Kernel, Wiring Truth, autonomous repair, independent acceptance, real proof builds, competitor proof and truthful launch-capacity evidence.

## 55.2 V3.1 scale-hardening retained in V3.2

The useful V3.1 architecture remains authoritative unless superseded above:

- regional Platform Cells;
- Global Directory routing authority;
- CloudNativePG PostgreSQL HA reference;
- deterministic project placement/cell migration;
- project-scoped World Model with durable mutation journal;
- Temporal namespaces/task queues and history limits;
- Redpanda partitioning;
- Provider Capacity Manager;
- admission control/fair queues/P0-P1 reserve;
- worker and microVM autoscaling;
- platform SLOs;
- capacity manifests and signed Verified Envelope;
- platform economics in the Outcome Ledger;
- MB20/MB21 benchmark authority.

The difference is activation timing: dormant global infrastructure is no longer a pre-launch gate.

## 55.3 Research-verified infrastructure references retained from V3.1

The V3.1 infrastructure research freeze used:

- CloudNativePG 1.30.1 as the stable PostgreSQL operator reference;
- Temporal worker/task-queue scaling and Continue-As-New/child-workflow guidance;
- Redpanda partitions as the event-stream parallelism unit;
- AWS Global Accelerator as the future multi-region ingress reference.

Official reference URLs recorded by V3.1:

- `https://cloudnative-pg.io/releases/`
- `https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html`
- `https://docs.temporal.io/develop/worker-performance`
- `https://docs.temporal.io/child-workflows`
- `https://docs.redpanda.com/current/deploy/deployment-option/self-hosted/manual/sizing/`

V3.2 changes AWS Global Accelerator from a launch dependency to a deferred S2 dependency; it does not remove the future module.

No capacity number is treated as achieved merely because it appears in this design. Only signed MYCO-Bench evidence creates a `VERIFIED` claim.

## 55.4 Earlier V3 dependency/design changes

The 19 September 2026 dependency audit changed several earlier choices:

- Python 3.13.15 → Python 3.14.7.
- PydanticAI 2.44.0 → 2.45.0.
- Temporal Python SDK 1.32.0 → 1.33.0.
- E2B Runtime 2026.29 → 2026.30.
- uv 0.12.12 → 0.12.17.
- React locked to 19.3.
- React Router locked to 8.4.0.
- TypeScript locked to 7.0.2.
- Fastify uses 5.12.5 stable; v6 alpha excluded.
- Tauri uses 2.11.3 stable; v3 alpha excluded.
- Expo uses SDK 57 stable; SDK 58 beta excluded.
- Drizzle uses 0.45.2 stable; 1.0 RC excluded.
- PostgreSQL 18.6 retained; PostgreSQL 19 beta excluded.
- Node 24.21.0 LTS retained; Node 26 Current excluded from production baseline.
- Terraform 1.16.3 stable; 1.17 beta excluded.
- Helm 4.3.0 stable.
- Security/evaluation tooling refreshed to current stable September releases.

The general rule is deliberate: **latest compatible stable production release, never “latest” blindly when latest is prerelease.**

The general rule is deliberate: **latest compatible stable production release, never “latest” blindly when latest is prerelease.**

