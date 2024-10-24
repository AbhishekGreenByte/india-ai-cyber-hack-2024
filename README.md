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

### 1. Preprocessing
   - Removed extra spaces
   - Dropped NaN rows
   - Removed duplicate rows
   - Removed rows with less than 20 characters in the text description (`crimeaditionalinfo`)

### 2. Exploratory Data Analysis (EDA)
   - Category Distribution (category vs. count)
   - Sub-Category Distribution
   - Bar and Pie Charts
   - Distribution of Word Lengths (histogram)
   - Further analysis and insights...(Any Ideas?)

## Pending Tasks

### 1. Preprocessing
   - **N-gram Analysis:** Analyze n-grams (1, 2, or 3-word sequences) to identify common phrases in crime descriptions.
   - **TF-IDF and Category Correlation:** Use TF-IDF to assess word importance across different categories.
   - **Chi-Square Test:** Check for significant associations between words and categories.
   - Correct spellings
   - Handle different languages (especially Hindi in English script)
   - Address class imbalance (consider class weighting)
   - Remove stop words, perform tokenization, and apply lemmatization/stemming

### 2. Embeddings
   - Use **SBERT** (experiment with both pretrained and fine-tuned versions on our dataset)
   - Explore domain-adapted SBERT or other BERT-based models
   - Extract key phrases like subjects, verbs, and objects using **SpaCy**, and compute their embeddings

### 3. Model Design
   - Implement a **Multi-Task Learning (MTL) Model** for classification using a neural network
   - Advanced Approach: Apply **Transfer Learning with BERT and MTL**
   - Use ensemble methods like **XGBoost** and **LSTM** on embeddings
   - Investigate the potential of clustering techniques

### 4. Pipeline Preparation
   - Convert relevant code into Python files
   - Create a pipeline for processing new data end-to-end
   - Develop and host a webpage for the system

### 5. Submission Requirements
   - Prepare the final report
   - Use **Sphinx** for documentation
   - Clean the code, add comments, and include proper visualizations
