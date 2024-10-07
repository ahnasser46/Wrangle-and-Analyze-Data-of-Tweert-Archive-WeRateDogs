# Wrangle and Analyze Data

This project is part of the Professional Data Analysis Nanodegree by Udacity. This project involves gathering, assessing, and cleaning data from the WeRateDogs Twitter account to perform analysis and visualization.

## Contents
- Introduction
- Data Gathering
- Data Assessment
- Data Cleaning
- Analysis and Visualization
- Conclusion

## Introduction
The goal of this project is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The data includes tweet information, image predictions, and additional data gathered from the Twitter API.

## Data Gathering
- **Twitter Archive**: Downloaded `twitter-archive-enhanced.csv`.
- **Image Predictions**: Downloaded `image-predictions.tsv` from Udacity's server.
- **Twitter API**: Queried Twitter API to get additional tweet data (retweet count, favorite count).

## Data Assessment
- **Quality Issues**: Identified issues such as missing values, incorrect data types, and inaccurate ratings.
- **Tidiness Issues**: Identified issues such as multiple columns for dog stages and wide format for image predictions.

## Data Cleaning
- **Quality Fixes**: 
  - Removed retweets and replies.
  - Converted data types.
  - Fixed inaccurate and invalid ratings.
  - Handled missing values and duplicates.
- **Tidiness Fixes**:
  - Merged dog stage columns.
  - Reshaped image predictions data.
  - Combined datasets into a master dataset.

## Analysis and Visualization
- **Tweet Interactions**: Analyzed tweet counts over time, days of the week, and months.
- **Ratings Analysis**: Explored the relationship between ratings, retweet counts, and favorite counts.
- **Dog Stages**: Analyzed the distribution and average ratings of different dog stages.
- **Source of Tweets**: Visualized the sources of tweets (e.g., Twitter for iPhone).
- **Dog Breed Predictions**: Analyzed the most common dog breeds and their prediction confidence.

## Conclusion
The cleaned dataset provides valuable insights into the WeRateDogs Twitter account, including tweet interactions, ratings, and dog breed predictions.

## How to Run
1. Clone the repository.
2. Install necessary libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `tweepy`).
3. Run the Jupyter notebook to see the analysis and results.

## Files
- `twitter-archive-enhanced.csv`: Original Twitter archive.
- `image-predictions.tsv`: Image predictions data.
- `tweet_json.txt`: Additional tweet data from Twitter API.
- `twitter_archive_master.csv`: Cleaned master dataset.
- `wrangle_act.ipynb`: Jupyter notebook containing the data wrangling, analysis, and visualization.

## License
This project is licensed under the MIT License.
