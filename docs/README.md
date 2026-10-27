# Documentation Catalog

`docs/` is the source of truth for repository contracts. This repository owns the typeopt optimizer.

## Repository contracts

- [Technology defaults](repository-defaults.md)
- [Development and CI](repository-workflow-contract.md)
- [Configuration and secrets](repository-environment-contract.md)
- [Licensing](repository-license-contract.md)
- [Dependency security](repository-dependency-security-contract.md)

## Templates

- [Project index](project-template.md)
- [Domain contract](domain-template.md)

## Project catalog

### typeopt

- [Project index](project-typeopt.md)
- [Rust CLI foundation](crates-typeopt-foundation.md)

## Instruction update policy

Keep feature behavior in its owning contract. Update `AGENTS.md` only when development procedures, directory ownership or development rules change. Keep validation evidence and issue or pull request traceability in GitHub records and CI logs, rather than instruction files or documentation. See [root instructions](../AGENTS.md).
