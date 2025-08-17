 🚀 DevOps Project — Flask App with Docker & Nginx

This repository demonstrates a practical DevOps project where a simple Python Flask web application is containerized with Docker and deployed behind an Nginx reverse proxy using Docker Compose.  
The project is designed to showcase core DevOps skills such as containerization, service orchestration, networking, and deployment on a Linux server.


 📌 Key Features

 🐳 Containerized Flask App — Packaged the Python Flask app into a Docker image for portability and consistency across environments.  
 🌐 Reverse Proxy with Nginx — Configured Nginx as a reverse proxy to handle incoming HTTP traffic on port 80 and route it to the Flask app running on port 5000 inside the container.  
 ⚙️ Multi-Container Orchestration— Used Docker Compose to manage multiple services (Flask app + Nginx) in a single configuration file.  
 🖥️ Deployment on Ubuntu — Successfully deployed and tested the setup on an Ubuntu server, making the application accessible via browser.  
 🔒 Separation of Concerns — Application logic (Flask) and traffic handling (Nginx) run in separate containers for cleaner architecture.  
 

🔧 Tech Stack

Flask — Lightweight Python web framework for building the app  
Gunicorn — Production-grade WSGI server for running Flask  
Docker — Containerization for portability  
Nginx — Reverse proxy & load balancing  
Docker Compose— Multi-container orchestration  
ubuntu — Deployment environment  

---

📂 Project Structure


my-flask-app/

├── app.py                                   
├── requirements.txt                      
├── Dockerfile                            
├── docker-compose.yml                       
└── nginx/
└── default.conf                                
