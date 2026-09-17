# Contributing

Thanks for your interest in contributing. This file is the organization-wide default —
it applies to any repository that does not declare its own `CONTRIBUTING.md`. A few
repositories do, and their guide takes precedence for anything it covers:

- [provider-upjet-supabase](https://github.com/wildbitca/provider-upjet-supabase/blob/main/CONTRIBUTING.md)
- [provider-upjet-cloudflare](https://github.com/wildbitca/provider-upjet-cloudflare/blob/main/CONTRIBUTING.md)
- [provider-upjet-bunnynet](https://github.com/wildbitca/provider-upjet-bunnynet/blob/main/CONTRIBUTING.md)
- [upjet](https://github.com/wildbitca/upjet/blob/main/CONTRIBUTING.md) (our fork of
  `crossplane/upjet`; it keeps upstream's own contribution rules, DCO sign-off included)

## Before you start

If the repository has issues enabled, open one describing what you'd like to change
before writing code — it avoids duplicated effort and lets a maintainer steer you before
you invest time. Most repositories in the organization do **not** have issues enabled;
if that's the case, open your pull request directly and describe the change in its
description instead.

## Branches

Branch names are enforced org-wide on creation. A branch name must match:

```
^(build|chore|ci|docs?|feat(ure)?|fix|bugfix|hotfix|perf|refactor|release|revert|style|tests?)/[\w\-./]+$
```

For example: `feat/short-description`, `fix/short-description`, `docs/short-description`.

## Commits

The default branch requires every commit message on it to follow
[Conventional Commits](https://www.conventionalcommits.org/):

```
^(build|chore|ci|docs|feat|fix|perf|refactor|revert|style|test)(\([\w\-.]+\))?(!)?: .+
```

For example: `fix(auth): reject expired tokens` or `feat!: drop support for v1 config`.

## Pull requests

The default branch of every repository is protected:

- A pull request is required — no direct pushes.
- At least one approving review, from a code owner where a `CODEOWNERS` file exists.
- A push to the PR after approval or a rewrite of its history dismisses stale approvals
  and requires a fresh review of the latest state.
- Review threads must be resolved before merging.
- History must stay linear (squash or rebase merges; no merge commits).
- Some repositories additionally require a green `ci` status check before merging.

## License

Unless a repository states otherwise, contributions are made under the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), the license our
public repositories use, on an inbound = outbound basis: you license your contribution
under the same terms as the project. No Developer Certificate of Origin sign-off or
Contributor License Agreement is required.
