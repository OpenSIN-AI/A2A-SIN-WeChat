# A2A-SIN-WeChat Boundaries

## Role
`A2A-SIN-WeChat` owns WeChat messaging integration, automation, and WeChat-specific contracts.

## This repo should own
- WeChat messaging, routing, and automation workflows
- WeChat evidence, recovery, auth, and session handling
- WeChat contracts used by downstream messaging automation agents
- runbooks tied to WeChat delivery, automation, and monitoring

## This repo must not own
- generic messaging ownership outside WeChat
- unrelated social, community, or product platform behavior
- organization SSOT docs or architecture canon

## Hard rules
- Keep changes scoped to WeChat messaging integration and automation.
- Move non-WeChat behavior back to the repos that own those surfaces.
- Keep reusable contracts focused on WeChat delivery and automation workflows.
