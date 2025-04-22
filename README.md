# Spam_Detection
This project focuses on detecting spam emails using a machine learning approach. Based on a dataset with word frequencies and special character occurrences, the model classifies emails as either spam or non-spam.

# 🧠 Techniques Used:
Data Preprocessing using word and character frequency features.

Exploratory Data Analysis (EDA) with correlation heatmaps and confusion matrices.

Machine Learning Models including Logistic Regression and Decision Trees.

Feature Importance Analysis to identify which words are most strongly associated with spam.

Evaluation Metrics like Accuracy, Precision, Recall, and F1-Score.

# 🔍 Key Insights:
Words like "remove", "free", and "our" are strongly correlated with spam messages.

The confusion matrix was used to track true positives, false negatives, and misclassifications.

The model achieved over 85% accuracy with proper tuning.

# 📊 Dataset:
The dataset includes features such as:

word_freq_make, word_freq_address, ..., word_freq_remove

Character frequencies: char_freq_;, char_freq_!, etc.

Capitalization patterns like capital_run_length_total
