🧪 Swag Labs (SauceDemo) - Manual Testing Project

📌 Project Overview
This repository contains complete manual testing artifacts for the **Login Module** of Swag Labs (SauceDemo), a demo e-commerce application. The testing covers functional, negative, and UI validation scenarios.

🎯 Scope of Testing
- **Module:** Login
- **Testing Type:** Manual Functional & UI Testing
- **Application URL:** https://www.saucedemo.com

📂 Repository Contents
| File/Folder | Description |
|-------------|-------------|
| `Test Summary Report.pdf` | Final test execution summary and conclusion |
| `TS_TC_BUG_Report.xlsx` | Complete test scenarios, test cases, and bug report |
| `Screen_shots/` | Visual evidence of bugs found during execution |

📊 Test Execution Summary
- **Total Test Scenarios:** 12
- **Total Test Cases:** 16
- **Executed:** 16
- **Passed:** 15
- **Failed:** 1
- **Pass Rate:** 93.75%

🐛 Defects Identified
| Bug ID | Title | Severity | Status |
|--------|-------|----------|--------|
| BUG_001 | Error message text gets cut off due to fixed height (60px) | Medium | Open |

**Root Cause:** The error message container has a fixed `height: 60px` with `line-height: 20px`, which causes 3-line error text to overflow and get clipped. 
**Suggested Fix:** Change `height: 60px` to `min-height: 60px` or `height: auto`.

🛠️ Tools Used
- **Manual Testing**
- **Google Chrome DevTools** (for CSS inspection)
- **Microsoft Excel** (Test Case & Bug Management)
- **MS Word** (Test Summary Reporting)

👨‍💻 Tester
Md Abu Bakkar Siddik  
Email: mdshoyan30@gmail.com
