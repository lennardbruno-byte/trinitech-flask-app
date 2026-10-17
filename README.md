# Trinitech DevOps CI/CD Pipeline Project

## Chapter 4 — Flask Application

### Project Overview
This project demonstrates how to create, configure, test, and manage a Python Flask application as part of a DevOps CI/CD pipeline.

### Technologies Used
- Linux (RHEL/CentOS)
- Python 3
- Flask
- Git
- GitHub
- GitHub Desktop

### Application Features
- Flask web application
- Homepage endpoint (/)
- Health check endpoint (/health)
- HTTP 200 status verification
- Git version control

### Project Files
- app.py — Main Flask application
- requirements.txt — Python dependencies

### Installation
Install the application dependencies:

```bash
python3 -m pip install -r requirements.txt
```

### Run the Application
Start the Flask application:

```bash
python3 app.py
```

### Test the Application
Open another terminal and run:

```bash
curl http://localhost:5000/
curl http://localhost:5000/health
```

Expected homepage response:

Hello from the Trinitech DevOps Flask App!

Expected health check response:

{"status":"ok"}

### CI/CD Pipeline Architecture
Developer Workstation → GitHub → Jenkins → Docker → RHEL Deployment Server

### Chapter 4 Accomplishments
- Created Flask application
- Installed Flask dependencies
- Configured homepage and health check
- Tested application using curl
- Initialized Git repository
- Committed project files
- Published application to GitHub

### Next Phase
Integrate GitHub with Jenkins and Docker to automate application building, testing, and deployment.
