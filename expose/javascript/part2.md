1. Line 12 will print 3 because the for loop will run 3 times. In the last iteration, i will become 3 and the for loop will be broken. Since, i is a var it will be able to exist outside for loop.
2. Same like number 1, `discountedPrice` is a `var` so it will exist outside the for loop. In the last iteration, it will be `300 * 0.5 = 150`. So, line 13 will print 150.
3. `finalPrice` will be 150 because in the last iteration, `discountedPrice` is 150. And it is a whole number so multiplying and dividing by 100 is the same thing. So 150 will be printed.
4. This function will return an array that has calculated the price of an item after applying 50% discount. So, when we print this function, the answer will be `[50, 100, 150]`.
5. This will cause an error because `i` is out of scope after the for loop is executed.
6. This will also cause an error because discountedPrice is a local variable whose scope is limited to the for loop. And, it will be deleted after the for loop's execution is finished.
7. line 14 will print 150 because `finalPrice` is declared outside the for loop but inside the function's scope. So, it won't be deleted after for loop's execution.
8. This function will return an array that has calculated the price of an item after applying 50% discount. So, when we print this function, the answer will be `[50, 100, 150]`.
9. This line will cause an error because `i` does not exist outside the scope of for loop.
10. Line 12 will print 3 because thee variable `length` is assigned `prices.length` which is 3 when passed.
11. This function will return an array with length 3 whose elements will be `[50, 100, 150]`. First, `discounted` gets created that will represent the values returned. Then, in the for loop, it will run for 3 iteration from 0 to 2. `discountedPrice` will get original price/2. And, line 8 will push it into `discounted`.
12.
a. `student.name`
b. `student["Grad Year"]`
c.`student.greeting()`
d. `student["Favorite Teacher"].name`
e. `student.courseLoad[0]`

13.
a. `32` because 2 will become a string due to 3 having a string type and they will be concatenated.

b. `1` same as above

c. `3` because null becomes 0. 

d. `3null` because it is a concatenation operatioin and both 3 and null gets treated as strings.

e. `4` because `true` maps to 1.

f. `0` because false maps to 0 and null also maps to 0.

g. `3undefined` same as a. `undefined` becomes a string and gets concatenated with 3 because 3 is also a string.

h. `NaN` because we have a minus sign so it gets treated as a subtraction and `undefined` becomes `NaN` and anything minus `undefined` is `NaN`.

14.

a. `true` because 2 will be treated as an integer.

b. `false` because it is a string operation and 2 and 1 gets compared first. Since, 2 is more than 1. this will return false.

c. `true` because 2 gets treated as a string and both 2 and 2 are the same integer.

d. `false` because this is strong comparision and it is comparing an integer and a string. Therefore, it returns false.

e. `false` because true maps to 1 and 1 != 2.

f. `true` because Boolean 2 is a 1 and true is 1. We have a strong type comparision and both are non zero. 
