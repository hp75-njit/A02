# PART 1: WebStorm 

Download Link: https://www.jetbrains.com/webstorm/download/

**Opening a Project**

**To open a project**:<br>
	-	On the Welcome Screen, click Open and then select the folder with your application.
**To check out a project from a version control system**:
1.    Click Get from VCS on the Welcome screen.
	-	Alternatively, select File | New | Project from Version Control or Git | Clone… from the main menu.
	-	Instead of Git in the main menu, there may be other Version Control Systems that is associated with your project.
2.    In the dialog that opens, select your version control system from the list and specify the repository to check out the application sources from. 
 
**To create an empty WebStorm project**:
1. Click Create New Project on the Welcome screen or select File | New | Project from the main menu. The New Project dialog opens.
2. In the left-hand pane, choose Empty Project. In the right-hand pane, specify the application folder and click Create. 

**Creating a File in the Project**
- In the Project tool window, select the folder where you want to create a new file and press Option + Insert.
- Alternatively, you can select New from the context menu of the selection and then choose the file type from the list.

**Completing the code**
WebStorm automatically completes keywords, symbols from standard language API's and from the project dependencies. Press Ctrl + Space to get the code completion options for the current context, the icon next to each suggested member indicates its type.

**Run the application**
- Create a run configuration of the type that fits your app and click Run.
- In some cases, you can run your app or file without creating a run configuration, WebStorm can do it for you. For example, to run any file with Node, just choose Run <file_name> on its context menu or press Ctrl + Shift. This also works for an HTML file, WebStorm just opens it in the browser.
- If your project has an npm script that starts your application in the development mode or builds it, just open your project package.json in the editor, click Run in the gutter next to the start task, and choose Run 'start' from the list.
