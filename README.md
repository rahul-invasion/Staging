# Staging


#### Step 1 - Clone the Staging repo.
git clone https://github.com/rahul-invasion/Staging.git

#### Step 2 - Set user name and email globally.
git config --global user.email “your email”
git config —global user.name “your git username”

#### Step 3 - Check Status.
git status

#### Step 4 - Create branch.
git branch branchname
git branch
git checkout branchname

git checkout -b branchname
git branch

#### Step 5 - adding files to your branch.
git checkout branchname 
git add . or git add -A
git commit -m "put some comment"

#### Step 6 - update your remote branch.
git push or git push —set-upstream origin branchname

#### Step 7 - update your local master branch.
git pull origin master

#### Step 8 - merge your local branches with master locally.
git checkout master
git merge --no-ff branchname or git merge branchname





