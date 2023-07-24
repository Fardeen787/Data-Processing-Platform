# Data-Processing-Platform
The objective of this project is to gather and store CSV data from various 
devices in a data warehouse as a table format, and then use Amazon 
QuickSight to visualize the data for efficient and effective analysis and 
decision making. The goal is to provide a centralized and organized storage 
solution for the data and to facilitate the visualization of the data.

![image](https://github.com/Fardeen787/Data-Processing-Platform/assets/80382150/6286e45c-7718-46a6-a857-33ca2b1a29f9)

So as you can see there are multiple devices from which csv files are generating like IOT device,some application some database so it will store inside the S3 bucket from there I will use crawler which will scan the whole database of s3 and store it inside the AWS glue and then I will use one more crawler which will scan the data from AWS glue and store it inside the amazon redshift in the form of table and then at last I will use amazon quicksight which will visualize the data in the form of graph on the dashboard.


# Implelementation


![image](https://github.com/Fardeen787/Data-Processing-Platform/assets/80382150/b4c39f55-040c-470c-b171-0adc2601532e)

![image](https://github.com/Fardeen787/Data-Processing-Platform/assets/80382150/494c0d68-ccdb-477b-b700-50e93c29bdf7)

![image](https://github.com/Fardeen787/Data-Processing-Platform/assets/80382150/eebd2654-e520-45a4-b0b6-a0f8d34c6823)


![image](https://github.com/Fardeen787/Data-Processing-Platform/assets/80382150/b02a935d-b6af-4685-a0fa-9167eb33325a)


![image](https://github.com/Fardeen787/Data-Processing-Platform/assets/80382150/4173f447-d8e7-4f91-8ede-7c45b307cc8f)





