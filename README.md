# Matchbox's Cursor configs

A collection of [Cursor](https://github.com/getcursor/cursor) configurations and rules used by the Matchbox team.

## Rules

Cursor rules ([docs](https://docs.cursor.com/context/rules-for-ai)) customize the AI behavior. You can set project-specifc or global rules. Because we develop in multiple languages with different coding-standards, we use project rules stored in `/.cursor/rules` directory.

- [`style-guide.mdc`](.cursor/rules/style-guide.mdc) - Documentation style guide for writing, punctuation and formatting.

> [!IMPORTANT]
> The `.cursorrules` file is being deprecated ([source](https://docs.cursor.com/context/rules-for-ai#cursorrules)). If you encounter a project using this format, please update it to use project rules.
