# Twitter Analytics Dashboard — Power BI

## Project Overview

This project presents an interactive **Twitter Analytics Dashboard** built in Microsoft Power BI to analyze tweet activity, reach, engagement, and content performance.

The dashboard transforms tweet-level analytics data into a three-page reporting experience designed to answer:

- How is overall Twitter performance?
- When and how are users engaging?
- Which tweets and posting patterns perform best?

## Tools & Technologies

- **Power BI Desktop**
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures and date analysis
- **Microsoft Excel** — source dataset

## Data Preparation

The dataset was imported from Excel into Power BI and prepared using Power Query.

Key preparation steps included:

- Promoted the source row to column headers
- Corrected column data types
- Converted tweet timestamps into usable Date/Time values
- Created Tweet Date and Tweet Hour fields
- Created a dedicated Date Table for time-based analysis
- Built a one-to-many relationship between the Date Table and Twitter Data
- Handled missing numeric metric values appropriately
- Created reusable DAX measures for tweet and engagement metrics

## DAX Measures

Key measures used in the dashboard include:

- Total Tweets
- Total Impressions
- Total Engagements
- Total Likes
- Total Retweets
- Total Replies
- Average Engagement Rate
- Average Impressions per Tweet


### 1. Tweet Analysis

This dashboard presents the analysis completed across all six project tasks, including tweet interactions, engagement rate, media interactions, overall engagement metrics, monthly trends, and top-performing tweets.

![Tweet Analysis](Tweet%20Analysis.png)

## Key Insights

The dashboard highlights several useful patterns:
•	Different tweet categories can generate different types and levels of audience interaction.
•	Separating media and non-media tweets helps compare content-related engagement patterns.
•	Replies, retweets and likes provide complementary indicators of audience response.
•	Monthly and day-of-week analysis helps identify temporal engagement patterns.
•	Top-engagement analysis helps identify tweets generating stronger audience response.


## Project Structure

```text
Twitter-Analytics-PowerBI/
│
├── README.md
├── project description.txt
├── Tweet Analysis.PNG
├── Twitter_Analytics_Project_Report
│
└── Tweet.xlsx
```


## Author

**Vedanti Madane**

Data Analyst | Power BI | SQL | Python | Excel
