# Field Specifications

## General Elements

- Field Name: Current Step
- Parent Table: Orders
- Shared By: Production Steps
- Description: Current Production Step of the Order, which could be used both for management purposes and to inform the customers about the status of the orders. It contains the respective Step ID from the Production Steps Table.

## Physical Elements

- Data Type: Numeric
- Length: 
- Decimal Places:
- Character Support: Numbers

## Logical Elements

- Key Type: Foreign
- Key Structure: Simple
- Uniqueness: Non-Unique
- Null Support: No Nulls
- Values Entered By: User
- Required Value: Yes
- Range of Values: Any Step ID of the Production Steps Table.
- Edit Rule: Enter Now, Edits Allowed
