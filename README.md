### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:


#### final-project-starter.yml
Students have to write the CloudFormation code using this YAML template for building the cloud infrastructure, as required for the project. 

#### server-parameters.json
Students may use a JSON file for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject". 

In YAML code, the `${EnvironmentName}` would be substituted with `UdacityProject` accordingly.
The infrastructure in image
![infrastructure Diagram](/img/UdacityProjectVPC.png "UdacityProject infrastructure Diagram")

Public URL of load balancer 👉🏽: http://udaci-albwe-90er0bojay9l-1915125289.us-east-1.elb.amazonaws.com/

![website deployed](/img/3 - website-deployed.png "UdacityProject infrastructure Diagram")
