# GreenHouseGasesEmissionPrediction
<h1>An AIML Project for Green House Gases Emission Prediction.</h1>

<p>The goal is to develop a regression model that can predict the Supply Chain Emission Factors with Margins based on descriptive and quality metrics (substance, unit, reliability, temporal/geographical/technological/data collection correlations, etc.).</p>

<b>Dataset:
<p>U.S. industries and commodities official dataset from data.gov.</p>

<b>Tools:
<p>#pip install scikit-learn as sklearn's original name is "scikit-learn"</p>
Python, Pandas, Scikit-learn, Matplotlib, Seaborn , numpy, joblib, openpyxl

<h5>Instruction;</h5>
-Source code and application is in Week 3
<p>-Extract models.zip in same folder as source code and app to use.</p><br>
The model is around 32mb. It is in compressed form(.zip) as GitHub doesnot allow files more than 25 mb.<br>
(Using file compression is quicker than LFS)
<br><br><br><br>
<h3>Some Steps involved in model creation:</h3>
<h6>Step 1: Imported required libraries</h6>
<h6>Step 2: Loaded the Dataset</h6>
<h6>Step 3: Completed Data Preprocessing (EDA+Cleaning+Encoding)</h6>
-Checked categorical variables
-Created  visualization of distribution, 
-Checked unique values and replaced empty values,
-Did univariate and multivariate analysis, and correlation heatmap
<h6>Step 4: Found top 10 emitters with their barplot</h6>
<h6>Step 5: Training</h6>
-Divided data into training and testing data(80/20)
<h6>Step 6: Prediction and Evaluation
-calculated MSE, RMSE and R2 score 

<h6>Step 7: Hyperparameter Tuning</h6>
-Did hyperparameter tuning for Random Forest Regressor using GridSearchCV
<h6>Step 8: Did comparative study among the models and based on the results selected the best model</h6>
<h6>Results:</h6>

