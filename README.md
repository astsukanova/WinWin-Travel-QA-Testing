# WinWin.travel — Manual QA Testing Project

## Project Overview
Comprehensive manual testing of the WinWin.travel platform, focusing on the registration flow, search engine functionality, and AI-driven Chat Centre.

## Testing Scope
* **API & Backend:** Identified server-side errors (503 Service Unavailable) and JSON parsing issues.
* **Functional Testing:** Verified hotel search logic, date validation, and AI response accuracy.
* **UI/UX Testing:** Evaluated input field behaviors, button states, and responsive design.
* **Validation:** Checked character counters and registration form error handling.

##  Bug Reports (6 Issues Found)
I have documented **6 high-impact bugs** in the [Issues]([https://github.com/astsukanova/WinWin-Travel-QA-Testing/issues](https://github.com/astsukanova/WinWin-Travel-QA-Testing/issues) tab:
1. **Critical:** 503 API Errors during page load.
2. **Functional/UX:** Search button displays "Error" state without validation feedback.
3. **Critical:** Search suggestions fail to load (Dropdown bug).
4. **UX/Logic:** Conflicting date displays for long stays (>30 days).
5. **Technical:** Raw JSON/HTML leak during registration failure.
6. **Data Consistency:** Search results resetting to "0 offers" on valid queries.

## Environment
* **Browser:** Chrome 147.0.0.0
* **OS:** Windows 10
* **Tools:** Browser DevTools (Network tab analysis).
