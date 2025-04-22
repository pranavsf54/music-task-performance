# Effect of Music on Task Performance

This project investigates whether listening to background music improves cognitive task performance, specifically in memory-related tasks. It also explores the predictive modeling of improvement using logistic regression.

## Overview

- **Dataset**: Public dataset from [Zenodo](https://zenodo.org/) on cognitive performance under music and silence conditions.
- **Focus**: Memory performance (based on `raw-data-memory.xlsx`)
- **Hypothesis**: Listening to music improves memory performance compared to silence.
- **Outcome**: A small but statistically significant improvement was found.

## Features

- Descriptive analytics (mean, standard deviation, visualizations)
- Statistical testing using paired t-test
- Feature engineering (score difference, improvement label)
- Predictive modeling using logistic regression
- ROC curve analysis with AUC evaluation

## Technologies Used

- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn
- scipy

## Key Results

- **Mean Score (Music)**: 23.60
- **Mean Score (Silence)**: 22.51
- **T-test p-value**: 0.047 (Statistically significant)
- **Logistic Regression Accuracy**: \~79%
- **AUC (ROC Curve)**: 0.72

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/pranavsf54/music-task-performance.git
   cd music-task-performance
   ```

2. Install required packages:

   ```bash
   pip install pandas matplotlib seaborn scikit-learn scipy
   ```

3. Run the notebook:

   ```bash
   jupyter notebook project.ipynb
   ```

OR: Add `raw-data-memory.xlsx` to Google Colab and run `project.ipynb`

## Acknowledgements

- Dataset from: *Background Music and Cognitive Performance* on [Zenodo](https://zenodo.org/)
- Inspired by research in cognitive psychology and environmental factors in memory performance.

