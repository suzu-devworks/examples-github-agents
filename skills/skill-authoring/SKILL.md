---
name: skill-authoring
description: |
  Format SKILL.md descriptions in English with a clear action, target, and criterion first. Keep the description to 1 to 2 short sentences before Use when.
  Use when creating a new SKILL file, updating an existing SKILL file, or reviewing a SKILL description.
---

# Skill Authoring

Use this workflow when creating or updating a SKILL.md file.

## Description

Write the front matter description as YAML block scalar text in this shape:

```yaml
description: |
  [Verb] [target] [criterion]. [Concrete behavior sentence 1].
  Use when [condition 1], [condition 2], or [condition 3].
```

## Requirements

- Start with a concrete verb.
- Make the target explicit.
- Write the description in English.
- Include side effects or follow-up actions when they matter.
- Avoid vague trigger phrases such as improve code.
- Keep the description to 1 to 2 sentences before Use when.
- Insert a line break before Use when, and place it on its own line.
- End with explicit Use when conditions.
- Apply the format to both new SKILL files and existing SKILL files being maintained.
