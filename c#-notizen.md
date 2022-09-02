<h1>C# Notizen</h1>

* C# is used to make interactive websites, mobile apps, video games, augmented and virtual reality (AR and VR), back-end services, and desktop applications

* .NET generally refers to the family of programs and commands that let you make applications with C#

* C# and .NET jobs are out there! Build video games with Unity, build websites with ASP.NET…The skills you learn on Codecademy can open new doors

* The command Console.WriteLine() prints text to the console

* The command Console.ReadLine() captures user input in the console

* Comments are lines of code that are ignored by your computer; they’re intended to be read by developers instead. Make them with // or /* and */

* int - whole numbers, like: 1, -56, 948

* double - decimal numbers, like: 239.43909, -660.01

* char - single characters, like: “a”, “&”, “£”

* string - string of characters, like: “dog”, “hello world”

* bool - boolean values, like: true or false

* Math.Abs()—will find the absolute value of a number. Example: Math.Abs(-5) returns 5.

* Math.Sqrt()—will find the square root of a number. Example: Math.Sqrt(16) returns 4.

* Math.Floor()—will round the given double or decimal down to the nearest whole number. Example: Math.Floor(8.65) returns 8.

* Math.Min()—returns the smaller of two numbers. Example: Math.Min(39, 12) returns 12.

<h2>Learn how to:</h2>

* Use arithmetic operators to write expressions.

* Combine operators together to write more concise programs.

* Use the modulo operator (%) to find remainders.

* Use built-in methods to do more complex math.

* Use documentation to look new things up.

* Save char and string values to a variable.

* Use the addition symbol (+) to concatenate strings.

* Interpolate strings for easier string construction.

* Find information about a string using .Length and .IndexOf().

* Grab characters and parts of strings using bracket notation and .Substring().

* Use built-in methods such as .ToUpper() and .ToLower() to manipulate strings.

<h2>Comparison operators include:</h2>

* Equals ==: returns true if the value to the left is equal to the value to the right.

* Inequality operator !=: returns true if the two values are not equal.

* Less than <: returns true if the value to the left is less than the value to the right.

* Greater than >: returns true if the value to the left is more than the value to the right.

* Less than or equal to <=: returns true if the value to the left is less than or equal to the value on the right.

* Greater than or equal to >=: returns true if the value to the left is more than or equal to the value to the right.

<h2>You learned:</h2>

* how to define variables with a bool data type

* how to use comparison operators with different data types to return boolean values

* what a truth table is and how to read one

* how to use logical operators to compare boolean values and expressions

* using if, else if, and else keywords to write conditional statements

* writing switch statements for situations where they are many condition

* using ternary operators for shorter conditional statements

* call a method with its name and parentheses: VisitPlanets();

* store a method’s returned value in a variable: double result = Math.Round(3.14159, 2);

* define a basic method with the following syntax: static void VisitPlanets() {}

* every time an application is started, the Main() method is called.

* Values passed to a method are called arguments. When defined in the method, they are parameters.

* Method parameters can only be used within the method body.

* Method parameters can be optional if given a default value using equals = syntax: static void VisitPlanets(int numberOfPlanets = 0)

* When calling a method, pass arguments by position or by name. If using names, use the colon (:) syntax: VisitPlanets(numberOfPlanets: 9);

* In method overloading, multiple methods can have the same name, as long as they have different method signatures.

* A method signature is a method’s name and parameter types in order.

<h2>You learned:</h2>

* Methods return values with the return keyword.

* Every method has a return type, designated in its method signature. That type must match the type of the value actually returned.

* If a method returns no type, its return type is void.

* out parameters can be used to return multiple values from a method.

<h3>Expression-bodied definitions can be used for one-line method bodies:</h3>

bool isEven(int num) => num % 2 == 0;

<h3>Lambda expressions can be used to create an anonymous method:</h3>


bool hasEvenNumbers = Array.Exists(numbers, (int num) => num % 2 == 0 );

<h2>You learned two “sub-shortcuts” within lambda expressions:<h2>

<h3>You can remove the parameter type if it can be inferred:</h3>


bool hasEvenNumbers = Array.Exists(numbers, (num) => num % 2 == 0 );

<h3>You can remove the parentheses if there is one parameter:</h3>

bool hasEvenNumbers = Array.Exists(numbers, num => num % 2 == 0 );