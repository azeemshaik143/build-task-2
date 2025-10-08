# build-task-2

Java Web Application: Build & Deploy Guide (Java 17 + Maven + Tomcat)

Overview
This project is a Java Web Application designed to run on Java 17, built using Maven, and deployed on Apache Tomcat. The project demonstrates a basic Java web app structure, with a simple calculator implementation.

Project Structure
JavaWebCalculator/
├── pom.xml
├── src/
│   ├── main/
│   │   ├── java/mypackage/Calculator.java
│   │   └── webapp/
│   │       ├── WEB-INF/web.xml
│   │       └── index.jsp
│   └── test/java/mypackage/CalculatorTest.java
pom.xml: Maven project configuration.
simple java application
index.jsp: The homepage of the web application.
web.xml: Web application configuration.

Prerequisites
creating servers for build and deploy
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/87d8e6b6-0d0b-4c37-9323-94ef26c66369" />
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/bfff7972-2faf-487f-8ac4-22abf0a90968" />
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/05e6cc02-b942-4b58-b86a-d7206d968b54" />
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/ce8367b6-b71a-4fa5-a05a-5dfd4ec49621" />
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/531e4e54-bbc5-4ea3-9917-7b91e10c329b" />
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/08da1d1d-e151-4ba8-9e47-9a5ebcd25e40" />
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/c1b6caa4-7feb-4815-95f5-3140a6d26c81" 

 Install Java 17
To install Java 17, run the following commands (for Ubuntu/Debian):

sudo apt update
sudo apt install openjdk-17-jdk -y
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/78ed8db8-fe76-48e8-ac14-6442b3c1ca83" />
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/3f9cacad-59c5-4882-b389-7a1030c10567" />

clone the code from github repository
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/c5c7021c-5ba8-49bb-a4ee-7ede6953af1d" />
install maven
sudo apt -y install maven
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/9e2a80ba-22df-4a0d-bde5-fc37ac374f69" />
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/b1df0a0a-8b0e-47d5-bf36-aea662c5109b" />
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/2bac5cf3-3550-4d47-a08c-cd8eca14820b" />

install apache tomcat on deploying server
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/623a47ca-dd8d-4946-9b20-64d1d0471509" />



