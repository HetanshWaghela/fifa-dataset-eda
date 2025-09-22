# FIFA Player Performance — EDA & Modeling

**One-line:** Exploratory Data Analysis and initial modeling for predicting FIFA player `Overall` rating.

## Dataset
`fifa_merged_cleaned.csv` as the primary dataset.

**Target variable:** `Overall` (player overall rating)

**Key features used (detected in notebook):**
- `Technical_Score`
- `Physical_Score`
- `Attacking_Score`
- `Defensive_Score`
- `Age_Group`
- plus other numeric features selected dynamically in the notebook.

## What the notebook contains
The notebook follows a standard EDA → preprocessing → modeling flow and includes:
- Data loading and initial inspection.
- Missing value checks.
- Visualizations: seaborn/matplotlib plots, boxplots, heatmap (correlation).
- Encoding: `LabelEncoder` for categorical columns.
- Scaling: `StandardScaler`.
- Modeling experiments: `LinearRegression`, `RandomForest`, `GridSearchCV`, `cross_val_score`.
- Train/test split via `train_test_split`.

Notebook structure:
- `# Exploratory Data Analysis for Player Performance Prediction`
- `## Advanced Player Performance Prediction Model`
