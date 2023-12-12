# Test cases

## Creating a test case 
ARCAD iUnit simplifies the creation of test cases by retrieving all the procedures and parameters for the parent object targeted by the test case. The test cases can be created manually or by using an existing ARCAD iUnit repository depending on the object details. 

(-sc-)

1. In the Test Cases Node, click the (+)  Add Test Case icon

(-sc-)

2. Click Select Object from existing iUnit Repository. Click Next > to continue

(-sc-)

3. Select the object from the list of objects referenced for the repository. 

(-sc-)

(-sc-)

(-sc-) 

The name of the procedure(s) will be automatically generated based on the selected object and procedure. However, if needed, you can edit the generated name to provide a more descriptive or meaningful identifier for the procedure being Tested.

>note  
Skip Source Parsing Allows you to skip the Parsing of Selected Procedure Source member.

4. Click Enter.

The Test case will be created and displayed in the Explorer.

## Editing Test Cases
To edit a test case, right-click on it and select Edit, select it and click the edit icon in the toolbar, or double click on it.  

(-sc-)

Add Before /After Test Case Execution Command  

(-sc-)

Enter Command name eg.

        (DLTDTAARA DTAARA(QTEMP/TEST)

Click on (+) icon  

## Create Expected Result
Right click on the Test case you want to create the expected Result. Then click on the Create Expected Result button as shown below.

(-sc-)

(-sc-)

Clicking on the save button will the expected result of the selected test case

## Change Expected Result
When working with a test case, expected results may need to be changed.

You can use this option to access the expected result again. Follow the subsequent steps to change the expected result of a test case. 

1. Right-click on a test case and click the **Change Expected Result** option. The Input Parameter Definition dialog opens. 
2. Change the input or output values for the parameters. Click OK. 

The expected result has changed.

## Executing Test Cases 
To execute a Test case after setting its expected result, you can right-click on the Test case and select the "Change Base Result" option as shown below.  

(-sc-)

A dialog displays a simplified view of the execution result for the test case. Complete results are available in a dedicated view.  

(-sc-)

## Understanding Test Results

The Execution Results : The results obtained when Executing the Test case.  

To view the outcome, expand the desired Test Case Node where the execution details will be displayed. A red icon signifies a failed test case, while a green icon indicates a successful pass.  

(-sc-)

## Viewing the Code Coverage Report

(-sc-)

Code coverage analysis is the process of finding areas of a program not covered by a set of test cases. You can create additional test cases to increase the coverage.  

Follow the subsequent steps to display the code coverage report for an individual test case.

1. Select a test case in the Test Cases search view and click the  Result icon or select Show Results > All in the contextual menu. 
2. click on the Code Coverage icon in front of the Execution Result. 

The code coverage report is displayed in the editor. 

## Viewing the Test Execution log

(-sc-)

1. Select a test case in the Test Cases search view and click the  Result icon or select Show Results > All in the contextual menu. 
2. Right-click on a result and select Show IBM i logs. The IBM i log is displayed in the editor.

