# Testing Summary - Ksisters Website

## Overview
The `ksisters.sk` website was tested using manual and exploratory testing.
The main focus was on search functionality, as well as basic user interactions such as navigation and cart.

## Issues Found
During testing, several issues were identified:
* Search allows empty input submission using the `Enter` key  
  ([View bug report](../bug-reports/search-returns-results-for-empty-query.md))

* Registration returns 500 Internal Server Error when name exceeds allowed length  
  ([View bug report](../bug-reports/signup-long-input-500-response.md))

* Raw validation error is displayed for invalid email input  
  ([View bug report](../bug-reports/registration-raw-email-validation-error.md))

* Raw validation error is displayed for invalid password input  
  ([View bug report](../bug-reports/registration-raw-password-validation-error.md))

* Cart summary is not updated after removing the last item  
  ([View bug report](../bug-reports/cart-summary-not-updated-after-removing-last-item.md))

* Product page static text request returns 404  
  ([View bug report](../bug-reports/product-page-static-text-404.md))

* Long user name breaks header layout  
  ([View bug report](../bug-reports/header-long-username-layout-break.md))

## Test Results
The main user flows of the website were tested, including search, registration, cart, and product pages.
Several functional and UI issues were identified during testing, especially in edge cases and input validation.
Most core features are working, but there are inconsistencies in error handling and UI behavior.

## Conclusion
The website provides core e-commerce functionality, but several issues were found related to validation, UI consistency, and error handling.
Improvements are needed in input validation, frontend-backend synchronization, and user experience in edge cases.
Overall, the system works for basic scenarios but requires fixes to ensure stability and better usability.