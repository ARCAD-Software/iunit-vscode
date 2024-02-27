# Getting Started

## Prerequisites
Before you start using the iUnit extension for Visual Studio Code, make sure you have an up and running ARCAD iUnit server (a version 24.0 or above).

> __NOTE__  
> The server's installation package can be downloaded from the [ARCAD's Customer Portal](https://portal.arcadsoftware.com/).

## Installing  the VSCode Extension (Using VSIX File)

**Step 1** &nbsp; Download and install the `ARCAD iUnit` extension from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=arcadsoftware.arcad-iunit).

**Step 2** &nbsp; Once installed, open Visual Studio Code and navigate to the **Extensions** view by clicking the **Extensions** icon in the sidebar or pressing `Ctrl + Shift + X`.

**Step 3** &nbsp; Click the three dot icon **(...)** in the upper-right corner of the Extensions view and select the **Install from VSIX** option.

**Step 4** &nbsp; Locate and select the downloaded VSIX file.

**Step 5** &nbsp; Click the **Install** button to launch the installation of the extension.

## Add the Required AFS Server Configuration

After the installation is completed, open your project or workspace in Visual Studio Code.  
Access the extension's settings by clicking on the Settings icon and then selecting **Extension" > iUnit Extension**.  
Enter the required AFS server configuration:
- Server address,
- Port,
- Host Name,
- Trace.

## Connect to AFS

Once the configuration is set, click the **Connect** button in the **iUnitExtension** panel.
This establishes a connection to the AFS server using the provided configuration.

> __Note__  
> For a detailed walkthrough of iUnit, refer to the Visual Studio Code Walkthrough by clicking on **Get Started**.