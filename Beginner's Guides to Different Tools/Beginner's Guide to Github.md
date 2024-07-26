What is Git?
- A software that exists on your computer.
- Git is memory storage for code, local on your computer. It enables you to save your progress as you code.
- It allows you to go back to your saved progress.
Here are the key git commands to know.
- git init: initializes the memory storage
- git add: adds specific changes that you want to save to the "staging area" (pre-saving)
- git commit: commits those changes to memory (git commit -m "Insert message describing commit here")
- git log: shows all of your past commits
- git checkout: allows you to go back in time to a different save point

What is Github?
- Github is a website.
- Each person can put all of their files/commit history/git from their computer onto the website. Every other person can then download their files/commit history/git, look through the different changes, make their own changes, and push it back onto the website.
- Push: you push files from your computer onto the website. (uploading)
- Pull: you pull someone's files from the website onto your computer. (downloading)
- Repository: a repository is a folder. A repository contains all of the files/save history for one project that you want to keep together.

What are branches?
- By default, all code is on the master (main) branch. This is the "regular" code.
- Someone can download your code, make changes, and thus make them on a different branch, so that their changes do not happen on your branch.
- You can merge the changes on their new branch with the main branch if you want to, or not do that if you don't want to.
- git push origin new-branch: push the new branch new-branch onto Github.
- Pull request: request your branch to be merged with the main one. The person who owns the main branch can merge it with their own.
- Very Important: you always want your local computer to be synced with the Github.
- git pull origin master: pulls down new changes from Github down onto your local computer.
