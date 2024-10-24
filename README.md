# IndiaAI CyberGuard AI Hackathon

## Team Name: TO_BE_DECIDED

## Team Members:
1. **Abhishek Sahu** (Software Developer @ Oracle, MTech in CSE @ IIT Kanpur)
2. **Apoorva Dixit** (Engineer @ Qualcomm, MSR in EE @ IIT Kanpur)
3. **Ayush Mishra** (Data Scientist @ Oracle, MSR in CSE @ IIT Kanpur)
4. **Manish Kumar** (Software Developer @ CDIS, MTech in CSE @ IIT Kanpur)
5. **Raju Ranjan Gupta** (Software Developer @ Cisco, Distributed Systems)
6. **Tanikella Sai Kiran** (Software Developer @ Intel, MTech in CSE @ IIT Kanpur)

Table of Contents
=================
* [Problem Statement](#problem-statement)
* [Project Structure](#project-structure)

## Problem Statement:

## Project Structure

## Progress
1. Preprocessing:
    a. removed extraspaces
    b. dropped NaN rows
    c. removed duplicate rows
    d. removed rows with less that 20 characters text description (crimeaditionalinfo)
2. EDA:
    a. Category Distribution (category vs count)
    b. Sub-Category Distribution
    c. Bar and Pie charts
    d. Distribution of word lengths histogram
    e. Think Think Think...

## Pending
1. Preprocessing:
    a. N-gram Analysis: Analyze n-grams (sequences of 1, 2, or 3 words) to understand common phrases used in the crime descriptions.
    b. TF-IDF and Category Correlation: Use Term Frequency-Inverse Document Frequency (TF-IDF) to analyze the importance of words in different categories.
    c. Chi-Square Test: Perform a chi-square test to check if certain words are significantly associated with a particular category.
    d. Correct the spellings
    e. Handle different languages (esp. Hindi in English script)
    f. Handle class imbalance (Use class weighting?)
    g. Remove Stop words, tokenization, lemmatization/stemming

2. Embeddings:
    a. Use SBERT (try both pretrained and finetuned on our dataset)
    b. Check for domain adapted SBERT or other BERT based models
    c. Also try to condense text to key words like subjects, verbs and objects using SpaCy and get the embeddings.

3. Model Design:
    a. We can use Multi Task Learning Model for classification(Neural Network)
    b. Advanced Approach: Transfer Learning with BERT and MTL.
    C. Use Ensemble methods on embeddings like XGBoost, LSTM etc.
    d. Can we use clustering techniques?

4. Pipeline Preparation:
    a. Convert the necessary code into python file
    b. Create necessary pipeline to process new data end to end.
    c. Create a webpage and host this system.

5. Submission requirements:
    a. Prepare Report
    b. Use sphinx for documentation.
    c. Clean the code, add proper comments and visualizations.
