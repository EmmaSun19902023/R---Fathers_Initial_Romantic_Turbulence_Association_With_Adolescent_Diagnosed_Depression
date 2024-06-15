# (R) Fathers Initial Romantic Turbulence Association with Adolescent Diagnosed Depression

Developing GLM and Random Forest models to examine predictions based on the Princeton & Columbia FFCWS dataset.

The models are fitted after preprocessing in a loop of 5-fold stratified K-fold cross-validation. For each iteration, various test scores, including accuracy, F1 score, precision, and recall, are calculated. At the end of the iterations, the function returns a list of average test scores for these metrics.

The Random Forest model emerged as the best performer based on the combination of metrics. It achieved a mean F1 score of 93.98%, indicating a strong balance between precision and recall.

Required library versions:

python = 3.10.5

matplotlib = 3.5.2

pandas = 1.4.2

scikit-learn = 1.1.1

numpy = 1.22.4

xgboost = 1.5.1

shap = 0.40.0

jupyter_client = 7.3.1

jupyter_core = 4.10.0

jupyterlab = 3.4.2

jupyter_server = 1.17.0

jupytext = 1.13.8

rise = 5.7.1

plotly = 5.8.0

ipywidgets = 7.7.0







