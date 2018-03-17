# ci-tdd-java-template
A little template used for explaining CI and TDD

# Introduction
This project is suppose to be used as a helper project when demonstrating and 
explaining continuous integration (CI), code coverage and test driven development (TDD).

The project uses Travis CI for building and the combination of Jacoco and CodeCov for code coverage.
All master branch merges must go through a pull request (PR) and each PR has multiple status checks.

The status checks required are the following:
1. Successful build from Travis CI
2. 100% code coverage, reported from CodeCov



# Assignment
The goal with this assignment is to create PR from the `develop` branch of a forked repository,
to the master branch of the main repository where all the status checks are approved.

In order to do that, the following tasks are required.

* Fork the repository
* Checkout the `develop` branch
* Do the coding task

## Coding
The coding task is very simple but should give a good feeling of the difference between
test driven development and regular unit testing. The coding task consists of implementing
one method which already has unit tests, write unit tests for an already implemented method
and finally implement both the method and write unit tests for one method.

**Note** that for the final implementation part, you can choose if you want to write the test
first or the functionality. 

The implementation part should be done in this order:
1. Implement `StringUtils.isPalindrome(final String str)`
2. Implement the tests for `Calculator.sumAll(final Integer... valuesPram)`
3. Implement both the tests and the functionality for `StringUtils.isBlank(final String str)`
    