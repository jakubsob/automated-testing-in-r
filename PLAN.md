# Part 1: Foundations of Testing

## What is a test?

## Why test?

- Two aspects of quality
- Ability to make change
- Regression
- Feedback loops
- Test as a playground

## When to test?

# Part 2: Practical Testing in R

## Testing Architecture

- The Testing Pyramid
  - Unit tests
  - Integration tests as specialized unit tests
  - Acceptance tests
- Commit-level tests and CI/CD pipelines
- Releaseability principles
-
## Unit Testing

### Anatomy of a Unit Test

### Types of Unit Tests

### Test First

### Test Last

    - Thinking about outcomes
    - Setting up inputs
        - Faking data
        - Tools like Copilot
    - Prototyping your interfaces
    - Writing effective assertions
        - Balancing specificity vs robustness
    - How to use {testthat}
        - test_that vs describe syntax
        - Writing meaningful test case titles
        - Arrange-Act-Assert and Given-When-Then patterns
        - Testing public interfaces only

## Acceptance Testing

### Anatomy of an Acceptance Test

- Four Layer Model: Focusing on your system
- Behavior-Driven Development (BDD) with {cucumber}
- Testing R packages and Shiny apps
    - shinytest2 vs Cypress/Playwright
    - PageObjects and Protocol Drivers

# Part 3: Specialized Testing

## Snapshot Testing

- When to use snapshots (and when not to)
- Capturing, managing, and reviewing snapshots
- CI workflows for snapshot testing

## Shiny Applications

- Unit testing Shiny components
- Testing Shiny modules
- Using `shiny::testServer` effectively
- Integration and end-to-end testing of Shiny apps

# Part 4: Optimizing Testing

## Optimizing for Fast Feedback

- Lessons from the Testing Pyramid
- Organizing files and test suites effectively

## Troubleshooting Testing Issues

- Handling intermittent tests
- Debugging with tests
- Addressing integration challenges
