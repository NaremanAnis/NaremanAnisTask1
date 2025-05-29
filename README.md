#task1
# User Login System

## Overview

This repository implements a User Login System for a banking application using Git Flow branching methodology. The project demonstrates the process of feature development, conflict resolution, release management, hotfixes, and commit history debugging.

## Features

- User login functionality
- Case handling for different login scenarios
- Security fixes for vulnerabilities

## Technologies Used

- Git
- GitHub
- Bash (for command line operations)
- Text Editor (e.g., VSCode, Sublime Text)

## Git Workflow

This project follows the Git Flow branching model, which includes the following branches:

- **main**: The production-ready state of the application.
- **development**: The integration branch for features.
- **feature/login**: A feature branch for implementing the login functionality.
- **release/v1.0**: A branch for preparing a new release.
- **hotfix/security-fix**: A branch for applying urgent fixes.

### Git Commands Used

1. **Clone the repository**:
git clone https://github.com/NaremanAnis/NaremanAnisTask1.git
cd NaremanAnistask1

2.**Create branches**
git checkout -b main
git checkout -b development

3.**Add initial content**
echo "Initial content" > f1
git add f1
git commit -m "Add initial content to f1"

4.**Create feature branch**
git checkout -b feature/login

5.**Implement login functionality**
echo "Implement the login functionality" >> f1
git add f1
git commit -m "Implement the login functionality"

6.**Merge feature branch**
git checkout development
git merge feature/login --no-ff

7.**to delete the Feature Branch**
git branch -d feature/login

8.**create a release branch**
git checkout -b release/v1.0

9.**Create hotfix branch**
git checkout -b hotfix/security-fix

