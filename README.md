# 💰 SpendDNA — Your Wallet's Financial DNA

> A financial analytics project that transforms raw transaction data into meaningful insights about spending behaviour, vendors, categories, trends, anomalies, and financial habits.

---

## 📌 Project Overview

**SpendDNA** is a financial analytics project designed to understand an individual's spending behaviour from transaction data.

The project takes raw transaction records, cleans and standardizes the data, identifies vendors and spending categories, analyses monthly and time-based spending patterns, detects unusual transactions, and generates a consolidated financial report.

The goal is to answer questions such as:

- 💳 How much money was spent?
- 💰 How much money was received?
- 🛍️ Which categories consume the most money?
- 🏪 Which vendors are used most frequently?
- 📅 How does spending change month by month?
- 🕐 What time of day has the highest spending activity?
- 🚨 Which transactions appear unusual?
- 🧬 What type of spender does the user appear to be?

---

## 🎯 Objectives

The main objectives of SpendDNA are:

1. Clean and standardize raw transaction data.
2. Extract and normalize merchant/vendor names.
3. Categorize transactions automatically.
4. Calculate important financial statistics.
5. Analyse monthly spending patterns.
6. Analyse time-of-day spending behaviour.
7. Detect potentially anomalous transactions.
8. Identify spending archetypes.
9. Generate a final consolidated financial report.
10. Present financial insights in a simple and understandable format.

---

## 🛠️ Features

### 1. Transaction Parser

The transaction parser prepares the raw dataset for analysis.

It performs:

- Date parsing
- Multiple date format handling
- Amount cleaning
- Currency symbol removal
- Comma and formatting cleanup
- Transaction type standardization
- Duplicate detection/removal
- Invalid value checking

---

### 2. Vendor Extractor

Merchant names are extracted and normalized using keyword-based matching.

Example:

```text
ZOMATO ORDER
Zomato Food
ZOMATO ONLINE

        ↓

     Zomato
