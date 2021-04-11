# Scratch Fisherman Code
Given the scenario below answer the following

 A man walks  into a fish market and asks the fisherman of the cost of one kilo of a specific type.
- a.	The fisherman replies the price of one Kilo is 1.5 OMR 
- b.	 If you buy more than 10 kilos you would get 2 Rials discount on the bill otherwise you get 0.500 Rials on the bill.
- c.	The man replies, “I would like to buy 8 kilos please, how much would that cost me?”

 Write a scratch code to read the number of kilos and calculate:
a.	The old bill before discount is  calculated  as number of kilos multiplied by Price of one kilo.
b.	The discount percentage is calculated based on  the number of units bought.
c.	The new bill  is calculated by subtracting the discount from the old bill.

The system should display all the data.

The pseudocode for the following code is given below:

-	Start
-	Set old_bill = 0, new_bill=0, discount=0
-	Read price_of_1_kilo
-	Read num_of_kilos
-	Set old_bill = price_of_1_kilo * num_of_kilos
-	If num_of_kilos >=10
-	Discount = 2
-	Else
- Discount = 0.5

-	Set new bill =old_bill – discount
-	Display “the new bill is” + new_bill
-	Display “the old bill was” + old_bill
-	Display “the discount is” + discount
-	End.
