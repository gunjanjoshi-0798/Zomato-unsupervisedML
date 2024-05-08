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

## Usage

1. Clone the repository: `git clone https://github.com/gunjanjoshi-0798/Zomato-unsupervisedML.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the collab notebook or Python script to perform the analysis and clustering.

## Authors
Gunjan Joshi
gunjan.joshi513@gmail.com
