🎯 Aim

The aim of this repository is to study and understand the special member functions in C++ that control the lifecycle of objects. These include:

Constructors – for automatic initialization of objects.

Copy Constructors – for creating safe copies of objects.

Destructors – for automatic cleanup of objects.

By experimenting with different .cpp files, we learn how objects are created, initialized, copied, and destroyed in a structured manner.

📚 Theory
🔹 Object Lifecycle in C++

In Object-Oriented Programming (OOP), every object follows a lifecycle: it is created, used, and then destroyed. C++ provides special functions to manage this lifecycle efficiently:

A constructor is automatically called when an object is created.

A copy constructor is called when a new object is made as a copy of an existing one.

A destructor is automatically called when an object goes out of scope or is deleted.

This automatic management ensures better memory safety, reliability, and control in programs.

🔹 Constructors 🏗️

A constructor is a special member function of a class, used to initialize objects.

Key Characteristics:

Same name as the class.

Called automatically at object creation.

No return type.

Types of Constructors:

Default Constructor – Initializes objects with default values.

Parameterized Constructor – Initializes objects with values provided by the user.

Copy Constructor – Initializes an object as a copy of another object.

Constructors simplify the process of object creation and ensure that all data members are given valid starting values.

🔹 Copy Constructors 📋

A copy constructor is a special type of constructor that creates a new object as an exact copy of another existing object.

When it is used:

When an object is passed by value to a function.

When a function returns an object by value.

When manually copying objects.

Importance:
Without a copy constructor, C++ performs a shallow copy, which may lead to multiple objects sharing the same memory location, causing errors. A proper copy constructor ensures a deep copy when needed, maintaining data integrity.

🔹 Destructors 🧹

A destructor is a special member function that is automatically invoked when an object’s lifetime ends.

Characteristics:

Same name as the class but preceded by a tilde ~.

Takes no arguments and returns nothing.

Each class has only one destructor.

Role:
Destructors are responsible for releasing memory, closing files, and cleaning up resources before the program ends or before the object is destroyed. They play a vital role in preventing memory leaks and ensuring efficient resource management.

🧩 Part A: Constructors

Demonstrates how constructors are defined inside and outside the class.

Shows the use of default constructors for automatic initialization.

Explains parameterized constructors for flexibility in object creation.

🧮 Part B: Copy Constructors

Explains how objects can be copied safely.

Highlights the difference between shallow copy and deep copy.

Shows how copy constructors prevent accidental data overwriting or corruption.

🧹 Part C: Destructors

Explains how destructors ensure automatic cleanup when objects go out of scope.

Shows their role in resource management and memory safety.

Reinforces the idea of automatic destruction without manual intervention.

🧠 Conclusion

From these programs, we understand the complete lifecycle of objects in C++:

✅ Constructors handle the creation and initialization of objects.

✅ Copy constructors allow safe duplication of objects.

✅ Destructors automatically release resources when objects are no longer needed.

Together, they form the backbone of Object-Oriented Programming in C++, making programs more reliable, structured, and easier to maintain. This experiment provides a foundation for advanced OOP concepts such as inheritance, polymorphism, and dynamic memory management.
