# Social Media Video Engagement Analysis

## Project Overview
This project focuses on analyzing the engagement of trending social media videos from May to August 2021. The dataset includes metrics such as likes, shares, comments, plays, and video length, with a time dimension to study trends by hour of day and seasonality.

## Dataset
- **File Name**: `trending_videos.csv`
- **Columns**: `user_id`, `video_id`, `video_time`, `video_length`, `n_likes`, `n_shares`, `n_comments`, `n_plays`

## Key Analyses Performed:
1. **Total and Average Engagement Calculation**:  
   - Calculated total and average likes, shares, comments, and plays per video.

2. **Video Length Categorization**:  
   - Categorized videos into `Short`, `Medium`, `Long`, and `Very Long` based on video length.
   - **Key findings**:
     - Short videos: 2.65M likes, 22.2M plays.
     - Medium videos: 2.87M likes, 47.33M plays.
     - Long videos: 682K likes, 5.15M plays.

3. **Correlation Analysis**:  
   - Explored relationships between engagement metrics.  
   - **Strong correlations**:
     - Likes and plays (0.879).
     - Comments and shares (0.857).
   - Weak correlations between video length and other metrics.

4. **Video Performance by Time of Day**:  
   - Analyzed hourly engagement, highlighting that early morning and afternoon are peak times for interaction.
     - 2 AM - 7 AM had high play counts and interactions.
     - 1 PM - 3 PM also showed strong engagement.

5. **Seasonality Analysis**:  
   - Studied performance trends by month (May - August), revealing engagement spikes in specific months.

## Usage Instructions
- Clone the repository.
- Run the Jupyter notebook to replicate the analysis using Python (Pandas, Matplotlib, Seaborn).
- Dataset (`trending_videos.csv`) is included in the repository.

## Visualizations
- **Length vs Engagement**: Bar charts comparing engagement across short, medium, and long videos.
- **Correlations**: Heatmap showing relationships between engagement metrics and video length.
- **Time-of-Day Analysis**: Line charts showcasing peak engagement hours.
- **Seasonal Trends**: Graphs depicting monthly performance for each engagement metric.

## Impact of the Project
- This analysis helps marketers optimize video content based on length, posting times, and seasonality.
- Correlation analysis reveals key relationships that can help plan viral content strategies.
