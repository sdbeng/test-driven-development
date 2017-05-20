# Test-Driven Development
Web developers have different workflows for creating and maintaining projects. For example, when implementing responsive design, some developers will program "mobile-first" by starting with the mobile view and scaling up, while others will start with the desktop view and update as necessary on smaller and smaller screens.

In this article we will discuss a very popular development workflow called test-driven development (TDD). TDD allows developers to take time to specify what their projects should be able to do before writing any code. They then work their way through each feature and implement them one at a time, using the tests to verify that each feature works the way it was intended to.

## What are tests?
A test is a piece of code that checks to see if project code can complete a specific task. For example, a Go Fish app should have a test that makes sure that each player starts with seven cards. This test will start the game and check each player's hand. If a player doesn't have seven cards, the test will fail.

When a test fails, it returns a message to the developer explaining why that test failed. In the case of our Go Fish test, the test would return something like, "Each player should start the game with seven cards." A good test will describe the situation with the word "should", making it clear which part of your code is not working as intended.

In test-driven development, developers create these "should" statements for each feature of their project. They then write test code for each statement. Once all the tests are set up, developers will begin writing the code to make them pass.

A typical TDD workflow will look like this:

1. Run tests and select a failing test to fix.
2. Write code that should pass that test.
3. Run tests again. If selected test still fails, keep attempting to fix until test passes.
4. Select a new failing test and start over.

There are many benefits to using TDD:

* TDD causes developers to focus on what their app should do rather than coding without planning.
* TDD ensures that adding new features doesn't break old ones (old tests will fail if their corresponding features get broken).
* TDD makes it easy to identify where bugs have appeared in code through clear error messaging.

## How to run tests

## ee

## 44

##
