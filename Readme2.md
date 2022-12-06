## **Group 2**

## _Contributors: Lief Herzfeld, Mai Yang, Randy Lam, Thomas Lenzmeier_

____________________________________________________

## Topic : Researching Lung Cancer Attributes

____________________________________________________

# **Overview**
- ### Our group used the *cancer patient data sets.csv* (the link is provided below), to perform a Research Track and as a result show all of the attributes that lead to lung cancer which we would nornamlly not think of. For example, in most cases the leading cause is notably known to be smoking. However, there are a few of other attributes that cause lung cancer according to our the data. 

- ### our group will present the results of our research analysis in a website, showing some data and visualization to support our findings.


Links: 

- Data: https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link

- ### GitHub Link: [lung-cancer-prediction]
(https://github.com/herzf012/lung-cancer-prediction)

____________________________________________________

# **Instructions**

## Part 1: Create Repository

 - ### Create a new repository project in GitHub called *lung-cancer-prediction*

 - ### Clone the new repository from GitHub to your computer's desktop then add the notebook files, Resource file, and README file. Remember to commit and push to GitHub regularly.


## Part 2: Preprocessing data in Pandas

 - ### Open a GitBash (Window) or Terminal (Mac) to the *lung-cancer-prediction* repo.

 - ### Change the Python environment to "PythonData38* then launch Jupyter Notebook by typing 'jupyter notebook' and press Enter.

 - ### Use Jupyter notebook to preprocess the *cancer patient data sets.csv* first. To preprocess the dataset, drop columns *index, and Patient Id* since it is not necessary to have these two columns in the sets.  


## Part 3: Using Classification Types in Supervised Machine Learning
 
 1. The K-nearest neighbor (KNN) 
   - #### Use only odd numbers for the k values. From sklearn.neighbors import KNeighborsClassifier. Preprocess the data by dropping the three columns, *index, Patient Id, and Level* and split the data to train and test sets, then fit it to the standardscaler, transform and loop through different k values to find which has the highest accuracy.

 - ### Plot the k values for train and test datasets to figure out where the best combination of scores occurs. this point provides the optimal k value for your model.
 
 2. The Support Vector Machine (SVM)
    - ### From sklearn import svm and fit the data to the model then import classification_report and print the report to show the optimal value. Firstly, preprocess the data by dropping the 3 columns then proceed with the SVM steps.
    - ### Create dataframes for the different levels, *High, Medium, Low* and plot it in a scatter plot graph.
    - ### Plot data to count for one of the features, *Wheezing*

 3. The Random Forest
   - ### This classification is used to calculate the most important features in *cancer patient data sets.csv*. 
       1. Import SelectFromModel to extract the best features from Random Forests model.
       2. Preprocess the data by dropping the 3 columns first then proceed with the steps for Random Forest.
       3. fit the logistic regression to the original dataset, and then print its score. Compare the two scores of the models.
 
 4. The ROC (Receiver Operating Characteristics) Curves
   - ### Use this classifier to combine *Low and Medium* in one and label to a binary value then compute and plot the ROC Curve (AUC) for AUC measures.
 
 
 ## Part 4: Unsupervised Machine Learning
  - ### Clustering Data - Import sklearn.cluster, then drop the three columns, *High, Medium, Low* then normalize the data. Plot the data in two of the features, *Coughing of Blood, and Shortness of Breath, Wheezing and Alcohol use* in a scatterplot.

  - ### Neural Network is used:

## Part 5: HTML Webpage
 1. Host on GitHub

 2. HTML Files
        1. Home Page (/templates/index.html)
        2. Methodology page (/templates/methodology.html)
        3. Analysis page (/templates/analysis.html)  
        4. Conclusion page (/templates/conclusion.html)

 3.  CSS Files (Cascading Style Sheets)
        1. /static/css/style.css


