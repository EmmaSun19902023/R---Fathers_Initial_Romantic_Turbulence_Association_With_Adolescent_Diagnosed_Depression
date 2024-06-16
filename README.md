# (R) Fathers Initial Romantic Turbulence Association with Adolescent Diagnosed Depression

Developing GLM and Random Forest models to examine predictions based on the Princeton & Columbia FFCWS dataset.

The models are fitted after preprocessing in a loop of 5-fold stratified K-fold cross-validation. For each iteration, various test scores, including accuracy, F1 score, precision, and recall, are calculated. At the end of the iterations, the function returns a list of average test scores for these metrics.

The Random Forest model emerged as the best performer based on the combination of metrics. It achieved a mean F1 score of 93.98%, indicating a strong balance between precision and recall.









