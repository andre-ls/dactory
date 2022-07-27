# Business Rule Specification

## Rule Information

- Statement: Every Employee registered must have an Address, Phone Number, Email and Production Step registered.
- Constraint: The fields Phone Number, Email, Street Address, City, State, Zip Code and Production Step must not accept Null Values and a value must always be required.
- Type: Database Oriented
- Category: Field Specific
- Test On: Insert, Update

## Structures Affected

- Field Names: Phone Number, Email, Street Address, City, State, Zip Code, Production Step
- Table Names: Employees

## Field Elements Affected

- Null Support
- Required Value

## Actions Taken

For each respective Field's Specification:

    - The Null Support is set to "No Nulls"
    - The Required Value is set to "Yes"
