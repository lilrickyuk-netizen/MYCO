# MYCO V3 — FINAL IMPLEMENTATION-LOCKED PRODUCTION DESIGN AND BUILD PLAN

**Version:** 3.0 Final — Implementation-Locked Edition  
**Owner:** Richard Curley  
**Status:** Authoritative Production Design and Construction Specification  
**Research freeze:** 19 September 2026  
**Primary commercial competitors:** Lovable, Replit  
**Secondary architecture benchmark:** Factory  
**Build authority:** This document supersedes all earlier MYCO v1/v2/v3 drafts where they conflict.

---

# 0. AUTHORITY RULES

This specification defines both **what MYCO is** and **how it is built**.

There are four levels of authority, in this order:

1. **This V3 specification** — product behaviour, architecture, security, autonomy and completion rules.
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

**Control path:**

MYCO Interfaces  
→ API Gateway  
→ Authentication  
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
→ Build Supervisor  
→ Adaptive Agent Topology Controller  
→ Temporal Durable Workflow Engine  
→ 13 Permanent Departments  
→ Temporary Specialist Workforce  
→ Five-Model Gateway  
→ Context Intelligence Layer  
→ Tool Gateway  
→ Engineering Cell Service  
→ microVM Task Fork Runtime  
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

Each responsibility has one production authority.

---

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

MYCO optimises:

> probability of verified completion / total cost / elapsed time

Total cost includes retries, repair, verifier work, compute, failed trajectories and human intervention.

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

`v3-phase-XX-<slug>`

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

Required metrics:

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

Primary commercial metric:

> **Cost and elapsed time to independently verified finished software.**

---

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

# 36. DATA OWNERSHIP AND SERVICE BOUNDARIES

## 36.1 PostgreSQL

One PostgreSQL cluster, strict schema ownership.

`apps/api` is the sole authority for platform relational writes and migrations through Drizzle.

Schemas:

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

Python AI services do not write PostgreSQL directly. They use authenticated internal APIs/events.

## 36.2 Neo4j

World Model Service is sole graph-write authority.

## 36.3 Redis

Permitted only for:

- cache;
- rate limiting;
- transient coordination;
- short-lived presence.

Redis is never authoritative durable workflow state.

## 36.4 Object storage

S3 API.

Local: MinIO.

Production: S3-compatible provider.

Evidence/artifact objects use versioning, digest and retention lock where available.

## 36.5 Event stream

Redpanda using Kafka protocol.

Event envelope: CloudEvents 1.0.

---

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

MYCO Cloud control plane:

- RPO ≤5 minutes.
- RTO ≤60 minutes.
- PostgreSQL PITR enabled.
- object storage versioning enabled.
- Neo4j backups enabled.
- Temporal persistence backed up according to deployment architecture.
- Vault recovery material protected separately.
- full restore test quarterly after commercial launch.

Backup existence alone is insufficient; restore must be tested.

---

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

# 41. SOURCE-CONTROLLED DEPENDENCY FILES

Required root files:

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

No caret/range is permitted for top-level production dependencies. Exact versions only.

---

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
│   └── design/
├── infra/
│   ├── docker/
│   ├── terraform/
│   ├── kubernetes/
│   ├── helm/
│   ├── temporal/
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
│   ├── e2e/
│   └── acceptance/
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
- `task build`
- `task verify`
- `task sbom`
- `task phase -- <phase-number>`

`task verify` is the root acceptance command and must fail on any mandatory gate.

---

# 44. PHASE EXECUTION CONTRACT TEMPLATE

Every phase file under `docs/phases/PHASE-XX.md` must contain:

1. Phase ID/name
2. Objective
3. Preconditions
4. V3 sections implemented
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

Claude Code is not allowed to implement the phase until this contract exists.

---

# 45. CLAUDE CODE BUILD DIRECTIVE

Every phase prompt begins with this immutable instruction:

> The MYCO V3 specification and the current Phase Execution Contract are authoritative. You may not change architecture, substitute required production behaviour with mocks/stubs, defer mandatory phase scope, weaken acceptance tests, remove required validation, expand permissions, or declare completion without executing all required evidence-producing commands. Inspect the complete current repository state relevant to this phase before editing. If a required dependency, API or design rule is contradictory or unavailable, stop and report the exact blocker instead of inventing an alternative architecture.

---

# 46. PHASE-BY-PHASE ZERO-GUESS BUILD PLAN

