# Repositories
## Creating new repository
**Step 1**   Click on the **(+)** icon on the **Repository Explorer** to open the Repository creation page.

**Step 2**   Set the new Repository's properties:  
> * Set the name of the Repository,  
> * _[Optional]_ Enter a description of this new Repository,  
> * Set the new Repository's ASP Group,  
> * Add libraries to the Repository.  
    
![create_repo](./../../media/add-Repository.png)
_Creating a new Repository_

**Step 3** Click the **Add Repository** button.  

**Result** The Repository is successfully created and auto-initialized. The new Repository is then displayed in the repository list in the **ARCAD iUnit Explorer** view.

## Editing a repository
You can edit the properties of any created Repository later on, such as Libraries, Execution Log or Code Coverage (if not set while creating the Repository).

To do so, right-click on the **Repository** node from the **ARCAD iUnit Explorer** view to open the Repository in Edit Mode and make changes.

## Initializing repositories
Initializing a repository allows you to load all the objects and sources from the libraries defined in the repository.

When you create a new Repository, it is auto-initialized. However, when you add a new Library to an existing Repository or some of the sources/objects have been changed and you want to rebuild the repository, it requires the re-initialization of the repository.

To do so, right-click on the Repository to initialize, then click on **Initialize** option.

The **Refresh Repository** option is lightweight processing to synchronize day to day source/object changes to have corresponding reflection in iUnit repository. It only works on added/deleted/modified objects and sources and doesn't build the entire repository.

![initialize_repo](./../../media/init-repo.png")  
_Initialize a  Repository_

## Adding Repositories to the Explorer
If you previously added Repositories with the same configuration, they are automatically loaded into the AFS Extension.

If that is not the case, you have to manually add the Repositories to the Explorer.

![adding_repo](./../../media/add-repo-to-explorer.png)  
_Adding a  Repository to the Explorer_

Follow the subsequent steps to add a Repository to the Explorer.

**Step 1** Click on the **Add Repository to Explorer** button in the iUnit Extension panel to display the Repositories of the connected Server.

**Step 2**  Select the Repository you want to work with to add them to the Explorer.

![list_repo](./../../media/add-repo-to-explorer-list.png)  
_Select the Repository to work from the List of iUnit Repositories_


**Result** The selected Repositories are successfully added to the iUnit Repository Explorer, allowing you to access and manage its Test Cases, Test Suites and other functionalities.