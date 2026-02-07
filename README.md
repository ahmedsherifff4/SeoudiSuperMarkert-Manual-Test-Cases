# 🛒 Seoudi Market - Manual Testing Project

A comprehensive manual testing project for the **Seoudi Market** e-commerce platform. This repository documents the end-to-end testing process, from test case design to bug reporting and validation.

---

## 📌 Project Overview
This project validates the core functionalities of the Seoudi Market website to ensure a seamless and error-free shopping experience for users.

* **Target Website:** [Seoudi Market](https://seoudimarket.com/)
* **Testing Types:** Manual Testing, Functional Testing, UI/UX Testing, and Regression Testing.
* **Primary Goal:** Identifying critical functional defects and verifying requirement coverage.

---

## 🧪 Testing Scope
The testing process covered the following modules:
* **User Authentication:** Registration, Login, and Profile Management.
* **Product Catalog:** Search, Category filtering, and Sorting mechanisms.
* **Shopping Cart:** Adding/removing items and price calculations.
* **Checkout Process:** Address book management and order placement.

---

## 📂 Project Deliverables

### 1️⃣ Test Cases Suite
[`File Of Test Cases`](https://github.com/ahmedsherifff4/SeoudiSuperMarkert-Manual-Test-Cases/blob/62aabc31087cb1634b012deff34e1738ff9252ff/SeoudiSuperMarket-Test-Cases.xlsx)
Detailed test cases were designed to cover various scenarios, including:
* Adding multiple items to the cart and verifying quantities.
* Validating promo code fields (valid, invalid, and empty states).
* Verifying search functionality by keywords and filters.

### 2️⃣ Bug Reporting (Defect Documentation)
During execution, several defects were identified and documented. Key bugs include:

| Bug ID | Title/Summary | Severity | Priority | Status |
| :--- | :--- | :--- | :--- | :--- |
| **BUG_01** | Sort by Price (Low to High) displays incorrect order. | Medium | High | New |
| **BUG_02** | Sort by Price (High to Low) displays incorrect order. | Medium | High | New |
| **BUG_134** | System accepts invalid phone numbers in Address Book without OTP. | Critical | High | New |

---

## 📈 Detailed Bug Samples

### 🔴 Critical Bug: Address Validation Issue
* **Description:** The system allows users to save an invalid phone number (e.g., `012345678992`) in the Address Book and proceed to checkout without any validation or OTP verification.
* **Expected Result:** System should validate the format and send an OTP to confirm ownership.
* **Actual Result:** Address saved successfully, and order confirmed with an incorrect number.

### 🟡 Functional Bug: Sorting Malfunction
* **Description:** When selecting "Sort by Price: Low to High", products appear in an inconsistent order, failing to maintain a true ascending sequence.
* **Environment:** Tested on Windows 10 (Microsoft Edge) and Windows 11 (Firefox).

---

## 🛠️ Tools & Environment
* **Documentation:** MS Excel / Google Sheets.
* **Browsers:** Microsoft Edge (v141), Firefox (v144).
* **OS:** Windows 10 & 11.

---

## 👤 By
**Ahmed Sherif**
* **Role:** Software Quality Control Engineer



