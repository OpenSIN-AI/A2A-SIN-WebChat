# A2A-SIN-WebChat Boundaries

## Role
`A2A-SIN-WebChat` owns WebChat messaging integration, embed surfaces, and WebChat-specific contracts.

## This repo should own
- WebChat messaging integration, routing, and embed workflows
- WebChat evidence, recovery, auth, and session handling
- WebChat contracts used by downstream messaging automation agents
- runbooks tied to browser-based chat delivery and WebChat monitoring

## This repo must not own
- generic messaging ownership outside WebChat
- unrelated social, community, or product platform behavior
- organization SSOT docs or architecture canon

## Hard rules
- Keep changes scoped to WebChat messaging integration and embed workflows.
- Move non-WebChat behavior back to the repos that own those surfaces.
- Keep reusable contracts focused on browser chat delivery and WebChat automation.
