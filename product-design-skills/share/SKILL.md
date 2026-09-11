---
name: share
description: Deploy a verified runnable prototype using the user's chosen hosting target and return the working share URL.
---

# Share Prototype

Confirm the project directory and deployment target. If the user has not selected a host, ask one concise question about their preferred provider. Do not substitute another provider without permission.

Before deploying, run the project’s appropriate build and available checks. Verify the result is runnable and preserve the existing project configuration. Use the chosen deployment tool when available; otherwise explain the limitation and ask whether the user wants another target.

Return a working share URL only after deployment succeeds. State any remaining manual follow-up and do not claim the prototype is shared based merely on a successful local build.
