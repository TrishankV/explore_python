# Classes and Objects

In Python, almost everything is an object, each with its own properties and methods.

## Classes

A **class** in Python is like a blueprint or template for creating objects. It defines the properties and behaviors that objects of that class will have. 

```python
class Dog:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def bark(self):
        return "Woof!"

# Creating an instance of the Dog class
my_dog = Dog("Buddy", 3)
```
### self 
In Python, the self keyword is used to refer to the instance of the class (the object) itself. It is typically the first parameter in the definition of methods within a class, although it can technically be named differntly . 

## Objects

An object is an instance of a class. It is a concrete realization of the class blueprint, with its own unique state and behavior.


#### Accessing object properties
```python
print("My dog's name is", my_dog.name)
print("My dog's age is", my_dog.age)
```
 

#### Calling object methods
```python
print("My dog says", my_dog.bark())
```
