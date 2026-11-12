
# SauceDemo - Requirements Document

## 1. Introduction

This document defines the functional requirements for the SauceDemo e-commerce application.

The requirements describe the expected behaviour of the application and will be used as the basis for designing and executing manual test cases.

## 2. User Stories and Acceptance Criteria

### REQ-001: User Login

**User Story:**

As a user, I want to log in using valid credentials so that I can access the shopping application.

**Acceptance Criteria:**

- User should be able to enter a username and password.
- User should be able to log in using valid credentials.
- Successful login should redirect the user to the Products page.
- Invalid credentials should display an appropriate error message.
- Locked-out users should not be allowed to log in.

### REQ-002: Product Listing

**User Story:**

As a customer, I want to view available products so that I can choose items to purchase.

**Acceptance Criteria:**

- Products page should display available products.
- Each product should display its name, image, price and description.
- Product information should be readable.
- Product listing should be accessible after successful login.

### REQ-003: Product Sorting

**User Story:**

As a customer, I want to sort products so that I can find products according to my preferences.

**Acceptance Criteria:**

- Products should be sortable by name from A to Z.
- Products should be sortable by name from Z to A.
- Products should be sortable by price from low to high.
- Products should be sortable by price from high to low.
- Product order should update according to the selected option.

### REQ-004: Product Details

**User Story:**

As a customer, I want to view individual product details so that I can learn more about a product before purchasing it.

**Acceptance Criteria:**

- Clicking a product name should open its details page.
- Product details page should display the product name.
- Product image, description and price should be displayed.
- User should be able to return to the Products page.

### REQ-005: Add Product to Cart

**User Story:**

As a customer, I want to add products to my shopping cart so that I can purchase them later.

**Acceptance Criteria:**

- User should be able to add a product to the cart.
- Cart badge should increase after adding a product.
- Added products should appear in the shopping cart.
- Multiple products should be addable to the cart.

### REQ-006: Remove Product from Cart

**User Story:**

As a customer, I want to remove products from my shopping cart so that I can change my selection.

**Acceptance Criteria:**

- User should be able to remove an added product.
- Removed products should no longer appear in the cart.
- Cart badge should update after removal.
- User should be able to remove all products from the cart.

### REQ-007: View Shopping Cart

**User Story:**

As a customer, I want to view my shopping cart so that I can review my selected products.

**Acceptance Criteria:**

- User should be able to open the shopping cart.
- Added products should be displayed.
- Product names and prices should be correct.
- Product quantities should be displayed.
- Continue Shopping and Checkout options should be available.

### REQ-008: Cart Persistence

**User Story:**

As a customer, I want my cart items to remain available after navigating or logging out and back in so that I do not lose my selections.

**Acceptance Criteria:**

- Cart items should remain available after navigating between pages.
- Cart items should remain available after logout and subsequent login using the same account, as observed in the tested application.
- Cart contents should be displayed correctly when reopened.

### REQ-009: Checkout Navigation

**User Story:**

As a customer, I want to proceed to checkout so that I can place my order.

**Acceptance Criteria:**

- Checkout option should be available in the shopping cart.
- Clicking Checkout should open the customer information form.
- User should be able to navigate back to shopping.

### REQ-010: Checkout Information Form

**User Story:**

As a customer, I want to enter my personal and postal information so that I can proceed with checkout.

**Acceptance Criteria:**

- First Name field should be available.
- Last Name field should be available.
- Zip/Postal Code field should be available.
- User should be able to enter valid information.
- All required fields must be completed before proceeding.

### REQ-011: Checkout Form Validation

**User Story:**

As a customer, I want to receive error messages when required information is missing so that I can correct my input.

**Acceptance Criteria:**

- Empty First Name should display an error.
- Empty Last Name should display an error.
- Empty Zip/Postal Code should display an error.
- Error messages should clearly identify missing information.
- User should be able to correct the information and continue.

### REQ-012: Checkout Overview

**User Story:**

As a customer, I want to review my order before completing the purchase so that I can verify my selected products and charges.

**Acceptance Criteria:**

- Selected products should be displayed.
- Product prices should be correct.
- Item total should be calculated correctly.
- Tax should be displayed.
- Final total should equal item total plus tax.
- Finish button should be available.

### REQ-013: Order Completion

**User Story:**

As a customer, I want to complete my order so that I receive confirmation of my purchase.

**Acceptance Criteria:**

- Clicking Finish should complete the demo checkout process.
- A confirmation page should be displayed.
- A successful order confirmation message should appear.
- Back Home option should be available.

### REQ-014: Post-Checkout Behaviour

**User Story:**

As a customer, I want to return to the Products page after completing an order so that I can continue shopping.

**Acceptance Criteria:**

- Back Home should return the user to the Products page.
- Previously completed cart items should be cleared.
- Cart badge should reflect the empty cart.

### REQ-015: User Logout

**User Story:**

As a user, I want to log out of the application so that my session is closed.

**Acceptance Criteria:**

- Logout option should be available in the navigation menu.
- Clicking Logout should return the user to the login page.
- User should be required to log in again to access protected pages.

### REQ-016: Browser Navigation

**User Story:**

As a customer, I want to navigate between pages using browser navigation controls so that I can revisit previous pages.

**Acceptance Criteria:**

- Browser Back should navigate to the previous page when applicable.
- Browser Forward should navigate to the next page when applicable.
- Cart information should remain consistent during navigation.
- Application should handle navigation without displaying incorrect page information.

### REQ-017: User Interface Consistency

**User Story:**

As a customer, I want the application interface to display correctly so that I can use the website without confusion.

**Acceptance Criteria:**

- Product images should correspond to their products.
- Buttons and icons should be positioned correctly.
- Product information should be readable.
- Checkout elements should be displayed in their expected positions.
- Application layout should remain usable across supported pages.

### REQ-018: Application Response Behaviour

**User Story:**

As a customer, I want the application to respond to my actions within a reasonable time so that I can shop without unnecessary delays.

**Acceptance Criteria:**

- Login should respond to user actions.
- Products page should load successfully.
- Buttons should respond when clicked.
- Cart and checkout navigation should function correctly.
- Unusually slow responses should be recorded during testing.