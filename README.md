# json2Excel
Code snippet which converts json format response into excel records

Task Completion status:

### Build a REST api automation connector  
- Use the provided endpoint to capture all the information and save it in an excel with correct  headers. → (Mandatory) - [COMPLETED]


## jSon2Excel

In this File I'm going to explain <b>How to configure </b> and <b>Run this Framework</b>

The tech stack used for developing this framework are:
1. **JAVA** as the programming language for writing test code
2. **Maven** as the build tool
3. **Intellij** as the preferred IDE for writing java code.


#### Getting Started
Setup your machine.
1. Install JDK 11 & set "JAVA_HOME" in environment variable
2. Install Intellij
3. Download and Set "Maven_Home" as a environment variable
4. Add dependency - org.json to the POM.xml

#### Running tests
``Note:`` Sometime JRE System Library might be referring the wrong Library, please do select the JDK path in Build Path ```
1. You can run the tests directly from the intellij, by right-clicking POM.xml and **maven test**.
2. Framework will executes on Both Mac & Win [Make sure the above mentioned tools are installed and configured].
3. For Mac:
		-> Open the terminal
		-> Navigate to Project [project] Folder{root} directory 
		-> Execute the below command 
		```mvn clean install```
4. For Windows: 
		-> Open the command prompt
		-> Navigate to Project [project] Folder{root} directory 
		-> Execute the below command
		```mvn clean install```

---


### Framework Folder Structure

### Project Folder- Root Directory
	
	### src/main/java - For keeping all the reusable codes [Project Specific & Generic's]
		###com.project.context - For dependency injection using Pico Containers
		###com.project.managers - For Managing the driver, page, property file reader
		###com.project.pages - Page classes for web elements and actions
		###com.project.utils - All the utilities functions are developed under this package in different classes.
	
	### src/test/java - Execution package
		###com.project.runner - To specify what to scenarios to run
		###com.project.steps - Step implementations for all the steps in feature files
	
	### src/test/resources - test data and configuration folder
		###dataset - To keep Browser name, waits, urls, test data to test the app
		###feature - All the tests are written in Gherkin language in .feature files
		###extens.properties - Extent report related configuration settings
		###log4j.properties - Log4j configuration information
		
	###POM.xml - Project Object Modal file for all the dependency and executions.
	
	*** Json2Excel conversion code snippet ***



















