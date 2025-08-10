# Yes Planet Website – Manual QA Project

This repository contains a **manual quality assurance (QA) project** performed on the Yes Planet cinema website.  
The goal of the project was to evaluate core functionalities of the site, identify defects, and provide structured documentation for test cases and results.

##  Project Overview
The project focused on testing key user journeys and functionalities, including:
- Changing cinema location on the website
- User registration and login
- Movie selection and ticket booking process
- Seat confirmation and payment flow

##  Repository Contents
- **Yes Planet Project.pdf** – Detailed STR (System Test Report) summarizing the execution of all test cases, pass/fail results, and defect descriptions.
- **STD Tables.xlsx** – Full STD (System Test Design) documentation containing all test cases, expected results, and execution outcomes.

##  Testing Scope
The tests covered **8 main STD tables**:

| Module                  | Total Test Cases | Passed | Failed |
|-------------------------|------------------|--------|--------|
| Change cinema location  | 8                | 5      | 3      |
| Registration form       | 12               | 10     | 2      |
| User login              | 9                | 8      | 1      |
| Movie selection         | 12               | 10     | 2      |
| Select ticket           | 14               | 10     | 4      |
| Reset password          | 5                | 5      | 0      |
| Confirm seats           | 12               | 12     | 0      |
| Customer details        | 11               | 11     | 0      |
| Payment form            | 15               | 15     | 0      |

##  Key Defects Found
Some examples of the most critical issues identified:
- Incorrect cinema search results when entering certain city names or postal codes.
- Registration allowed duplicate email addresses.
- UI layout issues due to missing input length limitations.
- Partial language translation on the login page.
- Calendar on movie selection page not functioning properly.
- Missing ID verification in ticket selection process.

##  Testing Methodology
- **Type:** Manual Testing
- **Approach:** Positive & Negative test scenarios
- **Documentation:** STD & STR based on ISTQB principles
- **Environment:** Desktop web browser testing


