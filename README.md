git init
commit-echo "# webpage@url.com"
git add .
git config user.name "username"
git config user.email "user@email.com"

git branch -M main
git commit -m "first commit"

git remote add "origin newrepo.git"
curl -sS https://webi.sh/gh | sh
gh auth login
git push -u origin main


//Create a save point and attach memo to it
git commit -m

//View the value of origin
git remote -v

//Change the value of origin
git remote set-url origin "repolink.git"
//Activate or initialize source control
git init

//Renames current branch to main
git branch -M main

git add .
git commit -m ""
git push

//Pushes changes to the origin main branch and saves parameters
git push -u origin main
