1. Line 12 will print 3 because i is the iteration variable of the for loop and line 12 prints what i equals after the loop ends. The loop ends when i is no longer less than the length of the prices array, and since i starts at 0 and increments by 1, i will equal the length of the prices array when it ends. The array prices, in this scenario, has the length of 3 so 3 is printed.
2. Line 13 will print 150 because since this line is after the for loop, discountedPrice will be set to prices[i] * (1 - discount), where i is the last iteration that occurs in the for loop. That means, in this scenario, i = 2, and prices[i] = 300. Since discount is 0.5, discountedPrice is set to 150 before exiting the for loop and then it is printed.
3. Similarly to number 2, line 14 will print 150 because since this line is after the for loop, finalPrice will be the rounded version of discountedPrice, which we showed is equal to 150, therefore, finalPrice will be equal to 150 at the end of the for loop and this will be what is printed.
4. This function will return [50, 100, 150]. discountPrices returns discounted, which is an array that stores the discounted prices of the intial prices array. Each value of the prices array is iterated through and discounted according to the given discount (in this scenario, 0.5) and then that value is stored in the discounted array. The values [100, 200, 300] discounted by 0.5 will be [50, 100, 150] which is what ends up being stored in discounted.
5. The code causes an error because since we are using the let keyword for the variable i, i cannot be accessed outside of the scope of the block it is in, which would be the for loop. The console.log line is after the for loop and tries to access i which is not possible so there is an error.
6. The code causes an error because since we are using the let keyword for the variable discountedPrice, discountedPrice cannot be accessed outside of the scope of the block it is in, which would be the for loop. The console.log line is after the for loop and tries to access discountedPrice, which is not possible so there is an error.
7. Similarly to number 3, line 14 will print 150 because since this line is after the for loop, finalPrice will be the rounded version of discountedPrice, which we showed is equal to 150, therefore, finalPrice will be equal to 150 at the end of the for loop and this will be what is printed. There is no error because, even though finalPrice has the let keyword, it is still within the scope of the block it is defined in, which is the function discountPrices.
8. Similarly to number 4, this function will return [50, 100, 150]. discountPrices returns discounted, which is an array that stores the discounted prices of the intial prices array. Each value of the prices array is iterated through and discounted according to the given discount (in this scenario, 0.5) and then that value is stored in the discounted array. The values [100, 200, 300] discounted by 0.5 will be [50, 100, 150] which is what ends up being stored in discounted. Even though all the variables are defined with the let keyword, all the variables are used properly in the scope they are defined in, so it functions normally.
9. The code causes an error because since we are using the let keyword for the variable i, i cannot be accessed outside of the scope of the block it is in, which would be the for loop. The console.log line is after the for loop and tries to access i which is not possible so there is an error.
10. Line 12 prints out 3 because length is initialized to prices.length in line 4 where the length of the prices array is 3 and then the variable length does not get changed until line 12 so 3 is printed.
11. Similarly to number 4, this function will return [50, 100, 150]. discountPrices returns discounted, which is an array that stores the discounted prices of the intial prices array. Each value of the prices array is iterated through and discounted according to the given discount (in this scenario, 0.5) and then that value is stored in the discounted array. The values [100, 200, 300] discounted by 0.5 will be [50, 100, 150] which is what ends up being stored in discounted. None of the variable keyword rules are violated so the code works functionally.
12. A. student.name

    B. student['Grad Year']
    
    C. student.greeting()
    
    D. student['Favorite Teacher'].name
    
    E. student.courseLoad[0]
    
13. A. 32, integers map to their exact string representation

    B. 1, the subtraction converts the string into an integer to be able to perform arithmetic.

    C. 3, null's toNumber value is equal to 0 so 3 + 0 = 3

    D. 3null, '3' starts the output as a string, and adding null just adds null as a string as well.

    E. 4, true maps to the value of 1.

    F. 0, both false and null map to the value of 0 so 0 + 0 = 0.

    G. 3undefined, '3' starts the output as a string,  and adding undefined just adds undefined as a string as well.

    H. NaN, the subtraction makes the values convert toNumber and undefined maps to NaN.

14. A. true, '2' is type converted to 2 and 2 is greater than 1.

    B. false, both values are strings so it compares the first character. The character 2 is greater than the character 1 so it would be false.

    C. true, '2' is type converted to the value and 2 is equal to 2.

    D. false, === is the string equality operator and the two values have different types so it would be false.

    E. false, true maps to 1 which is not equal to 2

    F. true, Boolean(2) is true and both values of the strict equality are of the boolean type.

15. === is a strict equality operator while == is the equality operator. The strict operator always considers values of different types to be different (false) whereas the equality operator can automatically do type conversions.

16. in file part2-question16.js

17. The result would be the array [2,4,6]. We call modifyArray with the given array and doSomething as our callback function. doSomething takes in a number and returns double of that. In modifyArray, the inputted array is iterated through and put into the callback function which is doSomething, and the value returned, which would be double, would be stored in the array newArr which is returned at the end. This essentially doubles each value and returns the array with the values of the doubles which would result in [2,4,6].

18. in file part2-question18.js

19. 1

4

3

2
