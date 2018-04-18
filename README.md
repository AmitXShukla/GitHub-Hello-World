### GitHub-Hello-World
TEST
GitHub Git Commands Git Desktop Basics Installation and Commands

For any questions or queries, please open an issue or leave comments here.

### Installation
[Desktop version] (https://desktop.github.com/)

[Command Line] (https://git-scm.com/downloads)

[Git Documentation] (https://git-scm.com/doc)

[Git Explore] (https://github.com/explore)


### Update Windows Environment Variables
PATH -> C:\amit.io\Program\PortableGit\cmd (Path to Git CMD Exe) 

vscode -> Settings -> git.path = "C:\\\amit.io\\\Program\\PortableGit\\\cmd"


### GitHub WorkFlow
![Alt text](GitHub_workflow.png?raw=true "GitHub WorkFlow")

| Command | Description |
| --- | --- |
| ## Config: | |
| git config --global user.name "Amit Shukla" | |
| git config --global user.email amit@elishconsulting.com | |
| ## Init or Clone New Repository: | |
| git init | Initialize a new Repository |
| git clone https://github.com/AmitXShukla/Git-Hello-World.git | Clone an Existing Repository |
| ## Status: | |
| git status	| Check status |
| git add <file_name_without_angle_brackets> | Add a file from working to staging area |
| git add -A	Add All files from working to stating area |
| git commit -m \"\<your message here without angle brackets\>\" | Commit changes to Local Repository |
| git rm -r <file-name.txt> | Remove a file or folder from working area |
| ## Branch: | |
| git branch |	List all branches (* means current branch) |
| git branch -a |	List all branches (local & remote) |
| git branch <branch_name> |	Create a new branch |
| git branch -d <branch_name> |	Delete branch from local repository |
| git push origin --delete <branch_name> |	Delete a remote branch |
| git checkout -b <branch_name> |	Create a new branch and switch to it |
| git checkout -b <branch_name> origin/<branch_name> |	Clone a remote branch and switch to it |
| git checkout <branch_name> |	Switch to a branch |
| git checkout |	Switch to the branch last checked out |
| git checkout -- <file_name> |	Discard changes to a file |
| git merge <branch_name> |	Merge a branch into the active branch |
| git merge <source_branch> <target_branch> |	Merge a branch into a target branch |
| git stash |	Stash changes in a dirty working directory |
| git stash clear	Remove all stashed entries |
| ## Publish: | |
| git push origin <branch_name> |	Push a branch to your remote repository |
| git push -u origin <branch_name> |	Push changes to remote repository |
| git push |	Push changes to remote repository |
| git push origin --delete <branch_name> |	Delete a remote branch |
| git pull |	Update local repository to the newest commit |
| git pull origin <branch_name> |	Pull changes from remote repository |
| git remote add origin ssh://git@github.com/[username]/[repository-name].git |	Add a remote repository |
| git remote set-url origin ssh://git@github.com/[username]/[repository-name].git |	Set a repository's origin branch to SSH |
| ## Log: | |
| git log |	View changes |
| git log --summary |	View changes (detailed) |
| git diff <source_branch> <target_branch> |	Preview changes before merging |
