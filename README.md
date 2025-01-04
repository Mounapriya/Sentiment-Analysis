# Sentiment Analysis of Product Reviews

This project analyzes customer product reviews, categorizing them into positive, neutral, and negative sentiments based on their rating. The analysis helps identify trends in customer satisfaction and extract valuable insights from textual feedback.

## Dataset

The dataset used for this project contains product reviews paired with their corresponding ratings. Reviews provide textual feedback on products, while ratings are assigned on a 1 to 5 scale. The data is used to explore how reviews are distributed across different sentiment categories.

### Sample dataset format:

| Review | Rating |
|--------|--------|
| "It was a nice product. I like its design a lot." | 5 |
| "Awesome sound, very pretty to see this and think." | 5 |
| "Great sound quality. Battery lasts for 7-8 hours." | 4 |
| "I think it is a good product, not only as expected but beyond." | 5 |
| "Fantastic bass sound, very good battery life." | 5 |

## Sentiment Classification

Each review is classified based on the rating it has been given:

- **Positive**: Rating of 4 or 5 stars
- **Neutral**: Rating of 3 stars
- **Negative**: Rating of 1 or 2 stars

### Data Preprocessing Steps:
- **Text Cleaning**: Removal of unwanted characters (special characters, extra spaces, etc.)
- **Text Normalization**: Conversion to lowercase and lemmatization to reduce words to their base forms
- **Stopword Removal**: Removal of common but unimportant words (e.g., "the", "and", etc.)
- **Unwanted Text Removal**: Deleting specific words like "READ MORE" that are irrelevant to sentiment analysis.

## Visualizations

To gain insights from the reviews, the following visualizations are provided:

- **Sentiment Distribution**: A bar plot that shows how reviews are distributed across each sentiment category (positive, neutral, negative).
- **Word Cloud**: For each rating category (1-5 stars), a word cloud is generated to display the most common words in reviews.

## Requirements

To run this project, you will need the following Python libraries:
- **Python 3.x**
- **Pandas**: For data manipulation
- **NLTK**: For text preprocessing (tokenization, lemmatization, etc.)
- **Matplotlib**: For generating visualizations
- **WordCloud**: For creating word clouds from reviews
