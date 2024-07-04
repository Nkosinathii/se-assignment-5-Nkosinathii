[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15364682&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Firstly you need to make sure you have windows 11 system.
   1.1. Go to google website and type in "code.visualstudio.com" in the search tap. Once you are inside, you can proceed to click the download for windows tap.

   1.2. Run the installer. Find the downloaded file named "vscodesetup.exe" and double click on it and proceed to accept the license agreement.

   1.3.Choose intallation options.
   1.3.1. Pick the installation folder (default)
   1.3.2. Check the options to add VS Code to your PATH and create a desktop icon.
   1.3.3. Click instsll tap.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   2.1. Setup Theme and Font by going into File> Preferances> Colour theme> Settings and Font size.

   2.2. You enable autosave by clicking File> Preferances> Settings, then search autosave.

   2.3. Adjust Tap size and formatting in the settings you can search Tap size and set your preferance.

   2.4. Customize Terminal by going to settings and search Terminal integrated shell and set your prefered shell between powershell and git bash.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   3.1. Activity Bar
   -Location: On the far left.
   -Purpose: Gives quick access to different views like Explorer, Search, Source Control, Run and Debug, and Extensions.

   3.2.Side Bar
   -Location: Next to the Activity Bar on the left.
   -Purpose: Displays the contents of the selected view from the Activity Bar, such as your file explorer, search results, or version control.

   3.3.Editor Group
   -Location: Center of the screen.
   -Purpose: Where you open and edit your files. You can have multiple editor tabs open and even split the editor to view and edit files side-by-side.

   3.4.Status Bar
   -Location: Bottom of the window.
   -Purpose: Shows useful information about your current workspace, like the Git branch, encoding, line number, and any warnings or errors.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   4.1. Open a file
   -Type Open File to quickly open any file.

   4.2. Change colour theme
   -Type Color Theme to switch how VS Code looks.

   4.3. Install etensions
   -Type Install Extensions to add cool features to VS Code.

   4.4. Run code
   -Type Run to run your code.

   4.5. Git commands
   -Type Git to see options like commit, push, or pull.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   5.1. Finding etensions
   -You can find extensions in VS Code by clicking on the Extensions icon on the left side (it looks like four squares). Here, you can search for extensions by typing what you need, like "HTML" or "Python".

   5.2. Installing extensions
   -Once you find an extension you like, click "Install" to add it to VS Code. Some extensions might ask you to reload VS Code to start working.

   5.3. Managing extensions
   -Managing extensions means you can turn them on or off, update them, or even remove them if you don't need them anymore. You can do this all from the Extensions view.

   Examples of essential extensions for web development:
   5.4. Live server
   -This extension helps you see your web pages live in your browser as you edit them. It's like having your changes appear instantly.

   5.5. Prettier code formatter
   -Prettier makes your code look nice automatically. It fixes the formatting so your code is easy to read and looks clean.

   5.6. ESLint
   -ESLint helps you write better JavaScript code by catching mistakes and showing you how to fix them. It helps you keep your code clean and error-free.

   5.7. GitLens
   -GitLens makes working with Git easier. It helps you see who changed what in your code, when they did it, and why. It’s like having a detective for your code history.

   5.8. CSS Peek
   -CSS Peek lets you quickly jump from your HTML to the CSS that styles it. It helps you find and edit styles faster.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   6.1. Opening the integrated terminal
   -Click on View in the top menu and select Terminal Or use the shortcut: Ctrl + (backtick) on Windows.

   6.2. Using the terminal
   -You can run commands just like you would in any other terminal. For example, type ls (or dir on Windows) to list files, git status to check Git status, or npm start to run a Node.js project.

   6.3. Switching and creating terminals
   -To open a new terminal instance, click the + icon in the terminal pane or use the shortcut Ctrl + Shift + (backtick) on Windows.
   -You can switch between multiple terminal instances using the dropdown menu in the terminal pane.

   Advantages of using the integrated terminals:
   6.4. Convenience
   -The integrated terminal is built right into VS Code, so you don't need to switch between windows or applications. Everything is in one place.

   6.5. Contex awareness
   -The terminal opens in the root of your project directory, so you don't have to navigate to your project folder manually every time.

   6.6. Synchronization
   -Commands run in the integrated terminal can directly interact with your open files and projects, making tasks like running scripts, using version control, and debugging more seamless.

   6.7. Extension integration
   -Many VS Code extensions work directly with the integrated terminal, providing a smoother workflow for tasks like testing, linting, and deploying code.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   7.1. Create New File
   -Click the New File icon in the Explorer view on the left (it looks like a paper with a plus sign).

   7.2. Create New Folder.
   -Right-click in the Explorer view and select New Folder.
   -Name your folder and press Enter.

   7.3. Open a Folder.
   -Click File > Open Folder... and select the folder you want to open.

   7.4. Rename.
   -Right-click on a file or folder in the Explorer view and select Rename.

   7.5. Delete.
   -Right-click on a file or folder and select Delete.

   7.6. Move.
   -Drag and drop the file or folder to the desired location within the Explorer view.

   Efficient Navigation Between Files and Directories:

   7.7. Quick Open.
   -Press Ctrl + P (Windows/Linux) or Cmd + P (Mac) to open the Quick Open menu. Start typing the name of the file you want to open and select it from the list.

   7.8. Go to Symbol.
   -Press Ctrl + Shift + O (Windows/Linux) or Cmd + Shift + O (Mac) to navigate to a specific symbol (function, variable, etc.) within the current file.

   7.9. Go to Definition.
   -Right-click on a symbol in your code and select Go to Definition, or press F12.

   7.10. Breadcrumb Navigation.
   -Use the breadcrumb navigation bar at the top of the editor to quickly move between files and folders in your project hierarchy.

   7.11. Explorer View.
   -Use the Explorer view on the left to navigate through your project’s files and folders. Click on a file to open it in the editor.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   8.1. Open Setings.
   -Click on File > Preferences > Settings.

   Examples of Customizing Settings.

   8.2. Change the Theme.
   -Open the Command Palette by pressing Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac)
   -Type Color Theme and select Preferences: Color Theme.
   -Choose a theme from the list.

   8.3. Change Font Size.
   -Open the Settings menu.
   -In the search bar at the top, type Font Size.
   -Adjust the Editor: Font Size setting to your preferred size (e.g., 14).

   8.4. Change Keybindings.
   -Click on File > Preferences > Keyboard Shortcuts.
   -Search for the command you want to change, click the pencil icon next to it, and press the new key combination you want to assign.



