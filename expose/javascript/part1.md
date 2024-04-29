1. values added: 20
2. final result: 20
3. values added: 20
4. The code returns an error because since the variable result has the let declaration, result can only be accessed within the scope of the block it is defined in, or in this case just the if block. Line 13 is outside of that block so result cannot be accessed.
5. The code returns an error because since the variable result has the const keyword, result cannot be reassigned after the first time, which would be in line 5. There is an error in line 7 because the code tries to reassign the variable result to the sum of num1 and num2 but it is a const.
6. The code returns an error because the const keyword has the same scope as the let keyword. That means that the variable result cannot be accessed outside of the scope of the block it is defined in, which would be the if block. Line 13 is outside of that block so result cannot be accessed.
