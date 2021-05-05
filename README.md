# git-with-CLI

## Command
+ git init
+ git status
+ git add .
+ git commit -m "message"
+ git log => q to exit

+ git pull
+ git branch => show branch's list
+ git branch "new-branch-name" => create new branch
+ git checkout "branch-name" => switch to new branch
+ git checkout -b "branch-name" => create new branch and checkout 
+ git push

## pull another branch
+ git branch -f remote_branch_name origin/remote_branch_name
+ git checkout remote_branch_name

## Resolve conflict
+ Assume: master and my-branch
1. In my-branch => switch to master and pull new code
2. Switch to my-branch => git merge master (merge master into my-branch)
3. Resolve confict => add => commit => push new code

## Reset commit
+ git reset --hard HEAD~3 => go back 3 commits
