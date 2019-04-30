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
  * [Categorical variables]:https://render.githubusercontent.com/view/ipynb?commit=279362ce0052f4821c90745fa75021258d3fcfc4&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f76616d73686967756e6a693138332f446174612d536369656e63652d706f7274666f6c696f2f323739333632636530303532663438323163393037343566613735303231323538643366636663342f42616e6b2d4d61726b6574696e672d43616d706169676e2d416e616c797369732f42616e6b5f4d61726b6574696e675f50726f6a6563742e6970796e62&nwo=vamshigunji183%2FData-Science-portfolio&path=Bank-Marketing-Campaign-Analysis%2FBank_Marketing_Project.ipynb&repository_id=184240058&repository_type=Repository
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
|Logistic Regression|0.7900|Logistic Regression![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/ROC-LR.JPG "Correlation heatmap")|
|Decision Tree |0.7919|Decision Tree![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/ROC-DT.JPG "Decision Tree")|
|Random Forest|0.7979|Random Forest![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/ROC-RF.JPG "Random Forest")|
|Gradient Boosting|0.80065|Gradient Boosting![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/ROC-GB.JPG "Random Forest")|
|Ada Boost|0.8006|AdaBoost![alt text](https://github.com/vamshigunji183/Data-Science-portfolio/blob/master/Bank-Marketing-Campaign-Analysis/img/ROC-Ada.JPG "AdaBoost")|
