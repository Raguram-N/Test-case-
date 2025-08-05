# 🧪 QA Test Case Suite – E-Commerce Web Application

Welcome to the **E-Commerce QA Testing Project**, a comprehensive repository of manual test cases for core functionalities of a typical e-commerce website. This project is designed to demonstrate strong test design, test documentation, bug reporting, and QA thinking to potential recruiters.

---

## 📌 Features Covered

- 🔐 User Login
- 🔍 Product Search
- 🛒 Add to Cart
- 💳 Checkout & Payment
- 🚫 Negative & Boundary Testing
- 📸 UI Verification
- 🐞 Sample Bug Reports

---

## Test cases

<table>
  <tr>
    <th>TC ID</th>
    <th>Test Scenario</th>
    <th>Test Case Description</th>
    <th>Test Steps</th>
    <th>Test Data</th>
    <th>Expected Result</th>
    <th>Priority</th>
    <th>Status</th>
  </tr>
  <tr>
    <td>TC_LG_001</td>
    <td>Valid Login</td>
    <td>Verify login with valid credentials</td>
    <td>1. Go to login page<br>2. Enter valid email and password<br>3. Click login</td>
    <td><a href="mailto:user@example.com">user@example.com</a> / Pass@123</td>
    <td>User should be redirected to dashboard</td>
    <td>High</td>
    <td>Pass</td>
  </tr>
  <tr>
    <td>TC_LG_002</td>
    <td>Invalid Login</td>
    <td>Verify login fails with wrong password</td>
    <td>Enter correct email and wrong password</td>
    <td><a href="mailto:user@example.com">user@example.com</a> / wrongpass</td>
    <td>Show error message “Invalid credentials”</td>
    <td>High</td>
    <td>Pass</td>
  </tr>
  <tr>
    <td>TC_LG_003</td>
    <td>Blank Fields</td>
    <td>Verify login fails with empty fields</td>
    <td>Leave email and password blank, click login</td>
    <td>Blank</td>
    <td>Show validation messages</td>
    <td>Medium</td>
    <td>Pass</td>
  </tr>
  <tr>
    <td>TC_LG_004</td>
    <td>UI Validation</td>
    <td>Check placeholder and alignment of login fields</td>
    <td>Open login page</td>
    <td>N/A</td>
    <td>Email and Password placeholders shown correctly</td>
    <td>Low</td>
    <td>Fail</td>
  </tr>
  <tr>
    <td>TC_LG_005</td>
    <td>SQL Injection</td>
    <td>Enter SQL payload in login field</td>
    <td>Enter <code>' OR 1=1 --</code> as email and click login</td>
    <td>Malicious Input</td>
    <td>Show error or block login attempt</td>
    <td>High</td>
    <td>Pass</td>
  </tr>
</table>


