# Student-Management-Sysytem

1. Data.csv:
    This file contains data of student entered by teacher in csv format.
    First line contains header --> Name, F_name, Roll_no, Maths, English, Science.
	
2. users.py:
    This file can be operated by admin.
    This file used to create users who can access data base and enter details of students.
    Run this file separetly to enter user details and password.
	
3. users_data.pkl:
	This file contais user_name and encrypted password in dictanory format stored in pickle file.
	
4. store_load_data.py:
	This file is use to create data and write it into Data.csv, and load data from Data.csv file.
	There are two functions in this file for storing and loading the data.
	
5. login.py:
	This file is used to check the login details entered by the user.
	This file encrypts the password entered and checks it with the users_data.pkl file.
	If the details matched then access is given, else it returns False.
	
6. main.py
	This is the main file of the project.
	Run this file directly to see the output window.
	Enter the required inputs and get the desired output as per the details entered.
	
![Output_1](https://user-images.githubusercontent.com/49095782/111474525-2b646580-8752-11eb-9d35-48ae0889f72c.jpg)

![Output_2](https://user-images.githubusercontent.com/49095782/111680044-d0149f00-8847-11eb-9e5a-bf0666744e7a.jpg)

![Output_3](https://user-images.githubusercontent.com/49095782/111680055-d3a82600-8847-11eb-9cae-d793e1aef075.jpg)
