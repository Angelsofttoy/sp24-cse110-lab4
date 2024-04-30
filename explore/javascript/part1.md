### var

1. At line9, the sum of num1 and num2 is printed when add is evaluated to be true: "values added : num1 + num2". This is because the var value in javascript could be reassigned.

2. Else, at line 13, it will print "final result: num1 + num2". 

### let

3. At line9, the sum of num1 and num2 is printed when add is evaluated to be true: "values added : num1 + num2". This is because the let declaration of value in javascript could be reassigned as long as it's in the same code block.

4. This line will return an error as the let is first declared as a block-local varaible. 


### const 

5. Line 9 will print the initial value of the variable, as it's declared as a constant type that could not be altered.

6. Line 13 in this case will return an error, since similarly as let declaration const could not be acessed outside of a block scope. 