# Business Rules

This directory contains Business Rules Specification Sheets that could be already defined on the Database Design Process. They are grouped in two main types:
    - *Database-Oriented* Business Rules, which can be established within the Logical Design of the Database.
    - *Application-Oriented* Business Rules which cannot be establish within the logical design of the Database, and should be instead established with the Application that will use the Database.

For each specification, the following fields may be defined:

 - Statement: The text of the business rule itself.
 - Constraint: Brief explanation of how the constraint applies to the Tables and Fields of the database.
 - Type: Indication of whether the rule is Database Oriented or Application Oriented.
 - Category: Category of the Rule, being either Field Specific, Relationship Specific or both.
 - Test On: Indication of which actions (Insert, Update or Delete) will test the constraint the Business Rule imposes.
 - Structures Affected: Indicates the Fields and Table Names affected by the Business Rule.
 - Field Elements Affected: Indicates which Field Specification characteristics may be affected by the Business Rule.
 - Actions Taken: Modifications made on the Database Project to implement the Rule, in case of a Database Oriented Business Rule.
