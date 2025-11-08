# 🏀 EDA Basketball

An interactive **Exploratory Data Analysis (EDA)** web application for **NBA player statistics**, built with **Python** and **Streamlit**.  
The app enables users to dynamically explore, filter, and visualize NBA player data directly from the web — with powerful data wrangling and visualization tools.

---

## 🚀 Features

- 🔍 **Dynamic Data Filtering** — Filter players by **season**, **team**, and **position** in real-time.  
- 🌐 **Web Scraping Integration** — Automatically fetches the latest NBA player stats from [Basketball Reference](https://www.basketball-reference.com).  
- 🧹 **Data Cleaning & Preprocessing** — Cleans and structures web-scraped data into a pandas DataFrame for smooth analysis.  
- 📊 **Interactive Visualization** — Generates **correlation heatmaps**, descriptive statistics, and allows CSV export.  
- 🧠 **Built for Analysis** — Perfect for quick insights, trends discovery, and data-driven basketball analytics.

---

## 🧰 Tech Stack

- **Frontend/UI:** [Streamlit](https://streamlit.io/)  
- **Backend:** Python  
- **Libraries:** `pandas`, `numpy`, `requests`, `base64`, `matplotlib`, `seaborn`

---

## 📷 Application Preview

### 🖼️ 1. Dashboard View — *NBA Player Stats Explorer*

![NBA Player Stats Explorer](heatmap.png)

**Description:**  
This screen displays the **player statistics table** for the selected season (2019 in this example).  
Users can:
- Select **Year**, **Team**, and **Position** on the left panel.  
- View dynamic stats such as points, assists, rebounds, FG%, etc.  
- Instantly analyze data dimensions and player performance metrics.

---

### 🖼️ 2. Visualization View — *Correlation Heatmap*

![Correlation Heatmap](player_stats.png)

**Description:**  
This **correlation matrix heatmap** visually shows relationships among key performance metrics — such as points, assists, rebounds, and efficiency.  
Lighter shades indicate stronger positive correlations, helping users understand which stats move together (e.g., FG% vs. PTS).

---

## 📈 How It Works

### 🕸️ Web Scraping
The app scrapes data from **[Basketball Reference](https://www.basketball-reference.com)** for the selected year.

### 🧹 Data Cleaning
Handles missing values, converts data types, and filters relevant columns to create a clean and structured dataset.

### 🖥️ Interactive Dashboard
Built with **Streamlit**, the dashboard allows **real-time filtering** by year, team, and position — enabling instant updates to the displayed data.

### 📊 Visualization
A **correlation heatmap** provides insights into relationships between player performance metrics (e.g., FG%, PTS, REB, AST).

---

## 🧑‍💻 Example Use Cases

- 🔍 Compare **player performance** across teams or positions.  
- 📈 Identify **key statistical relationships** (e.g., correlation between FG% and PTS).  
- 🕰️ Explore **historical trends** in player stats.  
- 💾 Export cleaned datasets for **further machine learning or analytics** tasks.  

---

## 🌟 Demo Highlights

- ⚡ Interactive filtering by **year**, **team**, and **position**  
- 🔁 Real-time data table updates  
- 📉 Correlation heatmap for performance relationships  
- 📂 CSV export feature  
- 🌙 Responsive, modern **dark-themed UI**

---

## 📜 License

This project is open source and available under the **[MIT License](LICENSE)**.

---

## 🙌 Acknowledgments

- 🏀 **[Basketball Reference](https://www.basketball-reference.com)** — for providing player data.  
- 💡 **[Streamlit](https://streamlit.io/)** — for the intuitive web app framework.  
