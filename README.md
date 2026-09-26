# Express GitHub Actions

A simple Express.js project focused on learning and implementing **GitHub Actions**, **Continuous Integration (CI)**, and later **Continuous Deployment (CD)**.

## 🎯 Project Goal

The main goal of this project is to learn GitHub Actions through a real Express.js application and gradually build a complete CI/CD pipeline.

## 🛠️ Technologies

* Node.js
* Express.js
* Git
* GitHub
* GitHub Actions

## 📁 Project Structure

```text
express-github-actions/
├── .github/
│   └── workflows/
│       └── ci.yml
├── src/
├── package.json
├── package-lock.json
└── README.md
```

## ⚙️ GitHub Actions

The current CI workflow runs automatically when code is pushed to the `main` branch.

The workflow performs the following steps:

1. Checkout the repository
2. Setup Node.js 20
3. Install dependencies with `npm ci`
4. Run tests
5. Build the application

### CI Workflow

```text
Push to main
     ↓
Checkout repository
     ↓
Setup Node.js
     ↓
Install dependencies
     ↓
Run tests
     ↓
Build application
     ↓
CI completed
```

## 🚀 Run Locally

Clone the repository:

```bash
git clone <your-repository-url>
cd express-github-actions
```

Install dependencies:

```bash
npm install
```

Run the application:

```bash
npm start
```

Run tests:

```bash
npm test
```

## 🔮 Future Goals

* Improve CI workflow
* Add pull request checks
* Add environment variables and secrets
* Add GitHub Environments
* Implement Continuous Deployment (CD)
* Add Docker
* Build a complete production deployment pipeline

## 📚 Purpose

This repository is primarily a **learning and practice project** for GitHub Actions and DevOps concepts using an Express.js application.
