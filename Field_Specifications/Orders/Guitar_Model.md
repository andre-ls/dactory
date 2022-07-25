# Field Specifications

## General Elements

- Field Name: Guitar Model
- Parent Table: Orders
- Shared By: Guitar Models
- Description: Guitar Model being selected for the order. It contains the ID of the Model according to the Guitar Models table, where further details of it can be found. It should be defined at the ordering, and once the production started, it cannot be changed.

## Physical Elements

- Data Type: Numeric
- Length: 
- Decimal Places: 
- Character Support: Numbers

## Logical Elements

- Key Type: Foreign
- Key Structure: Sinple
- Uniqueness: Non-Unique
- Null Support: No Nulls
- Values Entered By: User
- Required Value: Yes
- Range of Values: Any of the Model ID's present at the Guitar Models table.
- Edit Rule: Enter Now, Edits Not Allowed
