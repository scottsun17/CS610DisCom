# Game Testing
Since the game is a text-based game, the majority tests are input validations. I tested around balance, inventory, market product id, and business operation options to ensure that invalid/incorrect input will not crash/stop the game. In case of invalid input, the game will re-prompt for re-input. The game explains the type of input it will accept. 
<br /><br />

## Balance Testing 
There can be a situation that the player wants to purchase more products than the player can afford. This tests the balance to make sure that the player has sufficient balance to make a purchase. <br />
![alt text](https://raw.githubusercontent.com/scottsun17/CS610DisCom/master/GameTestingScreenShots/1_out_of_balance.PNG)
<br /><br />

## Inventory Testing
In case player wants to sell more inventory than the player owns. This test is to make sure that player has sufficient products in the inventory to make a sell.<br />
![alt text](https://raw.githubusercontent.com/scottsun17/CS610DisCom/master/GameTestingScreenShots/2_out_of_inventory.PNG)
<br /><br />
![alt text](https://raw.githubusercontent.com/scottsun17/CS610DisCom/master/GameTestingScreenShots/9_not_enough_quantity_input.PNG)
<br /><br />

## Invalid Inventory Testing
This test is to ensure the game will not crash if the player input incorrect inventory id. If the player input invalid id, the game will re-prompt for re-input.<br />
![alt text](https://raw.githubusercontent.com/scottsun17/CS610DisCom/master/GameTestingScreenShots/7_invalid_inventory_input.PNG)
<br /><br />
![alt text](https://raw.githubusercontent.com/scottsun17/CS610DisCom/master/GameTestingScreenShots/8_invalid_inventory_quantity_input.PNG)
<br /><br />

## Product ID Validation 1 & 2
This test is to make sure that invalid product id input will not crash the game. In case player makes an incorrect input on product id, the game will prompt again for re-input.<br />
![alt text](https://raw.githubusercontent.com/scottsun17/CS610DisCom/master/GameTestingScreenShots/3_invalid_input_product_id_1.PNG)
<br /><br />
![alt text](https://raw.githubusercontent.com/scottsun17/CS610DisCom/master/GameTestingScreenShots/4_invalid_input_product_id_2.PNG)
<br /><br />

## Invalid Quantity Testing
This tes is to make sure that incorrect quantity input will not crash the game. In case player makes an invalid input, the game will prompt the input again for re-input.<br />
![alt text](https://raw.githubusercontent.com/scottsun17/CS610DisCom/master/GameTestingScreenShots/5_invalid_quntity_input.PNG)
<br /><br />

## Business Operation Testing
Player is prompted to input business operation for each week. This test is to ensure that invalid input will not crash the game. If the player input invalid input, the game will re-prompt the question again for business operation.<br />
![alt text](https://raw.githubusercontent.com/scottsun17/CS610DisCom/master/GameTestingScreenShots/6_invalid_operation_input.PNG)
<br /><br />





























