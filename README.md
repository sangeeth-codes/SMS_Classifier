# SMS_Classifier
SMS Spam Classifier (Binary Classification) , SMS Classifier (Companion notebook / variant)

SMS Spam Classifier (Binary Classification)
Problem: Identify spam vs ham in SMS messages.
Dataset: UCI SMS Spam Collection (cleaned and split 80/20).
Approach: TF-IDF → Logistic Regression pipeline.
Results: ~97% test accuracy; strong precision/recall for ham, good recall for spam (confusion matrix in PDF).
Artifacts: Saved pipeline (sms_spam_model.joblib) and predict_sms() function.
Key learnings: thresholding and sample distribution matter in imbalanced datasets; TF-IDF + simple linear model is effective for short-text spam detection.

SMS Classifier (Companion notebook / variant)
This file contains the dataset loading, pipeline training, evaluation, and joblib save steps. It complements the spam classifier notebook and demonstrates how to load local datasets, build reproducible pipelines, and export artifacts.
