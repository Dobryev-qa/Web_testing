# Test Plan #001  
## Web Demo Shop – OpenCart

**Project:** Demo OpenCart Web Shop  
**URL:** https://demo.opencart.com/en-gb  

**Start date:** 10.10.2025  
**Project acceptance date:** 14.10.2025  

---

## 1. Introduction

Demo OpenCart is an educational e-commerce web application that includes a product catalog, user registration, shopping cart, and checkout functionality.  
The application is fully developed. No formal requirements documentation is available.

This test plan is created for learning and practicing manual QA activities on a web-based e-commerce system.

---

## 2. Objectives

- Verify that core functionalities of the web shop work correctly  
- Ensure that users can complete main user flows from registration to checkout  
- Practice test planning, scope definition, prioritization, and risk analysis  

---

## 3. Test Types

- Functional testing  
- UI testing  
- Basic performance checks  
- Cross-browser testing  
- Mobile testing  

---

## 4. Test Items

- Web application functionality  
- User interface elements  
- User flows from registration to checkout  

---

## 5. Scope

### 5.1 In Scope

#### Functional Testing

**Navigation & Layout**
- Header (L)  
- Navigation bar with drop-down menu (H)  
- Footer (L)  
- All links functionality (M)  

**Catalog & Search**
- Product catalog (H)  
- Search functionality (L)  

**User Actions**
- Registration and Login (H)  
- Shopping Cart (H)  
- User Account (H)  
- Payment process simulation (H)  

---

#### UI Testing

**Interface Consistency**
- Logical consistency of the interface (H)  
- Consistency of interface elements (M)  
- Correct display of images (M)  
- Correct alignment of elements (M)  

**Navigation & Readability**
- Intuitive navigation (M)  
- Text readability (size, contrast) (H)  
- Logical flow of user scenarios (H)  

---

#### Basic Performance Checks
- Page load time (H)  

---

#### Mobile Testing
- Responsive layout on different screen sizes (L)  
- Usability of touch elements (M)  
- Gesture handling (M)  
- Correct screen orientation (L)  

---

### 5.2 Out of Scope

- Regression testing  
- Automated testing  
- Load and stress testing  

---

## 6. Priority Scale

- **H** – High  
- **M** – Medium  
- **L** – Low  

---

## 7. Acceptance Criteria

Testing is considered complete when:

- All planned test cases are executed  
- No critical bugs blocking core user scenarios (registration, login, add to cart) remain  
- Low-priority bugs do not affect normal system operation and are documented  

---

## 8. Test Environment

**Operating Systems**
- macOS 15.3.2  
- Windows 11  

**Browsers**
- Google Chrome 138–141 (stable)  
- Safari 18.2 – 26.0.1 (stable)  

**Mobile Platforms**
- Android 15  
- iOS 26  

**Tools**
- TestRail  
- Jira  

---

## 9. Timescales

| Activity                          | Duration |
|----------------------------------|----------|
| Test planning                    | 2 days   |
| Test analysis and design         | 2 days   |
| Test cases and checklist creation| 3 days   |
| Test execution                   | 2 days   |
| Test summary and reporting       | 1 day    |

---

## 10. Risks

- **No detailed requirements**  
  Lack of clear requirements may lead to misunderstanding of expected system behavior.

- **Limited experience with e-commerce systems**  
  Some typical online shop issues may be missed.

- **Project developed by another team**  
  Limited access to developers may slow down issue clarification.

- **Short testing timeline**  
  Time constraints may reduce test coverage.

- **Incorrect effort estimation**  
  Poor estimation may result in untested areas.

---

## 11. Approvals

- Test plan reviewed and approved by team members
