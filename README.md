# AWS Spot Instance Forecasting

We retrieved Amazon Spot Price data which was collected by a third-party person.
• Data has 5 fields <Timestamp, ProductDescription, InstanceType, SpotPrice,
AvailabilityZone> 
• According to data fields;
1. Timestamp (TS) is a time when the tuple was collected.
2. Product Description (PD) is referring to kind of operating system on an instance of Virtual Machine
(VM) where Operating System will be installed according to customer’s demands. It is consisting of 6
unique operating systems.
3. Instance type (IT) is referring to type of VM. Since IT can be picked with respect to business’ goal of
customer, it was taken down into wide brands with 33 unique VM types by AWS.
4. Spot Price (SP) is showing the current market price for each IT and Availability Zone (AZ).
5. AZ is consisting of 22 unique zones in different countries across the world.

This code contains a jupyter notebook that contains code and plots for,
•	Data fetching using boto3
•	Exploratory data analysis
•	Data insights
And the best part! The python file "Spot_instance.ipynb" contains the code for,
•	Data import
•	Feature extraction and engineering
•	Data preparation
•	Predictive Model built using random forests.

