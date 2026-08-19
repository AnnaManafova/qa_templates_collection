# 🚀 General Web Smoke Checklist

> **Purpose:** Ultra-fast verification to ensure the build is stable enough for deeper testing.  
> **⏱️ Estimated time:** 5–10 minutes  
> **🎯 Scope:** Any web application

---

## 1. 🌐 Availability & Critical Errors

- [ ] **`Verify`** that the main URL opens and returns a `200 OK` status *(no 404, 500 errors)*.
- [ ] **`Check`** the browser console on initial load to ensure there are no unhandled exceptions or blocking errors.
- [ ] **`Verify`** that the SSL certificate is valid and a secure HTTPS connection is established.

---

## 2. 🔑 Authentication (Core Flow)

- [ ] **`Test`** successful user login using valid credentials.
- [ ] **`Verify`** that the user dashboard or profile page loads successfully after login.
- [ ] **`Test`** the logout functionality and ensure the user session terminates completely.

---

## 3. 🗺️ Core Functionality & Navigation

- [ ] **`Verify`** that the main navigation links open the primary functional pages of the site.
- [ ] **`Check`** that high-priority interactive forms *(e.g., Contact Us, Lead Generation)* can be submitted.
- [ ] **`Ensure`** that core UI components *(like search bars or filters)* respond to user actions without crashing.

---

## 4. 📱 Environment & Responsiveness (Minimum)

- [ ] **`Verify`** that the site home page loads and functions correctly on mobile viewport size.
- [ ] **`Ensure`** that the application is fully accessible and interactive in the primary target browser *(e.g., Chrome)*.

---

## 📊 Execution Summary

| Metric | Value |
| :--- | :--- |
| 📅 **Test Date** | `__.__.____` |
| 🕒 **Start Time** | `__:__` |
| ⏳ **End Time** | `__:__` |
| 🔢 **Total Checks** | **14** |
| ✅ **Passed** | `___` |
| ❌ **Failed** | `___` |
| 🚫 **Blocked** | `___` |

### 🐛 Issues Found
*Note: Any bug found during a Smoke Test is usually considered Critical or Blocker.*

| ID | Description | Severity | Ticket Link |
| :--- | :--- | :--- | :--- |
| **BUG-01** | *e.g., Internal Server Error (500) on login attempt* | 🔥 Blocker | `[Link]` |
| **BUG-02** | | | |

---

## ✅ Conclusion

**Final Status:** 🟩 **PASS** / 🟥 **FAIL**  
*(Rule: If any single item in this checklist fails, the entire Smoke Test is considered FAILED).*

💬 **Notes:**
- 
