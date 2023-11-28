# Credit Card Fraud Prediction 2023
- This project is about creating a model to detect credit card fraud.
- We mainly used the PyCaret package to build and compare models automatically. It can also create blended and stacked models.
- The initial attempt, LightGBM.ipynb training the LightGBM model using the official LightGBM package. However, it wasn't used in the final analysis.
- The primary Jupyter notebook, PyCaret_trial.ipynb, played a key role in creating, comparing, and fine-tuning predictive models.
- When we got a new dataset, we compared the performance of the original model (trained on the initial dataset) with an incremental model (trained on the original model plus new data) and a re-trained model (trained on all data).
- The re-trained model was chosen for the final prediction because it had the highest F1 score compared to all other models.
- The Combine_result_for_uploading.ipynb helped combine different data frames.
- The data came from the AI CUP 2023 玉山人工智慧公開挑戰賽－信用卡冒用偵測