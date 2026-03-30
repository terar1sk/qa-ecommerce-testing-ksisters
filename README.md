![Manual Testing](https://img.shields.io/badge/Testing-Manual-blue)
![API Testing](https://img.shields.io/badge/API-Testing-green)
![Exploratory Testing](https://img.shields.io/badge/Testing-Exploratory-orange)
![Bug Reporting](https://img.shields.io/badge/Bug-Reporting-red)
![Chrome DevTools](https://img.shields.io/badge/Tools-DevTools-yellow)
![E-commerce Testing](https://img.shields.io/badge/Domain-Ecommerce-blueviolet)
![QA Portfolio](https://img.shields.io/badge/Project-QA_Portfolio-success)

# QA Testing Portfolio - Ksisters Website

## Project Overview
This project is a manual QA testing portfolio project for the website [ksisters.sk](https://ksisters.sk/).
The goal of this project is to practice real-world testing, improve QA skills, and demonstrate the ability to identify, analyze, and document software issues.
Testing was performed from a user perspective without access to backend logic or internal system data.

## Scope of Testing
The following parts of the website were tested:
* Search functionality
* Product pages
* Cart functionality
* Navigation (header and menus)
* Login form
* Registration (sign up)

## What Was Done
* Created a test plan
* Defined test scenarios
* Performed exploratory testing
* Identified and documented bugs
* Added screenshots and recordings as visual evidence

## Key Findings
During testing, several important issues were identified:
* Cart summary is not updated after removing the last item
* Registration returns 500 Internal Server Error for long input
* Raw validation errors are displayed in the UI
* Product page API returns 404 for static content
* Long user name breaks header layout

See full list in the [bug reports](./bug-reports/).

## Skills Demonstrated
* Manual testing
* Exploratory testing
* API testing (using DevTools)
* Bug reporting
* Test documentation (Test Plan, Test Scenarios, Summary)
* Edge case analysis

## Project Structure
```bash
.
├── bug-reports/
├── test-documentation/
│   ├── test-plan.md
│   ├── test-scenarios.md
│   └── summary.md
├── assets/
│   ├── screenshots/
│   └── recordings/
├── .gitignore
├── LICENSE
└── README.md
```

## Tools Used
* Google Chrome
* Chrome DevTools
* GitHub (for documentation)

## Notes
This is a personal QA testing project focused on real-world application testing.
The project demonstrates practical testing skills, including bug reporting, scenario design, and analysis of application behavior.

## Author
Dmytro Isai

## License
This project is licensed under the MIT License.