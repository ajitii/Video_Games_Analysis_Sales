# Video Games Sales Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
    - [Data Extraction](#data-extraction)
    - [Data Cleaning](#data-cleaning)
    - [Data Visualization](#data-visualization)
- [Key Findings](#key-findings)
- [Actionable Insights](#actionable-insights)
- [Interactive Dashboard](#interactive-dashboard)
- [How to Run This Project](#how-to-run-this-project)
- [Future Improvements](#future-improvements)
- [Acknowledgments](#acknowledgments)

## Project Overview
The **Video Games Sales Analysis** project aims to analyze video game sales data to uncover trends, understand market preferences, and provide insights that can help drive strategic business decisions. Utilizing SQL for data manipulation and Power BI for data visualization, this project offers a comprehensive view of the gaming industry's performance from 1980 to 2020.

## Objective
- To analyze sales performance across different platforms (e.g., Xbox, PlayStation, PC) and genres.
- To identify regional sales distribution and preferences.
- To provide actionable insights for business strategy and marketing.

## Data Sources
- **Sales Data**: The primary dataset used in this analysis is sourced from [Kaggle Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales), containing records of video game sales including:
    - Title
    - Platform
    - Year
    - Genre
    - Publisher
    - Global Sales
    - Other sales metrics across different regions (NA, EU, JP, etc.)

## Methodology

### Data Extraction
SQL queries were written to extract relevant data from the sales dataset, focusing on key metrics like total sales by platform, genre, and year.

### Data Cleaning
Data cleaning tasks included:
- Removing duplicate entries
- Handling missing values
- Ensuring data consistency

### Data Visualization
Power BI was used to create interactive dashboards, visualizing data through charts, graphs, and tables to highlight key sales trends and comparisons.

## Key Findings
- **Top Platforms**: PlayStation and Xbox consistently show higher sales over the years.
- **Genre Performance**: Action games tend to dominate sales figures across different platforms.
- **Regional Insights**: North America leads in sales, while Japan has unique preferences for certain genres.

## Actionable Insights
- **Marketing Strategies**: Increase marketing investments in top-performing platforms and genres.
- **Product Development**: Focus on developing action and sports games based on consumer preferences.
- **Regional Promotions**: Create localized marketing campaigns targeting specific genres popular in different regions.

## Interactive Dashboard
Explore the interactive dashboard developed using Power BI for deeper insights:
[![Dashboard Screenshot](https://user-images.githubusercontent.com/125219883/219969990-00a7485e-5bf8-46b3-b255-c146972fc312.png
)](link-to-your-live-dashboard)

*Note: To access the dashboard, you may need a Power BI license or permissions set by the creator.*
## Games Details 
![image](https://user-images.githubusercontent.com/125219883/219970081-b1774f5d-8858-4459-84f2-ff6653686f72.png)

## Games Publisher Details 
![image](https://user-images.githubusercontent.com/125219883/219970112-d038c26d-9349-4338-a49c-9ec7aaa0931e.png)

## Games Published in a specific Year 
![image](https://user-images.githubusercontent.com/125219883/219970214-19708a13-e5a2-41e1-af21-32a0b15ff7f1.png)

## How to Run This Project

### Prerequisites
- SQL environment (e.g., MySQL, PostgreSQL)
- Power BI Desktop installed on your machine

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ajitii/Video_Games_Analysis_Sales.git

2. **Set Up the Database**: Import the provided SQL scripts into your database environment to set up the sales data.

3. **Open Power BI**: Launch Power BI and import the video_games_sales_analysis.pbix file included in this repository.

4. **Interact with the Dashboard**: Use the interactive features in Power BI to explore different data insights and trends.

## Future Improvements
- Advanced Analytics: Incorporate predictive models and sentiment analysis for comprehensive insights.
- Enhanced Documentation: Add more detailed explanations and examples within the Power BI reports.
- User Feedback: Plan a feedback mechanism to improve the dashboard's usability and features based on user interactions.

## Acknowledgments
- Special thanks to the contributors for their insights and support in bringing this project to fruition.
- Dataset sourced from Kaggle.

