# Cloud-Security-IAM

## Objectives:
1. Create EC2 instances
2. IAM policies
3. IAM users and User Groups
4. AWS account Alias.

<img src= "https://github.com/user-attachments/assets/8df8fc70-3fa0-495c-a659-00dd86707741" width = "300">

**What is EC2 ?**
It is a service that lets you rent and use virtual computers in the cloud. Similar to PCs but exist on the cloud. We can create, customize, for many purposes like running applications to hosting websites. 

An additional benefit is it is able to adapt and scale to meet the demands. 

## Procedure
### *A. Creating EC2 instances*
1. Search for EC2 in the search box on the AWS mgmt console and launch an instance.
   We will set up two instances, one for development and another for production.

   <img src= "https://github.com/user-attachments/assets/477a5223-fb5e-41be-912a-54885e0a7780" width = "500">

   I gave the name and a tag for my instances. It is important to given every EC2 instance a unique name in its AWS Region. 

   The tags are like labels useful for organization. I create an Env(iroment) tag and used the value production and development for my two instances. These tages will help identify all resrouces with the same tag at once . It can be based on cost, allocation, policies     or environment types. 

2. Select AMI(Amazon Machine Image)
   An AMI is a template or blueprint used to create an EC2 instances and contains the software configuration (OS, application server, and applications) needed to launch the instance. 

   For this project, I am selected the Amazon Linux from the free tier options.

   <img src = "https://github.com/user-attachments/assets/79807909-da88-4139-8a18-84407f8036b8" width = "500">

3. Select the instance type
   Instance types deals with the hardware aspects. CPU power, memory size, storage space, etc are slected with the instance type and determine how powerful the instance performs.
   
   Once again, I selected the instance type under the free tier. 
   
   <img src = "https://github.com/user-attachments/assets/f3d1a30a-63d5-4929-affc-13195cc4d476" width = "500">

4. Create a key pair
   The key pair  is used for securely accessing the EC2 instance without going through the AWS Mangement Console. I can use SSH access with the key pairs for this purpose. This allows for additional troubleshooting and managment capabilities.
   
   <img src ="https://github.com/user-attachments/assets/b702187f-b8e1-4c20-b071-9371ad27b832" width = "400">


 


