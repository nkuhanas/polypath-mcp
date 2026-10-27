# Agent Instructions

## Read before working

- Read [README.md](README.md) for project context and setup.
- Read [CONTRIBUTING.md](CONTRIBUTING.md) for the development and commit workflow.
- Read the relevant sections of [SPEC.md](SPEC.md) for the current task. Read
  additional sections when a change affects their assumptions or contracts.
- Check for more specific `AGENTS.md` instructions in directories you work in.
- Before changing an interface or exchanged data, read
  [contracts/README.md](contracts/README.md) and the relevant contract definitions.

## Schemas and contracts

- Keep shared schemas and interface contracts in the top-level `contracts/`
  directory. Link to canonical definitions rather than maintaining independent
  copies in component directories or documentation.
- Keep producers, consumers, examples, and relevant validation aligned when a
  contract changes. Check compatibility and document any migration needed.
- Choose schema formats and validation tools when requirements and the stack
  are established. Do not invent schemas or select tooling to fill placeholders.
- Follow `CONTRIBUTING.md` when a contract change contradicts established spec
  requirements.

## Working expectations

- The current scope is documentation scaffolding only. Do not add application
  code, dependencies, build tooling, or deployment configuration until the user
  authorizes implementation.
- Keep changes scoped to the task and preserve unrelated work.
- Treat placeholder text as unfinished documentation, not a source of invented
  requirements. Ask for clarification when a material decision cannot be inferred
  from the task or existing code.
- Implement small, reviewable slices and make a Conventional Commit after each
  completed slice when Git is available, following `CONTRIBUTING.md`.
- Run checks appropriate to the change and report their results and any limits.
- Update documentation when behavior, setup, or interfaces change.
- When deployable components exist, report whether a requested change requires
  redeployment, whether it was deployed, and any remaining deployment action.
