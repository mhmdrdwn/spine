## Lower Back Pain Dataset

This report is part of the interview process at Oslo Metropolitan University in Norway

In this report, we will use machine learning models for classification lower back pain. The task is to classify whether each data sample is normal or abnormal based of a set of features. The number of features in the dataset is 12. The used dataset is https://www.kaggle.com/datasets/sammy123/lower-back-pain-symptoms-dataset.

### Results

| Model                 | Accuracy    | F1     | Precision   | Recall |
| --------------------- |:-----------:|:------:|:-----------:|:------:|
| Logistic Regression   |  0.863      |  0.841 |      0.847  | 0.835  |
| Random Forest         |  **0.892**  | **0.874** | **0.885** | **0.865**  |
| Decision Tree         |  0.775      |  0.744 | 0.743       | 0.746  |
| Support Vector Machine|  0.863      |  0.841 | 0.847       | 0.835  |
| Multilayer Perceptron |  0.882      |  0.866 | 0.865       | 0.866  |


