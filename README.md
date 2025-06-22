# 📊 Tweet Engagement Analysis Project (Python + Power BI)

This project analyzes the relationship between *media views* and *media engagements* on tweets. It filters tweets based on several engagement and metadata criteria and visualizes the result using both *Python (Plotly)* and *Power BI*.

---

## 🎯 Project Objective

To build a *scatter chart* that shows how media engagements relate to media views, focusing only on high-quality tweets posted during peak engagement hours.

---

## ✅ Filtering Criteria

Only tweets that meet *all* the following conditions are included in the chart:

- 💬 *Replies > 10*
- 📈 *Engagement rate > 5%*
- 🗓 *Tweet date is an odd number* (e.g. 1, 3, 5, ...)
- 📝 *Word count > 50*
- ⏰ *Chart is visible only between 6 PM to 11 PM IST*

> If the current time is outside the allowed time range, the chart is *not shown* in the dashboard.

---

## 🧰 Tools & Technologies

| Tool       | Purpose                        |
|------------|--------------------------------|
| Python     | Data filtering and visualization using Plotly |
| Plotly     | Interactive scatter chart      |
| Pandas     | Data manipulation              |
| Power BI   | Alternate version of the chart |
| CSV        | Tweet dataset source           |

---

## 📁 Project Files

| File Name              | Description                               |
|------------------------|-------------------------------------------|
| tweets.csv           | Dataset used for analysis                 |
| project_code.ipynb   | Python notebook with complete logic       |
| scatter_chart.png    | Final chart exported from Plotly          |
| scatter_chart.pbix   | Power BI version of the same visualization|

---

## 📸 Output Chart (Python)

> Scatter plot of media views (X-axis) vs media engagements (Y-axis). Tweets with engagement rate > 5% are highlighted.

![Scatter Chart](scatter_chart.png)

---

## 🔗 How to Run This Project

### 🐍 Python (Colab or Jupyter)
1. Load tweets.csv into the notebook
2. Run project_code.ipynb
3. The chart will only render between 6PM–11PM IST
4. Save or export the chart as image or HTML

### 📊 Power BI
1. Open scatter_chart.pbix in Power BI Desktop
2. You can explore filters or export the chart as PDF/image