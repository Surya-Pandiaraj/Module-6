# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```
class Beans:
    def type(self):
        print("Vegetable")
    def color(self):
        print("Green")
class Mango:
    def type(self):
        print("Fruit")
    def color(self):
        print("Yellow")
def func(obj):
    obj.type()
    obj.color()
b = Beans()
m = Mango()
print("Beans:")
func(b)
print("\nMango:")
func(m)
```
## Output
![441159057-8c02a8d3-bb9d-4cfa-8e2c-024cb0b93875](https://github.com/user-attachments/assets/5ad3c1f0-2396-4ffd-9f2e-c4450e8e9cd2)
## Result
Thus,the python program Code Execution Successful
