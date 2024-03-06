# git-begins

Learning Git for Beginners. 

Thank You FreeCodeCamp :->

Yada! Yada!

## Some header 

Some more text from tutorial on youtube.
Yada! Yada! 

So now what? 

        GitHub WorkFlow                     Local Git WorkFlow

            Write Code                          Write Code
                 |                                  |
                 |                                  |
            Commit Changes                  Stage Changes (git add)
                 |                                  |
                 |                                  |
            Make a pull request             Commit Changes (git commit)
                                                    |
                                                    |
                                            Push Changes (git push)
                                                    |
                                                    |
                                            Make a Pull request    

Pull request is made in the following cases:
a. When you don't own the repository 
b. When you don't have access rights 
c. When you have to get your code reviewed.
d. Also when Error "Updates were rejected because the remote contains work that you do not have locally"


-------------------------------- Branching -----------------------------
                            
                                                     (Hot fix branch)
                                                    |--- commit_1 ---|
                    (Master Branch)                 |                |
commit_1 -----> commit_2 ------> commit_3 ------> commit_4 -------> merge -------> merge
                  |                                                                 |   
                  |                                                                 |
                  |------> commit_1 -----> commit_2   --------------------------->|   
                               (feature branch)  

Master Branch is the main branch.
Feature branch is the one which will be merged later with master branch
Hot fix branch is an emergency measure needed to resolve a bug and later merged with the master branch. 





