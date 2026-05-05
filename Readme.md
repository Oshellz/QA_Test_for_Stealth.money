# Stealth Money QA Testing Project

## Project Overview

This project contains a comprehensive manual QA testing exercise performed on a crypto purchase platform (Stealth Money).

The objective of this testing was to validate the core functionalities of the platform, identify defects, and evaluate the system’s behavior across multiple user flows.

---

## Scope of Testing

The testing covered the following major modules:

* User Registration
* User Login
* Password Reset
* User Dashboard
* KYC Verification
* Crypto Purchase (BTC & USDT)
* Fiat Amount Input
* BTC Satoshi (Sats) Conversion Display
* Wallet Address Input
* Virtual Account Generation
* Payment Flow & Time Constraints
* Transaction Processing
* Transaction History
* Navigation Menu
* UI/UX Interface

---

## Testing Types Performed

The following testing types were executed during this test cycle:

* Functional Testing
* Validation Testing
* End-to-End Testing
* UI Testing
* Boundary Testing
* Usability Testing
* Exploratory Testing

---

## Test Design Approach

Test cases were designed directly from functional requirements, ensuring:

* Positive test coverage (valid inputs and expected flows)
* Negative test coverage (invalid inputs and error handling)
* Edge case validation (boundary values and unusual inputs)

Each test case includes:

* Preconditions
* Step-by-step user actions
* Test data
* Expected results
* Actual results (status)

---

## Test Execution Summary

* Total Test Cases Executed: 53
* Passed: Majority of core functionalities
* Failed: Multiple validation and flow-related issues
* Needs Check: Some flows could not be fully validated due to missing system responses

---

## Key Defects Identified

During testing, several defects were identified, including:

* Incorrect or unclear error messaging (e.g., duplicate email registration)
* Missing validation behavior (empty field submissions not handled correctly)
* Password reset emails not being delivered
* Incomplete crypto purchase flow (USDT purchase failure)
* Missing or unclear payment processing feedback
* Uncertain transaction confirmation due to lack of system response
* UI feedback inconsistencies

---

## Notable Observations

* Some features showed expected UI feedback but lacked backend confirmation (e.g., password reset email not received).
* Certain flows (e.g., crypto purchase and transaction processing) had unclear or incomplete system responses.
* Error handling needs improvement for better user guidance.

---

## Test Artifacts Included

* Test Cases & Scenarios (Excel/PDF)
* Bug Observations (within test case comments)
* Test Closure Report

---

## Tools Used

* Manual Testing Techniques
* Browser (Chrome)
* Excel / PDF Documentation
* DevTools (basic inspection)

---

## Conclusion

The platform demonstrates a working structure for core crypto purchase functionality; however, several defects and inconsistencies were identified, particularly in validation, communication feedback, and transaction flow reliability.

Although, all discovered bugs has been fixed, further re-testing and subsequent fixes are recommended.

---

## Project Link

https://github.com/Oshellz/QA_Test_for_Stealth.money

