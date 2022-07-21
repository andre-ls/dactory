# Final Table List

## Orders
    - Type: Data
    - Description: All the orders being produced at the moment or that were crafted somewhere in the past. Keeping track of them is not only important for the production line management but also for future analytical needs of the production itself.

## Guitar Models
    - Type: Data
    - Description: All the Guitar Models crafted by the Factory at any point in time. Not only the table keep a centralized register of all important details of each model, but also, if combined with other tables, can allow specific calculations over the Inventory.

## Models Material List
    - Type: Subset
    - Description: All the material list and their specific quantities to craft a specific model at the Factory. This information is important to document and manage the amount of material being used to craft each model and help to keep the Inventory properly supplied to handle the production.

## Customers
    - Type: Data
    - Description: All contact and address information of all the Factory Customers, which are the ways of maintaining them informed about their orders and knowing where to deliver the fresh new guitars.

## Suppliers
    - Type: Data
    - Description: All relevant information of the Factory Suppliers to manage the raw materials supply at the beggining of the production line. 

## Materials
    - Type: Data
    - Description: A centralized reference of all materials used at any point in time to craft the guitars and their respective suppliers. This table is important to give support to both the Inventory Table and Models table, giving specific details about each material and piece being used. 

## Inventory
    - Type: Subset
    - Description: The quantity available for each material to keep track and manage the Factory Inventory.

## Employees
    - Type: Data
    - Description: Information about each Factory Employee, mainly contact information for any necessary contact, and information about their placement on production line for management purposes.

## Production Steps
    - Type: Data
    - Description: Cetralized reference of all the Steps of the Production Line applied at some point in time, which is useful for references by other tables, and for future analytical usage of the production line. 


