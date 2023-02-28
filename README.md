# learn-git

Git is difficult to understand!

But you don't need to learn everything.

Learn these 10 Git commands because you'll be using them 99% of the time.

1. `git init`

Initialize a new Git repository.

This creates a new subdirectory named ".git" in the current directory, where Git stores all the metadata for the repository.

2. `git clone`

Clone an existing repository.

This creates a local copy of the repository, including all of its history and branches.

`git clone <repo-link>`

3. `git add`

Stage changes for the next commit.

This adds the specified file(s) to the staging area, where they will be included in the next commit.

`git add file1.txt file2.txt`

4. `git commit`

Create a new commit.

This records the staged changes and any additional changes made since the last commit, along with a commit message describing the changes.

`git commit -m "Add new feature"`

5. `git push`

Push commits to a remote repository.

This sends the local commits to the specified remote repository, updating the branch on the remote with the new commits.

`git push origin main`

6. `git pull`

Fetch and merge changes from a remote repository.

This retrieves the latest commits from the specified remote repository and merges them into the current branch.

`git pull origin main`

7. `git branch`

List, create, or delete branches.

This command can be used to list the available branches in a repository, create a new branch, or delete an existing branch.

`git branch new-branch`

8. `git checkout`

Switch to a different branch.

This command allows you to switch to a different branch in the repository and make it the current working branch.

`git checkout main`

9. `git merge`

Merge one branch into another.

This command combines the changes from one branch into another branch, creating a new commit that reflects the merged changes.

`git merge new-branch`

10. `git status`

Show the status of the repository.

This command displays the current branch, any staged or unstaged changes, and any untracked files.

`git status`
