<git to github Push>

git init
git add file naem
git commit -m "first commit"
git branch -M main
git remote add origin (SSH url)
git push -u origin main

<git to github Pull>

git pull origin main

<Branch> for safe clone

/\* 1. Create branch on git

git switch -c <name of the brach which want to create>
git switch <name of the branch> : branch main
git switch git-branches
code . :VS open
git switch main

/\* 2. Push new branch to git

git status
git add .
git commit -m
git push origin git-branches (branch name)
--> go to pull request(from the link or repo pull requests)

c
/\* 3. merge to main on Github

/\* 4. last step merged main to git pull

git switch main
git pull origin main
