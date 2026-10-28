# Contributing to Bever

Thank you for your interest in Bever. Contributions of every size are welcome: bug reports, documentation fixes, examples, and code.

## Where things live

| Change | Repository |
| --- | --- |
| Language, compiler, semantic model, runtime, migrations | [bever](https://github.com/bever-team/bever) |
| `bever` commands | [bever-cli](https://github.com/bever-team/bever-cli) |
| JavaScript SDK | [bever-js](https://github.com/bever-team/bever-js) |
| Generated app and server | [bever-templates](https://github.com/bever-team/bever-templates) |
| Editor support | [bever-vscode](https://github.com/bever-team/bever-vscode) |
| Example models | [bever-examples](https://github.com/bever-team/bever-examples) |
| Website and documentation | [bever.dev](https://github.com/bever-team/bever.dev) |

Each repository's `CONTRIBUTING.md` explains how to build and test it.

## How to contribute

1. **Search existing issues** before opening a new one.
2. **Bugs:** include a minimal `.bev` model, the command you ran, what you expected, and what happened.
3. **Ideas and language changes:** open an issue first. Changes to the language, the semantic model, or the HTTP API span several repositories, so agree the design in the issue before opening pull requests.
4. **Pull requests:** keep them focused, add tests, and describe how you verified the change. Update the documentation in the same change or in a linked pull request to bever.dev.

## Principles

- **Business meaning first.** The language describes the business, not the framework.
- **Secure by default.** Nothing is allowed until an action allows it, and the server decides every request.
- **No silent behavior.** Unsupported constructs are errors; destructive changes need consent; record IDs are never shown to people.
- **People own their code.** Generated projects are ordinary projects; Bever stays a library.

## License

By contributing, you agree that your contribution is licensed under the license of the repository it is made to: the Apache License 2.0 for `bever`, `bever-cli`, `bever-js`, and `bever-vscode`; MIT No Attribution for `bever-templates`, `bever-examples`, and code in `bever.dev`; CC BY 4.0 for documentation text in `bever.dev`. "Bever" and the Bever logo are [trademarks](https://github.com/bever-team/bever/blob/main/TRADEMARKS.md).

## Code of conduct

Everyone participating in the Bever community follows the [code of conduct](CODE_OF_CONDUCT.md).
