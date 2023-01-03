# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.
- After creating and initializing your local repository and adding and committing your files, you would create your GitHub repository and push your existing local repository from the command line (terminal). 
- When pushing your local repository, you would use `git remote add origin` with the SSH protocol (which is more secure than a https link). Then, to be sure, run `git branch -M main` to make sure the default branch name is `main`. Lastly, run `git push -u origin main` to send your current version of your local repository to the remote repository with `main` as the default branch.