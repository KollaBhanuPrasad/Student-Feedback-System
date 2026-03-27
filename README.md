# Student Feedback System

A web-based application designed to collect and manage student feedback efficiently.
This project also demonstrates modern DevOps practices using Docker, Jenkins, and Ansible.

---

## 🚀 Features

* Submit student feedback through a simple web interface
* Store and manage feedback data
* Clean and responsive UI
* Containerized using Docker
* Automated CI/CD pipeline using Jenkins
* Deployment automation using Ansible

---

## 🛠️ Tech Stack

* Python
* Flask
* HTML, CSS
* Docker
* Jenkins
* Ansible

---

## 📁 Project Structure

```
student-feedback-system/
│
├── app/              # Backend application code
├── templates/        # HTML files
├── static/           # CSS and static assets
├── ansible/          # Deployment scripts
├── Dockerfile        # Docker configuration
├── Jenkinsfile       # CI/CD pipeline configuration
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/KollaBhanuPrasad/Student-Feedback-System.git
cd Student-Feedback-System
```

---

### 2. Install Dependencies

```bash
pip install -r app/requirements.txt
```

---

### 3. Run Application

```bash
python app/app.py
```

Application will run on:

```
http://localhost:5000
```

---

## 🐳 Run Using Docker

### Build Docker Image

```bash
docker build -t student-feedback-app .
```

### Run Container

```bash
docker run -p 5000:5000 student-feedback-app
```

---

## 🔄 CI/CD Pipeline (Jenkins)

This project includes a **Jenkinsfile** that automates:

* Code build
* Docker image creation
* Deployment process

### Steps to Use:

1. Create a Pipeline in Jenkins
2. Select **Pipeline script from SCM**
3. Add your GitHub repository URL
4. Set script path: `Jenkinsfile`
5. Click **Build Now**

---

## 🚀 Deployment (Ansible)

* Ansible scripts are available in the `ansible/` directory
* Used for automated deployment and server configuration

---

## 📌 Future Enhancements

* Add authentication system
* Store feedback in database (MySQL / MongoDB)
* Dashboard for analytics
* API integration

---

## 👤 Author

**Kolla Bhanu Prasad**
Computer Science (AIML) Student

---

## 📄 License

This project is for educational purposes.
