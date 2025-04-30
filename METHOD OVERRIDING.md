# Exp.No:26  
## Method overloading

---

### AIM  
To define a Python class accessories that demonstrates operator overloading using the __add__() method to perform addition for both integers and string values using object instances.

---

### ALGORITHM

Define a class accessories with:

An __init__ method to initialize object data (X).

An __add__ method to overload the + operator so that two objects of this class can be added (using their X attributes).

Take two integer inputs from the user and create object_1 and object_2 using the accessories class.

Add the two objects using the overloaded + operator and display the result with the message "Rate is :".

Take two string inputs from the user and create object_3 and object_4 using the accessories class.

Add these two objects using the overloaded + operator and display the result with the message "accessories are:".

---

### PROGRAM

```
class accessories:  
    def __init__(self, X):  
        self.X = X  
   
    # adding two objects  
    def __add__(self, U):  
        return self.X + U.X  
object_1 = accessories( int( input()))  
object_2 = accessories( int( input()))  
print ("Rate is :", object_1 + object_2)  
object_3 = accessories(str( input()))  
object_4 = accessories(str( input()))  
print ("accessories are: ", object_3 + object_4)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/3f29f40e-2655-4903-afbc-14181467a2e9)

### RESULT
Thus the program Overloading have been executed and verified sucessfully.
