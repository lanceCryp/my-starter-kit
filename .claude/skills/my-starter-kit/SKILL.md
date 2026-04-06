```markdown
# my-starter-kit Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill teaches the core development patterns and conventions used in the `my-starter-kit` repository, a TypeScript-based React starter kit. You'll learn about file naming, import/export styles, commit message patterns, and testing conventions to ensure consistency and maintainability across the codebase.

## Coding Conventions

### File Naming
- Use **camelCase** for all file names.
  - Example: `myComponent.tsx`, `userProfile.test.ts`

### Import Style
- Use **relative imports** for all modules.
  - Example:
    ```typescript
    import { MyComponent } from './myComponent';
    ```

### Export Style
- Use **named exports** for all modules.
  - Example:
    ```typescript
    // myComponent.tsx
    export const MyComponent = () => { ... };
    ```

### Commit Message Patterns
- Commit messages are **freeform**, but may use the `deps` prefix for dependency updates.
- Average commit message length: 78 characters.
  - Example:
    ```
    deps: update react and react-dom to latest version
    ```

## Workflows

_No automated workflows detected in this repository._

## Testing Patterns

- **Framework:** Unknown (not detected)
- **Test File Pattern:** Files ending with `.test.*`
  - Example: `myComponent.test.tsx`
- **Test Placement:** Test files are placed alongside the modules they test.

## Commands
| Command | Purpose |
|---------|---------|
| /commit-deps | Use when updating dependencies (prefix commit with `deps:`) |
| /test | Run all test files matching `*.test.*` pattern |
```