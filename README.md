[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15295599&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   skipped

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

SOLUTION

Step 1: Download and Install Visual Studio Code
Download VS Code:

Visit the Visual Studio Code download page.
Select the installer for Windows and download it.
Install VS Code:

Run the downloaded installer.
Follow the installation prompts. It is recommended to select options to add VS Code to your PATH and to associate VS Code with supported file types.
Step 2: Install a Text Editor or Integrated Development Environment (IDE)
Launch VS Code:
After installation, launch VS Code from the Start menu or by typing code in the command prompt (if added to PATH).
Step 3: Set Up Version Control System
Install Git:

Download and install Git from the official Git website.
During installation, you can choose default options. It's recommended to select "Use Git from the command line and also from 3rd-party software".
Configure Git:

Open Git Bash (installed with Git) or use the command prompt.
Set your Git username and email:

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Create a GitHub Account:

Visit GitHub and sign up for an account.
Initialize a Git Repository:

Open VS Code and create a new project folder.
Open the integrated terminal (`Ctrl+``) and navigate to your project folder.
Initialize a new Git repository:

git init
Make your first commit:

git add .
git commit -m "Initial commit"
Step 4: Install Necessary Programming Languages and Runtimes
Install Python:

Download Python from the official Python website.
Run the installer and ensure you check the box to add Python to PATH.
Verify Python Installation:

Open a command prompt and type

python --version
pip --version
Step 5: Install Package Managers
Verify pip Installation:
pip is installed with Python. Verify it by typing:

pip --version
Step 6: Configure a Database (MySQL)
Download MySQL:

Visit the MySQL download page and download the MySQL Installer.
Install MySQL:

Run the MySQL Installer.
Follow the installation prompts to install MySQL Server and MySQL Workbench.
Configure MySQL Server during the installation process, setting a root password and configuring other settings as required.
Verify MySQL Installation:

Open MySQL Workbench and connect to the local MySQL server using the root account.

Step 7: Explore Extensions and Plugins
Open Extensions View in VS Code:

Click on the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X.
Install Essential Extensions:
It is recommended to install only the verified extensions
Python: Search for Python by Microsoft and click Install.

Reload Window:

Some extensions may require you to reload the VS Code window. Click on the reload button when prompted.
