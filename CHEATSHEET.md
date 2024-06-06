

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

- `git branch` >
- `git branch <branch-name>` >
- `git branch -d <branch-name> ` > Deletes the specified branch
- `git branch -a` > lists all local and remote branches
- `git checkout` >
- `git checkout <branch-name>` >
- `git checkout -b <new-branch-name> ` >
- `git merge` >
- `git log` >
- `git log` >
- `git log` >
- `git log` >
- `git log` >
- `git log` >


# INSPECT & COMPARE










  Reference from : https://education.github.com/git-cheat-sheet-education.pdf

