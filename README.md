# Credit Card Fraud Prediction 2023
### Overview
This project builds a machine learning model to detect fraudulent credit card transactions using a dataset from the AI Cup 2023 competition. The goal is to accurately classify transactions as fraudulent or genuine.

### Methodology
The modeling approach primarily uses the PyCaret library to efficiently build, compare, and tune multiple machine learning models. The goal is to optimize the F1-score. The final model chosen is a LightGBM classifier trained on all available data.

### Key Files
- [PyCaret_trial.ipynb](https://github.com/chun-yu-L/Credit-Card-Fraud-Prediction-2023/blob/main/PyCaret_trial.ipynb): Created, compared, and tuned machine learning models like LightGBM, Logistic Regression, MLP, Random Forest, etc. using the PyCaret library.
- [Incremental_and_final_model.ipynb](https://github.com/chun-yu-L/Credit-Card-Fraud-Prediction-2023/blob/main/Incremental_and_final_model.ipynb): Compared performance by re-training on new data vs incrementally updating original model
- [Combine_result_for_uploading.ipynb](https://github.com/chun-yu-L/Credit-Card-Fraud-Prediction-2023/blob/main/Combine_result_for_uploading.ipynb): Concatenates dataframes for submission to the competition
- [LightGBM.ipynb](https://github.com/chun-yu-L/Credit-Card-Fraud-Prediction-2023/blob/main/LightGBM.ipynb) : First attempt. built and trained a LightGBM model using the LightGBM package, including data cleaning steps. This standalone approach was replaced by modeling with PyCaret later on.

### Data
The data comes from the AI CUP 2023 玉山人工智慧公開挑戰賽-信用卡冒用偵測 competition. It contains over 9 million credit card transactions with 26 feature variables including transaction amount, vendor information, and time of purchase. The target variable indicates fraudulent (1) or genuine (0) transactions.
