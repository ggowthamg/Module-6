# Exp.No:30  
## POLYMORPHISM

---

### AIM  
The aim of this code is to demonstrate the concept of abstraction and polymorphism in object-oriented programming using Python.

---

### ALGORITHM

Define a class Cat:

Create a constructor __init__ with parameters name and age.

Store name and age as instance variables.

Define a method info() that prints the cat's name and age.

Define a method sound() that prints "Meow".

Define a class Cow:

Create a constructor __init__ with parameters name and age.

Store name and age as instance variables.

Define a method info() that prints the cow's name and age.

Define a method sound() that prints "Moo".

Create instances:

Create an object cat1 of class Cat with name "Kitty" and age 2.5.

Create an object cow1 of class Cow with name "Fluffy" and age 4.

Loop through both animals:

For each object in the tuple (cat1, cow1):

Call sound() to print the animal’s sound.

Call info() to print the animal’s name and age.

Call sound() again.

---

### PROGRAM

```
class Cat:
    def __init__(self, name, age):
        self.name = name
        self.age = age
 
    def info(self):
        # Add your code here
        print(f"I am a cat. My name is {self.name}. I am {self.age} years old.")
        
    def sound(self):
        print("Meow")
 
 
class Cow:
    def __init__(self, name, age):
        self.name = name
        self.age = age
 
    def info(self):
        print(f"I am a Cow. My name is {self.name}. I am {self.age} years old.")
 
    def sound(self):
        print("Moo")
        
cat1 = Cat("Kitty", 2.5)
cow1 = Cow("Fluffy", 4)
 
for animal in (cat1, cow1):
    animal.sound()
    animal.info()
    animal.sound()
```

### OUTPUT
![image](https://github.com/user-attachments/assets/6e576cd2-d807-4cdc-b4ae-5f338cdd45c4)


### RESULT
Thus the program Polymorphism have been executed and verified sucessfully.
