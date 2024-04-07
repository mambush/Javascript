# Javascript
  # JAVASCRIPT
        ## INTRODUCTION TO JAVASCRIPT
        # WHAT IS JAVASCRIPT?

        *Javascript is a programming language use to make web pages interactive. It is what gives a page life-the interactive element and animations that engages the user.
        * Javascript is one of the three pillars of the web development-the other two being HTML AND CSS. Javascript was purposely designed to intergrate in HTML. All major web browser support Javascript.
        * Javascript is the world most popular programming language
        * Javascript is the programming language of the web
        * Javascript creates interactivity
          = For your website to function on your Mobile devices we use Javascript
          * Javascript runs right in your browser.
          * Javascript provides a real-time content updates.

            # Javascript Variables
            * One of the fundamental characteristics of a programming language is the set of data types it supports
            * Variables can be thought of as named containers.
            * You can place data into these containers and then refer to the data simply by naming containes.
              # NOTE
              = Before you use a variable in Javascript program, you must declare it. Variable are declared with the var.
              var money;
              var name;
              * var a=10;
                var b=20;
                var sum=a+b;
                * var: Used to declare variables globally or within a function scope. It's less commonly used nowadays.

* let: Introduces block scope and allows the variable's value to be changed.

* const: Also introduces block scope, but the value of a const variable cannot be changed after it's assigned.
  Operators
  * Operators are symbol that perform operations on values. There are several types of operators in javascript
    · Arithmetic operators: +, -, *, /, % (addition, subtraction, multiplication, division, modulus).

* Assignment operators: =, +=, -=, *=, /= (assigning and modifying values).

* Comparison operators: ==, ===, !=, !==, >, <, >=, <= (comparing values).

* Logical operators: &&, ||, ! (logical AND, logical OR, logical NOT).
  Javascript operators the operands, these symbols that are used to manipulate a certain value or operand. Operators are used to performing specific mathematical and logical computations on operands.
  # Javascript assignment
  * The assignment(=) operator is used to assign a value to a variable or property. The assignment expression itself has a value, which is the assigned value. This allows multiple assignments to be chained in order to assign a single value to multiple variables.
    Assignments operators( =,+=,-=,*=,/=):
    * assign and modify values.

      # DAY 2 ( Strings and Arrays)

      # Array
      * Array are a fundamental part of most programming  languages and scripting languages. Array are simply an ordered stack of data items with same data types.
      * Using Arrays , you can store multiple under a single name.Instead of using a separate variable for each items,you can use one array to hold all of them.
      * Array: A data structure in JavaScript that allows you to store multiple values in a single variable. Array Element: Each value within an array is called an element. Elements are accessed by their index. Array Index: A numeric representation that indicates the position of an element in the array.
      *  we can say that in computer programming, arrays are generally used to organize the same type of data.
      *  An array is a group of similar elements or data items of the same type collected at contiguous memory locations. In simple words, we can say that in computer programming, arrays are generally used to organize the same type of data.

        # Creating Array
        = Most programming languages use similar syntax to create arrays. Javascript arrays are created by first assigning an array object to a variable name.

        [ var array_name=new Array(number_of_element)]

        * When you assign a value to a array you write:
          [ Array_name[0]="array element"]

          * So,using our prior example, we could write:
            = var faq=new Array(3)
            = faq[0]="what are javascript arrays"
            = faq[1]="How to create arrays in Javascript?"
            = faq[2]="what are two dimensional arrays?"

            * Also an Array is a special variable, which can hold more than one value:

              # Why use Arrays
              If you have a list of items( a list of car names, for example), storing the cars in single variables could look like this:
              = let car 1="Saab";
              = let car2="volvo";
              = let car 3="Bmw";

              Syntax:

              Const array_name=[item1,item2,...];
              It is a common practise to declare arrays with the const keyword.

              Example;
              const cars=["Saab","volvo","Bmw"];

              You can also create an array,and then provide the elements:

              Example;
              Const cars=[];
              Cars[0]="Saab";
              cars[1]="volvo";
              cars[2]="Bmw";

              Accessing Array Element
              * You can access an array element by referring to the index number;
                = Const cars=["Saab","Volvo","Bmw"];
                let car=cars[0];
                car[0]="Opel";

                Example
                const cars=["Saab","volvo","Bmw"];
                cars[0]="Opel";

                # Strings
                * A String is a sequence of one or more characters that may consists of letters, numbers or symbols. Strings in javascript are premitive data types and immutable, which means they are unchanging.
                * A string is used to represent text rather than numbers.
                * A string can contain letters,numbers,symbols and even spaces. It must be enclosed in quotation marks for it to be recognised as a string.
                * Strings are useful for holding data that can be represented in text form. Some of the most-used operations on strings are to check their length to build and concatenate them using the -+ and += operators, checking for the existence or location of subscript with the index() method, or extracting substrings with the substrings()methond.

                * A string can be any text inside double or single quotes
                   # Example:
                  = let carName 1="volvo XC60"; let carName 2="volvo XC60";

                   # How to declare a string

                    You can declare a string variable like this:
                  Var myName="your Name";
                  # Note
                  * "your Name" is called a string literal. A string literal or string is a series of zero or more characters enclosed in single or double quotes
                    = which means there is no difference between the two.
                    # You can Add a string inside a string
                    = You can add a string inside a string as long they do not match the quotes surrounding the string.
                    For example:
                    let answer 1="It's alright";
                    let answer 2= "He's called 'Johnny'";
                    let answer 3= 'He's called "Johnny"';

 * Strings can be created as primitive,from string literals, or as a object using the string() constructor.
    # Primitive string
   Const string 1 = "A string primitive";
  # Object string
  * Const string 4= newString("A String object")
    # Booleans
    In JavaScript, boolean is a basic data type that can represent true or false values. It's frequently applied to conditional statements and logical procedures. Here's a quick rundown of how JavaScript handles booleans:

