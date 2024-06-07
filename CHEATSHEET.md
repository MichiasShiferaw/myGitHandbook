

# SETUP
*Configuring user information used across local repositories*
- ` git config --global user.name "Michias Shiferaw"`
- ` git config --global user.email "*****@***.ca"`
- ` git config --global color.ui auto` ---> set auto CMD line coloring
- ` git help` > Help documentation

<div style="background-color: rgb(124,252,0);">
  
  # SETUP & INIT
  - `git init` > initialize an existing directory as a Git Repo
  - `git clone` [url] > retrieve entire repo *add . after the url to keep the clone in the curr folder
  - `git clone -branch <branch_name> [url]` > Clones a specific branch from a repo

</div>

# STAGE & SNAPSHOT
- `git status` > displays modified files in working directory
- `git status -ignored ` > Displays ignored files
- `git add [file]` > adda file as it looks now
- `git reset [file]`> unstage a file
- `git diff` > difference of what is changed but not staged
- `git diff --staged` >  diff of what is changed but not yet committed



# COMMITS
- `git commit -m "msg"` > commit your staged content as a new commit
- Can add additional detail with the follwoing options to indicate the commit's relation to the program
  <details>
    <summary> <code>`-m "****: "msg"`</code></summary>
    <br>
    <ul>
    <li>feat**-> feature</li>
    <li>fix</li>
    <li>chore: routine task</li>
    <li>refactor: improve the code structure</li>
    <li>docs: Documenation-related</li>
    <li>style: Related to styling and formatting of the codebase</li>
    <li>test: test-related changes</li>
    <li>perf: performance-related change</li>
    <li>ci: Continuous integration system-related cghanges</li>
    <li>build: related to the build process</li>
    <li>revert: changes to revert a previous commit</li>
    </ul>
  </details>



# BRANCH & MERGE

- `git branch` > list your branches
- `git branch <branch-name>` > create a new branch
- `git branch -d <branch-name> ` > Deletes the specified branch
- `git branch -a` > lists all local and remote branches
- `git checkout` > switch to another branch
- `git checkout <branch-name>` >
- `git checkout -b <new-branch-name> ` >
- `git merge` >  merged the specified branch's history into the current one
- `git log` > show all commits in the curr branch's historu
- `git log <branch>` > display the commit history of the specified branch
- `git log --follow <file>` > display the commit hostory of a file, including its renames
- `git log -all` > displays the commit history of all branches

# GIT TAG
- `git tag` > Lists all tags in the repo
- `git tag <tag-name>` > Create a lightweight tag at the current commit

# TEMPORARY COMMITS
- `git stash` > Stashes the changes in the working directory, allowing you to switch to a different branch or commit
- `git stash list` > Lists all stashes in the repo
- `git stash pop` > Applies and remove the most recent stash from the stash list
- `git stash drop` > Removes the most recent stash from the stash list

# SHARE & UPDATE
- `git remote add <alias> [url]` > add a git URL as an alias
- `git fetch <alias>` > fetch down all the branches from that Git remote
-  `git fetch -prune` > Removes any remote-tracking branches that no longer exist on the remote repository
- `git merge <alias>/<branch>` > merge a remote branch into your current branch to bring it up to date
- `git push <alias>/<branch>` > transmit local branch commits to the remote repo branch
- `git pull` > fetch and merge any commits from the tracking remote branch

# TRACKING PATH CHANGES
- `git rm <file>` > dete the file from project and stage the removal for commit
- `git mv <existing-path> <new-path>` > change an existing file path and stage the move
- `git log --stat -M` > show all commit logs with indication of any path that moved

# REWRITE HISTORY
- `git rebase <branch>` > Apply any commits of curr branch ahead of specified one
- `git reset --soft [commit]` > Preserves the changes in the staging area
- `git reset --hard [commit]` > Clear staging area, rewrite working trree from specified commit
- `git restore <file>` > Restore the file in the working directory to its state in the last commit
- `git revert [commit]` > Creates a new commit that undoes the changes introudced by the specified commit
- `git revert -no-commit [commit]` > Undoes the changes introduced by the speicifed commit, but does not create a new commit 
-  



- `git stash pop` >



# REMOTE REPOSITORIES



# INSPECT & COMPARE










  Reference from : https://education.github.com/git-cheat-sheet-education.pdf

