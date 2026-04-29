## TypeScript
- Separate test configurations (e.g., `tsconfig.test.json`) must be referenced in `package.json` scripts and the main `tsconfig.json` should exclude test files to prevent overlapping strictness. When extending `tsconfig.json` for tests, override `exclude` to ensure test files are not inadvertently excluded.
