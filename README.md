# NAME:- V.B.LAKSHA
# REG.NO:- 212224220051
# Experiment-15
## The study of the Selenium Web Testing Tool reveals its effectiveness in automating web applications for testing purposes across different browsers and platforms.
# What is Selenium?
JavaScript framework that runs in your web browser Works anywhere JavaScript is supported Hooks for many other languages Java, Ruby, Python Can simulate a user navigating through pages and then assert for specific marks on the pages All you need to really know is HTML to start using it right away

# Selenium IDE
Selenium Integrated Development Environment (IDE) is a Firefox plugin that lets testers to record their actions as they follow the workflow that they need to test. It provides a Graphical User Interface for recording user actions using Firefox which is used to learn and use Selenium, but it can only be used with Firefox browser as other browsers are not supported. However, the recorded scripts can be converted into various programming languages supported by Selenium and the scripts can be executed on other browsers as well.

# Selenium-IDEDownload

Step 1 − Launch Firefox and navigate to the following URL - http://seleniumhq.org/download/. Under the Selenium IDE section, click on the link that shows the current version number as shown below. 

<img width="770" height="261" alt="435375171-9640140e-34bb-42cd-b4cd-f55f7b166e2b" src="https://github.com/user-attachments/assets/48978f87-2d69-43af-b5bc-888facf0726d" />

Step 2 − Firefox add-ons notifier pops up with allow and disallow options. User has to allow theinstallation.

<img width="408" height="172" alt="435375274-6780c850-f3b6-469d-824f-b2b236cf6675" src="https://github.com/user-attachments/assets/a6c188b7-affc-474c-b9b8-0a9834014fb8" />

Step 3 − The add-ons installer warns the user about untrusted add-ons. Click 'Install Now'.

<img width="568" height="388" alt="435375318-52e37156-2320-4adc-88f9-6117823b9219" src="https://github.com/user-attachments/assets/993bf5fb-47cc-4583-a066-6832c2b9395e" />


Step 4 − The Selenium IDE can now be accessed by navigating to Tools >>Selenium IDE.

<img width="508" height="233" alt="435375346-f372f56c-f36e-46a4-86fb-b846354bd006" src="https://github.com/user-attachments/assets/7e9c46b5-56c8-4bfd-87a9-8ade0576f896" />

Step 5 − The Selenium IDE can also be accessed directly from the quick access menu bar as shown below.

<img width="279" height="91" alt="435375371-844807c4-b79c-4380-a24b-c3ae3b310f0c" src="https://github.com/user-attachments/assets/c623090b-b4d9-45aa-ba1b-7a2d233c189f" />

# Selenium IDE Features
This section deals with the features available in Selenium IDE. The following image shows the features of Selenium IDE with the help of a simple tool-tip.

<img width="505" height="354" alt="435375413-308658dc-e78a-4343-bffc-0fd3f27fb72b" src="https://github.com/user-attachments/assets/596e813b-a3e4-4570-9e88-b8be74258921" />

The features of the record tool bar are explained below.

<img width="574" height="740" alt="435375446-48bdbef0-38f1-4550-b686-6c861300963d" src="https://github.com/user-attachments/assets/4c3e832f-1482-4f29-944c-60abf4413269" />


# Creating Selenium IDE Tests
This section deals with how to create IDE tests using recording feature. The following steps are involved in creating Selenium tests using IDE − Recording and adding commands in a test Saving the recorded test Saving the test suite Executing the recorded test RecordingandAdding CommandsinaTest We will use www.ncalculators.com to demonstrate the features of Selenium.

Step 1 − Launch the Firefox browser and navigate to the website - https://www.ncalculators.com/

Step 2 − Open Selenium IDE from the Tools menu and press the record button that is on the top- right corner.

<img width="513" height="236" alt="435375664-db9d878e-8aad-499e-943f-bcb176a18712" src="https://github.com/user-attachments/assets/fba65b16-8f8e-4a26-b5d4-a51e4c1edc2d" />


