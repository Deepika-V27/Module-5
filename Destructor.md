# Exp.No:22  
## Destructor



### AIM  
To create a Python class `Student` with a destructor.



### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.



### PROGRAM

```
class student:
    def __init__(self):
        print("Inside Constructor")
        print("Object initialized")
        print("Hello, my name is Emma")
    def __del__(self):
        print("Inside destructor")
        print("Object destroyed")
s2=student()
del s2
```

### OUTPUT
![image](https://github.com/user-attachments/assets/57e2f976-0492-4f51-95d9-bd10c84cd8e1)


### RESULT
Thus the python program for Class Student with a destructor, was implemented and executed successfully.
