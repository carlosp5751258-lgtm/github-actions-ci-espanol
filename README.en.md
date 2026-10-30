# GitHub Actions workflows (free)

🇪🇸 [Leer en español](README.md)

CI workflows commented line by line, with minimal permissions and caching.

**Free and open source (MIT).** Use it in your projects and your clients' projects. The files are commented in Spanish.

## What's included

- `node-ci.yml`: lint and tests on Node 20 and 22 with npm caching
- `python-ci.yml`: ruff and pytest with uv on 3.11–3.13
- `auditoria-dependencias.yml`: weekly vulnerability check

## Installation

```bash
git clone https://github.com/carlosp5751258-lgtm/github-actions-ci-espanol.git
mkdir -p .github/workflows
cp github-actions-ci-espanol/.github/workflows/node-ci.yml .github/workflows/   # or the one for your language
```

Commit and push: the workflow runs on every push and pull request. Each file tells you what to change.

## Want the full version?

This is the free version and it works on its own. The **Pro version** adds:

- 5 more workflows: Go, Docker to GHCR, tag releases, GitHub Pages deploy and caching patterns
- README guide with requirements and settings

👉 [See the Pro version](https://claudecodees.gumroad.com/l/github-actions-ci) · pay what you want from 2 USD. Buying it also helps us keep publishing free resources.

## License

MIT: you can use, modify and share it, including in commercial projects. See [LICENSE](LICENSE).

---
Part of **[Ctrl+IA](https://ctrlia.dev/en/)**: resources for coding with AI. Made by Carlos P.
