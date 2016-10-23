<img src="https://github.com/IBMDataScience/WOW2016/blob/master/images/logo.png">
#Hands on Lab - Data Science Experience

Description: Follow this lab and perform hands on exercises with IBM Data Science Expereince. Use a public data set of car accidents in united states and perform basic corrolations. Data Science Experience allows you to easily develop and share a model that scales using Apache Spark, Python or RStudio. 

# Instructions:

#Step 1. Get on IBM Data Science Experience (DSX).
##Create an account.

1.  Go to [http://datascience.ibm.com/](http://datascience.ibm.com/)

2.  Click the signup button on the top right

 > <img src="https://github.com/ibmdataworks/datafirst/raw/master/datascientist/media/DSX Sign On.png">

3. If you have a Bluemix account you can click continue with Bluemix credentials, otherwise click create your Bluemix account and enter your email.

4. You should get an email from "ibmacct" with your IBMid Confirmation code

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/confirmation-code.png?raw=true"/>

5. Then, on the next page fill in the corresponding fields and click CREATE ACCOUNT

 > <img src="https://github.com/ibmdataworks/datafirst/blob/master/appdeveloper/media/image3.png?raw=true" width="624" height="300" />

6. In the new page, write your email and click CONTINUE

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/enter-email.png?raw=true"/>

7. Write your recently generated password and click on SIGN IN

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/enter-password.png?raw=true"/>

8. It will take a minute to create your account. When ready, click on Get Started.

 > You are now in the Data Science Experience landing page. Your environment is automatically set up with one Apache Spark instance and 5 GB of object storage. From here you can explore any of the tutorials, videos, sample notebooks, totorials or articles in the community.

>  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/landing.png?raw=true"/>

#Step 2. Create a project

1. Click on the left hand side "hamburger" icon and then click on My Projects to see a list of your projects. You should only see a default project.

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/my-projects.png?raw=true"/>

2. Click on the create project icon on the top right of the project list.

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/create-new-project.png?raw=true" />

3. Type a name for your project. For instance, "DSX Lab". A Spark service and an object storage will be automatically selected as well as a container with a default name. A container is a directory on the object storage. Click on Create.

 > You are now in your new project where you can create notebooks and data assets as well as add collaborators.

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/create-project.png?raw=true" width="512" height="499" />

#Step 3. Put data into DSx

1. [Click here to download this repository](https://github.com/IBMDataScience/wow-lab-to-production/archive/master.zip) to your computer to access the data stored in the data directory.

2. Unzip this zip file on your computer so you have a directory with all the assets in the repository.  We will be using the data from the data directory.  The screenshot below shows dragging the contents to the desktop for easy access:

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/open-data-set.png"/>

2. Go to your recently created project on DSX and click on the add data assets + icon

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/add-data-asset.png"/>

3. Click on the Add file and select the transactions.csv file from your computer and click on open

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/add-file.png" width="450" height="275"/>

5. Once the file is loaded, click on Apply to add this file to your project.

 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/apply-file.png" width="450" height="275"/>
 
 > Click Apply on the pop-up:
 
 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/apply-changes.png" width="500" height="225"/>

  > You should see transactions.csv under the data assets list of your project. Your data is  now loaded in your object storage in the container associated to your project. If your project name is "DSX Lab", the default container name is DSXLab (unless you change to a different name on Step 2, part 3).
 >  <img src="https://github.com/IBMDataScience/wow-lab-to-production/blob/master/images/project-view.png"/>


#Step 4. Create a new notebook.


 1.  From the your project page, on the "Overview" tab click "add notebook"

 2.  Click “Add Notebook” 
 
 >  <img src="https://github.com/IBMDataScience/WOW2016/blob/master/images/NewNotebook.png"/>
 
 3. Enter a notbook Name, Description and Select from URL then enter notbook Raw URL, Copy and Paste this URL: https://raw.githubusercontent.com/IBMDataScience/WOW2016/master/VehicleAccidentLab.ipynb

 >  <img src="https://github.com/ibmdataworks/datafirst/blob/master/datascientist/media/LN2.png" width="512"/>

 3. Click on Create Notebook
 
 4. Follow Steps in Notbook.





