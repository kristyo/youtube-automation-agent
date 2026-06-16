```markdown
# youtube-automation-agent Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill teaches you the core development conventions and patterns used in the `youtube-automation-agent` repository. The project is built with TypeScript and Express, focusing on automating YouTube-related tasks. You'll learn about file organization, code style, commit message habits, and how to write and structure tests in this codebase.

## Coding Conventions

### File Naming
- Use **camelCase** for all file names.
  - Example: `youtubeAgent.ts`, `videoProcessor.ts`

### Import Style
- Use **relative imports** for modules within the project.
  - Example:
    ```typescript
    import { processVideo } from './videoProcessor';
    ```

### Export Style
- Use **named exports** for functions, classes, and constants.
  - Example:
    ```typescript
    // In videoProcessor.ts
    export function processVideo() { ... }
    export const VIDEO_LIMIT = 10;
    ```

### Commit Patterns
- Commit messages are **freeform** with a **title prefix**.
- Average commit message length is about 65 characters.
  - Example:
    ```
    Add video processing logic for batch uploads
    ```

## Workflows

_No explicit workflows detected in repository._

## Testing Patterns

- **Testing Framework:** Unknown (not specified in the repository).
- **Test File Pattern:** All test files follow the `*.test.*` naming convention.
  - Example: `youtubeAgent.test.ts`
- **Test Placement:** Tests are placed alongside implementation files or in dedicated test directories.
- **Test Example:**
  ```typescript
  // youtubeAgent.test.ts
  import { processVideo } from './youtubeAgent';

  describe('processVideo', () => {
    it('should process video successfully', () => {
      // test implementation
    });
  });
  ```

## Commands
| Command | Purpose |
|---------|---------|
| /coding-conventions | Show coding conventions for this repo |
| /testing-patterns   | Show how to write and structure tests |
```
