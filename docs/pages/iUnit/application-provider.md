
# Application Provider Mode

The Application Provider mode is used to create, manage and run Test Cases and Test Suites. To do so, the Application Provider mode has to be linked to the Repository.

The way we have iUnit integrated with ARCAD via the Application Provider mode is also available in the Visual Studio Code version.  
When the iUnit repository is linked with an ARCAD version, it should display the **Versions** node and if a specific version has child versions (it is the case of a node version), the **Versions** node should be displayed too.

The automatic actions settings as it is in RDi mode, should be active in Visual Studio Code too.

## Link the Application to the Repository

Follow the subsequent steps to link the Application to the Repository.

**Step 1** &nbsp; Right-click on the Repository you want to link to the Application to open the context menu.

**Step 2** &nbsp; Select the **Link Application** option from the Context Menu.  

**Step 3** &nbsp; A new window opens to let you select the **SCM Provider**.

![application-context](./../../media/link-application-window.png)

**Step 4** &nbsp; Select the SCM Provider and press **Enter**.  

**Step 5** &nbsp; A new window opens to let you select the **Application**.

![application-context](./../../media/choose-application-window-2.png)

**Step 6** &nbsp; Select the Application and press **Enter**.  

**Result** &nbsp; The Application is successfully linked to the Repository.
   
> **Note**    
> Linking the Application to the Repository clears all the Libraries. It also adds the application library to the Repository and re-initializes the Repository.