## PHASE 0 — AUTHORITATIVE TRUTH BASELINE

**Objective:** create a reproducible empty MYCO V3 monorepo with all construction rules locked before product code.

**Create:**

- repository structure from §42;
- `MYCO_V3_SPEC.md`;
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
- ADR template;
- phase-contract template;
- GitHub Actions skeleton;
- CODEOWNERS;
- branch protection documentation;
- Renovate/Dependabot configuration in proposal-only mode.

**Commands:**

`corepack enable`  
`pnpm install --frozen-lockfile`  
`uv sync --frozen`  
`task verify`

**Negative tests:** no floating top-level versions; no prerelease package without ADR; no source file containing placeholder success implementation.

**Evidence:** dependency inventory, licence inventory, initial SBOM, successful clean bootstrap.

**Exit:** fresh clone on reference environment runs `task bootstrap && task verify` successfully.

**Tag:** `v3-phase-00-truth-baseline`.

---

## PHASE 1 — CONTRACTS AND CORE DOMAIN SCHEMAS

**Objective:** establish machine-readable cross-language authority before services.

**Create:**

- `packages/contracts/`;
- JSON Schemas for Project, Requirement, Architecture, Task, Agent, Model, Tool, Evidence, Approval, Usage, Deployment;
- OpenAPI root contract;
- CloudEvents schemas;
- generated TypeScript/Python models.

**Rule:** generated models are never hand-edited.

**Tests:** schema round-trip, TS/Python compatibility, UUIDv7/RFC3339 validation, Problem Details schema.

**Exit:** same canonical fixtures validate in TypeScript and Python.

**Tag:** `v3-phase-01-contracts`.

---

## PHASE 2 — AUTHENTICATION, TENANCY AND AUTHORITY

**Objective:** establish identity boundaries before business features.

**Build:**

- Keycloak reference IdP;
- OIDC session flow;
- organisations/memberships/roles;
- PostgreSQL RLS;
- SPIFFE/SPIRE service identities;
- OPA decision service;
- Vault integration;
- approval levels A0–A6/AX;
- immutable audit events.

**APIs:** `/api/v1/auth/*`, `/api/v1/organisations/*`, `/api/v1/memberships/*`, `/api/v1/approvals/*`.

**Negative tests:** forged user ID, cross-tenant resource ID, expired token, revoked session, worker with wrong SPIFFE identity, tool request above authority.

**Exit:** automated breakout suite proves no cross-tenant read/write path.

**Tag:** `v3-phase-02-identity-tenancy`.

---

## PHASE 3 — DURABLE DATA FOUNDATION

**Objective:** bring up authoritative persistence.

**Build:** PostgreSQL 18.6, Redis 8.10, Neo4j 2026.08.1, MinIO local object store, Temporal, Redpanda, OTel Collector.

**Database ownership:** Drizzle migrations are sole PostgreSQL migration authority.

**Tests:** restart persistence, PITR rehearsal, object checksum, graph persistence, Temporal workflow restart, Redpanda replay.

**Exit:** service restart and host restart do not lose committed project/task/audit state.

**Tag:** `v3-phase-03-durable-data`.

---

## PHASE 4 — PROJECT INTAKE AND REPOSITORY TRUST FIREWALL

**Objective:** safely ingest files/repos while preserving provenance.

**Build:** upload service, repository importer, MIME/type detection, SHA-256 provenance, archive extraction sandbox, lifecycle-script scanner, symlink/path escape protection, secrets scan, agent-instruction classification.

**APIs:** `/api/v1/projects`, `/api/v1/projects/{id}/assets`, `/api/v1/projects/{id}/repositories/import`.

**Negative tests:** zip-slip, symlink escape, malicious package postinstall, secret in repo, repository prompt injection.

**Exit:** malicious fixture repository cannot execute before trust decision.

**Tag:** `v3-phase-04-intake-trust`.

---

## PHASE 5 — REQUIREMENTS ENGINE

**Objective:** convert source intent into a versioned Requirements Contract.

**Build:** requirement classifier, source links, contradiction detection, clarification queue, acceptance criteria, versioning, progressive slices, change impact.

**APIs:** `/api/v1/projects/{id}/requirements/*`.

**Tests:** assumption cannot become confirmed without approval; changed requirement creates new version and impact record.

**Exit:** every confirmed requirement has source + validation method + evidence rule.

