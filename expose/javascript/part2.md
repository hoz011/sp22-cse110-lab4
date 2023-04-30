1. At line 12, the code will print out the length of prices[], 3.
2. Line 13 will print 150.
3. Line 14 will print 150.
4. The function will return [50, 100, 150], which is the discounted prices of the prices[] array.
5. An error is thrown, because i was declared in a code block.
6. An error is thrown, because dicountedPrice was declared in a code block.
7. It will print 150, because finalPrice was declared outside of the code block but inside the function, so it is in scope.
8. It will return [50, 100, 150] because the array discounted was declared in the function in the same scope as the return statement.vf
9. An error is thrown, because i is not defined in scope.
10. 3 is printed, because length was defined in the same scope as the print statement.
11. It will return [50, 100, 150], because a const variable can still be seen outside of its code block.
12. See following:
    A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. 
    E. 
13. ARITHMETIC:
    A. '32', 2 was converted to string
    B. 1, '3' was converted to int
    C. 3, null was converted to 0
    D. '3null', null was converted to string
    E. 4, true was converted to 1
    F. 0, false and null both converted to 0
    G. '3undefined', undefined was converted to string
    H. NaN, undefined is converted to NaN and operation does not work
14. COMPARISON:
    A. true, '2' was converted to int
    B. false, they are compared as strings and 2 comes after 1 when comapring strings
    C. true, they are converted and the same
    D. false, because they are different types
    E. false, because true was converted to 1 and they are not the same
    F. true, because they are the same type
15. == checks if the values of two variable are the same, and will convert automatically. === checks if two variable are of the same type, without converting any of the variables.
16. See file
17. The result will be [2, 4, 6]. When modifyArray() is called, it will start going through the code. When line 4 is reached, it will go to the function doSomething with that element of array as the parameter, and execute the code in doSomething, which just multiplies the value by 2. It will do that each time, and ultimately return newArr, which is the old array with values nultiplied by 2.
18. See file
19. The code prints 1, 3, and 4 right away after calling, but then prints 2 one second after the call is made. The output is:
    1
    4
    3
    2
