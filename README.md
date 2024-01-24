# Calculator
Mark and prabhnoor built simple calculator that can be used like a real-life calculator. You can divide numbers, multiply, subtract, remainder, and addition. We added icons on the number button and exit button. You can also exit the document by pressing exit and pressing C to clear the text field. The numbers and operators all connect to the text field. There is also an equal button to show the total. 

To clear the text field we used Txtresult.setText(“”);   to clear the text
To exit the system you do System. exit(0);
For all the numbers we used almost the same code where you have to display the numbers in the field. 
If it the empty then it displays 7 when you press the button. If it is not empty then you display the number after the number before. When the text field already contains any operator you display the number after the operator or number. Store the number after the operator to value. Then you make the string to integer with value2 = integer.parseInt(value2 + “Any number”);

If the text field is empty you won’t display it on the text field if it is a operator.
If there is a number before then it will display. It will make the number before the operator becomes an integer from the string storing value1. then you store the type of operator you press into the variable operator. Then you do the same for all other operators.  

On variable operators, if it is plus then you add value1 + value2. If it is minus then you do value1-value2. If it is multiplication then you value1*value*. If it is division then you do value1/value2. If it is remainder then you do value1%value2.
