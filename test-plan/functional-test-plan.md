# Test Plan – Internal Invoicing Web App

## 1. Project Overview
This test plan covers the functional testing activities for the internal web-based invoicing system used by client stakeholders. The application in this sprint allows users to create, execute, delete, or cancel a task called 'Netting maintenance' in the Maintenance section.

## 2. Objectives
- Verify that the invoice lifecycle works as expected (creation, approval, and status tracking)
- Ensure that only authorized users can access or edit invoices
- Detect bugs early by analyzing acceptance criteria and validating edge cases

## 3. Scope
### In Scope
- Netting maintenance creation, execution, deletion, and cancellation
- Netting maintenance periodicity: none, daily, and weekly
- Role-based access (Administration access, no administration access)
- Windows messages indicating statuses of the task (start → progress → end)
- Error handling and validations

### Out of Scope
- Netting maintenance periodicity: monthly and yearly

## 4. Test Types
- Functional testing
- Regression testing
  
## 5. Test Deliverables
- Test cases in Excel format
- Bug reports documented per issue
- OneNote (credentials)
- Test summary report (TSR)

## 6. Environment
- Web: Edge (latest)
- Test Environment: QA server (URL provided internally)
- Data: User test for QA example-test2@example.net

## 7. Tools
- Azure DevOps (Test case tracking and bug reporting)
- Excel (Test case documentation)
- Scrnlu Screenshots & Screen Video Recorder (Bug evidence capture)
## 8. Risks and Mitigation
- Delays in development delivery: Adjust the test schedule accordingly and prioritize high-risk test cases first
- Defects not fixed in time for testing: Track blockers in bug reports and communicate daily in standups or via ticketing tools (e.g., Azure DevOps)

## 9. Entry & Exit Criteria
### Entry
- Dev team has deployed the latest build
- Acceptance criteria are reviewed and ready

### Exit
- All high-priority test cases passed
- No critical or high severity defects open

## 10. Team
- QA Manual Tester: Rocio Bustamante
- Product Owner: Denisa
- Developers: Sergio, William
