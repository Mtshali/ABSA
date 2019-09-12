BDD Cucumber framework or Page object model framework

In Absa Assessment folder I have six packages

accelerators where I have Actions Class and Base Class, 
Actions class has all methods that will be performed by the user on the Application and the Base class has the methods that will run first before any action, like launching the browser. 
com - Contains Cucumber extent report or Html report
features - Contains the features of the application and Gherkins Steps for the API and front end task
pageObjects - Contains all objects of the application. Id, Name, ClassName, Xpath and etc.  
seleniumgluecode - Contains the step definitions that links Gherkins line with the actions methods that will be performed by the user.
utility - Contains method for reading data from the external file, e.g excel file and config file

1, Import the marvin project to eclipse

2, Go to Runner class, ABSA_Assessment\src\test\java\runner

3, Right click anywhere in the runner class

4, Eclipse Dropdown selection list will show

5, Choose to run the project as Junit

6, And go to Com package to check the extent report or Html report.
