1. 3 will be printed as `i` is a var and has function scope.
2. 150 will be printed as `discountedPrice` is a var and has function scope.
3. 150 will be printed as `finalPrice` is a var and has function scope.
4. It will return `[50, 100, 150]` which is the list containing discounted prices because `discounted` is of type `var` which means it has function scope. So, the function will return whatever discounted was updated to at the end of the function call.
5. Error because `i` is not defined as its scope is the `for` loop.
6. Error because `discountedPrice` is not defined as its scope is the `for` loop.
7. 150 will be printed as the scope of `finalPrice` is the whole function.
8. It will return `[50, 100, 150]` because `discounted` is of type `let` meaning it has block scope which is the whole function. So, the function will return whatever discounted was updated to at the end of the function call.
9. Error because `i` is not defined as its scope is the `for` loop.
10. 3 will be printed as `length` of the list is 3.
11. It will return `[50, 100, 150]` which is the list containing discounted prices because declaring `discounted` of type `const` means we cannot reassign its memory address but we can still add or remove elements.
12. * (A) student.name
    * (B) student['Grad Year']
    * (C) student.greeting()
    * (D) student['Favorite Teacher'].name
    * (E) student.courseLoad[0]
13.  
