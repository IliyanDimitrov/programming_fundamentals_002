# Written questions

The following questions are intended to be answered with written answers (no coding required) and should re-enforce some of the learning you have completed.

1. In what data type have we chosen to represent a book?

    A1. String and grouped them in array/collection.

2. Is this the best data type, do you think? Could we have chosen a more appropriate data type? Why?

    A2. Strings do the job, but we could choose to create a book object as well. Giving it keys of `author` and `title` and then when iterating through the object we can just call them properties instead of iterating through a piece if text.

3. Take a read of the Jest Documentation about [Matchers](https://jestjs.io/docs/en/using-matchers) such as `toBe` and `toEqual`. What other matchers might come in useful? Check the tests you have written and make a list of alternative matchers which you might have been able to use.

    A3. We can create a function that throws an excetpion/error for example in the `catalogueService.countBooksByKeyword` if the input is not text maybe also add some regex to check for special characters or white spaces and validate against them as well. 

    And test with .toThrow();

4. What data types are considered "complex" data types?

    A4. Objects/array 

5. What data types are considered "primitive" data types?

    A5. The ones which are not an object type(num, string, boolean ,null, undefined, char)

6. In JavaScript it is possible to use `==` ("double equals") or `===` ("triple equals") to compare two values. What is the difference and why do we prefer triple equals?

    A6. == : non-strict equality convert the values to the same type and then compares them
    === : strict equality compares both the type and the value, if the type's of the variables are not the same, the result will be false;