# AI Coding Agents

This document provides information about AI coding agents used in the SillyTavern project.

## Overview

SillyTavern utilizes AI coding agents to assist with development tasks, code reviews, and maintaining code quality. These agents help streamline the development process while maintaining the project's standards.

## Configured Agents

### Gemini Code Review

The project uses Gemini for automated code review. Configuration can be found in `.gemini/config.yaml`.

**Features:**
- Automated code review on pull requests
- Comment severity filtering (HIGH threshold)
- Configurable review depth

**Configuration:**
- Code review is enabled by default
- Only HIGH severity comments are shown
- Pull request summaries are disabled by default

## Working with AI Agents

When contributing to SillyTavern, you may interact with AI agents in several ways:

1. **Automated Code Reviews**: Pull requests will automatically receive feedback from AI agents
2. **Code Suggestions**: Agents may suggest improvements or identify potential issues
3. **Best Practices**: Agents help enforce coding standards and project conventions

## Guidelines

- AI agent feedback is advisory, not mandatory
- Maintainers make final decisions on all code changes
- Agent suggestions should be evaluated in context
- See [CONTRIBUTING.md](CONTRIBUTING.md) for more information about code contribution guidelines

## Customization

Project maintainers can customize agent behavior through:
- `.gemini/config.yaml` for Gemini settings
- GitHub Actions workflows in `.github/workflows/`
- Repository settings for GitHub Copilot and other integrated tools

## Privacy and Data

AI agents operate within GitHub's infrastructure and follow the project's privacy guidelines. No sensitive data or secrets should be included in code that agents will review.

## Support

For questions or issues related to AI agents:
- Review the [CONTRIBUTING.md](CONTRIBUTING.md) guidelines
- Check the [documentation](https://docs.sillytavern.app/)
- Join our [Discord community](https://discord.gg/sillytavern)
- Open a GitHub issue if you encounter problems

## Further Reading

- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [Google Gemini Documentation](https://ai.google.dev/)
- [AI Coding Assistance Guidelines in CONTRIBUTING.md](CONTRIBUTING.md#use-of-ai-coding-assistance-tools-vibe-coding)
