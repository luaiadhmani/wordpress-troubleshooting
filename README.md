# 🛠️ WordPress Troubleshooting Guide

This project documents **real WordPress issues** I fixed during practical training using LocalWP. Each issue includes **before/after screenshots**, a **clear explanation**, and a **step-by-step solution**. Ideal for showcasing WordPress troubleshooting skills to clients or employers.

---

## ✅ Issues Covered (with Fixes)

| # | Issue Description                         | Screenshot File Name              | Status   |
|--:|-------------------------------------------|-----------------------------------|----------|
| 1 | HTTP Error 500                            | `http-error-500.png`              | ✅ Fixed |
| 2 | White Screen of Death                     | `white-screen-issue.png`          | ✅ Fixed |
| 3 | Site Not Working After Update             | `site-not-working-fixed.png`      | ✅ Fixed |
| 4 | 404 Page Not Found                        | `404-page-not-found-fixed.png`    | ✅ Fixed |
| 5 | Button Not Working                        | `button-not-working.png`          | ✅ Fixed |
| 6 | Form Not Showing                          | `form-not-showing.png`            | ✅ Fixed |
| 7 | Header Display Error                      | `header-error-fixed.png`          | ✅ Fixed |
| 8 | Mobile Layout Broken                      | `mobile-layout-broken.png`        | ✅ Fixed |

---

## 🧰 Tools Used

- 🖥️ **LocalWP** – Local environment for WordPress testing  
- 🧩 **Browser Developer Tools** – Inspecting layout and responsiveness  
- ⚙️ **WordPress Dashboard** – Plugin/theme control, settings  
- 🔌 **Plugin Deactivation Testing** – Conflict isolation  
- 🎨 **Elementor / Cache Clearing** – Front-end fixes  

---

## 🖼️ Example Fixes (Before / After)

---

### ⚠️ 1. HTTP Error 500

**Before**  
![HTTP Error 500 - Before](screenshots/http-error-500.png)

**After**  
Issue fixed after identifying a missing semicolon in `functions.php`.

**Steps:**
1. Opened the theme files using LocalWP.
2. Found a syntax error in `functions.php`.
3. Corrected the code and refreshed the site.

---

### ⚪ 2. White Screen of Death

**Before**  
![White Screen](screenshots/white-screen-issue.png)

**After**  
Issue resolved by disabling a faulty plugin causing PHP errors.

**Steps:**
1. Accessed the plugin folder via LocalWP.
2. Renamed the suspected plugin folder.
3. Site loaded successfully again.

---

### 🟠 3. Button Not Working

**Before**  
![Button Not Working](screenshots/button-not-working.png)

**After**  
Fixed by checking Elementor settings and removing a conflicting plugin.

**Steps:**
1. Inspected the button using the browser tools.
2. Identified overlapping CSS from another plugin.
3. Disabled the plugin and adjusted button layout in Elementor.

---

## 🧠 Purpose of This Project

> To practice and showcase real troubleshooting skills in WordPress by solving common errors in a real test environment. Each issue simulates what clients typically face.

---

## 📂 Screenshots

All images are located inside the [`screenshots/`](./screenshots) folder and renamed clearly to reflect each issue.

---

## 👤 Who This Is For

- Clients needing fast, effective WordPress fixes  
- Freelancers looking to offer debugging services  
- Developers learning how to resolve real-world issues  

---

## 📫 Contact

Need help with your WordPress site?  
Feel free to reach out via [GitHub](https://github.com/luaiadhmani).

---

## 🔖 GitHub Tags (Suggested)

> `wordpress` &nbsp;&nbsp; `troubleshooting` &nbsp;&nbsp; `localwp` &nbsp;&nbsp; `elementor` &nbsp;&nbsp; `debugging` &nbsp;&nbsp; `freelance`
