# 🐔 Data-Driven Analysis of Poultry Farm Operations and Live Chicken Supply

## 📌 Project Overview

This project is a **Business Data Management (BDM) Capstone Project** focused on analyzing the operations of **Karthik Reddy Poultry**, a small-scale B2B poultry farm located in Siddipet District, Telangana.

The farm supplies live chickens to nearby **meat shops, hotels, and restaurants**. The project applies data-driven analysis to identify operational problems and provide actionable recommendations for improving **chick survival, sales performance, and inventory cost management**.

The analysis is based on **primary business data collected from the farm for the period July 2025 to September 2025** through daily operational records, manual records, purchase/sales information, and interactions with the business owner.

---

## 🎯 Business Problems

The project addresses three major operational problems:

### 1. 🐣 Chick Mortality

High chick mortality results in financial losses and reduced productivity.

The project analyzes factors such as:

- Shed temperature
- Humidity
- Vaccination
- Ventilation
- Hygiene / litter condition
- Cleaning practices

### 2. 📈 Sales and Revenue Fluctuation

The farm experiences variations in sales and demand.

The project analyzes:

- Birds available
- Birds sold
- Unsold birds
- Average bird weight
- Selling price
- Total sales amount
- Buyer type
- Daily and monthly sales trends

### 3. 📦 Inventory Cost Management

Feed, vaccines, medicines, and hygiene materials contribute to operating costs.

The project identifies high-value inventory items and prioritizes them using **ABC Analysis** to support better stock management and reduce wastage.

---

## 📊 Dataset

The project uses **primary business data collected from Karthik Reddy Poultry**.

**Data Period:** July 1, 2025 – September 30, 2025

### Dataset Categories

| Dataset | Purpose |
|---|---|
| 🐣 Chick Mortality Data | Analyze factors affecting chick mortality |
| 📈 Sales Data | Analyze demand, sales and revenue trends |
| 📦 Inventory Data | Analyze inventory consumption and cost |

### 🔗 Dataset

**[Access Dataset & Supporting Evidence](https://drive.google.com/drive/folders/1ZsQzRXFA9x4W8ZZUfXPyhwjINgj0StTT?usp=sharing)**

The dataset and supporting evidence include information collected through farm records, business-owner interaction, and transaction records.

---

## 🧹 Data Cleaning & Preprocessing

The collected data was cleaned and standardized before analysis.

The preprocessing included:

- Handling missing values
- Identifying duplicate records
- Correcting data-entry inconsistencies
- Standardizing categorical variables
- Normalizing item names
- Standardizing measurement units
- Creating derived variables such as mortality rate
- Calculating inventory consumption value

**Python:** Pandas, NumPy  
**Spreadsheet:** Microsoft Excel / Google Sheets

---

## 📐 Methodology

The project follows a structured business analytics workflow:

```text
Primary Business Data
        ↓
Data Collection
        ↓
Data Cleaning & Preprocessing
        ↓
Descriptive Statistics
        ↓
 ┌──────────────┬────────────────┬────────────────┐
 ↓              ↓                ↓
Regression    Time-Series       ABC Analysis
Analysis      Analysis          Analysis
 ↓              ↓                ↓
Mortality      Sales Trends     Inventory Costs
        \         |              /
         \        |             /
          └───────┴────────────┘
                  ↓
          Business Insights
                  ↓
          Recommendations
