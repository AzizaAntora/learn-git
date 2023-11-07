# Table of Contents

- [Introduction]
- [Installation]
  -Windows
  -Mac
  -Linux
  Creating a Local Folder and Linking it to GitHub
  Creating a Git Repository and cloning it
  Introduction
  Git is a distributed version control system that allows you to track changes to your code over time. It was created by Linus Torvalds in 2005 to help manage the development of the Linux kernel. With Git, you can create a repository to store your code and collaborate with others by sharing your changes and merging them with others' changes.

Installation
Windows
Download the latest Git for Windows installer.
When you've successfully started the installer, you should see the Git Setup wizard screen. Follow the Next and Finish prompts to complete the installation. The default options are pretty sensible for most users.
Mac
Download the latest Git for Mac installer.
Follow the prompts to install Git.
Open a terminal and verify the installation was successful by typing git --version:
Linux
You can install Git in a number of ways, depending on your Linux distribution. If you're on Fedora (or any closely-related RPM-based distribution, such as RHEL or CentOS), you can use dnf:
$ sudo dnf install git-all
If you're on a Debian-based distribution, such as Ubuntu, try apt:
$ sudo apt install git-all
Creating a Local Folder and Linking it to GitHub
Create a new repository on GitHub.
Navigate to GitHub.
Click on the '+' button on the upper right corner and select 'New repository'.
Name your repository and provide a description (optional).
Choose to make the repository either public or private.
Click 'Create repository'.
Create a new directory on your local machine.
Open a terminal.
Navigate to the location where you want to create the directory using cd command.
Create a new directory using mkdir your-directory-name.
Initialize the local directory as a Git repository.
Navigate into the new directory using cd your-directory-name.
Initialize the directory as a Git repository using git init.
Create and Add Files.
Create a new file.
Add the file to the staging area using git add ..
Commit the file using git commit -m 'First commit'.
Set the branch to main using git branch -M main.
Link the local repository to the GitHub repository.
Use the command git remote add origin your-github-repository-url.
Push local changes to the GitHub repository.
Push the changes in your local repository to GitHub using git push -u origin main.
Creating a Git Repository and cloning it
Create a new repository on GitHub.
Navigate to GitHub.
Click on the '+' button on the upper right corner and select 'New repository'.
Name your repository and provide a description (optional).
Choose to make the repository either public or private.
Click 'Create repository'.
Clone the repository.
Open a terminal.
Navigate to the location where you want to clone the repository using cd command.
Clone the repository using git clone your-github-repository-url.# learn-git
