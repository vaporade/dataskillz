---
name: ideate
description: Generate distinct image-based product-design directions, remixes, or visual alternatives from a grounded product brief.
---

# Visual Ideation

Use this after `$get-context` has established the product, intended outcome, and target surface. Prefer visual exploration to prose-only concepts unless the user explicitly requests prose.

Develop three materially distinct directions. Each should solve the same user problem but differ in hierarchy, interaction emphasis, visual language, and information density. Ground prompts in supplied screenshots, brand assets, tokens, and references when relevant. Do not mix alternatives into one generated image.

For every direction, define the user task, primary screen/state, key content, and visual constraints before generating. Use current dates for any time-sensitive mock data. Avoid device bezels or operating-system chrome in mobile app concepts unless the user specifically requests device framing.

Return each generated option exactly once in display order, then ask the user to choose an option or request refinements. Do not start implementation until a visual target is selected.
