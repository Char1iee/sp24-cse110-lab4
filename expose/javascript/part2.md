1. Length of the prices will be printed. Since variable i is created using var, it can be accessed by this whole function. Therefore, after the program exits the for loop, i is still accessible. After for loop is exited, i will be the value of prices.length, which is 3 in this case since [100, 200, 300] has a length of 3.
2. 150 will be printed. Since discountedPrice is created using var, it can be accessed by this whole function. Therefore, by the time the program exits the for loop, discountedPrice has the value of the last element of the variable prices applied by the discount, which is 300*0.5=150 in this case.
3. 150 will be printed. Since finalPrice is created using var, it can be accessed by this whole function. By the time the program exits the for loop, finalPrice stores the value of the last element of the variable prices applied by the discount and rounding method, which 150 at the end.
4. This function will return the list of prices applied by the discount given. This function takes two inputs, one is the list of prices and the other is the discount rate. By using for loop, the program goes each element in the price list and applies it with the discount and push the final value to the new array representing the discounted prices.
5. Error, because variable i is created using let inside the for loop, which makes i only accessible within the for loop. Since line 12 accesses i outside its scope, the program does not recognize what i is and error occurs.
6. Error, because variable discountedPrice is created using let inside the for loop, which makes discountedPrice only accessible within the for loop. Since line 12 accesses discountedPrice outside its scope, the program does not recognize what discountedPrice is and error occurs.
7. 150 will be printed. Since variable finalPrice is created outside for loop and inside the function, it is accessible within the whole function. By the time the program exits the for loop, finalPrice stores the value of the last element of the variable prices applied by the discount and the rounding. Therefore, the result is 300*0.5 rounded, which is 150.
8. This function will return the list of prices applied by the discount given. This function takes two inputs, one is the list of prices and the other is the discount rate. By using for loop, the program goes each element in the price list and applies it with the discount and push the final value to the new array representing the discounted prices.
9. Error, because variable i is created using let inside the for loop, which makes i only accessible within the for loop. Since line 12 accesses i outside its scope, the program does not recognize what i is and error occurs.
10. 3 is printed because length is a constant variable assigned with the value of the length of the variable prices, which is length of [100, 200, 300] in this case which is 3.
11. This function will return the list of prices applied by the discount given. This function takes two inputs, one is the list of prices and the other is the discount rate. By using for loop, the program goes each element in the price list and applies it with the discount and push the final value to the new array representing the discounted prices.
12. A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]
13. A. 32, because a string representation of the number 2 is concatenated to the string '3'.
B. 1, because when using -, the string '3' is converted to a number and the arithmetic operation is done.  
C. 3, because when doing arithmetic operation, null is converted to 0.
D. 3null, because when concatenating a string, null is converted to the string 'null'.
E. 4, because when doing arithmetic operation, true is converted to 1.
F. 0, because when doing arithmetic operation, both false and null are converted to 0.
G. 3undefined, because when concatenating a string, null is converted to the string 'null'.
H. NaN, because when using -, the operation becomes an arithmetic operation, where '3' becomes 3 and undefined becomes NaN, so the result is NaN.
14. A. True, because string '2' becomes number 2.
B. False, because there are no conversions here. The first character of '2' is not smaller than the first character of '12' which is '1'.
C. True, because string '2' becomes number 2.
D. False, because type of 2 is number and type of '2' is string, which is not the same.
E. False, because true becomes number 1 and 1 is not equal to 2.
F. True, because both of them are of type boolean.
15. == is using the type conversion to compare the values and === is not using type conversion to compare the types of the variables. Therefore, for === to be true, variables on both sides have to be the same type and the same value.
17. The result will be [2,4,6]. When we call the function modifyArray, the program take an array and a function as input. The program first creates an empty array. Then the program goes over each element of the array and applies the function to it and store it to the new empty array. Therefore, the result is the array storing each element of the original one applied with the function, which is times the element by 2.
19. 1 4 3 2