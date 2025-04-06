# Test Plan – Internal Invoicing Web App

## 1. Project Overview
This test plan covers the functional testing activities for the internal web-based invoicing system used by client stakeholders. The application allows users to create, edit, send, and track invoices.

## 2. Objectives
- Verify that the invoice lifecycle works as expected (creation, approval, and status tracking)
- Ensure that only authorized users can access or edit invoices
- Detect bugs early by analyzing acceptance criteria and validating edge cases

## 3. Scope
### In Scope
- Invoice creation and editing
- PDF generation and download
- Role-based access (Admin, Accountant, Viewer)
- Status changes (Draft → Sent → Paid)
- Error handling and validations

### Out of Scope
- Integration with third-party accounting software
- Mobile responsiveness

## 4. Test Types
- Functional testing
- Regression testing
- Smoke testing

## 5. Test Deliverables
- Test cases in Excel format
- Bug reports documented per issue
- Test summary report (TSR)

## 6. Environment
- Web: Chrome / Edge (latest)
- Test Environment: UAT server (URL provided internally)
- Data: Preloaded test users and invoice data

## 7. Tools
- Azure DevOps (Test case tracking and bug reporting)
- Excel (Test case documentation)
- Snagit / Loom (Bug evidence capture)

## 8. Entry & Exit Criteria
### Entry
- Dev team has deployed the latest build
- Acceptance criteria are reviewed and ready

### Exit
- All high-priority test cases passed
- No critical or high severity defects open

## 9. Team
- QA Manual Tester: [Your Name]
- Product Owner: [Name]
- Developers: [Name(s)]
