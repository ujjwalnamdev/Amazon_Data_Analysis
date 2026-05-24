# 📊 Amazon Product Analysis

An end-to-end Data Analytics project focused on analyzing Amazon product data using Python, SQL, Tableau, and Streamlit concepts. This project demonstrates the complete analytics workflow including data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, business insight generation, SQL analysis, and interactive dashboard development.

---

# 🚀 Project Overview

The goal of this project is to extract meaningful business insights from Amazon product data and build professional analytics dashboards.

The dataset contains:

- Product details
- Prices
- Discounts
- Ratings
- Reviews
- Product categories
- Product links

This project focuses on:

- Data Cleaning
- Data Analysis
- Feature Engineering
- SQL Queries
- Dashboard Development
- Business Insight Generation

---

# 🛠️ Tools & Technologies Used

| Tool / Technology | Purpose                       |
| ----------------- | ----------------------------- |
| Python            | Data analysis & preprocessing |
| Pandas            | Data manipulation             |
| NumPy             | Numerical operations          |
| Matplotlib        | Data visualization            |
| Seaborn           | Statistical visualization     |
| Tableau           | Interactive dashboard         |
| Jupyter Notebook  | Development environment       |

---

# 📂 Project Structure

```bash
Amazon_Product_Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── dashboard/
├── images/
├── reports/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📥 Data Collection

Used an Amazon product dataset containing:

- Product names
- Actual prices
- Discounted prices
- Discount percentages
- Product ratings
- Rating counts
- Product categories
- Product URLs

---

# 🧹 Data Cleaning & Preprocessing

Performed extensive data cleaning using Python and Pandas:

### Tasks Performed

- Removed currency symbols and commas from price columns
- Converted object datatypes into numeric datatypes
- Handled null values and duplicate entries
- Cleaned `rating_count` column
- Cleaned `discount_percentage` column
- Fixed encoding and formatting issues
- Standardized category values

### Feature Engineering

Created additional useful columns:

- `popularity_score`
- `main_category`
- `category_grouped`

### Category Optimization

- Grouped low-frequency categories into `Other`
- Improved dashboard readability and analysis quality

---

# 📊 Exploratory Data Analysis (EDA)

Performed detailed exploratory data analysis using:

- Pandas
- Matplotlib
- Seaborn

### Analysis Performed

- Top product categories
- Rating distribution
- Discount vs Rating analysis
- Most reviewed categories
- Category-wise average rating
- Correlation heatmap

---

---

# 📈 Tableau Dashboard

Developed an interactive Tableau dashboard for business intelligence and data visualization.

### Dashboard Features

#### KPI Cards

- Total Products
- Average Rating
- Average Discount
- Total Reviews

#### Visualizations

- Top Categories Chart
- Rating Distribution Histogram
- Discount vs Rating Scatter Plot
- Most Reviewed Categories
- Category-wise Average Rating

### Dashboard Optimization

- Used horizontal and vertical containers
- Applied filters and formatting
- Improved chart readability
- Managed spacing and layout professionally

---

# ❓ Business Questions Solved

This project answers multiple real-world business questions using data analysis and visualization:

- Which categories receive the highest discounts?
- Are expensive products rated better?
- Which products are most popular?
- Do discounts improve ratings?
- What words appear most frequently in positive reviews?
- Which category has the highest customer engagement?
- Which categories receive the maximum reviews?
- Which products have the highest ratings?
- What is the relationship between discounts and customer satisfaction?

---

# 🧠 Example Analytical Queries

### Category Discount Analysis

- Which categories provide the highest average discount?

### Product Popularity Analysis

- Which products have the highest rating count?

### Rating vs Price Analysis

- Are expensive products rated better than cheaper products?

### Customer Engagement Analysis

- Which category has the highest review activity?

### Discount Impact Analysis

- Does increasing discount percentage improve ratings?

### Sentiment/Keyword Analysis

- Which words appear most commonly in positive reviews?

### Top Product Analysis

- Which products combine high ratings, high reviews, and high discounts?

---

# 💡 Key Business Insights

### Electronics category dominates

Electronics products have the highest number of listings and customer engagement.

### Most ratings lie between 3.5 and 4.5

Most products maintain good customer satisfaction levels.

### Discounts do not guarantee high ratings

Products with higher discounts are not always highly rated.

### Customer engagement is concentrated

A few major categories dominate reviews and ratings.

---

---

# 📸 Dashboard Screenshots

Add dashboard screenshots inside the `images/` folder.

Example:

```bash
images/
├── category_analysis.png
└── rating_distribution.png
```

---

# ⚙️ Installation & Setup

## Clone Repository

```bash
git clone <your-github-repo-link>
```

## Navigate to Project Folder

```bash
cd Amazon_Product_Analysis
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Jupyter Notebook

```bash
jupyter notebook
```

---

---

# 📦 Requirements

Main Python libraries used:

```txt
pandas
numpy
matplotlib
seaborn
plotly
jupyter
notebook
```

---

# 📚 Learning Outcomes

This project helped in learning:

- Real-world data cleaning
- Data preprocessing techniques
- Feature engineering
- Exploratory Data Analysis
- SQL querying
- Business intelligence dashboarding
- Data visualization best practices
- Dashboard design optimization
- End-to-end analytics workflow

---

# 🔮 Future Improvements

- Add machine learning recommendations
- Perform sentiment analysis on reviews
- Build advanced interactive filters
- Integrate AI-generated business insights

---

# 👨‍💻 Author

Ujjwal Namdev

---

# ⭐ Project Status

✅ Data Cleaning Completed

✅ Feature Engineering Completed

✅ EDA Completed

✅ SQL Analysis Completed

✅ Tableau Dashboard Completed



---

# 📌 Conclusion

This project demonstrates a complete end-to-end Data Analytics workflow starting from raw data preprocessing to business intelligence dashboard development.

The project showcases practical skills in:

- Python
- SQL
- Data Visualization
- Business Analytics
- Dashboard Development
- Insight Generation

making it a strong portfolio project for Data Analytics and Data Science roles.

