---
name: index
description: Route explicit Product Design work—including UX research, product-flow audits, visual ideation, source recreation, prototype QA, or sharing—to the focused workflow. Do not use for ordinary code implementation unless the request is chiefly product-design work.
---

# Product Design Router

Use this as the entrypoint for Product Design requests. It routes work; it does not perform the focused workflow itself.

Choose the narrowest matching skill:

- `$user-context` for setup, saved references, preferences, or recalling context.
- `$get-context` before a new design, redesign, prototype, or UI exploration when the target or user outcome is unclear.
- `$research` for evidence-backed investigation of current user pain or workflow friction.
- `$audit` for critique, review, or accessibility/UX assessment of an existing flow or screen.
- `$ideate` for image-based visual alternatives before a visual target is chosen.
- `$url-to-code` for a faithful local recreation of a site the user owns or may recreate.
- `$image-to-code` after the user supplies or chooses a screenshot, mockup, or other visual target.
- `$design-qa` only to compare an implemented prototype with its reference before handoff.
- `$share` only when the user asks to deploy or create a shareable URL.

For a new product UI with no visual target, resolve the brief with `$get-context`, then use `$ideate`; do not scaffold or build before a design is selected. For a request that combines audit and implementation, audit first and treat follow-on implementation as a separate step.

Use the available browser only when evidence from a live surface is needed. Keep the user updated briefly, state assumptions, and preserve any existing codebase unless the request authorizes changes.
