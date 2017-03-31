# GameDevClubRPG
This is a Repository for the GameDevClub to make their first game.

We are using LibGDX for our Libraries for this project.

# How to install

To setup you will need to install eclipse
To do this you can just google eclipse and download the IDE (Integrated Development Environment)

Then once you have installed eclipse you will need to install Gradle into your workstation
When you are in eclipse go "Help > Eclipse Marketplace"
Now search for Gradle or Buildship. The project is called Buildship Gradle Integration 2.0. It has a picture of an angry elephant. This package will give you the tools you need to work with a gradle project.

Now that we have the setup ready we need to install the Git.

Create a folder where you would like to store your git project. (This folder will be created in the OS, not eclipse) And make sure this folder is seperate from your workstation. If your git folder and the workstation are the same then you will have lots of files created from eclipse that will want to be pushed to the git.
Use CMD or Terminal and use the commands
First go to the folder you are working in through commands such as cd (goes to directory) and ls/dir (Views the directory)
"git init" This command creates a hidden file that stores the git info
"git pull https://github.com/UngratefulFool/GameDevClubRPG.git"
This grabs the project files for this project
You can use "git status" to see if there are any files left in there that shouldn't be
You can also use Dir or ls to see all the files in that dir

Now import the project as an existing gradle project.
Click next, next, finish

Now if you try to run the desktopLauncher.java you will see that you recieve an error
Go to your green run button and click the arrow next to it and click run configuration
Click DesktopLauncher, go to arguments, and change working direction to Bounce-core
