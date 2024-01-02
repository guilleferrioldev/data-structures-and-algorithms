# Software Engineer Skills

### Algorithms, Data Structures and Design Patterns implemented in Python. Concepts of programming. 

### 1- Concepts
#### Generals:
- **Scope**: Refers to the scope or visibility that a variable has within a program. Defines where in the code a variable can be used and accessed. The scope of a variable can be global, meaning that it can be accessed from anywhere in the program, or local, meaning that it can only be accessed within a specific portion of the code, such as a function or a block of code.
- **Mutability**: Refers to the ability of an object to change or modify its state after its creation.
- **Parameter by reference**: It is a type of parameter in programming that allows a function to directly access and modify the value of a variable in memory, instead of operating on a copy of the value. This means that any modification made to the parameter by reference inside the function will directly affect the original value of the variable outside the function.
- **Parameter by value** : When a parameter by value is passed to a function, a copy of the actual value is passed to the function parameter. This means that any modifications made to the parameter inside the function will not affect the original value outside the function.
- **Serialization**: Refers to the process of converting an object or data structure into a format that can be stored or transmitted, and then reconstructed. It allows you to convert complex data into a form that can be saved or sent efficiently, and then restore it to its original form when necessary.

#### OOP
- **Generics**: Allow you to write code (classes, functions, interfaces) that can work with any type of data. Instead of specifying a specific data type, you can use a generic type that will be replaced by an actual type when the code is used. This makes the code more flexible and reusable. Ex: getitem and setitem in python allow the same behavior although generics do not exist as such.
- **Overloading**: Refers to the ability to have multiple methods or functions with the same name in the same class, but with different parameters. This means that you can have the same function with different behaviors depending on the parameters it receives.
- **Overriding**: Refers to the ability of a subclass (a class that inherits from another) to provide a specific implementation for a method that already exists in the base class. This means that the subclass can "replace" or "augment" or "override" the implementation of the method in the base class with its own implementation.
- **Abstraction**: It consists of identifying the main characteristics and behaviors of a real-world object and representing them in the code through a class.
- **Encapsulation**: It consists of hiding the internal details of an object and exposing only the operations or methods that can be used by other objects. This is accomplished by using access modifiers, such as public, protected, and private, which control the visibility of an object's attributes and methods.
- **Inheritance**: Allowing one class (called a child class or subclass) to inherit characteristics (attributes) and behaviors (methods) from another class (called a parent class or superclass).
- **Polymorphism**: It means that an object can take many forms. Allows an object to be treated as if it were a different type. It allows different objects to respond uniquely to the same messages.
- **Overloading polymorphism**: Refers to the ability of different classes to have methods with the same name but different implementations. When you call a method with a particular name, the compiler determines which method to execute based on the number and type of the arguments provided. In python it does not exist.
- **Inclusion polymorphism**: Refers to the ability of a base class to be used as if it were an instance of its derived classes. This means that an object of a base class can be treated as an object of any of its derived classes.
- **Abstract classes**: These are classes that cannot be instantiated directly, that is, objects cannot be created from them. Instead, they are used as templates for other classes that inherit from them. Abstract classes can contain normal methods (with implementation) and abstract methods (without implementation). Abstract methods must be implemented by subclasses that inherit from the abstract class.
- **Interfaces**: Defines a set of methods that a class must implement. Basically, an interface establishes a contract that classes must fulfill if they want to be considered the type of that interface.
- **Interaces vs Abstract Classes**: The main difference between an abstract class and an interface is that an abstract class can contain implementations of methods, while an interface cannot contain implementations and defines a set of methods that a concrete class must implement.
- **Static methods**: Also known as class methods, these are functions that belong to the class itself rather than to individual instances of the class. This means that you can call a static method without creating an instance of the class.
- **Virtual methods**: Also known as polymorphic methods, they are functions that can be overridden in derived classes (subclasses). In other terms, virtual methods allow a base class to provide an interface for derived classes to implement their own version of the method.
- **Non-virtual methods**: These are functions that cannot be replaced or overwritten in child classes or subclasses.
- **Mutator methods**: This type of method is used to change the internal state of an object, which means that it modifies the values ​​of the attributes of that object. In other words, a mutator method is responsible for changing the state of an object in some specific way based on logic defined within that method.
- **Class attribute**: It is a variable that belongs to the class itself, rather than belonging to a specific instance of the class. This means that the class variable is shared by all instances of the class.
- **Class method**: It is a function that is associated with a class. These methods are invoked on the class itself, rather than on a particular instance of the class.
- **Composition**: Refers to the technique in which objects are combined to form a more complex object. Instead of inheriting properties and behaviors from a parent class, an object can contain other objects as part of its internal structure. It is the creation of complex classes by combining simpler objects.

