# Fake-News-Detection
# Fake-News-Detection-Machine-Learning
Currently, we are in a world of mis-information and fake news. The goal is to detect fake news based on Recurrent Neural Networks.

Al/ML-based fake news detector is crucial for companies and media to automatically predict whether circulating news is fake or not.

## Dataset
The dataset is taken from Kaggle. It contains 20,800 news articles, each labeled with one of the four labels: true, mostly-true, half-true, barely-true, false, pants-fire. The dataset is split into 70% training and 30% testing.

## Model
3 Models are used to detect fake news:
1. Lenear Regression
2. Random Forest
3. K'Nearest Neighbors

## Results

| Model | Accuracy |
| --- | --- |
| Linear Regression | 0.98 |
| Random Forest | 0.98 |
| K'Nearest Neighbors | 0.69 |

## Training the Model on the Dataset

1. Training Accuracy of Logistic Regression is:  0.9910571038089013
2. Training Accuracy of Random Forest Classifier is:  1.0
3. Training Accuracy of KNN Classifier is:  0.7312674549884128
5. Training Accuracy of Hybrid Model of Logistic Regression and KNN Classifier is:  0.9744191574068573

## Testing the Model on the Dataset
1. Testing Accuracy of Logistic Regression is:  0.9863636363636363
2. Testing Accuracy of Random Forest Classifier is:  0.9889483065953654
3. Testing Accuracy of KNN Classifier is:  0.6919786096256685
4. Testing Accuracy of Hybrid Model of Logistic Regression and KNN Classifier is:  0.814795008912656
## Dynamic Interface
![Fake-News-Detection](DynamicSystem.png)