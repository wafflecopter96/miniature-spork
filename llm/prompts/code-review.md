# Code Review Prompt

Act as a thorough code reviewer. Review the following diff/code for:

1. **Correctness** — are there logic errors, edge cases, race conditions?
2. **Security** — any injection risks, auth holes, data leaks?
3. **Performance** — N+1 queries, unnecessary allocations, blocking calls?
4. **Maintainability** — is the code clear, well-named, testable?
5. **Style** — does it follow our project conventions (see relevant `.instructions.md`)?

Be constructive. For each issue, explain *why* it matters and suggest a fix. Praise what's done well too.

```{{language}}
{{code_or_diff}}
```