Step 3 − Navigate to "Math Calculator" >> "Percent Calculator >> enter "10" as number1 and 50 as number2 and click "calculate".

<img width="643" height="219" alt="435375699-0106ae43-ba92-4458-8379-bf6c60ba3b96" src="https://github.com/user-attachments/assets/51a0c309-7bf7-4bfb-9d34-80cedaab5dd6" />


Step 4 − User can then insert a checkpoint by right clicking on the webelement and select "Show all available commands" >> select "assert text css=b 5"

<img width="647" height="333" alt="435375732-be6ff515-306b-4d31-8fed-9b8a906be672" src="https://github.com/user-attachments/assets/36c97f18-b9b9-4bc7-83a5-e09a8b6ebade" />

Step 5 − The recorded script is generated and the script is displayed as shown below.

<img width="649" height="351" alt="435375758-a7b0939c-ff86-4147-8037-761eb2483af3" src="https://github.com/user-attachments/assets/40cd6f47-32fb-4f11-815e-f73b56731417" />


# SavingtheRecordedTest
Step 1 − Save the Test Case by navigating to "File" >> "Save Test" and save the file in the location of your choice. The file is saved as .HTML as default. The test can also be saved with an extension htm, shtml, and xhtml.

<img width="627" height="287" alt="435375798-29cee702-8d26-4c2b-a4dd-658acf8de20a" src="https://github.com/user-attachments/assets/e356e1d4-565a-4313-91dc-af37970d70f3" />


# SavingtheTest Suite
A test suite is a collection of tests that can be executed as a single entity.

Step 1 − Create a test suite by navigating to "File" >> "New Test Suite" as shown below.


<img width="615" height="294" alt="435375837-8816e8fc-8f0b-47e4-83d9-63c3b43386a4" src="https://github.com/user-attachments/assets/571345a0-6ac7-4cb7-959d-50af8566ee83" />


Step 2 − The tests can be recorded one by one by choosing the option "New Test Case" from the "File" Menu.

Step 3 − The individual tests are saved with a name along with saving a "Test Suite".


<img width="652" height="293" alt="435375900-424d8df0-8ddb-4885-a0ec-f83e138178f9" src="https://github.com/user-attachments/assets/cfde3d66-f47f-4d6c-b01b-2530d6d2a62e" />


Executingthe RecordedTest
The recorded scripts can then be executed either by clicking "Play entire suite" or "Play current test" button in the toolbar.

Step 1 − The Run status can be seen in the status pane that displays the number of tests passed and failed.

Step 2 − Once a step is executed, the user can see the result in the "Log" Pane.

Step 3 − After executing each step, the background of the test step turns "Green" if passed and "Red" if failed as shown below.


 <img width="940" height="498" alt="435376062-de10a1f0-3418-4a52-be9e-59c80706b8b7" src="https://github.com/user-attachments/assets/3da47f24-1774-4e82-b4e5-bcb7c690f94e" />

 

# Selenium IDE Script Debugging
This section deals with debugging the Selenium IDE script. Debugging is the process of finding and fixing errors in the test script. It is a common step in any script development. To make the process more robust, we can make use a plugin "Power Debugger" for Selenium IDE.

Step 1 − To install Power Debugger for Selenium IDE, navigate to https://addons.mozilla.org/en- US/firefox/addon/power-debugger-selenium-ide/ and click "Add to Firefox" as shown below.


<img width="917" height="324" alt="435376155-0fef1f06-acf8-4b39-8946-a373baba2006" src="https://github.com/user-attachments/assets/4101ea94-d029-4964-9721-80cd196210ce" />

Step 2 − Now launch 'Selenium IDE' and you will notice a new icon, "Pause on Fail" on recording toolbar as shown below. Click it to turn it ON. Upon clicking again, itwould be turned "OFF".  

<img width="913" height="426" alt="435376202-4ee36fd5-d480-4dfd-96b4-0817c03cbb6e" src="https://github.com/user-attachments/assets/2aeecab8-857b-43e2-a9f9-63a714c54b6d" />

