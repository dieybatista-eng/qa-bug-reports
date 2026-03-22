# Bug Reports (Jira Simulation)

---

# Bug Reports

---

## BUG-01 - Invalid password error message

Environment:
Chrome / Windows

Steps to Reproduce:
1. Access login page
2. Enter valid username
3. Enter invalid password
4. Click login

Expected Result:
System should display a clear and user-friendly error message

Actual Result:
Error message displayed: "Epic sadface: Username and password do not match any user in this service"

Severity:
Medium

Priority:
High

Evidence:
See evidence/bug-invalid-password.png

---

## BUG-02 - Login blocked user feedback issue

Environment:
Chrome / Windows

Steps to Reproduce:
1. Access login page
2. Enter username "locked_out_user"
3. Enter password "secret_sauce"
4. Click login

Expected Result:
System should clearly inform that the user is blocked and provide proper guidance

Actual Result:
User is blocked with a generic message that may not provide sufficient context or guidance

Severity:
Medium

Priority:
Medium

Evidence:
See evidence/bug-locked-user.png

---

## BUG-03 - Product not properly added to cart for specific user

Environment:
Chrome / Windows

Steps to Reproduce:
1. Login with user "problem_user"
2. Click "Add to cart" on a product

Expected Result:
Product should be added to cart and visible in cart icon

Actual Result:
Product behavior is inconsistent (cart does not update correctly or UI behaves unexpectedly)

Severity:
High

Priority:
Medium

Evidence:
See evidence/bug-product-cart.png
