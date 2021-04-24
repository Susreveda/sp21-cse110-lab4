## Part 1a

### Var Declaration

1. values added: 20
   >The value of add is true, so we will run the if conditional. We then add the values of num1 and num2 and store it in result. The value of result is now 20, and in line 9, we return the value of result.
2. final result: 20
   >The value of result is still 20 after the if conditional. Therefore, line 13 will also return 20.

### Let Declaration

1. values added: 20
   >The value of add is true, so it will run the if conditional and add the values of num1 and num2. The result is stored in the variable "result", which is returned in line 9.
2. This code would return an error. 
   >The code would return an error because the variable "result" was declared with the let keyword. This means that the variable is only accessible in the block. Since line 13 is outside the block, it wouldnt be able to access result.

### Const Declaration

1. This code would return an error.
   >Since the variable result was made a const, we can't reassign the variable. In line 7, we try to reassign the value of result, so the code would return an error.
2. This code would return an error.
   >In addition to the error mentioned above, line 13 would also have an error as const has the same scope as let. Therefore, this line wouldn't have access to it.


## Part 1b

1. 3
   >The variable i starts at 0 and increments until the statement "i < prices.length" is false. The first time this would happen when i is 3. 
2. 150
   >The for loop would run and the final value of discountedPrice would be at the last iteration of the for loop. Therefore, it would be the last element of the prices list, which is 300. We then multiply by 0.5 .
3. 150
   >In the same manner as 2. , the final value of finalPrice would be at the last iteration of the for loop. Therefore, it would be the last value of discountedPrice, which is 150. We then multiply by 100, round, and then divide by 100. The result is 150.
4. [50, 100, 150]
   >The variable discounted is the array of the intial prices array with discounted prices. We can run the operations on each value of the prices arrray and add them to the discounted array. 
5. This code would return an error. 
   > This is because i is declared with a let. Since the variable declaration was inside the for loop, we can't access it outside in line 12.
6. This code would return an error.
   > This is because discountedPrice is declared with the let keyword. It was also declared inside the for loop, so we would not be able to access it in line 13.
7. 150
   > The let keyword wouldn't affect the variable in this case because it was declared at the start of the function. Therefore, the entire function has access to it. It would be the same as number 3.
8. [20, 100, 150]
   > In the same manner as the answer above, discounted is declared at the start of the function so the entire function has access to it. Therefore it would be the same as question 4.
9. This code would return an error.
    > The variable is declared with the let keyword. Line 11 wouldn't have access to the variable and would return an error.
10. 3
    >The variable was intialized to the value of 3. We don't change the value of length, so it doesn't throw an error. It was also declared atthe start of the function, so we line 12 has access.
11. [50, 100, 150]
    > Since we are only pushing to the array, we don't have any problems with the const keyword. We can just proceed as usual and get the same array as before.
12. (Data Types)
    1. student.name
    2. student["grad year"]
    3. student.greeting()
    4. student["Favorite Teacher"].name
    5. student.courseLoad[0]
13. (Basic Operators & Type Conversion - Arithmetic)
    1. '32'
    > Since we are adding to a string, the result will also be a string. The integer maps to its string representation so we get '32'.
    2. 1
    > Since we can't add to a string, we use the number 3 instead of the string '3'. The result is just 3 - 2.
    3. 3
    > The value of null is set to 0, so when we add, it would just be 3.
    4. '3null'
    > Once again, we use the addition as a concatenation and get '3null'.
    5. 4
    > Since the value of true is equal to 1, we can just add 1 to 3.
    6. 0
    > The value of false is equal to 0. The value of null is also equal to 0. When we add the two, we would just get 0.
    7. '3undefined'
    > Once again, the addition symbol is interpreted as a concatenation and we just combine the two.
    8. NaN
    > Since we can't subtract from a string, we would want to convert them to numbers. However, the value of undefined is NaN, so we get Nan.
14. (Basic Operators & Type Conversion - Comparison)
    1. true
    > Since we are comparing a string and a number, we convert the string into a number and carry on with the comparison.
    2. false
    > When comparing two strings, we compare letter-by-letter. Since '2' is larger than '1', we would return false.
    3. true
    > Since the types are different, we convert the types to numbers. 2 is the same as 2 so we return true.
    4. false
    > Since the === is a strict equality, we return false since they are of different types.
    5. false
    > Since they are of different types, we convert them to number values. The value of true is 1, so it would not be equal to 2.
    6. true
    > The Boolean function will return true when we pass in a number that is not 0. Therefore, we are essentially doing true === true. This is true.
15. The difference between the two operators is that the === is a strict comparison. In other words, they must be of the same type and value in order to evaluate to true. The == doesn't really take the types into consideration. 
16. (in part1b-question16.js)
17. [2, 4, 6]
    > Once we pass in the array, we iterate through it and use it as a parameter for a different function. This function takes in the value that is at that position in the array and multiplies it by 2. The function returns this number and we push it to the new array. We do this for every element in the array, so we just multiplied each element in the original array by 2.
18. (in part1b-question18.js)
19. 1 4 3 2
    > Since 1 and 4 do not have any delays, they are printed immediately. 3 has a delay of 0, so it shows up preety much at the same time. 2 shows up last since it has a delay of 1000.