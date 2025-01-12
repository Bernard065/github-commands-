# What is Git

Git is a distributed version control system designed to track changed in source code during software development.

Start with configuring git to work with your name and email.

> `git config --global user.name "Name"`

> `git config --global user.email "email@gmail.com"`

# Initialize a git repository

> `git init`
> Initializes a new git repository. This command creates a new Git repository in the current directory. It sets up the basic files and the directories need to start tracking changes.

# Clone repository

> ` git clone [repository URL]`
> Clones an existing git repository. It creates a copy of an existing repository on your local machine.

# Add file to staging

> `git add [file/directory]`
> Adds a file or directory to the staging area. It prepares the changes for the next commit. It adds the specified file pr directory to the index.
> `git add .`
> Adds all file and directories.

# Commit with a message

> `git commit -m "[commit message]"`
> Creates a new commit with a message describing the changes made.

# Pull Changes

> `git pull`
> Updates the local repository with changes from the local repository. It pulls the changes from remote repository and merges them with the locak changes.

# Push Changes

> `git push`
> Pushes the local changes to the remote repository. It updates the remote repository with the cahnges made locally.

# Check Status

> `git status`
> Shows the current status of the repository. It shows the status of the repository and the changes that are currently staged and unstaged.

# List branches

> `git branch`
> This command lists all the branches of the current repository.

# Switch a branch

> `git checkout [branch_name]`
> Switch to the specified branch.

# Merge branch

> `git merge [branch_name]`
This command merges the specified branch into the current branch. It combines changes from both branches and creates a new commit.

# Create branch
>` git branch [branch_name]`
This command creates a new branch.

# Create and switch into the branch
>` git checkout -b [branch_name]`
Creates a new branch and immediately switch to that branch