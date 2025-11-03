# Claude Code Configuration

This directory contains configuration files for Claude Code, an AI-powered coding assistant.

## Files Overview

### `context.md`
Provides project context to Claude, including:
- Project overview and purpose
- Technology stack details
- Project structure
- Development workflow
- Deployment information

This helps Claude understand your project better and provide more relevant assistance.

### `ignore`
Specifies files and directories that Claude should not read or modify, including:
- Image files (binary assets)
- Compiled/minified CSS
- Git directory
- Build artifacts

This improves performance and prevents Claude from modifying files that shouldn't be changed.

### `commands/`
Custom slash commands that provide shortcuts for common tasks:

- **`/bump-version`** - Bump the semantic version number in version.txt
- **`/add-project`** - Add a new project to the portfolio showcase section
- **`/validate`** - Validate HTML structure and check for common issues
- **`/optimize`** - Analyze the site and suggest optimizations for performance, accessibility, and SEO

## Using Claude Code

To use these configurations with Claude Code:

1. Make sure you have Claude Code installed
2. The configuration is automatically loaded when Claude Code runs in this directory
3. Use slash commands by typing them in Claude Code (e.g., `/bump-version`)
4. Claude will automatically reference the context.md file for better understanding of your project

## Customization

Feel free to:
- Add more custom commands in the `commands/` directory
- Update `context.md` as your project evolves
- Modify `ignore` patterns based on your needs

For more information about Claude Code configuration, visit: https://docs.claude.com/claude-code
