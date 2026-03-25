# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```
class Fish:
    def type(self):
        print("fish")
class Shark:
    def type(self):
        print("shark")
obj_goldfish=Fish()
obj_hammerhead=Shark()

for i in (obj_goldfish,obj_hammerhead):
    i.type()
```
## Output
<img width="537" height="252" alt="image" src="https://github.com/user-attachments/assets/a285ff3e-6a64-45d1-ae07-edb1d98e9751" />

## Result
Thus , the program has been executed successfully.