**Tag:** `v3-phase-05-requirements`.

---

## PHASE 6 — ARCHITECTURE ENGINE

**Objective:** generate a machine-readable technical architecture tied to requirements.

**Build:** architecture entities/relations, service boundaries, API/data/event contracts, security boundaries, ADR workflow, architecture rules.

**Exit:** intentionally violating architecture rule is detected mechanically.

**Tag:** `v3-phase-06-architecture`.

---

## PHASE 7 — SOFTWARE WORLD MODEL

**Objective:** build canonical project knowledge graph.

**Build:** Neo4j entity types, relation types, graph ingestion from source/requirements/architecture, provenance links, read API.

**Exit:** MYCO answers “what exists?”, “what depends on it?”, “which requirement owns it?” using evidence-backed graph queries.

**Tag:** `v3-phase-07-world-model`.

---

## PHASE 8 — PROJECT DIGITAL TWIN

**Objective:** compute desired/actual/difference state.

**Build:** desired-state projector, actual-state projector, difference classifier, evidence links, drift events.

**Exit:** seeded missing API or migration appears as explicit difference state.

**Tag:** `v3-phase-08-digital-twin`.

---

## PHASE 9 — AUTONOMY READINESS ENGINE

**Objective:** implement R0–R5 scoring and remediation.

**Build:** weighted rubric from §12, hard blockers, remediation task generator, authority cap by readiness.

**Exit:** poor fixture repo scores below R3, repairs are generated, repaired repo rescored upward with evidence.

**Tag:** `v3-phase-09-readiness`.

---

## PHASE 10 — PERSISTENT ENGINEERING CELLS

**Objective:** create reusable project environments.

**Build:** cell manifests, dependency/toolchain installation, persistent dev services, health checks, cache management, snapshot source point.

**Reference execution host:** Linux KVM worker nodes. Local Windows development does not attempt Firecracker directly.

**Exit:** cell survives worker/service restart and returns identical toolchain/version manifest.

**Tag:** `v3-phase-10-engineering-cells`.

---

## PHASE 11 — microVM TASK FORKS

**Objective:** safe isolated parallel task execution.

**Build:** E2B/Firecracker runtime adapter, snapshot/fork, quotas, network classes N0–N5, copy-on-write workspace, isolated task DB, destroy/cleanup.

**Negative tests:** path escape, host secret access, cross-project mount, privileged container, Docker socket access.

**Exit:** two concurrent forks can edit same parent project without cross-contamination.

**Tag:** `v3-phase-11-microvm-forks`.

---

## PHASE 12 — REAL EXECUTION ENGINE

**Objective:** execute actual engineering commands.

**Build:** command API, xterm stream, stdout/stderr/exit/duration/resource accounting, process kill/timeout, dev server supervisor.

**Rule:** non-zero exit is failure unless command contract explicitly defines accepted codes.

**Exit:** build/test/migration/server commands run in fork and produce immutable evidence.

**Tag:** `v3-phase-12-execution`.

---

## PHASE 13 — TOOL REGISTRY AND GATEWAY

**Objective:** governed real tool use.

**Build:** ToolDefinition/Grant/Call/Verification tables, MCP adapter, credential broker, OPA checks, read-back verifiers.

**Exit:** unauthorised tool cannot be discovered/invoked; authorised write is independently verified.

**Tag:** `v3-phase-13-tool-gateway`.

---

## PHASE 14 — LIFECYCLE HOOK RUNTIME

**Objective:** signed deterministic extension hooks.

**Build:** OCI/WASI hook packaging, Cosign verification, Wasmtime sandbox, permissions, typed I/O, timeouts.

**Exit:** malicious hook fixture cannot access undeclared filesystem/network.

**Tag:** `v3-phase-14-hooks`.

---

## PHASE 15 — FIVE-MODEL GATEWAY

**Objective:** one provider-independent gateway for five model families.

**Build:** provider adapters, model manifest, BYOK, managed keys, self-hosted Qwen/vLLM, data-class routing, health/fallback, usage records.

**Exit:** common contract suite passes against all five families; one provider can be disabled without platform failure.

**Tag:** `v3-phase-15-five-model-gateway`.

---

## PHASE 16 — MODEL PERFORMANCE ROUTER

**Objective:** route by verified outcome, not preference.

**Build:** capability scores, task history, expected total-cost estimator, producer/verifier diversity rule, benchmark registry.

