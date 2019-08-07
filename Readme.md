# Gui testing application

This desktop application is for practicing DevOps. It was developed with java technology.<br />
In addtion it can be used to do the gui testing for this app - [wru_gradle](https://github.com/awt-03/wru_gradle.git).

## Getting Started

These instructions will get you started for getting a copy of the project and running on your local machine for development and testing purposes.

### Prerequisites

For Developing and Testing using an IDE.
- Eclipse IDE as Editor.
- Java 8

For Testing only.
- Browser like Google Chrome/Firefox, etc.

### Installing

**For Developing**.<br />
Get the app.
```
git clone -b develop https://github.com/awt-03/wru_gradle_gui_test.git
```
Update the dependencies for the project.
- Open the App with Eclise IDE.
- Once it was opened, Right Click on the projet.
- From context menu, do mouse Over to **"Gradle"** option.
- Click on **"Refresh Gradle Project"** option.
- Then the dependencies are going to be updated. Wait ultil it was done.
- Finally you can start to coding.

**For testing using an ide**.<br />
Get the app.
```
git clone -b develop https://github.com/awt-03/wru_gradle.git
```
Update the dependencies for the project.
- Open the App with Eclise IDE.
- Once it was opened, Right Click on the projet.
- From context menu, do mouse Over to **"Gradle"** option.
- Click on **"Refresh Gradle Project"** option.
- Then the dependencies are going to be updated. Wait ultil it was done.<br />
Build the application.
- Go to the Gradle view 
- Find the project, then with focus in the project display the drop down.
- Go to **"build"** folder display the drop down.
- Right click on **"build"** and click on **"Tun Gradle Tasks"**.
- Then the application is going to be builded. Wait ultil it was done.
- Finally the gui automated tests will be started.
- Review the Results in the console. (If it was passed or failed).

**For testing without using an ide**. <br />
Get the app.
```
git clone -b develop https://github.com/awt-03/wru_gradle.git
```
- Go to the project folder
```
cd wru_gradle
```
Update the dependencies and Build the application.
```
./gradlew build
```
- Finally the gui automated tests will be started.
- Review the Results in the console. (If it was passed or failed).

## Authors

* **Wara Rojas** - *Working on my project* - [Git Hub Repo] (https://github.com/awt-03/wru_gradle_gui_test.git)
See also [Web Application - Register User](https://github.com/awt-03/wru_gradle.git)

## License

This project is Open source licensed.
