# Superstore Sales Performance Analysis

An exploratory data analysis (EDA) of a superstore's sales dataset to identify key drivers of revenue and discover strategic business insights. This project uses Python, Pandas, and Seaborn to process, analyze, and visualize sales performance.

---

## 💡 Key Findings

This analysis revealed several key insights into the superstore's sales performance:

1.  **Top Customer Segment:** The **Consumer** segment is the largest contributor to total sales, significantly outperforming the Corporate and Home Office segments.
2.  **Key Product Categories:** **Technology** products generate the highest revenue, closely followed by Furniture. Within Technology, "Phones" and "Copiers" are particularly high-performing sub-categories.
3.  **Consistent Sales Growth:** The analysis shows a consistent year-over-year growth in total sales, indicating a positive business trajectory and successful market expansion.

---

##  Actionable Insights

Based on the analysis, here are some actionable recommendations for the business:

1.  **Focus on Top Segments:** Double down on marketing and sales efforts targeting the **Consumer** segment, as it is the primary driver of revenue.
2.  **Optimize Regional Inventory:** Increase inventory for **Technology** products in the top-performing states to meet demand and maximize sales.
3.  **Review Sub-Category Performance:** Investigate why sub-categories like "Fasteners", "Labels", and "Art" have low sales figures and consider running targeted promotions.

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:**
  - Pandas & NumPy (for data wrangling and analysis)
  - Matplotlib & Seaborn (for data visualization)
- **Environment:** Jupyter Notebook (run in VS Code)

---

## 🚀 Setup and Installation

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/phucndq05/superstore-analysis.git](https://github.com/phucndq05/superstore-analysis.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd superstore-analysis
    ```
3.  **Create and activate a virtual environment (Recommended):**
    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    ```
4.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
5.  **Launch the Jupyter Notebook:**
    ```bash
    jupyter notebook superstore_analysis.ipynb
    ```

---
## 📁 Project Structure
```markdown
superstore-analysis/
├── data/
│   └── superstore_sales_dataset.csv
├── superstore_analysis.ipynb
├── requirements.txt
└── README.md
```