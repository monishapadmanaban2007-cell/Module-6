# 🐍 Python OOP: Encapsulation with Private Members
## NAME: MONISHA P
## REF NO: 25018486
## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
class Rectangle:

    def __init__(self, length=5, breadth=4):
    
        self.__length = length       
        
        self.__breadth = breadth     

    def display(self):
    
        print("Length:", self.__length)
        
        print("Breadth:", self.__breadth)

rect = Rectangle()

rect.display()


## Output
Length: 5

Breadth: 4

## Result
The program successfully demonstrates encapsulation in Python by using private member variables __length and __breadth. The private members cannot be accessed directly from outside the class, but can be accessed through a class method.
