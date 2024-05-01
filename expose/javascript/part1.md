1. Line 9 prints: values added:  20
2. Line 13 prints: final result:  20
3. Line 9 prints: values added: 20
4. Line 13 returns an error. This is because the variable 'result' is not defined because it was declared using 'let', which means it doesn't extend past the scope of the if statement, since it was declared within the if statement. 
5. The code returns an error. This is because the line 'result = num1 + num2;' causes a TypeError, because a new value cannot be assigned to a variable declared as a 'const'.
6. The code returns an error. This is because the variable 'result' was declared using 'const', which means its scope is only within the if statement, where it was declared, so it is undeclared when it is used in line 13. 