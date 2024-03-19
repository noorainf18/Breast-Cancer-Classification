<p align="center"><img width=100% src="https://github.com/noorainf18/noorainf18/blob/main/Noorain%20Fathima%20-%20Banner.png"></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.11+-blue.svg)
![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# BREAST CANCER CLASSIFICATION

The main objective of this problem is to build a machine-learning model that can accurately classify breast masses as either benign or malignant based on a set of features of tissue samples from breast cancer patients. Accurate classification of breast cancer as benign or malignant is crucial for timely and appropriate treatment, as well as for improving patient outcomes. Early detection and diagnosis of breast cancer can significantly increase the chances of successful treatment and survival.


### Table of Contents

1. Data Description
2. Models Used
6. Results
7. Conclusion


## Data Description

The dataset used for this problem is the Breast Cancer Dataset sourced from Kaggle, which contains 569 instances, with 5 features and the target variable (diagnosis). The features include information such as the mean radius, mean texture, mean perimeter, mean area, and mean smoothness. The target variable is a binary variable with a value of 0 for benign and 1 for malignant.


## Models Used

- **Gradient Boosting:** The key idea behind Gradient Boosting is to iteratively add new models to the ensemble that correct the errors made by the previous models. This is done by fitting the new models to the residual errors of the previous models, which helps to gradually improve the overall performance of the ensemble.
- **Random Forest:** The key idea behind Random Forest is to build a set of decision trees, where each tree is trained on a random subset of the training data and a random subset of the features. This helps to reduce overfitting and improve the generalization performance of the model.
- **Extreme Gradient Boosting:** Extreme Gradient Boosting (XGBoost) is a powerful machine learning algorithm used for both classification and regression tasks. It is an optimized version of the Gradient Boosting algorithm that is designed to be faster and more scalable. XGBoost uses a regularized objective function to prevent overfitting and improve the generalization performance of the model.
- **Adaptive Boosting:** Extreme Gradient Boosting (XGBoost) is a powerful machine learning algorithm used for both classification and regression tasks. It is an optimized version of the Gradient Boosting algorithm that is designed to be faster and more scalable. XGBoost uses a regularized objective function to prevent overfitting and improve the generalization performance of the model.


## Results

With an impressive accuracy of 92.11%, the Random Forest model demonstrates the power of machine learning in accurately discerning between benign and malignant breast masses.
| Ranking    | Model                        | Accuracy    | F1-Score    | Recall    | Precision    |
| -----------|:-------------                |:-----:      |:-----:      |:-----:    |:-----:       |
| 1          | Random Forest                | 92.11       | 93.62       | 91.67     | 95.65        |
| 2          | Gradient Boosting            | 91.23       | 92.86       | 90.28     | 95.59        |
| 3          | Adaptive Boosting            | 90.35       | 92.20       | 90.28     | 94.20        |
| 4          | Extreme Gradient Boosting    | 89.47       | 91.30       | 87.50     | 95.45        |


## License

MIT License

Copyright (c) 2024 Noorain Fathima

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
