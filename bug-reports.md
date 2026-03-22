# Bug Reports (Jira Simulation)

---

## BUG-01 - Invalid password message validation issue

Tool:
Jira (simulated)

Environment:
Chrome / Windows

Steps to Reproduce:
1. Access login page
2. Enter valid username
3. Enter invalid password
4. Click login

Expected Result:
System should display clear and consistent error message

Actual Result:
Error message displayed is inconsistent or unclear

Severity:
Medium

Priority:
High

Evidence:
See evidence/bug-invalid-password.png

---

## BUG-02 - Login error message layout issue

Tool:
Jira (simulated)

Environment:
Chrome / Windows

Steps to Reproduce:
1. Access login page
2. Enter invalid credentials
3. Click login

Expected Result:
Error message should be properly aligned and readable

Actual Result:
UI layout issue observed in error message

Severity:
Low

Priority:
Medium

Evidence:
See evidence/bug-error-layout.png

---

## BUG-03 - Slow response on login error feedback

Tool:
Jira (simulated)

Environment:
Chrome / Windows

Steps to Reproduce:
1. Enter invalid login
2. Click login

Expected Result:
Immediate feedback to user

Actual Result:
Delay before error message appears

Severity:
Low

Priority:
Medium

Evidence:
See evidence/bug-delay.png
