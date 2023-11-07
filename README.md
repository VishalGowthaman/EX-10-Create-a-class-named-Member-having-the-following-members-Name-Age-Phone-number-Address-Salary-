# EX-10 Create a class named 'Member' having the following members(Name;Age;Phone number;Address;Salary);
# program
```
class Member {
    String name;
    int age;
    String phoneNumber;
    String address;
    double salary;

    void printSalary() {
        System.out.println(salary);
    }
}

class Employee extends Member {
    String specialization;
}

class Manager extends Member {
    String department;
}

public class Main {
    public static void main(String[] args) {
        Employee employee = new Employee();
        employee.name = "John";
        employee.age = 30;
        employee.phoneNumber = "123-456-7890";
        employee.address = "123 Main St";
        employee.salary = 50000.0;
        employee.specialization = "Software Development";

        Manager manager = new Manager();
        manager.name = "Alice";
        manager.age = 40;
        manager.phoneNumber = "987-654-3210";
        manager.address = "456 Oak Ave";
        manager.salary = 80000.0;
        manager.department = "HR";

        System.out.println("Employee details:");
        System.out.println("Name: " + employee.name);
        System.out.println("Age: " + employee.age);
        System.out.println("Phone number: " + employee.phoneNumber);
        System.out.println("Address: " + employee.address);
        System.out.print("Salary: ");
        employee.printSalary();
        System.out.println("Specialization: " + employee.specialization);

        System.out.println("\nManager details:");
        System.out.println("Name: " + manager.name);
        System.out.println("Age: " + manager.age);
        System.out.println("Phone number: " + manager.phoneNumber);
        System.out.println("Address: " + manager.address);
        System.out.print("Salary: ");
        manager.printSalary();
        System.out.println("Department: " + manager.department);
    }
}

```
# output
![image](https://github.com/Rohith-AIDS/class_MEMBER/assets/94980736/b8d8d0f7-b368-49cd-a2ff-fedfea1c7af6)
