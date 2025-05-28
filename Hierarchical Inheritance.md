# Exp.No:25  
## Hierarchical Inheritance



### AIM  
To write a Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor`.


### ALGORITHM

1. **Begin the program.**
2. **Create a class Details** with an `__init__` method to initialize three attributes: `id`, `name`, and `gender`.
3. **Define a method display_details()** to print the values of `id`, `name`, and `gender`.
4. **Create a class Employee** that inherits from the `Details` class. 
   - Add two additional attributes: `company` and `department`.
   - Override the `display_details()` method to print the employee-specific attributes (`company` and `department`) along with the inherited details.
5. **Create a class Doctor** that also inherits from the `Details` class. 
   - Add two additional attributes: `hospital` and `department`.
   - Override the `display_details()` method to print the doctor-specific attributes (`hospital` and `department`) along with the inherited details.
6. **Accept input** for employee and doctor details.
7. **Create objects of Employee and Doctor** using the input.
8. **Call the `display_details()` method** for both objects to print the details.
9. **Terminate the program.**



### PROGRAM
```
def display_details(self):
    print(f"Id:  {self.id}")
    print(f"Name:  {self.name}")
    print(f"Gender:  {self.gender}")
def display_details(self):
    print("Employee Object")
    super().display_details()
    print(f"Company:  {self.company}")
    print(f"Department:  {self.department}")
def display_details(self):
    print("Doctor Object")
    super().display_details()
    print(f"Hospital:  {self.hospital}")
    print(f"Department:  {self.department}")
employee = Employee(employee_id, employee_name, employee_gender, employee_company, employee_department)
employee.display_details()
print("")
# Create Doctor object and display details
doctor_id = int(input())
doctor_name = input()
doctor_gender = input()
doctor_hospital = input()
doctor_department = input()

doctor = Doctor(doctor_id, doctor_name, doctor_gender, doctor_hospital, doctor_department)
doctor.display_details()

```

### OUTPUT  

![image](https://github.com/user-attachments/assets/d9751351-2b2a-49fb-82d6-33fad87acf4f)



### RESULT
Thus the python program for Hierarchical Inheritance to get the employee details was implemented and executed successfully.
