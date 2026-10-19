# Week 7 Lab – Dart Fundamentals
Name: Palinsad, Naomi Myriam Grace G.
Section: 3.7-BSIT


[- campus_brew_receipt.dart 
](https://github.com/424000532-png/dart-week7-lab/blob/5291f3858f78326aa25e560f242b578fb689456d/campus_brew_receipt.dart)- 

[print_shop.dart 
https://github.com/424000532-png/dart-week7-lab/blob/42b7c91344a04cce4e263a2cb7e7747c52728900/print_shop.dart]

 How to run
Copy a file's code into https://dartpad.dev and click Run.

Part 7 – Answers
a. Ana received the voucher because she is a student and her subtotal (PHP 296.75) is at least PHP 250.
b. Delivery was not free because Ana was not picking up and her amount after the voucher was PHP 281.25, below PHP 300.
c. We use ~/ because reward points count only complete PHP 50 amounts.
If isStudent is false: voucher = Not eligible; delivery = PHP 29.50; total = PHP 326.25; points = 6.

https://docs.google.com/document/d/10DITsfEVSaIJj45B1x5bp8h_ZZYV8Gg7lFfbwBuU6V0/edit?usp=sharing

Test 3 answer: Carla does not get the discount because her subtotal is PHP 83.25, below the PHP 100 minimum. 

## Reflection
1. The error that confused me the most was assigning a decimal value to an int. I fixed it by changing the variable type to double.

2. final is a better choice for values that should not change after being assigned, such as the student's name or item prices.

3. In a real Flutter app, the INPUT values would come from user input fields, buttons, dropdown menus, or other parts of the app's interface.

  
