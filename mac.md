## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?

Git is a piece of software used to track changes in sets of files. It is an example of a distributed version control system, and is often used by teams of programmers during collaborative software development.

2. What is the difference between Git and GitHub?

Git is the foundational underlying software, while GitHub is one particular provider of hosting and version control services that makes use of Git. In addition to hosting source code, GitHub has its own features on top of the core functionality of Git.

3. Why do we create a branch? 

We create a branch to be able to separate development work without impacting any other branches that may be in the repository. Creating a branch basically lets us work on software in a niche within the repository.

4. What is the purpose of a Pull Request?

A pull request allows us to submit proposed changes to a repository.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.

We can use the `checkout` command to switch between branches.

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?

`Git fetch` downloads all changes from a specified repository, but does not integrate them into your current HEAD branch.
`Git merge` merges a specified branch into your current HEAD branch.
`Git pull` downloads changes from a specified repository, and merges / integrates them into your current HEAD branch.

7. What is a merge conflict?

A merge conflict occurs when there is a difference between merged branches. There are multiple potential causes, but you have to fix the conflict before you actually merge the branches.

8. How do you resolve a merge conflict?

How you resolve a merge conflict depends on the cause, but you should probably talk to whoever made the change that caused the conflict. If both you and someone else made different changes to the same line, you would need to sort out whose change to keep and why. If someone edited a file and someone else deleted it, you would need to decide whether or not to keep it.
