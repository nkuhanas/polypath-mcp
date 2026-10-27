# Polypath MCP - Master Specification

Status: initial documentation scaffold. No product behavior, technology stack,
interface, or deployment target has been selected. No implementation exists.

This document is the canonical specification. TBDs are unresolved questions, not
requirements or permission to invent behavior. Changes to established
requirements follow [CONTRIBUTING.md](CONTRIBUTING.md) and the
[delta workflow](deltas/README.md).

## 1. Summary

- Project name: Polypath MCP.
- Problem statement and product purpose: TBD.
- Intended users and primary value: TBD.
- Repository remote and deployment targets: TBD.
- Current state: documentation scaffolding only.

## 2. Goals, scope, and non-goals

### 2.1 Goals

TBD: define the outcomes the product should achieve and how to assess them.

### 2.2 Intended MVP (P0)

TBD: define the smallest useful scope and acceptance criteria before coding.

### 2.3 Non-goals

TBD: record explicit product exclusions. The current task is limited to
documentation; application code and tooling are outside its scope.

## 3. Users and workflows

TBD: primary users, entry points, inputs, successful outcomes, partial outcomes,
failure states, and recovery paths. Add diagrams when the workflow is defined.

## 4. Requirements

TBD: establish functional and nonfunctional requirements with stable identifiers,
priorities, and observable acceptance criteria. No product requirements are
established by this scaffold.

## 5. Architecture and dependencies

### 5.1 Status vocabulary

- **Implemented and verified:** code exists and the stated check ran.
- **Selected / pending:** a decision is established; implementation or verification
  remains incomplete.
- **Planned:** intended future work, not an accepted implementation decision.
- **Proposed:** requires evaluation or approval before implementation.
- **Blocked / unresolved:** requires an external dependency or decision.

Naming a technology does not make it a selected dependency or an integration.

### 5.2 Architecture

TBD: component boundaries, runtime, transports, storage, external dependencies,
ownership, and deployment model. The repository name alone does not establish
MCP tools, resources, prompts, SDK choices, or transport requirements.

### 5.3 Responsibilities, rationale, and tradeoffs

TBD: record technology choices, alternatives, constraints, and rationale as
decisions are established. No packages or frameworks are selected yet.

## 6. Interfaces and data contracts

Canonical shared contracts belong in [contracts/](contracts/README.md).

TBD: operations, exchanged models, validation, errors, compatibility, and
versioning. Define concrete contracts before implementing their producers and
consumers. No schema format or validation tooling is selected yet.

## 7. Data handling

TBD: data sources, ownership, provenance, persistence, retention, deletion, and
limits appropriate to the eventual product.

## 8. Core behavior and methodology

TBD: core processing rules, algorithms, constraints, and failure handling.

## 9. Integrations and agent workflows

TBD: whether integrations or agent workflows are needed; if selected, define
their responsibilities, permissions, inputs, outputs, and failure handling.

## 10. User experience

TBD: interaction model, client surfaces, accessibility requirements, and user
facing errors appropriate to the selected product. No frontend is assumed.

## 11. Security and privacy

TBD: trust boundaries, authentication, authorization, secrets handling, external
access, sensitive data, and operational limits once scope is defined.

## 12. Testing and validation

### 12.1 Current checks

The scaffold contains Markdown documentation only. No application build, tests,
lint tooling, runtime checks, or deployment verification exist yet.

### 12.2 Required validation

TBD: define checks for accepted requirements and selected contracts. Document
exact commands when tooling exists. Distinguish synthetic checks from integration
and live verification, and record limitations alongside results.

## 13. Implementation priorities and ownership

### 13.1 Workstreams and priorities

TBD: define the initial scope, acceptance criteria, dependencies, and ownership.
Implementation begins only after the user authorizes coding.

### 13.2 Open questions

- What problem does Polypath MCP solve, and for whom?
- What is the first complete workflow and its acceptance criteria?
- What capabilities, clients, and external systems are in scope?
- What constraints should guide architecture, security, and deployment?

### 13.3 Architecture decision log

No architecture decisions have been established.

When decisions are made, add numbered ADR entries with date, status, context,
decision, alternatives, consequences, and related requirements or delta links.
Preserve superseded entries and link their replacements.

### 13.4 Specification change history

- 2026-10-26: initial documentation scaffold, requested by the user to follow the
  workflow in `/srv/workspaces/dead-internet-theory`. No product requirements,
  architecture decisions, or implementation were adopted from that project.

Approved changes to established requirements will be linked here and indexed in
[deltas/README.md](deltas/README.md).
