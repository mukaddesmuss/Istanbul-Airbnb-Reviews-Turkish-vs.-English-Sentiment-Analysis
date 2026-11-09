# Istanbul Airbnb Reviews: Turkish vs. English Sentiment Analysis

## About the Project

This project presents a comparative sentiment analysis of Turkish and English Airbnb reviews in Istanbul using Natural Language Processing (NLP) and Machine Learning techniques.

The study investigates language-based differences in guest satisfaction and accommodation experiences by analyzing customer reviews in two languages. It explores sentiment distributions, compares classification approaches, and examines how guests express positive and non-positive experiences.

## Research Objectives

- Analyze Turkish and English Airbnb guest reviews.
- Classify reviews based on their sentiment.
- Compare sentiment distributions across the two languages.
- Identify differences in customer satisfaction and feedback.
- Investigate the relationship between language and guest experience.

## Dataset

- **Location:** Istanbul, Türkiye
- **Languages:** Turkish and English
- **Data Source:** [Inside Airbnb](http://insideairbnb.com/)
- **Data Type:** Airbnb listings and guest reviews
- **Analysis Period:** January – September 2025
- **Sample Size:** 6,000 reviews (3,000 Turkish and 3,000 English)

The dataset was cleaned, preprocessed, and balanced to support a comparative analysis between the two languages.

## Methodology

The study follows a structured data analysis and machine learning workflow:

1. **Data Collection & Preparation:** Collecting Airbnb review data and merging relevant datasets.
2. **Text Preprocessing:** Cleaning text data, removing unnecessary elements, and preparing reviews for analysis.
3. **Sentiment Analysis:**
   - VADER sentiment analysis for English reviews.
   - TF-IDF-based machine learning models for Turkish reviews.
4. **Machine Learning Model Comparison:** Evaluating Logistic Regression, Linear SVM, and Multinomial Naive Bayes models.
5. **Statistical Analysis:** Comparing sentiment distributions and examining language-based differences.
6. **Data Visualization:** Presenting findings through statistical charts and comparative visualizations.

## Machine Learning Models

The following models and approaches were explored:

| Model | Application |
|---|---|
| VADER | English sentiment classification |
| Logistic Regression | Turkish sentiment classification |
| Linear SVM | Turkish model comparison |
| Multinomial Naive Bayes | Turkish model comparison |

TF-IDF was used for text feature extraction, with unigram and bigram representations.

## Key Findings

- Turkish reviews showed a higher proportion of non-positive sentiment compared to English reviews.
- English reviews were predominantly classified as positive.
- Statistical tests indicated a significant difference in sentiment distributions between the two languages.
- Logistic Regression achieved a **Macro F1-score of 0.831** on the Turkish test dataset.
- The relationship between review language and sentiment remained statistically significant after controlling for selected listing characteristics, including price, room type, and neighborhood.

## Tools & Technologies

- **Programming:** Python
- **Data Analysis:** Pandas, NumPy
- **Natural Language Processing:** NLTK, langdetect
- **Machine Learning:** Scikit-learn
- **Text Representation:** TF-IDF
- **Visualization:** Matplotlib, Seaborn
- **Statistical Analysis:** Hypothesis Testing, Logistic Regression

## Project Outcomes

This research highlights how language can be associated with differences in customer feedback and reported accommodation experiences.

By combining NLP, machine learning, and statistical analysis, the project provides a comparative perspective on multilingual customer reviews in the tourism and accommodation industry.

## Project Status

<badge>Completed</badge>

**Academic Thesis Project – 2026**

## Keywords

Airbnb, Istanbul, Sentiment Analysis, Natural Language Processing, Turkish NLP, English NLP, Machine Learning, TF-IDF, Customer Reviews, Tourism Analytics, Comparative Analysis
