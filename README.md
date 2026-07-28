# DecodeLabs Data Analytics Internship — Task 2

## 📊 Project Title: Exploratory Data Analysis (EDA)
**Goal:** Perform exploratory data analysis on cleaned e-commerce transaction data to calculate 5-number statistical summaries, identify numerical outliers, analyze top-performing categories, and assess revenue risk across order statuses.

---

## 📁 Repository Deliverables
- `Cleaned_Raw_data.csv` — Cleaned dataset from Task 1 used for analysis
- `Task2_Notebook.ipynb` — Complete Jupyter Notebook containing all EDA code, statistical calculations, and visualizations

---

## 🔑 Key EDA Highlights & Analysis

1. **5-Number Summary & Descriptive Statistics:**
   - Computed minimum, Q1, median (Q2), Q3, maximum, mean, standard deviation, and IQR across all numerical metrics (`UnitPrice`, `Quantity`, `TotalPrice`).

2. **Outlier Detection (1.5 × IQR Rule):**
   - Applied Interquartile Range thresholds to isolate extreme transactions.
   - Identified high-value order outliers in total pricing without removing critical business signals.

3. **Product & Category Performance:**
   - Aggregated sales metrics by product categories to identify top revenue generators and highest average order value drivers.

4. **Revenue Loss & Risk Analysis:**
   - Calculated revenue volume distributed across order statuses (`Delivered`, `Cancelled`, `Returned`).
   - Highlighted financial risks associated with cancelled and returned order volumes.

---

## 🛠️ Tools & Libraries Used
- **Python 3.x**
- **Pandas & NumPy** (Data aggregation and statistical calculation)
- **Matplotlib & Seaborn** (Data visualization and distribution plots)
- **Jupyter Notebook / JupyterLab**

---

## 👤 Author
- **Email:** kamranali6739@gmail.com
- **Program:** DecodeLabs Data Analytics Internship
