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

## Dashboard Pages

### 1. Twitter Overview

Provides a high-level view of account performance through:

- Total Tweets
- Total Impressions
- Total Engagements
- Total Likes
- Total Replies
- Total Retweets
- Average Engagement Rate
- Average Impressions per Tweet
- Daily Tweet Activity
- Daily Engagements
- Daily Impressions
- Engagement by Day of Week

![Twitter Overview](twitter_overview.png)

### 2. Twitter Engagement Analysis

Focuses on engagement drivers and audience interaction:

- Engagement by Tweeting Hour
- Engagement Rate by Tweeting Hour
- Impressions vs Engagement Rate
- Top 10 Tweets by Engagement
- Engagement Composition

![Twitter Engagement Analysis](twitter_engagement_analysis.png)

### 3. Tweet & Content Performance

Focuses on content reach and posting behavior:

- Top 10 Tweets by Impressions
- Top 10 Tweets by Likes
- Tweet Volume by Hour
- Tweet Activity by Day

![Tweet & Content Performance](tweet_content_performance.png)

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

> Keep the original dataset only if you have permission to redistribute it. Otherwise, upload the dashboard screenshots, PBIX file (if appropriate), and documentation without republishing the source dataset.

## Author

**Vedanti Madane**

Data Analyst | Power BI | SQL | Python | Excel
