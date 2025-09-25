# Real-time Data Management with AWS Kinesis & DynamoDB

## Project Overview
This is a test/learning project for the AWS Solutions Architect course.  
It demonstrates real-time data streaming using **AWS Kinesis Data Streams** and storing/processing the data.

## Files Included
- **docs/** : Documentation related to the project.  
- **infra/** : Infrastructure setup notes or scripts.  
- **src/** : Python scripts or any code used for the project.  
- **# Real-time Data Management Kinesis.txt** : Commands and notes for running Kinesis tests.  
- **.gitignore** : Files ignored by Git.  
- **README.md** : Project summary and instructions.

## How to Run
1. Make sure you have AWS CLI installed and configured.  
2. Run `aws kinesis put-record` commands to send sample data to your stream.  
3. Use Python script to decode base64 data from Kinesis stream.  
4. Retrieve records using `aws kinesis get-records` with the correct shard iterator.  

## Notes
- Stream Name: `TelemaxStream`  
- Shard Count: 1 (for testing)  
- This project is for learning real-time data processing on AWS.
