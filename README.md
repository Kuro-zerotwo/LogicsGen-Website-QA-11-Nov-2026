# LogicsGen Website – QA Testing Project

**Project Date:** 11 November 2026  
**Project Type:** Individual QA Portfolio Project  
**Testing Approach:** Manual Functional and Responsive Testing  
**Website:** [https://logicsgen.com/](https://logicsgen.com/)

## 1. Project Overview

This project involved manual testing of the LogicsGen website to check its main pages, navigation, forms, input validation, user interactions and responsive behaviour.

The objective was to verify important website functions, identify issues, document actual results and evaluate selected website quality metrics using Google Lighthouse.

Testing was performed across desktop Chrome, a physical Redmi 13 mobile phone and Chrome DevTools responsive emulation.

## 2. Testing Scope

The following areas were tested:

- Homepage loading and navigation
- Services dropdown and service links
- Courses listing and category pages
- About Us, Contact Us and Blogs pages
- Contact form validation and submission
- Course enquiry form validation and submission
- Name, email and phone number validation
- Message character limit
- Blog Read More links
- Course and blog navigation buttons
- Browser Back and Forward navigation
- Mobile menu and responsive layout
- CAPTCHA interaction in responsive emulation

## 3. Testing Approach

The project used the following manual testing techniques:

- Functional Testing
- Positive Testing
- Negative Testing
- Form Validation Testing
- Boundary Value Testing
- Navigation Testing
- Responsive UI Testing
- Exploratory Testing

## 4. Tools and Test Environment

| Item | Details |
|---|---|
| Website | LogicsGen |
| Browser | Google Chrome 156.0.8078.80 (64-bit) |
| Desktop OS | Windows 11 |
| Physical Mobile | Redmi 13 |
| Responsive Testing | Chrome DevTools – 768 × 1024 |
| Performance Audit | Google Lighthouse 13.5.0 |
| Documentation | Microsoft Word and PDF |
| Repository | GitHub |

## 5. Test Execution Summary

A total of **20 manual test scenarios** were recorded as Passed in the tested environments.

Three additional findings were documented separately:

| Finding ID | Description | Severity / Classification | Status |
|---|---|---|---|
| LG-QA-001 | Suggested course cards lead to the same incomplete course page. | High | Open – Reproduced |
| LG-QA-002 | Explore All Blog Posts button redirects to the Courses page instead of the Blogs page. | High | Open – Reproduced |
| LG-QA-003 | CAPTCHA could not be clicked in Chrome DevTools responsive emulation at 768 × 1024. | Low | Needs verification |

The CAPTCHA behaviour was observed in responsive emulation but worked in normal desktop Chrome and on the physical Redmi 13. Physical tablet verification is still required.

## 6. Lighthouse Audit Results

A Lighthouse audit was performed on the LogicsGen homepage using Mobile Navigation mode and Slow 4G network simulation.

| Category | Score |
|---|---:|
| Performance | 62 |
| Accessibility | 93 |
| Best Practices | 77 |
| SEO | 100 |

### Key findings

- **Performance:** Opportunities to improve image delivery, JavaScript execution, unused CSS and JavaScript, and render-blocking resources.
- **Accessibility:** Colour contrast and touch-target size or spacing need improvement.
- **Best Practices:** One deprecated API warning and issues in the Chrome DevTools Issues panel.
- **SEO:** The homepage received a score of 100.

This was a mobile audit of the homepage only, not a full website audit.

## 7. Project Deliverables

The repository contains the following project reports:

- **QA Test Report:** Manual testing scope, test results, findings, evidence and recommendations.
- **Lighthouse Report:** Mobile homepage audit scores, performance metrics and audit findings.

## 8. Project Limitations

The following areas were not fully verified:

- Actual enquiry email delivery and backend receipt.
- CAPTCHA behaviour on a physical tablet.
- Lighthouse audits for other website pages.
- A separate desktop Lighthouse audit.
- Full cross-browser compatibility.
- Complete website coverage across all devices and screen sizes.

Successful form notifications were observed, but they do not confirm actual email delivery or backend receipt.

## 9. Recommendations

The main recommended actions are:

1. Correct the suggested course-card destinations and incomplete course page.
2. Fix the Explore All Blog Posts button destination.
3. Verify CAPTCHA on a physical tablet or another supported tablet browser.
4. Confirm enquiry submission through the receiving inbox or backend.
5. Improve Lighthouse performance and best-practice findings.
6. Perform retesting after the reported issues are corrected.

## 10. Project Status

**Testing Status: Completed**

The documented manual testing and Lighthouse audit were completed on 11 November 2026. Three findings remain outstanding and require correction or further verification.

This project demonstrates practical QA activities, including test execution, validation testing, responsive checks, defect documentation, evidence collection and reporting.

---

*Individual QA portfolio project – LogicsGen Website.*