**Exit:** routing decision includes auditable reason and measured historical evidence.

**Tag:** `v3-phase-16-model-router`.

---

## PHASE 17 — CONTEXT INTELLIGENCE

**Objective:** retrieve only decision-relevant context.

**Build:** hybrid lexical/vector/code retrieval, tenant/project filters, Context Broker, compression service, context provenance.

**Exit:** retrieval benchmark returns required files/requirements without cross-project contamination.

**Tag:** `v3-phase-17-context`.

---

## PHASE 18 — SKILLS AND REASONINGBANK

**Objective:** reusable verified engineering expertise.

**Build:** Skill schema, ReasoningLesson schema, evaluation score, versioning, promotion pipeline.

**Exit:** one lesson learned from fixture A improves fixture B without copying proprietary source.

**Tag:** `v3-phase-18-skills-reasoningbank`.

---

## PHASE 19 — AGENT HARNESS

**Objective:** bounded runtime contract for every worker.

**Build:** identity, objective, context, model, tools, workspace, network, budget, evidence, heartbeat, termination.

**Exit:** one bounded specialist completes and proves a real engineering task with no out-of-scope writes.

**Tag:** `v3-phase-19-agent-harness`.

---

## PHASE 20 — 13 PERMANENT DEPARTMENTS

**Objective:** implement every permanent department as tested real capability.

**Build:** typed agent definitions, department-specific tool grants, outputs, tests and handoffs.

**Rule:** prompt-only agent is incomplete.

**Exit:** each department passes department acceptance suite on a real fixture.

**Tag:** `v3-phase-20-departments`.

---

## PHASE 21 — TEMPORARY SPECIALIST WORKFORCE

**Objective:** elastic worker spawning.

**Build:** worker lifecycle, concurrency, heartbeat, stale detection, reassignment, duplicate prevention, cleanup, resource limits.

**Exit:** killed worker task is recovered exactly once.

**Tag:** `v3-phase-21-temporary-workforce`.

---

## PHASE 22 — ADAPTIVE TOPOLOGY CONTROLLER

**Objective:** select single/sequential/swarm/competitive execution scientifically.

**Build:** feature extraction, topology policy, cost/parallel gain estimation, outcome logging.

**Exit:** sequential benchmark selects sequential path; parallel benchmark selects parallel path; decision recorded.

**Tag:** `v3-phase-22-topology`.

---

## PHASE 23 — BUILD SUPERVISOR

**Objective:** orchestrate complete multi-phase engineering work.

**Build:** requirement loading, difference-state planning, task graph, department assignment, topology call, budget control, checkpoints, blocker handling.

**Exit:** one multi-service fixture is planned/executed without manual task-by-task prompting.

**Tag:** `v3-phase-23-build-supervisor`.

---

## PHASE 24 — WIRING TRUTH ENGINE

**Objective:** prove end-to-end product wiring.

**Build:** journey registry, OpenTelemetry journey propagation, static flow map, runtime span correlation, required-node policy, WiringTrace evidence.

**Exit:** seeded disconnected button and seeded fake backend success both fail completion.

**Tag:** `v3-phase-24-wiring-truth`.

---

## PHASE 25 — BASE TEST ENGINE

**Objective:** normal correctness coverage.

**Build:** Vitest/pytest, API/integration DB harness, Playwright, Maestro, axe-core, k6, visual baseline store.

**Exit:** deliberately broken business logic, permission and migration fixtures are detected.

**Tag:** `v3-phase-25-base-testing`.

---

## PHASE 26 — TEST ADVERSARY

**Objective:** test the tests.

**Build:** StrykerJS, mutmut, mutant classification, surviving-mutant task creation, assertion weakening detection.

**Exit:** intentionally weak test suite fails mutation threshold until strengthened.

**Tag:** `v3-phase-26-test-adversary`.

---

## PHASE 27 — PROPERTY / DIFFERENTIAL / METAMORPHIC TESTING

**Objective:** find broad edge cases and migration regressions.

**Build:** fast-check, Hypothesis, differential runner, metamorphic relation schema.

**Exit:** seeded invariant violation and seeded migration behaviour drift are detected.

**Tag:** `v3-phase-27-advanced-testing`.

---

## PHASE 28 — COMPUTER-USE VERIFICATION

**Objective:** prove running software through real user interaction.

**Build:** browser session service, DOM/accessibility/network capture, screenshots/video, mobile emulator integration.

