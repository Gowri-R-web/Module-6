# Exp.No:28  
## Abstraction

---

### AIM  
To write a Python program to define the abstract base class named `Polygon` and also define the abstract method. This base class is inherited by various subclasses. Implement the abstract method in each subclass. Create objects of the subclasses and invoke the `sides()` method.

---

### ALGORITHM

1. **Start the Program.**
2. **Import the ABC class** from the `abc` module to implement abstraction.
3. **Define the abstract base class Polygon**:
   - Inherit from `ABC` (Abstract Base Class).
   - Define an abstract method `sides()` with no implementation.
4. **Define the Triangle class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Triangle has 3 sides"`.
5. **Define the Pentagon class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Pentagon has 5 sides"`.
6. **Define the Hexagon class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Hexagon has 6 sides"`.
7. **Define the Square class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"I have 4 sides"`.
8. **Create an object `t` of the Triangle class** and call the `sides()` method to print the number of sides.
9. **Create an object `s` of the Square class** and call the `sides()` method to print the number of sides.
10. **Create an object `p` of the Pentagon class** and call the `sides()` method to print the number of sides.
11. **Create an object `k` of the Hexagon class** and call the `sides()` method to print the number of sides.
12. **End the Program.**

---

### PROGRAM

```
# 212223060073
# Gowri Sankari R
from abc import ABC, abstractmethod
class Polygon:
    def sides(self):
        pass
class Triangle(Polygon):
    def sides(self):
        print("Triangle has 3 sides")
class Square(Polygon):
    def sides(self):
        print("I have 4 sides")
class Pentagon(Polygon):
    def sides(self):
        print("Pentagon has 5 sides")
class Hexagon(Polygon):
    def sides(self):
        print("Hexagon has 6 sides")
t=Triangle()
t.sides()
s=Square()
s.sides()
p=Pentagon()
p.sides()
k=Hexagon()
k.sides()
```

### OUTPUT
<img width="1171" height="318" alt="6A" src="https://github.com/user-attachments/assets/036a1af6-be0b-428c-9e90-fbf8a2fa53ed" />


### RESULT
Thus a Python program to define the abstract base class named Polygon and also define the abstract method. This base class is inherited by various subclasses was successfully implemented and executed.
