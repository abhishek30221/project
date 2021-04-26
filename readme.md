

<b>PROJECT</b>

In this project I have Implemented a full-fledged CI CD Pipeline using DevOps Methodology.

Product is available on this GitHub link:  https://github.com/abhishek30221/project.git
(Open-Source)

Following are the specifications of the lifecycle:
1.	Git Workflow is implemented
2.	Code Build is automatically triggered once commit is made to master branch or develop branch.

If commit is made to master branch, test and push to production
If commit is made to develop branch, just test the product, do not push to production

3.	The Code is containerized with the help of a Docker file. The Docker file is built every time there is a push to Git-Hub. I am using the following pre-built container for my application:

hshar/webapp

The code is residing in '/var/www/html'
Production Slave running at this IP address: 3.87.147.109

4.	Once the website is built, I have designed a test-case, which will basically check if the website can be opened or not. If yes, the test should pass. This test is running in headless mode, on the test server.


5.	These above tasks is defined in a Jenkins Pipeline,
Job 1 - Building Website
Job 2 - Testing Website Job 3 - Push to Production

6.	Since I have set up the server for the first time, I am ensuring the following file exists on both Test and Production server in /home/ubuntu/config-management/status.txt. This file will be used by a third-party tool. This should basically have the info whether apache is installed on the system or not.
 
The content of this file, is based on whether apache is installed or not.

If apache is installed => Apache is Installed on this System"
If apache is not installed => "Apache is not installed on this System"


7.	Created a Monitoring Service for the website on the Production server 

Architecture Used:

Created 3 servers on AWS "t2.micro"

Server 1 - Jenkins Master, Puppet Master and Nagios Installed 
Server 2 - Testing Server, Jenkins Slave
Server 3 - Prod Server, Jenkins Slave


Tools Used:

1.Git
2.Jenkins
3.Docker
4.Puppet
5.Selenium
6.Nagios



FULL DOCUMENTATION IS AVAILABLE:
Reach out to me at abhishekgusain2705@gmail.com  
