# IOT-Based-Smart-Attendance-System-Using-WebApp

## Abstract

Taking attendance manually in class of students consumes a lot of time which could be used for other useful work. Also, manual attendance is not reliable as the chances of people giving proxy attendance is also very high, especially when the strength of the class is high. Radio Frequency Identification (RFID) based attendance system is discussed here which makes attendance taking much more reliable and less cumbersome. COVID-19 has also made it necessary to ensure that students who show symptoms of the disease like high temperature are not allowed to enter the class. So, a non-contact MLX90614 temperature sensor is also used to accurately monitor the temperature of the students entering the class. Each student is uniquely identified with the help of their RFID tag when it is scanned and details like the Student ID, time, temperature and date are recorded. The recorded information is sent to a database where it is stored and can later be used. The website and database also make it unnecessary to maintain physical attendance records and monitoring of attendance is much easier than with physical records, apart from being secure. Random forest regressor model has been used to predict future attendance and visualization of trends has been performed.

## Flowchart

![image](https://github.com/rittikadeb/IOT-Based-Smart-Attendance-System-Using-WebApp/assets/76259897/cc3ed4ce-44a1-4364-9785-1f1279e1b2cd)


## Hardware Implementation

![image](https://github.com/rittikadeb/IOT-Based-Smart-Attendance-System-Using-WebApp/assets/76259897/79d7bb6d-7f59-4463-a07a-5e13781e8412)

## Graphical User Interface

The XAMPP Control Panel Database is used in this project to build a visual server that stores each student's attendance information. One database was created using the XAMPP Control Panel database is named “rfidattendance” which consists of admin, devices, users, user logs. Information about the students who attended a lecture class is kept in the "users" database. The administration or lecturer uses this
information to identify and manipulate each student's attendance data.

![image](https://github.com/rittikadeb/IOT-Based-Smart-Attendance-System-Using-WebApp/assets/76259897/8ca3a9dd-8445-4754-846b-5da077215641)


## Data Analytics

The data analytics part of this project includes marking of absence or presence, prediction of future attendance, and visualizing the data. We have used Jupyter notebook for this process. Libraries such as Pandas, Numpy, Matplotlib, Scikit learn have been used.
● Assigning presence or absence based on the entry time. 

![image](https://github.com/rittikadeb/IOT-Based-Smart-Attendance-System-Using-WebApp/assets/76259897/53930eb3-6473-4fc4-bda7-622c6217e358)


● Visualizing the number of present vs absent students for every day using Bar plot.

![image](https://github.com/rittikadeb/IOT-Based-Smart-Attendance-System-Using-WebApp/assets/76259897/1dcc94eb-4306-44a6-bf95-a8c3e73f5f7a)

● Prediction of next day’s attendance using Random forest regressor model.

![image](https://github.com/rittikadeb/IOT-Based-Smart-Attendance-System-Using-WebApp/assets/76259897/a8c8bd03-f4d5-4ded-98d2-b06ed37f2336)

## Results

The experimental results show that the proposed system designed for attendance management, has provided significant results in managing attendance through RFID system, it has revolutionized the method of registering the attendance. The web GUI provided gives better clarity of the attendance registered and helps in generating reports as and when needed.


