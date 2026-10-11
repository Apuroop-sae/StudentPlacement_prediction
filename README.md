# Student Placement Prediction using KNN

A beginner machine learning project that predicts student placement
status using the **K-Nearest Neighbors (KNN)** classification algorithm.

## Dataset

-   `placement.csv` --- student academic, skills, and activity-related
    features.
-   Target column: `placement_status` (`Placed` / `Not Placed`).

## Workflow

-   Exploratory data analysis (EDA)
-   Categorical feature encoding
-   Train-test split (70/30)
-   Feature scaling using `StandardScaler`
-   KNN model training (`k=5`) (*you can tune as you like for better prediction score*)
-   Evaluation using accuracy, confusion matrix, and classification
    report

## Result

-   Test accuracy: **86.13%** (as reported by the notebook)

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Jupyter
Notebook.

## Run

Install dependencies:

``` bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

Open `KNN.ipynb` in Jupyter Notebook and run the cells. Ensure
`placement.csv` is in the file path used by the notebook.
