# git-shell-colab-exercise

What is Git, and why is it used?

Answer: Git is a distribation version control system that tracks changes in the source code or other types of files. It allows multiple developers to work to work on a project simultaneously without overwriting each other's work.

Why it is used: Open source and popularity, Code integrity, Collaboration, Version History, Branching/experimentation
and, Backup and security.



What is the difference between Git and GitHub?


Answer: Git is used to keep track of changes to files like source codes and manage different version of a project. it operates on your local machine and you can use it without an internet connection.

While

Guthub is a cloud based platform for hosting Git repositories, allowing developers to collaborate on projects, share their code, abd contribute to other projects. It is a service built on top of Git.


How do you initialize a Git repository?


Answer: You run the "git init" command



What is a Git commit, and how do you create one?


Answer: A Git commit is a snapshot of the changes in your project at a specific point in time. Each commit records what changes were made, by whom and when it was made. it is a unique way of saving your work in Git.

How to create a Git commit: You have to add your changes by adding the file to the staging area using the command "git add filename" then you create the commit using the "git commit" command.



What is the purpose of git add?


Answer: It is use to add your changes to the staging area for committing.



What is the difference between git pull and git fetch?


Answer: Git pull fetches the latest changes from the remote repository and then immediately merge them into your current branch. It is the combination of git fetch followed by git merge.

While

Git fetch retrives the latest changes from the remote repository and updates your local copy of the remote branches without merging or modifying your working directory.



What is a branch in Git?


Answer: A Git branch is a saparate workspace or timeline for making changes, allowing developers to work independently without affecting the main codebase.


How do you create a new branch in Git?


Answer: You make use of the "git branch" command to create a branch.



How do you merge one branch into another?


Answer: You use the "git merge" command to merge the branch to the main and you merge the main to the branch with the same command.



How do you view the commit history in Git?


Answer: You use the "git log" command.




# Advanced Questions on Git

What is the purpose of git rebase, and how does it differ from git merge?


Answer: git rebase is used to integrate changes from one branch into another by applying the changes from the source branch onto the base of the target branch. It essentially rewrites commit history to create a linear progression of the commits.c

git rebase is use to crate a clean, linear history, especially for feature brances, While git merge is use to integrate changes while preserving history, often used for integrating long running branches. 



How does Git's cherry-pick command work?



Answer: Unlike git merge or git rebase, which deal with full branch histories, git cherry-pick lets you apply individual commits from one branch to another.
The git cherry-pick command allows you to make specific commit or commits from one branch to another, this is useful when you want to integrate specific changes from one branch into another without merging the entire branch.



What is the significance of Git's staging area, and how can you view it?



Answer:



What are Git hooks, and how can you use them?

How can you resolve conflicts in Git during a merge or rebase?
