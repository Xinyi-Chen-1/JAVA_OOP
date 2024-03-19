*Java Object-Oriented Programming (OOP)
Java, as an object-oriented language, supports fundamental concepts including:

Polymorphism
Inheritance
Encapsulation
Abstraction
Class
Object
Instance
Method
Overloading
In this section, we will focus on the concepts of objects and classes.

Objects: An object is an instance of a class, possessing both state and behavior. For instance, a dog is an object with state attributes such as color, name, and breed, and behaviors like wagging its tail, barking, and eating.

Classes: A class serves as a blueprint describing the behavior and state of a category of objects.

Objects in Java
Now, let's delve deeper into what objects are. Observing the real world around us, we encounter numerous objects like cars, dogs, and people. Each of these objects possesses its own state and behavior.

Take a dog for example, its state includes attributes like name, breed, and color, while its behaviors encompass barking, wagging its tail, and running.

When comparing real-world objects with software objects, we find striking similarities. Software objects also exhibit state and behavior, where the state represents attributes and behavior is manifested through methods.

In software development, methods operate on the internal state of objects, and the interaction between objects is accomplished through method calls.

Classes in Java
A class can be seen as a template for creating Java objects. A class may contain the following types of variables:

Local variables: Defined within methods, constructors, or blocks. These variables are declared and initialized within the method and are automatically destroyed after method execution.
Instance variables: Variables defined within the class but outside of methods. These variables are instantiated when an object is created. Instance variables can be accessed by methods within the class, constructors, and specific class blocks.
Class variables: Variables declared within the class but outside of methods, which must be declared as static.
Constructor Methods: Every class has constructor methods. If a class doesn't explicitly define a constructor method, the Java compiler provides a default constructor method for it. When creating an object, at least one constructor method must be called. Constructor methods must bear the same name as the class, and a class can have multiple constructor methods.

Creating Objects
Objects are created based on classes. In Java, the keyword new is used to create a new object. Creating an object involves three steps:

Declaration: Declare an object, specifying its name and type.
Instantiation: Use the new keyword to create an object.
Initialization: When using new to create an object, the constructor method is called to initialize the object.
Accessing Instance Variables and Methods
Access member variables and member methods through the created object.
