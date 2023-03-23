# Student-Enrollment-Form
## Description 
This is a web based html form for student enrollment using JsonPowerDB as Database 
JsonPowerDB is used to perform CURD operation.


# Benefits of using JsonPowerDB
* Simple to use , real time database
* Simplest way to retrieve data in a JSON format.
* No need for defining schema 
* It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
* It is low level (raw) form of data and is also human readable.
* It helps developers in faster coding, in-turn reduces development cost.
* Simplest way to retrieve data in a JSON format.
* Backends code is not required for database 
* Querying the database is easy there is no need  of knowledge of SQL commands


# Illustrations:
* **SAVE** : If student roll number is not existed in database then we can fill other field and save in database
* **UPDATE** : when student roll number is already present in database then student information is fetched from database and filled in respective feild then user can UPDATE student information 
* **clear** : By this we can clear all field of form and with this except first field (roll-no) other field are disabled until user enter any roll number
* **Alert** : This website uses disposable Alter prompt using bootstrap

# Screenshots:
<img src="/images/Data1.PNG">
<img src="./images/Database.PNG">



# HOW TO USE STEP BY STEP

* **Initially**
<img src="./images/Homepage">

We need to enter a roll number 

If roll number is not valid 

<img src="./images/Invalid_Roll.PNG">

If roll number is valid and that roll number is existnig in database

<img src="./images/Student_Exist.PNG">

* **Fetching student data using roll number**
  If student already present in database, then all field filled with that student information
  
  <img src="./images/Student_Exist.PNG"">
  otherwise, other fields are enabled after user input roll number
  
* **Updation of student details**
  In order to update student details input roll number, and then we can update the student data
  
  <img src="./images/Update_Student.PNG">
  
  <img src="./images/Change_Class.PNG">

  <img src="./images/Updated_Successfully.PNG">

  <img src="./images/New_Database.PNG">

* **Adding new student data**

  Enter new roll number and then all other fields are enabled and then after filling student information we can save this data into database only if input is valid
  
  <img src="./images/Save_data1.PNG">
  
  <img src="./images/Alert_Save_data1.PNG">
  
 * **If input data is not valid**
  
   <img src="./images/invalid_details.png">


  
