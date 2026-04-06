# Employee Management System (Spring Boot MVC)

## 📌 Project Overview

This project is a **basic Spring Boot MVC application** developed using **annotation-based configuration** (no XML).
It demonstrates the **MVC architecture** by accepting user input and displaying employee details.

The application allows users to:

* Enter an Employee ID
* Fetch employee details
* Display results using Thymeleaf views

---

## 🚀 Technologies Used

* Java 17+
* Spring Boot
* Spring MVC
* Thymeleaf
* Maven
* Embedded Tomcat Server

---

## 📂 Project Structure

```
Task_9
│── src/main/java/edu/Task_9
│   ├── Task9Application.java
│   ├── Employee.java
│   ├── EmployeeRepository.java
│   └── EmployeeController.java
│
│── src/main/resources
│   ├── templates
│   │   ├── home.html
│   │   └── employee.html
│
│── pom.xml
```

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/employee-management-system-springboot.git
```

### 2️⃣ Import into IDE

* Open **Eclipse / IntelliJ**
* Import as **Maven Project**

### 3️⃣ Run Application

* Open `Task9Application.java`
* Right-click → **Run As → Java Application**

### 4️⃣ Open Browser

```
http://localhost:8080/
```

---

## 🧪 Sample Inputs

| Employee ID  | Result                 |
| ------------ | ---------------------- |
| 101          | Shows employee details |
| 102          | Shows employee details |
| 103          | Shows employee details |
| Any other ID | "Employee not found"   |

---

## 📸 Output Screens

* Home Page → Enter Employee ID
* Employee Details Page → Shows data or error message

---

## ⚠️ Important Notes

* Ensure HTML files are placed in:

```
src/main/resources/templates/
```

* If port **8080 is already in use**, change it in:

```
src/main/resources/application.properties
```

Add:

```
server.port=8081
```

---

## 🎯 Features

* Annotation-based configuration (No XML)
* MVC architecture implementation
* Simple in-memory data storage
* Clean UI using Thymeleaf

---

## 📚 Learning Outcomes

* Understanding Spring Boot MVC flow
* Controller → Model → View interaction
* Handling user input using @RequestParam
* Using Thymeleaf templates

---

## 👨‍💻 Author

**Your Name**

---

## 📜 License

This project is for educational purposes.
