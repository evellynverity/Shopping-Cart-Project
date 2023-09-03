# Shopping-Cart-Project
This project was made as final project for PacMann Pro Introduction to Python. 

**Part 1: Problem Statement**

This project was aimed to utilize object oriented programming as a way to create a functional shopping cart. 

**Part 2: Purpose**

1. Practicing clean code in accordance with PEP 8
2. Practicing Object Oriented Programming
3. Creating simple shopping cart program in which users are able to:
   - Add new item, item quantity and item information
   - Detect when an input contains error
   - Update item name, quantity, and/or price
   - Delete specific item or all item from their shopping cart
   - Get calculation total price
   - Check their order

**Part 3: Program Description**

**1. Create Transaction Class**

   The shopping cart class will be named Transaction. This Class will have 2 attributes and 8 method. The attributes includes:
   - **self.contents**: a dictionary that contains all item names, item quantities, and item prices inputed by user
   - **self.nama**: a list that contain all item names from self.contents. This attributes will be used in several class method.

**2. add_item() method**

User can add item by calling add_item function. This item will append user input into self.contents attribute.
   
<img width="155" alt="image" src="https://github.com/evellynverity/Shopping-Cart-Project/assets/139136838/b422d07a-262d-483c-b952-73b85234082d">

**3. update_item_name() method**

User can update item name in the cart. This method requires two input: old name and new name. 

<img width="373" alt="image" src="https://github.com/evellynverity/Shopping-Cart-Project/assets/139136838/5274310b-b601-4393-a97a-de2e54c2a767">

**3. update_item_qty() method**

User can update item quantity in the cart. This method requires two input: item name and new quantity. 

<img width="590" alt="image" src="https://github.com/evellynverity/Shopping-Cart-Project/assets/139136838/27d12729-6181-46bc-a892-94fb54654542">

**4. update_item_price() method**

User can update item quantity in the cart. This method requires two input: item name and new quantity.   

<img width="368" alt="image" src="https://github.com/evellynverity/Shopping-Cart-Project/assets/139136838/e09fc619-4363-4112-b65c-de0263379ac4">

**5. clear_transaction() method**

User can delete all items in the cart.

<img width="589" alt="image" src="https://github.com/evellynverity/Shopping-Cart-Project/assets/139136838/79a1e0af-9a73-4415-b44c-470a37ebab28">

**6. delete_item() method**

User can delete certain item in cart by inputting item name.

<img width="377" alt="image" src="https://github.com/evellynverity/Shopping-Cart-Project/assets/139136838/677b0c90-0985-4b37-b1ec-e8f35475b089">


**7. total_price method**

Calculating total item_quantity*item_price for all item in the cart.

<img width="351" alt="image" src="https://github.com/evellynverity/Shopping-Cart-Project/assets/139136838/99158984-ae89-4d09-8ad7-48bb0f185765">


  
   
