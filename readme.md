
<div align="center">

# 🛒 E-Commerce Website Manual Testing Documentation

![Testing](https://img.shields.io/badge/Testing-Manual-blue?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-Dummy_Ecommerce-success?style=for-the-badge)
![QA](https://img.shields.io/badge/QA-Test_Cases-orange?style=for-the-badge)

# 🧪 TestShopEasy - E-Commerce Testing Project

### Complete Manual QA Test Cases Documentation

</div>

---

# 📌 Project Description

This repository contains complete manual testing test cases for a dummy e-commerce website called **ShopEasy**.

The project covers testing of:

- 🔐 Login Module
- 👤 Registration Module
- 🛍️ Product Module
- 🛒 Cart Module
- 💳 Checkout & Payment
- 📦 Order Management
- ❤️ Wishlist
- 🔎 Search Functionality
- 📱 Responsive UI Testing
- 🔒 Security Testing

---

# 🌐 Dummy Website Information

| Property | Details |
|---|---|
| Website Name | ShopEasy |
| Website Type | E-Commerce |
| Testing Type | Manual Testing |
| Browser Support | Chrome, Firefox, Edge |
| Environment | QA / Staging |
| Base URL | https://shopeasy-demo.com |
| Test Case Format | Functional + UI + Security |

---

# 📊 Test Case Summary

| Module | Total Cases |
|---|---|
| Login | 15 |
| Registration | 10 |
| Product | 12 |
| Cart | 10 |
| Checkout | 10 |
| Order | 8 |
| Search | 5 |
| Wishlist | 5 |
| UI / Responsive | 5 |
| Security | 5 |
| TOTAL | 85 |

---

# 🔐 LOGIN MODULE TEST CASES

| TC ID | Test Scenario | Test Steps | Expected Result | Priority |
|---|---|---|---|---|
| LG_001 | Login with valid credentials | Enter valid email & password | Login successful | High |
| LG_002 | Login with invalid password | Enter wrong password | Error message displayed | High |
| LG_003 | Login with empty fields | Keep fields blank | Validation should appear | High |
| LG_004 | Forgot password | Click forgot password | Reset page opens | Medium |
| LG_005 | Password hidden check | Type password | Password masked | Low |
| LG_006 | Session timeout | Stay idle 30 mins | Auto logout | Medium |
| LG_007 | Multiple wrong attempts | Enter wrong password 5 times | Account temporarily blocked | High |
| LG_008 | Browser compatibility | Test on browsers | Login works properly | Medium |
| LG_009 | Keyboard navigation | Use Tab + Enter | Login successful | Low |
| LG_010 | Logout functionality | Click logout | User logged out | High |

---

# 👤 REGISTRATION MODULE TEST CASES

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| RG_001 | Register with valid data | Account created |
| RG_002 | Register with existing email | Error message displayed |
| RG_003 | Empty mandatory fields | Validation messages shown |
| RG_004 | Invalid email format | Proper validation |
| RG_005 | Weak password validation | Warning displayed |
| RG_006 | Password mismatch | Error displayed |
| RG_007 | Mobile number validation | Accept valid numbers only |
| RG_008 | Terms & Conditions unchecked | Registration blocked |
| RG_009 | Verify email verification | Verification mail sent |
| RG_010 | Responsive registration page | Proper mobile UI |

---

# 🛍️ PRODUCT MODULE TEST CASES

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| PD_001 | Open product page | Product details visible |
| PD_002 | Product image gallery | Images load correctly |
| PD_003 | Product zoom functionality | Zoom works |
| PD_004 | Add product to cart | Product added |
| PD_005 | Out of stock product | Proper message displayed |
| PD_006 | Product price display | Correct pricing shown |
| PD_007 | Product description | Proper details visible |
| PD_008 | Product review section | Reviews displayed |
| PD_009 | Product sorting | Sorting works |
| PD_010 | Product filtering | Filters work correctly |

---

# 🛒 CART MODULE TEST CASES

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| CT_001 | Add product to cart | Product added |
| CT_002 | Remove product from cart | Product removed |
| CT_003 | Update quantity | Quantity updated |
| CT_004 | Add multiple products | All products added |
| CT_005 | Empty cart validation | Proper message shown |
| CT_006 | Cart total calculation | Correct total |
| CT_007 | Apply coupon code | Discount applied |
| CT_008 | Invalid coupon code | Error displayed |
| CT_009 | Continue shopping button | Redirect correctly |
| CT_010 | Save cart after refresh | Cart persists |

---

# 💳 CHECKOUT MODULE TEST CASES

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| CH_001 | Checkout with valid details | Order placed |
| CH_002 | Empty address validation | Validation shown |
| CH_003 | Payment via card | Payment successful |
| CH_004 | COD payment | Order placed |
| CH_005 | Invalid card details | Payment failed |
| CH_006 | Order summary validation | Correct details shown |
| CH_007 | Shipping calculation | Correct shipping fee |
| CH_008 | Tax calculation | Correct tax shown |
| CH_009 | Checkout page responsiveness | Mobile friendly |
| CH_010 | Payment gateway timeout | Proper error shown |

---

# 📦 ORDER MODULE TEST CASES

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| OD_001 | View order history | Orders displayed |
| OD_002 | Cancel order | Order cancelled |
| OD_003 | Track order | Tracking visible |
| OD_004 | Download invoice | Invoice downloaded |
| OD_005 | Return request | Return accepted |
| OD_006 | Order confirmation email | Email received |
| OD_007 | Order status update | Status updated |
| OD_008 | Multiple order handling | Orders managed properly |

---

# ❤️ WISHLIST MODULE TEST CASES

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| WL_001 | Add to wishlist | Product added |
| WL_002 | Remove from wishlist | Product removed |
| WL_003 | Move wishlist item to cart | Product moved |
| WL_004 | Wishlist persistence | Data saved |
| WL_005 | Guest wishlist validation | Login prompt shown |

---

# 🔎 SEARCH MODULE TEST CASES

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| SR_001 | Search valid product | Product displayed |
| SR_002 | Search invalid product | No results found |
| SR_003 | Search suggestions | Suggestions shown |
| SR_004 | Search special characters | Proper handling |
| SR_005 | Search responsiveness | Fast results |

---

# 📱 UI & RESPONSIVE TEST CASES

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| UI_001 | Mobile responsiveness | Proper mobile UI |
| UI_002 | Tablet responsiveness | Proper tablet UI |
| UI_003 | Broken link validation | No broken links |
| UI_004 | Button alignment | Proper alignment |
| UI_005 | Image responsiveness | Images scale correctly |

---

# 🔒 SECURITY TEST CASES

| TC ID | Test Scenario | Expected Result |
|---|---|---|
| SC_001 | SQL Injection testing | Application secure |
| SC_002 | XSS validation | Scripts blocked |
| SC_003 | Password encryption | Password encrypted |
| SC_004 | Session security | Session protected |
| SC_005 | HTTPS validation | Secure connection |

---

# 🧰 TOOLS USED

- Selenium (Optional)
- Chrome DevTools
- JIRA
- Excel / Google Sheets
- Postman
- BrowserStack

---

# 🌐 BROWSER COMPATIBILITY

| Browser | Status |
|---|---|
| Google Chrome | ✅ Supported |
| Mozilla Firefox | ✅ Supported |
| Microsoft Edge | ✅ Supported |
| Safari | ✅ Supported |

---

# 📌 BUG REPORT FORMAT

| Bug ID | Module | Severity | Status |
|---|---|---|---|
| BUG_001 | Login | High | Open |

---

# 🚀 QA BEST PRACTICES

- Verify expected results carefully
- Capture screenshots for failed cases
- Retest after bug fixes
- Perform cross-browser testing
- Validate responsive design
- Check security vulnerabilities

---

# 📄 LICENSE

This project is created for learning and QA practice purposes only.

---

<div align="center">




</div>
