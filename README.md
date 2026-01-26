# SAP-S4HANA-Labs

Hands-on **SAP S/4HANA** lab portfolio covering end-to-end ERP workflows using the **Global Bike (GBI)** dataset.  
This repository documents practical execution across **SD / MM / PP / FI / CO** modules with lab summaries and selected screenshots.

---

## 🎯 Project Goal

This project is designed to document hands-on SAP S/4HANA practice through structured lab execution and supporting evidence.

What this repo demonstrates:
- Hands-on execution of key SAP S/4HANA transactions (not theory-only)
- Understanding of ERP process flow across multiple modules
- Validation of business process impact through screenshots and lab summaries

---

## 🧩 Lab Summaries

All lab documents are available in the `labsummary/` folder.

| Lab | Topic | Modules | Key Learning Outcome |
|---|---|---|---|
| [Lab 1](https://github.com/hyuntaepark-gh/SAP-S4HANA-Labs/blob/main/labsummary/Lab%201_Order_to_cash.pdf) | Order-to-Cash (O2C) | SD → FI | Executed the sales lifecycle from sales order to delivery and billing (FI impact) |
| [Lab 2](https://github.com/hyuntaepark-gh/SAP-S4HANA-Labs/blob/main/labsummary/Lab_2_Materials_Management.pdf) | Materials Management | MM | Practiced the procurement lifecycle (PO → Goods Receipt → inventory updates) |
| [Lab 3](https://github.com/hyuntaepark-gh/SAP-S4HANA-Labs/blob/main/labsummary/Lab_3_Production_Planning.pdf) | Production Planning | PP | Worked with BOM/routing and production order execution flow |
| [Lab 4](https://github.com/hyuntaepark-gh/SAP-S4HANA-Labs/blob/main/labsummary/Lab_4_Controlling.pdf) | Controlling | CO | Explored cost elements and basic cost flow / controlling concepts |
| [Lab 5](https://github.com/hyuntaepark-gh/SAP-S4HANA-Labs/blob/main/labsummary/Lab_5_Integrated_Process.pdf) | Integrated Process | SD + MM + FI + CO | Validated end-to-end integration and data flow across modules |

---

## 📚 Case Study

The case study document is available in the [`case-study/`](./case-study) folder.

- [`ERP_MRP_Case_Study_Dupry_Beauty.pdf`](./case-study/ERP_MRP_Case_Study_Dupry_Beauty.pdf)  
  A structured case study focused on MRP planning logic and ERP process reasoning.

---

## 📷 Screenshot Evidence (Selected)

Selected screenshots are available in the [`screenshot/`](./screenshot) folder as proof of hands-on execution.

Example highlights:
- SD: Quotation creation and pricing conditions
- MM: Purchase Order → Goods Receipt → follow-on document flow
- PP: Material master update (MRP view)
- FI: GL account balance validation

---

## 🛠 Tools & Environment

- SAP S/4HANA (Lab environment)
- SAP GUI (Windows)
- Global Bike (GBI) dataset
- ERP modules: SD, MM, PP, FI, CO

---

## 📌 Notes
- This repository is intended for **learning and portfolio demonstration** purposes.
- Lab PDFs and materials belong to their respective owners/instructor.
- Screenshots may include masked values for privacy/security.

---

## 📁 Repository Structure

```text
SAP-S4HANA-Labs/
├── labsummary/          # Lab PDF summaries (O2C, MM, PP, CO, Integration)
├── case-study/          # Case study PDF
├── screenshot/          # Selected screenshots from SAP execution (evidence of hands-on practice)
└── README.md
