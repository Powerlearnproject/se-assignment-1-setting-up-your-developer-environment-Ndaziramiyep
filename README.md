[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15284583&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

# Answers:

# Step-by-Step Guide to Setting Up Your Development Environment

# 1. Select Your Operating System: Windows 11
Download and Install Windows 11 from Microsoft's official website.

<h5>Step 1: Check System Requirements</h5>
Before you begin, ensure your system meets the minimum requirements for Windows 11:

Processor: 1 GHz or faster with at least 2 cores on a compatible 64-bit processor or SoC
RAM: 4 GB or more
Storage: 64 GB or larger storage device
Firmware: UEFI, Secure Boot capable
TPM: Trusted Platform Module (TPM) version 2.0
Graphics Card: DirectX 12 compatible graphics / WDDM 2.x
Display: >9” with HD Resolution (720p)
Internet Connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.

Step 2: Backup Your Data
Before proceeding with the installation, it is recommended to back up all your important files and data.

Step 3: Create a Windows 11 Installation Media
Download the Media Creation Tool:
Visit the Windows 11 download page and download the Media Creation Tool.
Run the Tool:
Open the downloaded Media Creation Tool and select “Create installation media (USB flash drive, DVD, or ISO file) for another PC.”
Choose Language, Edition, and Architecture:
Select your preferred language, Windows 11 edition, and architecture (64-bit).
Create the Installation Media:
Choose whether you want to use a USB flash drive (at least 8 GB) or create an ISO file to burn to a DVD later.
Follow the on-screen instructions to complete the process.

Step 4: Install Windows 11

Insert the Installation Media:
Plug the USB drive into your PC or insert the DVD.
Restart Your Computer:
Restart your computer and boot from the USB drive or DVD. You may need to change the boot order in your BIOS/UEFI settings to do this.
Start the Installation Process:
Once booted, you’ll see the Windows 11 setup screen. Select your language, time, and keyboard preferences, then click “Next.”
Click “Install now.”
Enter Product Key:
Enter your Windows 11 product key, or if upgrading, click "I don't have a product key" and Windows will automatically activate later.
Select Installation Type:
Choose “Custom: Install Windows only (advanced)” if you’re doing a clean install. If upgrading, choose the upgrade option.
Partition Your Drive:
Select the partition where you want to install Windows 11. You can delete, format, create new partitions as needed.
Click “Next” to start the installation.
Step 5: Complete the Installation
Wait for Installation to Finish:
The installation process will copy files, install features, and configure settings. This can take some time.
Set Up Your Windows 11:
After the installation, your PC will restart. Follow the on-screen instructions to set up your Windows 11, including choosing your region, keyboard layout, and connecting to Wi-Fi.
Sign In with a Microsoft Account:
You will be prompted to sign in with your Microsoft account. You can also create a local account if preferred.
Finalize Settings:
Choose your privacy settings and preferences.
Set up a PIN for quick login.

Step 6: Install Drivers and Updates

Update Windows:
Go to Settings > Update & Security > Windows Update and check for updates to ensure your system has the latest patches and drivers.

Install Device Drivers:
Install any necessary device drivers from the manufacturer’s website if not automatically updated by Windows Update.

Step 7: Restore Your Data

Reinstall Applications:
Reinstall any applications you need.
Transfer Back Your Data:
Restore your backed-up data to your new Windows 11 installation.
By following these steps, you should have a successful installation of Windows 11 on your system.

# 2. Install a Text Editor or IDE: Visual Studio Code

For Windows
Download Visual Studio Code:

Visit the Visual Studio Code download page.
Click on the download link for Windows to download the installer (e.g., VSCodeUserSetup-x64-<version>.exe).
Run the Installer:

Once the download is complete, run the installer.
If prompted by User Account Control, click “Yes” to allow the installer to run.
Installation Wizard:

Read and accept the license agreement.
Choose the destination folder where you want to install VS Code (the default is usually fine).
Select any additional tasks you want (e.g., creating a desktop icon, adding to PATH).
Complete Installation:

Click “Install” to begin the installation process.
Once the installation is complete, click “Finish” to launch Visual Studio Code.

# 3. Set Up Version Control System: Git and GitHub
Install Git:

Download Git from git-scm.com and follow the installation instructions.
During installation, select appropriate options (e.g., adjusting PATH environment, choosing default editor).
Configure Git:

Open a command prompt or Git Bash and configure your Git identity:
arduino
Copy code
git config --global user.name 
git config --global user.email
Create a GitHub Account:

Go to GitHub and create an account.
Verify your email address.
Initialize a Git Repository:

Create a new directory for your project.
Open VS Code, go to File -> Open Folder, and select your project directory.
Open the integrated terminal in VS Code (Ctrl+`) and initialize a Git repository:
csharp
Copy code
git init
Make your First Commit:

Create a sample file (e.g., README.md) in your project directory.
Stage the file and commit it:
sql
Copy code
git add README.md
git commit -m "Initial commit"

# 4. Install Necessary Programming Languages and Runtimes: Python

Install Python:

For Windows
Download Python:

Go to the official Python website.
Click on the download link for the latest version of Python for Windows. This will download the installer (e.g., python-3.x.x.exe).
Run the Installer:

Open the downloaded installer.
Check the box that says “Add Python to PATH” at the bottom of the installation window. This is crucial for running Python from the command line.
Choose “Install Now” for the default installation or select “Customize installation” for advanced options.
Customize Installation (Optional):

If you choose “Customize installation,” you can select optional features and advanced options. It’s generally safe to leave the default selections.
Click “Next” and then “Install” to proceed with the installation.
Complete Installation:

Wait for the installation to complete.
Click “Close” once the installation is finished.
Verify Installation:

Open Command Prompt.
Type python --version and press Enter. This should display the installed Python version.
Type pip --version to verify that pip (Python’s package installer) is installed.


# 5. Install Package Managers: pip (Python)

For Windows
If Python is Already Installed
Check pip Installation:

Open Command Prompt.
Type pip --version and press Enter. If pip is already installed, you'll see the version information. If not, follow the steps below.
Download get-pip.py:

Open your web browser and go to https://bootstrap.pypa.io/get-pip.py.
Right-click on the page and choose "Save As..." to save the get-pip.py file.
Run get-pip.py:

Open Command Prompt.
Navigate to the directory where you saved get-pip.py using the cd command. For example:
cd C:\path\to\directory

Run the following command:
python get-pip.py

Verify Installation:

After the installation completes, type pip --version and press Enter to ensure pip is installed correctly.


6. Configure a Database: MySQL

For Windows
Download MySQL:

Go to the MySQL download page.
Download the MySQL Installer for Windows.
Run the Installer:

Open the downloaded installer file.
Choose "Setup Type". For most users, "Developer Default" or "Server only" is sufficient.
Click "Next" and follow the instructions.
Configure MySQL Server:

In the configuration step, set up the MySQL Server with the following options:
Config Type: Choose "Development Machine", "Server Machine", or "Dedicated Machine" based on your use case.
Connectivity: Enable TCP/IP, and keep the default port (3306) unless you need to change it.
Authentication Method: Choose "Use Strong Password Encryption for Authentication" for better security.
Root Password: Set a strong password for the MySQL root user. Make sure to remember this password.
Add User Accounts:

Optionally, add additional MySQL user accounts with specific privileges.
Start MySQL Server:

Complete the installation and ensure the MySQL Server is running.
Verify Installation:

Open Command Prompt.
Run mysql -u root -p and enter your root password to access the MySQL shell.

7. Set Up Development Environments and Virtualization (Optional): Docker 

For Windows
Download Docker Desktop:

Visit the Docker Desktop for Windows download page.
Download the Docker Desktop installer.
Install Docker Desktop:

Run the downloaded installer.
Follow the installation instructions and select the necessary options (e.g., enabling WSL 2 backend if you're using Windows Subsystem for Linux).
Click "Finish" to complete the installation and launch Docker Desktop.
Start Docker Desktop:

Open Docker Desktop from the Start menu.
Wait for Docker to start and ensure it is running properly (you'll see the Docker icon in the system tray).
Verify Installation:

Open Command Prompt or PowerShell.
Run the command docker --version to verify the installation.
Run docker run hello-world to verify that Docker can pull and run containers.

8. Explore Extensions and Plugins: Visual Studio Code

Step 1: Open Extensions View
Launch Visual Studio Code:

Open VS Code on your computer.
Open Extensions View:

Click on the Extensions icon in the Activity Bar on the side of the window. This icon looks like a square made up of four squares (or you can press Ctrl+Shift+X on Windows/Linux or Cmd+Shift+X on macOS).
Step 2: Browse and Search for Extensions
Browse Extensions:

In the Extensions view, you can browse popular and recommended extensions.
Search for Specific Extensions:

Use the search bar at the top of the Extensions view to search for specific extensions by name, category, or functionality (e.g., "Python", "Git", "Docker").
Step 3: Install Extensions
Select an Extension:

Click on an extension from the list to view more details about it, including a description, installation instructions, and user ratings.
Install the Extension:

Click the green "Install" button to install the extension. VS Code will download and install the extension automatically.
Step 4: Manage Installed Extensions
View Installed Extensions:

Click on the "Installed" tab in the Extensions view to see a list of all the extensions you have installed.
Disable or Uninstall Extensions:

To disable an extension, click the gear icon next to the extension and select "Disable".
To uninstall an extension, click the gear icon and select "Uninstall".
Step 5: Update Extensions
Check for Updates:
Go to the "Installed" tab and click on the gear icon next to any extension to see if an update is available.
Click "Update" to install the latest version of the extension.
Step 6: Explore Recommended Extensions
Recommendations:
VS Code offers recommendations based on your project type and usage.
Click on "Show Recommended Extensions" to see extensions that might be useful for you.
Step 7: Customize Extensions Settings
Configure Extensions:

Many extensions have customizable settings. To configure an extension, go to the extension's detail page and look for a "Settings" or "Configure" button.
Access Settings:

Alternatively, go to File > Preferences > Settings (or press Ctrl+, on Windows/Linux or Cmd+, on macOS) and find the settings for the specific extension.
Popular Extensions to Consider
Language Support:

Python: ms-python.python
JavaScript/TypeScript: ms-vscode.vscode-typescript-next
Java: redhat.java
C++: ms-vscode.cpptools
Code Formatting:

Prettier: esbenp.prettier-vscode

<h5><i>End of answers!</i></h5>




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









