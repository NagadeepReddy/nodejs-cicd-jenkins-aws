# nodejs-cicd-jenkins-aws
Production-Ready CI/CD Pipeline for Node.js with Jenkins on AWS EC2(End-to-End Automating)

**🚀 CI/CD Pipeline for Node.js with Jenkins on AWS**

Thrilled to share that I’ve successfully built and deployed a containerized Node.js application using Jenkins, Docker, GitHub, and AWS EC2! 💻☁️

This setup enables end-to-end automation — turning code commits into a running app in just minutes. 🐳✨

🔍 Project Overview
A complete CI/CD pipeline that builds, packages, and deploys a Node.js app in a Docker container — fully hosted on AWS EC2.

🔹 Use Case:
Automate build & deployment every time new code is pushed to GitHub.

🔄 Workflow Summary:
1️⃣ GitHub hosts the source code
2️⃣ Jenkins is triggered via webhook on each push
3️⃣ Jenkins pulls the latest code → builds Docker image → runs it
4️⃣ Docker runs the app in detached mode
5️⃣ AWS EC2 hosts everything with the following ports open:
 🔓 Port 8080 – Jenkins
 🌐 Port 8000 – Node.js App

✅ Key Benefits:

Fully automated pipeline from commit to deployment

Dockerized for portability and consistency

App remains live post-SSH session

Scalable, cloud-hosted on AWS EC2

📎 I’ve also documented every implementation step — great for anyone looking to learn CI/CD hands-on!

🛠️ Stack Used: Jenkins | Docker | GitHub | AWS EC2 | Node.js

This was an amazing hands-on experience applying real-world DevOps and Cloud deployment practices!
