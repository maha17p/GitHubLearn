1.git init -> Create Local Repository
    * We can't modify or add anything inside .git folder.
    * It will only stores the commit that we make as a log. .git folder moniters entire folder.(U)

2. git status --> find the status of the file
    * In git, There are two types of file . One is track file and another one is untrack file. Git will track the file the moment we make our untrack file to track file. For this we use git add comment

3. git add filename --> make particular untackable  file to trackble file(A). (M)

4. git add . -->  For making all the untrackable file to trackable file.
 
5. git add *.txt --> For making particular format of the  untrackable file to trackable file.

6.  git diff --> find the difference of modified and original file (added file).

7. git rm --cached filename --> make particular trackable file to untrackable file.

8. git commit -m "msg" --> It stores the trackable file to our local repo. If use git status , you won't see that file since we have added that file to our local repo.

9. git log --> We can see the all the commits that we have made in this folder.
10.git log --oneline --> to see all commits in oneline
11. cat filename --> to see what context inside in file
10.git config --global user.name ""
11.git config --global user.email ""
12.git config --list
13.git branch --> to list the git branches
14.git branch branchName --> to create new Branch.
15.git branch -d branchName --> to delete the branch. 
16.git checkout branchName --> to move one branch to another branch
17.git checkout -b branchName --> to create new branch and move into that brach.
[Though you are in new branch you can access all the files of master branch. But if we create new file in new branch you can't access in master branch]

18.git checkout commitId --> to go previous commit.
19.git checkout . --> to go to the previous place where you commit after modified(for specific file we can mention fileName)
20.git checkout master --> id section to master
21. git reset --hard id --> One use this comment you can't get back to the master branch--> It makes particular id as a master branch.
22.git merge branchName --> to merge the branch.



# .gitignore file:
    1.Sometimes, we don't need to add all files  to our git hub repo like nodemodules .By using .gitignore file we can do this.

    2.Whatever the filename that we mention in .gitognore file, It won't be added to the repo

    3. For hide folder -> we should filefolder/
# LifeCycle of GitHub:
            * git init --> initalize repository
    1. Working Directory --> our directory
            * git add -->
    2. Staging Area --> make files trackable
            * git commit
    3. Local Repository --> save our files in our local
            * git push
    4. Remote Repository --> save our local repo to remote repo