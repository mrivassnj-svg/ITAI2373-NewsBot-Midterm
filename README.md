1. This File Contains proper implementation for the following steps:
   # NewsBot Intelligence System - Midterm Project
   **Author:** Michael Rivas  
   **Course:** ITAI2373  
   **Date:** 12/10/2025  
   **Repository:** https://github.com/mrivassnj-svg/ITAI2373-NewsBot-Midterm  

   ## Project Overview
   This project demonstrates the development of a news classification system using Natural Language Processing    (NLP). The system categorizes news articles into predefined categories using techniques such as TF-IDF    vectorization, Naive Bayes classification, and named entity recognition.

   ### Dataset Information
   The dataset used in this project is the **BBC News dataset**, which contains labeled news articles categorized    into various types. The dataset consists of two CSV files:
   - **BBC News Train.csv**: Training data
   - **BBC News Test.csv**: Test data
   - **BBC News Sample Solution.csv**: Ground truth for evaluation

   ### Key Modules
   1. **Data Preprocessing**: Cleaning and preparing the text data.
   2. **Text Classification**: Using TF-IDF and Naive Bayes to classify articles.
   3. **Evaluation**: Generating classification reports and confusion matrix visualizations.

   ### Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/mrivassnj-svg/ITAI2373-NewsBot-Midterm.git
   cd ITAI2373-NewsBot-Midterm

2. To install dependancies:
   pip install -r requirements.txt

3. Download and upload the required datasets (BBC News Train.csv, BBC News Test.csv, and BBC News Sample Solution.csv) into the data/ directory. The script expects these files to be available in the specified paths.

4. Run the Jupyter notebook in notebooks/NewsBot_Midterm_Project.ipynb or run the preprocessing, modeling, and evaluation scripts individually.

# Files and Folder Structure

- data/: Contains the raw and cleaned datasets

- notebooks/: Contains the main Jupyter notebook with all analysis and model code

- src/: Contains Python scripts for preprocessing, modeling, and evaluation

- results/: Contains output files like classification reports, confusion matrices, and performance metrics

# Dataset Description

The dataset used is the BBC News dataset from Kaggle. It includes articles with the following columns:

- Text: The news article text

- Category: The article's category label (e.g., Technology, Sports, Business, Entertainment)

# License

   This project is licensed under the MIT License - see the LICENSE
    file for details.
