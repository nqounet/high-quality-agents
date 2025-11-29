# AGENTS.md

## Project Overview

This repository demonstrates the AGENTS.md format—an open specification for providing AI coding agents with the context and instructions they need to work effectively on a project. The AGENTS.md format is designed to complement README.md by containing detailed technical context specifically for automated tools.

**Key Technologies**: Markdown

**Purpose**: Serve as a reference implementation and example of a well-structured AGENTS.md file that follows the public guidance at https://agents.md/.

## Setup Commands

Since this is a documentation-focused repository, no build or installation steps are required:

- Clone the repository: `git clone <repository-url>`
- Navigate to project root: `cd <project-directory>`

## Development Workflow

This repository contains documentation files only. To contribute:

1. Create a new branch from `main`
2. Make your changes to the Markdown files
3. Validate Markdown syntax and formatting
4. Submit a pull request

## Testing Instructions

For Markdown-only repositories:

- Validate Markdown links: Check that all links resolve correctly
- Validate Markdown syntax: `npx markdownlint-cli2 "**/*.md"`
- Review rendered output: Preview Markdown files in an editor or browser

## Code Style

### Markdown Guidelines

- Use ATX-style headers (`#` symbols)
- Use fenced code blocks with language identifiers
- Maintain consistent list formatting (use `-` for unordered lists)
- Include blank lines between sections for readability
- Use meaningful link text instead of raw URLs
- Keep lines at a reasonable length for readability

### File Organization

- Place AGENTS.md at the repository root
- Use clear, descriptive section headers
- Order sections from most to least essential
- Group related information together

## Build and Deployment

No build or deployment steps are required for this documentation repository. Changes merged to the `main` branch are immediately available.

## Pull Request Guidelines

- **Title format**: `[docs] Brief description of changes`
- **Required checks**: Validate Markdown syntax before submission
- **Review requirements**: Ensure all sections are accurate and actionable
- **Commit messages**: Use clear, descriptive commit messages

## Additional Notes

### About AGENTS.md Format

The AGENTS.md format works with 20+ AI coding tools including:

- Cursor
- Aider
- Gemini CLI
- GitHub Copilot
- And many others

### Best Practices for Creating AGENTS.md Files

1. **Be specific**: Include exact commands, not vague descriptions
2. **Use code blocks**: Wrap commands in backticks for clarity
3. **Include context**: Explain why certain steps are needed
4. **Stay current**: Update as the project evolves
5. **Test commands**: Ensure all listed commands actually work
6. **Consider nested files**: For monorepos, create AGENTS.md files in subprojects as needed

### Adapting This Template

When using this as a template for your own projects:

1. Replace placeholder sections with project-specific commands
2. Add language-specific code style guidelines
3. Include actual test commands and coverage requirements
4. Add security considerations if applicable
5. Document debugging and troubleshooting tips
6. For monorepos, create additional AGENTS.md files in subproject directories
