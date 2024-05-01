1. At line 12, the program prints 3. This is because 'i' is declared using 'var', which means its scope lies throughout the entire function and the value of 'i' is 3 when the for loop ends, since there are only 3 elements in the parameter 'prices'.
2. At line 13, the program prints 150. This is because 'discountedPrice' is declared using 'var', which means its scope lies throughout the entire function and the value of 'discountedPrice' is 150 when the for loop ends, since the last element in the parameter 'prices' is 300 and 'discountedPrice' is assigned 150 after the calculation.
3. At line 14, the program prints 150. This is because 'finalPrice' is declared using 'var', which means its scope lies throughout the entire function and the value of 'finalPrice' is 150 when the for loop ends, since the last element in the parameter 'prices' is 300 and 'finalPrice' is assigned 150 after the rounding calculation. 
4. This function returns a list or array of the discounted prices. The function does not print anything, because there is no line with 'console.log()'. The function returns the variable 'discounted', which is an array, and the discounted prices generated from the parameter 'prices', are pushed into the array.
5. At line 12, there is an error. The error is a ReferenceError, and this is occurring because the variable being printed is declared using 'let', which means the scope of the variable 'i' ends with the for loop. Thus the variable is undeclared in line 12. 
6. At line 13, there is an error. The error is a ReferenceError, and this is occurring because the variable being printed is declared using 'let', which means the scope of the variable 'discountedPrice' ends with the for loop. Thus the variable is undeclared in line 13. 
7. At line 14, the program prints 150. This is because 'finalPrice' is declared using 'let', which means its scope lies throughout the entire function, since the code block it was declared in is the entire function and the value of 'finalPrice' is 150 when the for loop ends, since the last element in the parameter 'prices' is 300 and 'finalPrice' is assigned 150 after the rounding calculation. 
8. This function returns a list or array of the discounted prices. The function does not print anything, because there is no line with 'console.log()'. The function returns the variable 'discounted', which is an array, and the discounted prices generated from the parameter 'prices', are pushed into the array. 
9. At line 11, there is an error. The error is a ReferenceError, and this is occurring because the variable being printed is declared using 'let', which means the scope of the variable 'i' ends with the for loop. Thus the variable is undeclared in line 11. 
10. At line 12, the program prints 3. This is because 'length' is declared using 'const', which means its scope lies throughout the entire function, since the block is was declared in is the entire function, and the value of 'length' is 3, since there are only 3 elements in the parameter 'prices'.
11. This function returns a list or array of the discounted prices. The function does not print anything, because there is no line with 'console.log()'. The function returns the variable 'discounted', which is an array, and the discounted prices generated from the parameter 'prices', are pushed into the array. The 'discounted' variable is declared with const, but the elements inside the array can still be changed or elements can be added.
12. A. `student.name`
    
    B. `student["Grad Year"]`

    C. `student.greeting()`

    D. `student["Favorite Teacher"].name`

    E. `student.courseLoad[0]`

13. A. Output: `'32'`. This is because the int 2 gets mapped to '2'.
    
    B. Output: `1`. This is because the string '3' gets mapped to the int 3.

    C. Output: `3`. This is because null gets mapped to 0.

    D. Output: `'3null'`. This is because null gets mapped to the string 'null'.

    E. Output: `4`. This is because the boolean value true gets mapped to the int 1.

    F. Output: `0`. This is because false maps to the int 0 and null maps to the int 0 as well.

    G. Output: `'3undefined'`. This is because undefined maps to the string 'undefined'.

    H. Output: `NaN`. This is because the undefined cannot mapped to any int.

14. A. Output: `true`. This is because the string '2' maps to the int 2.

    B. Output: `false`. This is because alphabetically, the string '12' is less than '2'.

    C. Output: `true`. This is because the string '2' gets mapped to the int 2.

    D. Output: `false`. This is because the === operator checks the data type as well, and the two values are not of the same type.

    E. Output: `false`. This is because the boolean value true maps to the int 1 and that is not equal to 2.

    F. Output: `true`. This is because Boolean(2) maps to true and the two values are equal and of the same type.

15. The difference between the `==` and the `===` operators is that the `==` operator checks if the two values are equal after any necessary type conversion, whereas the `===` operator checks equality without any type conversion, so it checks the equality of the data types and the values as well.
16. Code in file: part2-question16.js
17. The result of the function is an array: `[ 2, 4, 6 ]`. Calling the function `modifyArray()` and creates a new array using the callback parameter which contains the function called `doSomething()`, and pushes the values to the new array and returns that. 
18. Code in file: part2-question18.js
19. The output of the code is: 

    `1`

    `4`

    `3`

    `2`

    However, the last value (`2`), was outputted after a certain delay.