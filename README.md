[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15284665&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.


ANSWERS
INSTALLING VS CODE

Download the Installer:
I visit the official Visual Studio Code website at https://code.visualstudio.com/ and click on "Download for Windows".

Run the Installer:
Once the download completes, I locate the downloaded .exe file in my Downloads folder and double-click on it to start the installer.

Begin Installation:
The installer launches, and I click on "Next" to proceed.

Review License Agreement:
I carefully read the license agreement, then check "I accept the agreement" and click "Next".

Select Destination Location:
I choose the default destination folder for installation (C:\Users\YourUsername\AppData\Local\Programs\Microsoft VS Code).

Select Start Menu Folder:
I select the folder where I want the Visual Studio Code shortcuts to appear in the Start Menu and click "Next".

Select Additional Tasks:
Optionally, I choose to create a desktop icon and add context menu entries. After making my selections, I click "Next".

Ready to Install:
I review my installation settings and click "Install" to begin the installation process.

Installation Progress:
I wait for the installer to complete the installation of Visual Studio Code on my system. This may take a few moments.

Completing the Installation:
Once the installation finishes, I see the "Completing the Visual Studio Code Setup Wizard" screen. I ensure the "Launch Visual Studio Code" option is checked if I want to start VS Code immediately after installation. Finally, I click "Finish" to exit the installer.

Start Visual Studio Code:
After installation, I can launch Visual Studio Code by double-clicking the desktop icon (if I created one) or by searching for "Visual Studio Code" in the Start Menu.

INSTALLING GIT
Download Git Installer:
I visit the official Git website at https://git-scm.com/ and click on the "Download" button to download the Git installer.

Run the Installer:
Once the download completes, I locate the downloaded .exe file (typically named something like Git-x.x.x.x-64-bit.exe) in my Downloads folder and double-click to run the installer.

Choose Installation Options:
The installer launches, and I click "Next" to proceed.

Select Destination Location:
I choose the destination folder where I want Git to be installed. The default location (C:\Program Files\Git) works fine for me. I click "Next".

Select Components:
I leave the default components selected as they are sufficient for my needs. I click "Next".

Adjusting your PATH environment:
I select the option "Use Git from the Windows Command Prompt" to add Git to my PATH. This allows me to use Git from the command line. I proceed by clicking "Next".

Choosing HTTPS transport backend:
I leave the default "Use the OpenSSL library" selected and click "Next".

Configuring line ending conversions:
I choose the default "Checkout Windows-style, commit Unix-style line endings" and click "Next".

Configuring terminal emulator to use with Git Bash:
I opt for the default "Use MinTTY" and click "Next".

Choosing the default editor used by Git:
I select my preferred text editor for Git to use and click "Next".

Choosing SSH executable:
I leave the default "Use OpenSSH" selected and click "Next".

Installing:
I review my installation settings and click "Install" to begin the installation process.

Installation Progress:
I wait for the installer to complete the installation of Git on my system. This usually takes a few moments.

Completing the Git Setup Wizard:
Once the installation finishes, I see the "Completing the Git Setup Wizard" screen. I ensure the "Launch Git Bash" option is checked if I want to start Git Bash immediately after installation. Finally, I click "Finish" to exit the installer.

Verify Installation:
To confirm that Git has been installed successfully, I open a command prompt or Git Bash and type git --version. If Git has been installed correctly, I will see the version number of Git displayed.

INSTALLING PYTHON

Download Python Installer:
I go to the official Python website at https://www.python.org/, and I navigate to the Downloads section.

Choose Python Version:
I choose the latest stable version of Python that fits my needs. Typically, it's prominently displayed on the homepage. Currently, I'm opting for Python 3.10.1.

Download Python Installer:
Scrolling down, I locate the Windows installer (usually labeled "Download Windows installer (64-bit)"). As I'm on a 64-bit system, I select the appropriate version. The download begins after I click it.

Run Python Installer:
I open the downloaded installer (python-3.10.1-amd64.exe) by double-clicking it from my browser or navigating to the Downloads folder. The "User Account Control" prompt asks for permission to run the installer. Selecting "Yes" begins the installation.

Customize Python Installation:
When the installer starts, the first page offers options to modify the installation. Here, I confirm that I want to install Python for all users and include it in the system PATH, which makes Python accessible from the command line. Click "Install Now" to proceed.

Installation Progress:
I patiently wait while Python installs. The progress bar fills, and a small status window details each step.

Complete Python Installation:
After a successful installation, I select "Close" to exit the installer. Python is now available on my computer.

Verify Python Installation:
To confirm Python's installation, I open the command prompt and type python --version. It displays Python's version number (Python 3.10.1).

Install Python Packages:
As I explore Python, I add additional packages. Utilizing pip, Python's package manager, I install them by opening the command prompt and entering pip install package-name.

GITHUB REPOSITORY WITH A SAMPLE PROJECT INITIALIZED WITH GIT AND ANY NECESSARY CONFIGURATION

https://github.com/Neezahbel/demo.git