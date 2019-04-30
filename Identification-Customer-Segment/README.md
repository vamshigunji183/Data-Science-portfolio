
# Unsupervised Learning
## Project: Identify customers segments 

## Introduction
In this project, you will apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data that you will use has been provided by our partners at Bertelsmann Arvato Analytics, and represents a real-life data science task.

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### To-Do tasks
Step-1: Load data 
#### Observations 
`From the very first sight it appears that some features contains plenty of unknown or missing values. For example AGER_TYP has at least 75% of lines filled with '-1' which means 75% of data missing/unknown. Will prepare a dataset where both naturally missing and unknown/missing values will be marked as NaNs. Based on that will take a decision for dropping certain features. `

Step-2: Pre-processing
   * Assessing missing values
       - Convert Missing Value Codes to NaN
       - Assess Missing Data in Each Column
   * Select and Re-Encode Features
        * Re-Encode Categorical Features
        *  Engineer Mixed-Type Features
        
Step-3: Feature Transformation
   * Apply feature scaling
   * Perform Dimensionality Reduction - PCA
   * Interpret Principal Components
Step-4: Clustering
   * Apply Clustering to General Population
   * Apply All Steps to the Customer Data
   * Compare Customer Data to Demographics Data

     



### Code

Solution is provided in the `Identify_Customer_Segments.ipynb` notebook file. 

### Data

The actual data was removed due to terms and conditions of AZ Direct GmbH which prohibits of using data in any other content rather than Udacity course. 

### Results 

Within the project both general population (Germany) and customers population were compared. Segments were identified that could be target for future marketing campaigns or to be considered outside of company interests. Typical portrait of a customer for different segments was described.  

`Now let's check median values of below features which will characterize cluster 4.`

`What can we say about people that typically outside of target group:MOBI_REGIO (movement in the region) low movement in the region. `

`KBA05_ANTG1 (Number of 1-2 family houses in the microcell) - average share of 1-2 family houses in the microcell.`

`FINANZ_MINIMALIST (MINIMALIST: low financial interest) - is high. `

`HH_EINKOMMEN_SCORE (Estimated household net income) - average income.` 

`PLZ8_ANTG3 (Number of 6-10 family houses in the PLZ8 region) - lower share of 6-10 family houses in the PLZ8 region.`

`CAMEO_INTL_2015_WL (Wealth of household) - Prosperous households.`

`FINANZ_SPARER (financial typology - money saver) - low.`

`FINANZ_VORSORGER (financial typology - be prepared) - high, so mostly financial typology is "be prepared" which is above money saver but less than investor. `

 `SEMIO_REL (religious) - very low affinity.`

`ALTERSKATEGORIE_GROB (Estimated age) - 30 - 45 years old`

`ANREDE_KZ (Gender) - Female`

`SEMIO_KAEM (personal typology -combative attitude) - average SEMIO_DOM (personal typology -dominant-minded) - average SEMIO_VERT (personal typology - dreamful)- average SEMIO_SOZ (personal typology - socially-minded) - average SEMIO_FAM (personal typology- family-minded)- low. `

### Summary
Typical person outside of target group is a woman, mid age (30-45) with average income, low affinity to religious, she is not money saver, living in prosperous household, in the microcell with average 1-2 families, in the region of low movement. Personal typology. She can be in average combatative/dominant, dremful, socially-minded with lower probability for family-minded. We can say this is a person modern, active, which can stands for his rights and needs.
