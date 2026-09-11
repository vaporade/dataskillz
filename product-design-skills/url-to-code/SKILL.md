---
name: url-to-code
description: Recreate a live website the user owns or has permission to reproduce as a local, interactive frontend using captured source evidence.
---

# URL To Code

Before proceeding, remind the user to ensure they have permission and comply with the target site's terms. Use this only for a faithful recreation request—not for an open-ended redesign.

Capture the source before writing code. Inspect desktop and mobile views, page sections, responsive behavior, assets, fonts, visible controls, and meaningful interaction states. Stop if the browser shows a login wall, blocked page, wrong page, or another state that prevents valid capture.

Build only from captured evidence. Copy or replace assets locally; do not hotlink source assets. Use a suitable open-source font or icon library when the original cannot be reused. Implement the core controls and paths represented in the captured experience, then compare desktop, mobile, and key interactions with the source.

Run `$design-qa` before handoff. Report any intentionally substituted assets or behavior, and do not claim fidelity that could not be verified.
