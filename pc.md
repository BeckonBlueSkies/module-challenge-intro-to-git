## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is the flow of work for an individual or collaborative users to change and update a single public document. It is a distributed version control system. It controls code changes during development.
2. What is the difference between Git and GitHub?
GitHub is the host for all the git changes while git is the development tools used to make the changes.
3. Why do we create a branch?
Branches allow you to make development changes independently from the main code.
4. What is the purpose of a Pull Request?
This informs the team that changes to the code needs to be reviewed.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
git checkout main
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git merge merges the branch you are working on with the main branch. git pull sends the request for review of the current branch. git fetch extracts the data and files of the most recent updated commits.
7. What is a merge conflict?
when an independent branch is merged with the main, and then another independent branch merges with main but has different information. the file doesn't know which version to be. or removing a file while changes are happening in a different location.
8. How do you resolve a merge conflict?
review changes manually, accept local changes with git checkout --ours <file name>, or accept remote changes with git checkout --theirs <file name>. 
