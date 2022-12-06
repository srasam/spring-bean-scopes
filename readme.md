


About the project:
This is a sample java/spring application that can be used to understand the concept of Bean scope and Bean lifecycle. The project demonstrates singleton and prototype scopes.

Technologies and tools used
1. Java 11
2. Spring 5.3.9
3. Eclipse IDE

How to download spring jar files and add it to the lib folder of your project:

1. Go to this URL: https://repo.spring.io/ui/packages
2. Use the path below to choose the latest version of spring version to download the libraries
	Path: Artifactory->choose artifacts->libs-release->org->springframework->spring->choose latest version->download spring dist.zip
3. unzip file->libs->copy all jar files->paste in lib folder of the project
4. Add these jar file to java build path (Classpath)

Instructions:
1. How to checkout the code from git?

clone this repository: https://github.com/srasam/spring-bean-scopes.git
2. How to Run the code locally?

There are several ways to run a Spring application on your local machine. One way is to execute the main method in the com.demo.spring.BeanLifeCycleDemoApp,com.demo.spring.BeanScopeDemoApp  class from your IDE.

3. How to deploy to Tomcat locally and on remote server?

This project does not require a tomcat server. This is a simple spring application 

different Bean scopes:

1.singleton-default 
2.prototype- new object for each request
3.request
4.session
5.global-session






