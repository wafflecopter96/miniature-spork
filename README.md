# miniature-spork

Personal knowledge repo — random text files, notes, and LLM instructions that I want version-controlled and available across machines.

## Structure

```
llm/            Custom instructions, system prompts, and reusable prompts for LLMs
  instructions/   .instructions.md / .prompt.md style files
  prompts/        Reusable prompt templates for specific tasks

tech/           Technical notes, configs, setup guides, troubleshooting
personal/       Personal notes, health, finance, recipes, etc.
journal/        Time-based journal entries (YYYY/YYYY-MM-DD.md)
templates/      Reusable document templates
```

## Conventions

- Files are Markdown (`.md`) unless there's a reason not to be
- Journal entries go in `journal/YYYY/YYYY-MM-DD.md`
- Keep files reasonably atomic — one topic per file
- No sensitive data (passwords, tokens, PII). Use `.gpg` or `.age` if needed and add the encrypted extension to git.
- Use `git` for syncing; keep commits small and messages descriptive
