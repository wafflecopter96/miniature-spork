# LLM Instructions

Place custom `.instructions.md` or `.prompt.md` files here that you want to use with VS Code Copilot or other LLM tools.

## Format

Each file should follow the standard format with YAML frontmatter:

```yaml
---
applyTo: "*"          # glob pattern for files this applies to
description: "..."     # short description of what this does
---
Your instructions here...
```

## Examples

- `general.instructions.md` — global coding preferences
- `python.prompt.md` — Python-specific conventions
- `git-commit.instructions.md` — commit message style
