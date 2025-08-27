# Video Game Sales Analysis (Excel Project)

This project analyzes video game sales data (16,500+ records) from Kaggle using **Microsoft Excel**. It includes **data cleaning** and **pivot table analysis** to uncover trends in sales, genres, and publishers.

---

## 📌 Project Overview
- Dataset: [Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)
- Tool Used: **Microsoft Excel**
- Total Records: ~16,598 rows

---

## ✅ Step 1: Data Cleaning
1. **Column A & B**: Leave data as is.
2. **Column C (Platform)**: Convert values like `2600` to text.
3. **Column D (Year)**: Replace `N/A` with **Mode** of the column.
4. **Column K (Global Sales)**: Use `=SUM(G:H:I:J)` to recalculate the correct value.
✔ Data is now clean and ready for analysis.

---

## ✅ Step 2: Pivot Table Analysis
**Questions Answered:**
1. **Genre with the Highest % of Games**
   - Insert Pivot Table → Rows: Genre, Columns: Name (Count → %)
   - Sort in descending order.

2. **Genre with the Highest Sales**
   - Modify previous pivot → Sum of Global Sales
   - Sort in descending order.

3. **Top 10 Publishers**
   - Pivot Table → Row: Publisher
   - Sort by total sales, display **Top 10**.

4. **Top 10 Games Sold**
   - Pivot Table → Row: Name
   - Sort by global sales, display **Top 10**.

5. **Year of Highest Sales**
   - Pivot Table → Row: Year
   - Sort descending to find peak sales year.

---

## 🛠️ Technology Used
- **Microsoft Excel** (Data Cleaning & Pivot Tables)

---

## ✅ Key Learnings
- Cleaning and preparing large datasets in Excel.
- Applying pivot tables for business insights.
- Visualizing sales trends by genre, publisher, and year.

