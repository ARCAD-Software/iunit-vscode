# Setting up the JUnit testing environment

In order to execute unit-tests on your applications via JUnit, you must first set up the testing environment. Setting up the environment includes creating projects and managing repositories and versions.

ARCAD iUnit projects are used to create and run unit test cases via JUnit.

![junit-image](./../../media/junit.png)  
_Working with JUnit_

## Prerequisites
Before you start, it is necessary to habve prior knowledge of JUnit testing methods and technical vocabulary. This documentation does not cover JUnit technology.

> **Reference**  
For more information about JUnit, refer to the [documentation](https://help-arcad-iunit.arcadsoftware.com/Topics/JUnit/JUnit-Intro.html).

Make sure that the [Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) is installed in your Visual Studio Code IDE to use the JUnit testing features.

![extension-image](./../../media/extension-pack-for-java.png)  
_Extension Pack for Java_

## Exporting the ARCAD iUnit project to Local Workspace

> **Note:**  
To run the JUnit-iUnit project, you have to manually export the ARCAD iUnit project to the Workspace.

To export the ARCAD iUnit project in the Workspace, right-click on the repository and click the **Export to ARCAD iUnit Project** option from the ARCAD iUnit Extension.  
The ARCAD iUnit project is then created with the same name as the repository and added to the current Workspace in the Visial Studio Code IDE.

![export-to-iunit-project-image](./../../media/junit-export-to-iunit-project.png)

The JUnit extension detects automatically the ARCAD iUnit project and displayd the test cases in the **Test Explorer** view.  
You can execute the test cases directly from the **Test Explorer** view and the test results are shown in the **Test Results** window.









