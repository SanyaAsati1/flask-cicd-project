# Flask CI/CD Pipeline — AWS EC2 + GitHub Actions

## What this project does
Automatically deploys a Flask web application to AWS EC2 whenever code is pushed to GitHub.

## Tech Stack
- Python, Flask
- AWS EC2 (Ubuntu)
- GitHub Actions (CI/CD)
- Systemd (process management)
- Bash Scripting, SSH

## How it works
1. Code pushed to GitHub
2. GitHub Actions triggers automatically
3. SSHs into AWS EC2 server
4. Pulls latest code + restarts Flask service
5. App is live on internet within 12 seconds

## Live Demo
http://23.22.188.232:5000
