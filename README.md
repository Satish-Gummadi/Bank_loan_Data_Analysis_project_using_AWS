# Bank_loan_Data_Analysis_project_using_AWS
In this project I will be analyzing the bank loan data set (attached in this repository). Here I will use various frameworks such as HDFS, Hive, Spark and MongoDB, which I will run on EMR cluster in AWS.

The work flow I will be adopting is as follows: 
1)	To Load the file in S3 bucket 
2)	Creating EMR cluster on AWS, and run Hive on the cluster 
3)	Load the CSV file in Hive external table from S3 
4)	To use PySpark in Hadoop and query the hive table on spark using sparksql 
5)	Installing MongoDB on Hadoop cluster 
6)	Converting the queried result sets into dictionary and storing them in MongoDB in the form of collections from PySpark. 

![Flow chart of project-2](https://github.com/Satish-Gummadi/Bank_loan_Data_Analysis_project_using_AWS/assets/111731023/725e2c1c-064d-4a2a-a70e-042b9445f86e)

The Detailed process is explained in the project report attached. Please refer the report file to check the End-to-End modeling of the pipeline and analysis of the Bank loan data.
