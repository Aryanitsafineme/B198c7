# B198c7
AI Applications for Digital Business
# Fake News Detection AI Project

## Project Overview
This project implements an AI-driven system to detect fake news, using Natural Language Processing (NLP) and machine learning techniques to accurately classify news articles.

## Data Description
- **True News Articles:** 21,417
- **Fake News Articles:** 23,481
- Columns: Title, Text, Subject, Date

## Implementation Details
- **Data Cleaning:** Regular expression-based cleaning
- **Feature Extraction:** TF-IDF vectorization
- **Machine Learning Models:** Logistic Regression (primary), Random Forest

## Evaluation Results
- Logistic Regression achieved ~99% accuracy, precision, recall, and F1-score.
- Cross-validation confirmed robustness.

## Repository Structure
- `/data`: Datasets
- `/models`: Saved models and vectorizers
- `/notebooks`: Jupyter notebook implementation

## How to Run
1. Clone repository.
2. Install dependencies (`pandas`, `scikit-learn`, `numpy`).
3. Run the notebook in Jupyter Lab.

## Future Improvements
- Integration of multimodal content
- Expansion of datasets
- Advanced NLP and deep learning models
