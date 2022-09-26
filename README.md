# DevOps_Udacity_Project2
Advanced DevOps NanoDegree Udacity Project_2
Project 2 --> Deploy a high-availability web app using CloudFormation -Infrastructure as Code (IaC)-

To create network and service stacks you can run the create.sh followed by the stack name,template name and parameter file for  both Network and server stacks

1-  
  ./create.sh networkstack project2_network.yml network-parameters.json
2-
  ./create.sh serverstack project2_servers.yml  server-parameters.json 


Parameters are stored in network-parameters.json and server-parameters.json to avoid hard coding parameter values.
