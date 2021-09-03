A class is a user-defined blueprint or prototype from which objects are created. Classes provide a means of bundling data and functionality together. Creating a new class creates a new type of object, allowing new instances of that type to be made<br><br>
Syntax:<br>
class class_name:<br>
statements<br>
<img src="images/img1.PNG"><br><br>


<h4>How to define class objects</h4>
An Object is an instance of a Class. A class is like a blueprint while an instance is a copy of the class with actual values.<br>
An object consists of : <br>

State: It is represented by the attributes of an object. It also reflects the properties of an object.<br>
Behavior: It is represented by the methods of an object. It also reflects the response of an object to other objects.<br>
Identity: It gives a unique name to an object and enables one object to interact with other objects<br><br>

Syntax:<br>
Object_name.class_name()<br><br>
Program<br><br>
<img src="images/img2.PNG"><br><br>
Output<br><br>
graduate<br>
I'm a graduate<br>
I'm a student<br><br>
<b>The self</b>
Class methods must have an extra first parameter in the method definition. We do not give a value for this parameter when we call the method, Python provides it.<br>
If we have a method that takes no arguments, then we still have to have one argument.<br>
When we call a method of this object as myobject.method(arg1, arg2), this is automatically converted by Python into MyClass.method(myobject, arg1, arg2)<br><br>
__init__ method<br>
The __init__ method is similar to constructors in C++ and Java. Constructors are used to initializing the object’s state. It runs as soon as an object of a class is instantiated. The method is useful to do any initialization you want to do with your object.<br><br>
Program<br><br>
<img src="images/img4.PNG">
Output<br><br>
Hello, my name is John<br><br>
Class and Instance Variables:<br><br>
Class variables is a variable that is shared by all instances of a class. They are defined within a class but outside any of the class's methods.<br><br>
Instance Variable is a variable that is defined inside a method and belongs only to the current instance of a class.<br><br>
Program<br><br>
<img src="images/img5.PNG"><br><br>
Output<br><br>
myobj1 details:<br>
myobj1 is a student<br>
Breed:  Harry<br>
Color:  Physics<br>

Accessing class variable using class name<br>
student<br>


