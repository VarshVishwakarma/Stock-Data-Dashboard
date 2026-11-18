# Extracting and Visualizing Stock and Revenue Data for Tesla and GameStop

**Author:** Data Science Specialist  
**Email:** varshv2007@gmail.com  
**Course:** IBM Python Project for Data Science (Coursera)  

This project extracts historical stock price data using `yfinance` and web-scrapes quarterly revenue data using `requests` and `BeautifulSoup` for **Tesla (TSLA)** and **GameStop (GME)**. It cleans the revenue datasets and visualizes the relationship between stock prices and quarterly revenues using two-panel graphs.

---

## Project Structure

```
├── Stock_and_Revenue_Analysis.ipynb    # Main Jupyter Notebook
├── README.md                           # Documentation and visual results
├── screenshots/
│   ├── question_1_tesla_data_head.png
│   ├── question_2_tesla_revenue_tail.png
│   ├── question_3_gme_data_head.png
│   ├── question_4_gme_revenue_tail.png
│   ├── question_5_tesla_graph.png
│   └── question_6_gamestop_graph.png
└── render_all_screenshots.py           # Reproducible execution & screenshot script
```

## Instructions to Run

1. Clone or download this repository:
   ```bash
   git clone <REPO_URL>
   cd ibm_stock_analysis
   ```
2. Install dependencies:
   ```bash
   pip install yfinance pandas requests beautifulsoup4 plotly matplotlib
   ```
3. Open and run the notebook:
   ```bash
   jupyter notebook Stock_and_Revenue_Analysis.ipynb
   ```
