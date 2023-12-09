
# Water Potability Prediction

## Overview

Ensuring access to safe drinking water is crucial for public health. This project leverages machine learning to predict the potability of water, providing a tool to identify whether water is safe for human consumption. The outcome contributes to effective water management and supports health policies at various levels.

## Dataset

The [dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability) comprises water quality metrics for 3276 different water bodies. Key features include:

1. **pH value:** Indicator of water acidity or alkalinity (WHO recommended range: 6.5–8.5).
2. **Hardness:** Caused by calcium and magnesium salts, affecting soap precipitation.
3. **Solids (TDS):** Indicates mineralization; desirable limit for drinking is 500 mg/l.
4. **Chloramines:** Common disinfectants in public water; safe up to 4 ppm.
5. **Sulfate:** Naturally occurring substances; concentration in freshwater ranges from 3 to 30 mg/L.
6. **Conductivity:** Measures water's ability to conduct electricity; WHO standard is ≤400 μS/cm.
7. **Organic Carbon:** Total amount of carbon in organic compounds; critical for water treatment.
8. **Trihalomethanes:** Chemicals found in chlorine-treated water; safe levels up to 80 ppm.
9. **Turbidity:** Indicates solid matter in water; WHO recommends ≤5.00 NTU.
10. **Potability:** Binary indicator (1: Potable, 0: Not Potable).

## Problem Statement

The task is to predict water potability, addressing the challenge of class imbalance (61% not potable, 39% potable). The objective is to deploy a reliable model that aids in prioritizing water safety interventions.

## Model Accuracies

- K-Nearest Neighbors (KNN): _accuracy_
- Logistic Regression: _accuracy_
- XGBoost: _accuracy_
- Random Forest: _~80% accuracy_
- Support Vector Machine (SVM): _~70% accuracy_
- Naive Bayes: _~63% accuracy_
- Neural Network (NN): _accuracy_

## Impact

Identifying potable water sources contributes to:

- **Public Health:** Reducing waterborne diseases.
- **Economic Benefits:** Efficient use of resources in water treatment.
- **Policy Implementation:** Informed decision-making for water management.

## Project Structure

- `data/`: Contains the dataset file (water_potability.csv).
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model evaluation.
- `src/`: Source code for data preprocessing and model training.
- `models/`: Saved model files.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/TonyLei43/Water-Potability-prediction.git
   cd water-potability-prediction
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks or execute the Python scripts in the `src/` directory.

## Results

The Random Forest model emerged as the most effective, achieving an accuracy of approximately 80%. Further details and evaluation metrics are available in the respective notebooks.

## Contributing

Contributions to enhance the model or address specific water quality challenges are welcome. Follow the standard GitHub flow: Fork, Branch, Commit, and Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to reach out for questions or collaborations!
