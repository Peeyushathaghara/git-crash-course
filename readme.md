git cheat sheet = https://education.github.com/git-cheat-sheet-education.pdf

all steps of git
1. git init
2. git add filename = enables git to track these files
3. git commit -m message
4. git log --oneline
5. git reset --hard commithashcode  => a way to remove faulty code and move head to backwards 
6. git revert

Some central servers where we can push our code for collaboration related works
    github, bitbucket, gitlab 
    
Till now the versioning is maintained by git and its commands

Now, we need to push our code to central repo, will use github here.
remote url : https://github.com/Peeyushathaghara/git-crash-course.git

1. git remote add petname url
git remote add original https://github.com/Peeyushathaghara/git-crash-course.git

2. git origin -v

3. git push -u origin main
4. SSH authentication - secure socket shell authentication