# Submission_BTC
1) The comparision.ipynb file compares different classification models such as Decision Tree, Random Forest, Naive Bayes, K-nearest, SVM, Bagging etc out of which we find that Random Forest gave the best results with 99% accuracy. Models with with 100% accuracy and too low accuracy generally are results of overfitting and underfitting respectively.
2) Model: Random Forest
   - Accuracy: 99.4652%
   - Precision: 98.3333%
   - Recall: 98.3333%
4) The final_algo.ipynb file creates an individual Random Forest Model and predicts the predicted signal for the whole dataset in order to plot the graph
5) The trained model if saved in the model_sig.sav file so it can be used in the following manner:
   
   import joblib\n
   model_sig = joblib.load('model_sig.sav')\n
   pred = model_sig.predict()
   
6) Graph.png is the output graph from the trained model
7) Deep Learning was not used as it was a case os classification with only 936 data points whereas deep learning requires a huge dataset.
8) Skills used in this project are:
   - Feature extraction
   - EDA
   - Outlier Detection(Not necessary in this scenario as outliers are crucial for our model)
   - Encoding
   - Scaling of Data (negative values present)
   - Model Creation
   - Plotting Graph
