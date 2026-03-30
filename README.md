Problem 1 — CI/CD Pipeline Automation

Tools: Jenkins, Docker, GitHub Actions

1.Pipeline Flow

Code pushed to GitHub
GitHub Actions runs tests + builds Docker images
Jenkins pulls and deploys via docker compose


2.GitHub Actions

Runs on every push to main
 1: Install → Test → Build Docker images
 2: Full integration test with docker compose


3.Jenkins

Pipeline defined in Jenkinsfile
Stages: Checkout → Install & Test → Build → Deploy
Access: 

4.CI/CD Links

GitHub Actions: https://github.com/Trackpulse828/CI-CD-Pipeline-Automation.git
Jenkinsfile: ./Jenkinsfile
