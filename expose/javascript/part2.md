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
13. * (A) '32' because integers map to their exact string representation and          adding a string to an integer acts like concatenation.
    * (B) 1 because there is no subtract operation for strings so it assumes          we are subtracting 2 from 3.
    * (C) 3 because null becomes 0 and 3 + 0 = 3. 
    * (D) '3null' because null maps to its string representation which is             'null' and concatenates to '3' which is also a string.
    * (E) 4 because true becomes 1 and 1 + 3  = 4
    * (F) 0 because false and null are both 0 in their integer representation.
    * (G) '3undefined' because undefined becomes 'undefined' and gets                 concatenated to '3'.
    * (H) NaN because the subtract operation converts '3' to 3 and tries to           convert undefined to an integer as well but it results in NaN since it         cannot be converted. Hence, the whole operation results in NaN.
14. * (A) true because it converts '2' to its integer representation 2 and            then does the comparison.
    * (B) false because it converts '2' to 2 (an integer) and '12' to 12 (an          integer) and then checks if 2 is less than 12 which is false.
    * (C) true because it converts '2' to 2 (an integer) and then checks if 2         == 2 which is true.
    * (D) false because here we are using `===` (string equality operator) and       it performs the comparison without type conversion.
    * (E) false because it converts true to 1 and then sees if it's equal to 2.
    * (F) true because it checks if true is equal to Boolean(2) which after          conversion results into true since it is non-zero.
15. `==` performs comparison by doing some automatic type conversions                beforehand. On the other hand `===` performs comparison without perform        any automatic type conversions.

