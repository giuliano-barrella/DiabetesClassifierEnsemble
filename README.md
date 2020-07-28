# Diabetes Free

A machine learning ensemble model that predicts whether a patient has diabetes or not. Google Collaboratory was used to easily organize the code and data visulization. 

## Libraries used:

### Data preprocessing and visualization:

  - pandas, numpy, matplotlib and seaborn 
  
### Model developement:

  - sklearn and xgboost.

### The ensemble is composed of 3 models:

  - Deep Neural Network (MLPClassifier from sklearn.neural_network)
  - Random Forests (RandomForestClassifier from sklearn.ensemble)
  - XGBoost (XGBClassifier from xgboost)
  
Each model's hyperparameters are individually fine-tuned by performing GridSearchCV (from sklearn.model_selection) and then the ensemble is built with VotingClassifier from sklearn.ensemble.



There is a detailed description of the dataset and it's features in the Google Collaboratoy notebook.

## Acknowledgements:

  - Smith, J.W., Everhart, J.E., Dickson, W.C., Knowler, W.C., & Johannes, R.S. (1988). Using the ADAP learning algorithm to forecast the onset of diabetes mellitus.   In Proceedings of the Symposium on Computer Applications and Medical Care (pp. 261--265). IEEE Computer Society Press.

  - Tensorflow 2.0 Practical: https://www.udemy.com/course/tensorflow-2-practical

  - Kaggle: https://www.kaggle.com/kumargh/pimaindiansdiabetescsv
  
  
