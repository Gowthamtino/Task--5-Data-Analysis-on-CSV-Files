# Task--5-Data-Analysis-on-CSV-Files
# Sales Data Analysis using Pandas

## Objective  
Analyze sales data from a CSV file using **Python** and **Pandas**, and visualize the results using **Matplotlib**.

---

## Tools Required  
- Python 3.x  
- Pandas → `pip install pandas`  
- Matplotlib → `pip install matplotlib`  
- Jupyter Notebook or Google Colab  

---

## Dataset Requirements  
Your `sales_data.csv` should have the following columns:  
- **Order Date** → Date of the order (format: `YYYY-MM-DD`)  
- **Category** → Product category (e.g., Electronics, Furniture)  
- **Product Name** → Name of the product  
- **Sales** → Sales amount (numeric)  

Example:  
| Order Date | Category    | Product Name | Sales |
|------------|------------|--------------|-------|
| 2024-01-01 | Electronics | Laptop       | 1200  |
| 2024-01-16 | Furniture   | Chair        | 300   |

---

## Steps in the Code
1. **Load CSV file** using `pd.read_csv()`
2. **View dataset** with `.head()`, `.info()`, `.describe()`
3. **Analyze total sales by category** using `groupby()` and `sum()`
4. **Plot bar chart** for sales by category  
5. **Analyze monthly sales trend** by converting `Order Date` to datetime  
6. **Plot line chart** for monthly trend  
7. **Find top 5 products by sales** and plot them as a bar chart  

---

## Output
The notebook will generate:
- **Printed outputs** for dataset info, summary, and group analysis  
- **Charts:**
  - 📊 Bar chart — Total Sales by Category  
  - 📈 Line chart — Monthly Sales Trend  
  - 📊 Bar chart — Top 5 Products by Sales  

---

## How to Run
1. Clone or download the repository  
2. Place `sales_data.csv` in the same directory as the notebook  
3. Open the notebook in **Jupyter** or **Colab**  
4. Run all cells to see the analysis and charts  

---

## Outcome
- Learned how to **load and inspect CSV files**  
- Used **Pandas groupby and aggregation** for analysis  
- Created **visual insights** with Matplotlib
