# Contributing to A2A-SIN-WebChat

## Scope first

Before changing code or docs, verify the change genuinely belongs to the **WebChat** surface.

Put the change here when it affects:
- WebChat messaging integration, routing, or embed workflows
- WebChat evidence, recovery, auth, or session handling
- WebChat contracts tied to browser chat delivery and integration

Do **not** put the change here when it belongs to:
- generic messaging ownership outside WebChat
- unrelated social, community, or product platform behavior
- organization SSOT docs or architecture ownership

## Workflow

1. Branch from the latest `main`.
2. Make the smallest repo-scoped change possible.
3. Run validation command(s) relevant to the touched surface.
4. Include exact validation commands and evidence in the PR.

## Boundary checklist

- Does this change stay within WebChat ownership?
- Does another repo already own the adjacent platform behavior?
- Does this PR avoid redefining shared docs, runtime, or platform canon?

## License

By contributing, you agree that your contributions will be licensed under the Apache License 2.0.
