# Workshop for Hogeschool Windesheim - Countries of the World - Linear

## Introduction
Tests the functionality of naming all countries in the JetPunk country quiz.

This test automates the process of opening the browser, navigating to the JetPunk
"How many countries can you name?" quiz, and verifying that all countries can be
correctly entered and marked as correct answers.

### Steps
1. Arrange: Set up the Playwright environment and browser, and navigate to the quiz page.
2. Act: Accept cookie consent, start the quiz, retrieve all country names, and enter each country into the answer box. Close any popups that appear.
3. Assert: Verify that all entered countries are marked as correct.
4. Cleanup: Close the Playwright browser and environment.

## Prerequisites
* IntelliJ Community Edition (or any other IDE like Eclipse, Visual Studio Code, etc.)
* JDK 21

## Exercise
In `src/test/java/com/polteq/workshop/AllCountriesTest.java` you will find a template for the test.
But you will see that the selectors are missing. Please change all the blocks with `<Your selector here>` to the correct selector.
If all selectors are correct, you should be able to run the test and the test should pass.

Good luck!