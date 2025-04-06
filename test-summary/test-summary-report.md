# Test Summary Report – Internal Invoicing Web App

**Tested By:** [Your Name]  
**Testing Period:** March 25–April 3, 2025  
**Environment:** UAT  
**Release Version:** 1.4.0

---

## 1. Test Scope
The test covered all core features of the invoice lifecycle:
- Creation, editing, and deletion
- Status transitions (Draft → Sent → Paid)
- Role-based permissions
- PDF generation

## 2. Test Execution Summary

| Test Type     | Total | Passed | Failed | Blocked |
|---------------|-------|--------|--------|---------|
| Functional    | 20    | 18     | 1      | 1       |
| Regression    | 15    | 15     | 0      | 0       |
| Smoke         | 8     | 8      | 0      | 0       |

## 3. Bugs Reported
- **BUG-001**: "Paid" status not saved after refresh – *High*

## 4. Conclusion
The app is stable for release to staging. One bug remains blocked due to missing backend response.

**Recommendation:** Move forward with deployment to staging once the blocked case is unblocked.
