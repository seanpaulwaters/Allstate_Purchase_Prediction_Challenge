# Insurance Policy Prediction

## Overview
This project focuses on predicting a customer's final insurance policy choice based on their shopping history. Utilizing a dataset provided in a Kaggle competition, the goal was to forecast the coverage options a customer will select. The model's accuracy is evaluated based on whether it can predict all coverage options correctly for each customer.

## Key Highlights
- The project entails preprocessing, feature engineering, model training, and prediction.
- Major challenges included managing historical shopping point data and integrating it into the model.
- The model achieved a score of 0.51666, closely following the winning team's score of 0.53743.
- Due to hardware limitations, hyperparameter tuning was constrained, highlighting the importance of computational resources in machine learning tasks.

## Dataset Description
The dataset comprises transaction histories, where each row represents a customer's quote with varying coverage options. The challenge was to predict the purchased coverage options using a subset of the interaction history.

## Model Development
- **Preprocessing:** Included handling missing values and encoding categorical variables.
- **Feature Engineering:** Extracted significant features from the shopping history, such as cost changes and option preferences.
- **Model Training:** Utilized a RandomForestClassifier for prediction.
- **Prediction:** Focused on predicting the final policy choice for each customer based on the last known shopping point.

## Challenges Faced
- Handling the historical shopping points data was intricate, requiring thoughtful feature extraction and modeling strategies to account for temporal data.
- Computational limitations restricted extensive hyperparameter tuning, emphasizing the need for adequate resources for optimal model performance.

## Conclusion
Despite hardware constraints and the challenges posed by the dataset, the project underscores the potential of machine learning in predicting customer preferences in dynamic contexts like insurance policy shopping. Future work could explore more complex models and hyperparameter optimization techniques to improve prediction accuracy.

## License
Specify the license under which the project is released.

## Citation
JeffFitzgerald, Will Cukierski. (2014). Allstate Purchase Prediction Challenge. Kaggle. https://kaggle.com/competitions/allstate-purchase-prediction-challenge
