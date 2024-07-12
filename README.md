[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15401833&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   - ANSWER
   - 1. Visit the official VS Code download page and click on the "Windows" download button.
     2. Run the installer and accept the license terms and conditions during installations.
     3. Select the installation location (default is C:\Users\HP\AppData\Local\Programs\Microsoft VS Code). Choose whether to have a desktop icon.
     4. Launch VS Code and select a theme and a language for the editor
     Prerequisites:
Ensure your system meets the following requirements:
CPU with a clock speed of 1 GHz or more.
At least 1 GB of RAM.
1 GB of available storage.
Display resolution of 1024x768 pixels or higher
   

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   - ANSWER
1. Install relevant extensions based on your programming languages and work flow.
2. Choose a color theme that suits your prefrence
3. Configure workspace-specific settings (if needed) by creating a .vscode/settings.json file in your project folder.
4. Ensure IntelliSense (code completions, suggestions) is enabled for your language.
5. Connect VS Code to your Git repository.
    

6. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
ANSWER
Activity Bar
- Located on the far left-hand side. Allows you to switch between different views, such as Explorer, Search, Version Control, Debug, and Extensions
Side Bar
- Provides context-specific information and tools.
Editor Group
- This is the main area where you edit your files.
Status Bar
- Provides information about the opened project and the files being currently edited.


7. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
ANSWER
- This is a tool that allows one to access various features, commands, and settings directly via keyboard shortcuts. It can be accessed by using the F1 key. The command palette can be used for activities such as running tasks, Installing extensions and configuring settings.
https://code.visualstudio.com/docs/getstarted/userinterface


8. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
ANSWER
- The role of extensions in VS Code is to add tools to support your development workflow. User can find extensions by openning VS Code and clicking on the Extensions icon in the activity bar. Click the install button that is next to the extension you desire to use. One uses the Manage button to configure or uninstall the extension. Example of an extension used in Web Devepolmemt is HTML CSS Support: Provides autocompletion and syntax highlighting for HTML and CSS.
https://code.visualstudio.com/docs/editor/extension-marketplace


9. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
ANSWER
- To open the intergrated terminal, you can use the menu: Terminal>New Terminal.
- Advantages of the Integrated Terminal:
1. Seamless Integration: Execute commands (e.g., mkdir, git) directly within VS Code, enhancing productivity.
2. Git Integration: Easily run Git commands (commit, push, branch management) without leaving the editor environment.
3. Multiple Instances: Manage different tasks simultaneously by having multiple terminal instances.
4. Shell Integration: Track where commands are run with decorations and scrollbar indicators.
5. Customizable Shells: Use various shells installed on your machine (configurable in terminal profiles).
https://code.visualstudio.com/docs/terminal/basics


10. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
ANSWER
- To open a folder in VS Code, use the File > Open Folder… menu. Once you open a folder, VS Code automatically treats it as a workspace. It keeps track of your open files, editor layout, and other configurations. You can create, delete, and rename files and folders directly within the Explorer view. Use the Explorer view to browse and manage files.
- https://code.visualstudio.com/docs/editor/workspaces

     
11. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
ANSWER
- To open Setting s Editor, navigate to File > Preferences > Settings. To change the theme: Search for “Color Theme” in the Settings editor. Choose a theme from the dropdown. To chang ethe font: Search for “Font Size” in the Settings editor.
Modify the font size. For Keybinding: Search for “Keybindings” in the Settings editor. Customize keybindings.
https://code.visualstudio.com/docs/getstarted/settings


12. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
ANSWER
- Click the Run and Debug icon in the Activity Bar on the side of VS Code. VS Code uses a launch.json file to configure debugging settings. Edit the generated launch.json file. Specify the entry point. Click the editor margin to toggle breakpoints. Press F5 or click the green play button. Some of the key debugging features are as follows: Watch, Call stack, Hover, and Debug Console.
- https://code.visualstudio.com/docs/introvideos/debugging


13. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
ANSWER  
  - Ensure you have Git installed on your computer. Restart VS Code after installing Git.
  - Open an existing or new folder in VS Code. In the Source Control view, click Initialize Repository. This creates a new Git repository in the folder.
  - Use the source control view to stage changes and add a commit message. Press ctrl+Enter to commit.
  - Click Publish to GitHub in the Source Control view. Choose a name, description, and privacy settings for the repository. VS Code pushes your code to GitHub.
https://code.visualstudio.com/docs/sourcecontrol/intro-to-git


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

