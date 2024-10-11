# Urban Traffic Safety Technology

## Overview
This project analyzes accident data in the United States to predict accident severity based on weather and environmental features. It utilizes machine learning models such as Linear Regression, Random Forest Regressor, Logistic Regression, and Random Forest Classifier to explore regression and classification tasks.

## Dataset
The dataset used in this project is from the [US Accidents dataset](https://www.kaggle.com/sobhanmoosavi/us-accidents). Due to its large size, it is not uploaded to this repository. You can download the dataset from the provided link and place it in the root directory of the project.

- **File name:** `US_Accidents_March23.csv`
- **Features used:**
  - Temperature (°F)
  - Humidity (%)
  - Visibility (miles)
  - Wind Speed (mph)
  - Precipitation (inches)
- **Target Variable:** `Severity`

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/username/urban-traffic-safety-technology.git

## Install dependencies
pip install -r requirements.txt

## Usage
Run the analysis script:
python analysis.py

## Machine Learning Models Used

### Regression Models:

- **Linear Regression**: Predicts accident severity based on weather and environmental conditions.
- **Random Forest Regressor**: An ensemble model that improves regression predictions using decision trees.

### Classification Models:

- **Logistic Regression**: Classifies accident severity into different levels (e.g., minor, severe).
- **Random Forest Classifier**: Another ensemble model for classifying severity with higher accuracy.

## Results

### Regression Results:

|Model|MSE|RMSE|R² Score|
|---|---|---|---|
|Linear Regression|0.147364|0.383880|0.001891|
|Random Forest Regressor|0.146992|0.383395|0.004412|

### Classification Results:

|Model|Accuracy|Precision|Recall|F1 Score|
|---|---|---|---|---|
|Logistic Regression|94.19%|89.06%|94.19%|91.37%|
|Random Forest Classifier|94.12%|91.47%|94.12%|91.91%|

## Visualizations

### Feature Importance from Random Forest:
![a760c0f4-e845-4c85-b772-716e439ed503](https://github.com/user-attachments/assets/0ab3af3d-623f-4a3b-a8ba-f4e73ef5033b)

### Severity Distribution in Top 10 States and Cities:
![223538e2-ee3c-4135-9914-5efe770db2cc](https://github.com/user-attachments/assets/7f9946c8-e4b3-44ac-9302-dcf71e572127)

### Actual vs Predicted Severity (Regression):
![847d400c-7a5f-420f-9223-9706709c2371](https://github.com/user-attachments/assets/995f684a-24ca-4199-af60-20ef356cf795)

### Confusion Matrix for Classification:
![80c72807-6e8e-43f1-80a6-05c8d49b0a91](https://github.com/user-attachments/assets/1a896a11-b347-4cd4-b780-68727910a85b)

## Conclusion
This project demonstrates how machine learning can be used to predict accident severity based on weather conditions. Both regression and classification approaches were evaluated, with Random Forest models performing better in both tasks. The visualizations provide valuable insights into the distribution of accidents and the impact of different environmental factors.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
This `README.md` is now correctly formatted using Markdown syntax.
