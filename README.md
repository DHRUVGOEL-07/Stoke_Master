 **StockMaster – Inventory Management System (IMS)**

**StockMaster** is an **intuitive and modular Inventory Management System (IMS)** built for a hackathon using **React, Node.js, Express, SQLite3, and Tailwind CSS**. It **digitizes and streamlines stock operations**, replacing manual registers and Excel sheets with a **centralized, real-time, and user-friendly application**.

---

 **Why StockMaster?**

Managing stock manually is slow and error-prone. **StockMaster** helps businesses:

* **Inventory Managers:** Gain complete control over incoming and outgoing stock
* **Warehouse Staff:** Track, move, and count items effortlessly
* **Real-Time Visibility:** Dashboards and alerts show inventory status instantly
* **Multi-Warehouse Support:** Manage multiple locations with ease

---

 **Key Features**

 **Smart Authentication**

* Secure **user sign-up and login**
* **OTP-based password reset**
* Direct access to a personalized **Inventory Dashboard**

 **Powerful Dashboard**

Quickly see the pulse of your inventory:

* **Total products in stock**
* **Low stock / Out of stock alerts**
* **Pending receipts & deliveries**
* **Scheduled internal transfers**

 **Dynamic Filters**

* By document type: **Receipts, Delivery, Internal, Adjustments**
* By status: **Draft, Waiting, Ready, Done, Canceled**
* By **warehouse/location** or **product category**

---

 **Core Modules**

 **1. Product Management**

* Create/update products with **Name, SKU/Code, Category, Unit, Initial stock**
* Check **stock availability per location**
* Set **categories and reordering rules** for smarter inventory control

 **2. Operations**

 **Receipts (Incoming Stock)**

* Record items arriving from vendors
* **Stock automatically updated**
  **Example:** Receive 50 units of “Steel Rods” → **stock +50**

 **Delivery Orders (Outgoing Stock)**

* Pick, pack, and ship orders
* **Stock decreases automatically**
  **Example:** Deliver 10 chairs → **stock –10**

 **Internal Transfers**

* Move stock between warehouses or racks
* **All transfers logged in the ledger**

 **Stock Adjustments**

* Correct discrepancies between **recorded stock** and **physical count**
* System **auto-updates and logs changes**

---

 **Inventory Flow Example**

1. **Receive goods from vendor:** 100 kg steel → **stock +100**
2. **Move to production rack:** Internal transfer → **stock location updated**
3. **Deliver finished goods:** Deliver 20 kg steel → **stock –20**
4. **Adjust damaged items:** 3 kg steel damaged → **stock –3**

**All operations are tracked in a stock ledger** for full visibility.

---

 **Technology Stack**

* **Frontend:** React + Tailwind CSS + JavaScript
* **Backend:** Node.js + Express
* **Database:** SQLite3 (local, relational)
* **Version Control:** Git

---

 **UI/UX Highlights**

* **Responsive and clean interface** using Tailwind CSS
* **Intuitive navigation** and menu placement
* **Robust validation** to prevent errors
* **Smart search and filters** for quick access

---

 **Hackathon Highlights**

* Uses **real-time dynamic data** with SQLite3
* Demonstrates **backend API design, database modeling, and inventory logic**
* Fully **offline-capable** with local database
* Focused on **functional design and practical impact**

---

**StockMaster** makes inventory management **fast, reliable, and transparent**, helping businesses **save time, reduce errors, and stay on top of their stock effortlessly**.
