# Antigravity Starter Repo

An antigravity starter repo to start building anything with AI agent skills built-in.

## Overview

This repository provides a foundation for projects that work with AI coding agents. It includes a structured collection of skills that help agents work more effectively across common software development tasks.

## Features

- **📚 Skill Library**: Pre-built skills covering essential development practices
- **🔍 Skill Helper**: Easy-to-use guide for discovering and applying skills
- **🎯 Systematic Approach**: Structured methodologies for common tasks
- **📖 Best Practices**: Curated guidance from industry standards

## Getting Started

### For AI Agents

When working on tasks in this repository, consult the `.agent/SKILL_HELPER.md` file to:
1. Identify which skills are relevant to your current task
2. Follow the guidance in the appropriate skill documents
3. Apply best practices consistently

### For Developers

1. Clone this repository as a starting point for your project
2. Review the skills in `.agent/skills/` to understand available guidance
3. Customize or add skills specific to your project's needs
4. Use the skills as a reference when working or reviewing code

## Skill Library

The `.agent/skills/` directory contains skills for:

- **Code Review** - Performing thorough code reviews
- **Debugging** - Systematically identifying and fixing bugs
- **Testing** - Writing effective tests
- **Refactoring** - Improving code structure
- **API Design** - Creating clean, intuitive APIs
- **Problem Solving** - Approaching complex problems systematically
- **Documentation** - Creating clear documentation

See [`.agent/SKILL_HELPER.md`](.agent/SKILL_HELPER.md) for detailed guidance on using these skills.

## Structure

```
.
├── .agent/
│   ├── SKILL_HELPER.md          # Guide for using skills
│   └── skills/                   # Individual skill documents
│       ├── code-review.md
│       ├── debugging.md
│       ├── testing.md
│       ├── refactoring.md
│       ├── api-design.md
│       ├── problem-solving.md
│       └── documentation.md
└── README.md
```

## Adding Skills

To add new skills to your project:

1. Create a new file in `.agent/skills/` following the skill template
2. Update `.agent/SKILL_HELPER.md` to reference the new skill
3. Follow the structure outlined in the Skill Helper guide

See the [Skill Template section](.agent/SKILL_HELPER.md#skill-template) in the Skill Helper for the recommended format.

## Usage Examples

### Example 1: Code Review
When reviewing a pull request, reference `.agent/skills/code-review.md` to ensure you:
- Check code style and consistency
- Identify potential bugs or security issues
- Verify test coverage
- Provide constructive feedback

### Example 2: Debugging
When investigating a bug, follow `.agent/skills/debugging.md` to:
- Systematically reproduce the issue
- Isolate the problem
- Form and test hypotheses
- Apply and verify the fix

### Example 3: API Design
When creating a new API, consult `.agent/skills/api-design.md` for:
- Design principles and best practices
- REST API conventions
- Error handling patterns
- Documentation requirements

## Contributing

This is a starter template. Feel free to:
- Customize existing skills for your project
- Add project-specific skills
- Modify the structure to fit your needs
- Share improvements back to the community

## License

This starter repo is provided as-is for use in your projects. Customize it as needed for your specific requirements.
