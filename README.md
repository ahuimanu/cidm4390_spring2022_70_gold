# CIDM 4390 Section 70

# Team Gold
This README contains a set of steps to follow.

# Git

## What is it?
Git is a version control system that allows multiple developers to contribute to a project simultaneously. It is a command-line application with a set of commands to manipulate commits and branches.

* [Install git for windows](https://gitforwindows.org/)

## Github 

GitHub offers the distributed version control and source code management (SCM) functionality of Git. It provides access control and several collaboration features such as bug tracking, feature requests, task management, continuous integration and wikis for every project.

### Recommended worflow for ALL DOTNET PROJECTS

**Pre-requisites**
* `git` is installed
* Use of a terminal (PowerShell, Git-bash, or the Terminal in Mac)
* Version 6.0 of the dotnet SDK is installed. [Download]
    * confirmation: run this command `dotnet info` or this one `dotnet --list-sdks` from the terminal
    * if any earlier versions of the SDK exist, [uninstall them](https://docs.microsoft.com/en-us/dotnet/core/install/remove-runtime-sdk-versions?pivots=os-windows)
* [Visual Studo Code](https://code.visualstudio.com/)

**Procedure**
1. Start a new repository at Github
    1. Do not add any files (do not check any checkboxes offering READMEs or licenses)
    2. Take note of the link to the repository ![Repository Link](https://i.imgur.com/YUqXwhn.png)
2. On your local machine (in your filesystem), create a folder where you want your project to be created
3. use the `pwd` command to make sure that you are in the place where your project will be created and tracked by git.
4. run `git init` from the terminal where your project will be created
5. run `git status` from the terminal to confirm


**Collaborators**
For teamwork, it is only necessary to create one repository. One of you will invite the others to this repository as [collaborators](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository).