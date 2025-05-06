# GitHub Actions Demo Project

This project demonstrates the integration of GitHub Actions for continuous integration and deployment workflows in a React application.

## Project Overview

This is a simple React application built with Vite that showcases how to set up automated CI/CD pipelines using GitHub Actions. The application includes a basic UI with a toggle button to show/hide a help area.

## Features

- React-based UI with component structure
- Testing setup with Vitest
- GitHub Actions workflow for automated testing and deployment
- Vite for fast development and building

## Tech Stack

- React 18
- Vite
- Vitest for testing
- GitHub Actions for CI/CD

## Project Structure

```
.
├── .github/workflows      # GitHub Actions workflow configurations
├── public/                # Static assets
├── src/                   # Source code
│   ├── assets/            # Images and other assets
│   ├── components/        # React components
│   ├── test/              # Test files
│   ├── App.jsx            # Main App component
│   ├── main.jsx           # Entry point
│   └── index.css          # Global styles
├── .gitignore             # Git ignore configuration
├── index.html             # HTML entry point
├── package.json           # Project dependencies and scripts
└── vite.config.js         # Vite configuration
```

## GitHub Actions Workflow

The project includes a GitHub Actions workflow that:

1. Triggers on push events and manual dispatches
2. Runs automated tests
3. Deploys the application after successful tests

The workflow uses the following steps:
- Checkout code
- Set up Node.js environment
- Install dependencies
- Run tests
- Build the project
- Deploy to server (currently a placeholder)

## Getting Started

### Prerequisites

- Node.js (version 18 or later)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd github-actions-demo
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

### Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Builds the production-ready application
- `npm run preview` - Previews the built application
- `npm test` - Runs tests

## Deployment

This project is configured to deploy automatically using GitHub Actions. When code is pushed to the repository, the GitHub Actions workflow will run tests and deploy the application.