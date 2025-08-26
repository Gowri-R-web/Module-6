# Exp.No:27  
## Operator Overloading

---

### AIM  
To write a Python program to perform addition of two complex numbers using the binary '+' operator overloading. Class name: `Complex`, where the objects `Ob1 = Complex(1, 2)` and `Ob2 = Complex(2, 3)` represent complex numbers.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the Complex class**:
   - Define the constructor `__init__()` to accept two parameters: `real` and `imag` (representing the real and imaginary parts of the complex number).
   - Assign these values to `self.real` and `self.imag` respectively.
3. **Define the `__trueadd__()` method** to perform the addition of two complex numbers:
   - Calculate the real part of the result as the addition of `self.real` and `other.real`.
   - Calculate the imaginary part of the result as the addition of `self.imag` and `other.imag`.
   - Return a new Complex object with the calculated real and imaginary parts.
4. **Define the `__repr__()` method** to represent the complex number as a string.
   - Return a string formatted to display the real and imaginary parts using `f"{self.real}, {self.imag}"`.
5. **Create two objects of the Complex class**:
   - `Ob1 = Complex(1, 2)` represents the complex number `1 + 2j`.
   - `Ob2 = Complex(2, 3)` represents the complex number `2 + 3j`.
6. **Perform the addition operation**: Use the `+` operator to add `Ob1` and `Ob2`. This will call the `__trueadd__()` method.
7. **Print the result**: Print the result of the addition, which will be formatted by the `__repr__()` method.
8. **End the Program.**

---

### PROGRAM

```
# 212223060073
# Gowri Sankari R
class Complex:
    def __init__(self,a,b):
        self.a=a
        self.b=b
    def __add__(self,other):
        return other.a+self.a,other.b+self.b
obj1=Complex(1,2)
obj2=Complex(2,3)
obj3=obj1+obj2
print(obj3)
```

### OUTPUT
<img width="1188" height="258" alt="6E" src="https://github.com/user-attachments/assets/11f65822-3c19-496b-8f7c-395625369367" />

### RESULT
Thus a Python program to perform addition of two complex numbers using the binary '+' operator overloading. Class name: Complex, where the objects Ob1 = Complex(1, 2) and Ob2 = Complex(2, 3) represent complex numbers was successfully implemented and executed.


