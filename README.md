# Pharma Sales Analysis

## 📌 Overview
The **Pharma Sales Analysis** project focuses on analyzing pharmaceutical sales data to gain insights into sales trends, customer behavior, and market performance. This project utilizes Python and SQL to process, analyze, and visualize sales data for better decision-making. 

This repository contains a project focused on analyzing and visualizing pharmaceutical sales data. It includes an exploration notebook for data analysis and a Power BI file for creating interactive dashboards. 
The project aims to provide insights into sales trends, patterns, and performance in the pharmaceutical industry, helping to make data-driven decisions. 
Key tools include Jupyter Notebooks for data processing and Power BI for visualization.


## 🔧 Features
- Import and process large pharmaceutical sales datasets
- Perform sales trend analysis across different regions and time periods
- Identify top-selling products and customer preferences
- Generate interactive visualizations using Matplotlib and Seaborn
- SQL-based data extraction and reporting

## 📂 Project Structure
```
📁 pharma_sales/
├── 📄 main.py             # Main script to run the analysis
├── 📄 database.sql        # SQL schema for storing sales data
├── 📄 config.py           # Configuration file for database connection
├── 📂 data/               # Raw and processed datasets
├── 📂 notebooks/          # Jupyter Notebooks for detailed analysis
├── 📂 scripts/            # Python scripts for data processing
└── 📄 README.md           # Project documentation
```

## 🚀 Installation & Setup
1. **Clone the repository**:
   ```sh
   git clone https://github.com/Somakshi1/pharma_sales.git
   cd pharma_sales
   ```
2. **Create a virtual environment** (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # For Mac/Linux
   venv\Scripts\activate     # For Windows
   ```
3. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
4. **Configure the database connection**:
   - Update `config.py` with your database credentials.
   - Ensure the database server is running.
5. **Run the project**:
   ```sh
   python main.py
   ```

## 🛠 Technologies Used
- **Python** 🐍
- **SQL (SQLite/MySQL/PostgreSQL)** 🗄️
- **Pandas, Matplotlib, Seaborn** 📊
- **Flask/FastAPI (if applicable for API integration)** 🚀

## 📖 Usage
- Modify `database.sql` to define your sales database schema.
- Use `main.py` to execute sales data analysis.
- Add custom scripts inside the `scripts/` folder for automation and reporting.


