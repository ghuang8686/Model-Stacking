This project is to explore and implement model stacking

1. The ground idea is to train Model1 on the dataset and get the prediction1
2. Add the prediction1 to the original dataset and then train Model2 on the added dataset
3. Check if the stacking models outperform than model2 alone. If yes, continue the step, otherwise stop


Notes: The models can be repeated in each iteration. This is kind of greedy algorithm idea.
If the training dataset is the same, overfitting might be a problem.
The candidates of the models are SVM, XGBoost, Ridge, and KNN.