Tuesday 03/30/2021
Afternoon Link: https://github.com/Toppedyk/vendr

What is the purpose of Encapsulation?
to organize data and the methods that act on that data such that access to that data is restricted from outside the bundle.

What were some of the problems with closures and the underscore prefix?
new developer may not know what it means. it can lead to breaking changes, can create dependencies that will break code if they are changed. 

How do we create private variables in a ES6 Class? Why would you do this?
by decalring it outside of the class that is exported and with a # or _, you use this to declare a variable that will stay local to the class and not be exported. you would do this with a function that has no user interaction such as draw.