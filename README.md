![image](https://github.com/Powerlearnproject/se-assignment-5-lewiskea/assets/159833418/c7a3341a-ea09-4762-a845-f0e5a76ebb6a)Installation of VS Code:

Steps to Download and Install Visual Studio Code on Windows 11:**

1. Download Visual Studio Code:
   - Open your web browser and go to the [official Visual Studio Code website](https://code.visualstudio.com/).
   - Click on the "Download for Windows" button to download the installer.
   - ![image](https://github.com/Powerlearnproject/se-assignment-5-lewiskea/assets/159833418/ca86f5b7-8153-4855-bac3-a35c5a5c7de1)



2. Run the Installer:
   - Locate the downloaded file (`VSCodeSetup.exe`) and double-click to run it.

3. Setup Wizard:
   - The Visual Studio Code Setup Wizard will open. Click "Next" to proceed.
   - Accept the license agreement and click "Next".
   - Choose the destination folder where you want to install VS Code (default is recommended) and click "Next".
   - Select additional tasks (e.g., adding VS Code to PATH, creating a desktop icon) and click "Next".
   - Click "Install" to start the installation process.

4. Complete Installation:
   - Once the installation is complete, click "Finish" to launch Visual Studio Code.

Prerequisites:
   - Ensure you have Windows 11 installed.
   - An internet connection to download the installer.
   - Basic administrative privileges to install software on your computer.

First-time Setup:

Initial Configurations and Settings for an Optimal Coding Environment:

1. Theme and Appearance:
   - Open VS Code and press `Ctrl + Shift + P` to open the Command Palette.
   - Type "Color Theme" and select "Preferences: Color Theme" to choose your preferred theme.
   - ![image](https://github.com/Powerlearnproject/se-assignment-5-lewiskea/assets/159833418/ca3f1e50-3694-496b-a517-f3589b0723ca)


2. Install Extensions:
   - Click on the Extensions icon in the Activity Bar on the side of the window or press `Ctrl + Shift + X`.
   - Search for and install the following essential extensions:
     - ESLint: JavaScript and TypeScript linting.
     - Prettier - Code Formatter**: Code formatting tool.
     - Live Server: Launch a local development server with live reload.
     - Python: Support for Python development.
     - GitLens: Enhances the built-in Git capabilities.
     - ![image](https://github.com/Powerlearnproject/se-assignment-5-lewiskea/assets/159833418/60a87767-9414-47a0-95f9-a89ed477365d)


3. Settings Configuration:
   - Go to `File > Preferences > Settings` or press `Ctrl + ,`.
   - ![image](https://github.com/Powerlearnproject/se-assignment-5-lewiskea/assets/159833418/096c7762-0a39-4c46-a69a-fccb69acc760)
   - Adjust important settings like:
     - `editor.fontSize`: Set your preferred font size.
     - `editor.tabSize`: Set the number of spaces for a tab.
     - `files.autoSave`: Configure auto-save options.

User Interface Overview:

Main Components of the VS Code User Interface:

1. Activity Bar:
   - Located on the far left of the interface.
   - Provides access to different views like Explorer, Search, Source Control, Run and Debug, and Extensions.

2. Side Bar:
   - Adjacent to the Activity Bar.
   - Displays content for the selected view in the Activity Bar, such as the file explorer or version control status.

3. Editor Group:
   - The main area where you open and edit your files.
   - Supports multiple editor groups for side-by-side editing.

4. Status Bar:
   - Located at the bottom of the window.
   - Displays information like current line number, programming language mode, Git branch, and errors/warnings.

Command Palette:

Description and Usage of the Command Palette:

What is it?
  - The Command Palette is a powerful tool in VS Code that provides access to various commands and features.

- How to Access:
  - Press `Ctrl + Shift + P` (or `F1`).

- Examples of Common Tasks:
  - Change theme: Type "Color Theme" and select a new theme.
  - Install extensions: Type "Extensions: Install Extensions" to search and install.
  - Open settings: Type "Preferences: Open Settings (UI)" to configure settings.

Extensions in VS Code:

Role and Management of Extensions in VS Code:

- Role:
  - Extensions enhance the functionality of VS Code by adding support for additional languages, debuggers, and tools.

- Finding and Installing Extensions:
  - Click on the Extensions icon in the Activity Bar or press `Ctrl + Shift + X`.
  - Search for desired extensions and click "Install".

  Managing Extensions:
  - View installed extensions and disable/uninstall them from the Extensions view.

 Examples of Essential Extensions for Web Development:
  - **ESLint**: Helps maintain consistent coding style.
  - **Prettier**: Automatically formats code.
  - **Live Server**: Provides live reloading for web development.
  - **HTML CSS Support**: Enhances HTML and CSS editing experience.
  - **Debugger for Chrome**: Debug JavaScript in the Chrome browser.

Integrated Terminal:

How to Open and Use the Integrated Terminal:

Opening the Terminal:
  - Go to `View > Terminal` or press `` Ctrl + ` `` (backtick).

  Using the Terminal:
  - The integrated terminal allows you to run shell commands directly within VS Code.
  - Supports multiple terminal instances and different shell types (e.g., PowerShell, Command Prompt, Bash).

  Advantages:
  - Seamless workflow as you don’t need to switch between applications.
  - Supports integrated debugging and task running.

File and Folder Management:

Creating, Opening, and Managing Files and Folders:

Creating Files/Folders:
  - Right-click in the Explorer view and select `New File` or `New Folder`.
  - Use the command palette (`Ctrl + Shift + P`) and type `New File` or `New Folder`.

 Opening Files/Folders:
  - Drag and drop files/folders into the editor.
  - Use `File > Open File` or `File > Open Folder`.

 Navigating Files and Directories:
  - Use the Explorer view to navigate.
  - Press `Ctrl + P` to quickly open files by typing the filename.
  - Use breadcrumbs at the top of the editor for quick navigation.

Settings and Preferences:

Customizing Settings in VS Code:

Accessing Settings:
  - Go to `File > Preferences > Settings` or press `Ctrl + ,`.

  Changing the Theme:
  - Type `theme` in the search bar within the settings and choose your preferred theme under `Color Theme`.

  Adjusting Font Size:
  - Search for `fontSize` and change the value to your preferred size.

Customizing Keybindings:
  - Go to `File > Preferences > Keyboard Shortcuts` or press `Ctrl + K, Ctrl + S`.
  - Search for commands and change their keybindings as needed.

### Debugging in VS Code:

Setting Up and Starting Debugging:

1.Open a Project:
   - Open the folder containing your project files.

3. Configure Debugger:
   - Click on the Run and Debug icon in the Activity Bar or press `Ctrl + Shift + D`.
   - Click on `create a launch.json file` to create a debug configuration.

4. Set Breakpoints:
   - Click in the gutter next to the line numbers to set breakpoints.

5. Start Debugging:
   - Click the green play button in the Run and Debug view or press `F5`.

Key Debugging Features:
   - Step over, step into, and step out of code.
   - Watch expressions.
   - View call stack and variables.

 Using Source Control:

Integrating Git with VS Code:

1. Initialize a Repository:
   - Open the folder you want to turn into a repository.
   - Click on the Source Control icon in the Activity Bar or press `Ctrl + Shift + G`.
   - Click `Initialize Repository`.

2. Making Commits:
   - Make changes to your files.
   - Stage changes by clicking the `+` icon next to the files.
   - Enter a commit message and click the checkmark icon to commit.

3. Pushing Changes to GitHub:
   - Click on the Source Control icon.
   - Click on the `...` menu and select `Push to`.
   - Follow the prompts to set up your remote repository on GitHub and push your changes.
