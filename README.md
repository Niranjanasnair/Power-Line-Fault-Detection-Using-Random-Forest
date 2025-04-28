# Detection of Power Line Faults Using Random Forest Classifier

This project uses machine learning techniques to detect faults in power lines based on voltage, current, and power data. The goal is to identify whether a power line is operating normally or has encountered a fault, using a Random Forest Classifier model.

# Project Significance
This project demonstrates how machine learning can be used in real-world applications like power grid monitoring. Detecting faults in power lines in real-time can significantly reduce maintenance costs, prevent power outages, and ensure the safety of the electrical grid system.

## Project Overview

- **Technologies Used:**  
  Python, scikit-learn, Pandas, Matplotlib, Seaborn

- **Dataset:**  
  `Smart grid.csv` — A dataset containing voltage, current, and power readings from power lines. The data is used to identify any abnormal readings or faults.

- **Goal:**  
  The objective of this project is to use machine learning to classify whether a power line is functioning normally or experiencing a fault based on the sensor data.

## How the Model Works

1. **Data Preprocessing:**  
   - The dataset is loaded and cleaned using Python's Pandas library.
   - Outliers (potential faults) are detected using a standard deviation-based method on key features: Voltage, Current, and Power.

2. **Fault Detection:**  
   - A new column, `Fault`, is created to represent whether the power line is faulty or not, based on the threshold of standard deviation for each feature.

3. **Model Training:**  
   - A **Random Forest Classifier** is used for classification. It is trained using the features: Voltage, Current, and Power, and tested on unseen data.

4. **Model Evaluation:**  
   - The model's performance is evaluated based on accuracy, confusion matrix, and classification report.
   - Visualizations such as confusion matrix are plotted to understand the model's performance better.

## Setup Instructions

1. **Clone the Repository:**  
   Clone this repository to your local machine using the following command:
   ```bash
   git clone https://github.com/Niranjanasnair/Power-Line-Fault-Detection-Using-Random-Forest.git
