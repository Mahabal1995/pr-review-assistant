# PR Review Assistant

![Java](https://img.shields.io/badge/Java-17-blue) 
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen) 
![React](https://img.shields.io/badge/Frontend-React-blue) 
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## Overview
PR Review Assistant is an automated tool designed to simplify and speed up the pull request (PR) review process.  
It integrates with GitHub to:
- Fetch pull request details and code changes.
- Analyze code using static analysis tools (e.g., Checkstyle, ESLint).
- Optionally leverage AI (OpenAI GPT models) to generate PR summaries and improvement suggestions.
- Post automated feedback directly on GitHub PRs.
- Provide a dashboard to view PR review history and analytics.

---

## Features
- **Webhook-based PR event handling**
- **Static code analysis** for detecting common issues
- **Optional AI-powered suggestions** (via OpenAI API)
- **Automated PR commenting** with actionable feedback
- **Dashboard (React + Tailwind)** for PR review history

---

## Tech Stack
- **Backend:** Spring Boot (Java 17+)
- **Frontend:** React + Tailwind CSS (optional, for dashboard)
- **Database:** PostgreSQL (production) / H2 (development)
- **AI Integration:** OpenAI GPT-4 (optional)
- **CI/CD:** GitHub Actions, Docker

---

## Getting Started

### Prerequisites
- **Java 17+**
- **Maven 3+**
- **Node.js 18+** (for frontend)
- **GitHub Personal Access Token** (for GitHub API access)

- #Author
- Mahabal

### Clone the Repository
```bash
git clone https://github.com/Mahabal1995/pr-review-assistant.git
cd <repo-name>
