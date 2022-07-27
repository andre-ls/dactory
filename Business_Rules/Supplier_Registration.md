# Business Rule Specification

## Rule Information

- Statement: Every Supplier registered must have an Address, Phone Number and Email registered.
- Constraint: The fields Phone Number, Email, Street Address, City, State, Zip Code must not accept Null Values and a value must always be required.
- Type: Database Oriented
- Category: Field Specific
- Test On: Insert, Update

## Structures Affected

- Field Names: Phone Number, Email, Street Address, City, State, Zip Code
- Table Names: Supplier

## Field Elements Affected

- Null Support
- Required Value

## Actions Taken

For each respective Field's Specification:

    - The Null Support is set to "No Nulls"
    - The Required Value is set to "Yes"
