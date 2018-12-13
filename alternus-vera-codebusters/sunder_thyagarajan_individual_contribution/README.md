# Alternus Vera 

Course code : **CMPE-257** 
    
Group name : **Codebusters**
    

### Liar Liar Pants on Fire Dataset Description 
- It has 3 files test, training and valid.
- Each file has 14 columns
   - Column 1: the ID of the statement ([ID].json).
   - Column 2: the label.
   - Column 3: the statement.
   - Column 4: the subject(s).
   - Column 5: the speaker.
   - Column 6: the speaker's job title.
   - Column 7: the state info.
   - Column 8: the party affiliation.
   - Column 9-13: the total credit history count, including the current
    statement. 9: barely true counts, 10: false counts, 11: half true counts, 12: mostly true counts, 13: pants on fire counts.
   - Column 14: the context (venue / location of the speech or statement).
        
## Business Problem

Fake news problem is too important to ignore especially after recent election of Donald Trump. These news are like malignant tumor that causes moral treats. It is nothing but a nassault on truth. Being impartial about the real news are same as that of a deliberate lies.

The main purpose of this project is to identify essential features that can be trusted to predict if a news is fake or not. These features are realted to the news content. Our key classification is to predict if a news is fake or not based on these features. In addition, we are also intended to learn various deep learning and neural networking techniques and compare their performances.


We initially as a team performend literature survey on list of features that has so far played major role in popularising a fake news. Each member of the team took one major feature and performed distillation process. We vectorized and came up with embedding vectors. Computed polynomial equation and classified the news articles based on all the below features. 



- Name: Sunder Thyagarajan
- Student ID: 011528062

## Contributions

* ### Sunder Thyagarajan : Complex Features : Context, Spam
    - ####  Data Preparation
    - ####  Data Observation
    - ####  Data Visualization
    - ####  Featured Extraction, 
    - ####  Classification, 
    - ####  Distillation 
            - LDA 
            - LDA2Vec
            - DOC2VEC
            - Word2Vec
            - MeanEmbeddingVectorizer
            - Topic Modeling
            - Sentiment Analysis
    - ####  Extract Feature Vector
    - ####  Tag Documents using the Label
    - ####  DOC2VEC on Tagged Documents
    - ####  Concat distilled vectors with  LDA and Sentiment
    - ####  Classification
       -  Naives Bayes regression
       -  Logistic regression
       -  Linear SVM Classifier
       -  SVM Stochastic Gradient Descent on hinge loss
       -  RandomForestClassifier
    - ####  Validation
       -  K-Fold cross validation