<h1> Elevate_Labs_Sentiment_Analysis</h1>
<h1>🧠 Brand Sentiment Analysis via Reddit + Power BI</h1>
Scarpes Reddit and News Sources to extract data on companies to gte an idea of their public perecption and financial performance.

## 📂 Project Structure

├── SentimentAnalysis.ipynb <--- Python script to scrape Reddit & analyze sentiment

├── Sentiment_Analysis_Dashboard.pbix <--- Power BI dashboard for visualization

├── requirements.txt <--- Python dependencies

└── README.md <--- This file

## 🚀 Features

- 🔍 Scrapes Reddit posts about any company/brand
- 💬 Uses a transformer-based sentiment model (`transformers` + HuggingFace) to classify post sentiment
- 📊 Power BI dashboard to monitor public opinion trends

## 🔧 Setup Instructions

### 1. Clone the Repo

```
git clone https://github.com/yourusername/repo-name.git
cd repo-name
```
2. Install Requirements
Make sure you have Python 3.8+ and install dependencies:
```
pip install -r requirements.txt
```
## 🧪 How to Use
Edit the notebook SentimentAnalysis.ipynb to enter your company or brand name.

Run all cells to fetch Reddit posts and get sentiment predictions.

The results will be saved to a CSV file (SentimentAnalysis.csv).

## 📈 Dashboard (Power BI)
Open Sentiment_Analysis_Dashboard.pbix in Power BI Desktop.

Make sure the CSV output from the notebook is present at the correct location Power BI expects.

You can also:

Set auto-refresh to update data when the notebook re-runs

Filter by date, sentiment, or brand

## 🛡️ License
MIT License. See LICENSE file.

## 🙋‍♂️ Author
Debanuj Roy -@KaiAllAlone

## 🌐 Contributions
PRs are welcome. Open issues for suggestions or bug reports.

