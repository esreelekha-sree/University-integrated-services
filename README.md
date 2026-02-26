University Integrated Services

Project Overview
University Integrated Services is a web-based application designed to centralize and manage multiple university-related services on a single platform.  
The system aims to improve efficiency, accessibility, and transparency for students, faculty, and administrators.

This project is developed by combining Java-based web technologies with a Machine Learning module for intelligent processing.



Objectives
- To provide a unified platform for university services  
- To simplify academic and administrative processes  
- To improve user experience through centralized access  
- To reduce manual work and data redundancy  
- To enhance decision-making using Machine Learning techniques  



Technologies Used

 Frontend
- HTML  
- CSS  
- JavaScript  
- JSP  

 Backend (Web Application)
- Java  
- Servlets  
- Apache Tomcat  
- Maven  

 Machine Learning & API
- Python  
- FastAPI (ML microservice)
- TF-IDF (Term Frequency–Inverse Document Frequency)
- Cosine Similarity

 Database
- MySQL  

 Tools & Version Control
- Eclipse IDE  
- Git & GitHub  



 System Architecture
- Client–Server architecture  
- MVC (Model–View–Controller) design pattern  
- Java-based web application handles UI and business logic  
- Python-based FastAPI microservice handles Machine Learning processing  
- RESTful communication between Java application and ML service  



Machine Learning Component

The project integrates a Machine Learning module to provide intelligent similarity-based results and recommendations.

  ML Workflow
1. Textual data is collected and preprocessed  
2. Features are extracted using **TF-IDF Vectorization**  
3. Similarity between records is computed using **Cosine Similarity**  
4. The ML logic is exposed as REST APIs using **FastAPI**  
5. The Java web application consumes the ML API responses  

  Advantages
- Efficient handling of textual data  
- Improved accuracy in similarity matching  
- Scalable ML service using FastAPI  
- Separation of concerns using microservice architecture  



 Project Structure
University/
│── src/ # Java source files
│── WebContent/ # JSP pages and web resources
│── images/ # Application screenshots
│── pom.xml # Maven configuration
│── README.md # Project documentation



---

 Features
- User authentication and authorization  
- Student information management  
- Academic service integration  
- Admin management panel  
- Secure and role-based access  
- ML-based similarity and recommendation system  
- Intelligent text matching using TF-IDF and Cosine Similarity  

---

 Setup & Installation

 Prerequisites
- Java JDK 8 or above  
- Apache Tomcat 9 or 10  
- MySQL Server  
- Maven  
- Eclipse IDE  
- Python 3.x  

---

 Steps to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/sreelekha-sree/University-integrated-services.git
Import the project into Eclipse as a Maven Project

Configure Apache Tomcat in Eclipse

Set up the MySQL database and update credentials in the project

Start the FastAPI ML service

uvicorn main:app --reload


Run the Java project on the server

Access the application via browser:

http://localhost:8080/University

 Security

Role-based authentication

Input validation

Secure session handling
