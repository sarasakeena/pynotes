---
title: Oop
date: 2025-06-29
author: Your Name
cell_count: 40
score: 40
---

```python
class Person:
    pass

```


```python
p1 = Person()
print(type(p1))

```

    <class '__main__.Person'>
    


```python
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    
```


```python
s1 = Student("Sara", 20)
print(s1.name, s1.age)

```

    Sara 20
    


```python
class Dog:
    def __init__(self, breed):
        self.breed = breed

    def bark(self):
        print("Woof! I am a", self.breed)

```


```python
d = Dog("Labrador")
d.bark()

```

    Woof! I am a Labrador
    


```python
class Book:
    def __init__(self, title):
        self.title = title

    def __str__(self):
        return f"Book: {self.title}"

```


```python
b = Book("Harry Potter")
print(b)

```

    Book: Harry Potter
    


```python
class Animal:
    def __init__(self, name):
        self.name = name

    def speak(self):
        print("I am an animal.")

```


```python
class Cat(Animal):
    def speak(self):
        print(f"{self.name} says Meow!")

```


```python
c = Cat("Luna")
c.speak()

```

    Luna says Meow!
    


```python
class Parent:
    def __init__(self):
        print("Parent init")
```


```python

class Child(Parent):
    def __init__(self):
        super().__init__()
        print("Child init")
```


```python
c = Child()
```

    Parent init
    Child init
    


```python
class Account:
    def __init__(self, balance):
        self.__balance = balance  # private

    def show_balance(self):
        print("Balance:", self.__balance)

```


```python
acc = Account(1000)
acc.show_balance()

```

    Balance: 1000
    


```python
class BankAccount:
    def __init__(self, name, balance):
        self.name = name
        self.__balance = balance

    def deposit(self, amount):
        self.__balance += amount

    def withdraw(self, amount):
        if amount <= self.__balance:
            self.__balance -= amount
        else:
            print("Insufficient funds")

    def show(self):
        print(f"{self.name} has ₹{self.__balance}")

```


```python
user1 = BankAccount("Sara", 5000)
user1.show()

```

    Sara has ₹5000
    


```python
user1.deposit(2000)
user1.show()

```

    Sara has ₹7000
    


```python
user1.withdraw(3000)
user1.show()

```

    Sara has ₹4000
    


```python
class MathOps:
    @staticmethod
    def add(a, b):
        return a + b

```


```python
print(MathOps.add(5, 7))

```

    12
    


```python
class Student:
    school = "CodeHigh"

    @classmethod
    def get_school(cls):
        return cls.school

```


```python
print(Student.get_school())

```

    CodeHigh
    


```python
class Calculator:
    def add(self, a: int, b: int) -> int:
        """Returns the sum of two numbers."""
        return a + b

```


```python
calc = Calculator()
print(calc.add(2, 3))

```

    5
    


```python
class Vehicle:
    def __init__(self, name):
        self.name = name

    def drive(self):
        print(f"{self.name} is driving.")

```


```python
class Car(Vehicle):
    def drive(self):
        print(f"{self.name} (car) is zooming!")

```


```python
class Bike(Vehicle):
    def drive(self):
        print(f"{self.name} (bike) is vrooming!")

```


```python
v = Vehicle("Generic")
v.drive()

c = Car("Suzuki")
c.drive()

b = Bike("Yamaha")
b.drive()

```

    Generic is driving.
    Suzuki (car) is zooming!
    Yamaha (bike) is vrooming!
    


```python
class Student:
    def __init__(self, name):
        self.__name = name

    def get_name(self):
        return self.__name

    def set_name(self, new_name):
        self.__name = new_name

```


```python
s = Student("Sara")
print(s.get_name())
s.set_name("Queen Sara")
print(s.get_name())

```

    Sara
    Queen Sara
    


```python
class Book:
    def __init__(self, title):
        self.title = title
        self.available = True

```


```python
class Library:
    def __init__(self):
        self.books = []

    def add_book(self, book):
        self.books.append(book)

    def show_books(self):
        for book in self.books:
            status = "Available" if book.available else "Issued"
            print(f"{book.title} - {status}")

    def issue_book(self, title):
        for book in self.books:
            if book.title == title and book.available:
                book.available = False
                print(f"{title} has been issued.")
                return
        print(f"{title} is not available.")

```


```python
lib = Library()
book1 = Book("Harry Potter")
book2 = Book("Sherlock Holmes")
lib.add_book(book1)
lib.add_book(book2)

```


```python
lib.show_books()

```

    Harry Potter - Available
    Sherlock Holmes - Available
    


```python
lib.issue_book("Harry Potter")
lib.show_books()

```

    Harry Potter has been issued.
    Harry Potter - Issued
    Sherlock Holmes - Available
    


```python
class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.salary = salary

```


```python
employees = [
    Employee("Sara", 70000),
    Employee("Ali", 65000),
    Employee("Afia", 72000)
]

for emp in employees:
    print(f"{emp.name} earns ₹{emp.salary}")

```

    Sara earns ₹70000
    Ali earns ₹65000
    Afia earns ₹72000
    


```python

```


---
**Score: 40**