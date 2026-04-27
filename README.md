# Learning CI/CD with GitHub Actions in Action

This repository is dedicated to learning and practicing **Continuous Integration and Continuous Delivery (CI/CD)** using the book **GitHub Actions in Action** (Manning Publications).

## About the Book

**GitHub Actions in Action** is a practical, hands-on guide that teaches you how to build robust CI/CD pipelines using GitHub Actions — from beginner to advanced level.

The book covers:
- GitHub Actions fundamentals
- Workflow syntax and best practices
- Jobs, steps, runners, and reusable workflows
- Building complete CI/CD pipelines
- Security, optimization, and advanced techniques

## Purpose of This Repository

- Store practical examples and exercises from the book
- Practice writing GitHub Actions workflows
- Build and experiment with real CI/CD pipelines
- Keep personal notes and improvements while learning

## Repository Structure
```plaintext
.
├── .github/
│   └── workflows/          # All GitHub Actions workflow files (.yml)
├── chapter-01/             # Examples & exercises from Chapter 1
├── chapter-02/             # Examples & exercises from Chapter 2
├── chapter-03/             # ...
├── globoticket/            # Full sample project from the book (if used)
├── docs/                   # Personal notes, summaries, and additional resources
├── scripts/                # Helper scripts (optional)
└── README.md
```


## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/github-actions-in-action-learning.git
   cd github-actions-in-action-learning
2. Read the book chapter by chapter
3. Try the examples in the .github/workflows/ folder
4. Push your code to GitHub and watch the workflows run automatically
5. Experiment by modifying workflows, adding jobs, secrets, caching, matrix strategies, etc.