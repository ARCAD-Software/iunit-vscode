# Application Provider Mode

The Application Provider mode is used when iUnit repository is created from an Arcad application or any other change management system integrated with iUnit. 

When the iUnit repository is linked with an ARCAD application, it would display the **Versions** node. Subsequently, if a version has child versions (e.g. the case of a node version), the **Versions** node would be displayed for the parent node.

When the repository is created and linked to an Arcad application, the additional settings for automatic actions (e.g. auto checkout, auto promote etc) can be set depending on the requirement.

## Link the Application to the Repository

Follow the subsequent steps to link the Application to the Repository.

**Step 1**   Right-click on the Repository you want to link to the Application to open the context menu.

**Step 2**   Select the **Link Application** option from the Context Menu.

**Step 3**   A new window opens to let you select the **SCM Provider**.

![application-context](./../../media/link-application-window.png)

**Step 4**   Select the SCM Provider and press **Enter**.

**Step 5**   A new window opens to let you select the **Application**.

![application-context](./../../media/choose-application-window-2.png)

**Step 6**   Select the Application and press **Enter**.

**Result**   The Application is successfully linked to the Repository.

> **Note**  
> Linking the Application to the Repository clears the library setting (if already set for that iUnit repository). It adds the operational libraries of the application to the Repository and initializes it.

<!-- TODO: udpate the application settings page -->
## Update Skipper Application Settings

Follow the subsequent steps to update the Skipper Application settings.

**Step 1** Right-click on the Repository you want to update the settings for.

**Step 2** Select the **Skipper Application Settings** option from the Context Menu.

![application-context](./../../media/update-skipper-application-settings-context.png)

**Step 3**  A new window opens to let you update the Skipper Application settings for Automation.

![application-context](./../../media/update-skipper-application-settings-window.png)

**Step 4**   Update the Skipper Application settings by clicking the Save Icon on the window **Enter**.


## Viewing Linked Versions in the Repository

> __Note__  
> Once the Repository is linked to an application and initialized, an extra node labeled 'Versions' will appear in the tree view. This node will contain all the linked versions. If a version has child versions, the Version Repository Node will be displayed under the version node. 

### Adding Version Repository Manually

If the **Auto Version Repository Creation** setting is not selected in the Skipper application, or if a version has already been created in skipper, follow these steps to manually add a version repository in iunit:

**Step 1** Click on the icon of **Add Version**. This will display a list of available version repositories.
 
 ![application-context](./../../media/add-version-repository.png)
  
**Step 2**   Select the version repository you want to add and click on the 'Add' button.

![application-context](./../../media/select-version-repository.png)

**Step 3**   The version repository will be added to the repository.

![application-context](./../../media/version-repository.png)


### Checkout Test Case in Version Repository

To checkout a Test Case in the Version Repository, follow these steps:

**Step 1**   Click on the Test Case checkout icon given on the Test Cases Node.

![application-context](./../../media/checkout-test-case.png)

**Step 2**   Choose Test Case to checkout and click on the 'Ok' button.

![application-context](./../../media/checkout-test-case-list.png)

**Result**   The Test Case is successfully checked out in the Version Repository.

> __Note__
> To Successfully checkout a Test Case, the Test Case Object must be checked out in the Version and compiled.