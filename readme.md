🚀 DevOps Git Workflow Project
📌 Objective
The goal of this project is to simulate a real-world DevOps environment using Git and GitHub. It focuses on applying version control best practices such as branching strategies, pull requests, tagging, and documentation using markdown.

🧰 Tools Used
Git: For version control

GitHub: For repository hosting and collaboration

🛠️ Project Setup and Workflow
1. Repository Initialization
Created a local Git repository using git init

Pushed to a remote GitHub repository

2. Branching Strategy
main: Stable and production-ready code

dev: Integration branch for merged features

feature/*: Individual branches for each feature/task

3. Development Process
Each feature was developed in a separate feature/ branch

Changes were committed with clear messages

Pull Requests (PRs) were used to merge feature/* → dev

Final changes merged from dev → main using PRs

4. Versioning and Tags
Added a version tag (v1.0) to mark the initial release after merging into main

5. Ignored Files
Created a .gitignore file to exclude unwanted files like:

bash
Copy
Edit
node_modules/
.env
.DS_Store
*.log
6. Documentation
Added this README.md to describe the project

🧠 What I Learned
Effective branching and versioning strategies

Creating and managing pull requests

Conflict resolution and merge strategies

Git commands and real-world version control workflow

Importance of .gitignore and tagging
