# LockedMe
LockedMe - Virtual Key for Repositories

Simple Java Console based program to allows user to input menu options for 

* Displaying File/Folder structure. 
* Search for File/Folder recursively.
* Add/Delete File/Folder recursively.

## View project locally

To try out the project in your local machine:

* clone this repository using `git clone `
* Open the folder from Eclipse/IntelliJ 
* Open LockedMeMain.java and Run


## Component Hierarchy

| File    |  Description           |
|-----------------|-------------------         |
| `LockedMeMain.java` | This component contains the Main method. It's the entry point of the program. |
| `MenuOptions.java` | This component contains methods for displaying menu options. |
| `HandleOptions.java` | This component contains methods for handling different options from user input and calls respective methods from FileOperations. |
| `FileOperations.java` | This component defines all the operations required for displaying, searching, deleting and adding files/folder.|

