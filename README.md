# E-commerce Automated Test Scripts
This repository contains reusable automated test scripts designed for end-to-end testing of e-commerce websites. These scripts help verify critical functionalities, such as adding items to the cart and completing purchase workflows, ensuring that the e-commerce website operates smoothly and provides a consistent user experience.

Overview
The scripts are structured to be easily maintainable and adaptable to changes in the website’s structure. The locators in the scripts are flexible and can be updated as the website evolves, making them robust against updates or modifications by the development team.

Key Features
Reusable Test Scripts: Structured to allow quick updates to locators, ensuring long-term usability.
End-to-End Scenarios: Covers essential e-commerce workflows such as product search, add-to-cart, checkout, and payment processing.
Easily Maintainable: Designed to allow quick adjustments to locator paths when the website structure changes.
Scalable for Regression Testing: Can be integrated into CI/CD pipelines for automated regression testing.
Structure
add_to_cart: Script for testing the "add to cart" functionality.
endToEnd S2/S3/S4: Comprehensive end-to-end scripts covering multiple user journeys on the website.
test_end2end5: Specific scenario tests for in-depth functionality verification.

Getting Started

Clone the Repository:
git clone https://github.com/kek005/e-commerce.git

Set Up Dependencies: Install Selenium or any other required testing libraries.
pip install selenium

Run the Tests: Execute the scripts for different scenarios.

Future Enhancements
Add More Scenarios: Expand test coverage to include other features like account creation, order history, and profile management.
Integration with CI/CD: Automate the test execution by integrating with CI/CD tools for continuous testing.
