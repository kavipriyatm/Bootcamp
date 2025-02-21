# Task 1: Class Creation (Dog Class)

## Overview
This task involved defining a `Dog` class in Python with attributes and methods for basic behaviors.

## What I Learned
- How to define a class using the `class` keyword.
- Implementing instance attributes using the `__init__` constructor.
- Creating and calling methods within a class.
- Instantiating objects and invoking their methods.

## Challenges Faced
- Ensuring correct initialization of instance attributes.
- Understanding the importance of `self` in method definitions.
- Structuring the class so that methods interact correctly with attributes.

## Final Thoughts
This task provided a foundational understanding of object-oriented programming (OOP) by implementing a simple `Dog` class with behaviors like `bark()` and `sleep()`.

---

# Task 2: Constructor Usage

## Overview
This task involved modifying the `Dog` class constructor to accept parameters dynamically and initializing attributes accordingly.

## What I Learned
- How to define a constructor (`__init__`) with parameters.
- Dynamically initializing instance attributes based on user input.
- Creating multiple instances with different attribute values.
- Printing or returning attribute values to verify correctness.

## Challenges Faced
- Ensuring attributes were correctly assigned from constructor parameters.
- Avoiding errors due to missing or incorrect arguments when creating objects.
- Validating that multiple instances retained their unique values.

## Final Thoughts
This task helped me understand how constructors work in Python and how they allow objects to be created with unique attribute values.

---

# Task 3: Inheritance (Puppy Class)

## Overview
This task demonstrates the concept of **inheritance** in Python by creating a `Puppy` class that inherits from the `Dog` class. The `Dog` class has attributes such as `name`, `age`, and `breed`, along with methods for barking and sleeping. The `Puppy` class extends `Dog` by adding additional behaviors like weeping and playing.

## What I Learned
- How to create a class and define attributes using `__init__`
- How to implement inheritance where a subclass (`Puppy`) inherits from a parent class (`Dog`)
- How subclass methods can extend parent class functionality
- How inherited attributes and methods work in Python

## Challenges Faced
- Ensuring that the `Puppy` class properly inherited the `Dog` class
- Structuring the `weep()` and `play()` methods correctly while maintaining inheritance
- Printing out inherited attributes to confirm the subclass retained parent class properties

## Final Thoughts
This task provided a solid understanding of **inheritance** in Python. The `Puppy` class successfully inherits the attributes and methods from `Dog`, while adding its own new methods. This concept is useful in real-world applications where multiple related classes share common functionalities.

---

# Task 4: Multiple Inheritance (Hybrid Class)

## Overview
This task explores **multiple inheritance** by creating a `Hybrid` class that inherits from both `Dog` and `Cat`. The `Dog` class provides behaviors like barking and sleeping, while the `Cat` class introduces meowing and purring. The `Hybrid` class combines these behaviors, demonstrating how multiple inheritance allows a class to inherit methods from multiple parent classes.

## What I Learned
- How **multiple inheritance** works in Python
- How a child class can inherit attributes and methods from multiple parent classes
- How Python resolves method conflicts using the **Method Resolution Order (MRO)**
- How to create a class that exhibits behaviors from different sources

## Challenges Faced
- Managing method conflicts when both parent classes have similar method names
- Understanding the execution order of inherited methods
- Structuring the `Hybrid` class to correctly inherit from both `Dog` and `Cat`

## Final Thoughts
This task deepened my understanding of **multiple inheritance** and its practical use cases. The `Hybrid` class successfully inherits behaviors from both parent classes, showing how different functionalities can be combined into a single class.

---

# Task 5: Encapsulation (Robot Class)

## Overview
This task focuses on **encapsulation** by implementing a `Robot` class with private (`__energy_level`) and protected (`_model`) attributes. Controlled access to these attributes is managed using getter and setter methods. Additionally, a `charge()` method modifies the energy level while maintaining data integrity.

## What I Learned
- The concept of **encapsulation** in Python
- How to use **private (`__`) and protected (`_`) attributes** to restrict direct access
- How to implement getter and setter methods for controlled attribute modification
- How encapsulation enhances **data security and integrity**

## Challenges Faced
- Understanding the difference between private and protected attributes
- Ensuring proper data access using getter and setter methods
- Handling attribute modification securely without breaking encapsulation

## Final Thoughts
Encapsulation is crucial for **data protection and access control** in object-oriented programming. This task helped me understand how to implement **controlled attribute access**, ensuring better security and maintainability in class design.

---

# Task 6: Polymorphism (Animal Class)

## Overview
This task demonstrates **polymorphism** in Python, where the same method `speak()` is defined in the base class `Animal` and overridden in the subclasses `Dog` and `Cat` to exhibit different behaviors.

## What I Learned
- **Polymorphism** allows objects of different classes to be treated as objects of a common superclass.
- **Method overriding** in subclasses provides different implementations of a method defined in the parent class.
- **NotImplementedError** is used in the base class to enforce that subclasses implement the method.

## Expected Output
- `animal_speak(dog)` will print **"Woof!"** as the output.
- `animal_speak(cat)` will print **"Meow!"** as the output.

## Challenges Faced
- Understanding how **polymorphism** allows the same method (`speak()`) to behave differently for different object types.
- The need to implement **abstract methods** (using `raise NotImplementedError`) in the base class to ensure subclasses define their own version of the method.
- Ensuring that each subclass implements the `speak()` method correctly for expected behavior.

## Final Thoughts
Polymorphism enables flexibility by allowing different classes to share the same method name but implement distinct behaviors. This task helped me understand how polymorphism works, especially the importance of method overriding in subclasses. It was a good exercise in recognizing how a single interface can be used for different types of objects, making code more maintainable and extensible.

---

# Overall Learning

- Gained a solid understanding of **object-oriented programming (OOP)** principles such as **inheritance, multiple inheritance, encapsulation,** and **polymorphism** in Python.
- Learned how to effectively use **constructors, methods**, and **class attributes** to manage data within classes.
- Developed a deeper appreciation for the flexibility and power of **inheritance** and **method overriding** in Python, as well as the importance of controlling data access with **encapsulation**.
