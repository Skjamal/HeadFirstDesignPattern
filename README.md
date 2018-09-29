# "Head First Design Pattern" Notes

***Vocabulary:*** <br>
<strong> Participants </strong>:classes interacting with each other<br>
Collaboration: how classes interact with each other<br>
Consequences -tradeoffs of choosing a particular design pattern<br>
Implementation- the solution part of pattern<br>
Sample code- how to use the pattern (not an implementation of the pattern)<br>
Known uses- examples of real usages of the pattern<br>
Related patterns-other patterns that have some relationship with the pattern;<br> 
***FIRST DESIGN PRINCIPLE***<br>
***Identify the aspects of your application that vary and separate them from what stays the same (static and dynamic stuff mixed, example- static html and ruby within static). This way you can alter or extend without affecting other parts***<br>
•	Basis of almost every design pattern- every instance variable must represent an object in the class<br>
•	A method should touch an instance variable because it keeps track of state with object<br>
•	Static methods (exception)<br>
•	Classes are independent of each other and don’t refer or modify eachother<br>
•	“They do one thing well and only one thing”<br>
•	Normalization (pull out the thing that varies)<br>
•	Creates more easily reusable objects<br>
•	Objects delegate parts of their behavior to other objects<br>
