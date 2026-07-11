---
applyTo: "**/*.{ts,tsx,js,jsx}"
description: "TypeScript and JavaScript coding conventions"
---

# TypeScript / JavaScript Instructions

- Use TypeScript over plain JS for any non-trivial project
- Use `const` by default, `let` only when reassigning, never `var`
- Prefer `async/await` over `.then()` chains
- Use arrow functions for callbacks and anonymous functions
- Use `interface` over `type` for object shapes (open by default)
- Use strict TypeScript config (`strict: true`)
- Use ESM (`import`/`export`) over CommonJS (`require`/`module.exports`)
- Prefer `undefined` over `null`
- Use `===` and `!==` over `==` and `!=`
- Name files with kebab-case (`my-component.tsx`)
