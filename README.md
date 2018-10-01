# "Head First Design Pattern" Notes

***Vocabulary:*** <br>
<strong> ***Participants*** </strong>:classes interacting with each other<br>
***Collaboration***: how classes interact with each other<br>
***Consequences*** -tradeoffs of choosing a particular design pattern<br>
***Implementation***- the solution part of pattern<br>
***Sample code***- how to use the pattern (not an implementation of the pattern)<br>
***Known uses***- examples of real usages of the pattern<br>
***Related patterns***-other patterns that have some relationship with the pattern;<br> 


***DESIGN PRINCIPLE***<br>
***Identify the aspects of your application that vary and separate them from what stays the same (static and dynamic stuff mixed, example- static html and ruby within static). This way you can alter or extend without affecting other parts***<br>
•	Basis of almost every design pattern- every instance variable must represent an object in the class<br>
•	A method should touch an instance variable because it keeps track of state with object<br>
•	Static methods (exception)<br>
•	Classes are independent of each other and don’t refer or modify eachother<br>
•	“They (classes) do one thing well and only one thing”<br>
•	Normalization (pull out the thing that varies)<br>
•	Creates more easily reusable objects<br>
•	Objects delegate parts of their behavior to other objects<br>


***DESIGN PRINCIPLE***<br>
***Application Program Interface-Program to an interface, not an implementation-care more about what the program does and how services can be obtained, NOT the inner workings (code)-What methods are public***<br>
•	Program to a supertype<br>
•	Java interface (a list of methods you can call)<br>
(Example, map is the supertype. Types -hash or concurrent hash map)<br>
•	Can better use polymorphism<br>
•	Can easily change implementation<br>


***DESIGN PRINCIPLE***<br>
***Favor composition over inheritance***<br>
•	Inheritance limits reusability- too much functionality<br>
•	Favor Has-a relationships (has an engine) over is-a relationship (is an engine)<br>

***OBSERVER PATTERN***<br>
Observer Pattern-defines a one-to-many dependency between objects so that when one object changes state, all of its dependents are notified and updated automatically. The subject is the sole owner of data. Cleaner OO design. One-to-Many relationships (subject-observers)
