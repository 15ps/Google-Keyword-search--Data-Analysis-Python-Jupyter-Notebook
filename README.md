# 🔍 Google Keyword Search Trends Analysis

This project uses the **Pytrends** API to analyze and visualize how different keywords trend on Google over time and across the world. With just a quick keyword change, you can explore global interest, compare multiple keywords, and gain insights into what people are searching for online. 

*There are no raw input file used in this project, the data is directly fetches from google and analysed.

---

## 📌 Features

* **Dynamic Keyword Search:** Easily switch out the keyword to analyze new trends without rewriting the code.
* **Top Countries Insight:** Visualizes the top 15 countries showing the highest interest in a keyword.
* **Interactive World Map:** Displays country-wise search interest using a choropleth map.
* **Time Series Analysis:** Tracks how a keyword's popularity has changed over the past 12 months.
* **Keyword Comparison:** Compare multiple related keywords in one interactive graph.

---

## 🛠️ Libraries Used of jupyter notebook
* **Pytrends** – to access Google Trends data
* **Pandas** – for data manipulation
* **Matplotlib / Seaborn** – for static data visualization
* **Plotly Express** – for interactive world map visualizations

---
## 👾 Warnings

* The request failed: Google returned a response with code 429/400 are errors thrown by google based on busy searches/frequent searches. Its nothing to do with incorrect code.
---

## 📊 Output Examples

* Bar chart showing top 15 countries searching the keyword.
* Interactive world map colored by search interest.
* Line chart showing search trend over time.
* Multi-line plot comparing several keywords.

---

## 🙌 Acknowledgements

Thanks to [Pytrends](https://github.com/GeneralMills/pytrends) for making it easy to work with Google Trends data in Python jupyter notebook.
**Note**:Google Trends data is normalized and does not represent absolute search volume. It shows interest relative to the highest point on the chart for the selected time and region.

---

## 📬 Contact

Have feedback or want to contribute? Feel free to open an issue or pull request on the GitHub repo!

---
