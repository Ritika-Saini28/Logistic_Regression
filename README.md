<h3 align="center">Logistic Regression</h3>
<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">
<h4>Overview</h4>
This project uses logistic regression to predict whether an object detected by sonar signals represents a rock or a mine. <br>
<h4>Dataset</h4>
The dataset consists of sonar signals reflected from metal cylinders (mines) and rocks. Each sample is a set of 60 features representing the energy within a particular frequency band. The task is to classify each object as either a "rock" (R) or a "mine" (M) based on these features.
<ul><li><b>Attributes:</b> 60 numeric attributes (real-valued)</li></li>
<li><b>Class:</b> Target variable (R for rock, M for mine)</li></ul>
<h4>Files</h4>
<ul><li><b>sonar_dataset.csv:</b>CSV file containing the dataset.</li>
<li><b>Rock_vs_Mine_Prediction.ipynb:</b>Jupyter notebook containing the logistic regression model implementation and evaluation.</li></ul>
<h4>Requirements</h4>
<ul><li>Python 3.x</li>
<li>Jupyter Notebook</li>
<li>Required Libraries:</li>
<ul><li>pandas</li>
<li>numpy</li>
<li>scikit-learn</li>
<li>matplotlib</li></ul></ul>
<h4>Result</h4>
<ul><li>The logistic regression model achieves an accuracy of 76.8% on the test set.</li>
<li>The logistic regression model achieves an accuracy of 83.6% on the train set.</li>
<li>Confusion matrix and classification report are provided to evaluate model performance.</li></ul>
