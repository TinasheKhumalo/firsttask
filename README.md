


# Spring MVC Greeting App

A simple Spring Boot MVC application built for the Java Labs course at Vistula University. You can run it locally to display a personalized greeting message (via a URL parameter) and an image. The project follows the MVC pattern and uses Thymeleaf templates.

## ✅ Features
- Displays a greeting message using the `name` query parameter from the URL.
- Shows an image (vistula.png) in the view.
- Follows the MVC pattern using Thymeleaf templates.

## 🚀 How to run (you)
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spring-mvc-greeting-app.git
   ```
   Replace `your-username` with your GitHub username (or use the appropriate repo URL).
2. Open the project in IntelliJ IDEA as a Maven project.
3. Run the application:
   - From your IDE: run `DemoApplication.java`, or
   - From the command line:
     ```bash
     mvn spring-boot:run
     ```
4. Open your browser and visit:
   ```
   http://localhost:8080/greeting?name=YourName
   ```
   Replace `YourName` with the name you want to display.

## 📸 Screenshots
- PROGRAM OPERATION  
  !<img width="1917" height="1015" alt="home" src="https://github.com/user-attachments/assets/656b5ef8-a917-4e93-bd45-fc95f2b11c73" />


- Image displayed in the view  
  !<img width="1897" height="1029" alt="name2" src="https://github.com/user-attachments/assets/aab468e5-2aab-4fcb-ab69-98ef72c7aa50" />


(Ensure the image files `home.png` and `name2.png` are present in the repository root or update the image paths accordingly.)

## 🛠 Tech stack
- Java 17
- Spring Boot
- Spring MVC
- Thymeleaf
- Maven

---

