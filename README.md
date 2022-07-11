# Lesson 1

## Step 1
1. Create the account at github.com
2. Create the new repository.

## Step 2
[Install git](https://www.atlassian.com/git/tutorials/install-git)

### Install the username
```bash
git config user.name some_name
```
### Install the email
```bash
git config user.email example@mail.test
```
Recommends to use github email and username.


## Step 3
1. Create a new folder on your local machine
2. Create a new file README.md there. With content "# HELLO WORLD"

run commands:
```bash
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin "path to your repo".
git push -u origin main
```

## Step 4
1. Create a new branch
```
git checkout -b "feature/newbranch"
```
2. Change README.md file. Add row "My world is new"
```bash
git add README.md
git commit -m "second commit"
git push -u origin feature/newbranch
```
3. Check your github repo. The new changes shpuld be there.


## Step 5
How to merge the code.

Github:
1. To go your feature/newbranch.
2. Contribute -> Open pull request.
3. Create PR to the main branch.
4. Check your changes and click "merge"
You changes will be in main branch in repo.

Local:
```bash
git checkout main
git merge feature/newbranch
git push -u origin main
```
You changes will be in main branch in repo.