Declaration and Initialization: The true and false keywords can be used to declare and initialise booleans.

JavaScript
Copy the programming
let isFalse = false; let isTrue = true;
Operators with logic:
Logical operators for working with boolean values are provided by JavaScript:

If both operands are true, the logic AND operator && returns true. If one or more operands are true, the function (logical OR) returns true. Returns the operand's opposite boolean value (logical NOT).
JavaScript
Copy the code: let y = false; let x = true;

log.console(x && y); // false log.console(x || y); // true log.console(!x); // false
Operators for comparison:
Based on the comparison, comparison operators return boolean values.
 # Functions
 One of the core components of JavaScript is a function, which lets you wrap a code block and run it repeatedly. An overview of JavaScript functions is provided here:

Function Declaration: The function keyword, the function name, and two parenthesis containing any parameters the function should accept are used to declare a function. Curly braces {} encapsulate the function body.


JavaScript
The code for the function greet(name) is copied as follows: console.log("Hello, " + name + "!");
Function Expression: This is the name given to the assignment of functions to variables.

JavaScript
Copy the following code: const greet = function(name) { console.log("Hello, " + name + "!"); };
Arrow Operations:
When writing functions, especially simple ones, arrow functions offer a more condensed syntax.

JavaScript
Paste the code const hello = (name) => console.log("Hello, " + name + "!"); };
Invocation of a Function:
After a function is established,

