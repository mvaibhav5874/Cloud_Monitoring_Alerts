# CLOUD_MONITORING_ALERTS

**COMPANY**: CODTECH IT SOLUTIONS 

**NAME**: M.S.G.N. SURYA VAIBHAV

**INTERN ID**: CT08IVH

**DOMAIN**: CLOUD COMPUTING

**BATCH DURATION**: JANUARY 20, 2025 to FEBRURAY 20, 2025

**MENTOR NAME**: NEELA SANTOSH

## TASK: 
SET UP MONITORING FOR A CLOUDBASED APPLICATION USING AWS
CLOUDWATCH.

### Description :
In This task i need to deploy an cloud based application or and web application connected to multiple services provided by the CSP (AWS)

### procedure:
1. Create an EC2 instance :
   - Create an basic instance of an aws amazon linux
   - select the amazon linux ami
   - select t2 micro for the basic web applications or applications
   - select an key pair
   - configure the networ settings
   - allow http trafic as it is an web application
   - go to advance settings
   - get to user data - optional and add the code for the instance
   - [user data](user_data)
   - create the instance
2. For alarms :
   - go to the cloud watch -> alarms -> create alarm
   - enter the conditions for the alarms
   - enter the threshold  value
   - next -> ec2 actions -> stop this instance
   - this will stop this instance when the threshold value is hit
   - next -> review and create -> create alarm
   - [ALARM](EC2_alarm)
