<!-- qompassai/deno-template/README.md -->
<!-- Replace Deno, Template for Qompass AI Deno projects. and deno when you instantiate this template. -->

# Deno

> Template for Qompass AI Deno projects.

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)

A Qompass AI template for Deno (tool) projects — starter configs,
automation skeletons, and operational notes in the standard Qompass AI
layout.

## How to use this template

1. On GitHub, click **Use this template** → **Create a new repository**.
   ([About creating a repository from a template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template))
2. Name it after your project.
3. Replace every `{{PLACEHOLDER}}` in this README and in `CITATION.cff`,
   then delete this section.
4. Copy the starter configs into place and validate each with the command
   noted at its top (e.g. `nginx -t`, `terraform validate`).

Placeholders used in this template:

| Placeholder      | Meaning                          | Example               |
|------------------|----------------------------------|-----------------------|
| `Deno`    | Project name, title case         | Deno           |
| `Template for Qompass AI Deno projects.`| One-line repo description        | Template for Qompass AI Deno projects.       |
| `deno`       | Lowercase, URL-safe name         | deno              |

## Layout

```text
src/            # source: configs, scripts, automation
tests/          # validation notes (each starter names its check command)
docs/           # deep dives: setup, operations, gotchas, ecosystem map
examples/       # smallest-first runnable/usable snippets
.github/        # CI: sanity checks on every push
```

## Neovim-first

Matt builds in Neovim. His config (diver) is the primary driver here:
see [docs/NEOVIM.md](docs/NEOVIM.md) for the wiring checklist
(formatter, linter, build/test, DAP). `.nvim.lua` ships project-local
settings — it defines commands only and never runs anything by itself.

## License

This project is licensed under the [Apache License, Version 2.0](./LICENSE).

Copyright 2026 Qompass AI.
