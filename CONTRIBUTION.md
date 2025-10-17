# CONTRIBUTING GUIDELINES
Thank you for considering contributing to this project!  
Your help is greatly appreciated — whether it’s fixing a bug, improving documentation, or building new features.

## Table of Contents
- [CONTRIBUTING GUIDELINES](#contributing-guidelines)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [Development Workflow](#development-workflow)
  - [Commits \& Branches](#commits--branches)
    - [Commit messages](#commit-messages)
  - [Pull Requests](#pull-requests)
  - [Reporting Issues](#reporting-issues)
  - [Feature Suggestions](#feature-suggestions)

---

## Getting Started
1. **Fork** the repository and clone your fork:
    ```bash
    git clone https://github.com/Koaden/diary.git
    cd diary
    ```
2. Duplicate the environment file:
    ```bash
    cp .env.dist .env
    ```
    Then update configuration values as needed.
3. **Install dependencies** using Docker:
    ```bash
    make start
    ```

4. Open the app in your browser:
    ```
    http://localhost:8081   # mongo-express
    http://localhost        # symfony api
    http://localhost:3000   # website
    ```

## Development Workflow
- The backend runs on **Symfony** with **MongoDB**.  
- The frontend uses **React**  
- Use **Docker compose** to run all services (this ensures a consistent setup for every contributor).

## Commits & Branches
- **Main branch:** `main` — stable code only
- Create a **new branch** for each change
    ```bash
    git checkout -b feature/add-new-form
    ```

### Commit messages
Follow those methods : [Conventional Commit Messages](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)

## Pull Requests
1. Make sure your branch is **up to date with main**
2. Write clear **PR titles** and **descriptions**
3. **Sign** your commits
4. **Small PRs** are easier to review and merge
5. **Tests** are required for backend code

## Reporting Issues
If you encounter a bug, please open an issue and include:
- A clear **title** and **description**
- **Steps to reproduce**
- Expected vs. actual **behavior**
- **Environment** details (browser, OS, etc.)

## Feature Suggestions
**New ideas are always welcome!**

Before implementing a major feature, please open an issue or discussion to gather feedback.

Use the `enhancement` label for feature proposals.
