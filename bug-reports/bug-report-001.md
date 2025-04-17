# Bug Report - Netting maintenance- The task is not executed for users without Administration permissions

**ID:** BUG-001  
**Title:** Netting maintenance task is not executed for users without permissions  
**Severity:** High  
**Priority:** High  
**Reported by:** Rocio Bustamante 
**Date:** 2025-04-05

## Steps to Reproduce
1. PRE-REQ: Log in to QA as a user without Administration permissions. Exits a weekly task previously created for Netting maintenance.
2. Observe the web-app sections after the task has started
3. Validate that the user can only see the maintenance window; other sections are not available

## Expected Result
The task starts, the web app is blocked, and the user can only see the maintenance window.

## Actual Result
The task did not start, the user can see the web app according to the user's permissions.

## Environment
- Edge v135
- QA environment

## Attachments
N/A
