# CRM Build

Contains the required modules to build the CRM Webservice. 

Maven project includes [CRM Parent POM](https://github.com/ISingh2015/CustParent) and modules which need to be built before the webservice components are assembled into the CRM Web or the CRM Swing client.

# Windows:
Download all the modules as in the POM file into a single directory including this POM project. Build the CRM web application components as below. 

Before building ensure that you have a SQL database server running and server configuration is setup correctly in application.properties, to enable running all the CRUD test successfully and building the below three:-

1. CRM Web service war file runnable in a web server (e.g Tomcat 8.0 or above).
2. CRM SWING CLIENT jar file. 
3. CRM SWING client download WEB app.

Once all the test pass the war and jar files will be built into the respective project / target folder. 
1. Start the CRM web service.
2. Start the CRM SWING client download web app (copy the CRM SWING client jar file into a folder accessable to this web app).

Login to the CRM SWING client download web app by registering a user. This will allow downloading the SWING client which can connect to the centralised CRM local database.

With the CRM Service running, run the SWING client using JAVA -JAR option and login to CRM system using the credentials created while downloading the CRM Swing Client. The SWING client will allow creating other users which work for a period of 90 days.

Ubuntu-Linux setups and B2B payment gateway integration pending.
