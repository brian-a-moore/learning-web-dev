# Lesson 2: An Introduction to Git

Git is a tool used to keep different versions of your code. It allows you to work on specific things in isolation that don’t affect your main code base. This will make even more sense when you start working with teams and several people are working on the same code at the same time.

You can learn more about Git here: https://dev.to/olawanle_joel/git-github-explained-like-i-m-five-58f2

**NOTE**: Please follow this entire 5-part series

Here’s the most important highlights about Git you should know:

- Git only works in a **repository**, which is a folder of files that Git is tracking
- Git keeps many versions (or copies) of your code, each is called a **branch**
- Each branch has a name associated with it, the main branch for most git repositories is called **main** (in older code you will see it called master)
- Your repository can exist in one of two places:
  - **Local**, which means it is on your machine
  - **Remote**, which means it is in the cloud on a website like GitHub or GitLab
- Throughout our exercises, I will be posting code on a repository stored remotely on GitHub, you will need to **clone** this repo (or repository) to your local machine. This means, you will create your own copy that exists on your PC.
- If you or I make changes on our machines and we want to share them with each other, we have to **push** them to GitHub
- But before we can push them, we have to **commit** them (or save them) to our local branch first
- You can commit all or some of your changes by **adding** them to a commit
- Once your changes are on GitHub, if you want to get the most recent changes on your machine, you have to **pull** those changes down to your PC.
- You can **checkout** a branch as well if you are not currently on that branch.

There’s a lot more to git, but these are the most common commands you will use to get started. Below I’ve added a cheatsheet, you should keep this saved for reference

Here’s the cheatsheet: https://education.github.com/git-cheat-sheet-education.pdf