Step 3 − Users can turn "pause on fail" on or off any time even when the test is running.

Step 4 − Once the test case pauses due to a failed step, you can use the resume/step buttons to continue the test execution. The execution will NOT be paused if the failure is on the last command of any test case.

Step 5 − We can also use breakpoints to understand what exactly happens during the step. To insert a breakpoint on a particular step, "Right Click" and select "Toggle Breakpoint" from the context- sensitive menu.

<img width="924" height="663" alt="435376248-55acedf6-e22a-4c7f-801c-d6d3b05c76f7" src="https://github.com/user-attachments/assets/7096283b-bf1e-48b5-a131-eae653388423" />

Step 6 − Upon inserting the breakpoint, the particular step is displayed with a pause icon as shown below.


<img width="923" height="576" alt="435376292-c3845b7b-7b46-48f0-adec-cc471821af4a" src="https://github.com/user-attachments/assets/231bb6e4-393b-4297-a942-cea8903a9032" />

Step 7 − When we execute the script, the script execution is paused where the breakpoint is inserted. This will help the user to evaluate the value/presence of an element when the execution is inprogress.



<img width="923" height="506" alt="435376317-d8877cde-5df2-410f-9aba-5287e674d808" src="https://github.com/user-attachments/assets/58fc25e1-e1d5-4500-9b4c-07ace988ff00" />


# Inserting Verification Points
This section describes how to insert verification points in Selenium IDE.

The test cases that we develop also need to check the properties of a web page. It requires assert and verify commands. There are two ways to insert verification points into the script. To insert a verification point in recording mode, "Right click" on the element and choose "Show all Available Commands" as shown below.



<img width="921" height="520" alt="435376364-818415c3-c52c-4afa-bed1-a7ee47af342b" src="https://github.com/user-attachments/assets/9675182b-afa7-4104-9a3f-f87e2648ca50" />

We can also insert a command by performing a "Right-Click" and choosing "Insert New Command".



<img width="931" height="557" alt="435376396-e3760cf5-e8d5-4ce3-9742-27de030267bb" src="https://github.com/user-attachments/assets/bc27f7ce-61f3-4f0e-bfec-bb841060cacf" />


After inserting a new command, click 'Command' dropdown and select appropriate verification point from the available list of commands as shown below.


<img width="928" height="332" alt="435376427-0037771e-ae3a-4223-82a2-482cf85ab9c4" src="https://github.com/user-attachments/assets/4b8215c7-6a90-400a-b589-b3534990d142" />

Given below are the mostly used verification commands that help us check if a particular step has passed or failed.

 verifyElementPresent  assertElementPresent  verifyElementNotPresent  assertElementNotPresent  verifyText  assertText  verifyAttribute  assertAttribute  verifyChecked  assertChecked  verifyAlert  assertAlert  verifyTitle  assertTitle

# SynchronizationPoints
During script execution, the application might respond based on server load, hence it is required for the application and script to be in sync. Given below are few a commands that we can use to ensure that the script and application are in sync.

waitForAlertNotPresent

waitForAlertPresent

waitForElementPresent

waitForElementNotPresent

waitForTextPresent

waitForTextNotPresent

waitForPageToLoad

waitForFrameToLoad

# Selenium Pattern Matching
□ This section deals with how to work with regular expressions using IDE. Like locators, patterns are a type of parameter frequently used by Selenium. It allows users to describe patterns with the help of special characters. Many a time, the text that we would like to verify are dynamic; in that case, pattern matching is very useful.

Pattern matching is used with all the verification point commands - verifyTextPresent, verifyTitle, verifyAlert, assertConfirmation, verifyText, and verifyPrompt. There are three ways to define a pattern −

Globbing

Globbing

regular expressions, and exact patterns.

Most techies who have used file matching patterns in Linux or Windows while searching for a certain file type like *.doc or *.jpg. would be familiar with term "globbing"

Globbing in Selenium supports only three special characters: *, ?, and [ ].

• * − matches any number of characters.

• ? − matches a single character.