**Exit:** MYCO can execute required user journey and attach machine-readable + visual evidence.

**Tag:** `v3-phase-28-computer-use`.

---

## PHASE 29 — INDEPENDENT VERIFICATION KERNEL

**Objective:** make acceptance independent from production agents.

**Build:** Requirements Verifier, Behaviour Verifier, Wiring Verifier, Mergeability Verifier, cross-model critic, Acceptance Vault.

**Exit:** deliberately false producer completion claim is rejected.

**Tag:** `v3-phase-29-verification-kernel`.

---

## PHASE 30 — FORMAL VERIFICATION

**Objective:** machine-check critical invariants.

**Build:** formal trigger classifier, TLA+/TLC runner, Z3 service, Dafny adapter, Lean adapter, proof evidence.

**Exit:** selected distributed/permission fixture has machine-checkable proof/model-check evidence; seeded invariant failure is found.

**Tag:** `v3-phase-30-formal-verification`.

---

## PHASE 31 — DEVSECOPS ENGINE

**Objective:** continuous secure development.

**Build:** Semgrep, Gitleaks, OSV-Scanner, Trivy, Syft, Cosign, ZAP integration, threat model schema, ASVS mapping.

**Exit:** scanners run from CI and task runtime; seeded secret/dependency/IaC vulnerability is detected.

**Tag:** `v3-phase-31-devsecops`.

---

## PHASE 32 — OFFENSIVE SECURITY SWARM

**Objective:** authorised runtime attack verification.

**Build:** auth attacker, tenant attacker, API attacker, business-logic attacker, exploit verifier; safe target allowlist.

**Exit:** seeded authorised vulnerability is reproduced, repaired and reverified.

**Tag:** `v3-phase-32-offensive-security`.

---

## PHASE 33 — AUTOMATIC REPAIR ENGINE

**Objective:** bounded autonomous failure recovery.

**Build:** failure classifier, root-cause candidate generation, repair task, before/after evidence, no-progress/oscillation detector, rollback.

**Exit:** seeded failure repairs without weakening tests; oscillating repair fixture stops safely.

**Tag:** `v3-phase-33-repair`.

---

## PHASE 34 — DESIGN SYSTEM AND DESIGN STUDIO

**Objective:** implement the locked MYCO visual direction and visual product-building tools.

**Build:** design tokens from §35, shared component library, creation screen, canvas, responsive frames, screenshot import, variants, visual diff, component extraction.

**Exit:** screenshot-to-working-screen fixture matches visual acceptance threshold and all controls remain wired.

**Tag:** `v3-phase-34-design-studio`.

---

## PHASE 35 — CONNECTOR FABRIC

**Objective:** deterministic external engineering-system integrations.

**Initial connectors:** GitHub, GitLab, Jira, Linear, Slack, Teams, Sentry, Datadog/Grafana adapter, AWS, Azure, GCP, OCI registry, deployment providers.

**Exit:** connector read/write actions use scoped credentials and read-back verification.

**Tag:** `v3-phase-35-connectors`.

---

## PHASE 36 — ENGINEERING PACK PLATFORM

**Objective:** safe extension ecosystem.

**Build:** pack manifest, OCI registry, signatures, permission review, SBOM, install/update/revoke, Pack Factory test harness.

**Exit:** signed fixture pack installs; modified unsigned fixture is rejected.

**Tag:** `v3-phase-36-engineering-packs`.

---

## PHASE 37 — DELIVERY AND PROVENANCE

**Objective:** independently rebuildable final package.

**Build:** artifact manifest, source export, SBOM, SLSA provenance, test/security/wiring evidence index, documentation package, known-risk register.

**Exit:** clean reference machine rebuilds product using delivery docs only.

**Tag:** `v3-phase-37-delivery`.

---

## PHASE 38 — DEPLOYMENT ENGINE

**Objective:** real staged deployment and rollback.

**Build:** OCI image pipeline, Terraform/Helm adapters, provider credentials, health/smoke/read-back, release digest, rollback.

**Exit:** staging deploy succeeds, seeded bad release is detected and rollback restores previous healthy version.

**Tag:** `v3-phase-38-deployment`.

---

## PHASE 39 — OPERATIONS MODE

**Objective:** persistent engineering ownership after delivery.

**Build:** alerts, incidents, SLOs, dependency maintenance, vulnerability response, controlled production repair.

