# Beauty & Skincare Sentiment Analysis Using Python

## Project Overview
This project explores customer sentiment toward skincare products using Python and data science techniques. It was developed as part of a Data Science with Python internship task focused on the beauty and wellness industry.

## Objectives
- Explore customer ratings and skincare review data.
- Classify review text as positive, negative, or neutral using VADER.
- Compare predicted sentiment with customer star ratings.
- Explore sentiment patterns across brands and products.
- Identify potential customer feedback themes using keyword analysis.

## Dataset
The analysis uses a skincare product review dataset containing 1,094,411 records. After basic text cleaning, 1,092,967 records had usable review text.

A sample of 1,000 reviews was used for the initial sentiment analysis. Refer to the original dataset source and its license before accessing or redistributing the data.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- VADER Sentiment Analysis
- Jupyter Notebook

## Methodology
1. Load and inspect the dataset.
2. Check missing values and prepare review text.
3. Explore customer star ratings.
4. Apply VADER sentiment classification.
5. Compare predicted sentiment with star ratings.
6. Analyze sentiment across brands and products.
7. Explore common keywords in negative-predicted reviews.
8. Interpret findings and document limitations.

## Preliminary Results
In the sample of 1,000 reviews, VADER classified 898 as positive, 77 as negative, and 25 as neutral.

A predefined rating–sentiment mismatch rule identified 75 reviews, representing 7.50% of the sample. Keyword-based exploration identified potential themes related to dryness and hydration, fragrance, texture and application, irritation, and product effectiveness.

## Limitations
The sentiment results are exploratory and have not been validated against a manually labelled dataset. Keyword matches do not necessarily represent confirmed complaints, and small product-level sample sizes limit comparisons.

## Future Improvements
- Validate sentiment predictions using manually labelled reviews.
- Improve customer complaint classification.
- Explore aspect-based sentiment analysis.
- Expand the analysis and evaluate model performance.

## Author
Aryan Katakdhond
