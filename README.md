# Instructions to Run the Project  

## Step 1: Install Dependencies  
Ensure you have the latest version of Python installed. Use the `install_libraries.ipynb` notebook to install all necessary libraries. Alternatively, each Jupyter Notebook includes a cell for installing the required libraries specific to that notebook.  

## Step 2: Data Collection  
Run `reddit_collection.ipynb` to collect Reddit posts and export the data to `hogwarts_legacy_alltime_posts.csv`.  

## Step 3: Data Preprocessing and Sentiment Analysis  
Run `sentiment_analysis.ipynb` to process and analyze the data:  
1. **Preprocessing:** The first cell preprocesses the data and exports it to `hogwarts_legacy_cleaned_posts.csv`.  
2. **VADER Analysis:** The second cell applies VADER sentiment analysis to the cleaned data and exports the results to `hogwarts_vader_sentiments.csv`.  
3. **BERT Analysis:** The third cell applies BERT sentiment analysis to the cleaned data and exports the results to `hogwarts_bert_sentiments.csv`.  

## Step 4: Apply Classifiers  
Run `sentiment_analysis_classifiers.ipynb` to evaluate sentiment predictions using machine learning classifiers:  
1. The first cell applies classifiers (Naive Bayes, Logistic Regression, and SVM) on `hogwarts_vader_sentiments.csv`.  
2. The second cell applies the same classifiers on `hogwarts_bert_sentiments.csv`.  

## Step 5: Compare Results  
Review and compare the outputs and visualizations from the classifiers to evaluate performance. Analyze metrics like accuracy, precision, recall, and F1-score to interpret the results effectively.  