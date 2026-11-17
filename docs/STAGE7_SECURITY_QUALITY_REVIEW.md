# Stage 7 — Public repository security and quality review

**Status:** Proposed documentation for maintainer review. This checklist is not evidence that any unverified GitHub setting is enabled. No settings change is authorised by this document.

## Observed public baseline (17 November 2026)

- This repository is public and documentation-focused; its default branch is `main`.
- The active `main` ruleset prohibits branch deletion and non-fast-forward updates. It does **not** require pull requests, approvals or status checks.
- Public Issues, Discussions, Wiki and Projects are disabled.
- The repository has a README, CONTRIBUTING.md, SECURITY.md, a central community guide and a public roadmap.
- Discord is described, but no verified direct application URL has been published.
- Private application source and sensitive operational evidence are out of scope.

## Owner-only checks — do not change without separate approval

| Check | Evidence required | Status |
| --- | --- | --- |
| Require PR before merging to `main` | Ruleset screenshot or API confirmation, and owner merge-path validation | Not configured |
| Review approval policy | Feasibility for single-maintainer account; no self-lockout | Not configured |
| Secret scanning and push protection | Repository Security settings and supported plan/feature availability | Not independently verified |
| Private vulnerability reporting | Advisory setting and testable reporting route; compare with SECURITY.md | Not independently verified |
| Collaborators and app access | Owner-only access review without publishing identities or tokens | Not reviewed |
| Tokens and account recovery | Owner-only least-privilege and 2FA check; never share credentials | Not reviewed |
| Workflow permissions | Read-only defaults and approved workflow design if Actions is later adopted | Not reviewed |

## Documentation quality checks

- Validate internal relative links and headings on a review branch.
- Confirm public statements distinguish design intent, historical milestones and independently verified results.
- Keep a central, maintained community entry route without publishing an unapproved Discord invite.
- Check that any proposed Actions workflow uses no wallet access, private dependencies, elevated permissions, remote scripts or private project artefacts.
- Preserve existing rights notices and the pseudonymous maintainer identity.

## Acceptance boundary

A checked box in this file is not a completed security qualification. Changes to rulesets, Actions, vulnerability reporting, Issues, Discussions, repository visibility, authentication, collaborators, tokens or permissions require separate explicit owner approval. No live trading or access to private systems is authorised.
