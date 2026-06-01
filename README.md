CV Web Application (MVC Project)

This is a Curriculum Vitae (CV) Form Web Application developed using Java (Jakarta Servlet 10), JSP, and Tailwind CSS following the MVC (Model-View-Controller) architecture.

Project Purpose
This project demonstrates the implementation of MVC architecture in a Java web application with proper separation of concerns between data, logic, and presentation layers.

Features
- CV form input page
- Dynamic CV generation
- Example CV page (hardcoded data)
- Image upload support
- Clean and responsive UI using Tailwind CSS

Technologies Used
- Java EE (Jakarta Servlet 10)
- JSP (JavaServer Pages)
- HTML5 & Tailwind CSS
- Apache Tomcat Server

MVC Structure
- Model: CV.java (stores CV data)
- View: form.jsp, cv.jsp (user interface)
- Controller: CVController.java (handles requests and logic)

How It Works
1. User fills in the CV form  
2. Form data is sent to the Controller  
3. Controller processes and stores data in a Model object  
4. Data is forwarded to JSP View  
5. CV is displayed in a structured format

Output Pages
- Form Page (user input)
- Generated CV Page
- Example CV Page (hardcoded data)
