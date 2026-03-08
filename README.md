# Sentiment Analyis: For checking statment sentiment whether it is negative or positive
This project focuses on  predicting sentiment of statements using Deep Learning techniques and exploratory data analysis (EDA) techniques. It demonstrates how data preprocessing, feature engineering, and model tuning can be applied to real-world for better predictions and insights.
## Project Overview
# Sections Covered
1. Libraries used:
   - Data Proprocessing:`Numpy`,`Pandas`
   - Data Visualisation:`Seaborn`,`Matplotlib`
   - Text Preprocessing:`NLTK`,`regex`
   - Deep Learning:`Bidirectional`,`LSTM`,`Embedding`,`Dense` layers and `Dropout` in order to avoid overfitting
   - Model Evaluation:`f1 score`,`confusion matrix`,`precision-recall curve` from `sklearn metrics`

2. Data Loading:
   - The data was imported and preprocessed for analysis and modeling.
3. Exploratory Data Analysis(EDA):
   - The textual data was cleaned using regex
   - for removing urls
   - for removing mention
   - for removing whitespaces
   - stopwords has been used to remove english common words
4. Data Preprocessing and Splitting
   - Tokenization has been used for tokenizing
   - Then using Sequences having `max_len` :150 and total vocabulary size=25000
   - Finally data divided into `train:test` as 80:20
5. Model Building:
   - Using different deep learning layers as
   - `Dense`,`Bidirectional`,`LSTM`,`Dropout`
6. Evaluation :
   Evaluated model using `Confusion Matrix` ,`Precision-Recall-curve` from sklearn metrics  
