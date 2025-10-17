## Key Variables for Cancer Diagnosis Using PCA at Anderson Cancer Center
# Project Overview
Applied Principal Component Analysis (PCA) to reduce the complexity of the breast cancer dataset and pinpoint the features most influential in distinguishing benign from malignant tumors. 
This analysis aims to support data-driven decisions for securing donor funding and optimizing diagnostic processes at the center.
## Requirements
- Python 3.7 or higher
- Required libraries: numpy, pandas, matplotlib, seaborn, scikit-learn

## Installation
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
Files Included
pca_analysis.py: Main Python script implementing data loading, PCA, visualization, and classification
README.md: This instruction file
Output files (generated after running the script):
pca_analysis.png: Visualizations of PCA results
confusion_matrix.png: Model performance visualization
feature_importance_analysis.csv: Rankings of feature importance
pca_transformed_data.csv: PCA-transformed datase


## How to Run
Ensure all dependencies are installed
Execute the main script:
Run
python pca_analysis.py

# Implementation Steps
1. Data Loading and Exploration
Loads the breast cancer dataset from sklearn
Examines data structure, features, and class distribution
Provides basic statistics
2. Data Preprocessing
Standardizes features to ensure equal contribution to PCA
3. Principal Component Analysis
Reduces 30 features to 2 principal components
Analyzes explained variance and feature contributions
Identifies key features important for diagnosis
4. Visualization
Plots PCA results in 2D space
Shows explained variance and cumulative contribution
Ranks feature importance
5. Classification 

# Implements logistic regression on PCA-reduced data
Evaluates performance with confusion matrix and classification report
Key Findings
Important Variables
Features such as Worst Area, Mean Area, Worst Perimeter, Mean Concave Points, and Worst Concave Points are identified as crucial for distinguishing cancer types.

# Model Performance
Variance explained by 2 principal components: over 63%
Logistic regression accuracy on PCA data: approximately 95%

# Interpretation for Donor Funding
Focus Areas
Advanced imaging technologies capturing area and perimeter features
Morphological analysis tools for concave point detection
Automated systems leveraging key features for efficient diagnosis

Recommendations
Prioritize funding towards measurement technologies of key features
Develop simplified screening tools based on PCA insights
Use PCA-reduced datasets for efficient storage and processing
Technical Insights

Effectiveness of PCA
Successfully reduces high-dimensional data while preserving diagnostic information
Facilitates high-accuracy classification with fewer features

# Model Performance
The logistic regression model trained on PCA components demonstrates that essential diagnostic information is maintained even with reduced dimensionality, supporting efficient and accurate cancer diagnosis.

Author
Pascal Eliezer Okai
