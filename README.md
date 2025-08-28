## Fake news detection - NLP 

This project focuses on detecting fake news using a combination of classical machine learning models and advanced Natural Language Processing (NLP) techniques. The dataset used contains news articles labeled as "Real" or "Fake," and the goal is to build models that can accurately classify these articles.

## Models :

## Logistic Regression

The text data was transformed into numerical form using TF-IDF vectorization, and a logistic regression model was trained.

Evaluation: 
Accuracy scores and classification reports were used to evaluate performance.

## Naive Bayes Classifier

Approach: This model also made advantage of TF-IDF vectorization. The effectiveness of multinomial Naive Bayes in text categorization led to its selection.
Evaluation: The model's performance was assessed using confusion and accuracy matrices.

## Random Forest Classifier

Approach: Using TF-IDF converted data, a Random Forest model with 100 estimators was trained.
Evaluation: The model's performance was examined using precision, recall, F1-score, and visually represented confusion matrices.

## BERT-tiny (Pre-trained NLP Model)

Approach: The BERT-tiny model from Hugging Face was fine-tuned for the classification task. Sentences were tokenized and encoded using the BERT tokenizer.
Evaluation: Achieved state-of-the-art performance by evaluating the model on unseen test data with visualizations like ROC curves and precision-recall curves.

## Data Visualization

The project includes various visualization techniques:

Confusion Matrices: To visually interpret model performance and error distribution.
ROC Curves: For assessing the trade-off between true positive and false positive rates across different models.
Precision-Recall Curves: Highlighting the precision and recall balance for each model, emphasizing the BERT-tiny model's effectiveness.
Feature Importance: For the Random Forest model, the most influential features in predicting fake news were visualized.

## Conclusion

This notebook demonstrates the effectiveness of combining classical machine learning models with advanced NLP techniques for fake news detection. The BERT-tiny model particularly stands out in achieving high accuracy, showcasing the power of transformer models in NLP tasks.
