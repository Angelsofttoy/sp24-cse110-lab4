### A Little More of A Challenge
1. The system will output the current index after finished iterating over the prices array. 

2. The system will output the discounted price at the last index of the array after the iteration is finished. 

3. The system will output the discounted price rounded to the nearest integer value at the last index of the array of the iteration over the array is finished. 

4. The function will return an array of discounted item prices based the given float parameter. 

5. This will instead cause an error because the codes are trying to access the let variable i outside of its declared block scope. 

6. Similarly as question 5, this will instead cause an error too because it's trying to access the discounted varaible declared by let outside of its initial block scope. 

7. Line 14 will be able to return an accessible discounted list because this line of code is positioned at the same block scope as its variable declaration line. 

8. The function will return the list with discounted item prices. 

9. This will instead cause an error because the codes are trying to access the let variable i outside of its declared block scope. 

10. Although being able to access the array discounted as the return line is located at the same block scope as its declaration line, 

11. The function will return an error as it's not plausible to access the variable that was declared as a constant type outside of its block scope. 

let student = {
    name: 'Sarah',
    major: 'Computer Science',
    'Grad Year': '2022',
    greeting: function() {console.log('Hello!');},
    'Favorite Teacher':{
        name: 'Thomas Powell',
        course: 'CSE 110'
    },
    courseLoad: ['CSE 110', 'CSE 134', 'VIS 134']
};

### Data Types
12. 
+ a) student.name;
+ b) student.['Grad Year'];
+ c) student.greeting();
+ d) student['Favorite Teacher'].name;
+ e) student.courseLoad[0];

### Basic Operations & Type Conversion

13.
 + a) '3' + 2 = '32' // The 2 in the latter place is converted to a stirng to concatenate with 3. 
    + b) '3' - 2 = 1 // The 3 is converted to a numerical 3 because substraction is performed on a numeric value. 
    +  c) 3 + null = 3 // null is equivalent to 0. 
    + d) '3' + null = '3null' // null is converted to 3 for addition
    + e) true + 3 = 4 //true is equivalent to 1 in case of addition
    + f) false + null = 0 //both evalutes to numerical value of 0
    + g) '3' + undefined = '3undefined' //undefined converted to string for addition
    + h)'3' - undefined = NaN //subtracting a non-numerical value from a numerical one makes the result not a number. 

14. 
+ a) '2' > 1 = true // JavaScript's Loose Type Comparision coverts 2 to 1 for the result
    + b) '2' < '12' = false // In this case, it performs a lexigraphical comparision, so "2" is greater than "12"
    + c) 2 == '2' = true // "2" is converted to its numerical type for comparison
    + d) 2 === '2' = false // the strict equal sign recongizes the type mismatch. 
    + e) true == 2 = false // true is equivalent to 1. 
    + f) true === Boolean(2) = true // Since both values are boolean, and any non zero number evaluates to true, so the end result is also true. 

15. The == operator is a loose equal sign, it does not consider/could convert type when comparing two varibales. The triple equal sign consider variable type and is more strict than the == operator. 

17. The function will add 2 to each of the original value of the array because of the do something function, so it will return [2, 4, 6] at the end. 

19. The result will be 1, 4, 3, 2. This is because the function will first execute 1 and 4, then 3 and 2 accordingly based on their time out length. 