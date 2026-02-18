# Test Plan for Naree Website

**Project Name:** Naree Online Store  
**Website URL:** [https://naree.pl/pl/](https://naree.pl/pl/)  
**Prepared by:** [Ewelina Wisińska]  
**Date:** [18.02.2026]  

---

## Table of Contents
1. [Purpose of the Document](#1-purpose-of-the-document)  
2. [Test Subject](#2-test-subject)  
3. [Description of the Test Subject](#3-description-of-the-test-subject)  
4. [Test Items](#4-test-items)  
5. [Test Scope](#5-test-scope)  
6. [Test Design Techniques](#6-test-design-techniques)  
7. [Test Data Requirements](#7-test-data-requirements)  
8. [Test Environment](#8-test-environment)  
9. [Test Environment Requirements](#9-test-environment-requirements)  
10. [Entry/Exit Criteria](#10-entryexit-criteria)  
11. [Test Pass Criteria](#11-test-pass-criteria)  
12. [Test Completion Criteria](#12-test-completion-criteria)  
13. [Testing Tools](#13-testing-tools)  
14. [Test Execution](#14-test-execution)  
15. [Test Reporting](#15-test-reporting)  
16. [Roles and Responsibilities](#16-roles-and-responsibilities)  


---

## 1. Purpose of the Document
The purpose of this document is to define the testing strategy, objectives, scope, and methodology for the **Naree Online Store** website. The plan ensures that all functional, usability, performance, security, and compatibility aspects are verified before release.

---

## 2. Test Subject
- **Website:** [https://naree.pl/pl/](https://naree.pl/pl/)  
- **Type:** Online fashion store  
- **Target Audience:** Customers browsing and purchasing fashion products online  

---

## 3. Description of the Test Subject
The Naree website is an e-commerce platform that provides users with the ability to:
- Browse product catalog  
- Search, filter, and sort products  
- Add products to the shopping cart and complete checkout  
- Register and manage user accounts  
- Subscribe to newsletters  
- Make secure online payments  

---

## 4. Test Items
- Homepage  
- Product catalog and product pages  
- Search and filtering system  
- Shopping cart and checkout process  
- User registration, login, and profile management  
- Payment gateway integration  
- Newsletter subscription functionality  
- Responsive design and accessibility features  

---

## 5. Test Scope

**In Scope:**  
- Functional testing of website features  
- Usability, UI consistency, and accessibility  
- Performance and load testing  
- Security validation  
- Cross-browser and cross-device compatibility  

**Out of Scope:**  
- Backend database testing  
- API stress testing beyond normal user scenarios  

---

## 6. Test Design Techniques
- **Equivalence Partitioning:** Testing valid and invalid input scenarios  
- **Boundary Value Analysis:** Input fields (e.g., quantity, price filters)  
- **Use Case Testing:** Simulate real user scenarios such as purchase flow  
- **Exploratory Testing:** Ad-hoc testing for unexpected behavior  
- **Cross-Browser Testing:** Compare behavior across multiple browsers and devices  

---

## 7. Test Data Requirements
- Test user accounts (new and existing)  
- Product data for browsing and purchase  
- Payment sandbox credentials  
- Sample shipping addresses  
- Newsletter subscription emails  

---

## 8. Test Environment
- **OS:** Windows, macOS, iOS, Android  
- **Browsers:** Chrome, Firefox, Edge, Safari  
- **Devices:** Desktop, tablet, mobile  
- **Network Conditions:** Wi-Fi, 4G, high latency scenarios  

---

## 9. Test Environment Requirements
- Stable deployment of the QA environment  
- Access to payment gateway sandbox  
- Test accounts for admin and users  
- Updated browser versions and device simulators/emulators  
- Logging and monitoring tools enabled  

---

## 10. Entry/Exit Criteria

**Entry Criteria:**  
- Website deployed to QA environment  
- Test data prepared and available  
- Access to payment and email systems  

**Exit Criteria:**  
- All critical and high-severity defects resolved  
- Test cases executed and verified  
- Test reports reviewed and approved  

---

## 11. Test Pass Criteria
- Functional features meet expected requirements  
- No high or critical defects remain unresolved  
- Website performance, security, and accessibility standards met  

---

## 12. Test Completion Criteria
- All planned test cases executed  
- Defect backlog reviewed  
- Test summary report submitted and approved  

---

## 13. Testing Tools
- **Test Management:** Jira, TestRail, or equivalent  
- **Automation Tools (if applicable):** Selenium, Cypress  
- **Performance Testing:** Lighthouse, GTmetrix  
- **Security Testing:** OWASP ZAP, SSL Labs  
- **Cross-Browser Testing:** BrowserStack, LambdaTest  

---

## 14. Test Execution
- Execute test cases according to the test plan  
- Log defects with severity and priority  
- Retest resolved defects  
- Record test results for reporting  

---

## 15. Test Reporting
- Daily/weekly test progress reports  
- Defect reports with reproduction steps and screenshots  
- Final test summary report including metrics, defects, and recommendations  

---

## 16. Roles and Responsibilities
- **QA Lead:** Plan and oversee testing activities  
- **Testers:** Execute test cases, log defects, verify fixes  
- **Developers:** Fix defects and support testing  
- **Product Owner:** Validate features and approve release  

---

