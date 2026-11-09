GitHub Usage & Workflow Guide

A concise guide on standard GitHub practices for cloning, branching, making changes, and managing pull requests.


🛠️ Prerequisites

- Git Installed: Verify by running `git --version` in your terminal.
- GitHub Account: Access to the target repository.
- SSH Key or Personal Access Token (PAT)**: Configured for authenticating pushed code.

 🚀 Quickstart Workflow
 
 1. Clone the Repository
Download a local copy of the repository to your machine:
bash
git clone [https://github.com/username/repository-name.git](https://github.com/username/repository-name.git)
cd repository-name

Update local main branch
git checkout main
git pull origin main

Create and switch to your feature branch
git checkout -b feature/your-feature-name
