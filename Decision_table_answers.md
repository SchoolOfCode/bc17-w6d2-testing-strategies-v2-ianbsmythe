# Decision Table for Shopping Cart Functionality

## Conditions: 

1) Product Type: The product can be either physical or digital.
2) Quantity: The quantity of the product can be 1 or 2.
3) Discount Code: The discount code can be either valid or invalid.

## Actions based in conditions:

1) Calculate Subtotal: Always calculated.
2) Apply Discount: Applied only if the discount code is valid.
3) Calculate Tax: Calculated only for physical products.
4) Calculate Shipping: Calculated only for physical products.
5) Calculate Total: Always calculated.
6) Update Inventory: Updated only for physical products.
7) Generate Invoice: Always generated.

## Task 1: Identify the Conditions and Actions 

Conditions: 
1) Product Type (physical or Digital)
2) Quantity: 1 or 2
3) Discount Code: valid or invalid

Actions: 
1) Calculate subtotal
2) Apply discount
3) Calculate tax
4) Calculate shipping
5) Calculate total
6) Update inventory
7) Generate Invoice

## Task 2: 

| Conditions & Actions |
|----------------------|
| Product Type         | 
| Quantity             |
| Discount Code        |
| Calculate Subtotal   |
| Apply Discount       |
| Calculate Tax        |
| Calculate Shipping   |
| Calculate Total      |
| Update Inventory     |
| Generate Invoice     |  

## Task 3: 

| Conditions         | Test Case 1 | Test Case 2 | Test Case 3 | Test Case 4 | Test Case 5 | Test Case 6 | Test Case 7 | Test Case 8 |
|--------------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
| Product Type       | Digital     | Digital     | Digital     | Digital     | Physical    | Physical    | Physical    | Physical    |
| Quantity           | 1           | 2           | 1           | 2           | 1           | 2           | 1           | 2           |
| Discount Code      | valid       | valid       | invalid     | invalid     | valid       | valid       | invalid     | invalid     |
| Calculate Subtotal | Y           | Y           | Y           | Y           | Y           | Y           | Y           | Y           |
| Apply Discount     | Y           | Y           | X           | X           | Y           | Y           | X           | X           |
| Calculate Tax      | X           | X           | X           | X           | Y           | Y           | Y           | Y           |
| Calculate Shipping | X           | X           | X           | X           | Y           | Y           | Y           | Y           |
| Calculate Total    | Y           | Y           | Y           | Y           | Y           | Y           | Y           | Y           |
| Update Inventory   | X           | X           | X           | X           | Y           | Y           | Y           | Y           |
| Generate Invoice   | Y           | Y           | Y           | Y           | Y           | Y           | Y           | Y           |          