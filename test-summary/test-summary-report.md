# Test Summary Report – Internal Invoicing Web App

**Tested By:** Rocio Bustamante  
**Testing Period:** March 25–April 3, 2025  
**Environment:** QA  
**Release Version:** 1.4.0

---

## 1. Test Scope
The test covered all core features of the Netting maintenance task:
- Creation, execution, deletion, and cancellation
- Netting maintenance periodicity (none, daily, weekly)
- Role-based permissions access
- Error validations

## 2. Test Execution Summary

Test Case Summary

| Category                      | Number of Test Cases | Notes |
|------------------------------|----------------------|-------|
| ✅ New Functionality          | 31                   | Based on sprint stories |
| 🔁 Existing Functionality     | 9                    | Validated for potential regressions |
| 📌 **Total Executed**         | 40                   | All tests executed manually |
| 🟢 Passed                     | 40                   | — |
| 🔴 Failed                     | 1                    | See Defect Summary |

## 3. Bugs Reported
- **BUG-001**: The task is not executed for users without Administration permissions – *High*

## 4. Conclusion
The web app is stable for release to staging. No bug remains open.

**Recommendation:** Move forward with deployment to staging.
