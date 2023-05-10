# Object-Oriented Programming

OOP ensures that code is clean.

OOP is centered around classes and objects.

## Sample Code

```
class Employee:
    def __init__(self, name, age, salary, position, department, marital_status): # placeholder
        self.name = name
        self.age = age
        self.salary = salary
        self.position = position
        self.department = department
        self.marital_status = marital_status #self age is attribute

    def add_age(self):
        self.age += 1

    def get_age(self):
        return "Age is {}". format(self.age)
```

## Pillars of OOP

- Encapsulation
- Inheritance
- Polymorphism
- Abstraction