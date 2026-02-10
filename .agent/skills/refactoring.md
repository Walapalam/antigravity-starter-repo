# Refactoring Skill

## Description
This skill helps you improve code structure and readability without changing its external behavior, making the codebase more maintainable.

## When to Use
- When code is difficult to understand or maintain
- Before adding new features to complex code
- When you notice code duplication
- When code violates design principles
- During code reviews when you spot improvement opportunities

## How to Use
1. **Ensure tests exist**: Make sure there are tests before refactoring
2. **Identify the smell**: Recognize what makes the code problematic
3. **Plan small steps**: Break the refactoring into incremental changes
4. **Refactor incrementally**: Make one small change at a time
5. **Run tests frequently**: Verify behavior hasn't changed after each step
6. **Commit regularly**: Save progress with clear commit messages

## Common Refactoring Patterns
- **Extract Method**: Break long functions into smaller, focused ones
- **Rename**: Give variables, functions, and classes clearer names
- **Remove Duplication**: Consolidate repeated code
- **Simplify Conditionals**: Make complex logic easier to understand
- **Extract Constants**: Replace magic numbers with named constants
- **Improve Data Structures**: Use more appropriate data structures

## Best Practices
- Never refactor and add features simultaneously
- Keep changes small and focused
- Maintain or improve test coverage
- Consider performance implications
- Update documentation alongside code changes
- Get feedback through code review
