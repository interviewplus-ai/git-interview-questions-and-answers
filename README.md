# Git Interview Questions And Answers

Most targeted up-to-date git interview questions and answers list

## Table of Contents
1. [What is Git?](#1-what-is-git)
2. [What is the difference between Git and GitHub?](#2-what-is-the-difference-between-git-and-github)
3. [What is a Git repository?](#3-what-is-a-git-repository)
4. [What is a Git commit?](#4-what-is-a-git-commit)
5. [What is a Git branch?](#5-what-is-a-git-branch)
6. [How do you create a new Git branch?](#6-how-do-you-create-a-new-git-branch)
7. [How do you switch to a different Git branch?](#7-how-do-you-switch-to-a-different-git-branch)
8. [How do you merge two Git branches?](#8-how-do-you-merge-two-git-branches)
9. [What is Git rebase?](#9-what-is-git-rebase)
10. [How do you undo a Git commit?](#10-how-do-you-undo-a-git-commit)
11. [What is Git cherry-pick?](#11-what-is-git-cherry-pick)
12. [How do you delete a Git branch?](#12-how-do-you-delete-a-git-branch)
13. [What is Git stash?](#13-what-is-git-stash)
14. [How do you apply a Git stash?](#14-how-do-you-apply-a-git-stash)
15. [How do you create a Git tag?](#15-how-do-you-create-a-git-tag)
16. [How do you push a Git tag to a remote repository?](#16-how-do-you-push-a-git-tag-to-a-remote-repository)
17. [What is Git clone?](#17-what-is-git-clone)
18. [How do you update a Git clone with the latest changes from the remote repository?](#18-how-do-you-update-a-git-clone-with-the-latest-changes-from-the-remote-repository)
19. [What is Git fork?](#19-what-is-git-fork)
20. [How do you contribute to an open-source project on GitHub?](#20-how-do-you-contribute-to-an-open-source-project-on-github)
- [Whats more?](#whats-more)
- [Contributing](#contributing)
- [License](#license)

## 1. What is Git?
Git is a distributed version control system that allows multiple people to work on the same codebase simultaneously. It was developed by Linus Torvalds for Linux kernel development.

## 2. What is the difference between Git and GitHub?
Git is a version control system, while GitHub is a web-based hosting service for Git repositories. GitHub provides a platform for developers to collaborate on code and manage projects.

## 3. What is a Git repository?
A Git repository is a directory that contains all the files and directories of a project along with the metadata required by Git to manage changes to the project.

## 4. What is a Git commit?
A Git commit is a snapshot of the repository at a particular point in time. It records the changes made to the repository since the last commit and includes a message describing the changes.

## 5. What is a Git branch?
A Git branch is a pointer to a particular commit in the repository's history. It allows developers to work on different versions of the code simultaneously.

## 6. How do you create a new Git branch?
To create a new Git branch, use the git branch command followed by the name of the new branch. For example, to create a branch called "feature-x", use the following command:

```perl
git branch feature-x
```

## 7. How do you switch to a different Git branch?
To switch to a different Git branch, use the git checkout command followed by the name of the branch. For example, to switch to the "feature-x" branch, use the following command:

```perl
git checkout feature-x
```

## 8. How do you merge two Git branches?
To merge two Git branches, first switch to the branch that you want to merge into, then use the git merge command followed by the name of the branch you want to merge. For example, to merge the "feature-x" branch into the current branch, use the following commands:

```perl
git checkout main
git merge feature-x
```

## 9. What is Git rebase?
Git rebase is a command that allows you to apply changes from one branch to another by replaying the commits of one branch on top of the commits of another.

## 10. How do you undo a Git commit?
To undo a Git commit, use the git reset command followed by the --soft option and the hash of the commit you want to undo. For example, to undo the most recent commit, use the following command:

```perl
git reset --soft HEAD~1
```

## 11. What is Git cherry-pick?
Git cherry-pick is a command that allows you to apply a specific commit from one branch to another.

## 12. How do you delete a Git branch?
To delete a Git branch, use the git branch command followed by the -d option and the name of the branch. For example, to delete the "feature-x" branch, use the following command:

```perl
git branch -d feature-x
```

## 13. What is Git stash?
Git stash is a command that allows you to temporarily save changes that are not ready to be committed yet.

## 14. How do you apply a Git stash?
To apply a Git stash, use the git stash apply command. For example, to apply the most recent stash, use the following command:

```perl
git stash apply
```

## 15. How do you create a Git tag?
To create a Git tag, use the git tag command followed by the name of the tag and the hash of the commit you want to tag. For example, to create a tag called "v1.0" for the current commit, use the following command:

```perl
git tag v1.0 HEAD
```

## 16. How do you push a Git tag to a remote repository?
To push a Git tag to a remote repository, use the git push command followed by the name of the remote repository and the name of the tag. For example, to push the "v1.0" tag to the "origin" remote repository, use the following command:

```perl
git push origin v1.0
```

## 17. What is Git clone?
Git clone is a command that allows you to create a copy of a Git repository on your local machine.

## 18. How do you update a Git clone with the latest changes from the remote repository?
To update a Git clone with the latest changes from the remote repository, use the git pull command. For example, to update the current branch with the latest changes from the "origin" remote repository, use the following command:

```perl
git pull origin
```

## 19. What is Git fork?
Git fork is a feature provided by hosting services like GitHub that allows you to create a copy of a Git repository under your own account.

## 20. How do you contribute to an open-source project on GitHub?
To contribute to an open-source project on GitHub, follow these steps:

- Fork the project repository.
- Clone your forked repository to your local machine.
- Create a new branch for your changes.
- Make your changes and commit them.
- Push your changes to your forked repository.
- Create a pull request to merge your changes into the original repository.

Code example:

```perl
# Fork the project repository on GitHub
# Clone your forked repository
git clone https://github.com/YOUR-USERNAME/YOUR-FORKED-REPO.git

# Create a new branch for your changes
git checkout -b my-feature

# Make your changes and commit them
# For example, edit a file called "README.md"
git commit -am "Add my feature"

# Push your changes to your forked repository
git push origin my-feature

# Create a pull request on GitHub to merge your changes into the original repository
```
## What's more?
<a href="https://www.interviewplus.ai/developers-and-programmers/git/questions">A comprehensive list of questions and answers</a>

## Contributing
We welcome contributions from our users to help make this resource as comprehensive and useful as possible. If you have been recently interviewed and encountered a question that is not currently covered on our website, feel free to suggest it as a new question. Your contributions will be added to our platform, and we will make sure to credit you for your contributions. We appreciate your help in making our platform a valuable tool for all job seekers.

## License
MIT License
