# Field Specifications

## General Elements

- Field Name: Guitar Color
- Parent Table: Orders
- Shared By: Guitar Colors
- Description: Color of the Body of the Guitar being produced. It contains the ID of the respective color on the Guitar Colors Table, where further details may be found. It should be defined at the ordering, and once the production started, it cannot be changed.

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
- Range of Values: Any Color ID of the Guitar Colors Table.
- Edit Rule: Enter Now, Edits Not Allowed
