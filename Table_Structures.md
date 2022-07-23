# Table Structures

- Orders
    - Order Serial Number (Primary Key)
    - Guitar Model
    - Guitar Color
    - Shield Color
    - Customer
    - Current Step

- Guitar Models
    - Model ID (Primary Key)
    - Name 
    - Type
    - Body Wood
    - Neck Wood
    - Fingerboard Wood
    - Number of Strings
    - Status

- Guitar Colors
    - Color ID (Primary Key)
    - Name
    - Description

- Shield Colors
    - Shield Color ID (Primary Key)
    - Name
    - Description

- Models Material List
    - Model ID (Composite Primary Key)
    - Material ID (Composite Primary Key)
    - Quantity

- Customers
    - Customer ID (Primary Key)
    - Name
    - Phone Number
    - Email
    - Street Address
    - City
    - State 
    - Zip Code

- Suppliers
    - Supplier ID (Primary Key)
    - Name
    - Street Address
    - City
    - State 
    - Zip Code
    - Phone Number
    - Email
    - Status

- Materials
    - Material ID (Primary Key)
    - Name
    - Description
    - Manufacturer
    - Supplier
    - Statu

- Inventory
    - Material ID (Primary Key)
    - Quantity
    
- Employees
    - Employee ID (Primary Key)
    - Name
    - Phone Number
    - Street Address
    - City
    - State 
    - Zip Code
    - Email
    - Sector
    - Status
    
- Production Steps
    - Step ID (Primary Key)
    - Name
    - Description
    - Order Number
    - Status

