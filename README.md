# Workflow CA

Workflow project at Noroff School of technology and digital media - Front End Development

This project aims to improve the quality of an existing social app by implementing better development workflows and establishing a strong testing strategy.

## Configuration

### Prettier

Prettier automatically formats the code, ensuring consistent styling, saving time on manual formatting, and enhancing code readability throughout the development workflow.

### ESlint

ESlint enforces coding standards, catches potential errors early, and maintains code quality, fostering consistency and collaboration in JavaScript development.

### Husky

Husky automates pre-commit hooks, ensuring code quality checks and preventing preventing commits that deviate from established standards.

### Jest

Implementing unit tests with Jest in this project ensures the reliability and correctness of individual code units, including testing the login and logout functions, facilitating early bug detection, and promoting robust software development practices.

### Cypress

Incorporating Cypress for end-to-end tests in this project validates the entire application workflow, including login and logout processes, ensuring seamless integration of components and instilling confidence in the overall functionality and user experience.

## Running instructions

### Installing

1. Clone the repo

2. Install dependencies

```
npm i
```

3. Build SASS

```
npm run build
```

### Running tests

Runs only Jest tests

```
npm run test-unit
```

Runs only Cypress tests

```
npm run test-e2e
```
