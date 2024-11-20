YouTube Channel Analysis and Growth Predictions Using Machine Learning
Top 1000 YouTube Channels Analysis
This project provides an in-depth analysis of the top 1000 YouTube channels worldwide. It explores engagement metrics, category trends, and growth patterns while incorporating machine learning models to predict subscriber counts.

Project Overview
YouTube, launched in 2005, is the largest video-sharing platform globally, with over 2 billion monthly active users. This dataset captures key details about top-performing YouTube channels, including rank, subscribers, video views, video count, category, and the year they started.

This project offers insights into YouTube trends, channel engagement, and predictive analytics for subscriber growth.
Files Included
youtube_models.ipynb: Jupyter Notebook focused on model training and evaluation.
youtube_visualization.ipynb: Jupyter Notebook containing data analysis and visualizations.
Top_YouTuber_Dataset.csv: The dataset used for analysis and modeling.
About the Dataset
The dataset provides detailed information on 1000 top-performing YouTube channels, including:

Rank: Channel's global ranking based on popularity and performance.
Youtuber: Name or title of the YouTube channel.
Subscribers: Total subscribers, reflecting the channel's popularity.
Video Views: Total views, indicating audience engagement.
Video Count: Number of videos uploaded.
Category: Genre of the channel (e.g., Music, Entertainment, Education).
Started: Year the channel was created, offering insight into growth and longevity.
The dataset is sourced from Kaggle: Top 1000 YouTube Channels Dataset 🌐📊🎥.

Analysis Summary
Key Insights:
Popular Categories: Entertainment, Music, and Shows dominate the platform.
Growth Trends: The number of new channels has significantly increased in recent years.
Top Channels: MrBeast and T-Series lead in subscriber counts.
Engagement Metrics: Music and Shows categories boast the highest engagement levels.
Word Cloud: Shows the prominence of categories.

Model Training
Two primary objectives were addressed using machine learning:

Predicting Subscriber Count: A regression model was trained using features such as Video Views, Video Count, Category, and Year Started to predict the number of subscribers a channel has.

Classifying Engagement Levels: An engagement classification task was undertaken, defining channels as High or Low engagement based on their average views per video.
Models Used
Subscriber Count Prediction:
Random Forest Regressor: Achieved a balanced trade-off between accuracy and interpretability.
XGBoost Regressor: Delivered the best R-squared value among tested models.
Linear Regression: Provided a baseline for performance comparison.
Engagement Classification
Random Forest Classifier: Demonstrated high precision and recall for engagement classification.
XGBoost Classifier: Provided robust performance with effective handling of feature importance and imbalances in the dataset.
Support Vector Machine (SVM): Balanced performance for distinguishing between High and Low engagement classes.

Insights
Subscriber Count Prediction: The XGBoost model outperformed others with a significant R² value, capturing key relationships between channel features and subscriber counts.
Engagement Classification: The XGBoost model delivered the best performance for distinguishing between High and Low engagement levels.

