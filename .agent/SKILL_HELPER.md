# Skill Helper Guide

## Overview
This directory contains a collection of skills to help you work more effectively. Each skill provides guidance on specific aspects of software development.

## Available Skills

### Core Development Skills
1. **[Code Review](skills/code-review.md)** - Perform thorough code reviews
2. **[Debugging](skills/debugging.md)** - Systematically identify and fix bugs
3. **[Testing](skills/testing.md)** - Write effective tests
4. **[Refactoring](skills/refactoring.md)** - Improve code structure and maintainability

### Design & Planning Skills
5. **[API Design](skills/api-design.md)** - Create clean, intuitive APIs
6. **[Problem Solving](skills/problem-solving.md)** - Approach complex problems systematically

### Communication Skills
7. **[Documentation](skills/documentation.md)** - Create clear, comprehensive documentation

## How to Use Skills

### 1. Identify the Relevant Skill
When facing a task, determine which skill(s) apply:
- Need to review code? → Use **Code Review** skill
- Fixing a bug? → Use **Debugging** skill
- Designing a new API? → Use **API Design** skill
- Code is messy? → Use **Refactoring** skill
- Writing tests? → Use **Testing** skill
- Creating docs? → Use **Documentation** skill
- Stuck on a problem? → Use **Problem Solving** skill

### 2. Read the Skill Guide
Open the relevant skill file and review:
- **When to Use**: Confirms this skill matches your situation
- **How to Use**: Step-by-step guidance
- **Best Practices**: Important tips and considerations

### 3. Apply the Skill
Follow the guidance in the skill document:
- Use the suggested methodology
- Consider the best practices
- Avoid common pitfalls
- Adapt to your specific context

### 4. Combine Skills
Many tasks require multiple skills:
- **Debugging + Testing**: Write a test that reproduces the bug, then fix it
- **Refactoring + Testing**: Ensure tests exist before refactoring
- **API Design + Documentation**: Document the API as you design it
- **Problem Solving + Code Review**: Use structured thinking to evaluate solutions

## Quick Reference

### Before Writing Code
- [ ] Use **Problem Solving** to understand the requirements
- [ ] Use **API Design** if creating interfaces
- [ ] Use **Testing** to plan test cases

### While Writing Code
- [ ] Keep **Refactoring** principles in mind
- [ ] Apply **Testing** to validate behavior
- [ ] Use **Debugging** when things don't work

### After Writing Code
- [ ] Use **Code Review** to assess quality
- [ ] Use **Testing** to ensure coverage
- [ ] Use **Documentation** to explain your work

### When Issues Arise
- [ ] Use **Debugging** to identify root causes
- [ ] Use **Problem Solving** for complex issues
- [ ] Use **Testing** to prevent regressions

## Tips for Effective Skill Usage

1. **Be Proactive**: Apply skills before problems arise
2. **Be Systematic**: Follow the structured approaches in each skill
3. **Be Reflective**: Consider which skills would improve your work
4. **Be Consistent**: Use skills regularly to build good habits
5. **Be Adaptive**: Adjust skill application to fit the context

## Adding New Skills

To add a new skill to this collection:

1. Create a new file in the `skills/` directory
2. Follow the standard skill template:
   ```markdown
   # [Skill Name]
   
   ## Description
   Brief overview of what this skill helps you do
   
   ## When to Use
   Situations where this skill is applicable
   
   ## How to Use
   Step-by-step guidance
   
   ## Best Practices
   Important tips and considerations
   ```
3. Update this guide to include the new skill in the appropriate category
4. Add a quick reference entry if applicable

## Skill Template

Use this template when creating new skills:

```markdown
# [Skill Name]

## Description
[What this skill helps you accomplish]

## When to Use
- [Situation 1]
- [Situation 2]
- [Situation 3]

## How to Use
1. [Step 1]
2. [Step 2]
3. [Step 3]

## [Optional Section: Strategies/Patterns/Types]
- [Item 1]
- [Item 2]

## Best Practices
- [Best practice 1]
- [Best practice 2]
- [Best practice 3]

## [Optional Section: Common Pitfalls/Mistakes to Avoid]
- [Pitfall 1]
- [Pitfall 2]
```

## Contributing

When you discover effective techniques or patterns:
1. Consider if they belong in an existing skill (update it) or require a new skill (create it)
2. Keep skills focused and actionable
3. Include specific, practical guidance
4. Provide examples where helpful
5. Update this helper guide to reference new or updated skills

## Feedback

If you find these skills helpful or have suggestions for improvements:
- Open an issue describing the enhancement
- Propose new skills that would be valuable
- Share examples of how skills helped in specific situations
- Suggest clarifications or additional best practices
