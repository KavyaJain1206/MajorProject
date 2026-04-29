# MajorProject

HR attrition analysis and classification project built around the `HR_comma_sep.csv` dataset.

## What the notebook does

- Loads the employee attrition dataset.
- Encodes categorical fields such as `salary` and `Department`.
- Runs exploratory data analysis with summary statistics, histograms, and a boxplot.
- Performs a Shapiro-Wilk normality test on numeric features.
- Builds a correlation matrix and heatmap.
- Trains a `RandomForestClassifier` to predict employee attrition (`left`).
- Saves the generated analysis and model outputs into the `results/` folder.

## Generated outputs

The notebook writes these files into `results/`:

- `summary_statistics.csv`
- `normality_test.csv`
- `correlation_matrix.csv`
- `model_results.txt`
- `histograms.png`
- `boxplot.png`
- `correlation_heatmap.png`

## Project structure

- `main.ipynb` - notebook with the full analysis and model workflow
- `HR_comma_sep.csv` - source dataset
- `results/` - saved outputs from the notebook

## How to run

1. Open `main.ipynb` in Jupyter or VS Code.
2. Run the notebook from top to bottom.
3. Review the saved files in `results/` for the analysis output and model evaluation.

## Notes

- The notebook uses `pandas`, `numpy`, `seaborn`, `matplotlib`, `scipy`, and `scikit-learn`.
- The correlation heatmap and model results are regenerated each time the notebook runs.