**Exit:** seeded production fault becomes isolated repair, verified release and healthy redeployment under policy.

**Tag:** `v3-phase-39-operations`.

---

## PHASE 40 — STANDING ENGINEERING GOALS

**Objective:** continuous objective enforcement.

**Build:** GoalContract, evaluator schedule, violation events, remediation policy, escalation.

**Exit:** seeded latency/security goal violation creates correct bounded workflow and verified recovery.

**Tag:** `v3-phase-40-standing-goals`.

---

## PHASE 41 — ENGINEERING OUTCOME LEDGER

**Objective:** quantify real autonomous engineering value.

**Build:** outcome metrics, cost attribution, human-intervention tracker, feature/requirement cycle time, defect escape metrics.

**Exit:** proof build produces auditable cost/time-to-verified-completion report.

**Tag:** `v3-phase-41-outcome-ledger`.

---

## PHASE 42 — ENGINEERING TELESCOPE

**Objective:** full trajectory observability for improvement.

**Build:** trajectory records, model/tool/context links, failure clustering inputs, privacy filters.

**Exit:** repeated seeded failure trajectories cluster into one root pattern without leaking another tenant's source.

**Tag:** `v3-phase-42-telescope`.

---

## PHASE 43 — CONTROLLED LEARNING FACTORY

**Objective:** safe measurable self-improvement.

**Build:** candidate creation, offline evaluation, regression, security/adversarial suite, canary, rollback.

**Exit:** one routing/skill candidate is promoted only after benchmark improvement; failing candidate is rejected.

**Tag:** `v3-phase-43-learning-factory`.

---

## PHASE 44 — TOOL INTELLIGENCE

**Objective:** owned specialist models for routine tool orchestration.

**Build:** verified tool-chain dataset generator, training manifest, TRL training pipeline, vLLM serving, tool benchmark.

**Exit:** self-hosted specialist meets defined success/cost threshold on bounded tool workflows.

**Tag:** `v3-phase-44-tool-intelligence`.

---

## PHASE 45 — EVOLUTIONARY ENGINEERING

**Objective:** objective search over candidate implementations.

**Build:** candidate population, benchmark function, selection, iteration budget, final regression/security verification.

**Exit:** optimisation benchmark beats first-pass solution while preserving behaviour.

**Tag:** `v3-phase-45-evolutionary-engineering`.

---

## PHASE 46 — MYCO EVERYWHERE

**Objective:** common project control from every surface.

**Build:** web, Tauri desktop, CLI, VS Code extension, JetBrains plugin, Expo mobile, Slack, Teams, API.

**Exit:** same task can be created on one surface, observed on another, approved on a third, with identical backend task/evidence IDs.

**Tag:** `v3-phase-46-everywhere`.

---

## PHASE 47 — SOVEREIGN DEPLOYMENT

**Objective:** deploy whole MYCO in customer-controlled environments.

**Build:** Cloud, Hybrid, BYOC, On-Prem, Air-Gap packaging; local model manifest; offline registry/mirror documentation.

**Exit:** at least one fully customer-controlled deployment passes platform acceptance without MYCO Cloud data-plane dependency.

**Tag:** `v3-phase-47-sovereign`.

---

## PHASE 48 — BILLING AND ENTITLEMENTS

**Objective:** secure commercial controls.

**Build:** Stripe Billing reference integration, subscriptions, usage aggregation, entitlements, overages, portal, billing audit.

**Rule:** frontend never determines entitlement.

**Exit:** tampered client cannot unlock paid capability; usage reconciles to server records.

**Tag:** `v3-phase-48-billing`.

---

## PHASE 49 — COMPLETE PRODUCT UI

**Objective:** wire every production capability to the premium V3 UX.

**Required screens:** Home, Projects, Design Studio, Requirements, Architecture, Readiness, Digital Twin, Build, Workforce, IDE, Terminal, Preview, Wiring Truth, Tests, Security, Evidence, Deployments, Operations, Standing Goals, Outcomes, Billing, Settings.

**Exit:** route/button/permission/error/empty-state sweep finds zero fake or disconnected production controls.

**Tag:** `v3-phase-49-product-ui`.

---

## PHASE 50 — MYCO-BENCH

**Objective:** repeatable internal benchmark authority.

**Bench classes:** MB01–MB19 from §47 below.

**Exit:** reproducible report records quality, speed, cost, security, autonomy and human intervention.

