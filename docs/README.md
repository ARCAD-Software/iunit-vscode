# ARCAD iUnit VSCode extension
![https://marketplace.visualstudio.com/items?itemName=arcadsoftware.arcad-iunit](https://img.shields.io/visual-studio-marketplace/v/arcadsoftware.arcad-iunit)
![https://marketplace.visualstudio.com/items?itemName=arcadsoftware.arcad-iunit](https://img.shields.io/visual-studio-marketplace/i/arcadsoftware.arcad-iunit)

<!-- About the iUnit VScode Extension -->
## About
The ARCAD-iUnit VSCode extension allows you to create unit tests automatically from IBM i source code in just a few clicks in VS Code.

![iunit-intro](../media/iunit-intro.png)

<!-- Prerequisites -->
## Prerequisites
An up and running ARCAD-iUnit server, version 24.0 or above. The server's installation package can be downloaded from [ARCAD's Customer Portal](https://portal.arcadsoftware.com/).


<!-- Installation -->
## Installation
### Install the VSCode Extension (Using VSIX File)
1. Download and install the `ARCAD-iUnit` extension from [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=arcadsoftware.arcad-iunit).
2. Open Visual Studio Code.
3. Navigate to the Extensions view by clicking on the Extensions icon in the sidebar or pressing Ctrl+Shift+X.

![Extensions](../media/extensions.png)

4. Click the three dot icon (...) in the upper-right corner of the Extensions view and select "Install from VSIX."

![Install from VSIX](../media/install-from-vsix.png)

5. Locate and select the downloaded VSIX file.

![Select VSIX](../media/select-vsix.png)

6. Click the "Install" button to install the extension.

![Install](../media/install.png)

### Add the Required AFS Server Configuration

After installation, open your project or workspace in Visual Studio Code.

Access the extension's settings by clicking on the gear icon in the bottom left corner (Settings) and then selecting "Extensions" > "iUnit Extension."

![Settings](../media/settings.png)

Enter the required AFS server configuration, including Server address, Port, Host Name , Trace and other required fields.

![Settings](../media/settings.png)

### Connect to AFS

Once the configuration is set, click the "Connect" button in the iUnitExtension panel.

This will establish a connection to the AFS server using the provided configuration.

![Connect](../media/connect.png)

Note* : For a detailed walkthrough of iUnit, refer to the Visual Studio Code Walkthrough by clicking on Get Started.

![Get Started](../media/get-started.png)

<!-- Features -->
## Features
### Create Test Cases
Create test cases from source code in just a few clicks.

![Create Test Cases](../media/create-test-cases.png)

### Create Test Suites

Create test suites from source code in just a few clicks.

![Create Test Suites](../media/create-test-suites.png)

### Run Test Cases

Run test cases from source code in just a few clicks.

![Run Test Cases](../media/run-test-cases.png)


<!-- License -->
## License
[MIT](https://choosealicense.com/licenses/mit/)

<!-- Contact -->
## Contact
ARCAD Software - [https://www.arcadsoftware.com/contact/](https://www.arcadsoftware.com/contact/)

