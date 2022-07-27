# Business Rule Specification

## Rule Information

- Statement: The Order's Features must be defined before the start of the crafting process, and cannot be changed after that.
- Constraint: The application must accept an Order Registration only one time, and after it reaches an specific Production Step, it should not allow any updates on the order.
- Type: Application Oriented
- Category: Field Specific
- Test On: Insert, Update

## Structures Affected

- Field Names: Guitar Model, Guitar Color, Shield Color, Customer
- Table Names: Orders



