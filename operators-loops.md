## Ch. 8: Operators and Loops (JS/Jquery book)

#### **Comparison Operators**:
* == (is equal to) compares two values (numbers, booleans, strings) to check if they are the same
ex: 'Cat' == 'Dog' returns FALSE // 'Cat' == 'Cat' returns TRUE

* === (STRICT equal to) checks that data is same *value and type*.
ex. '100' === 100 returns FALSE because '100' is a string and 100 is a number. '100' === '100' returns TRUE because same TYPE (number) and value (100)

* != (is not equal to) comapres values to see if they are *not* the same.
ex. 'Cat' != 'Cat' returns FALSE // 'Cat' != 'Dog' returns TRUE

* !== (STRICT not equal to) compares data type and value
ex. '100' !== 100 returns TRUE (string vs number) // '100' !== '100' returns FALSE (same value of 100 and same data type number)

* '>' (greater than) checks if number on left is *greater than* number on right
ex 4 > 3 ret TRUE // 3 > 4 ret FALSE

* '<' (less than) checks if number on left is less than number on right
ex. 4 < 3 ret FALSE // 3 < 4 ret TRUE

* '>=' (greater than or equal to) checks if left is greater than/equal to right
ex. 4 >= 3 ret TRUE // 3 >= 4 ret FALSE // 3 >= 3 ret TRUE

* '<=' (less than equal to) checks if left is less than equal to right
ex. 4 <= 3 ret FALSE // 3 =< 4 ret TRUE / 4 =< 4 ret TRUE

#### **Logical Operators**

Typically return single values of TRUE or FALSE. They allow you to compare more than one comparison operators.

*logical expressions evaluated left to right*

* && (logical and) tests more than one condtiion
((2 < 5>) && (3 >= 2)) ret TRUE

* || (logical or) tests at least one condition
((2 < 5) || 2 < 1) ret TRUE

* ! (logical not) takes single boolean value and inverts it
!(2 < 1) ret TRUE

**if the first condition provides enough info to answer (i.e. a disqualifying conditon) then there is no need for second evaluation.

#### Loops

Loops check conditions. If ret TRUE, a block of code will run, reapeating until ret FALSE.

Three common types:
**For loop**
run code specific number of times (most common type of loop). 

**While loop**
If you don't know how many times a code needs to run

**Do while**
Similar to **while** but always runs statement inside curly brackets at least once even if ret FALSE

for (var i = 0; o < 10; i++) {
    document.write(i);
}

Above, **for** is the condition. Parenthesis is the condition/counter. the document.write between the curly brackets is the code to executre during loop.

#### Loop Counters

Initialization ; Condition ; Update

In above example, **initialization** is var i = 0;
Only happens the first time the loop runs.

**Condition** is i < 10;
Sets the threshold at which loop continues until

**Update** is i++
This means that every time the loop runs the code in the curly brackets, it adds one to the counter.