# Real-Time-Industry-Insight-Strategic-Intelligence-System

# 📊 Real-Time Industry Insight & Strategic Intelligence System

## 🧠 Project Overview
The **Real-Time Industry Insight & Strategic Intelligence System** is a data analytics project designed to collect, preprocess, and visualize **real-time company insights** using open-source APIs and web data.  
The project focuses on three major Indian companies:
- 🚗 **Tata Motors** (Automobile)
- ⚡ **Reliance Industries** (Energy & Retail)
- 💻 **Wipro** (Consulting & Technology)

It provides valuable market and public-interest trends using data from **Google Trends**, **Wikipedia**, and **News APIs**, visualized through dynamic charts and word clouds in **Google Colab**.

---

## ⚙️ Features
✅ Fetch real-time company data from:
- **Google Trends API** – to track search popularity.  
- **Wikipedia API** – to gather company summaries and background information.  
- **News API** – to extract the latest business news headlines.

✅ Preprocess and clean raw data into structured CSV files.  
✅ Visualize industry insights through:
- Line charts (interest over time)
- Bar graphs and pie charts (comparative analysis)
- Word clouds (news keyword highlights)
- Sentiment visualization

---

## 🧩 Tech Stack
| Component | Tools / Libraries |
|------------|------------------|
| **Platform** | Google Colab |
| **Languages** | Python |
| **APIs** | Google Trends, Wikipedia, NewsAPI |
| **Libraries** | pandas, matplotlib, seaborn, pytrends, requests, wordcloud |

---

## 🗂️ Project Structure
```

📦 Real_Time_Industry_Insight_&*Strategic_Intelligence_System
│
├── company_trends.csv              # Google Trends data
├── company_wikipedia.csv           # Wikipedia company summaries
├── company_news.csv                # Company news data
├── Real_Time_Industry_Insight*&_Strategic_Intelligence_System.ipynb  # Main Google Colab notebook
└── README.md                       # Project documentation


---

## 🚀 How to Run in Google Colab
1. Open the `.ipynb` file in **Google Colab**.
2. Install required dependencies:
   ```python
   !pip install pytrends pandas matplotlib seaborn wordcloud requests
````

3. Run each cell step-by-step.
4. The project will automatically:

   * Fetch live company data.
   * Preprocess and save datasets.
   * Display visualizations (graphs/charts/wordclouds).

---

## 📈 Results

* **Tata Motors** showed rising trends linked to new EV announcements.
* **Reliance Industries** maintained consistent engagement due to retail and telecom growth.
* **Wipro** displayed interest spikes during quarterly IT service results.

The dashboard helps visualize **public perception, market activity, and search trends** in real time.

---

## 📄 Future Enhancements

* Integrate **Twitter API** for social sentiment analysis.
* Deploy a **real-time dashboard** using Streamlit or Power BI.
* Automate daily trend tracking and report generation.

---

## 👩‍💻 Author

**Kavita Sonawane**


⭐ *If you like this project, give it a star on GitHub!* ⭐

```



