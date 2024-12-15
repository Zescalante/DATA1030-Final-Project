# Star/Galaxy Classification in a Galaxy Cluster Field Using Machine Learning
Fall 2024 - DATA 1030 - Final Project

_Author: Zacharias Escalante_

This project entails analyzing a catalog of source information contained in the field of the Abell 3266 galaxy cluster field, created using data from the LoVoCCS survey and other external surveys. Exploratory data analysis is first carried out, followed by the engineering of new features, as well as data splitting and preprocessing in preparation for passing into a machine learing pipeline. Four ML models are trained: Logistic Regression with Elastic Net, SVC, K-Neighbors Classifier, and Random Forest Classifier. Model performance is then examined, followed by global and local feature importance.

## Contents

`data` folder

* `data_description.txt`: A brief summary of columns (features) in the dataset.

* Raw data file is too large for a repository, but can be shared upon reasonable request.

`figures` folder

* Figures generated for final report, midterm and final presentations. Supplementary figures also included.

`results` folder

* `knn_models_list.pkl`: .pkl file holding five sets of optimal parameters for KNeighborsClassifier model.
* `logreg_models_list.pkl`: .pkl file holding five sets of optimal parameters for LogisticRegression model.
* `rf_models_list.pkl`: .pkl file holding five sets of optimal parameters for RandomForest model.
* `svc_models_list.pkl`: .pkl file holding five sets of optimal parameters for SVC model.

`report` folder

* `DATA_1030_Midterm_Presentation.pdf`: Midterm presentation slides explaining origin of dataset, EDA splitting, and preprocessing.
* `DATA_1030_Final_Presentation.pdf`: Final presentation slides summarizing midterm presentation, models used, feature importance, and conclusions.

`src` folder

* `EDA_Prep_Models.ipynb`: Jupyter notebook containing initial data analysis (EDA, Splitting, Preprocessing) and model implementation (Logistic Regression Elastic Net, SVC, K-Neighbors Classifier, Random Forest Classifier)

* `Results.ipynb`: Jupyter notebook containing model evaluation, comparison, and feature importance examination.


## Installation

Python and package versions are contained within [data1030.yml](data1030.yml)


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.
