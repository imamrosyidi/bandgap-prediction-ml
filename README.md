# Bandgap Energy Prediction Using Machine Learning

## Overview
This project aims to predict bandgap energy using various machine learning models, including:
- Linear Regression
- Artificial Neural Network (ANN)
- Random Forest
- Extra Trees Regressor

The dataset contains thousands of inorganic material records with 286 features/properties. To enhance model performance, Recursive Feature Elimination (RFE) was applied, selecting the 65 most important features.

## Key Findings
After training and evaluating multiple models, Extra Trees Regressor proved to be the most accurate, achieving an R² score of 0.94.

## Features and Techniques Used
- **Dataset:** Inorganic materials dataset with 286 properties
- **Feature Selection:** Recursive Feature Elimination (RFE) to select 65 key features
- **Models:** Linear Regression, ANN, Extra Trees Regressor, Random Forest
- **Evaluation Metric:** R² score for model accuracy comparison

## Installation
```sh
# Clone the repository
git clone https://github.com/your-username/bandgap-prediction-ml.git
cd bandgap-prediction-ml

# Install dependencies
pip install -r requirements.txt
```

## Usage
```python
from model import predict_bandgap

# Example usage
features = [...]  # Provide input features
prediction = predict_bandgap(features)
print(f"Predicted Bandgap Energy: {prediction}")
```

## Results
| Model                 | R² Score |
|----------------------|---------|
| Linear Regression   | 0.82    |
| Artificial NN       | 0.87    |
| Random Forest    | 0.94 |
| **Extra Trees**       | **0.95** |

## Contributing
Contributions are welcome! Feel free to submit pull requests or open issues.

## License
This project is licensed under the MIT License.

