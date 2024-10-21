# e-commerce-manual-testing

This project contains the manual testing results for a hypothetical e-commerce website. The goal is to showcase the ability to create a test plan, execute test cases, and log defects found during testing.

## Contents
- Test Plan
- Test Cases
- Bug Report

  # Test Plan

## Objective
To ensure that the core functionalities of the e-commerce website are working as expected through manual testing.

## Scope
- User registration and login
- Product search and filtering
- Adding products to cart
- Checkout and payment process
- Order confirmation

## Roles and Responsibilities
- Tester: [Your Name]
- Test Manager: [Your Name]
- Developer: [Optional]

## Test Deliverables
- Test Cases
- Bug Report
- Screenshots

## Entry Criteria
- E-commerce website is deployed and accessible for testing.

## Exit Criteria
- All high-priority test cases have been executed.
- All critical bugs have been fixed or logged.

## Risks
- Website performance issues.
- Inconsistent test environments.

# Test Cases for E-Commerce Website

| Test Case ID | Title                           | Steps                                                                                  | Expected Result                                            | Status |
|--------------|---------------------------------|----------------------------------------------------------------------------------------|------------------------------------------------------------|--------|
| TC001        | User Registration               | 1. Go to the registration page. 2. Fill in valid user details. 3. Submit the form.     | User is registered and redirected to the login page.        | Pass   |
| TC002        | User Login                      | 1. Navigate to the login page. 2. Enter valid credentials. 3. Submit.                 | User is successfully logged in and redirected to the homepage. | Pass   |
| TC003        | Product Search                  | 1. Enter a product name in the search bar. 2. Click "Search".                         | Relevant products are displayed.                           | Pass   |
| TC004        | Add Product to Cart             | 1. Select a product from search results. 2. Click "Add to Cart".                      | Product is successfully added to the cart.                 | Pass   |
| TC005        | Checkout Process                | 1. Navigate to cart. 2. Click "Checkout". 3. Enter payment and shipping details. 4. Confirm the order. | Order is confirmed and user receives an order confirmation.  | Pass   |
| TC006        | Invalid Login Attempt           | 1. Enter incorrect username/password. 2. Click "Submit".                             | Error message is displayed indicating invalid credentials.  | Pass   |


# Bug Report

| Bug ID | Title                      | Description                                                                      | Steps to Reproduce                                                         | Severity  | Status |
|--------|----------------------------|----------------------------------------------------------------------------------|-----------------------------------------------------------------------------|-----------|--------|
| BUG001 | Checkout Page Crash         | The website crashes when attempting to complete a purchase with PayPal.          | 1. Add item to cart. 2. Click checkout. 3. Select PayPal as payment option. | Critical  | Open   |
| BUG002 | Missing Search Results      | Searching for "headphones" returns no results even though the product exists.    | 1. Search for "headphones".                                                 | Major     | Open   |
| BUG003 | UI Overlap on Mobile        | The navigation bar overlaps with the logo on small screen sizes (iPhone 5).      | 1. Open the website on an iPhone 5.                                         | Minor     | Open   |

