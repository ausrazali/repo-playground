# Steps to Contribute

1. Fork this repository. Refer [here](https://www.w3schools.com/git/git_remote_fork.asp?remote=github).

3. Clone the forked repository and configure remotes. Refer [here](https://www.w3schools.com/git/git_clone.asp?remote=github)

4. Create a new branch to keep your work organized and avoid conflicts with the main branch.  
`git branch your-branch-name`

5. Switch to the newly created branch.  
`git checkout your-branch-name`

6. ***(Optional)*** Create and checkout in one step. You can combine steps 3 and 4 using this command.  
`git checkout -b your-branch-name`

7. Open the root folder of the cloned repository in your IDE.

8. In the `src/Playground.java` file, add your nickname to the appropriate section.

9. Check your progress to see which files have been modified.  
`git status`  
You should see output similar to this:
    > Changes not staged for commit:  
    (use "git add <file>..." to update what will be committed)  
    (use "git restore <file>..." to discard changes in working directory)  
    modified:   src/Playground.java

10. Stage your changes  
`git add --all`

11. Commit your changes with a descriptive message  
`git commit -m "your message here"`

12. Switch back to the main branch  
`git checkout main`

13. Merge changes from previous branch to main branch  
`git merge your-branch-name`

14. Push the changes to your forked repository  
  `git push`

15. Create a pull request to propose your changes. Refer [here](https://www.w3schools.com/git/git_remote_send_pull_request.asp?remote=github)

That's it!  I'll review your pull request and merge it if everything looks good.
