# ESLint Configuration

This project uses a custom ESLint configuration designed for **React**, **TypeScript**, and modern **JavaScript** development. It combines recommended rules from ESLint, TypeScript, React, and several plugins to enforce code quality, formatting, and import organization.

---

## Key Features

- **TypeScript support** via `typescript-eslint`.
- **React & React Hooks** linting with recommended rules.
- **Prettier integration** for consistent code formatting.
- **Unused imports/variables detection**.
- **Import sorting** with `simple-import-sort`.
- **Browser global variables** support.
- Supports **JS, TS, JSX, TSX** files.

---

## Language Options

- ECMAScript latest version.
- JSX syntax enabled.
- Browser global variables available.

---

## Plugins

- [`eslint-plugin-react`](https://www.npmjs.com/package/eslint-plugin-react)
- [`eslint-plugin-react-hooks`](https://www.npmjs.com/package/eslint-plugin-react-hooks)
- [`eslint-plugin-prettier`](https://www.npmjs.com/package/eslint-plugin-prettier)
- [`eslint-plugin-import`](https://www.npmjs.com/package/eslint-plugin-import)
- [`eslint-plugin-unused-imports`](https://www.npmjs.com/package/eslint-plugin-unused-imports)
- [`eslint-plugin-simple-import-sort`](https://www.npmjs.com/package/eslint-plugin-simple-import-sort)
- [`eslint-plugin-react-refresh`](https://www.npmjs.com/package/eslint-plugin-react-refresh)

---

## Key Rules

| Rule | Description | Severity |
|------|-------------|----------|
| `prettier/prettier` | Enforces Prettier formatting: single quotes, no trailing commas | error |
| `unused-imports/no-unused-imports` | Removes unused imports automatically | error |
| `unused-imports/no-unused-vars` | Warns for unused variables, ignores `_` prefixed names | warn |
| `@typescript-eslint/no-unused-vars` | Warns on unused TypeScript variables | warn |
| `@typescript-eslint/explicit-function-return-type` | Disabled | off |
| `comma-dangle` | Disallow trailing commas | error |
| `@typescript-eslint/no-empty-function` | Warns on empty functions | warn |
| `@typescript-eslint/no-explicit-any` | Warns on `any` types | warn |
| `@typescript-eslint/consistent-type-imports` | Prefer type imports in TypeScript | warn |
| `prefer-const` | Suggest using `const` | warn |
| `jsx-quotes` | Enforce double quotes for JSX | warn |
| `consistent-return` | Warn if functions don't consistently return a value | warn |
| `import/first` | Ensure imports appear first | error |
| `import/newline-after-import` | Require a newline after imports | error |
| `simple-import-sort/imports` | Sort imports automatically | error |
| `simple-import-sort/exports` | Sort exports automatically | error |
| `react/display-name` | Disabled (not required for functional components) | off |
| `react/react-in-jsx-scope` | Disabled (React 17+ JSX transform) | off |

