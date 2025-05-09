# 🚀 Automated Static Website Deployment with DevOps Tools

This project demonstrates a beginner-friendly DevOps pipeline that automates the deployment of a static HTML website using Git, Docker, and CI/CD with GitHub Actions. The goal is to help learners understand the full lifecycle from code commit to live deployment.

## 🧱 Project Overview

- **Type**: DevOps Practice Project
- **Goal**: Deploy a static HTML website automatically using Docker and CI/CD
- **Tech Stack**:
  - Git (version control)
  - Docker (containerization)
  - GitHub Actions (CI/CD pipeline)
  - Optional Hosting: Render, Railway, or localhost

## 🛠 Features

- Simple and clean static HTML website
- Dockerized deployment environment
- Automated build and deployment on code push
- Lightweight, minimal, and educational setup
- Can be hosted for free using Render or Railway

## 📁 Project Structure

project-root/
├── .github/workflows/ # GitHub Actions CI/CD pipeline
│ └── deploy.yml
├── Dockerfile # Docker configuration for serving site
├── index.html # Static HTML site
└── README.md # Project documentation


## ⚙️ How It Works

1. **Development**: Edit your `index.html` file with desired content.
2. **Version Control**: Push changes to your GitHub repository.
3. **CI/CD**: GitHub Actions builds and (optionally) deploys your site using Docker.
4. **Deployment**: Serve the site locally via Docker or deploy to a free platform like Render.

## 🐳 Running Locally with Docker

# Build the Docker image
docker build -t static-site .

# Run the container
docker run -d -p 8080:80 static-site

# Visit http://localhost:8080 in your browser

📚 Learning Goals

 Understand how to containerize a simple app with Docker

 Learn CI/CD basics with GitHub Actions

 Get hands-on experience with automated DevOps workflows

 📄 License

This project is open-source and available under the MIT License.
