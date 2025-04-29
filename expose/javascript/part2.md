1. Line 12 will print 3 because i was declared with var, which makes it still accessible after the for loop finishes.
2. Line 13 will throw an error because discountedPrice was declared with var inside the for loop and can't be accessed outside the loop.
3. Line 14 would print 150 because finalPrice was declared with var and is accessible after the for loop.
4. The function will return [50,100,150] because it would calculate each price after a 50 percent discount and stores the results in the array.
5. Line 12 would throw an error because `i` was declared with `let`, so it can't be accessed outside of it.
6. Line 13 would throw an error because `discountedPrice` was declared with `let` inside the loop, so it can't be accessed outside of it.
7. Line 14 would print 150 because finalPrice was declared with let, so the function is still accessible after the for loop.
8. The function will return the discounted price array of [50,100,150] because it calculates the discounted prices and stores them in an array.
9. Line 11 would throw an error becasue i was declared with let inside the for loop, so you can't access it outside of it.
10. Line 12 will print 3 because length was declared with const, so it's accessible after the for loop.
11. The function will return [50,100,150] because it calculates and stores each discounted price in the array.
12.
- A. student.name
- B. student['Grad Year']
- C. student.greeting()
- D. student['Favorite Teacher'].name
- E. student.courseLoad[0]
13.
- A. '32' is outputted because string concatenation happens because one side is a string.
- B. '1' is outputted because javascript converts the string to a number for subtraction
- C. '3' is outputted because null is treated as 0 in addition with numbers
- D. '3null' is outputted because '3' is a string
- E. '4' is outputted because true is converted to 1, and 1 plus 3 equals 4
- F. '0' is outputted because false becomes 0 and null becomes 0, and 0 plus 0 equals 0
- G. '3undefined' is outputted because '3' is a string
- H. 'NaN' is outputted because subtraction tries to convert both 3 and undefined to numbers but can't 
14.
- A. 'true' is outputted because 2 is converted to a number, and 2 is greater than 1, so its true
- B. 'false' is outputted because string comparison happens alphabetically, and 2 comes after 1
- C. 'true' is outputted because the equal sign doesn't have a type conversion so both 2's are considered the same
- D. 'false' is outputted because the === sign checks type and value, and number is not equal to a string
- E. 'false' is outputted because true converts to 1, and 1 isnt't equal to 2
- F. 'true' is outputted because Boolean(2) is true, and both sides are true with the same types
15. The difference between == and === is that == compares values with type conversion, while === compares values without type conversion, only equality.
17. The result would be [2,4,6] because the doSomething function would double each number in the array. This being said, the modifyArray function would go through each element, apply doSomething, then push the result into the new array.
19. The output of the above code was: 1, 4, 3, 2 all on a new line