# Security Policy

## Reporting a vulnerability

**Do not open a public issue for a security problem.** An issue is visible to everyone the
moment it is created, including to whoever would exploit it.

Use GitHub's private vulnerability reporting instead. Most repositories in the
organization have it enabled:

1. Go to the repository's **Security** tab.
2. **Report a vulnerability**.
3. Describe what you found, how to reproduce it, and what an attacker gains.

The report is visible only to the maintainers. You will get an acknowledgement, and a fix
or an explanation of why it is not one, before anything is made public.

If a repository does not have private reporting enabled, open an issue there asking for a
reporting channel instead of describing the vulnerability itself — the fix is to turn the
feature on, not to publish the details.

## Scope

This file is the organization-wide default: it applies to any repository that does not
declare its own `SECURITY.md`. Several repositories carry a more specific policy (for
example, our Crossplane providers scope reports to credential handling, privilege
escalation through a Composition, and secret leakage into logs or managed-resource
status) — read the repository's own file first if it has one.

## Supported versions

Only the latest released version of a given repository is supported. There are no
backports to older tags: the fix ships in a new release.
