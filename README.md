# GitHub Actions CI/CD Demo

This is a mock CI/CD pipeline using GitHub Actions to simulate deploying a static web app to an EC2 instance.

## 🛠️ What It Does

- Triggers on push to `main`
- Simulates a build step
- Simulates SSH deploy to EC2 (no real EC2 used)
- Prints deployment steps to the GitHub Actions logs


github-actions-ci-cd-demo/
├── .github/
│   └── workflows/
│       └── main.yml       <-- GitHub Actions pipeline
├── app/
│   └── index.html         <-- Dummy static website
└── README.md              <-- Project explanation

