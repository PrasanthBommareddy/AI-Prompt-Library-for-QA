# ChatGPT Prompt Engineering Experiments

## Purpose

This document records my prompt engineering experiments while learning how to use Large Language Models (LLMs) for Quality Assurance and Test Automation.

Each experiment documents:
- The objective
- The prompt version
- AI-generated output
- Observations
- Improvements made
- Lessons learned

This iterative approach helps improve prompt quality and produce more accurate, structured, and automation-ready outputs.

---

# Experiment #1 – Login Test Case Generation

## Goal

Generate comprehensive Login Test Cases using Prompt Engineering.

---

## Problem Statement

The objective was to evaluate how prompt quality impacts the quality of AI-generated test cases.

---

## Prompt Version 1 (Basic Prompt)

```
Generate Login Test Cases.
```

### AI Response Summary

The AI generated:

- Basic Functional Test Cases
- Positive Test Cases
- Negative Test Cases

### Strengths

- Quick response
- Correct basic functionality
- Suitable for simple tasks

### Limitations

- Missing Security Testing
- Missing API Testing
- Missing Accessibility Testing
- Missing Database Validation
- Missing Performance Testing
- No Automation Recommendations

### Overall Rating

⭐⭐⭐☆☆ (6/10)

---

# Prompt Version 2 (Improved Prompt)

The prompt was enhanced by adding:

- Role
- Objective
- Business Context
- Business Rules
- Testing Categories
- Constraints
- Expected Output Format
- Automation Feasibility
- Test Data Requirements

(Refer to `prompts/testcase-prompts.md`)

---

## AI Response Summary

The AI generated:

- Functional Test Cases
- UI Test Cases
- Positive Test Cases
- Negative Test Cases
- Boundary Value Analysis
- Equivalence Partitioning
- Security Test Cases
- Accessibility Test Cases
- API Validation
- Database Validation
- Performance Testing
- Automation Recommendations

---

## Strengths

- Excellent test coverage
- Well-structured output
- Security-focused
- Automation-ready
- Suitable for enterprise projects
- Easy to convert into Playwright/Selenium automation

---

## Areas for Improvement

Future prompt versions should also include:

- Browser Compatibility Testing
- Mobile Responsiveness
- Localization Testing
- Internationalization Testing
- Usability Testing
- Recovery Testing
- Session Management Testing

---

## Prompt Comparison

| Category | Version 1 | Version 2 |
|-----------|-----------|-----------|
| Business Context | ⭐⭐ | ⭐⭐⭐⭐⭐ |
| Functional Testing | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| Security Testing | ⭐ | ⭐⭐⭐⭐⭐ |
| Accessibility | ❌ | ⭐⭐⭐⭐ |
| API Testing | ⭐ | ⭐⭐⭐⭐⭐ |
| Database Validation | ❌ | ⭐⭐⭐⭐ |
| Performance Testing | ❌ | ⭐⭐⭐⭐ |
| Automation Readiness | ⭐⭐ | ⭐⭐⭐⭐⭐ |
| Overall Quality | ⭐⭐⭐☆☆ | ⭐⭐⭐⭐⭐ |

---

## Lessons Learned

- Prompt quality directly influences AI output quality.
- Providing business context significantly improves response relevance.
- Clearly defining expected output results in better formatting.
- Breaking testing into categories leads to more comprehensive coverage.
- Prompt Engineering is an iterative process of continuous improvement.

---

## Next Experiment

Generate Playwright automation scripts using Prompt Engineering.

Status: Planned
