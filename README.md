# Real-Time-Industry-Insight-Strategic-Intelligence-System


⚙️ Implementation Steps

Data Collection

Data was fetched using open APIs like:

Google Trends API (Pytrends): To track public interest and search volume trends for each company over the past 3 months.

Wikipedia API: To fetch company information, summaries, and overviews.

News API: To collect the latest headlines and market news related to each company.

These datasets were combined into structured CSV files (company_trends.csv, company_wikipedia.csv, company_news.csv).

2.Data Preprocessing

Cleaned the data by handling null values, removing duplicates, and parsing timestamps.

Transformed text data (e.g., news titles and summaries) into a usable format for analysis.

Converted search trend indices into a time-series dataframe for visualization.

3.Data Visualization

Created line charts to visualize Google search trends over time.

Generated bar graphs and pie charts to compare company popularity.

Used word clouds to display the most frequent terms from company-related news articles.

Visualized sentiment distribution using color-coded bar charts.

4.Insights

Tata Motors showed spikes in trend data due to new EV announcements.

Reliance Industries maintained consistent public interest driven by retail and telecom updates.

Wipro trends correlated with IT service demand and quarterly result announcements.

Tools & Technologies

Google Colab for execution and visualization.

Python libraries: pytrends, pandas, matplotlib, seaborn, wordcloud, requests, and BeautifulSoup.

Data Format: CSV datasets for easy integration.