## week 2
# Document object Model and JavaScript syntax
* The Document object model is an application programming interface(API) for HTML documents.It does two things for web developers:
  = Provides a structural representation of the document
  = Defines the way that structure is to be accessed from script.

  * In Javascript syntax has to do with objects. To access an object, property or method, its reference must include every object that contains it,Separated by a dot.
    = This is called the"dot syntax".
    # Object
    * A javascript object  is any scriptable HTML element, that is any Html element within  a document that may be accessed through the javascript language. Although the browser window is not as HTML element, it too is a scriptable object. Although the browser window is not an HTML element,it too is scriptable object.
    * An object is a collection of properties and a property is an association between a name( or key) and a value. A property value can be a function, in which case the property is known as a method. Object in Javascript, just as in many other programming language can be compared to object in real life.
    * In javascript, an object is a standalone entity with properties and type. Compare it to a cup for example. A cup is an object, with properties, A cup has a color, a design, weight, a material it is amde of. The same way Javascript objects can have properties, which define characteristics.

      # Creating an object
      const obj={
      property 1: value 1, ( property name can be an identifier)
      2: value 2( or it can be a number)
      "property n": value 3 ( or can be a string)
      };
      * Each property name before colons is an identifier( either a name, a number, or a string literal), and each value N is an expression whose value is assigned to the property name. The property name can also be expression; computed keys need to be wrapped in square brackets. The object initializer reference contains a more detailed explanation of the syntax.

In this example, the newly created object is assigned to a variable obj — this is optional. If you do not need to refer to this object elsewhere, you do not need to assign it to a variable. (Note that you may need to wrap the object literal in parentheses if the object appears where a statement is expected, so as not to have the literal be confused with a block statement.)

Object initializers are expressions, and each object initializer results in a new object being created whenever the statement in which it appears is executed. Identical object initializers create distinct objects that do not compare to each other as equal.

# Objects and Properties
* A javascript object has properties associated with it. Object properties are basically the same as variables,except that they are associated with objects, not scopes. The properties of an object define the characteristics of the object.

  Const myCar= {
  make:"Ford",
  model:""Mustang",
  year: 1969,
  },
  # Properties
  A javascript property is a member of an object that associates a key with a value. A javascript object is a data structure that stores a collection of properties.
  * A property consists of the following parts:
    = A name(also called a key),which is either a string or a symbols.
    = A value, which can be any javascript value. A property that has a function as its value may also be called a "Method"
    Example:
    const obj={
    a=1,
    b() {},
    };
  # Method
  = Method are actions that can be applied directly to objects.
  = Method definition is a shorter syntax for defining a function property in an object.
  * Method are signified by parenthesis immediately following their name, e.g "Alert()". These parenthesis sometimes hold value called parameters, which are required by some methods.

  
    = A parameter is simply information needed by a method in order to accomplish its task. for instance, the alert() method pops an alert box without using a parameter, the alert method will generate a dialog box,
    ( using Internet Explore) alert() which is meaningless. But with a parameter, the alert method will generate a dialog box alert("Hello word") which communicates a message to the end user.

      Javascript Methods
    * alert() causes an alert dialog box to appear over the page that launched it.
    * write() writes content to a page
    * focus() causes the mouse cursor to be inserted into a form element.
   
              ## DAY 2
      
      ## Calling one function from another function
      * Code inside a function behaves just like code anywhere else.
      * This means you can call one function from inside another function.
      * This allows you to"nest" functions,So that you can create separate functions, which each perform a specific task, and then run them together as a complete process one right after the other. for example,here's a function that calls three other mythical function, each one returning a string of text that has been altered:
        = function run(){
        var Ret= changeText("change me");
      alert(Ret);
document.write(Ret);
}
  function changeText(text){
 text=makeBold(text);
text=makeItalics(text);
text=makeBig(text);
return(text);
}
 function makeBold(In string) {
return(In String.bold());
}       
 function makeItalics(In String){
return(In string.italics());
}    
 function makeBig(In string){
return(In string.big())
}    
 # Creating objects with user-defined functions
 * Javascript is based on object: the window is an object, links are objects,forms are object, even NetScape itself( or other browser) is an object. Using objects can help make programming easier and more streamlined. You can extend the use of object in javascript by making your own.
   # Making new object entails two steps
