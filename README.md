# 📊 SuperStore EDA Dashboard

An interactive **Exploratory Data Analysis (EDA)** dashboard built with **Streamlit** and **Plotly** to analyze SuperStore sales data.  
Easily filter data by region, state, and city, visualize trends, and export insights.

---

## 🚀 Features

- **📂 File Upload** — Upload your own dataset (`.csv`, `.xlsx`, `.txt`) or use the built-in sample.
- **📅 Date Filtering** — Select custom start and end dates.
- **🌍 Multi-Level Filters** — Filter by **Region → State → City**.
- **📊 Visualizations:**
  - Category-wise sales (Bar Chart)
  - Region-wise sales (Pie Chart)
  - Time Series trends
  - Treemap for hierarchical sales view
  - Segment & Category distribution
  - Month-wise sub-category summary
  - Sales vs. Profit scatter plot
- **📥 Data Export** — Download filtered datasets & summaries as CSV.
- **🖼 Interactive UI** — Built with Streamlit and Plotly for dynamic visuals.

---

## 🛠 Tech Stack

- **Python 3.x**
- **Streamlit** — For interactive UI
- **Pandas** — Data handling
- **Plotly Express & Figure Factory** — Data visualization
- **OS & Warnings** — Utility handling

---

## 📷 Dashboard Preview

| Category Sales | Region Sales | Time Series |
| --- | --- | --- |
| ![Bar Chart](https://via.placeholder.com/200x150) | ![Pie Chart](https://via.placeholder.com/200x150) | ![Line Chart](https://via.placeholder.com/200x150) |

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/superstore-eda.git
cd superstore-eda

# Install dependencies
pip install -r requirements.txt

# Run the dashboard
streamlit run dashboard.py
