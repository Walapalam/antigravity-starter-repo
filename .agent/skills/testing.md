# Testing Skill

## Description
This skill helps you write effective tests that verify code correctness, prevent regressions, and serve as documentation.

## When to Use
- When implementing new features
- When fixing bugs (write a failing test first)
- When refactoring existing code
- When improving test coverage
- When validating edge cases

## How to Use
1. **Understand the requirements**: Know what behavior you're testing
2. **Choose the test type**: Unit, integration, or end-to-end
3. **Follow AAA pattern**:
   - **Arrange**: Set up test data and conditions
   - **Act**: Execute the code being tested
   - **Assert**: Verify the expected outcome
4. **Test edge cases**: Consider boundary conditions, errors, and unusual inputs
5. **Keep tests independent**: Each test should run in isolation
6. **Make tests readable**: Clear naming and straightforward logic

## Test Types
- **Unit Tests**: Test individual functions or methods in isolation
- **Integration Tests**: Test how components work together
- **End-to-End Tests**: Test complete user workflows
- **Regression Tests**: Prevent previously fixed bugs from reappearing

## Best Practices
- Write tests before or alongside code (TDD)
- Each test should verify one specific behavior
- Use descriptive test names that explain what's being tested
- Avoid test interdependencies
- Keep tests fast and deterministic
- Aim for high coverage of critical paths
- Don't test implementation details, test behavior
- Use appropriate assertions and matchers
- Clean up test data and resources

## Test Organization
- Group related tests together
- Use setup/teardown hooks appropriately
- Share common test utilities and fixtures
- Keep test code as clean as production code
