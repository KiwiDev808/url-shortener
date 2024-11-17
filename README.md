# URL Shortener

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

A serverless URL shortener built with AWS Lambda, DynamoDB, and React.

## Project Structure

```bash
url-shortener/
├── packages/
│   ├── frontend/     # React frontend application
│   ├── backend/      # AWS Lambda functions
│   └── shared/       # Shared types and utilities
├── docs/
│   ├── architecture/ # Architecture and design documents
│   └── setup/       # Setup and deployment guides
└── package.json     # Root package.json for monorepo
```

## 🚀 Features
- Shorten long URLs
- Custom URL slugs
- Analytics dashboard
- Secure and scalable
- Fast redirects

## 🛠️ Technologies
- Frontend: React, Tailwind CSS
- Backend: AWS Lambda, Node.js
- Database: DynamoDB
- Infrastructure: Serverless Framework
- CI/CD: GitHub Actions

## 📖 Documentation
- [System Design](./docs/architecture/system-design.md)
- [API Documentation](./docs/architecture/api-spec.md)
- [Installation Guide](./docs/setup/installation.md)
- [Deployment Guide](./docs/setup/deployment.md)

## 🏗️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/url-shortener.git