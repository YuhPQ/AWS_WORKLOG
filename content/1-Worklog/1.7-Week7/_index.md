---
title: "Worklog Week 7"
date: 2026-02-23
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Objectives of Week 7:

* Improve user experience in the e-commerce system.  
* Build and complete the cart system.  
* Ensure data synchronization between frontend and backend.  
* Enhance product UI and purchasing flow.  
* Start exploring the coupon system.  

---

### Tasks performed during this week:

| Day | Tasks | Start Date | End Date | Resources |
| --- | ----- | ---------- | -------- | --------- |
| 2 | - Complete user authentication flow: <br>&emsp; + Login / Register flow <br>&emsp; + Store JWT on frontend <br> - Differentiate between user and guest modes | 23/02/2026 | 23/02/2026 | |
| 3 | - Build product UI: <br>&emsp; + Product listing page <br>&emsp; + Product detail page <br> - Display full product information (image, price, description, skin type) | 24/02/2026 | 24/02/2026 | |
| 4 | - Implement cart system (Guest mode): <br>&emsp; + Add products to cart (LocalStorage) <br>&emsp; + Display cart quantity on header icon <br> - Improve UX: loading state, toast notifications | 25/02/2026 | 25/02/2026 | |
| 5 | - Enhance cart functionality: <br>&emsp; + Prevent spam clicks (disable button) <br>&emsp; + Limit product quantity (max = 5) <br> - Implement increase/decrease/remove item features | 26/02/2026 | 26/02/2026 | |
| 6 | - Synchronize cart data: <br>&emsp; + Merge LocalStorage → Database on login <br>&emsp; + Real-time updates (save-on-click) <br> - Explore coupon system concepts | 27/02/2026 | 27/02/2026 | |

---

### Achievements of Week 7:

* Completed authentication flow:
  * Users can register and log in  
  * JWT is stored and used in requests  

---

* Built product UI:
  * Product listing page  
  * Product detail page  
  * Full product information displayed  

---

* Implemented cart system:

* Supported Guest mode:
  * Cart data stored using LocalStorage  

---

* Improved user experience:
  * Loading states during interactions  
  * Toast notifications when adding products  
  * Prevented spam clicks (disabled buttons)  

---

* Applied data constraints and controls:
  * Maximum 5 items per product  
  * Handled increase/decrease/remove actions  

---

* Implemented cart data synchronization:
  * Merged LocalStorage data into database on login  
  * Real-time updates (save-on-click)  

---

* Ensured data consistency across:
  * Frontend (LocalStorage)  
  * Backend  
  * Database (Prisma)  

---

* Tested and validated system flows:
  * Guest adds products to cart  
  * User logs in without losing cart data  
  * Cart operations update correctly  

---

* Started exploring coupon system:
  * How to store coupons in database  
  * How to apply discounts for users  