9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   9.1. Open a Project.
   -Open VS Code and open your project folder by clicking File > Open Folder....

   9.2. Create a Simple Program.
   -Create a new file (e.g., app.js for a JavaScript program) and write some code.

   9.3. Configure Debugging.
   -Click on the Run and Debug icon on the left sidebar or press Ctrl + Shift + D (Windows/Linux) or Cmd + Shift + D (Mac).
   -Click on create a launch.json file in the Run and Debug view.
   -Select the environment you are working with (e.g., Node.js for a JavaScript/TypeScript application).
   -A launch.json file will be created with default settings.

   9.4. Set Breaking Points.
   -Open the file you want to debug
   -Click in the gutter to the left of the line numbers to set a breakpoint (a red dot will appear).

   9.5. Start Debugging.
   -In the Run and Debug view, select your configuration (e.g., Launch Program) and click the green play button or press F5.

   Key Debugging Features in VS Code:

   9.6. Breaking Points.
   -Set breakpoints by clicking in the gutter next to the line numbers. Breakpoints allow you to pause the execution of your code at specific points.

   9.7. Step Through Code.
   -Use the step controls to navigate through your code:
   -Step Over (F10): Move to the next line of code.
   -Step Into (F11): Enter the function being called.
   -Step Out (Shift + F11): Exit the current function.

   9.8. Variables View.
   -See the current values of variables in the Variables pane. This helps you understand how your data is changing as your program runs.

   9.10. Watch Expressions.
   -Add expressions to the Watch pane to monitor their values as you debug.

   9.11. Call Stack.
   -View the call stack to see the order of function calls that led to the current point in the execution.

   9.12. Debug Console.
   -Use the Debug Console to evaluate expressions and run commands in the context of your program.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    10.1. Open VS Code.
    -Open your project folder in VS Code.

    10.2. Initialize Git Repository:
   -Open the Source Control view by clicking the Source Control icon on the sidebar (it looks like a    branch with a circle).
   -Click Initialize Repository if your project is not already a Git repository.
   -Alternatively, open the terminal in VS Code (Ctrl + (backtick)) and run.

   Making Commits:

   10.3. Stage Changes.
   -Open the Source Control view.
   -You’ll see all your changes listed. Click the + icon next to the files you want to stage, or click + next to Changes to stage all files.

   10.4. Commit Changes.
   -Enter a commit message in the message box at the top of the Source Control view.
   -Click the checkmark icon or press Ctrl + Enter to commit the changes.
   -Alternatively, in the terminal, stage changes with; (git add .) and commit with (git commit -m "Your commit message")

   Pushes Changes to GitHub:

   10.5. Create a Repository on GitHub.
   -Go to GitHub and create a new repository.
   -Copy the repository URL.

   10.6. Add Remote Repository.
   -Open the terminal in VS Code.
   -Add the GitHub repository as a remote with; (git remote add origin <your-repository-URL>)

   10.7. Push Changes.
   -In the terminal, push your commits to GitHub with; (git push -u origin master) or just (git push)






 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

