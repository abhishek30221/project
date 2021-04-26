<h1 align="center">Hi 👋, I'm Abhishek Gusain</h1>
<h3 align="center">A passionate Devops enthusiast from India</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=abhishek30221&label=Profile%20views&color=0e75b6&style=flat" alt="abhishek30221" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=abhishek30221" alt="abhishek30221" /></a> </p>

- 🌱 I’m currently learning **Devops**

- 📫 How to reach me **abhishekgusain2705@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://fb.com/abhishek gusain" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/neutral-icons/src/images/icons/Social/facebook.svg" alt="abhishek gusain" height="30" width="40" /></a>
<a href="https://instagram.com/abhishek30221" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/neutral-icons/src/images/icons/Social/instagram.svg" alt="abhishek30221" height="30" width="40" /></a>
<a href="https://www.leetcode.com/abhishek2705" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/neutral-icons/src/images/icons/Social/leet-code.svg" alt="abhishek2705" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.gnu.org/software/bash/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.jenkins.io" target="_blank"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.selenium.dev" target="_blank"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="40" height="40"/> </a> </p>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=abhishek30221&show_icons=true&locale=en&layout=compact" alt="abhishek30221" /></p>

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