> Define the object in a user-defined function.
> Use the new keyword to create( or instantiate) the object with a call to the object function
= create a new object:
> ret=new makeSimpleobject();
> function makeSimpleObject(){}
= The new object is called "ret". You just have to use any valid variable name for the new object.(use lower-case letters for variables that contain objects, so it's easier to tell that the variable contain an object)

# Defining new properties to already-made objects

> After an object has been created you can assign a value to it. But instead of just assigning a value to the object itself, you should define a new property for the object, and assign a value to the property. To create a new property and assign a value to it. You write a variable expression like this:

my object.property=value; > myobject is the name of the user-defined object
                          > property is the name of the property you want to create
                          > value is the value you want to assign

let's say you want to create an object called"customer" and you want to define three properties to it: name,address, and phone.

Customer=new makeSimpleObject();
Customer.name="fred";
Customer.address="123 Main Street";
Customer.Phone="555-1212";
function makeSimpleObject(){
return(this);
}

You can verify that you have created a new object and assigned properties to the object my adding an alert method to display one of the properties for example:
> You could put this after the customer.phone line. When you run the script the alert box will say "fred" for example:
> alert(customer.name);
# Defining properties when you create the object
Another method of defining properties for object is to include the property names in the object function.
> Customer=new makeCustomer("fred","123 Main street", "555-1212");
> alert( Customer.name);
> function makeCustomer(Name,address,Phone){
this.name=Name;
this.address;
this.Phone=Phone:
}
> These statements are assigned a property to the current object, which is the one being created in the makecustomer object function.
> Three parameters are passed to the object statement:
* Customer's name
* Address
* Phone number
  # Note:
  > These parameters are used to define the content of the three properties, which are name, address and Phone.
  > Javascript imposes no limitations on the number of properties you can assign to an object, just do this:
  * Customer=new makeCustomer("fred","123 Main Street","555-1212");
  * Customer.salutation="MR";

    # Operators
    > Javascript has both binary and unary operators.
    > Unary operators is an operation with only one operand. This operand comes either before or after the operator. Unary operator are more efficient than standard javascript function calls. Additionally, unary operator can be not be overriden, therefore their functionality is guarenteed.
    > A unary operator is an operator that operates on a single operand to produce a new value.Example:
    *Unary minus(-),unary plus(+),increment(++),decrement(--), logical Not(!), bitwise Not(~),address of (&), dereference(*), and size of operators.
    > Javascript has both binary and unary operators, one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator.

    * A unary operators requires a single operand,either before or after the operator.
      > operand  operand
      or
      > operand  operator
       ## Assignment Operators
      Return value and chaining
      > Like most expression, assignments like x=y have a return value. It can be retrieved by e.g assigning the expression or logging it:

      > An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal(=), which assigns the value of its right operand to its left operand.That is x=y assigns the value

      ## Table
      const z=(x=y); or equivalently: const z=x=y;
      Console.log(z): log the return value of the assignment x=y
      console.log(x=y); or log the return value directly.
      > The return value matches the expression to the right of the= sign in the"meaning" column of the above table.
      > That means that(x=y) returns y,(x+=y) returns the resulting sum x+y,(x**=y) returns the resulting power x**y, and so on.

      > In the case of logical assignments,(x&&=y),(x||=y), and (x??=y), the return value is that of the logical operation without the assignment, so x&&y,x||y, and x??y respectively.
      ## Note:
      > The return value are always based on the operands value before the operation.
      > when chaining these expression,each assignment is evaluated right to left.

      ## Day 3
      >Javascript "this" keyword
      * It contains properties(name and age) and a method greet. In the method greet, while accessing a property of an object, this keyword is used. In order to access the properties of an object, this keyword is used following by key.

        > "This"
        > In javascript, the "this" keyword refers to an object.
        > which object depends on how this is being invoked(used or called)
        > The this keyword refers to different objects depending on how it is used.
        > In an object method, this refers to the object.
        > Alone, this refers to the global object.
        > In a function, this refers to the global object
        ## Note
        "this" is not a variable. It is a keyword. Which means you cannot change the value of "this"
        = This in a method
        > when used in an object method,"this" refers to the object.
        > In javascript, object can also contain functions
        = object containing method
        > let person={
              name:'john',
              greet: function(){ console.log('hello');}
        };
        > A person object has a key(name and greet) and String value  and a function value.
        > The Javascript method is an object property that has a function value.
         ## Accessing object Methods
        > You can access an object method using a dot notation. The syntax is:
        = ObjectName.methodkey()- syntax

        > You can access a method by calling an objectName and key for that method along with(). And you can access property only by calling an objectName and a key.For example:
        * Accessing method and property:
          > let person={
                name:'John',
                greet: function(){ console.log('hello');}
          };
          * Accessing property:
            >person.name;//john
             // accessing method
               person.greet(); // hello
            >The greet method is accessed as person.greet() instead of person.greet

            # java  email validation
            > Validation is an essential part when communicating with the user. Especially when the user is providing critical information like the user credentials.
            * Email validation ensures:
              > user authenticity
              > Facilitates email validation on the client-side so that the processing of data on the server side is faster.
              > with javascript you can validate name,password,email,date etc.

              * validatng email addresses in javascript typically  involves using regular expression to match the pattern of a valid email address.While a perfect email validation regex is complex due to the intricacies of the email specification, a basic regex pattern can cover most common cases. Here's an example of how you can perform email validation in javascript.

                > Function validate Email(email) {
                *// Regular expression pattern for basic email validation
                * const regex=/^[^\s@]+@[^\s@]+\.[^\s@]+$/;
                  >^: Asserts the start of the string.

[^\s@]+: Matches one or more characters that are not whitespace (\s) or @. This part represents the local part of the email address before the @ symbol.

@: Matches the @ symbol.

[^\s@]+: Matches one or more characters that are not whitespace (\s) or @. This part represents the domain name of the email address after the @ symbol.

.: Matches a literal dot (.). It's escaped with a backslash because dot (.) has a special meaning in regular expressions and needs to be treated as a literal dot.

[^\s@]+: Matches one or more characters that are not whitespace (\s) or @. This part represents the top-level domain (TLD) of the email address.

$: Asserts the end of the string.

Putting it all together, the regular expression ensures that:

The email address starts with one or more characters that are not whitespace or @. Followed by an @ symbol. Followed by one or more characters that are not whitespace or @. Followed by a dot (.). Followed by one or more characters that are not whitespace or @. Ends with the end of the string. This regular expression provides a basic validation for email addresses. However, it's important to note that email address validation can be quite complex due to the variety of valid email formats and internationalization considerations. This regex does not cover all edge cases and may need to be adjusted based on specific requirements.

## WEEK 3
# DAY 1
String Operations
Accessing Individual Characters in a String:
You can access individual characters in a string using bracket notation ([]) or the charAt() method.

Using Bracket Notation:

const str = "Hello";

// Accessing the first character const firstChar = str[0]; console.log(firstChar); // Output: "H"

// Accessing the third character const thirdChar = str[2]; console.log(thirdChar); // Output: "l" Using charAt() Method:

const str = "Hello";

// Accessing the first character const firstChar = str.charAt(0); console.log(firstChar); // Output: "H"

// Accessing the third character const thirdChar = str.charAt(2); console.log(thirdChar); // Output: "l" Comparing Strings: You can compare strings in JavaScript using comparison operators (==, ===, !=, !==, <, >, <=, >=) or methods like localeCompare().

Using Comparison Operators:

const str1 = "apple"; const str2 = "banana";

console.log(str1 === str2); // Output: false console.log(str1 < str2); // Output: true (lexicographic comparison) Using localeCompare() Method:

const str1 = "apple"; const str2 = "banana";

console.log(str1.localeCompare(str2)); // Output: -1 (str1 comes before str2) When using localeCompare(), it returns:

-1 if the first string comes before the second string alphabetically. 0 if the strings are equal. 1 if the first string comes after the second string alphabetically. These are basic examples of how you can access individual characters in a string and compare strings in JavaScript. String manipulation and comparison are common tasks in JavaScript programming, and understanding these operations is essential for working with text data effectively.

## Event Handlers
A set of properties provided by DOM elements to help control how that element responds to events are known as the on-event handlers. Links, buttons, photos, and forms are examples of interactive elements. Non-interactive elements include the main document. Events include things like clicking, sensing when a key is pressed, focusing, etc. Typically, the on-event handler is named for the type of event it is intended to respond to, for example, onclick, onkeypress, onfocus, etc.

There are various ways in which you can designate a on<...> event handler for a certain event (like click) for a specified object:

By using the on{eventtype} HTML property to an element, for instance: <button onclick="return handleClick(event);">,
Alternatively, you can set the relevant JavaScript attribute by using document.getElementById("mybutton").function(event) {... } onclick.
Keep in mind that every object can only have one.
>The parameters of the event handler, this binding, and the return value
The code that is specified is wrapped into a function that has the following parameters when the event handler is specified as an HTML attribute:

event, source, lineno, colno, and error for the onerror event handler; event - for all other event handlers, excluding onerror. 
It should be noted that the error message is really contained as a string in the event argument.


This handler's keyword is set to the DOM element that the handler is registered on when the handler is called. If the event is canceled, it is determined by the handler's return value. The HTML specification's "The event handler processing algorithm" provides more information about how the return value is specifically handled based on the kind of event.

The phrase "event".
When talking about the several ways to listen to events,

An object or function registered via EventTarget is referred to as an event listener.while event handler refers to a function registered using on... attributes or properties, addEventListener()
A function is set up by the EventTarget method addEventListener() to be called each time the target receives the specified event. While Element, Document, and Window are common targets, any object that accepts events might be the target. In order for addEventListener() to function, a function or object that implements EventListener must be added to the EventTarget's list of event listeners for the designated event type. 

objective.addEventListener(listener[, options], type);

objective.addEventListener(listener[, useCapture], type);

# Dynamic
> Dynamic HTML refers to the combination of HTML,CSS and javascript to generate dynamic webpages. Events may in influence changes to a website features. Simple text font,color and style adjustments are one type of alteration that can be made, as can dynamically altering the pages content and rearring items on it.
* There are two methods for altering HTML pages:
  > Altering the objects class, which also alters the object style. To alter the style, use the objects style property.
  > Additionally, Javascript functions can be created in a variety of ways, such as:
  > The Id value in the javascript function is used to directly reference an object.
  > Then you may utilize this method to alter the style of just.
  > Dynamic HTML pages changes and update based on user interactions or server-side data. Content can be modified without reloading the entire page.
  > Utilize technologies like javascript,AJAX,and server-side scripting language(eg.PHP,Python) to generate content dynamically.
  > Allows for interactive features like form submissions, real-time updates and data fetching from database or API.

  # Date object
  > The Date object in javascript helps handle dates and times. It allows you work with dates and times, like finding out the current date and time.
  > Creating specific dates for your programs
  > Dynamic events
  > The date object in javascript offers methods starting with 'get' to access date components, returning associated numbers relative to the instantiated object. Correspnding to the 'get' methods, there are 'set' methods for modifying date components.
  Creating Date Objects
# Date objects are created with the new Date() constructor.

There are 9 ways to create a new date object:

new Date()
new Date(date string)

new Date(year,month)
new Date(year,month,day)
new Date(year,month,day,hours)
new Date(year,month,day,hours,minutes)
new Date(year,month,day,hours,minutes,seconds)
new Date(year,month,day,hours,minutes,seconds,ms)

new Date(milliseconds)

# Keyboard Events
The most significant keyboard events and the event handlers for them are listed below.

The Event of Keydown (onkeydown)

When a key on the keyboard is depressed, the keydown event is triggered. The onkeydown event handler can be used to manage the keydown event. You may see an alert message when the keydown event happens in the following example.
<input type="text" onkeydown="alert('You have pressed a key inside text input!')">
<text area onkeydown="alert('You have pressed a key inside text area!')"></text area>


```html
<!DOCTYPE html>
<html>
<head>
  <title>Keydown Event Example</title>
</head>
<body>

<p>Press any key and hold it down to trigger the alert.</p>

<script>
// Function to handle the keydown event
function handleKeyDown(event) {
  // Display an alert message when any key is pressed down
  alert("Key pressed down: " + event.key);
}

// Add event listener for keydown event
document.addEventListener('keydown', handleKeyDown);
</script>

</body>
</html>
```

In this example:

- We define a function `handleKeyDown(event)` to handle the keydown event.
- Inside this function, we use the `alert()` function to display a message indicating which key was pressed down. We access the key that was pressed using `event.key`.
- We add an event listener to the `document` object to listen for the keydown event. When the event occurs, the `handleKeyDown` function is called.

# The keyup Event(onkeyup)
Certainly! Below is an example of how you can use the `onkeyup` event handler in JavaScript to display an alert message when a key is released on the keyboard:
<input type="text" onkeyup="alert('You have released a key inside text input!')">
<textarea onkeypress="alert('you have pressed a key inside text area!')"></textarea>

```html
<!DOCTYPE html>
<html>
<head>
  <title>Keyup Event Example</title>
</head>
<body>

<p>Press any key and release it to trigger the alert.</p>

<script>
// Function to handle the keyup event
function handleKeyUp(event) {
  // Check if the key pressed is the Enter key (key code 13)
  if (event.keyCode === 13) {
    alert("You released the Enter key!");
  } else {
    alert("You released a key other than Enter!");
  }
}

// Add event listener for keyup event
document.addEventListener('keyup', handleKeyUp);
</script>

</body>
</html>
```

In this example:

- We define a function `handleKeyUp(event)` to handle the keyup event.
- Inside this function, we check if the key released is the Enter key (key code 13) or any other key, and display an appropriate alert message.
- We add an event listener to the `document` object to listen for the keyup event. When the event occurs, the `handleKeyUp` function is called.
 # The Keypress Event (onkeypress)
 <input type="text" onkeypress="alert('you have pressed a key inside text input!')">
 <textarea onkeypress="alert('you have pressed a key inside text area')"></textarea>

```html
<!DOCTYPE html>
<html>
<head>
  <title>Keypress Event Example</title>
</head>
<body>

<p>Press any key that has a character value associated with it to trigger the alert.</p>

<script>
// Function to handle the keypress event
function handleKeyPress(event) {
  // Display an alert message when a key with a character value is pressed
  alert("Key pressed: " + event.key);
}

// Add event listener for keypress event
document.addEventListener('keypress', handleKeyPress);
</script>

</body>
</html>
```

In this example:

- We define a function `handleKeyPress(event)` to handle the keypress event.
- Inside this function, we use the `alert()` function to display a message indicating which key with a character value was pressed. We access the pressed key using `event.key`.
- We add an event listener to the `document` object to listen for the keypress event. When the event occurs, the `handleKeyPress` function is called.

Note: As mentioned, certain keys like Ctrl, Shift, Alt, Esc, Arrow keys, etc., will not generate a keypress event.

# Form Event
When a form control gains or loses focus, or when a user modifies a form control value—for example, by entering text in a text input field or choosing any item in a pick box—a form event is triggered. 

The most significant form events together with associated event handlers are shown below.

The Event of Focus (onfocus)

When a person directs their attention to a web page element, this is known as the focus event. The onfocus event handler can be used to manage the focus event. When text input in the following example gains focus, its backdrop will be highlighted in yellow.
<!DOCTYPE html>
<html>
<head>
  <title>Focus Event Example</title>
  <style>
    .highlight {
      background-color: yellow;
    }
  </style>
</head>
<body>

<p>Click on the text input to see it highlighted.</p>

<!-- Text input field -->
<input type="text" id="textInput">

<script>
// Function to handle the focus event
function handleFocus() {
  // Add a class to highlight the background color
  document.getElementById("textInput").classList.add("highlight");
}

// Add event listener for focus event
document.getElementById("textInput").addEventListener('focus', handleFocus);

// Function to handle the blur event
function handleBlur() {
  // Remove the class to revert the background color
  document.getElementById("textInput").classList.remove("highlight");
}

// Add event listener for blur event
document.getElementById("textInput").addEventListener('blur', handleBlur);
</script>

</body>
</html>
<input type="text" id="textInput"> is our text input box.
We establish a CSS class.To make the backdrop color yellow, highlight it.
To handle the focus event, we define a function called handleFocus(). When the text input element has attention, we apply the CSS class highlight to it inside this method.
To manage the blur event, we define a function called handleBlur(). When the text input element loses focus, we remove the CSS class highlight from it inside this function.
For the focus and blur events on the text input element, we add event listeners. HandleFocus() is called when the input field becomes focused, and handleBlur() is called when it becomes non-focused.

# The blur event(onblur)
> The blur event occurs when the user takes the focus away from a form element or a window. You can handle the blur event with the onblur event handler. The following example will show you an alert message when the text input element loses focus.
* <input type="text" onblur="alert('Text input loses focus!')">
<button type="button">Submit</button>
* To take the focus away from a form element first click inside of it then press the tab key on the keyboard. You can handle the focus event with the onfocus event handler, gives focus on Something else, or click outside of it.

  # The Change Event (onchange)
  <!DOCTYPE html>
<html>
<head>
  <title>Change Event Example</title>
</head>
<body>

<p>Select an option from the dropdown to trigger the alert.</p>

<!-- Select box -->
<select id="selectBox">
  <option value="option1">Option 1</option>
  <option value="option2">Option 2</option>
  <option value="option3">Option 3</option>
</select>

<script>
// Function to handle the change event
function handleChange() {
  // Get the selected value from the select box
  var selectedValue = document.getElementById("selectBox").value;
  
  // Display an alert message with the selected value
  alert("Selected option: " + selectedValue);
}

// Add event listener for change event
document.getElementById("selectBox").addEventListener('change', handleChange);
</script>

</body>
</html>

*There are three alternatives in our select box, <select id="selectBox">.
To manage the change event, we construct a function called handleChange(). This function uses document.getElementById("selectBox").value to retrieve the selected value from the select box. It then displays the selected value in an alert message.
For the choose box element, we add an event listener for the change event. The handleChange() function is called when the value of the select box changes, and the selected choice is displayed in an alert message.

# The Submit Event (onsubmit)
<!DOCTYPE html>
<html>
<head>
  <title>Submit Event Example</title>
</head>
<body>

<form id="myForm">
  <!-- Input field -->
  <input type="text" name="name" placeholder="Enter your name">
  <!-- Submit button -->
  <button type="submit">Submit</button>
</form>

<script>
// Function to handle the submit event
function handleSubmit(event) {
  // Prevent the default form submission behavior
  event.preventDefault();
  
  // Display an alert message when the form is submitted
  alert("Form submitted!");
}

// Add event listener for submit event on the form
document.getElementById("myForm").addEventListener('submit', handleSubmit);
</script>

</body>
</html>
*
Our form, <form id="myForm">, has a submit button and an input field.
To handle the submission event, we define a function handleSubmit(event). This function uses event.preventDefault() to stop the form from being submitted to the server by overriding the default submission behavior.
Rather, we show an alert message letting you know that the form was sent in.
For the form element's submit event, we add an event listener. The handleSubmit() function is called and an alert message is displayed when the form is submitted.

# Document/Window Events
* Events are also started when the user resizes the browser window or the website loads, among other things. 

The most significant document/window events together with their event handlers are listed below.

The Onload Load Event

When a webpage has completed loading in the web browser, the load event takes place. The onload event handler can be used to manage the load event.
<body onload="window.alert('Page is loaded succefully!')">
<h1> This is a heading</h1>
<p> This is a paragraph of text</p>
</body>
