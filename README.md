# LogicsGen-Website-QA-11-Nov-2026
# LogicsGen Website – Manual QA Testing

A manual software testing project documenting functional testing, form validation, navigation, responsive checks, defect reporting, and Lighthouse auditing of the LogicsGen website.

## Project Overview

This project involved testing the LogicsGen website to evaluate its main user journeys, identify functional issues, verify form behavior, and check selected responsive layouts.

The testing was performed manually using desktop Chrome, a physical Redmi 13 mobile phone, and Chrome DevTools responsive emulation.

**Website:** https://logicsgen.com/

**Testing Date:** 11 November 2026

## Objectives

- Verify website navigation and page functionality.
- Test contact and course enquiry forms.
- Validate required fields and invalid inputs.
- Check selected responsive layouts.
- Identify, document, and classify defects.
- Capture screenshots as defect evidence.
- Evaluate the homepage using Google Lighthouse.

## Testing Environment

| Environment | Details |
|---|---|
| Desktop browser | Google Chrome 156.0.8078.80 (64-bit) |
| Physical mobile | Redmi 13 |
| Responsive testing | Chrome DevTools – 768 × 1024 |
| Website | https://logicsgen.com/ |

## Testing Scope

The following areas were covered:

- Homepage loading
- Main navigation and Services dropdown
- Courses and course categories
- About Us and Contact Us pages
- Blogs page and blog links
- Contact form validation
- Course enquiry form
- Name, email and phone validation
- Message character limit
- Browser Back and Forward navigation
- Selected tablet and mobile responsive checks

## Test Execution Summary

- 20 manual test scenarios marked as Passed.
- 3 findings documented separately.
- Screenshot evidence included in the QA report.
- Lighthouse mobile homepage audit completed.

## Defects Identified

| Bug ID | Description | Severity | Status |
|---|---|---|---|
| LG-QA-001 | Suggested course cards redirect to the same incomplete course page. | High | Open – reproduced |
| LG-QA-002 | “Explore All Blog Posts” redirects to the Courses page instead of the Blogs page. | High | Open – reproduced |
| LG-QA-003 | CAPTCHA could not be clicked in Chrome DevTools responsive emulation at 768 × 1024. | Low – investigate | Needs verification |

**Note:** LG-QA-003 requires verification on a physical tablet. CAPTCHA worked in normal desktop Chrome and on the physical Redmi 13.

## Lighthouse Audit Results

A mobile Lighthouse audit was performed on the homepage using Navigation mode and Slow 4G simulation.

| Category | Score |
|---|---:|
| Performance | 62 |
| Accessibility | 93 |
| Best Practices | 77 |
| SEO | 100 |

### Key Performance Metrics

- First Contentful Paint (FCP): 2.5 s
- Largest Contentful Paint (LCP): 3.9 s
- Total Blocking Time (TBT): 1,000 ms
- Speed Index: 3.7 s
- Cumulative Layout Shift (CLS): 0

These results apply to the mobile homepage audit only, not the entire website.

## Evidence and Documentation

The project includes:

- Detailed QA Test Report
- Test scenarios with expected and actual results
- Defect IDs and reproduction steps
- Severity and status classifications
- Screenshot evidence
- Lighthouse audit findings and recommendations

## Limitations

- Actual enquiry email delivery and backend receipt were not verified.
- CAPTCHA behavior still requires physical-tablet verification.
- Lighthouse testing was limited to the mobile homepage.
- Other pages, browsers and device combinations were not fully tested.
- Automated accessibility results do not replace complete manual accessibility testing.

## Recommended Next Steps

1. Correct the related course-card destinations and incomplete course content.
2. Fix the incorrect blog button destination.
3. Verify CAPTCHA on a physical tablet.
4. Confirm enquiry delivery through the receiving inbox or backend.
5. Perform regression testing after fixes.
6. Run Lighthouse audits on additional pages and desktop.

## Skills Demonstrated

- Manual Software Testing
- Functional Testing
- UI Testing
- Form Validation Testing
- Boundary Value Testing
- Responsive Testing
- Navigation Testing
- Bug Reporting and Documentation
- Severity and Priority Assessment
- Screenshot Evidence Collection
- Chrome DevTools
- Google Lighthouse

## Project Deliverable

The complete **LogicsGen Website QA Test Report** contains the detailed test cases, findings, screenshots, Lighthouse results, and recommended next actions.

---

*This project demonstrates practical manual QA testing and defect documentation. Findings and test results are limited to the environments and scenarios recorded in the report.*
