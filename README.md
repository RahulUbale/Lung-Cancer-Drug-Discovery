
# Data Mining Final Project :- Lung-Cancer-Drug-Discovery




## Abstract:
Lung cancer is the most common cause of cancer related deaths world-wide. Small cell lung cancer
(SCLC), the most common type of lung cancer, have both reacted well to chemo-, radiation-, and
adjuvant treatments. Surgery to remove the tumor also appeared to be a viable treatment option.
However, these treatments had unfavorable side effects, necessitating the development of alternate
lung cancer medications such as novel drugs. Activation of Epidermal Growth Factor Receptor
(EGFR) protein is a key reason for lung cancer.
Our project aims to compare various regression algorithms such as Random Forest Regressor,
Ada-boost Regressor and Bagging Regressor to predict the efficacy of a drug in inhibiting the
growth of cancer cells.



## Methodology:

The methodology for this project was divided into four parts: -
* 2.1. Data Collection 
* 2.2. Exploratory Data Analysis 
* 2.3. Molecular Fingerprint Calculation
* 2.4. Feature Engineering and Model Building


## Results
We can also observe the performance of these different regressor models by analyzing the graphs
that we have plotted for experimental vs predicted pIC50 values. The regression line in graph of
Random Forest Regressor is almost passing through origin which implies that there is very small
difference in Experimental and Predicted Values. Hence Random Forest Regressor is performing
best in these three models. If we observe the graph of Bagging regressor we can see that the
regression line is bit far from the origin hence there will be some difference in Experimental and
Predicted Values. In the graph of AdaBoost regressor the regression line is very far from origin
hence there will be significant difference in predicted and experimental values, hence the Error
values (RMSE and MSE) for AdaBoost regressor are highest.
Since our Target variable(pIC50) values ranges from 0-10, the Root Mean Squared Error and
Mean Absolute Error values i.e.,0.634 and 0.409 respectively are acceptable. Hence, we can
conclude that, using Random Forest Regressor Model we predicted the pIC50 values that are
very close to the experimental pIC50 values.



