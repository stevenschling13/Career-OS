# AI Collaboration Guide

This document outlines the workflow for coordinating multiple AI agents (Gemini in Google AI Studio, ChatGPT Agent/Codex) to collaborate on the Career OS project.

## Roles
- **Gemini (Google AI Studio)**: Use Build mode with Gemini 3 Pro to generate or modify code. Follow the design prompt in `docs/design_prompt.md` and commit code changes.
- **ChatGPT (Agent / Codex)**: Audits code changes, suggests improvements, writes tests, updates documentation, and manages repository settings.

## Workflow
1. **Plan & Prompt**: Before generating code, review `docs/design_prompt.md` and `docs/AI_collaboration.md` to ensure the design and coding standards are respected.
2. **Generate & Test**: Use Gemini to generate code. Run unit tests locally or via GitHub Actions.
3. **Commit Changes**:
   - After code generation, commit changes with descriptive messages.
   - Push to a feature branch and open a pull request if significant, or commit directly to `main` for minor updates.
4. **Audit & Review**:
   - Use ChatGPT agent or Codex to review the pull request or commit.
   - Ensure code quality, security, and standards compliance.
   - Provide feedback and request changes if necessary.
5. **Sync & Iterate**:
   - Merge approved changes.
   - Update documentation (`README.md`, `docs/design_prompt.md`, etc.) to reflect new features.
   - Ensure both AI tools reference the latest code state before continuing.

## Standards
- Adhere to the coding conventions outlined in `CONTRIBUTING.md`.
- Use consistent commit messages and update any changelog if maintained.
- Maintain synchronization between this repository and Google AI Studio sessions. Always pull latest changes before generating new code.

## Branch Protection
- The `main` branch should be protected; require at least one approving review and CI status checks to pass before merging.
