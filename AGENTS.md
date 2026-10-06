# Repository Guidelines

## Project Structure

This repository is currently an empty starting point: no application source, tests, assets, or package/build configuration are present yet. As the project takes shape, keep implementation code in clearly named top-level directories (for example, `src/`), tests in `tests/` or alongside their modules, and static files in `assets/` or the framework's conventional public directory. Update this guide when the actual structure and tooling are established.

## Development and Test Commands

No build, run, lint, or test commands are configured yet. When adding a toolchain, document its setup and canonical commands here and in the project README. Prefer commands that work from the repository root, such as `npm run build` or `pytest`, and make sure they match the checked-in configuration before relying on them.

## Style and Naming

Follow the conventions of the language and framework selected for the project. Use consistent formatting, descriptive names, and the repository's formatter or linter once configured. Name files and symbols predictably; keep modules focused and avoid introducing a second style or tool for the same purpose.

## Testing

There is no test framework or test suite yet. Add tests with new behavior and bug fixes when the project establishes its testing stack. Use clear test names that describe the behavior being checked, and document the command contributors should run before submitting changes.

## Reviewing Changes

Keep each change focused so it is easy to review. Before considering work complete, inspect the Git diff and summarize which files changed and why. Once the project has build and test commands, run the relevant checks and report their results; do not claim checks passed unless they were run.

## Commits and Pull Requests

Git history has no commits yet, so no commit-message convention can be inferred. Write concise imperative commit subjects (for example, `Add project scaffold`). Pull requests should explain the change, mention relevant issues, and include screenshots for user-visible UI changes. Call out tests run and any known gaps.

## Configuration and Secrets

Do not commit credentials, tokens, or local environment files. Provide safe examples in an environment template (such as `.env.example`) and document required configuration without exposing secret values.
