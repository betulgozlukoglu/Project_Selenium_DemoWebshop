Selenium Web Store Test Automation
This repository contains Selenium tests for automating the user journey in a web store application. The tests are designed to ensure various user features are functioning as expected. Below is an overview of the test cases and how to run the tests.

Test Scenarios
1. User Registration
As a user, I should be able to register on the web store to make purchases and access other features.
2. Email Validation During Registration
As a user, if I try to register with the same email address that already exists, I should see an appropriate error message to improve user experience.
3. User Logout
As a user, I should be able to log out from the web store to ensure my shopping experience remains secure.
4. User Login
As a user, I should be able to log into the web store to manage my account details, shop for products, and access other features.
5. Negative Login Test Cases
As a user, I want to test various negative scenarios while logging in to ensure that the login mechanism is secure and handles invalid login attempts correctly.
6. Order Placement Using Credit Card
As a user, I should be able to place an order using my credit card details to purchase products.
7. Survey/Pool Voting
As a user, I should be able to vote in surveys like "Community Pool". If I am not logged in, I should see an error message saying "Only registered users can vote".
After voting, if I am logged in, I should be able to see a result page showing the answers, strengthening user engagement.
8. Handling Missing Coupons/Gift Cards
As a user, when I don't have a coupon or gift card during shopping, I should see an appropriate warning message, improving the shopping experience.
9. Viewing Order History and Invoice Download
As a user, I should be able to view my order history and download invoices for any of my orders, helping me track past purchases and get necessary documentation.
Prerequisites
Before running the tests, ensure the following dependencies are installed:

Java JDK (Version 8 or higher)
Maven (for dependency management and running tests)
Selenium WebDriver (included in the Maven dependencies)
ChromeDriver (or other browser drivers, based on your browser choice)
JUnit / TestNG (for test execution framework)
