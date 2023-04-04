# House_Price_Prediction
Implemention of supervised statistical learning algorithms for predtion of house price. It is a regression task and for that I have used <b>Linear Regression</b> along with other algorithms to predict the housing price using the <b>ParisHousing.csv</b> dataset. <br><br>

## Dataset <br>
The "ParisHousing.csv" dataset is collected from Kaggle. Dataset is available here: <a href= "https://www.kaggle.com/datasets/mssmartypants/paris-housing-price-prediction" target="_blank">ParisHousing.csv</a>
## Linear Regression <br>
It is a supervised learning algorithm which uses statistical method to make predictions for continuous/real or numerical values. This algorithm is used for predicting sales, salary, weather, age, product price etc. More on Linear Regression <a href="https://www.javatpoint.com/linear-regression-in-machine-learning" target="_blank">JavaPoint</a>, <a href="https://www.geeksforgeeks.org/ml-linear-regression/" target="_blank">GeeksforGeeks</a>.
<br>
<b>Accuracy:</b> 99.99% (0.999999561980484)
<br>

## Polynomial Regression <br>
Basically a linear regression but models relationship between dependent and independent variables as n-th degree polynomial. <br>
<b>Accuracy:</b> For 2nd Degree: 0.9999995497190701, For 3rd Degree: 0.9999994956324605<br>

## Support Vector Regressor <br>
It is a support vector machine algorithm for regression tasks like this. <br>
<b>Accuracy:</b> 99.23% (0.9923266599052655) <br>

## Decision Tree Regressor <br>
Decision tree algorithm for regression tasks. <br>
<b>Accuracy:</b> 99.99% (0.9999962088679886) <br>

## Random Forest Regressor
Random Forest algorithm for regression analysis. <br>
<b>Accuracy:</b> 99.99% (0.9999981046318548) <br>

## Discussion
<b>Linear regression</b> has shown the best accuracy for this dataset. After the LR model, <b>Random Forest Regressor</b> has shown the highest accuracy among other algorithms. The RF is a powerful algorithm for performing both regression and classification problems. Still LR outperformed RF for this regression problem. Another observation is that, as the degree of of polynomial increases the accuracy decreases and it becomes more and more costly. <br>

<b>NB:</b> None of these models are optimized. I have used the defaults values that are preset. The <b>data_handle.ipynb</b> is for data preprocessing. I have used the well-known Pandas library for this task. Adter preprocessing I have spilted the dataset into a traing and testing file for making the job easy.