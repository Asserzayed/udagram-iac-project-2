## udagram-iac-project-2
## Submission for ND FWD - Cloud DevOps - 2nd Project
=======
### Temporary link to LB endpoint
http://proje-myweb-1k46sqk8b9di4-1148622837.us-east-1.elb.amazonaws.com/

### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:

#### final-project-starter.yml
Students have to write the CloudFormation code using this YAML template for building the cloud infrastructure, as required for the project. 

#### server-parameters.json
Students may use a JSON file for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject".

#### create.sh and update.sh
Shell script to deploy/update stack, shell script is used
``` ./create [stack-name] [body-name.yml] [parameters-file-name.json] [profile-name]```
``` ./update [stack-name] [body-name.yml] [parameters-file-name.json] [profile-name]```

## Diagram
![plot](diagram3.png)
