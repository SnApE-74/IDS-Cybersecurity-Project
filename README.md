# IDS-Cybersecurity-Project
IDS Cybersecurity Project

```markdown
# Behavioral-Based Intrusion Detection System for Financial Networks

This repository contains the implementation for a machine learning-based behavioral intrusion detection system (IDS) designed specifically for financial networks, focusing on ransomware threat mitigation.

## Research Paper

This codebase accompanies the research paper: "Mitigating Ransomware Threats Through Behavioral-Based Intrusion Detection Systems in Financial Networks"

## Features

- Machine Learning-based Behavioral Analysis
- Real-time Network Traffic Monitoring
- Ransomware Detection Framework
- Performance Analysis Tools
- Custom Feature Engineering Pipeline
- Model Evaluation Framework

## System Architecture

The system consists of three main components:
1. Data Collection and Preprocessing
2. Feature Engineering and Analysis
3. Detection and Alert System

## Requirements

- Python 3.8+
- scikit-learn
- pandas
- numpy
- xgboost
- tqdm
- matplotlib
- seaborn
- cuda libraries
- joblib
- keras
- warnings
- requests

## Dataset

This implementation uses the following publicly available datasets:
- CICIDS2017
- NSL-KDD

These datasets provide comprehensive network traffic patterns that simulate financial network environments.

## Usage
Use the Jupyter Notebook in Google Colab. And use a runtime with GPU availability. Enable High RAM options. Since the data is huge, you would need more RAM. Run the code after loading the dataset zips to file system. 

## Proposed Project Structure

```
├── src/
│   ├── preprocess.py
│   ├── feature_engineering.py
│   ├── train_models.py
│   ├── evaluate.py
│   └── utils.py
├── notebooks/
│   ├── EDA.ipynb
│   ├── Model_Analysis.ipynb
│   └── Performance_Evaluation.ipynb
├── tests/
│   └── test_modules.py
├── data/
│   ├── raw/
│   ├── processed/
│   └── results/
├── models/
│   └── saved_models/
├── docs/
│   └── technical_documentation.md
├── requirements.txt
└── README.md
```

## Current Project Structure

```
├── IDS_Cybersecurity_Project.ipynb
└── README.md
```

## Performance Metrics

Our implementation achieves:
- 97% Accuracy
- 95% Precision
- 98% Recall
- 96% F1-Score
- 2% False Positive Rate

## Contribution

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
Uppala Shanmukham Aneesh Babu
- Email: uppalashanmukhamaneeshbabu@gmail.com
- Institution: University of Maryland, Baltimore County

## Acknowledgments

- UMBC Department of Computer Science
- Professors for guidance and supervision
- CICIDS2017 and NSL-KDD dataset providers
