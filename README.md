# Machine Learning Classification Project

This repository contains a Machine Learning project focused on classification tasks, implemented in Python using popular libraries such as scikit-learn, XGBoost, and visualization tools like matplotlib and seaborn. The project is structured in a Jupyter notebook to facilitate code reproduction and understanding.

## Contents

### Main Files
- **classification.ipynb**: Contains the code for loading, exploring, and modeling the data.
- **math_e.csv**: Dataset used to train and evaluate the models.
- **best_eval_results.pkl**, **best_params.pkl**, **best_xgb_model.json**: Trained models, optimized parameters, and stored results for reuse.

## Features

1. **Data Exploration**:
   - Loading and visualizing the data from `math_e.csv`.
   - Descriptive statistics and variable distributions.

2. **Modeling**:
   - Use of various classification models but focused in XGBoost
   - Evaluation metrics such as:
     - Accuracy
     - Precision
     - Recall
     - F1-Score
     - AUC-ROC

3. **Hyperparameters and Optimization**:
   - Grid Search to find the best hyperparameters.
   - Saving results for future analysis.

4. **Visualization**:
   - Confusion Matrix and its visual representation.
   - ROC Curves and variable distributions.

## Technologies Used

- **Language**: Python
- **Libraries**:
  - pandas, numpy for data manipulation
  - scikit-learn, XGBoost for modeling and metrics
  - matplotlib, seaborn, plotly for visualization


## License

This project is licensed under the [MIT License](LICENSE), allowing wide use, modification, and distribution.

---

Feel free to contribute with improvements or report issues through issues or pull requests!
