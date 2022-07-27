# Business Rule Specification

## Rule Information

- Statement: Every order must have the Guitar Model, Guitar Color, Shield Color and Customer defined. 
- Constraint: The Guitar Model, Guitar Color, Shield Color and Customer from the Orders table should not accept NulL Values or Values inexisting on the Guitar Models Table, Guitar Colors Table and Shield Colors Table, respectively.
- Type: Database Oriented
- Category: Field Specific, Relationship Specific
- Test On: Insert

## Structures Affected

- Field Names: Guitar Model, Guitar Color, Shield Color
- Table Names: Orders, Guitar Models, Guitar Colors, Shield Colors, Customers

## Field Elements Affected

- Null Support
- Required Value
- Range of Value

## Relationship Characteristics Affected

- Type of Participation
- Degree of Participation

## Actions Taken

For each respective Field's Specification:

    - The Null Support is set to "No Nulls"
    - The Required Value is set to "Yes"
    - Range of Values is defined to the ID's of the according Reference Table

For the respective Relationships, some Relationship Characteristics should be defined:

    - Type of Participation should be Mandatory for the Guitar Models, Guitar Colors,Shield Colors and Customers, which means that a record must exist first in these tables before it can be referenced on the Orders Table.
    - The Degree of Participation must be set up in a way that the number of Orders related to a Specification(Model, Guitar Color or Shield Color) and Customer is unbounded, but exaclty one Specification and Customer must be defined for each Order. 
