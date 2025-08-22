# Superstore Sales Performance Analysis

An exploratory data analysis (EDA) of a superstore's sales dataset to identify key drivers of revenue and discover strategic business insights. This project uses Python, Pandas, and Seaborn to process, analyze, and visualize sales performance.

<details>
<summary><strong>日本語版 (Japanese Version)</strong></summary>

> スーパーーストアの売上データセットの探索的データ分析（EDA）を行い、収益の主要な要因を特定し、戦略的なビジネスインサイトを発見します。このプロジェクトでは、Python、Pandas、Seabornを使用して、売上実績の処理、分析、可視化を行っています。

</details>

---

## 💡 Key Findings

This analysis revealed several key insights into the superstore's sales performance:

1.  **Top Customer Segment:** The **Consumer** segment is the largest contributor to total sales, significantly outperforming the Corporate and Home Office segments.
2.  **Key Product Categories:** **Technology** products generate the highest revenue, closely followed by Furniture. Within Technology, "Phones" and "Copiers" are particularly high-performing sub-categories.
3.  **Consistent Sales Growth:** The analysis shows a consistent year-over-year growth in total sales, indicating a positive business trajectory and successful market expansion.

<details>
<summary><strong>主な発見 (Key Findings)</strong></summary>

> 1.  **トップ顧客セグメント:** **消費者 (Consumer)** セグメントが総売上に最も大きく貢献しており、法人 (Corporate) およびホームオフィス (Home Office) セグメントを大幅に上回っています。
> 2.  **主要製品カテゴリー:** **テクノロジー (Technology)** 製品が最も高い収益を生み出し、僅差で家具 (Furniture) が続いています。テクノロジーの中でも、「電話 (Phones)」と「コピー機 (Copiers)」は特に実績の高いサブカテゴリーです。
> 3.  **一貫した売上成長:** 分析によると、総売上は前年比で一貫して成長しており、良好な事業軌道と市場拡大の成功を示しています。

</details>

---

## Actionable Insights

Based on the analysis, here are some actionable recommendations for the business:

1.  **Focus on Top Segments:** Double down on marketing and sales efforts targeting the **Consumer** segment, as it is the primary driver of revenue.
2.  **Optimize Regional Inventory:** Increase inventory for **Technology** products in the top-performing states to meet demand and maximize sales.
3.  **Review Sub-Category Performance:** Investigate why sub-categories like "Fasteners", "Labels", and "Art" have low sales figures and consider running targeted promotions.

<details>
<summary><strong>実行可能な洞察 (Actionable Insights)</strong></summary>

> 1.  **トップセグメントへの注力:** 収益の主要な推進力である**消費者 (Consumer)** セグメントをターゲットにしたマーケティングと販売活動を強化します。
> 2.  **地域別在庫の最適化:** 需要に応え、売上を最大化するために、実績の良い州で**テクノロジー (Technology)** 製品の在庫を増やします。
> 3.  **サブカテゴリーの実績レビュー:** 「留め具 (Fasteners)」、「ラベル (Labels)」、「アート (Art)」などのサブカテゴリーの売上が低い理由を調査し、ターゲットを絞ったプロモーションの実施を検討します。

</details>

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:**
  - Pandas & NumPy (for data wrangling and analysis)
  - Matplotlib & Seaborn (for data visualization)
- **Environment:** Jupyter Notebook (run in VS Code)

<details>
<summary><strong>技術スタック (Tech Stack)</strong></summary>

> - **言語:** Python
> - **ライブラリ:**
>   - Pandas & NumPy (データラングリングと分析用)
>   - Matplotlib & Seaborn (データ可視化用)
> - **環境:** Jupyter Notebook (VS Codeで実行)

</details>

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

<details>
<summary><strong>セットアップとインストール (Setup and Installation)</strong></summary>

> このプロジェクトをローカルで実行するには、次の手順に従ってください。
>
> 1.  **リポジトリをクローンします:**
>     ```bash
>     git clone [https://github.com/phucndq05/superstore-analysis.git](https://github.com/phucndq05/superstore-analysis.git)
>     ```
> 2.  **プロジェクトディレクトリに移動します:**
>     ```bash
>     cd superstore-analysis
>     ```
> 3.  **仮想環境を作成して有効化します（推奨）:**
>     ```bash
>     python3 -m venv .venv
>     source .venv/bin/activate
>     ```
> 4.  **必要な依存関係をインストールします:**
>     ```bash
>     pip install -r requirements.txt
>     ```
> 5.  **Jupyter Notebookを起動します:**
>     ```bash
>     jupyter notebook superstore_analysis.ipynb
>     ```

</details>

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
