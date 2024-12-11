Open the project folder in Visual Studio Code.
Load the audio_feature.ipynb notebook.
Install the Jupyter extension for seamless execution of notebook cells.
Load the data.
Extract features from the data.
Divide the audio_features_with_labels.csv file into:
training_data.csv (training set).
testing_data.csv (testing set).
Apply PCA (Principal Component Analysis) to the training and testing datasets.
Save the PCA-transformed data as:
train_pca.csv for training data.
test_pca.csv for testing data.
Execute the cell to train an SVM (Support Vector Machine) model using the PCA-transformed training data.
Perform hyperparameter tuning (e.g., grid search or random search) to optimize the SVM.
Use cross-validation to validate the model's performance.
Use the trained SVM model to make predictions on the PCA-transformed testing data.
Save the predictions in a file named predict_svm.csv.
Evaluate the model's performance by calculating:
Accuracy.
Precision, recall, and F1-score (if needed).
Confusion matrix.
