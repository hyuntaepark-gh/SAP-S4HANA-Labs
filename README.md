# SAP S/4HANA Labs – ERP Process & Document Flow (Global Bike)

Hands-on **SAP S/4HANA lab exercises** using the **Global Bike (GBI)** dataset.  
This repository is built to demonstrate practical understanding of **end-to-end ERP processes** and how SAP transactions connect through **Document Flow**.

> 🔒 Note: Some fields in screenshots are intentionally masked for privacy/security.

---

## 🎯 Project Goals
- Build familiarity with SAP S/4HANA navigation and key screens  
- Understand how business transactions are created and tracked in SAP  
- Practice procurement & inventory-related process flows  
- Create a portfolio-ready record of hands-on SAP learning  

---

## ✅ What I Practiced
- SAP GUI navigation and screen structure
- Search help (F4) and selection criteria usage
- Purchasing Documents filtering & lookup
- Basic procurement flow concepts (PR / PO)
- Goods Receipt (GR) posting and confirmation
- Document Flow tracking and verification

---

## 🧩 Lab Summaries

All lab documents are available in the `labsummary/` folder.

| Lab | Topic | Modules | Key Learning Outcome |
|---|---|---|---|
| [Lab 1](https://github.com/hyuntaepark-gh/SAP-S4HANA-Labs/blob/main/labsummary/Lab%201_Order_to_cash.pdf) | Order-to-Cash (O2C) | SD → FI | Executed the sales lifecycle from sales order to billing and payment |
| [Lab 2](https://github.com/hyuntaepark-gh/SAP-S4HANA-Labs/blob/main/labsummary/Lab_2_Materials_Management.pdf) | Materials Management | MM | Practiced the procurement lifecycle (PO → Goods Receipt → Inventory updates) |
| [Lab 3](https://github.com/hyuntaepark-gh/SAP-S4HANA-Labs/blob/main/labsummary/Lab_3_Production_Planning.pdf) | Production Planning | PP | Worked with BOM/routing and production order execution flow |
| [Lab 4](https://github.com/hyuntaepark-gh/SAP-S4HANA-Labs/blob/main/labsummary/Lab_4_Controlling.pdf) | Controlling | CO | Explored cost elements and basic cost flow/controlling concepts |
| [Lab 5](https://github.com/hyuntaepark-gh/SAP-S4HANA-Labs/blob/main/labsummary/Lab_5_Integrated_Process.pdf) | Integrated Process | SD + MM + FI + CO | Validated end-to-end integration and data flow across modules |

---

## 🧾 SAP S/4HANA Lab Evidence (Global Bike Case)

This section contains screenshots from SAP UCC training labs to demonstrate hands-on experience across key ERP processes.

### 1) SAP Navigation / System Access
![SAP Easy Access](docs/screenshots/SAP_EasyAccess_MainMenu_NavigationTree.png)

### 2) Material / MRP Setup (Production Planning)
![MRP View](docs/screenshots/Step01_PP_ChangeMaterial_MRPView.png)

### 3) Purchasing Documents Search
![Purchasing Documents](docs/screenshots/Step09_Purchasing_PurchasingDocuments_SearchCriteria.png)

### 4) Create Purchase Order (PO)
![Create PO](docs/screenshots/Step10_MM_CreatePurchaseOrder_ItemOverview.png)

### 5) PO Conditions & Delivery Schedule
![PO Conditions & Delivery Schedule](docs/screenshots/Step10_MM_PO_Conditions_And_Delivery_Schedule.png)

### 6) Display Purchase Order (Validation)
![Display PO](docs/screenshots/Step11_MM_DisplayPurchaseOrder_POOverview.png)

### 7) Goods Receipt (GR) for Purchase Order
![GR Create](docs/screenshots/Step16_MM_GoodsReceipt_InitialScreen.png)
![GR Posted](docs/screenshots/Step16_MM_GoodsReceipt_Create_GRforPO.png)

### 8) PO History / Follow-on Documents
![PO History](docs/screenshots/Step17_MM_PO_History_FollowOnDocuments.png)

### 9) FI Impact (G/L Balance Display)
![G/L Balance](docs/screenshots/Step18_FI_GLAccount_BalanceDisplay.png)

---

## 📚 Case Study

The case study document is available in the [`case-study/`](./case-study) folder.

- [`ERP_MRP_Case_Study_Dupry_Beauty.pdf`](./case-study/ERP_MRP_Case_Study_Dupry_Beauty.pdf)  
  A structured case study focused on MRP-related planning and ERP process reasoning.

---

## 🛠 Tools & Environment

- SAP S/4HANA (Lab environment)
- Global Bike (GBI) dataset
- ERP modules: SD, MM, PP, FI, CO

---

## 📌 Notes
- This repository is intended for **learning and portfolio demonstration** purposes.
- Lab PDFs and materials belong to their respective owners/instructor.
- Screenshots may include masked values for privacy/security.

---

## 📁 Repository Structure

```

SAP-S4HANA-Labs/
├── labsummary/          # Lab PDF summaries (O2C, MM, PP, CO, Integration)
├── case-study/          # Case study PDF
├── screenshot/          # Selected screenshots from SAP execution (evidence of hands-on practice)
└── README.md

```
