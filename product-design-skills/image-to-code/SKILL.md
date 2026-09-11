---
name: image-to-code
description: Implement a selected screenshot, mockup, Figma frame, or image-generation result as a responsive, interactive frontend.
---

# Image To Code

Begin only with an unambiguous visual target. If a numbered ideation option was selected, resolve it against the displayed image order; if it cannot be resolved, ask the user to identify or reattach the target.

Treat the visual as the source of truth. Inspect it closely, list all sections, assets, responsive cues, typography, spacing, colors, states, and controls. Use supplied assets where allowed; otherwise generate or source compatible local assets. Avoid placeholder artwork and do not replace visible branded or illustrative content with code-drawn approximations.

Build the main user journey with working primary controls, navigation, inputs, and visible states where relevant. Keep non-core chrome lightweight unless the user requests production behavior, integrations, or persistence. Run the app and verify it in a browser at the relevant viewport.

Use `$design-qa` as the blocking final comparison. Fix material fidelity or interaction issues before handoff, and report only validated results.
