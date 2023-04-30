# Graded-Assignment-on-Python-1

## Question 1 - Description
 - Create a small command-line program in Python to calculate the total invoice amount for the below purchases - 
Book - Introduction to Python Programming : Rs 499.00
Book - Python Libraries Cookbook : Rs. 855.00
Book - Data Science in Python : Rs. 645.00
Taxes and additional charges are described as details - GST : 12%
Delivery Charges : Rs. 250.00



### GST Calculation Formula:

> Add GST: `GST Amount = (Original Cost x GST%)/100Net Price = Original Cost + GST Amount` <br/>
Remove GST: `GST Amount = Original Cost - [Original Cost x {100/(100+GST%)}]Net Price = Original Cost - GST Amount` </br>

To calculate GST (Goods and Services Tax), you need to follow these steps:

Step 1: Determine the GST rate applicable for the goods or services you are selling or purchasing.

Step 2: Determine the transaction value of the goods or services on which GST is to be calculated.

Step 3: Calculate the GST amount by multiplying the transaction value with the applicable GST rate.

Step 4: Determine the gross amount payable by adding the GST amount to the transaction value.

> Solution
- Test case 1
<img width="359" alt="invoice" src="https://user-images.githubusercontent.com/93705673/235346160-6cc876c7-b9d7-4bf8-a98c-c3c72a3892f7.png"/>

- Test case 2
<img width="359" alt="invoice_error" src="https://user-images.githubusercontent.com/93705673/235346306-50af627e-6aeb-4eab-a258-a5ae6dd72e48.png"/>

## Question 2 - Description
- Write a program in Python to print the number of unique letters in a string. Only new letters from the string should be counted and not duplicates.
> Solution
- Test case 1
<img width="359" alt="uniq1" src="https://user-images.githubusercontent.com/93705673/235346889-3a5aac35-33bd-464d-be17-729c16c8e724.png"/>


- Test case 2
<img width="359" alt="uniq2" src="https://user-images.githubusercontent.com/93705673/235346892-2bc86e02-20b6-46d5-ab49-0a2e78ca6788.png"/>


