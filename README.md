# ChatGPT Review Analysis

## Project Overview
This project analyzes customer reviews of ChatGPT to understand user sentiment, explore rating patterns, and identify frequently mentioned positive and negative themes.

## Objectives
- Perform data cleaning and preprocessing.
- Explore customer ratings and monthly review activity.
- Calculate sentiment polarity and subjectivity using TextBlob.
- Classify reviews as positive, neutral, or negative.
- Extract frequent keywords from positive and negative reviews.
- Visualize findings and develop actionable recommendations.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- TextBlob
- WordCloud

## Dataset
The original dataset contains 196,727 records and four columns: review ID, review text, rating, and review date.

After removing 2,511 exact duplicate rows, 194,216 records remained. Six records with missing review text were excluded from text-based sentiment analysis, leaving 194,210 reviews for sentiment analysis.

## Key Findings
- 76.34% of the records after duplicate removal had a five-star rating.
- 76.32% of analyzed reviews were classified as positive.
- 19.53% were classified as neutral.
- 4.15% were classified as negative.
- Average polarity was 0.4469.
- Average subjectivity was 0.5167.

Positive-review keywords included "good", "helpful", and "useful". Negative-review keywords included "wrong", "bad", and "error".

## Methodology
The project uses exploratory data analysis, TextBlob sentiment scoring, keyword frequency analysis, and data visualization.

## Limitations
TextBlob may misinterpret sarcasm, mixed sentiment, and context-dependent language. Results are automated estimates and should not be treated as definitive measures of customer satisfaction.

## Future Improvements
- Validate sentiment classifications against manually labeled reviews.
- Compare TextBlob with context-aware sentiment models.
- Use topic modeling to identify recurring customer concerns.

## How to Run
Open the notebook in Google Colab, upload the authorized dataset, and execute the cells from beginning to end.

## Author
Add your name here.

