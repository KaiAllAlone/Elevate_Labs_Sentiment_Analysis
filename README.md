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

## ❗❗ NOTE
### Make sure to delete the previous .csv file and then open the dashboard on PowerBI and hit refresh.
### The csv file must have the name of 'SentimentAnalysis.csv' or if there is a different path then on PowerBI follow the steps:-
#### 1) Go to 'File'.
#### 2) Click Options and Settings.
#### 3) click Data Source Settings.
#### 4) Right click on the path and then add the desired path of the saved CSV File. 

## 🛡️ License
MIT License. See LICENSE file.

## 🙋‍♂️ Author
Debanuj Roy -@KaiAllAlone

## 🌐 Contributions
PRs are welcome. Open issues for suggestions or bug reports.

## 🖼️ Images
![Screenshot 2025-06-27 154227](https://github.com/user-attachments/assets/05650a0f-9df6-42d1-bd1b-b2fb925a09b7)

![image](https://github.com/user-attachments/assets/fc1610cf-ea37-4b4d-a487-0917b8aa4976)

![Screenshot 2025-06-27 160429](https://github.com/user-attachments/assets/b62cb84c-249f-4865-bfe5-54cd40acb0b3)

![image](https://github.com/user-attachments/assets/4e0793f4-61c3-45a2-b870-cb8fbe6a4f36)



