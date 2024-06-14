[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15277603&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

 Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

1. locate the official Visual Studio Code website 
2.click on the Download for Windows button.
3.Choose the location where you want to install VS Code. By default, it installs in C:\Program Files\Microsoft VS Code
4.Once the download is complete, open the downloaded file
5. Read through the license  agreement, then check the box to accept the terms and click Next to Select Additional Tasks eg.add to path
6. Click Install to start the installation process. This may take a few minutes.
7.Once the installation is complete, you will see an option to Launch Visual Studio Code. Check this box and click Finish to open VS Code immediately.
8.After launching VS Code  Go to the Extensions view by clicking the Extensions icon .you can also access the settings to edit the vs code to your prefernce
9. Click File then Open Folder to start working on your projects.

prerequisites
internet connection
Operating System: Windows 11 (64-bit is recommended).
sufficient disk space



2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

 Initial Configurations
 1.Enable auto-save to avoid losing changes. 
2.Customize the appearance of your editor by selecting a theme.
3.Adjust the font size for better readability. 


Key Extensions
1.Python extension for Python development. 
2.Live Server
3.Prettier - Code Formatter which Automatically formats your code to maintain consistency.
4.dart
5,django
6.vscode extensions

settings

1.Sync Settings:Synchronize your settings,  extensions, and snippets across multiple machines.
2.Version Control:example when  you use Git,  You can configure user name and email by opening the integrated terminal and running:
   eg.git config --global user.name "carol"
      git config --global user.email "carol@gmail.com"






3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
a.ACTIVITY BAR ;Provides access to different views and functionalities. 
Components:
Search bar: Allows you to search for files  within your project.
Run and Debug: Provides debugging controls and configurations.
Extensions: Allows you to install, and manage extensions

b.SIDE BAR; Displays the contents and tools relevant to the selected Activity Bar item. 
Components:

Search View: Allows for searching across files in the project.
Debug View: Provides debugging controls
Extensions View: Lists installed extensions and provides a marketplace to discover new ones.

C.EDITOR GROUP; where one can edit your files.
Components:
Tabs: Each open file is represented by a tab at the top of the editor group


d.STATUS BAR: Displays important information about the current state of the editor and the workspace.
Components:
Current File Information: Displays details such as the current line and column number.
Language Mode: Indicates the language of the file and allows you to change the language mode.
Notification Icons: Provides quick access to notifications, problems, and the output pane




4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

*Command Palette is a  tool that provides quick access to a wide range of commands and features. 

*You can also access it either from the menu bar by navigating to View > Command Palette or by pressing Ctrl+Shift+P

Examples of Common Tasks

1.Opening Files
2.Installing Extensions
3.Changing Settings
4.Formatting Code
5.Running Git Commands


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
*extensions help in enhancing the functionality and customization of the editor to suit specific programming languages, tools and workflows for development environment


a.To Find Extensions Open the Extensions view by clicking on the Extensions icon in the Activity Bar  or by pressing Ctrl+Shift+X.

b.Install extension
1.use Extensions View:
Open the Extensions view and Search for the desired extension then Click the Install button toinstall.
2.use Command Palette:
Open the Command Palette then type Extensions, select to Install desired Extensions 
3. use of Terminal:
Use the command line to install extensions by typing the command of the extension you want to install.

c.Managing Extensions

1.Uninstall Extensions
2.Enable/Disable Extensions
3.Update Extensions

*Extensions include;
- prettier code formatter
-live server
-python


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   *To open the terminal you can use either ;
              -click Menu Bar then Go to View > Terminal in the menu bar.
              -press Press Ctrl+ ` 


  *How to use intergrated terminal
       -to  Navigating Between Terminals Use Ctrl+PageUp and Ctrl+PageDown to navigate between open terminal instances
       -to close the terminal use the delete icon
       -to create new terminal use the + icon in the terminal panel
        
   *advantages of interrated terminal compared to external terminal

1.The intergrated terminal is embedded within the VS Code interface, allowing one to easily switch between the terminal and your code unlike in external terminal
2.Itergrated terminal Runs code  scripts directly from the editor without leaving the code while external terminal Requires manual execution of commands and scripts, potentially increasing the risk of errors and inefficiencies.
3.Integrated Terminal can Access VS Code-specific tools and features easily while External Terminal has Limited integration with VS Code-specific tools and features.

 



7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?


(A) How to Creating Files and Folders

.Press Ctrl+Shift+P to open the Command Palette.Type  New File or  New Folder and select the respective command then Enter the name when prompted.
Opening Files and Folders

(B)To Open Files and folders
From File Menu, Go to File > Open File and navigate to the file you want to open.
Opening Folders:

From File Menu, Go to File > Open Folder and navigate to the desired folder.

(c) Managing Files and Folders

1. To Delete Files and Folders:
Right-click the file or folder in the Explorer view then Select  to Delete and confirm the action.
2. To Rename Files and Folders
Right-click the file or folder in the Explorer view then Select to  Rename, enter the new name, and press Enter.
3.To Move Files and Folders
Drag and drop the file or folder to the desired location within the Explorer view.
4.To copy Files and Folders
Right-click the file or folder and select Copy then Navigate to the destination, right-click, and select Paste.


*users can navigate between different files and directories efficiently
1.to navigate  Back and Forward:
Use Alt+Left Arrow to go back to the previous location and Alt+Right Arrow to go forward.
2.to Quick Open:
Press Ctrl+P to open Quick Open then Start typing the file name
3.to use the  integrated Terminal:
Use the integrated terminal (Ctrl+' ) to navigate directories and open files using command-line operations like cd





8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
1.the Settings UI
Open the Settings UI then Go to File > Preferences > Settings
Use the search bar to find specific settings by name or description.

customize settings

*Search for "theme".
In the "Color Theme" dropdown, select the theme you want
*Search for "font size".
Adjust the "Editor: Font Size" setting using the dropdown or input box
*keybindings
Go to File > Preferences > Keyboard Shortcuts or use the shortcut Ctrl+K Ctrl+S.


2.Settings JSON
navigate to the settings.json file located in Windows: %APPDATA%\Code\User\settings.json
*keybindings
open the Command Palette with Ctrl+Shift+P 
Type Preferences then Open Keyboard Shortcuts (JSON) and select 






9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?



1.Open VS Code and navigate to your project folder using File > Open Folder.

2.Click on the Debugging icon in the Activity Bar then Click on the gear icon  and then select the environment you want to debug for example Node.js

3.Configure Launch Settings (if necessary)
Open launch.json and modify configurations based on your project setup. For example command-line arguments.

4.Open the file containing your code.

5. Start Debugging click the debug button  in the Debug view VS Code will launch the debugger and start running your program, pausing at the first breakpoint encountered.


Debugging Features 
1.Breakpoints:breakpoints help your code to pause execution and inspect variables and state.
2.Debug Console:Views and interact with console output 
3.Variable Inspection:variables in your code help to inspect them in the Variables view.
5.Debugging Configurations




10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 1.Open Git Bash and navigate to your project:
cd /c/Users/YourUsername/Projects/YourProjectFolder
2.Initialize the Git repository:
git init
3.Open the project in VS Code:
code .
4.Stage and commit changes:
git add .
5.git commit -m "Initial commit"
6.Create a repository on GitHub and copy the URL and Link your local repository to GitHub:
git remote add origin https://github.com/username/repository.git
7.Push changes to GitHub:
git push -u origin master







 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

