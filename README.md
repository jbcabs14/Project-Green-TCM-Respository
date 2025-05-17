# Feature: User Login

This test suite covers various scenarios for the login functionality of the Hiraya application. It ensures that users can log in securely and that error handling is properly implemented.

---

## ✅ Test Case ID: AUTH-001
### Title: Successful Login with Valid Credentials
- **Pre-condition**: User must already be registered and email verified.
- **Test Steps**:
  1. Launch the Hiraya app.
  2. Tap the "Login" button.
  3. Enter a valid email and password.
  4. Tap "Sign In".
- **Expected Result**: User is redirected to the Main Dashboard.
- **Post-condition**: User session is active.
- **Priority**: High
- **Tester**: John Benedict Cabintoy

---

## 🛑 Test Case ID: AUTH-002
### Title: Login with Incorrect Password
- **Pre-condition**: User must already be registered.
- **Test Steps**:
  1. Launch the Hiraya app.
  2. Tap the "Login" button.
  3. Enter a valid email and an incorrect password.
  4. Tap "Sign In".
- **Expected Result**: Error message is displayed: "Incorrect password. Please try again."
- **Post-condition**: User remains on the login screen.
- **Priority**: Medium
- **Tester**: John Benedict Cabintoy

---

## 🛑 Test Case ID: AUTH-003
### Title: Login Attempt with Unverified Email
- **Pre-condition**: User is registered but email is not verified.
- **Test Steps**:
  1. Launch the Hiraya app.
  2. Tap the "Login" button.
  3. Enter registered email and password.
  4. Tap "Sign In".
- **Expected Result**: User is redirected to the "Verify Email" screen with instruction to verify their email.
- **Post-condition**: User remains in pending verification state.
- **Priority**: High
- **Tester**: John Benedict Cabintoy

---

## 🛑 Test Case ID: AUTH-004
### Title: Login with Empty Fields
- **Pre-condition**: App is launched.
- **Test Steps**:
  1. Tap the "Login" button without entering any credentials.
- **Expected Result**: Error message appears: "Please fill in all fields."
- **Post-condition**: No login attempt is made.
- **Priority**: Low
- **Tester**: John Benedict Cabintoy
