# AmdocsAssignment
Assignment
# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

This project  will start with Authorization service and internally call UserProfile Microservice having address http://localhost:9091
Use the below link for Post ,Put,Delete Operation  


1)  Post :

	localhost:9090/assignement/profile
	
	

	-This will  create data in Aauthorization table and Profile table


2) Put
	localhost:9090/assignement/{uname}/{pass}
	
	This method will first check in username and paasword ate present in authorization DB then will update the profile data

3) Delete
	localhost:9090/assignement/{uname}/{pass}
	
	This method will first check in username and paasword ate present in authorization DB then will delete the profile data
	
	
	
	Note : There are not error handling in this project as it was not mentioned in the requirement
