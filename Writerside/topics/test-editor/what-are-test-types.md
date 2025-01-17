# Test Types
A test type is a UI driven way of generating test code based on specific best-practice algorithms.

For example, a unit test using the [Equivalence Class Partitioning](equivalence-classes.md) test type might look like this. Don't worry too much about understanding this fully. We explain in detail later.

[TODO - proper image]

<img src="test-type-explanation.png" alt="test type explanation" width="550"/>

1. Handles the instantiation of the class ```CreditCheck``` by creating single valid Equivalence Class with three different representative values.
2. Test the method ```checkCredit``` by defining input values and then possible expected values, custom assertions, exceptions and side effects.
3. An auto-generated test case table that can be completed by you to determine the correct expected value for each generated input.

## Current and future test types

During Beta, we offer one of the most powerful test types, [Equivalence Class Partitioning](equivalence-classes.md).

We will then start adding many more test types, such as 

- [API Testing](api-testing.md)
- [Decision Flow Table](decision-flow-table.md)
- [Decision Flow Diagram](decision-flow-diagram.md)
- Decision table testing
- State transition testing
- Cause–effect graph
- Error guessing
- State transition testing
- Use case testing
- User story testing
- Business process testing
- Acceptance based testing
- Behavior driven testing

