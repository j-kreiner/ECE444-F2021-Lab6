# ECE444 Lab 6: Test Driven Development

Name: Justin Kreiner

This repo is a clone of the following: https://github.com/mjhea0/flaskr-tdd


## Complete Application

Heroku Deployment: https://gory-broomstick-49038.herokuapp.com/


## Unit Tests in Education Pathways

Unit test added to project: https://github.com/ECE444-2021Fall/project1-education-pathways-group-6-tensiletech/commit/005382edb33547bb82f9d23c9eab737b90fea2cb

## Pros and Cons of Test Driven Development (TDD)

### Pros
- TDD results in your code being more modular and testable. When code is not modular, it is harder to write tests.
- It helps prevent defects later on. New features can be added and if they break old features it will show up in the tests.
- It improves the maintainability of the codebase. If something breaks, developers can refer to a testcase to see the expected behavior of the broken part.
- It minimizes the code that developers need to write, to deliver an MVP.

### Cons
- It may initially slow down progress by forcing you to write tests before delivering features. Since TDD improves maintainability, it saves developers time in the long term.
- Some features benefit more from integration tests, and it is hard to write these ahead of time
- It can result in unnecessary and redundant tests
- Sometimes the direction of a project/feature changes during development, and tests will need to be rewritten
