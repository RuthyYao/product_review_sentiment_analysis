# Sentiment Analysis on Amazon Customers Review

![read-me-banner-cropped-img](./images/read_me_banner_cropped.PNG)

## Project Overview
This project applied NLP models to convert review text into numerical representations and implemented machine learning models to predict sentiment. This will help in understanding customer feedback, identifying product strengths and weaknesses and improving the overall customer experience. 

## Business Problem
PawPure is an online store selling dog and cat food. Every day their customers leave thousands of reviews. These reviews are rich sources of customer feedback but are often unstructured, making manual analysis time-consuming and inefficient. The leadership team needs to quickly interpret the sentiments expressed in these reviews to understand how customers feel about their products, identify key pain points and adjust their business strategies accordingly. However, sorting through vast amounts of text data to understand customer sentiment (positive or negative) poses a significant challenge. 

The data analytics team was asked to automate the process of sentiment analysis using machine learning (ML) and natural language processing (NLP) techniques. By automating sentiment detection, the leadership team can gain real-time insights from reviews, leading to better decision-making, improved product offerings and enhanced customer satisfaction.

## Data Understanding
The original dataset has over 560,000 pieces of reviews from Oct 1999 to Oct 2012, each with the customer who wrote the review, the product ID, the date and time of the review and the rating score. As we are only interested in the recent customer's feedback about our products, the dataset was trimmed to include only the last twelve months' reviews. The subsetted dataset has over 233,000 pieces of data.

The rating score from 1 to 5 represent the "Actual" sentiment from the customers. Since we use the review text to predict the sentiment, we assess the prediction accuracy against the "Actual" sentiment. The sentiment is divided to "Positive" and "Negative". Score above 3 will be classified as "positive" , otherwise the sentiment is "negative". The split of the data is 75 postive : 25 negative, which is inbalanced. 

## Methodology
I build a Term-doc incidence matrix using term frequency and inverse document frequency ponderation (TF-IDF) model to convert the text to numerical. I put in some explanation on why I choose TF-IDF model over the Bag-of-word models. To predict the sentiment, I fit into two machine learning models for comparision - Logistic Regression and Random Forest Model. 

## Analytical Process
I took the following steps for this sentiment analysis and prediction.

 * Data cleaning including text preprocessing, implemented stemming, punctuation removal, lower case conversion.
 * Prepare the data to get the observed *frequency*.
 * Run the Chi-square test to obtain the chi-square statistics and the p-value.
 * Calculate the critical value using Python's Scipy package.

## Reuslts


## Applications

