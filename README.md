# NLP_Statistical_Author_Features_Prediction
Title: Multi-label Text Classification for Blog Post Labeling

Business Objective: To develop a multi-label text classification model that can accurately predict and assign relevant labels to blog posts based on their content, including gender, age, topic, and sign.

Approach: The code preprocesses the text data by removing unwanted characters, converting text to lowercase, removing spaces, and eliminating stopwords. It then merges the label columns into a single column. The dataset is split into training and testing sets. The training data is transformed using CountVectorizer to create a term-document matrix. The OneVsRestClassifier is used to wrap a Logistic Regression classifier for multi-label classification. Evaluation metrics such as accuracy, F1 score, average precision, and average recall are calculated. Finally, the predicted labels are compared with the true labels for selected examples.

Tools Used: Python, pandas, numpy, scikit-learn, nltk




