# LogicsGen-Website-QA-11-Nov-2026
# LogicsGen Website – Manual QA Testing Project

**Project Date:** November 2026  
**Project Type:** Individual QA Portfolio Project  
**Testing Approach:** Manual UI Testing  
**Application Under Test:** [Tricentis Demo Web Shop](https://demowebshop.tricentis.com/)

## 1. Project Overview

This project demonstrates manual software testing of the Tricentis Demo Web Shop, an e-commerce practice application.

The purpose of this project was to understand the application's functionality, identify potential issues, verify important user workflows, and document testing results using standard QA practices.

The project was independently planned, designed, executed and documented as a QA portfolio project.

## 2. Testing Scope

The following application areas were covered:

- User Registration and Login
- Homepage and Navigation
- Search and Advanced Search
- Product Categories and Product Details
- Configurable Products
- Wishlist and Product Comparison
- Shopping Cart and Quantity Validation
- Guest and Registered Customer Checkout
- Order Confirmation
- Digital Downloads and Gift Cards
- Email a Friend and Newsletter
- Community Poll and Recently Viewed Products
- Responsive Viewport Exploration

Testing covered all seven product categories: Books, Computers, Electronics, Apparel & Shoes, Digital Downloads, Jewelry and Gift Cards.

## 3. Testing Approach

Manual testing was performed through the application UI using:

- Positive Testing
- Negative Testing
- Boundary Value Analysis
- Equivalence Partitioning
- Exploratory Testing
- Functional and UI Testing

## 4. Tools and Environment

| Item | Details |
|---|---|
| Application | Tricentis Demo Web Shop |
| Browser | Google Chrome 156.0.8078.80 (64-bit) |
| Operating System | Windows 11, Version 26H2 |
| Testing Type | Manual UI Testing |
| Responsive Exploration | Chrome DevTools – iPhone 16 viewport |
| Documentation | Microsoft Word and Excel |
| Repository | GitHub |

## 5. Project Deliverables

The project includes the following QA documents:

- **Test Plan** – Testing objectives, scope, approach and environment.
- **Requirement Analysis** – Functional requirements and business rules.
- **Test Scenarios** – High-level testing coverage.
- **Test Cases** – Preconditions, steps, test data and expected results.
- **Requirements Traceability Matrix (RTM)** – Mapping of requirements, scenarios and test cases.
- **Test Execution Results** – Actual results and execution status.
- **Bug Reports and Observations** – Potential issues, observations and testing limitations.
- **QA Test Report** – Summary of the completed testing project.
- **Lighthouse Report** – Recorded website audit results.

## 6. Key Findings

During testing, the following behaviours were recorded for further review:

- Some products displayed an In Stock label but did not show an Add to Cart option.
- Alphabetic characters were accepted in the checkout Phone Number field.
- Zero and negative cart quantities caused the selected product to be removed.
- Product image placeholders and stock-label differences were observed in the Accessories category.
- Different search results were returned for singular and plural keywords.

These findings were documented according to the available test expectations. Behaviours with unconfirmed expected rules were not automatically classified as confirmed defects.

## 7. Test Execution Summary

The test execution workbook records **91 Pass results and 9 Observation results** across 100 test cases.

Observation results were retained separately from Pass/Fail outcomes where the expected behaviour or requirement needed clarification.

## 8. Project Limitations

The following activities were outside the project scope or were not fully verified:

- API, database, automation and source-code testing.
- Performance, load and stress testing.
- Security and penetration testing.
- Real payment gateway or card transactions.
- Full cross-browser compatibility testing.
- Physical mobile-device and Safari testing.
- Email inbox delivery verification for Newsletter and Email a Friend.

Responsive exploration was performed using iPhone 16 viewport emulation in Chrome DevTools.

## 9. Important Note

This is an individual learning and portfolio project. Requirements and business rules were independently prepared from visible application features, observed workflows and reasonable test expectations. They are not official Tricentis specifications or stakeholder-approved requirements.

## 10. Project Status

**Status: Completed**

The project demonstrates the manual QA process from requirement analysis and test design through execution, traceability, issue documentation and reporting.

---

*Created as an individual QA portfolio project to demonstrate foundational manual software testing skills.*
