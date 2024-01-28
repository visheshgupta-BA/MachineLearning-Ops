# MLOps Foundation

## Overview
MLOps Foundation, a set of services designed to simplify Machine Learning Operations (MLOps) for data scientists and ML engineers. In collaboration with Craig Wiley, Director of Product Management, Cloud AI and Industry Solutions, they've created tools to help your business harness the power of AI efficiently.

## Key Requirements
As of September 1, 2020, McKinsey Global Institute predicts that companies fully embracing AI in their workflows by 2025 will experience a +120% cash flow growth by 2030. However, managing Machine Learning (ML) systems poses challenges such as technical debt, unique dependencies, and the need for continuous testing and validation.

## Services Overview
### AI Platform Pipelines
- Hosted offering for building and managing ML pipelines.
- Fully managed service available in preview by October, using TensorFlow Extended (TFX’s) pre-built components.
- Significantly reduces the effort required to deploy models.

### Continuous Evaluation
- Samples prediction input and output from deployed ML models.
- Analyzes model performance against ground-truth labels.
- Introduces human reviewers for data requiring human labeling.

### Continuous Monitoring
- Monitors model performance in production.
- Alerts for staleness, outliers, skews, or concept drifts.
- Expected availability to customers by the end of 2020.

### ML Metadata Management
- Tracks important artifacts and experiments.
- Provides a curated ledger of actions and detailed model lineage.
- Enables debugging, audit, or collaboration.
- Expected availability in preview by the end of September.

### Feature Store (Upcoming)
- Centralized repository of historical and latest feature values.
- Org-wide, promoting reuse within ML teams.
- Expected to boost productivity by eliminating redundant steps in feature engineering.
- Tooling to mitigate common causes of inconsistency between training and prediction features.

# Continuous Integration and Continuous Delivery (CI/CD)

## Overview
The world of Continuous Integration (CI) and Continuous Delivery (CD)! This README provides a quick overview of these essential practices in software development.

### Continuous Integration (CI)
- Imagine building a puzzle. Each developer is responsible for a piece of the puzzle.
- In software development, different developers work on different parts of the code (like pieces of a puzzle).
- CI is like putting the puzzle together regularly by combining code into a shared repository.
- The goal is to catch problems early, identifying and fixing issues that may arise when different code pieces come together.

### Continuous Delivery (CD)
- Now that we have our puzzle assembled, how do we make sure it gets to others?
- CD is like packaging the puzzle and putting it on a shelf, ready to be sent out (though not necessarily sent automatically).
- After integrating code (CI), the software is kept in a state where it could be released to users at any time.
- Continuous Deployment (a step beyond Continuous Delivery) is like automatically sending out the puzzle to others.

## Summing it up
- **Continuous Integration (CI):** Developers regularly combine their code to catch problems early.
- **Continuous Delivery (CD):** Code is always in a state where it could be released.
- **Continuous Deployment (CD - another meaning):** Code is not only ready but is automatically sent out.

## Why is this important?
- **Faster and Safer Development:** CI/CD helps developers work faster and catch mistakes early, making the development process smoother.
- **Reliable Releases:** Continuous Delivery ensures that the software is always in a release-ready state, making it easier to provide updates to users.

## In Summary
- **Continuous Integration (CI):** Regularly combining code to catch problems early.
- **Continuous Delivery (CD):** Code is always in a state where it could be released.
- **Continuous Deployment (CD - another meaning):** Automatically releasing the code.

CI/CD is like having a well-organized and efficient assembly line for building and delivering software!

