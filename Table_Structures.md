# Table Structures

- Orders
    - Order Serial Number (Primary Key)
    - Product Model
    - Code
    - Color
    - Shield Color
    - Customer
    - Current Step

- Guitar Models
    - Model ID (Primary Key)
    - Name 
    - Type
    - Body Wood
    - Neck Wood
    - Number of Strings
    - Status

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
