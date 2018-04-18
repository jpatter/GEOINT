# Machine Learning with Spark ML

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/DSX.png" height="150"/>](http://datascience.ibm.com/) [<img src="https://github.com/jpatter/LMCO/blob/master/Lab-1/images/DB2Warehouse.png" height="150"/>](https://www.ibm.com/analytics/us/en/technology/cloud-data-services/dashdb/)

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/jupyter.png" height="150"/>](http://jupyter.org/index.html) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/spark.png" height="150"/>](http://spark.apache.org/)

In this lab, you will use SparkML in IBM Watson Studio to run generated travel data through a machine learning algorithm, automatically tune the algorithm, and load the data into a DB2 database.

## Objectives:
Upon completing the lab, you will know how to:


1. Connect to a database and read data used for machine learning.
2. Identify labels and transform data.
3. Conduct feature engineering for algorithm data.
4. Declare a machine learning model.
5. Setup the Pipeline for data transofms and training.
6. Train the data.
7. Show and evaluate machine learning results.
8. Automatically tune machine learning results.
9. Score data and load  into a new table in DB2.

## Instructions:

### Step 1.  Log into your [Watson Studio](http://datascience.ibm.com/) account, then click Projects in the top menubar and select the project you created at the beginning of this proof of technology.

### Step 2.  Click the `Add to project > Notebook` link in the top right of your project pane.
<img src="https://raw.githubusercontent.com/jpatter/GEOINT/master/Lab-1/images/add-notebook.png" height="150"/>

### Step 3.  Click the `From URL` tab under `Create Notebook`.

### Step 4.  Give the notebook a name in the `Name` field, for example `Machine learning with SparkML` and optionally you can give it a description.

### Step 5.  In the Notebook URL field, use `https://github.com/jpatter/GEOINT/blob/master/Lab-2/Categorizing-Vetted-Data.ipynb`

<img src="https://github.com/jpatter/GEOINT/blob/master/Lab-2/images/create-notebook-from-url.png"/>

### Step 6.  Ensure that there is a `Spark Service` selected, then click the `Create Notebook` button on the bottom right of the screen.

### Step 7.  Follow the instructions in the notebook.

<img src="https://raw.githubusercontent.com/jpatter/GEOINT/master/Lab-2/images/edit-notebook-begin.PNG"/>
