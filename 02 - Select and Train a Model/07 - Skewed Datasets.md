# Skewed Datasets

 - Skewed Datasets have a significant imbalance between positive and negative examples, far from a 50/50 ratio.
 - Examples of Skewed Datasets:
    - In smartphone production, if 99.7% of devices are defect-free (labeled y=0) and only 0.3% are defective (labeled y=1), a trivial algorithm predicting all devices as defect-free would achieve 99.7% accuracy;
    - In medical diagnosis, if 99% of patients don’t have a disease, an algorithm that predicts no disease for everyone would have 99% accuracy;
    - In systems that detect wake words like “Alexa” or “Hey Siri”, where a small percentage (e.g., 3.3%) are positive examples.

# Limitations of Accuracy in Skewed Datasets

 - Raw accuracy can be misleading in skewed datasets since a model predicting only the majority class can achieve high accuracy;
 - A better way to evaluate model performance in skewed datasets is by categorizing predictions into:
    - **True Negatives (TN):** Correctly predicted negative examples;
    - **True Positives (TP):** Correctly predicted positive examples;
    - **False Negatives (FN):** Actual positives incorrectly predicted as negative;
    - **False Positives (FP):** Actual negatives incorrectly predicted as positive.

# Precision and Recall

 - Precision is the fraction of correctly predicted positive examples out of all predicted positives (TP / (TP + FP));
 - Recall is the fraction of correctly predicted positive examples out of all actual positives (TP / (TP + FN)).

# F1 Score
  
 - A metric combining precision and recall, calculated as the harmonic mean of the two;
 - Emphasizes the lower value between precision and recall, making it a balanced metric for skewed datasets.