**Tag:** `v3-phase-50-myco-bench`.

---

## PHASE 51 — REAL INTERNAL PROOF BUILDS

**Objective:** prove MYCO on substantial owned products, not toy demos.

**Rule:** manual coding used to fix a MYCO-declared-complete result invalidates that run.

**Exit:** multiple real end-to-end builds pass independent finished-software test.

**Tag:** `v3-phase-51-proof-builds`.

---

## PHASE 52 — LONGITUDINAL PRODUCT TEST

**Objective:** prove software remains evolvable.

**Build:** apply at least 50 sequential approved changes to one MYCO-built product.

**Measure:** regression, architecture drift, cost, manual intervention, test health.

**Exit:** product remains inside defined architecture/security/quality limits.

**Tag:** `v3-phase-52-longitudinal`.

---

## PHASE 53 — COMPETITOR PROOF

**Objective:** evidence-based differentiation against current Lovable and Replit.

**Method:** equivalent requirements and acceptance criteria, recorded costs and elapsed time, no hidden easier MYCO requirements.

**Measure:** first preview, finished time, human intervention, missing requirements, wiring, test strength, security, deployment, repair.

**Primary metric:** cost/time to independently verified finished software.

**Exit:** comparative evidence package exists; results are reported honestly whether favourable or not.

**Tag:** `v3-phase-53-competitor-proof`.

---

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

**Tag:** `v3-phase-54-controlled-autonomy`.

---

## PHASE 55 — FINAL SYSTEM HARDENING AND ACCEPTANCE

**Objective:** prove production MYCO V3 under adversarial failure.

**Required fault tests:**

- tenant breakout;
- malicious repository;
- prompt injection;
- secret theft attempt;
- provider outage;
- one of five LLMs removed;
- worker crash;
- Temporal worker restart;
- PostgreSQL fail/recovery;
- Redis loss;
- Redpanda interruption;
- Neo4j restart;
- object-store interruption;
- model timeout;
- tool timeout;
- network partition;
- corrupted task attempt;
- deployment failure;
- rollback;
- backup restore;
- overload/rate limit;
- malformed event;
- malicious Engineering Pack;
- malicious lifecycle hook.

**Exit:** no unresolved critical defect; final Acceptance Mission passes.

**Tag:** `v3.0.0-production-accepted`.

---

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

External component benchmarks may include SWE-bench, SWE-smith and ViBench, but none replaces MB19.

---

# 48. FINAL ACCEPTANCE MISSION

MYCO must autonomously prove all of the following in one substantial project:

1. account creation;
2. organisation creation;
3. project creation;
4. multimodal intake;
5. repository trust scan;
6. source provenance;
7. readiness assessment;
8. requirement extraction;
9. clarification;
10. Requirements Contract;
11. architecture;
12. ADRs;
13. Software World Model;
14. Project Digital Twin;
15. build graph;
16. topology selection;
17. permanent departments;
18. temporary workers;
19. five-model routing;
20. cross-model verification;
21. persistent Engineering Cell;
22. microVM forks;
23. real file changes;
24. dependency install;
25. migrations;
26. real build;
27. real runtime;
28. frontend/backend/data wiring;
29. Wiring Truth traces;
30. browser operation;
31. tests;
32. mutation testing;
33. property testing;
34. differential/metamorphic tests where applicable;
35. seeded implementation defect;
36. autonomous repair;
37. security scan;
38. seeded authorised exploit;
39. vulnerability repair;
40. formal verification where triggered;
41. SBOM;
42. SLSA provenance;
43. service restart mid-build;
44. workflow recovery;
45. one model provider removed;
46. continued work;
47. worker killed;
48. worker recovery;
49. delivery package;
50. staging deployment;
51. health verification;
52. bad deployment;
53. rollback;
54. documentation verification;
55. Engineering Outcome Ledger;
56. Standing Goal evaluation;
57. independent final acceptance;
58. truthful final report.

---

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
2. Read current V3 spec.
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
- Wiring Trace.

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

MYCO V3 is an autonomous software engineering organisation that takes responsibility for the finished engineering outcome.

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

Its interfaces remain simple for non-technical users while exposing deep engineering control to professional developers.

The final governing promise is:

> **MYCO does not give the customer most of an application. MYCO gives the customer the finished software.**

---

# 55. RESEARCH NOTES — WHAT CHANGED FROM THE EARLIER V3 DRAFT

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

