# Erylis Labs

Personal software engineering lab for experimenting with application architecture,
developer tooling, automation, and local-first software.

## About

Erylis Labs hosts personal projects built with an emphasis on:

- simple and maintainable architectures;
- reproducible development environments;
- local-first and privacy-conscious design where relevant;
- automated quality checks;
- dependency and supply-chain hygiene;
- minimal operational complexity and recurring cost.

Projects are primarily developed for personal use, learning, and experimentation.

## Projects

### Roadbook

Local-first travel planner designed for a couple.

Roadbook runs primarily on a home network, with a PC-hosted server and browser
clients. It also supports a detached offline travel mode for mobile devices.

Key technologies include:

- TypeScript
- React
- Vite
- Fastify
- Socket.IO
- SQLite
- npm workspaces
- VS Code Dev Containers

## Engineering principles

Projects in this organization generally favor:

**Local-first by default**
Data and services should remain under the user's control when cloud infrastructure
does not provide meaningful value.

**Explicit architecture**
Important architectural decisions, constraints, and invariants should be documented
rather than hidden in implementation details.

**Reproducible environments**
A project should be easy to clone, bootstrap, build, test, and run from a clean
development environment.

**Automation with least privilege**
CI/CD workflows should use minimal permissions, controlled dependencies, and
predictable execution environments.

**Keep operations simple**
Infrastructure and external services should only be introduced when their benefits
justify their operational and financial cost.

## Security

Security issues should not be reported through public issues.

Please follow the security policy provided by the affected repository, or the
organization-wide [security policy](../SECURITY.md) when no repository-specific
policy exists.

## Contributing

These repositories are primarily personal projects, but contributions may be
accepted where appropriate.

See the organization-wide [contributing guidelines](../CONTRIBUTING.md) for the
default development and contribution practices.

---

_Erylis Labs is a personal GitHub organization and is not a commercial entity._
