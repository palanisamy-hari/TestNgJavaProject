# Java - TestNG test framework

TestNG is a testing framework inspired from JUnit and NUnit but introducing some new functionalities that make it more powerful and easier to use

  - Annotations
  - Support for data-driven testing (with @DataProvider).
  - Support for parameters.


# Project Set-up!

  - Create a Maven Project in Eclipse IDE
  - Add jars to the Java Build Path
  - Download and add ChromeDriver 80.0.3987.16 to the classpath compatible Chrome Version 80.0.3987.132.



# Create a Maven Project in Eclipse IDE!
  - Open Eclipse and right click on Package Explorer. Select New >> Maven project. And click the Next button.
  - Tick the <Create a Simple Project (skip archetype selection)> checkbox and click Next.
  - Fill the group id, artifact id, and name. And click the Finish button to create the project.
  - In Eclipse, Window --> Preferences --> Installed JREs, Mkae sure its pointed to the installed JRE.
  - Add required Maven Dependencies in POM.XML

# Add following jars to Java Build Path
  - Selenium-java-2.41.0.jar
  - Selenium-server-standalone-2.46.0.jar
  - testNG-7.1.0.jar

# Running TestNG Tests!
  - Navigate to webUITests.AutomationPracticeTests
  - Once all the jars are added to the build path like testng.jar, selenium jars etc
  - Right click on the Test class and Run as --> TestNG Test

