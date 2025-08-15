# GitHub

GitHub is a platform for developers to store, manage, and collaborate on code. It’s built around Git, which is a version control system that tracks changes to files and helps multiple people work on a project simultaneously without overwriting each other's work.  

- Git is a version control system that tracks changes in your local project.
- GitHub is a cloud-based hosting platform for Git repositories—it's how teams share their code online.

----------------------------------------------------------------------------------------------------------------------------------------------

# GitHub Terminology

Understanding key GitHub terms is essential for managing and contributing to projects effectively. Below are commonly used terms and their definitions:  

- Repository (Repo)
- Commit
- Branch
- Fork
- Pull Request (PR)
- Merge

## Repository (Repo)

A **repository** is like a project folder on GitHub.  
It contains all the files, code, documentation, and history of changes related to a project.

## Commit

A **commit** is a snapshot of your changes.  
It records changes you've made to files and saves them in the repository, usually with a message explaining what you changed.

## Branch

A **branch** is a separate version of your project where you can make changes without affecting the main codebase.

## Fork

A **fork** is a personal copy of someone else's repository.  
It allows you to freely make changes without affecting the original project. Commonly used when contributing to open-source projects.

## Pull Request (PR)

A **pull request** is a way to propose changes to a repository.  
You open a PR to ask maintainers to review and merge your branch into the main project.

## Merge

To **merge** is to apply the changes from one branch into another.  
Usually done after a pull request is reviewed and approved.

------------------------------------------------------------------------------------------------------------------------------------------------------

# GitHub Workflow

- Clone a repository
- Create a branch
- Make changes and commit
- Push changes
- Create a pull request
- Review and merge

## Repository Management

git init                      # Initialize a new git repo
git clone <repo-url>         # Clone a remote repo
git status                   # Show changed files
git add <file>               # Stage a file
git add .                    # Stage all files
git commit -m "Message"      # Commit changes
git push origin <branch>     # Push to GitHub
git pull origin <branch>     # Pull from GitHub

## Initialize a New Git Repository

git init  

Initializes a new Git repository in your current directory. Use this when starting a new project from scratch.  

## Clone a Remote Repository

git clone <repo-url>  

Clones an existing GitHub repository to your local machine.  
Example:  
git clone https://github.com/username/repo-name.git  

## Check Status of Files  

git status  

Displays the current state of the working directory and staging area — shows which files are modified, staged, or untracked.

## Stage a File for Commit

git add filename    

Stages a specific file so it will be included in the next commit.  

## Stage All Changes

git add .  

Stages all changed and new files in the current directory and subdirectories.  

## Commit Changes

git commit -m "Your commit message"  

Commits staged changes to the local repository with a message describing what was changed.

## Push Changes to GitHub

git push origin branchname  

Uploads your local commits to the remote repository on the specified branch.  

## Pull Changes from GitHub

git pull origin branchname  

Fetches and merges changes from the remote repository into your current local branch.

-----------------------------------------------------------------------------------------------------------------------------------------------

# Git Branching Commands

Working with branches is essential for managing different features, bug fixes, or experiments without affecting the main codebase. Below are common Git branch commands with explanations and examples.

## List All Branches

git branch

Lists all local branches in your repository. The currently active branch will be highlighted with an asterisk (*).

## Create a New Branch

git branch branch-name

Creates a new branch based on the current branch but does not switch to it.

## Switch to a Branch

git checkout branch-name

Switches to the specified branch.

## Create and Switch to a New Branch

git checkout -b branch-name

Creates a new branch and switches to it immediately.

## Merge a Branch into Current Branch

git merge branch-name

Merges the specified branch into the branch you’re currently on.

Example:  

git checkout main  
git merge feature-login  

This will merge the changes from feature-login into main.

## Rebase Current Branch onto Another

git rebase branchname  

Moves the base of the current branch to the tip of the specified branch. This creates a cleaner history but must be used with care.

git checkout feature-login  
git rebase main

Reapplies your feature-login commits on top of main.


---------------------------------------------------------------------------------------------------------------------------------------------














