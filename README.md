# Sales Data Analysis

A simple Python project for **data analysis and visualization**.  
This project uses pandas, matplotlib, and seaborn to analyze a sales dataset and generate visual insights.

---

## 🛠 Features

- Load sales data from a CSV file  
- Perform basic data cleaning (drop missing values)  
- Generate descriptive statistics  
- Create visualizations:
  - Number of products per category  
  - Sales over time  
- Save summary and graphs to output folder  

---

## ✅ How to Use

### 1. Clone the repository

```bash
git clone https://github.com/l-slima/data-analysis.git
cd data-analysis
````

### 2. (Optional) Create and activate a virtual environment

```bash
python3 -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Prepare the dataset

Place your CSV file in the `data/` folder.
For example, `data/sales.csv`:

```csv
Date,Product,Category,Sales
2025-09-01,Notebook A,Electronics,1200
2025-09-01,Mouse B,Electronics,25
2025-09-02,Notebook A,Electronics,1300
2025-09-02,Chair C,Furniture,150
2025-09-03,Desk D,Furniture,300
2025-09-03,Headphones E,Electronics,80
2025-09-04,Mouse B,Electronics,30
2025-09-04,Notebook A,Electronics,1250
2025-09-05,Chair C,Furniture,170
2025-09-05,Desk D,Furniture,310
2025-09-06,Headphones E,Electronics,90
2025-09-06,Notebook F,Electronics,1400
2025-09-07,Desk D,Furniture,320
2025-09-07,Mouse G,Electronics,40
```

### 5. Run the analysis

```bash
python src/analysis.py
```

This will generate:

* `output/summary.csv` → descriptive statistics
* `output/category_count.png` → count of products per category
* `output/sales_over_time.png` → sales trend over time

---

## 📁 Project Structure

```
data-analysis/
│   README.md
│   requirements.txt
│
├── data/              # CSV files
│     sales.csv
├── src/               # Python scripts
│     analysis.py
├── notebooks/         # Optional Jupyter notebooks
│     analysis.ipynb
└── output/            # Generated summary and plots
```

---

## ✨ Possible Improvements

* Use a **database** instead of CSV files
* Add **interactive plots** with Plotly or Dash
* Perform **more advanced statistical analysis**
* Add **filtering by category, date, or product**
* Create a **dashboard** for real-time visualization

---

## 🧑‍💻 Author

Lucas de Souza Lima — Python enthusiast, focused on data analysis and visualization projects.
[GitHub Profile](https://github.com/l-slima)

---
