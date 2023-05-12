# BANKRUPTCY IN POLAND

Explore data collected by a team of Polish economists studying bankruptcy. Then building random forest and gradient boosting models to predict whether a company will go bankrupt. 

* Data Source : https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data

* the data contains financial rates from 1st year of the forecasting period and corresponding class label that indicates bankruptcy status after 5 years. The data contains 7027 instances (financial statements), 271 represents bankrupted companies, 6756 firms that did not bankrupt in the forecasting period.

### Attribute Information:
[Data information](https://github.com/iAbdellrahmann/bankruptcy-gradient-boosting-prediction-model/blob/codespace-iabdellrahmann-turbo-orbit-4gpqjjgprgj2qwjj/notebooks/data_dictionary.ipynb)

### For many Taske I've used Feature : X27 -> profit on operating activities / financial expenses

### Resampling Dataset
* the data was imbalanced
![image](https://github.com/iAbdellrahmann/bankruptcy-gradient-boosting-prediction-model/assets/39285876/e97a5935-30e3-4fee-a7c4-e731166283c2)
* applied a Over sample technique to overcome this problem.

### Train and fit Decicion Tree Classifier, Random Forest Model, Gradient Boosting Model
1- [Decicion Tree Classifier](https://github.com/iAbdellrahmann/bankruptcy-gradient-boosting-prediction-model/blob/codespace-iabdellrahmann-turbo-orbit-4gpqjjgprgj2qwjj/notebooks/data_insights_decision_tree_model.ipynb)
2- [Random Forest Model](https://github.com/iAbdellrahmann/bankruptcy-gradient-boosting-prediction-model/blob/codespace-iabdellrahmann-turbo-orbit-4gpqjjgprgj2qwjj/notebooks/random_forest.ipynb)
3- [Gradient Boosting Model](https://github.com/iAbdellrahmann/bankruptcy-gradient-boosting-prediction-model/blob/codespace-iabdellrahmann-turbo-orbit-4gpqjjgprgj2qwjj/notebooks/gradient_boosting.ipynb)

