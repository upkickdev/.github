<div align="center">

# Upkick

### Start projects with structure, not boilerplate.

Upkick is an open-source project scaffolding and code generation platform for building production-ready applications from clear, reusable blueprints.

[Website](https://upkick.dev) · [GitHub](https://github.com/upkickdev)

</div>

---

## What is Upkick?

Starting a new project usually means repeating the same decisions:

* Choosing a project structure
* Installing and configuring packages
* Creating database schemas
* Setting up authentication
* Connecting infrastructure
* Writing repetitive foundational code

Upkick turns those decisions into reusable, composable project blueprints.

Describe what you want to build, and Upkick helps generate the structure, configuration, schemas, and code required to get started.

## What we're building

### Upkick CLI

A developer-first command-line interface for creating and extending projects.

```bash
upkick create my-app
upkick add auth
upkick generate schema portfolio
```

The CLI is designed to understand the existing project before generating new code.

### Upkick Console

A web-based workspace for:

* Creating project blueprints
* Configuring application architecture
* Generating project-aware templates
* Managing reusable schemas and modules
* Connecting GitHub repositories
* Sharing templates with teams and the community

### Project-aware generation

Upkick does not treat every project as an empty folder.

Generators can use information about your:

* Framework and runtime
* Package manager
* Database and ORM
* Authentication system
* Existing directory structure
* Naming conventions
* Installed dependencies

This allows generated code to fit the project instead of forcing the project to fit a generic template.

## Principles

### You own the generated code

Generated projects are normal source-code repositories. They can be modified, deployed, and maintained without depending on Upkick at runtime.

### Predictable over magical

Generated changes should be understandable, reviewable, and reproducible.

### Composable building blocks

Templates, schemas, modules, and generators should work independently or together.

### Framework-aware, not framework-locked

Upkick can provide deep integrations without becoming a replacement for your framework, package manager, or monorepo tooling.

### Open by default

The core CLI, generator ecosystem, specifications, and official templates are being developed as open-source projects.

## Project status

Upkick is currently in early development.

The initial focus is on:

* CLI foundations
* Project detection
* Authentication between the CLI and Upkick Console
* Template and generator specifications
* Project-aware schema generation
* GitHub integration
* Community-maintained templates

Interfaces and commands may change while the foundations are being established.

## What Upkick is not

Upkick is not:

* A replacement for Turborepo, Nx, or workspace tools
* A deployment platform
* A proprietary application runtime
* A collection of unmaintainable copy-paste templates
* An AI agent that silently rewrites an entire codebase

Upkick focuses on **starting and extending software projects with structured, reviewable code generation**.

## Contributing

Upkick is being built in the open.

As repositories become available, contributions will be welcome across:

* CLI development
* Project detectors
* Code generators
* Templates
* Documentation
* Framework integrations
* Developer experience

Contribution guidelines will be published alongside the first public repositories.

## Community

Follow the organization to track the first public releases and development updates.

For product information, visit [upkick.dev](https://upkick.dev).

---

<div align="center">

**Build the foundation. Keep the ownership.**

</div>
