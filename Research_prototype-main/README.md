# Machine Learning-Based Prediction of Municipal Solid Waste Generation in India

## Problem Statement
Municipal solid waste generation varies across regions. This project develops a machine learning prototype to estimate waste generation using available population and waste-management features.

## Objectives
- Prepare and validate the dataset.
- Train a regression model.
- Evaluate prediction performance using MAE, MSE, RMSE, and R².
- Provide a simple interface for predictions.
- Maintain version control and reproducible execution instructions.

## Technologies Used
Python, Pandas, Scikit-learn, Joblib, Git, and GitHub,Models

## Project Structure
- `data/`: input dataset
- `results/`: trained model and evaluation metrics
- `docs/`: technical documentation
  
## Installation
Install Python, then run:

```bash
pip install -r requirements.txt
```
Place `Combined_MSW_Dataset.csv` in the `data/` folder.

## Execution
Train the model:

```bash
python src/train_model.py
```

Start the interface:

```bash
streamlit run src/app.py
```

## Evaluation
The model is evaluated using MAE, MSE, RMSE, and R². Actual results are recorded in `results/model_performance.csv` after execution.

## Limitations
The prototype's accuracy depends on data quality, sample size, feature availability, and the geographic consistency of the observations. Predictions should not be treated as official measurements.

## Future Scope
- Use more complete and recent state-level data.
- Compare additional regression algorithms.
- Apply stronger validation suitable for small datasets.
- Improve input validation and the user interface.

## Reproducibility
The dataset, Python dependencies, fixed random seed, source code, and execution instructions should be maintained consistently. Users should record their Python and package versions when reporting results.

## References
- Scikit-learn documentation: https://scikit-learn.org/
- Streamlit documentation: https://docs.streamlit.io/
- Git documentation: https://git-scm.com/doc
