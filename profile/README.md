<p align="center">
  <a href="https://bever.dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://bever.dev/brand/bever-logo-on-dark.svg">
      <img alt="Bever" src="https://bever.dev/brand/bever-logo.svg" width="220">
    </picture>
  </a>
</p>

<p align="center"><strong>Business applications as code.</strong></p>

Bever is an open-source language and framework for business applications. Describe entities, fields, relationships, and permissions in compact `.bev` files; Bever serves them as a validated, authorized API and a web app your team owns.

> **Bever is pre-alpha.** The language and APIs will change in breaking ways between releases, and there is no upgrade path yet. Do not use it for production data. See [Status](https://bever.dev/guide/what-is-bever#status).

```sh
dotnet tool install --global --prerelease Bever.Cli
bever new "My App" && cd "My App" && bever dev
```

| Repository | |
| --- | --- |
| [bever](https://github.com/bever-team/bever) | Compiler, semantic model, migrations, SQLite storage, and ASP.NET Core runtime |
| [bever-cli](https://github.com/bever-team/bever-cli) | The `bever` command-line tool |
| [bever-js](https://github.com/bever-team/bever-js) | `@bever/sdk`, the JavaScript SDK |
| [bever-templates](https://github.com/bever-team/bever-templates) | Project templates |
| [bever-vscode](https://github.com/bever-team/bever-vscode) | VS Code extension |
| [bever-examples](https://github.com/bever-team/bever-examples) | Example models |
| [bever.dev](https://github.com/bever-team/bever.dev) | Website and documentation |

[Documentation](https://bever.dev) · [Getting started](https://bever.dev/guide/getting-started) · [Roadmap](https://bever.dev/roadmap)