□ [ ] − called a character class, lets you match any single character found within the brackets. [0- 9] matches any digit.

To specify a glob in a Selenium command, prefix the pattern with the keyword 'glob:'. For example, if you would like to search for the texts "tax year 2013" or "tax year 2014", then you can use the golb "tax year *" as shown below.

However the usage of "glob:" is optional while specifying a text pattern because globbing patterns are the default in Selenium.


<img width="875" height="281" alt="435376826-b2564055-23cb-446b-b830-6a35052f59c5" src="https://github.com/user-attachments/assets/9668f39e-546e-441f-9369-e91378f5e78c" />


ExactPatterns
Patterns with the prefix 'exact:' will match the given text as it is. Let us say, the user wants an exact match with
the value string, i.e., without the glob operator doing its work, one can use the 'exact' pattern as shown below. In this example the operator '*' will work as a normal character rather than apattern- matching wildcard character.


<img width="879" height="286" alt="435376895-c046e6b1-3f7b-4968-b4fb-b40fb049e5b7" src="https://github.com/user-attachments/assets/238b3895-a982-49df-bb24-384786b6d70a" />

# RegularExpressions
Regular expressions are the most useful among the pattern matching techniques available. Selenium supports
the complete set of regular expression patterns that Javascript supports. Hence the users are no longer limited
by *, ? and [] globbing patterns.

To use RegEx patterns, we need to prefix with either "regexp:" or "regexpi:". The prefix "regexpi" is
case- insensitive. The glob: and the exact: patterns are the subsets of the Regular Expression patterns.
Everything that is done with glob: or exact: can be accomplished with the help of RegExp.

# Example
For example, the following will test if an input field with the id 'name' contains the string 'tax year', 'Tax Year',
or 'tax Year'


<img width="797" height="253" alt="435376968-8b24410d-05cd-4ca1-93af-c0498eef9179" src="https://github.com/user-attachments/assets/cd31930c-9e9d-42eb-97ea-c9d28d99b683" />


# Selenium User Extensions
The Java script that allows users to customize or add new functionality.

It is easy to extend Selenium IDE by adding customized actions, assertions, and locator-strategies. It is done with the help of JavaScript by adding methods to the Selenium object prototype. On startup, Selenium will automatically look through the methods on these prototypes, using name patterns to recognize which ones are actions, assertions, and locators.

Let us add a 'while' Loop in Selenium IDE with the help of JavaScript.

Step 1 − To add the js file, first navigate to https://github.com/darrenderidder/sideflow/blob/master/sideflow.js and copy the script and place save it as 'sideflow.js' in your local folder as shown below

<img width="716" height="185" alt="435377027-554e8b6b-16c2-4366-86bb-859da0038624" src="https://github.com/user-attachments/assets/17ff3df1-0510-425c-a731-3f8c99a24e16" />

Step 2 − Now launch 'Selenium IDE' and navigate to "Options" >> "Options" as shown below.

<img width="945" height="270" alt="435377052-b03e8937-c506-4604-a814-cfb9b5584c21" src="https://github.com/user-attachments/assets/c561481a-8369-4a3a-86ea-33896e38d527" />

Step 3 − Click the 'Browse' button under 'Selenium Core Extensions' area and point to the js file that we have saved in Step 1.


<img width="805" height="314" alt="435377082-cc4b7c64-99bf-4f2b-b43a-ee390b6bfff6" src="https://github.com/user-attachments/assets/3189ebf3-5a4b-43cb-93a5-8294ce9ef958" />


Step 4 − Restart Selenium IDE.

Step 5 − Now you will have access to a few more commands such as "Label", "While" etc.

Step 6 − Now we will be able to create a While loop within Selenium IDE and it will execute as shown below.

<img width="941" height="424" alt="435377149-72f6fa67-f830-470e-a01a-61906e2a04c2" src="https://github.com/user-attachments/assets/ebe39411-3d9a-4a18-8e27-a05e225c131d" />


# Result:
Thus, the study of selenium web testing tool is conducted and the results were noted.
