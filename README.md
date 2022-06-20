### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:


#### final-project-starter.yml
Students have to write the CloudFormation code using this YAML template for building the cloud infrastructure, as required for the project. 

#### server-parameters.json
Students may use a JSON file for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject". 

In YAML code, the `${EnvironmentName}` would be substituted with `AhmzyUdacityProject` accordingly.


The following are the screenshot steps of generated resources after deployment of infrastructure

## Auto Scaling
![Auto Scaling](/screenshots/autoscaling_group.png?raw=true "Auto Scaling")

## Load balancer
![Load balancer](/screenshots/loadbalancer.png?raw=true "Load balancer")

## Security group
![Security group](/screenshots/security_group.png?raw=true "Security group")

## Infrastrucre Stacks
![Infrastrucre Stacks](/screenshots/stacks.png?raw=true "Infrastrucre Stacks")