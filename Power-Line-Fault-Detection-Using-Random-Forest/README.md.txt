# Detection of Power Line Faults Using Random Forest Classifier

This project aims to detect faults in power lines based on voltage, current, and power values using a machine learning model (Random Forest Classifier).

## Project Overview
- **Technologies Used:** Python, scikit-learn, Pandas, Matplotlib, Seaborn
- **Dataset:** Smart grid.csv
- **Goal:** Classify whether a power line is operating normally or has a fault.

## How It Works
1. Load and preprocess the dataset.
2. Detect outliers (faults) based on standard deviation thresholds.
3. Train a Random Forest Classifier on the features (Voltage, Current, Power).
4. Evaluate the model's performance.
5. Visualize results using a confusion matrix.

## Setup Instructions
1. Clone the repository.
2. Install dependencies:
    ```
    pip install pandas scikit-learn matplotlib seaborn
    ```
3. Run the `main.py` script.

## Results
- Achieved an accuracy of around **100%** on the test data.

## Author
Niranjana S
