# student-sales-performance-eda
---
# 📊 Sales Performance Analysis using EDA and Predictive Modeling

This project performs **Exploratory Data Analysis (EDA)** and builds a **Linear Regression model** to analyze and predict **sales performance** using a real-world dataset. It includes data cleaning, visualization, and predictive modeling steps to derive meaningful insights from the data.

---

## 📁 Dataset

The dataset used is derived from a **Global Superstore sales data**, containing:
- 🛒 Order details: `order_id`, `item_id`, `sku`, `qty_ordered`
- 📅 Date: `order_date`, `year`, `month`
- 💰 Financials: `price`, `value`, `discount_amount`, `total`
- 🧾 Customer details: `full_name`, `gender`, `region`, `state`, etc.
- 🏷️ Product: `category`, `payment_method`, `status`
- 📉 Calculated field: `Discount_Percent`

---

## 🛠️ Tools and Technologies Used

- **Python** 🐍
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib** and **Seaborn** for data visualization
- **Scikit-learn** for Linear Regression modeling

---

## 🔍 Project Workflow

### 1. 📥 Data Loading
- Dataset was loaded from `kagglehub` and inspected for structure and content.

### 2. 🧹 Data Cleaning
- Removed duplicates.
- Handled missing values.
- Converted `order_date` to `datetime` format.

### 3. 📊 Exploratory Data Analysis (EDA)
- Visualized:
  - Sales distribution over time.
  - Sales by Region (Bar Chart).
  - Sales by Category (Pie Chart).
  - Relationship between `Profit` and `Discount` (Scatter Plot).

### 4. 📈 Predictive Modeling
- Built a **Linear Regression Model** to predict **Total Sales** using:
  - `Profit`
  - `Discount_Percent`
- Evaluated model using:
  - **R² Score**
  - **Mean Squared Error (MSE)**
- Plotted **Actual vs Predicted Sales** to visualize model accuracy.

---

## 📌 Key Insights

- Discount has a visible but nonlinear relationship with profit.
- Certain regions and categories consistently outperform others in terms of total sales.
- The model shows a strong predictive power for estimating sales based on financial inputs.

---

## 📷 Sample Visualizations

- 📉 Time Series plot for Sales
- 📊 Region-wise Bar Chart
- 🥧 Category-wise Pie Chart
- 🔁 Actual vs Predicted Sales Scatter Plot

---

## 📝 Conclusion

This project demonstrates a complete data science pipeline—from loading and cleaning real-world data to performing EDA and building a simple but effective predictive model.

---

## 🚀 Future Scope

- Use advanced models like Random Forest or XGBoost.
- Integrate more features like Customer demographics or Seasonal patterns.
- Deploy as a web application for real-time sales prediction.

---

## 📚 How to Run

1. Clone the repo  
```bash
git clone https://github.com/your-username/sales-performance-eda.git
```

2. Install required packages  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the Jupyter Notebook  
```bash
jupyter notebook Sales_EDA_and_Prediction.ipynb
```

