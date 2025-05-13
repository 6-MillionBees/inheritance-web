### P(redict)

Predict what the following code snippet will do:
```py
class Human:
    def __init__(self, name, age, occupation):
        self.name = name
        self.age = age
        self.occupation = occupation

    def think(self):
        print("The human is thinking deeply.")

    def communicate(self):
        print("The human is communicating clearly.")

class AI(Human):
    def __init__(self, name, age, occupation, intelligence_level):
        self.intelligence_level = intelligence_level
        super().__init__(name, age, occupation)

    def think(self):
        print("The A`perform_task()` online.")

    def communicate(self):
        print("The AI is communicating digitally with its human.")

    def learn(self):
        print("The AI is learning and improving its capabilities.")

my_ai = AI("Athena", 5, "Virtual Assistant", 9.8)
print(my_ai.name)
print(my_ai.age)
print(my_ai.occupation)
print(my_ai.intelligence_level)
my_ai.think()
my_ai.communicate()
my_ai.learn()
```
---

### I(nvestigate)

Answer these questions about the code snippet:

1. What is the relationship between the Human and AI classes?<br>
    The AI class is a child of the Human class
   
3. How does the `__init__()` method in the AI class use the `super()` function?<br>
    It uses the super() function to use the __init__() method of the parent class
   
5. How does the output of the `think()` and `communicate()` methods differ between the Human and AI instances?<br>
    They print different strings
      
7. Which attributes will the AI class get/grab from the Human class?<br>
    name, age, and occupation
    
8. Which attribute belongs specifically to the AI class?<br>
    intelligence_level
    
9. How many attributes **total** will an instance of the AI class have?<br>
    4

---
