# BISEFsd-AutoAdmission
This script automatically register students' of 9th and 1st year on Faisalabad board's Website.
it picks up the data from an excel sheet (template provided), automatically logs in to website, 
and automatically regsiter all the students there.
This script will work only for registered institutes by Fsd board. 
Link for the registered institute to login for 9th Class: 
http://registration.bisefsd.edu.pk/Account/Login.aspx
Link for the registered institute to login for 11th Class: 
http://iregistration.bisefsd.edu.pk/Account/Login.aspx

**Before Running The Code:**
- Download and Install Python from https://www.python.org/downloads/
- After installing python, open command prompt and install the Selenium and Openpyxl modules by running following commands one by one:

 > **pip install selenium**
  
  >**pip install openpyxl**

**How to Use this Code?**
- First you need to write the data of all the students in the excel sheet. You can use the "Excel template" provided in this code repository. 
  Please write the data in the fields carefully. if there is some mistake (Like less digits in B-Form num, the code will broke during execution)

**In the Code, you need to modify 4 things according to you for it to work:**
- the default link is currently set for the registration of 9th Class students. 
  If you are using it to register 11th Class students, you need to change the Link at **Line no 31 and 32.**
- At **Line no. 27 and 29**, you need to enter the username and password provided to your institute by Faisalabad Board. 
- Also, You need a small piece of software called ChromDriver (I suppose you are using Google Chrome since I tested this code on chrome only).
  >Link to Download ChromeDriver: https://chromedriver.chromium.org/downloads
- After you downloaded chromeDriver, you need to update the link of your chromeDriver at **Line Number 16.** 
And you are Done. 

If there is any issue, or the board updated the website, you can contact me by commenting here and i will try my best to fix it. 


Special Thanks to Mahboob Alam sb (Biology Teacher in my School) to give me the idea and also pushing me to work on the Code. 
