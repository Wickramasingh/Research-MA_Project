# YouTube Channel Analysis and Growth Predictions Using Machine Learning  

![68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f31334e6333786c4f316b476733532f67697068792e676966](https://github.com/user-attachments/assets/c9f07ddf-4183-4414-91f1-f7e122f2523a)

This project provides an in-depth analysis of the top 1000 YouTube channels worldwide. It explores engagement metrics, category trends, and growth patterns while incorporating machine learning models to predict subscriber counts.  

## Project Overview  

YouTube, launched in 2005, is the largest video-sharing platform globally, with over 2 billion monthly active users. This dataset captures key details about top-performing YouTube channels, including rank, subscribers, video views, video count, category, and the year they started.  

This project offers insights into YouTube trends, channel engagement, and predictive analytics for subscriber growth.  

## Files Included  

- **youtube_models.ipynb**: Jupyter Notebook focused on model training and evaluation.  
- **youtube_visualization.ipynb**: Jupyter Notebook containing data analysis and visualizations.  
- **Top_YouTuber_Dataset.csv**: The dataset used for analysis and modeling.  

## About the Dataset  

The dataset provides detailed information on the top 1000 YouTube channels, including:  

- **Rank**: Channel's global ranking based on popularity and performance.  
- **Youtuber**: Name or title of the YouTube channel.  
- **Subscribers**: Total subscribers, reflecting the channel's popularity.  
- **Video Views**: Total views, indicating audience engagement.  
- **Video Count**: Number of videos uploaded.  
- **Category**: Genre of the channel (e.g., Music, Entertainment, Education).  
- **Started**: Year the channel was created, offering insight into growth and longevity.  

The dataset is sourced from Kaggle: **Top 1000 YouTube Channels Dataset** 🌐📊🎥.  

## Analysis Summary  

### Key Insights  

- **Popular Categories**: Entertainment, Music, and Shows dominate the platform.  
- **Growth Trends**: The number of new channels has significantly increased in recent years.  
- **Top Channels**: MrBeast and T-Series lead in subscriber counts.  
- **Engagement Metrics**: Music and Shows categories boast the highest engagement levels.  
- **Word Cloud**: Highlights the prominence of key categories.  

## Model Training  

### Objectives  

1. **Predicting Subscriber Count**  
   A regression model was trained using features such as Video Views, Video Count, Category, and Year Started to predict the number of subscribers a channel has.  

2. **Classifying Engagement Levels**  
   Channels were categorized into *High* or *Low* engagement classes based on their average views per video.  

### Models Used  

#### Subscriber Count Prediction  
- **Random Forest Regressor**: Achieved a balanced trade-off between accuracy and interpretability.  
- **XGBoost Regressor**: Delivered the best R-squared value among tested models.  
- **Linear Regression**: Provided a baseline for performance comparison.  

#### Engagement Classification  
- **Random Forest Classifier**: Demonstrated high precision and recall for engagement classification.  
- **XGBoost Classifier**: Delivered robust performance with effective handling of feature importance and imbalances in the dataset.  
- **Support Vector Machine (SVM)**: Offered balanced performance for distinguishing *High* and *Low* engagement classes.  

## Insights  

- **Subscriber Count Prediction**: The XGBoost model outperformed others, achieving a significant R² value, effectively capturing relationships between channel features and subscriber counts.  
- **Engagement Classification**: The XGBoost model provided the best overall performance in distinguishing *High* and *Low* engagement levels.  
