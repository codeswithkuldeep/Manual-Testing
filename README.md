
 ----- 
   <div align="center">       
            
# Ecommerce-Manual-Testing-Project  

# 🔐 Login Module Test Cases

![QA](https://img.shields.io/badge/Testing-Manual_QA-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Test_Cases-23-success?style=for-the-badge)
![Priority](https://img.shields.io/badge/Priority-High-orange?style=for-the-badge)

### 🧪 Software Testing Documentation

</div>

---

# 📌 Project Overview

This repository contains detailed **Login Module Test Cases** for manual testing.

The test cases cover:

- ✅ Functional Testing
- ✅ Negative Testing
- ✅ UI Validation
- ✅ Security Testing
- ✅ Session Testing
- ✅ Cross Browser Testing
- ✅ Accessibility Testing

---

# 📋 Module Information

| Property | Details |
|---|---|
| Module Name | Login Functionality |
| Testing Type | Manual Testing |
| Environment | Web Application |
| Browsers | Chrome, Firefox, Edge |
| Total Test Cases | 23 |
| Priority Levels | High, Medium, Low |

---

# 📊 Test Case Summary

| 🔢 Total Cases | 🔥 High | ⚡ Medium | 🟢 Low |
|---|---|---|---|
| 23 | 9 | 6 | 8 |

---

# 🧾 Login Test Cases

| Test Case ID | Test Case Title | Pre-Condition | Test Steps | Test Data | Expected Result | Priority | Status |
|---|---|---|---|---|---|---|---|
| TC_LG_001 | Login with valid credentials | User is registered | 1. Open website <br> 2. Click My Account → Login <br> 3. Enter valid email & password <br> 4. Click Login | Email: test@gmail.com <br> Password: 12345 | User should successfully login and redirect to My Account page | 🔥 High | ⬜ |
| TC_LG_002 | Login with invalid credentials | Website open | 1. Go to Login page <br> 2. Enter invalid email & password <br> 3. Click Login | wrong@gmail.com <br> wrong123 | Error message should display | 🔥 High | ⬜ |
| TC_LG_003 | Valid email + Invalid password | Same | Enter valid email and wrong password | test@gmail.com <br> wrong123 | Login should fail | 🔥 High | ⬜ |
| TC_LG_004 | Invalid email + Valid password | Same | Enter invalid email and valid password | wrong@gmail.com <br> 12345 | Login should fail | 🔥 High | ⬜ |
| TC_LG_005 | Login with empty fields | Same | Leave fields blank and click Login | --- | Warning message should appear | 🔥 High | ⬜ |
| TC_LG_006 | Forgot Password link | Login page open | Click Forgotten Password | --- | Reset Password page should open | ⚡ Medium | ⬜ |
| TC_LG_007 | Keyboard navigation | Same | Use Tab + Enter | Valid credentials | Login should work using keyboard | 🟢 Low | ⬜ |
| TC_LG_008 | Check placeholder text | Same | Observe fields | --- | Correct placeholders displayed | 🟢 Low | ⬜ |
| TC_LG_009 | Browser back after login | User logged in | Click browser back button | --- | User remains logged in | ⚡ Medium | ⬜ |
| TC_LG_010 | Browser back after logout | User logged out | Press browser back | --- | User remains logged out | ⚡ Medium | ⬜ |
| TC_LG_011 | Login with inactive account | Account disabled | Try login | Inactive account | Login should fail | ⚡ Medium | ⬜ |
| TC_LG_012 | Multiple wrong attempts | Same | Enter wrong details 5 times | Wrong credentials | Account should be blocked temporarily | 🔥 High | ⬜ |
| TC_LG_013 | Password hidden | Login page | Type password | --- | Password should display as dots | 🟢 Low | ⬜ |
| TC_LG_014 | Copy password text | Same | Try copying password | --- | Password should not be copied | 🟢 Low | ⬜ |
| TC_LG_015 | Password in page source | Same | Inspect element | --- | Password must not be visible | 🔥 High | ⬜ |
| TC_LG_016 | Login after changing password | Password changed | Login with new password | New password | Login should succeed | 🔥 High | ⬜ |
| TC_LG_017 | Close browser after login | Logged in | Re-open browser | --- | User remains logged in | ⚡ Medium | ⬜ |
| TC_LG_018 | Session timeout | No activity | Wait 30 minutes | --- | User should auto logout | ⚡ Medium | ⬜ |
| TC_LG_019 | Navigation from login page | On login page | Click links | --- | All links should work | 🟢 Low | ⬜ |
| TC_LG_020 | Different ways to open Login page | Website open | Open login page from menu/footer | --- | User lands on login page | 🟢 Low | ⬜ |
| TC_LG_021 | Verify page elements | Login page | Check heading and URL | --- | Correct page content shown | 🟢 Low | ⬜ |
| TC_LG_022 | UI validation | Login page | Verify alignment | --- | UI should be clean | 🟢 Low | ⬜ |
| TC_LG_023 | Cross Browser testing | --- | Test in Chrome/Edge/Firefox | --- | Works properly in all browsers | 🔥 High | ⬜ |

---

# 🔒 Security Test Coverage

- Password Masking
- Session Timeout
- Invalid Login Validation
- Multiple Failed Attempt Handling
- Source Code Security
- Inactive Account Validation

---

# 🌐 Browser Compatibility

| Browser | Supported |
|---|---|
| Google Chrome | ✅ |
| Mozilla Firefox | ✅ |
| Microsoft Edge | ✅ |

---

# 🛠️ Tools Used

- Manual Testing
- Browser Developer Tools
- Bug Tracking System
- Excel / Google Sheets

---

# 📌 Execution Status Legend

| Symbol | Meaning |
|---|---|
| ⬜ | Not Executed |
| ✅ | Passed |
| ❌ | Failed |
| ⚠️ | Blocked |

---

# 🚀 Best Practices

- Always verify expected result carefully
- Attach screenshots for failed test cases
- Retest after bug fixes
- Validate in multiple browsers
- Check responsive UI behavior

---

<div align="center">

## ⭐ Happy Testing ⭐

Made with ❤️ by QA Team

</div>

