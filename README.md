# AI-Driven-Phishing-Analysis-with-Deep-Learning-and-API-Integration
The code provides an overview of an optimized phishing detection system built using deep learning models, hyperparameter tuning, cross-validation, and integration of URL analysis using an API. The code is designed to accurately classify emails as either spam or ham (non-spam) based on their content and incorporates additional features such as URL analysis and domain reputation checks.

## Model Building
The code employs a deep learning model with LSTM layers implemented using the Keras framework. Preprocessing steps for both text and numerical features are defined using CountVectorizer and StandardScaler, respectively. The preprocessing steps are combined using ColumnTransformer, and the deep learning model is wrapped using KerasClassifier. The pipeline encapsulates the preprocessing and modeling steps.

## Hyperparameter Tuning and Cross-Validation
To optimize the model's performance, hyperparameter tuning is performed using GridSearchCV. The code defines a parameter grid containing various combinations of hyperparameters, and GridSearchCV searches for the best combination based on accuracy. Cross-validation with a 3-fold split is used to evaluate the model's performance during hyperparameter tuning.

## Model Evaluation
The trained model is used to predict the labels for the test set. Evaluation metrics, including accuracy, precision, recall, and F1 score, are calculated to assess the model's performance in detecting phishing emails.
