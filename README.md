# WDIO_Appium
Mobile Automation using Webdriver IO




Instalation steps:-

	- Install Java and set environment variables in Path and JAVA_HOME.
	- Install Node for installing required dependencies
	- Download Android studio
	- Create a virtual device through Virtual Device Manager
	- Setup  Appium Desktop Inspector [Used for inspecting mobile app to get locators]
	- Install Appium
	- To the installation is done properly or not we can check with Appium-doctor cmd [Installing Appium-doctor  " npm i -g appium-doctor "]
	- Appium-doctor --android [To check appium android installed properly or not]
	- Appium driver install xcuitest
	- Appium driver install uiautomator2
	- Now to verify if its been installed, you can run - Appium driver list
    
	- Example:- will get details as below
	√ Listing available drivers are list
	- uiautomator2 [not installed]
	- xcuitest [not installed]
	- mac2 [not installed]
	- espresso [not installed]
	- safari [not installed]
	- gecko [not installed]
	- chromium [not installed]

npx appium driver install uiautomator2