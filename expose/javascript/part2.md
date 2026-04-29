1. Line 12 will print the value 3 because i is declared as var which means it is a function-scoped variable and is accesible outside the loop. Since the loop ends when i = 3 that will be the value when line 12 executes and there is no error.
2. Line 13 will print 150 since discountedPrice is declared as var. After the loop ends it's value will be 150 and line 13 will print that with no error.
3. Line 14 prints 150 because finalPrice is declared with var outside the loop on line 4, so it is accessible throughout the function. After the last iteration it holds the value 150, which is what gets printed with no error.
4. The function successfully returns [50, 100, 150]. The discounted array is declared with var on line 3, outside the loop, making it accessible throughout the function. Each iteration calculates the discounted price and pushes it into the array, and line 16 returns the completed array with no error.
5. Line 12 throws an error: i is not defined because i is declared with let on line 6, making it block-scoped to the for loop. Once the loop ends at line 10, i goes out of scope and is no longer accessible, so line 12 crashes.
6. Line 13 throws an error: discountedPrice is not defined because discountedPrice is declared with let on line 7, making it block-scoped to the for loop. Once the loop ends at line 10, discountedPrice goes out of scope and is no longer accessible, so line 13 crashes.
7. Since finalPrice is declared with let on line 4, outside the for loop, it is block-scoped to the function body. It gets updated each iteration and retains the value from the last iteration (300 * 0.5 = 150), so line 14 can access it and prints 150 with no error.
8. The function successfully returns [50, 100, 150]. The discounted array is declared with let on line 3, outside the loop, making it accessible throughout the function. Each iteration calculates the discounted price and pushes it into the array, and line 16 returns the completed array with no error.
9. Line 11 will throw an error because i is defined with let in the for loop meaning it is a block scoped variable. Since line 11 is outside of the for loop the variable i is out of scope and an error is thrown.
10. Line 12 prints 3. length is declared with const on line 4, outside the loop, and assigned prices.length which equals 3. Since it's declared outside the loop, it's accessible at line 12. const is block-scoped to the function body here, so there's no scope issue.
11. The function successfully returns [50, 100, 150] with no error, because discounted is declared with const outside the loop and is accessible throughout the function. Discounted is never reassigned so no error is thrown.
12.  A. student.name B. student['Grad Year'] C. student.greeting() D. student.['Favorite Teacher'].name E. student.courseLoad[0]
13.  A. '32'. The 2 is converted into a string and concatenated with the '3'.
  B. . 1 . The three is converted into an int and they subtract like integers
C. 3 . null converts to 0 and 3+0 is just 3
D. '3null'. null converts to a string and they are concatenated
E.. 4 . true converts to 1 and 1+3=4
F. 0 . false ocnverts to 0 and null converts to 0 who's sum is just 0
G. '3undefined'. undefined converts to a string and they concatenate
H. NaN. undefined converts to NaN or not a number so any computation becomes NaN
14. A. true. '2' converts to 2 and 2>1 is true
B. false. the strings are compared character by character and '2'>'1' alphabetically so it is false
C. true. '2' is converted to 2 and 2 = 2 is true
D. false. === does not convert types an since '2' is not equal to 2 it is false
E. false. true converts to 1 which is not equal to 2 so it is false
F. true. Boolean(2) converts to true which is the same type and value as true so it is true
15. == automatically converts one or both values to a common type before comparing, following JavaScript's built-in conversion rules. === does not convert anything. It compares both the value and the type directly, so if the types are different it immediately returns false.

17.) modifyArray([1,2,3], doSomething) returns [2, 4, 6].
doSomething is passed in as the callback parameter. Since functions are a data type in JavaScript, they can be passed around just like any other value. Each iteration calls callback(array[i]) which is equivalent to doSomething(array[i]), multiplying each element by 2 and pushing the result into newArr. After all 3 iterations, the function returns [2, 4, 6] which is all the elements of the oirginal array multiplied with 2.
19.) 1 4 3   2 (each on separate lines)

    
