# Bank-Marketing-Campaign-Analysis

- Analyzed the prior marketing campaigns of a Portuguese Bank using various ML techniques like Logistic Regression, Random Forests,Decision Trees, Gradient Boosting and AdaBoost and predicted if the user will buy the Bank’s term deposit or not

- Recommended, the marketing team, ways to better target customers using feature importance maps and business intuition


Instructions to run the code:
1. Make sure the data file ("bank-additional-full.csv") is in the same directory as the ipython notebook or
edit the ipython notebook accordingly.
2. Make sure to run the notebook in python 3 environment.
Make sure all the dependencies used in the notebook are installed in the local machine.
3. Run the code sequentially as given in the notebook.
4. Notebook is commented adequately to give the rational, inferences of the executed code.

### Overview
* Load data
* Exploratory Data Analysis
  * Categorical variables
      Numbers of customers...
      * JOBS![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/job.JPG "Jobs")
      * Martial![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/marital.JPG "Martial")
      * Education![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/education.JPG "Education")
      * Default![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/default.JPG "Default")
      * Loan![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/loan.JPG "Loan")
      * Contact![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/contact.JPG "Contact")
      * Month![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/month.JPG "Month")
      * Day of week![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/day.JPG "Day of week")
      * Out come![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/outcome.JPG "Out Come")
      * Target label![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/Y.JPG "Target label")

  ### Normalize the Data
  ### Accessing the missing values
  ###### Correlation
Correlation heatmap![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/correlation-heatmap.JPG "Correlation heatmap")


### Train and validate

|Model| AUC Score| ROC Curve|
|------------|------------|----------|
|Logistic Regression|0.7900|Logistic Regression![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/ROC-LR.JPG "Correlation heatmap")|
|Decision Tree |0.7919|Decision Tree![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/ROC-DT.JPG "Decision Tree")|
|Random Forest|0.7979|Random Forest![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/ROC-RF.JPG "Random Forest")|
|Gradient Boosting|0.80065|Gradient Boosting![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/ROC-GB.JPG "Random Forest")|
|Ada Boost|0.8006|AdaBoost![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/ROC-Ada.JPG "AdaBoost")|
