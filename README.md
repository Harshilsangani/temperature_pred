# Temperature Prediction Project

## Overview
This project predicts temperature based on various environmental and atmospheric features. The dataset includes air quality indicators such as SO₂, O₃, and CO concentrations, which are analyzed to find patterns and make predictions.

## Features & Methodology
- **Exploratory Data Analysis (EDA)**:
  - Checked for missing values and handled them using mean imputation.
  - Converted necessary columns to numeric format.
  - Visualized data to identify patterns.

- **Model Training**:
  - Loaded and preprocessed datasets (`train.csv` and `test.csv`).
  - Applied machine learning techniques to predict temperature.
  - Evaluated model performance.

- **Predictions & Submission**:
  - Generated predictions using the trained model.
  - Created `submission.csv` for evaluation.

## Files in the Repository
- `Temperature_2_.ipynb` - Jupyter Notebook containing the full workflow.
- `train.csv` - Training dataset.
- `test.csv` - Test dataset.
- `sample_submission.csv` - Example format for submission.
- `submission.csv` - Generated predictions.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Harshilsangani/temperature_pred
   cd temperature_pred
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook Temperature_2_.ipynb
   ```

## Dependencies
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGboost

## Contributing
Feel free to submit issues or contribute improvements via pull requests!

## License
This project is open-source under the MIT License.

