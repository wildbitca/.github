# wildbit

We build the infrastructure and tooling behind our own products, and publish the
reusable parts.

## Public projects

- **[ai-resources](https://github.com/wildbitca/ai-resources)** — a resource kit for AI
  coding agents: skills, workflows, orchestration rules, agent roles, and the
  `ai-resources` CLI. Works across Claude Code, Cursor, Gemini CLI, Codex, GitHub
  Copilot, Windsurf, Continue.dev, Aider, and OpenCode.
- **[daggerverse](https://github.com/wildbitca/daggerverse)** — shared
  [Dagger](https://dagger.io/) modules for CI/CD: a Slack progress-card engine, OIDC
  identity, toolchain and pin guards, gitleaks/Trivy scanning, and GitHub API helpers.
  Written once and consumed by every pipeline in the organization instead of being
  vendored byte-for-byte into each one.
- **[upjet](https://github.com/wildbitca/upjet)** — our fork of
  [crossplane/upjet](https://github.com/crossplane/upjet), the code generator our
  Crossplane providers below are built on.
- **[provider-upjet-supabase](https://github.com/wildbitca/provider-upjet-supabase)** —
  a Crossplane provider for [Supabase](https://supabase.com/), exposing its Management
  API as XRM-conformant managed resources.
- **[provider-upjet-cloudflare](https://github.com/wildbitca/provider-upjet-cloudflare)**
  — a Crossplane provider for the [Cloudflare](https://www.cloudflare.com/) API.
- **[provider-upjet-bunnynet](https://github.com/wildbitca/provider-upjet-bunnynet)** —
  a Crossplane provider for the [bunny.net](https://bunny.net/) API.

## Community

- [Contributing guide](../CONTRIBUTING.md)
- [Security policy](../SECURITY.md)
- [Support](../SUPPORT.md)
