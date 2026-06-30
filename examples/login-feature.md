# Login Feature Example

## Overview

This example demonstrates how a well-structured AI prompt can generate comprehensive test scenarios for a Login feature. It follows the Prompt Engineering workflow used throughout this repository.

---

# Business Requirement

The application provides a Login page with the following components:

## UI Components

- Username
- Password
- Remember Me
- Forgot Password
- Login Button

## Business Rules

- Username is mandatory.
- Password is mandatory.
- Password must contain at least 8 characters.
- Account is locked after 5 consecutive failed login attempts.
- A notification email is sent after the account is locked.
- "Remember Me" keeps the user signed in for 30 days.

---

# Prompt Used

The **Login Test Case Generator** prompt from:

```text
prompts/testcase-prompts.md
```

The prompt instructs the AI to generate:

- Functional Test Cases
- UI Test Cases
- Positive & Negative Test Cases
- Boundary Value Analysis
- Equivalence Partitioning
- Security Testing
- Accessibility Testing
- API Validation
- Database Validation
- Performance Testing
- Automation Feasibility

---

# AI Generated Output (Sample)

## Functional Test Cases

| Test ID | Scenario | Expected Result |
|----------|----------|-----------------|
| LGN-001 | Login with valid credentials | User is successfully logged in. |
| LGN-002 | Invalid password | Error message is displayed. |
| LGN-003 | Empty username | Username validation message appears. |
| LGN-004 | Empty password | Password validation message appears. |
| LGN-005 | Locked account login | User cannot log in and receives an appropriate message. |

---

## Security Test Cases

- SQL Injection validation
- Cross-Site Scripting (XSS)
- Brute Force protection
- Password masking verification
- Session timeout validation
- Secure authentication token validation

---

## Accessibility Test Cases

- Keyboard navigation
- Screen reader compatibility
- ARIA label verification
- Focus order validation
- Color contrast compliance (WCAG)

---

## API Validation

- HTTP Status Codes
- Authentication Token Validation
- JWT Verification
- Invalid Credential Handling
- API Response Time

---

## Database Validation

- Failed Login Counter
- Account Lock Status
- Last Login Timestamp
- Audit Log Verification

---

## Performance Testing

- Login response time
- Concurrent user login
- Stress testing
- Peak load validation

---

# Output Review

## Strengths

- Comprehensive test coverage
- Includes Functional, UI, API, Database, Security, Accessibility, and Performance testing
- Automation-friendly output
- Well-structured response
- Easy to convert into automation scripts

---

## Areas for Improvement

The generated output can be enhanced by including:

- Browser compatibility testing
- Mobile responsiveness
- Localization and internationalization testing
- Usability testing
- Cross-browser validation
- Session recovery scenarios

---

# Prompt Improvement

The second version of the prompt introduced:

- Detailed business context
- Clear testing categories
- Structured output format
- Test data requirements
- Automation recommendations
- Risk identification

These additions significantly improved the quality and completeness of the AI-generated output.

---

# Lessons Learned

- Well-defined prompts produce significantly better results than simple prompts.
- Providing business context helps AI generate more relevant test cases.
- Clearly defining the expected output improves consistency.
- Breaking testing into categories (Functional, Security, API, Accessibility, etc.) leads to more comprehensive coverage.
- Prompt refinement is an iterative process that improves AI output quality over time.

# AI Output Evaluation

## Requirement Coverage

⭐⭐⭐⭐⭐

## Functional Coverage

⭐⭐⭐⭐⭐

## Security Coverage

⭐⭐⭐⭐⭐

## Accessibility

⭐⭐⭐⭐☆

## API Validation

⭐⭐⭐⭐⭐

## Database Validation

⭐⭐⭐⭐☆

## Performance Testing

⭐⭐⭐⭐☆

## Automation Readiness

⭐⭐⭐⭐⭐

## Overall Rating

9.8/10
