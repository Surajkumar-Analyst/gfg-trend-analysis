# 📊 GFG Trend Analysis
### Exploring Content Evolution, Category Distribution & Publishing Patterns using Data Analytics

<div align="center">

![Banner](assets/banner.png)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Data Analysis](https://img.shields.io/badge/Data-Analytics-green?style=for-the-badge)

</div>

---

# 📌 Overview

**GFG Trend Analysis** is a data analytics project focused on discovering hidden patterns and publishing trends across a large-scale content dataset.

This project explores how different content categories evolve over time, which topics dominate the platform, how visual engagement differs between categories, and how category diversity changes as the platform grows.

The objective is to transform raw article data into **actionable insights through exploratory data analysis (EDA), interactive visualizations, and trend interpretation.**

---

# 🎯 Project Goals

✔ Understand category distribution  
✔ Identify dominant content areas  
✔ Measure category contribution percentages  
✔ Discover long-term publishing behavior  
✔ Track year-over-year content evolution  
✔ Analyze image usage across categories  
✔ Measure growth of content diversity  
✔ Detect recently growing topics  
✔ Group categories into broader themes

---

# 📂 Dataset

Dataset contains article-level information including:

| Column | Description |
|--------|-------------|
| title | Article Title |
| last_updated | Last Updated Timestamp |
| last_updated_date | Parsed Date |
| last_updated_month | Parsed Month |
| last_updated_year | Parsed Year |
| clean_tags | Content Category |
| day_of_week | Publishing Day |
| no_of_images | Number of Images |

---

# 🔍 Analysis Performed

## 1. Content Category Exploration
- Total unique categories
- Category frequency analysis
- Top contributing tags

---

## 2. Distribution Analysis
- Percentage share of categories
- Donut chart visualization
- Long-tail behavior detection

---

## 3. Temporal Trend Analysis
- Category growth across years
- Publishing consistency
- Evolution of dominant topics

---

## 4. Visual Engagement Study
- Images per category
- Comparison of visual-heavy vs technical content

---

## 5. Diversity Analysis
- Growth of unique categories
- Topic expansion over time

---

## 6. Theme Clustering
Grouped categories into larger domains:

- Programming Languages
- Web Development
- Interview / Career
- AI / ML / Data Science
- Backend & Frameworks
- Miscellaneous Topics

---

# 📈 Key Insights

### 🏆 Dominant Categories
- **Picked** emerged as the strongest content driver.
- **Web Technologies** maintained consistent growth.

### 🐍 Language Leadership
- **Python** dominated technical content volume.

### 💼 Career-Oriented Demand
- **Interview Experiences** ranked among the most active categories.

### 🌍 Long Tail Distribution
- Most activity concentrated among a few categories while hundreds of niche topics remained active.

### 📷 Visual Engagement
- Installation and Web categories contained significantly higher image density.

### 🚀 Rapid Expansion
- Category diversity accelerated sharply during recent years.

---

# 🛠 Tech Stack

```bash
Python
Pandas
NumPy
Matplotlib
Plotly
Jupyter Notebook
```

---

# 📊 Visualizations

Interactive dashboards include:

✅ Animated yearly category trends  
✅ Bar charts  
✅ Donut charts  
✅ Distribution plots  
✅ Trend comparisons  
✅ Category contribution analysis  

---

# 📁 Project Structure

```
GFG-Trend-Analysis
│
├── data/
│   └── dataset.csv
│
├── notebook/
│   └── analysis.ipynb
│
├── assets/
│   └── banner.png
│
├── visuals/
│   └── charts/
│
├── README.md
└── requirements.txt
```

---

# 🚀 Installation

Clone repository:

```bash
git clone https://github.com/your-username/GFG-Trend-Analysis.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run notebook:

```bash
jupyter notebook
```

---

# 💡 Future Improvements

- Build interactive dashboard
- Add machine learning prediction
- Deploy using Streamlit
- Add real-time data pipeline
- Content recommendation engine

---

# 🤝 Contributing

Contributions, ideas, and improvements are welcome.

Fork → Improve → Pull Request

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
📢 Share with others

---

Made with ❤️ using Python & Data Analytics
