# IBM Proof of Technology - Watson Studio

## Description:

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/DSX.png" height="150"/>](http://datascience.ibm.com/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/bluemix-logo.png" height="150"/>](https://www.ibm.com/cloud-computing/bluemix/solutions) [<img src="https://github.com/jpatter/LMCO/blob/master/Lab-1/images/DB2Warehouse.png" height="150"/>](https://www.ibm.com/analytics/us/en/technology/cloud-data-services/dashdb/)

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/jupyter.png" height="150"/>](http://jupyter.org/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/spark.png" height="150"/>](http://spark.apache.org/)

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/RStudio2.png"/>](https://www.rstudio.com/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/shiny.png"/>](https://shiny.rstudio.com/)

Use IBM’s Watson Studio and IBM Cloud services to create a working cloud-based application from start to finish.  Participants will be led through a series of three labs that build upon one another so it is important that they are completed in order. A fourth lab will explore additional features of Watson Studio. 

1. [Lab-1](Lab-1) - The first lab will begin with loading raw delimited data into DB2 Warehouse for Cloud and interacting with that data from a Jupyter notebook in Watson Studio with python.

1. [Lab-2](Lab-2) - The second lab will leverage Spark machine learning (SparkML) on the loaded data to create categorical predictions using pyspark and a supervised learning model and store the results back to the database.

1. [Lab-3](Lab-3) - The third lab will guide participants in creating an R notebook and Shiny UI in Watson Studio using RStudio.

1. [Lab-4](Lab-4) - Time permitting there will be two labs to choose from for Lab 4. The first one features Watson Machine Learning, a point and click capability to build a machine learning model and deploy it. The second lab features SPSS - a visual programming tool to create a machine learning pipeline. 

## Instructions:

### Step 1. Sign up for IBM Watson Studio.   We recommend using the Firefox browser.

__NOTE__: If you already have a Watson Studio account, please skip to __Step 2__.

#### Create an account.

1.  Go to [http://datascience.ibm.com/](http://datascience.ibm.com/)

2.  Click the signup button on the top right

> <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Sign%20Up%20Image.png" width="624" height="300">

3. Enter your email, click to accept the terms, and click Next. Note: If you already have an IBM id you can click Sign in with your IBM id -- if you don't have a Watson Studio account one will be created for you.

> <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Try%20Watson%20Data%20Platform.png" width="624" height="300">

4. On the next page, fill in the corresponding fields and click <b>Create Account</b>

 >  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Try%20IBM%20Cloud.png" width="624" height="300">

5. You will see the following screen. You need to go to your e-mail account to complete the sign up process.

 > <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Thanks.png" width="624" height="300"/>

6. In your e-mail inbox, there should be a message from IBM Cloud.

 >  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Gmail.png"/>

7. Open the e-mail and click on <b>Confirm Account</b>.

 >  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Gmail%202.png"/>

8. Go back to the Watson Studio session, and enter your Watson Studio user id (e-mail account) and click <b>Continue</b>. Or, skip to step 10 if the system automatically logs you in. 

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Sign%20into%20IBM.png"/>

9.  Enter your password and click <b>Sign in</b>.

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Enter%20Password.png"/>

10. Select the defaults which should be IBM Cloud Account (IBM), organization (your e-mail), and space (dev) and click <b>Continue</b>.

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Select%20Organization.png"/>

11. It may take several minutes to set up the account. You will see several screens pop-up (e.g. Registering User, Initializing Environment). Wait until you see the following screen and then click on <b>Get Started</b>.

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Done.png"/>


 > You are now in the Watson Studio landing page. From here you can explore any of the tutorials, videos, sample notebooks, tutorials or articles in the community.

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Welcome.png"/>

### Step 2. Create a project

1. Click on <b>Projects > View All Projects</b> to see a list of your projects. 

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/View%20All%20Projects.png"/>

2. If you just signed up, you will not have any projects. Click on the <b>New Project</b> button. 

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/ClickNewProject.png"/>

3. Type a Name for your project. For instance, "Watson Studio Labs" and optionally a Description.  Then select the <b>Add</b> link to select a Storage Service.

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/NewProject.PNG"/>

4. Select the <b>Lite</b> Plan and press <b>Create</b>. 

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/COS.png"/>

5. Change the Name if desired and press <b>Confirm</b>

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/COS-Confirm.PNG"/>

6. Return to the New Project page, and click <b>Refresh</b> in the Object Storage section. Your project should now appear similar to the following image.   Press <b>Create</b> to finalize project creation.

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/Storage.PNG"/>

7. The project overview page appears. You are now in your new project where you can create notebooks, add data assets, and add collaborators. 

>  <img src="https://github.com/bleonardb3/DSX/blob/master/images/signup/Project%20Overview.png"/>

8. Now create a Spark Service.  Change the tab to the <b>Settings</b> section 

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/Settings.png"/>

9. Scroll to <b>Associated Services</b> and select <b>Spark</b>

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/ServiceSpark.png"/>

10. Select the <b>Lite</b> (free) plan and select <b>Create</b>

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/CreateSpark.png"/>

11. Set the Spark instance name if you wish and select <b>Confirm</b> 

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/ConfirmSpark.PNG"/>

12. Scroll to <b>Associated Services</b> and select <b>Machine Learning</b>

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/SelectML.png"/>

13. Select the <b>Lite</b> (free) plan and select <b>Create</b>

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/CreateML.png"/>

14. Set the Machine Learning instance name if you wish and select <b>Confirm</b> 

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/ConfirmML.PNG"/>

15. Return to the <b>Assets</b> page. You are now in your new project where you can create notebooks, add data assets, and add collaborators. 

>  <img src="https://github.com/jpatter/GEOINT/blob/master/images/Assets.png"/>
 

You are now ready to begin [Lab-1](Lab-1/).
