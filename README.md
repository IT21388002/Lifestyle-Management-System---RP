
# Lifestyle Management System

**Project ID**: 24-25J-286  
**Developed By**: Hasamal M.A.P, Jayathissa K.A.D.S.S, Dhananjaya A.K.G.S, Dasanayaka D.M.U.H  

## Welcome
The Lifestyle Management System is a cutting-edge application designed to assist individuals aged 18-40 in managing daily life tasks, monitoring health levels, and minimizing stress. By leveraging modern technologies and wearables, this mobile application empowers users to achieve better health outcomes through personalized insights and recommendations.

---

## Table of Contents

- [Research Question](#research-question)
- [About the Project](#about-the-project)
- [Key Features](#key-features)
- [System Architecture](#system-architecture)
- [Technologies Used](#technologies-used)
- [System Requirements](#system-requirements)
- [Setup Instructions](#setup-instructions)
- [License](#license)

---

## Research Question

How can we develop a comprehensive system that provides personalized diseases diagnosis, stress management, diet plans and exercise schedules that take into a account medical conditions, dietary preferences and cultural factors to improve health outcomes for young adults ?

---

## About the Project

### Purpose
Health is essential, but many individuals struggle to maintain it due to their busy lifestyles. This system provides a holistic solution to help users:

- Identify health risks using real-time data from smartwatches and blood reports.
- Manage stress effectively.
- Follow personalized diet and exercise plans.

### Objectives
1. **Main Objective**  
   Develop a comprehensive mobile application for health management tailored to users aged 18-40.
   
2. **Specific Objectives**  
   - Identify health risks using OCR-based blood report analysis.
   - Generate exercise schedules based on BMI and calorie burn.
   - Provide meal plans considering user-specific health data.
   - Monitor and manage stress levels with suggestions and alerts.

---

## Key Features

### Health Risk Assessment - Hasamal M.A.P
- Analyze blood reports to identify risks for diseases like diabetes, cardiovascular conditions, and anemia.

### Personalized Meal Plans - Jayathissa K.A.D.S.S
- Generate tailored meal plans based on height, weight, and blood report data.

### Exercise Management - Dhananjaya A.K.G.S
- Create fitness schedules using BMI and caloric burn metrics.
- Monitor real-time data through smartwatches.

### Stress Management - Dasanayaka D.M.U.H
- Detect stress levels using user data.
- Offer actionable suggestions to reduce stress.

### User Dashboard 
- A single interface for monitoring all health metrics.
- Insights on diet, exercise, and stress.

---

## System Architecture

### Components
1. **Frontend**  
   - User-friendly interfaces for clients.
   
2. **Backend**  
   - FastAPI for seamless communication.
   - Machine learning models for predictions.
   
3. **Data Analysis**
   - OCR technology for extracting and analyzing blood report data.
   - Machine learning models including regression, SVM, and CNNs.

### Workflow
1. Input health metrics via smartwatch or manual upload.
2. OCR processes blood report data for analysis.
3. Backend predicts health risks and generates recommendations.
4. Results are displayed on the user dashboard.

### Diagram
![System Diagram](https://github.com/IT21388002/Lifestyle-Management-System---RP/raw/main/System%20Diagram.png)


---

## Tools & Technologies

### Frontend
- **Flutter**: Used for cross-platform UI development, primarily on Android (using Android Studio).

### Backend
- **Python (FastAPI)**: Primary backend framework for building RESTful APIs.
- **Node.js**: Potentially used for additional non-Python microservices or integration purposes.

### Database
- **Google Firestore**: Used as the NoSQL database for storing and managing application data.


## Machine Learning Models
- **Logistic Regression**
- **Random Forest**
- **Support Vector Machines (SVM)**
- **K-Nearest Neighbors (KNN)**


## Libraries

### Python
#### Machine Learning and Deep Learning
- TensorFlow
- PyTorch
- Scikit-learn
- Keras

#### Data Processing and Visualization
- Pandas
- NumPy
- Matplotlib
- Seaborn

#### Model Persistence
- Joblib

#### Text Processing
- PDFMiner.six (Text extraction from PDFs)
- EasyOCR (Optical Character Recognition)
- Autocorrect (Spell checking and correction)

#### Utilities
- bcrypt (Password hashing)
- Pillow (Image processing)

### JavaScript/Node.js
- Relevant libraries as needed, such as Express.js.


## Tools

### Development
- Google Colab (For data science and ML model development)
- VS Code
- Android Studio

### Version Control
- Git

### API Testing
- Postman

### Deployment
- Uvicorn (ASGI server for FastAPI applications)

### Dataset Management
- CSV files for handling data input and output

### Package Management
- pip (Python)
- npm (Node.js)

---

## System Requirements

### Functional
- Input and analyze health data from images or PDFs.
- Generate personalized recommendations.

### Non-Functional
- High accuracy for ML predictions.
- Fast response times.
- User-friendly interfaces.

---

## Setup Instructions

### Prerequisites
- Node.js and npm
- Python 3.x
- Google Firestore account
- Flutter and Android Studio setup
- Git

--- 

## License
