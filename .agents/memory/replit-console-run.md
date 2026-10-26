---
name: Replit console Run workflow
description: Naming and mapping the Run workflow for console applications in this project.
---

Use a descriptive workflow name such as `Java Console`, and keep `.replit`'s `workflows.runButton` mapped to that exact name. The generic name `Project` is rejected by workflow configuration.

**Why:** Replit refused to create a workflow named `Project`, despite that being the prior Run button mapping.

**How to apply:** When setting up a console app's Run button, configure its console workflow under a descriptive name and update the `.replit` mapping to match.
