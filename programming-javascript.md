## Programming with Javascript

**Javascript** can
* Access content
* Modify content
* Program rules
* React to events

Examples of JS would be slideshows, forms, reloads, filters.

A script is a series of instructions for a computer to accomplish a task...think recipes, handbooks, manuals.

Scripts require a goal, and then the steps that need to be taken in order for the goal to be achieved. A script might not use every instruction in every case.

* **Define** the goal
* **Design** the script
* **Code** each step

Computers solve problems *programmatically*, that is, step-by-step, one at a time.

A flowchart can help visualize the workflow of a script depending on different situations.

#### Expressions and Operators

An **expression** evaluates into one value. Expressions either:
* Simply assign value to a variable
    var color = 'beige';
        
        In this example, the value of color is now beige.
* Return one value from two or more values
    var area = 3 * 2;

        The result of the evaluation is 6, just one value.

**Operators** create a single value from one or more values.

*assignment* operators
    color = 'beige': -- this assigns value to variable.

*arithmetic* operators
    area = 3 * 2; -- performs basic math

*string* operators
    greeting = 'Hi ' + 'Molly'; -- combines two strings

*comparison* operators
    buy = 3 > 5; -- compares values and returns true or false

*logical* operators
    buy = (5 > 3) && (2 < 4>); -- combine expressions and return true or false

##### Arithmetic Operators

Many types used in Javascript
* addition (+)
* subtraction (-)
* division (/)
* multiplication (*)
* increment (++)
    adds 1 to current number
* decrement (--)
    subtracts 1 from current number
* modulus (%)
    divides two values and returns remainder (10 % 3 returns 1)

##### String Operator

The string operator (+) joins the strings on either side. This is called a  **concatenation**.
    var firstName = 'Ivy';
    var lastName = 'Stone';
    var fullName = firstName + lastName;

##### Functions

A **function** groups a series of statements for accomplishing a specific task.

Asking a function to do its thing is *calling* the function. Some will only be used when specific actions trigger them.

Info passed to functions is called a *parameter*. The response a function returns is known as *return value*.

**Declaring a function**

"function" is the function keyword below. "sayHello()" is the function name. The curly brackets contain the code block.

function sayHello() {
    document.write('Hello!');
}

**Calling a function**

sayHello();

*this is the most simple sort of function*. Some need information:

function getArea(width, height) {
    return width * height;
}

In this function, (width, height) represent parameters which are used like variables.

Parameters can function like variables, but the actual given data is referred to as an **argument**.