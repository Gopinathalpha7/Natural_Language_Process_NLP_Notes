# Natural Language Process NLP Notes

# Key Stepes Follow

## 1) Import Library

## 2) Import data

## 3) Clean and compress (Data Pre processing)
        1) Sentence Tokenization (Paragraphs to Sentence) (. ! ? ;)
        2) Word Tokenization (Sentance to word) (space, _ :)
        3) Punctual and Special character removal and Making text lower case
        4) Stop word removal (is, a, an, the, them, couldn't, ....)
        5) Lemmatization and Stemming (Extract only the root words from data)
        
## 4) Exploratory Data Analysis (EDA)
        1) Generate a Word Cloud by plotting the data.

## 5) Encoding data (Text data to Numerical data)
* TF-IDF (Term Frequency-Inverse Document Frequency)
* Score of words in a particular row = (Number of times words in row / Total number of  words in row) * log (Number of rows / Number of rows containing the word in them)

## 6) Apply Machine Learning 
        
### 1) Split the data      
         Futures (X - axis) (2D Matrix)
         Targe (Y - axis) (1D Array)
         Train, Test, Split, Random state

### 2) Scaling the data 
           1) Import model
           2) Initialize
           3) Fit (Learning process)
           4) Transform
### 3) Apply Machine learning algorithm
           1) Import model
           2) Initialize
           3) Fit (learning process)
           4) Predict

### 4) Evaluation matric (Check whether the model is correct or not)
           1) Regression - The evaluation metric for regression is R^2 between minus infinite to 1 
            A higher the R^2 is a better model
            
           2) Classification - The evaluation metric for classification is
               1) Accuracy score [ Higher accuracy is a better model (The value should near to 1) ]
               2) F1 score [ F1 score between 0 (low) to 1 (high), Higher F1 score better the model ]

## 7) Sentiment analysis
