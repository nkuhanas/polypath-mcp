# Schemas and contracts

This directory holds canonical shared schemas and interface contracts for data
exchanged between components, such as requests, responses, events, and shared
payloads, once those interfaces are established.

No contracts, schema formats, protocol versions, or validation tools have been
selected. This scaffold does not adopt the reference project's APIs or models.

## Usage

- Add definitions here as interfaces are established. Choose formats appropriate
  to the selected stack and document their validation commands when tooling exists.
- Give files descriptive names and group them by interface or domain as needed.
- Describe fields, required and optional values, constraints, and error behavior
  in each contract's format or accompanying documentation.
- Keep examples beside the canonical definition and validate them when tooling
  is available. Label synthetic examples clearly.
- Have producers and consumers reference or generate from these definitions.
  Document generated outputs and their regeneration command; edit source
  definitions rather than generated copies.
- Review affected producers and consumers before changing a contract. Document
  compatibility, versioning, and migration needs, and update examples and
  validation together with the definition.

## Validation

No contract checks are available yet. Document exact setup and validation commands
here when concrete contracts and tooling are selected. Contract validation alone
does not establish runtime correctness or live integration behavior.

[SPEC.md](../SPEC.md) defines requirements and links to concrete contracts here.
Follow [CONTRIBUTING.md](../CONTRIBUTING.md) for changes that contradict
established requirements.
