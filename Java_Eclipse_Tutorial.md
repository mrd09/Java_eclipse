# Eclipse Tutorial

- Install Java, JRE
- Download Tomcat 7.

- Add tomcat server to Eclipse
	+ Open Window -> Preferences -> Server -> Installed Runtimes to create a Tomcat installed runtime.
	+ Click on Add… to open the New Server Runtime dialog, then select your runtime under Apache (Apache Tomcat v7.0 in this example).
	+ Click Next , and fill in your Tomcat installation directory : D:\Git\tomcat_7\apache-tomcat-7.0.91

- Clone Repository from github to eclipse:
	+ Copy the github link:	
	+ Paste direct in Git Repositories in Eclipse: https://github.com/mrd09/Java_eclipse.git
		-> fill in the account
		-> Select the folder to store git
		-> select the code branch want to clone
	+ After finish rightclick the .git -> Import Project

- Check the library Build Path: Right Click the Imported project -> Properties
	+ Config the JRE version: JRE System Library -> Edit -> Environments -> JavaSE 1.7
	+ Check if library has error with mark "red x" -> Edit -> locate to tomcat library
		For Example: D:\Git\tomcat_7\apache-tomcat-7.0.91\lib

- Run Server:
	+ Normal mode: RightClick -> Run As -> Run on Server
	+ Debug mode: RightClick -> Debug As -> Debug on Server

- Make a hold point: In Debug mode
	+ F6: next run in debug mode
	+ Ctrl + Shift + I: check function result
	+ F8: to Resume for releasing the code running

- Export War File:
	+ Rigt Click Project -> Export -> Search WAR

