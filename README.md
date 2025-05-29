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

### Git Commands Used:

1. **Clone the repository**:
1.1.git clone https://github.com/NaremanAnis/NaremanAnisTask1.git
1.2.cd NaremanAnistask1

2.**Create branches**
2.1.git checkout -b main
2.2.git checkout -b development

3.**Add initial content**
3.1.echo "Initial content" > f1
3.2.git add f1
3.3.git commit -m "Add initial content to f1"

4.**Create feature branch**
4.1.git checkout -b feature/login

5.**Implement login functionality**
5.1.echo "Implement the login functionality" >> f1
5.2git add f1
5.3.git commit -m "Implement the login functionality"

6.**Merge feature branch**
6.1.git checkout development
6.2.git merge feature/login --no-ff

7.**to delete the Feature Branch**
7.1.git branch -d feature/login

8.**create a release branch**
8.1.git checkout -b release/v1.0

9.**Create hotfix branch**
9.1.git checkout -b hotfix/security-fix

