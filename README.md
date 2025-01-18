# Wine Classification with KNN: Enhancing Quality Prediction in Winemaking

## Business Problem

The global wine industry faces increasing demand for consistent quality. Producers aim to streamline quality control by using data-driven methods to assess wine attributes and predict quality ratings effectively. This project provides a scalable approach to classify wine quality based on physicochemical properties, offering winemakers insights into potential quality without extensive manual testing.

## Objective

The primary goal of this project is to classify red and white wines into quality categories using the K-Nearest Neighbors (KNN) algorithm. By accurately predicting wine quality, the project enables:
	•	Improved operational efficiency in winemaking.
	•	Enhanced product consistency, ensuring customer satisfaction.
	•	Cost-effective quality assessments.

## Dataset

The project uses the Wine Quality Dataset, which includes physicochemical properties of red and white wines, such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Alcohol content
- Quality ratings (target variable)  

## Dataset Details:
- Red wine: 1,599 samples, 12 attributes.
- White wine: 4,898 samples, 12 attributes.

## Methodology

1. Data Preprocessing:
- Combined datasets for red and white wines, adding a feature for wine type.
- Addressed missing values and normalized features for improved model performance.

2. Feature Engineering:
- Analyzed feature importance through correlation heatmaps.
- Retained key attributes contributing to quality prediction.

3. Model Selection:
- Applied the KNN algorithm, which is well-suited for non-linear relationships in data.
- Performed hyperparameter tuning to optimize the number of neighbors (k).

4. Model Evaluation:
- Split data into training (80%) and testing (20%) sets.
- Used accuracy, precision, recall, and F1-score to evaluate performance.

## Results
- Achieved an overall accuracy of X% on the test set.
- Precision and recall metrics demonstrate robust classification, particularly in identifying high-quality wines.
- Cross-validation confirmed model stability and generalizability.

## Key Insights
- Features like alcohol content, volatile acidity, and residual sugar strongly influence wine quality predictions.
- Red wines exhibit higher variation in quality compared to white wines, aligning with industry observations.

## Conclusion

This project showcases a practical application of machine learning in the wine industry. By leveraging KNN, winemakers can predict quality ratings efficiently, enabling proactive decision-making and reducing reliance on manual testing.

