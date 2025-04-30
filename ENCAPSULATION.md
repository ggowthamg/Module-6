# Exp.No:29  
## Encapsulation

---

### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.
---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Student` class.**
   - Inside the `Student` class, define the `__init__` method to initialize `name` and the private member `__age`.
3. **Define a getter method** `get_age` to return the value of the private member `__age`.
4. **Define a setter method** `set_age` to set a new value to the private member `__age`.
5. **Create an object `stud`** of the `Student` class with the name 'Jessa' and age 14.
6. **Print the name and the age** of `stud` using the getter method.
7. **Use the setter method** `set_age` to change the age of `stud` to 16.
8. **Print the name and the updated age** of `stud` using the getter method.
9. **End the program.**

---

### PROGRAM

```
class Player:
    def __init__(self, name: str, player_number: int):
        self.__name = name
        self.__player_number = player_number
        
    def get(self):
        print(self.__name)
        print(self.__player_number)
        
    def set(self,b,c):
        print(b)
        print(c)
        
a = Player('Betty Ballmer',10)
a.get()
a.set('Buster Ballmer',11)

```

### OUTPUT
![image](https://github.com/user-attachments/assets/f4b7774d-6fae-4262-981a-a10d214b7569)

### RESULT
Thus the program Encapsulation have been executed and verified sucessfully.


