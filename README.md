# Automated CI/CD Pipeline for Flask Web Application

This project demonstrates a simple CI/CD pipeline for a Flask-based web application using Azure DevOps.

## Features
- Basic web application using Flask
- Docker containerization
- Automated CI/CD pipeline
- Deployment to Azure App Service

## Prerequisites
- Python 3.9+
- Docker
- Azure Account

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/Seema2005406/Automated-CI-CD-Pipeline-for-a-Web-Application.git

The application is a **basic web app** that serves a simple HTML page with a styled message, "Welcome to My Web App!" It uses **Flask**, a lightweight Python web framework, to create and serve this page. Here's what it does:

### **Key Features**:
1. **Single Route**: 
   - The app has only one route (`/`), which responds to HTTP GET requests.

2. **HTML Rendering**:
   - The `index.html` file is rendered when the route is accessed. It provides a simple webpage with a styled message.

3. **Static Files**:
   - A CSS file (`styles.css`) is included to style the webpage (e.g., center text and use a specific font).

### **How It Works**:
1. **User Visits the App**:
   - When a user accesses `http://localhost:5000` (locally) or the deployed Azure App Service URL, the Flask app processes the request.

2. **HTML Template is Rendered**:
   - Flask uses the `render_template` function to serve the `index.html` file.

3. **User Sees a Simple Page**:
   - The browser displays the HTML page with the message and basic styling.

---

### **Purpose of This Application**:
- The app's simplicity makes it an ideal starting point for:
  - **CI/CD Demonstrations**: Automating the build, test, and deploy processes.
  - **Dockerization**: Showcasing containerization and deployment on Azure.
  - **Scalability**: The structure can be extended to add more routes, services
