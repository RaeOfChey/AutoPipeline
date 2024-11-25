# AutoPipeline

### Status: In Progress

![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Tools and Technologies](#tools-and-technologies)
6. [Dependencies and Installs](#dependencies-and-installs)
7. [License](#license)
8. [Contributing](#contributing)
9. [Tests](#tests)
10. [Questions](#questions)

## Description
AutoPipeline is a GitHub Actions-powered CI/CD pipeline designed for MERN applications. It ensures quality with Cypress component tests when a Pull Request is made to the develop branch and automatically deploys the application to Render when code is merged from develop to main.

To view the application, simply navigate to the live website at https://autopipeline.onrender.com.

## Features
- Continuous Integration: Runs Cypress component tests on Pull Requests to develop.
- Continuous Deployment: Deploys the application to Render when develop merges into main.
- Customizable YAML configuration for flexibility.
- Secure integration with Render API via GitHub secrets.

## Installation
To use the application, follow these steps:

- Step 1: Clone the repository.
- Step 2: Navigate to the project directory by typing `cd AutoPipeline`.
- Step 3: Install the required dependencies by running `npm install`.

## Usage
To start the application, run the following command: `npm run start:develop`.

- Push changes to a feature branch and submit a Pull Request to develop.
- View Cypress test results in the GitHub Actions tab.
- Merge develop into main to trigger the deployment action.
- Verify the application is live on Render.

## Tools and Technologies
**Programming Language**:
- TypeScript

**Libraries & Frameworks**:
- React
- Express.js
- GitHub Actions

**Development Environment**:
  - MongoDB Atlas

## Dependencies and Installs

**NPM Packages**:
- `@apollo/client` - GraphQL client for the React front-end.
- `apollo-server-express` - Integrates Apollo Server with Express.js.
- `bcrypt` - Hashes user passwords for secure authentication.
- `jsonwebtoken` - Handles user tokenization for secure sessions.
- `mongoose` - ODM for MongoDB, managing schema and data validation.
- `cypress` - Runs the component tests.

**External Tools:**
- Render Deploy Hook
- GitHub Secrets

## License
This project is licensed under the MIT License, which allows you to freely use, modify, and distribute this software, provided proper attribution is given.

## Contributing
This project is part of a coding bootcamp assignment and is not open for contributions. To comply with the course requirements, I must complete this project individually without outside assistance. Therefore, pull requests, issues, or other contributions will not be accepted. Thank you for understanding!

## Tests
Currently, this project does not have any automated tests.

## Questions
If you have any questions about the repository, feel free to reach out by opening an issue or contacting me directly at cheyennaraelynn@gmail.com You can also find more of my work on GitHub at https://github.com/RaeOfChey.
