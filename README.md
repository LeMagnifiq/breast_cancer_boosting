# breast_cancer_boosting
Predicting breast cancer with Gradient Boosting and AdaBoost.
This project predicts breast cancer diagnoses using the Breast Cancer Wisconsin Dataset, achieving 95.6% accuracy (93% recall for malignant cases) with tuned Gradient Boosting and 97.4% accuracy (95% recall) with AdaBoost.
Summary and Findings
I developed Gradient Boosting and AdaBoost models, tuning Gradient Boosting to learning_rate=0.05 and n_estimators=100. Gradient Boosting highlighted ‘mean concave points’ (44%) and ‘worst concave points’ (22%) as top predictors, aligning with clinical signs of tumour irregularity, while AdaBoost excelled at benign case recall (99%) through adaptive weighting. Both boosting algorithms ensured minimal missed diagnoses compared to a 97.4% accurate Logistic Regression baseline. This project showcases boosting for interpretable, high-stakes medical classification, supporting early cancer detection.

