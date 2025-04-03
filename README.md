## 💡 Demo Test Scenario: Full User Flow on automationexercise.com

This scenario covers a complete user journey:
- Signup
- Login
- Add product to cart
- Checkout
- Logout and validate logout

### ✅ Steps:
1. Navigate to [https://www.automationexercise.com](https://www.automationexercise.com)
2. Click on "Signup / Login"
3. Fill out the signup form with a random email
4. Verify successful login ("Logged in as <name>")
5. Add a product to the cart and proceed to checkout
6. Verify product details on checkout page
7. Logout
8. Verify redirection to login page and that the user is logged out

### 🧪 Validation Points:
- Homepage loads correctly
- Account is created and user is logged in
- Product appears in the cart
- Logout redirects to login screen and removes session

---

## 🧱 Project Structure & Best Practices

This project follows **Playwright** with the **Page Object Model (POM)** and includes:

- ✅ **Page Object Model (POM)** structure for scalable test management
- ✅ A properly designed **Base Class** (or base test file) to share common setup across tests
- ✅ Use of **`locator`** API (preferred in Playwright for stable selectors)
- ✅ Strategic use of **XPath** selectors when necessary (e.g., dynamic or sibling-based elements)
- ✅ **Valid `expect()` assertions** at the **test level** to ensure user flows and state transitions are correctly validated

---

> 💡 Use `npx playwright test` to run the full test suite.
