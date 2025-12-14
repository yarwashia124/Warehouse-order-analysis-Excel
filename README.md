# Warehouse-order-analysis-Excel

# 📦 Excel Logical Functions Task

## 📁 Dataset

Excel file containing order and shipment details.

## 🎯 Task Objective

This project focuses on using **Excel text functions, logical functions, and conditional logic** to prepare a clean and decision-ready warehouse report.

## ✅ Steps Performed

### 1️⃣ Extract State (Text Function)

* Created a new column **State**
* Used `LEFT()` to extract the first two letters from **RegionCode**
  *(Example: TX, CA)*

### 2️⃣ URGENT SHIP Flag (Logical AND)

* Created column **URGENT SHIP**
* Condition:

  * Status = **PENDING**
  * ItemCount < **5**
* Result:

  * **SHIP NOW** if both conditions are true
  * **HOLD** otherwise

### 3️⃣ Warehouse Note (Text + Logic)

* Created column **Warehouse Note** using `CONCATENATE` / `&`
* Logic:

  * If **SHIP NOW** → `State - RUSH ORDER`
  * If **HOLD** → `State - WAIT`

### 4️⃣ Presentation

* Applied **borders**
* Headers made **bold**
* Final report formatted to be **Boss-Ready**

## 🛠 Tools Used

* Microsoft Excel

## 📌 Learning Outcome

* Text functions (`LEFT`)
* Logical functions (`AND`, `IF`)
* Conditional decision making
* Professional report formatting

