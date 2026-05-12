````markdown
# Coursework

A modern software engineering coursework repository containing DevOps, cloud infrastructure, CI/CD workflows, containerization, and web application deployment configurations.

---

## 📌 Overview

This repository demonstrates practical implementation of modern software development and DevOps concepts including:

- Docker containerization
- CloudFormation infrastructure setup
- GitHub Actions workflows
- Static web application deployment
- SonarQube code quality integration
- CI/CD pipeline configuration

The project is designed for academic learning, cloud deployment practice, and software engineering coursework submission.

---

# 🚀 Features

- Dockerized application setup
- AWS CloudFormation template support
- GitHub Actions CI/CD workflows
- Static frontend application
- Automated build and deployment process
- Code quality analysis using SonarQube
- Infrastructure as Code (IaC)
- Version control using Git and GitHub

---

# 🛠️ Technologies Used

## Frontend
- HTML5
- CSS3
- JavaScript

## DevOps & Cloud
- Docker
- GitHub Actions
- AWS CloudFormation
- SonarQube

## Tools
- Git
- GitHub
- VS Code

---

# 📂 Project Structure

```bash
Coursework/
│
├── .github/
│   └── workflows/          # GitHub Actions workflows
│
├── Dockerfile              # Docker configuration
├── cloudformation.yaml     # AWS CloudFormation template
├── index.html              # Main web application page
├── sonar-project.properties # SonarQube configuration
└── README.md               # Project documentation
````

---

# ⚙️ Installation

## 1. Clone the Repository

```bash
git clone https://github.com/ikiranbc/Coursework.git
```

## 2. Navigate to Project Directory

```bash
cd Coursework
```

---

# ▶️ Running the Application

## Run Locally

Open the `index.html` file directly in your browser.

OR

Use a local development server:

```bash
python -m http.server 8000
```

Then open:

```bash
http://localhost:8000
```

---

# 🐳 Docker Setup

## Build Docker Image

```bash
docker build -t coursework-app .
```

## Run Docker Container

```bash
docker run -p 8080:80 coursework-app
```

Application will run at:

```bash
http://localhost:8080
```

---

# ☁️ CloudFormation Deployment

The repository includes an AWS CloudFormation template for infrastructure deployment.

## Deploy Stack

```bash
aws cloudformation create-stack \
--stack-name coursework-stack \
--template-body file://cloudformation.yaml
```

---

# 🔄 GitHub Actions

GitHub Actions workflows are configured inside:

```bash
.github/workflows/
```

These workflows may include:

* Automated builds
* Testing
* Deployment pipelines
* Code quality checks

---

# 📊 SonarQube Integration

The project includes SonarQube configuration using:

```bash
sonar-project.properties
```

## Run SonarQube Analysis

```bash
sonar-scanner
```

---

# 📖 Learning Objectives

This project demonstrates understanding of:

* CI/CD pipelines
* Docker containerization
* Infrastructure as Code
* Cloud deployment
* Version control workflows
* Static web hosting
* DevOps automation tools

---

# 📷 Screenshots

Add project screenshots here.

```markdown
![Application Screenshot](./screenshots/app.png)
```

---

# 👨‍💻 Author

## Kiran Budha Chetri

* GitHub: [https://github.com/ikiranbc](https://github.com/ikiranbc)

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Push to your branch
5. Open a Pull Request

---

# 📜 License

This project is developed for educational and academic purposes.

---


```
```
