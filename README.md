
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

### Health Risk Assessment
- Analyze blood reports to identify risks for diseases like diabetes, cardiovascular conditions, and anemia.

### Personalized Meal Plans
- Generate tailored meal plans based on height, weight, and blood report data.

### Exercise Management
- Create fitness schedules using BMI and caloric burn metrics.
- Monitor real-time data through smartwatches.

### Stress Management
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
   - RESTful APIs for seamless communication.
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
![System Architecture](path/to/system_architecture.png)

---

## Technologies Used

### Frontend
- **React.js**: Used for UI development.
- **CSS Frameworks**: Tailwind CSS or Material-UI for styling the frontend.

### Backend
- **Python (FastAPI)**: Primary backend framework for developing RESTful APIs.
- **Node.js with Express.js**: Assumed used for specific non-Python-based components or microservices, if any.

### Database
- **Google Firestore**: Used for NoSQL database storage.

### Libraries
#### Python
- **Machine Learning**:  
  - TensorFlow  
  - Scikit-learn  
  - Joblib (Model persistence)  

- **Data Processing**:  
  - Pandas  
  - NumPy  

- **Text Extraction**:  
  - PDFMiner.six  
  - EasyOCR  

- **Spell Checking and Corrections**:  
  - Autocorrect  

- **Utilities**:  
  - Pillow (Image processing)  
  - bcrypt (Password hashing)  

### Tools
- **Development**:  
  - VS Code  
  - Google Colab  

- **Version Control**:  
  - Git  

- **API Testing**:  
  - Postman  

- **Deployment**:  
  - Uvicorn (ASGI server)  

- **Dataset Management**:  
  - CSV files for loading and processing data  

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
- Git

--- 

## License
