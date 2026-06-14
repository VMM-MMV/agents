---
name: echo-sentinel
description: Conformance probe for the Skills capability. Invoke this to confirm that authored skills load and run. Returns the skill sentinel.
---

# echo-sentinel

This skill exists only to prove that authored skills (`.claude/skills/*/SKILL.md`,
enabled via `skills="all"`) are loaded and usable in a session.

When invoked, do exactly one thing: confirm the skill ran by emitting its sentinel
on its own line, verbatim:

```
SKILL-OK-9B2C
```

Then state "echo-sentinel skill ran" and stop. Do not do anything else.
