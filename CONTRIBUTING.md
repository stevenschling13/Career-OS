# Contributing to Career OS

Thank you for considering contributing to this project! We welcome contributions of all kinds.

## How to Contribute

- **Bug reports:** Please open an issue describing the problem, including steps to reproduce, expected behavior, and observed behavior. Provide as much context as possible (logs, screenshots, environment).
- **Feature requests:** Open an issue describing the enhancement you’d like to see, including why it’s useful and any examples.
- **Pull requests:** Fork the repository and create a branch for your change. Follow the coding standards described below. Write or update tests. Describe the change in the PR description and reference the relevant issue if applicable.

## Development Setup

1. Clone the repository and install dependencies:

```bash
git clone https://github.com/stevenschling13/Career-OS.git
cd Career-OS
# Install dependencies (root-level tools)
# For frontend:
cd frontend
npm install
cd ../backend
npm install
```

2. Create a `.env.local` in each package to store configuration (never commit secrets).

3. Run the development servers:

```bash
# In frontend/
npm run dev

# In backend/
npm run dev
```

## Coding Standards

- Use modern TypeScript and ECMAScript syntax.
- Follow the project's ESLint and Prettier configuration. Run `npm run lint` before committing.
- Write unit tests for new features (`npm test`).
- Keep functions small and focused. Write clear, descriptive names.
- Document functions and modules when non-obvious.

## Commit Messages

Use concise, present-tense commit messages:

```
Add feature X to module Y
Fix bug in Z function
Update documentation for...
```

## Pull Request Process

1. Ensure your branch is up to date with `main`.
2. Run tests and linters locally; fix any issues.
3. Submit a PR against the `main` branch. Explain what the change does and why.
4. A maintainer will review your PR. Please address feedback promptly.
5. After approval, the PR will be merged.

Thank you for helping make this project better!
