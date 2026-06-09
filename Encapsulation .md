# 🐍 Python OOP: Encapsulation with Private Members

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
```
class area:
    def __init__(self,length,breath):
        self.__length=length
        self.__breath=breath
    def rectangle(self):
        print(self.__length)
        print(self.__breath)
a=area(5,3)
a.rectangle()

```
## Output
<img width="407" height="197" alt="image" src="https://github.com/user-attachments/assets/432a526d-5c9a-4e19-8262-c855d96e1817" />

## Result
Thus the program was successfully executed.
