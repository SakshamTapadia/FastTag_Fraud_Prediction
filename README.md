# Fasttag Fraud Detection System

## Overview
This project implements a fraud detection system for fastag transactions using multiple machine learning classification techniques. The model identifies potentially fraudulent transactions by analyzing various patterns and features in the transaction data.

## Table of Contents
- [Project Structure](#project-structure)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)

## Project Structure
```
fasttag-fraud-detection/
│
├── main.py                 # Main script for model training and evaluation
├── data/                   # Data directory
│   └── fasttag_data.csv    # Dataset containing fasttag transaction information
```

## Features
- Multiple classification algorithms implemented and compared:
  - K-Nearest Neighbors (KNN)
  - Support Vector Classifier (SVC)
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Comprehensive Exploratory Data Analysis (EDA)
- Visual representation of fraud patterns using various graphs
- Model performance comparison

## Installation
To set up the project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/fasttag-fraud-detection.git
cd fasttag-fraud-detection

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage
To run the fraud detection system:

```bash
python main.py
```

Make sure the data directory containing the CSV file is in the same directory as the main.py file.

## Methodology
The project follows these key steps:

1. **Data Loading and Preprocessing**: Loading the fasttag transaction data from CSV files and preparing it for analysis.

2. **Exploratory Data Analysis (EDA)**: Analyzing various columns in the dataset to understand patterns and relationships, with special focus on identifying fraud indicators.

3. **Feature Engineering**: Creating relevant features that can help in detecting fraudulent transactions.

4. **Model Training**: Training multiple classification models:
   - K-Nearest Neighbors (KNN)
   - Support Vector Classifier (SVC)
   - Logistic Regression
   - Decision Tree
   - Random Forest

5. **Model Evaluation and Comparison**: Evaluating the performance of each model using appropriate metrics and comparing their effectiveness in detecting fraud.

## Results
The project includes a detailed comparison of the performance of different classification algorithms. The comparison metrics include accuracy, precision, recall, F1-score, and ROC-AUC.

Visual representations through various graphs provide insights into:
- Distribution of fraudulent vs. legitimate transactions
- Correlation between different features and fraud occurrence
- Performance comparison of different models

## Contributing
Contributions to improve the model or extend its functionality are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
