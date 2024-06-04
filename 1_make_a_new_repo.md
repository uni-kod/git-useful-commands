--------------------------------------------------------------------------------
# Step 1: Create Repo in Github Website:

- Login into Github.
- Choose create repo.
- Fill-in the details in required field Repository name and optional field Description.
- Choose your repo is public or private.
- Then click Create Repository Create Repo.

--------------------------------------------------------------------------------
# Step 2: Copy the Repo Url from Address Bar:

 - Copy the Git repo url from browser address bar. It will be used later in Step 7
Repo created.

--------------------------------------------------------------------------------
# Step 3: Create a directory with similar to repo name:

mkdir test_repo && cd test_repo

--------------------------------------------------------------------------------
# Step 4: Run Git init command to initialize directory:

git init

--------------------------------------------------------------------------------
# Step 5: Create branch main::

- After the initiatives of Inclusive naming convention, it is recommended to use branch
name as main, instead of master, So the below command renames the branch master to main.

git branch -m main

--------------------------------------------------------------------------------
# Step 6: Now add the repo to remote Git URL:

- After using the git init command, link the local repository to an empty GitHub
repository using the following command:

git remote add origin https://github.com/xxxx/test_repo.git

--------------------------------------------------------------------------------
# Step 7: Create a file:

echo "## test_repo readme" > README.md

--------------------------------------------------------------------------------
# Step 8: Check repo changes using git status

git status

--------------------------------------------------------------------------------
# Step 9: Add the files to local staging:

- Stages the file in preparation for versioning.

git add .

--------------------------------------------------------------------------------
# Step 10: Commit the staged files:

- Records staged files permanently in version history.

git commit -m "first commit"

--------------------------------------------------------------------------------
# Step 12: Push the repo changes to Git:

- git push Uploads all local branch commits to GitHub
The current branch main has no upstream branch in GitHub, since we initialized
a local directory as repo, so use below command for the first time to push the
current branch changes and set the remote branch as upstream.

git push --set-upstream origin main

We can now see the repo updated with checked-in files Repo Updated.
