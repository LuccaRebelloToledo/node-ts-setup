# Node Ts Setup

This is a template project for kick-starting new projects using node with typescript without having to configure everything from scratch. It comes with several pre-configured development tools to help maintain code quality and facilitate development.

## Included Tools

- **ESLint**: A linting tool for JavaScript and TypeScript that helps maintain code consistency and avoid bugs.
- **Prettier**: A code formatter that ensures all code follows a consistent style.
- **Husky**: Used to set up git pre-commit hooks that can format your code and run tests before each commit.
- **Lint Staged**: Used in conjunction with Husky, it allows only the files that are staged in git to be "linted" or formatted.
- **Git Commit Message Linter**: A tool that can check the commit message to ensure it follows a commit message convention.
- **Jest**: A testing framework.

## How to Use

1. Clone this repository
2. Install dependencies with `npm install`
3. Start developing!

## Available Scripts

- `npm test`: Runs tests with Jest.
- `npm run lint`: Runs linting with ESLint.
- `npm run format`: Formats code with Prettier.

Remember that Husky and lint-staged are set up to automatically run linting and formatting before each commit and git commit message linter before each push.

## Contributing

Contributions are always welcome.