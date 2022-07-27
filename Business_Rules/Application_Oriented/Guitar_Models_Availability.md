# Business Rule Specification

## Rule Information

- Statement: A Guitar Model can only be ordered when sufficient Material to build it is available on the Inventory.
- Constraint: If at least one of the Guitar Model Materials, defined on the Model Material List, have a Quantity available at the Inventory Table less than the quantity needed, also defined on the Model Material List.
- Type: Application Oriented
- Category: Field Specific
- Test On: Insert 

## Structures Affected

- Field Names: Guitar Model, Quantity
- Table Names: Guitar Model, Models Material List, Inventory

