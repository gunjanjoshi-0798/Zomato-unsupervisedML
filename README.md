# Zomato Restaurant Analysis

## Problem Statement

The project focuses on analyzing the sentiments of customer reviews and clustering Zomato restaurants into different segments. The goal is to provide useful insights for both customers and the company, helping customers find the best restaurants in their locality and assisting the company in areas where they are lagging.

## Dataset Description

### Zomato Restaurant Names and Metadata

- `Name`: Name of the restaurant
- `Links`: URL links of the restaurants
- `Cost`: Per person estimated cost of dining
- `Collection`: Tagging of restaurants with respect to Zomato categories
- `Cuisines`: Cuisines served by restaurants
- `Timings`: Restaurant timings

### Zomato Restaurant Reviews

- `Restaurant`: Name of the restaurant
- `Reviewer`: Name of the reviewer
- `Review`: Review text
- `Rating`: Rating provided by reviewer
- `MetaData`: Reviewer metadata - number of reviews and followers
- `Time`: Date and time of review

## Project Description

- EDA - Performed exploratory data analysis and text preprocessing
- Data CLeaning - I had to drop the entire feature as there were more than 50% null values
- Feature Selection - For sentiment analysis, we have used rating and reviews features. - For clustering we got cost, cusine and timing of the restaurant as the features to build the model
- Model development - For sentiment analysis, developed different models like: logistic regression, Random Forest classifier
## Approach

1. **Sentiment Analysis**: Analyzed the sentiments of the reviews to understand customer feedback.
2. **Clustering**: Clustered the restaurants into different segments based on metadata and reviews.
3. **Visualizations**: Created visualizations to present the findings in an understandable manner.
4. **Business Cases**: Solved business cases such as finding the best restaurants and identifying critics in the industry.

## Libraries Used

- numpy
- pandas
- matplotlib.pyplot
- seaborn
- wordcloud
- nltk
- sklearn.feature_extraction.text.CountVectorizer

## Conclusion

The project was successful in achieving the goals of clustering and sentiment analysis. The clustering part provided insights into the grouping of restaurants based on their features, which can help in decision making for users and businesses. The sentiment analysis part provided insights into the sentiments expressed by the users in their reviews, which can help businesses in improving their services and user experience.


## Author
Gunjan Joshi
gunjan.joshi513@gmail.com
