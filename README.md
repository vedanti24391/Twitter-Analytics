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

<h3>1. Twitter Overview</h3>

<p>Provides a high-level view of Twitter performance, including tweet activity, impressions, engagements, likes, retweets, replies, engagement rate, and daily trends.</p>

<img src="https://raw.githubusercontent.com/vedanti24391/Twitter-Analytics/main/twitter_overview.PNG" alt="Twitter Overview">

<h3>2. Twitter Engagement Analysis</h3>

<p>Analyzes engagement by tweeting hour, engagement rate, top-performing tweets, impressions, and engagement composition.</p>

<img src="https://raw.githubusercontent.com/vedanti24391/Twitter-Analytics/main/twitter_engagement_analysis.PNG" alt="Twitter Engagement Analysis">

<h3>3. Tweet &amp; Content Performance</h3>

<p>Analyzes the top tweets by impressions and likes, along with tweet volume by hour and day of the week.</p>

<img src="https://raw.githubusercontent.com/vedanti24391/Twitter-Analytics/main/tweet_content_performance.PNG" alt="Tweet & Content Performance">

## Key Insights

The dashboard highlights several useful patterns:

- Engagement varies significantly by posting hour, with stronger activity concentrated in the evening period.
- Likes represent the largest share of the engagement mix.
- A small number of tweets account for a disproportionately large share of impressions and likes.
- Tweet volume differs across days of the week, making posting frequency and engagement timing useful areas for optimization.
- Comparing impressions with engagement rate helps distinguish high-reach tweets from genuinely high-quality engagement.

## Business Value

This dashboard can help a social media or marketing team:

- Identify high-performing content
- Understand effective posting times
- Monitor reach and engagement
- Compare content performance
- Prioritize content strategies based on measurable audience behavior

## Project Structure

```text
Twitter-Analytics-PowerBI/
│
├── README.md
├── assets/
│   ├── twitter_overview.png
│   ├── twitter_engagement_analysis.png
│   └── tweet_content_performance.png
│
└── Tweet.xlsx
```


## Author

**Vedanti Madane**

Data Analyst | Power BI | SQL | Python | Excel
