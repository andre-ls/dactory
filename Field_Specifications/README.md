# Field Specifications

This directory contains Field Specifications Documentations for each column of the Database Project. On each file, it's possible to find the elements below:

## General Elements

- Field Name: Set of absolute minimal words that uniquely identifies a particular field throughout the database.
- Parent Table: Table that incorporates the specified field. The Parent Table is unique for each field, unless the field is used for relations between tables.
- Shared By: Indicates the names of other tables that share this field, in case of an explicit relationship with other tables.
- Description: Complete interpretation of the field, which involves  the identification of the field and why it exists.

## Physical Elements

- Data Type: Indicates the nature of the data that the field stores. Here, three generic types are used: Alphanumeric, Numeric and Date Type.
- Length: Specifies the total number of characters that can be entered for the given field.
- Decimal Places: Denotes the number of digits to the right of the decimal point in a real number allowed.
- Character Support: Indicates the type of characters that a user can enter into a given field value, which can be one or more of four types: 
    - Letters(A-Z) 
    - Numbers(0-9) 
    - Keyboard(. , / $ # % ...)
    - Special (® Σ π ...).

## Logical Elements

- Key Type: Designates a field's role within a table, being either a Primary Key, Foreign Key or Non-Key.
- Key Structure: Denotes whether a field designated as a Primary Key is acting as a Simple Primary Key or a Composite Primary Key.
- Uniqueness: Indicates whether a field's values are unique.
- Null Support: Specifies whether a field accepts Null.
- Values Entered: indicates the source of a field's value, being either the manually inserted by the User or automatically defined by the System.
- Required Value: Denotes whether a user is required to enter a value for a field.
- Range of Values: Specifies every possible valid value for a field, in case any restriction exists.
- Edit Rule: Designates at what point a user can enter a value into a field and whether he can modify that value.  Four categories are possible here:
    - Enter Now, Edits Allowed
    - Enter Later, Edits Allowed
    - Enter Now, Edits Not Allowed
    - Enter Later, Edits Not Allowed
