# 🧑‍🎓 Spring Boot Student Management - CRUD API

A simple **Spring Boot REST API** for performing **CRUD operations** (Create, Read, Update, Delete) on a list of students using in-memory data structures. 

---

## 🛠️ Technologies

- Java 17+
- Spring Boot
- Spring Web
- Maven

---

## API Endpoints
##### 1. Display 'Hello SpringBoot!' message.(GET Method)
End point:
```
http://localhost:8080/app/msg
```

Response:
```
Hello Spring Boot!
```

Output:
<img width="959" alt="image" src="https://github.com/user-attachments/assets/569fd973-47d9-4876-8d3c-f9bf41ac3aa8" />





##### 2. Display age from user inserting value.(GET Method)
End point:
```
http://localhost:8080/app/age/25
```

Response:
```
My age is 25
```

Output:
<img width="959" alt="image" src="https://github.com/user-attachments/assets/668fe687-6922-4a4e-9643-d55f56388fe8" />





##### 3. Return a student.(GET Method)
End point:
```
http://localhost:8080/app/student
```

Response:
```
{
    "regNo": "2020ICT47",
    "name": "Maleesha",
    "age": 23,
    "course": "ICT",
    "gpa": 3.66
}
```

Output:
<img width="959" alt="image" src="https://github.com/user-attachments/assets/3a76b209-071f-4191-b489-275b02b7fef5" />





##### 4. Return multiple students.(GET Method)
End point:
```
http://localhost:8080/app/students
```

Response:
```
{
    "2020ICT95": {
        "regNo": "2020ICT95",
        "name": "Saduni",
        "age": 30,
        "course": "AMC",
        "gpa": 3.25
    },
    "2020ASB88": {
        "regNo": "2020ASB88",
        "name": "Nimna",
        "age": 23,
        "course": "BIO Sceince",
        "gpa": 4.0
    },
    "2020ICT56": {
        "regNo": "2020ICT56",
        "name": "Pabodha",
        "age": 21,
        "course": "IT",
        "gpa": 3.59
    },
    "2020CS31": {
        "regNo": "2020CS31",
        "name": "Ruwini",
        "age": 24,
        "course": "CS",
        "gpa": 3.8
    },
    "2020ICT47": {
        "regNo": "2020ICT47",
        "name": "Maleesha",
        "age": 23,
        "course": "ICT",
        "gpa": 3.66
    }
}
```

Output:
<img width="959" alt="image" src="https://github.com/user-attachments/assets/81118fc7-34ee-45c6-97a2-abef8eea1075" />





##### 5. Add a new student.(POST Method)
End point:
```
http://localhost:8080/app/add
```

Input:
```
{
    "regNo":"20201ICT58", 
    "name": "Nazik", 
    "age": 25, 
    "course": "ICT",
    "gpa": 3.96
}
```

Response:
```
New student added
```

Output:
<img width="959" alt="image" src="https://github.com/user-attachments/assets/1c3f8577-86a4-47b3-9424-21131962fe46" />





##### 6. Delete a student.(DELETE Method)
End point:
```
http://localhost:8080/app/students/2020BS85
```

Response:
```
Student Delete SuccessFully.
```

Output:
<img width="959" alt="image" src="https://github.com/user-attachments/assets/32158380-ca0f-41c5-a5ec-9b19d188d695" />





##### 7. Update a student.(PUT Method)
End point:
```
http://localhost:8080/app/update/2020ASP29
```

Response:
```
Update Successfully!
```

Output:
<img width="959" alt="image" src="https://github.com/user-attachments/assets/0a18d096-918f-43fa-b1ca-819fbd712f33" />

