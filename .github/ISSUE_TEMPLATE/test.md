---
name: Testing
about: Create a new testing issue
title: "[TESTING] Title"
labels: testing
assignees: ''
---
# [Testing] Title

## 📋 Description
_A concise summary of why this testing is required and what it aims to validate._  
Examples:
- New functionality added that requires unit/integration coverage
- Bug fix verification
- Regression risk mitigation

## 🧭 Scope
_Select all applicable types of testing for this task._

- [ ] Unit tests
- [ ] Integration tests
- [ ] End-to-end (E2E) tests
- [ ] Manual QA checklist
- [ ] Performance / Load tests
- [ ] Security tests (e.g. auth, input validation)

## ✅ Definition of Done (DoD)
_What constitutes acceptable completion for this testing task?_

- [ ] Test coverage increases by at least **X%**
- [ ] Tests pass consistently in CI/CD across environments
- [ ] Test scenarios cover main success and edge cases
- [ ] No significant regressions found post-implementation
- [ ] QA sign-off (if applicable)

## 🔁 Related Issues / Context
_Link any relevant issues or epics for traceability._

- Related feature: #123
- Part of epic: #456
- Bug being addressed (if applicable): #789

## 📝 Notes / Edge Cases
_Include any assumptions, tricky scenarios, or edge cases observed._  
Examples:
- Known flakiness in specific environments
- Dependencies on external APIs
- Areas of uncertainty