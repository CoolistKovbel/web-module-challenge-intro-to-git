## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
- Git is an open sources software that is used to control files.
2. What is the difference between Git and GitHub?
- git is allows you to work with the local project without changing the orignal project that exists on github, github is a server where you can hold you projects on. 
3. Why do we create a branch?
- To be able to work on what we need to work on without effecting the main branch, and when everything works well with the branch we are working on we can push it to the main branch.
4. What is the purpose of a Pull Request?
- To be able to save any changes that wont effect the main branch unless it has been merged.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
- you used the "git checkout 'branch name' " To switch between branches
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
- git fetch command allows you to retrieve code without making changes 
- git merge command merges 2 branches together or meges branches to the main branch
- git pull retrieves all the new code from the main branch into your local copy
- The difference is, git fetch doesnt change your local code copy, git merge mergers two branches together, git pull copies the latest code from the main branch
7. What is a merge conflict?
- its is when merging two branches of code gives you conflict because there are new commits in main branch and changes have accoured from the branch out branch and when you try to push the main branch since your current branch is missing the latest commits it wont allow you to merge successfully
8. How do you resolve a merge conflict?
- make sure your commits are up to date with the latest branch.
