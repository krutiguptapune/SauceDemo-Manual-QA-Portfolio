
# Known Application Issues

## KNOWN-001: Incorrect Product Images

- **Module:** Products
- **Affected User:** problem_user
- **Related Test Case:** TC_USER_007
- **Severity:** Medium
- **Priority:** Low
- **Status:** Known Issue

### Preconditions
Log in using problem_user.

### Steps to Reproduce
1. Open SauceDemo.
2. Log in using problem_user and secret_sauce.
3. Navigate to the Products page.
4. Inspect the product images.

### Expected Result
Each product should display its corresponding product image.

### Actual Result
Dog images are displayed instead of the corresponding product images.

### Notes
This is a known, intentionally seeded behaviour of the SauceDemo demo application. It is documented for testing purposes and is not claimed as a newly discovered defect.


## KNOWN-002: Visual Layout Inconsistencies

- **Module:** User Interface
- **Affected User:** visual_user
- **Related Test Case:** TC_USER_008
- **Severity:** Low
- **Priority:** Low
- **Status:** Known Issue

### Preconditions
Log in using visual_user and secret_sauce.

### Steps to Reproduce
1. Open SauceDemo.
2. Log in using visual_user.
3. Inspect the Products page.
4. Navigate to the cart and checkout pages.
5. Observe the alignment and positioning of interface elements.

### Expected Result
Interface elements should be consistently aligned and displayed.

### Actual Result
Visual inconsistencies were observed, including unusual positioning of the cart icon and page elements.

### Notes
This is an intentionally seeded behaviour of the demo application.

---

## KNOWN-003: Slow Application Response

- **Module:** Application Performance
- **Affected User:** performance_glitch_user
- **Related Test Case:** TC_USER_006
- **Severity:** Medium
- **Priority:** Medium
- **Status:** Known Issue

### Preconditions
Log in using performance_glitch_user and secret_sauce.

### Steps to Reproduce
1. Open SauceDemo.
2. Log in using performance_glitch_user.
3. Navigate through the Products page.
4. Observe the time taken for pages and actions to respond.

### Expected Result
Application pages and actions should respond within a reasonable time.

### Actual Result
Noticeable delays were observed while using the application.

### Notes
This is an intentionally seeded behaviour. No formal performance benchmark was conducted.
