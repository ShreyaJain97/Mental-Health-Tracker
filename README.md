# Mental-Health-Tracker

The detailed step-by-step process includes :
i)	Loading of the Data: The CSV data is loaded into jupyter for data extraction. 

ii)	Data Cleaning: This refers to identifying and correcting errors in the dataset that may be affecting a predictive model. This process makes statistical analysis and data visualization easier. 

iii)	Data encoding: The exhibition of an AI model relies upon the model and the hyperparameters and furthermore on how the client cycles and feeds various sorts of factors to the model. Since most models just acknowledge mathematical factors, preprocessing the all out factors turns into a significant advance. Thus, convert these downright factors to mathematical qualities to such an extent that the model can comprehend and extricate significant data.
iv)	Variability comparison between the variables: The covariance matrix is a square and symmetric matrix that describes the covariance between two or more random variables. This can be utilized to decorrelate factors or applied as a change to different factors. It is a key component utilized in the Principal Component Analysis information decrease technique, or PCA for short.

v)	Checking the data relationship : Through bar graphs relationships between different variables is checked. This helps in checking how many people need treatment.

vi)	Scaling and fitting: Feature scaling is the procedure of normalising the range of features in a dataset. The surveyed datasets often contain features that are varying in degrees of magnitude, units and range. Thus, in order for machine learning models to interpret the features on the same scale, researchers need to perform feature scaling.

vii)	Data Tuning : It is the procedure of increasing a model’s performance without overfitting or creating variance. This is done by selecting hyperparameters. These are the “dials” or “knobs” of the machine learning model.These are learned through training methods. Method for selecting hyperparameters include Grid search and Random Search.[11]

viii)	Model evaluation using Logistic Regression : The data will be trained using algorithm like logistic regression. It is a supervised classification algorithm which takes produces discrete values for a given set of features.[12]

ix)	Predicting with neural networks :A neural network is a collection of algorithms that helps to recognize underlying relationships in a set of data through a process that imitates the way the human brain operates. Information flows through a neural network by following 2 ways. Whether it's learning (being trained) or operating normally (after being trained), patterns of information are put into the network via the input units, which trigger the layers of hidden units, and these in turn reach at the output units.[14] For the following data, 

a) input functions will be created to supply data for training, evaluation and prediction.
b) Define the feature columns : A feature column is an object demonstrating how the model should use raw input data from the features dictionary. At the point when the user constructs an Estimator model, he passes it a rundown of highlight sections that depicts every one of the features he needs the model to utilize.
c) Instantiate the estimator : The problem is based on classification. We want to predict whether a patient needs treatment or not. We'll use tf.estimator.DNNClassifier for deep modelling which will perform multi-class classification.
d) Train the model
e) Evaluate : Now that the model has been trained, we obtain some statistics on its performance through which we evaluate the accuracy of the trained model on the test data.
f)  Making predictions from the trained model : We now have a trained model that generates good evaluation results. We can now use the trained model to predict whether a patient needs to be treated or not.

x)	Creating predictions on the test set

However, this process require significant effort for data collection, and for task- and domain-specific feature engineering.

