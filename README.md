# Github-Assignment
A repository containing the answers of all the questions in the Github assignment.

# 1) - What are the advantages of using Git?.
       Git is a version control and tracking system and helps us to keep track and revert back to those changes in our development cycle. 
       With Git, we can easily track changes, identify the causes of Bugs using our tracking, and create separate branches or workflows for 
       development without affecting the main development process.
# 2) - What language is used in Git?.
       Git is mainly built using C and Python Programming Languages.


# 3) - What is the meaning of index and Staging Area in Git?
       Git index is the "holding area" of the main tree whose changes would be committed to the main branch. We can choose the files which 
       we want to commit and those files would be present in the Git index. Git staging area helps break one large commit into several 
       small components. Besides this, Staging is also used to track and resolve merge conflicts when we commit our changes into the main t
       tree.

# 4) - What is the process of creating a repository in Github?
       - On the upper right corner of your account, Click on the Plus account.
       - Enter the necessary details like name of the repository and you have the additional options of making the repository either public 
         or private and you can also initialize it with a readme file.

# 5) - What is head in Git and how many heads can be created?
       Head refers to the current branch of the Git Repository. A reposiroty can have many heads.
       
# 6) - Why do we need branching in Git?
        Git Branches are required to work on the code separately without disturing the main branch which usually contains production 
        ready code. Also multiple people can work on the same code, Branching makes this easier as each developer can work separately 
        with the help of branches.
        
 # 7) - What is the way to create a new branch in Git?
        The command to create a new branch is git checkout branchname.
   
 # 8) - How do you define a conflict in Git?
        A git conflict occurs usually when two separate and different changes have been made to the same line in the code. They also
        occur when one/multiple lines of code are missing in one branch but are present. Conflicts are basically inconsistencies
        which occur in the codebase when multiple are working on the same part of the codebase.
 
 # 9) - How to resolve conflicts in Git?.
        Git conflicts can be resolved by using git status command and tracking all the conflicts.Usually the process involves discussion
        between the two developers whose branches are conflicting. The developers then decide which parts of the code to be kept,
        discarded and what changes should be made in the codebase to resolve the conflicts.
 
 # 10) - What is the use of a Git Config File?
         Git config file is used to modify and assign the settings of a repository. The Git config file usually contains the user email 
         user username. It also contains all the dependencies associated with a branch.
         
  # 11) - What is Git Fork?
         Git Fork is used to propose changes to someone else's existing project or use someone else's repository as a starting point to
         make changes to that repository.
         
  # 12) - Difference between Fork, Branch and Clone?.
          Fork - Use someone else's branch as a starting point to start making changes.
          Clone - Copy an entire repository to one's local system and start working on that repository. Can be used for pull requests
          later.
          Branch - Create a separate code base separate from the main branch and make changes to that codebase(usually adding a separate 
          feature) and then merge the changes to the main branch. Useful for collobaration.
          
  # 13) - Difference between Pull Request and Branch?.
           Pull request is made to the users to let them know/ approve the changes made to their code by us and then merge the changes.            A git branch is created to create a separate copy/version of the main code in the main branch so that developers can work 
           without affecting the code in the main branch.
           
           
   # 14) - Difference between Git Pull and Git Fetch?.
           Git Fetch just copies the git metadata to the local system from the main repository. Git Pull merges the changes made to code
           to the main branch. Git Pull is Git Fetch + Merge.
   
   
   # 15) -  How to revert to previous commit in Git?.
            The best practice to revert to a commit is to use the git checkout followed by the commit id. So the command would be
            git checkout commitid.
      
   # 16) - Advaantages of Forking Workflow?
            The benefits of forking are mainly,we do not make any direct changes to the original repository. We get a clone or a copy 
           of the original repository and we can make all changes we want and then submit a pull request to the author of the original
           repository.
           
   # 17)- Difference between HEAD, working tree and index in Git?.
          Head is the current working branch or the last committed branch on the working tree.
          Index is the staging area where the commit files would be put before getting pushed to the branch.
          Working Tree consists of all the files that are currently being worked upon.
          
   # 18) - How to identify if a branch has been merged into master branch?
           We can use the command git branch --merged master to check out all the branches which have been merged to the main branch.
           
   # 19) - What is the use of Git Clone?.
           Git clone is used to clone or get a copy of a repository with all its associated files in our local system. We can run the
           application,make changes and then make a pull request after cloning.
           
   # 20) - What is Git Stash?
           Git stash is used to record a state of our current codebase without actually committing it. It is like a taking a temporary 
           snapshot wihtout actually committing the changes.
           
   # 21) - When to use Git Stash?
           Git stash should be used when we need to have a record of the current working state of our repository but we do not want to
           commit those changes and go back to a "clean" state.
   
   # 22) - What is Git Stash save?
           Git Stash save is used to save permanently the temporary state of our code which we saved using the git stash command.
           
   # 23) - What is Git Stash drop?
           Git Stash drop is used to drop/delete the temporary state which we saved using git stash command.
           
   # 24) - What is README.md and what is the purpose of Readme?.
           Readme file is used to provide an overall view/documentation of our project. It may also contain other information such as
           how to run the project, instructions to run the project. MD stands for Markdown which is a lightweight formatting language to 
           format our text.
           
   # 25) - How to create a repository from command prompt?.
           We can use the git init and hub commands to create a new repository from the command prompt.
           Eg: git init myRepo
               cd myRepo.
               hub create
               git push -u origin master.
               
   # 26) - What is the function of git checkout in git?.
            Git checkout helps us navigate or change branches in the working tree of our project.
    
   # 27) - How can we bring a new feature in main branch?
            We can create a new branch from the main branch, make our changes and new features in the sub branch and then merge it back
            to the main branch.
            
   # 28) - What is the use of git rm ?.
           It is used to remove a file, branch from a working directory.
           
   # 29) - Function of git stash apply?.
           It is used to apply(save) the changes made by the git stash command to the current working directory.
           
   # 30) - What is the use of git log?
           Git log is used to see all the previous commits and the commit history along with commit ids and other metadata.
        
   # 31) - What is the use of Git Add?.
           Git Add is used to add the files to be tracked by Git to the staging area. Files specified as parameters to git add will
           be tracked by Git.
           
   # 32) - What is the use of Git Diff?
           Git Diff takes two input files and lists out all the differences between them. It is used for comparing two files/ two
           snippets of code and find the differences between them.
    
   # 33) - What is git status used for ?
           Git status is used to track the changes made in the files and see whether they are tracked by Git. Any changes made and not
           pushed to the staging area would be highlighted.
           
   # 34) - Can we create multiple branch using one command?.
            Yes, we can create multiple branches using a single command using a modification of bash script.
            
            
   # 35) - Command to delete a branch?
           The command to delete a branch is git branch --delete <branchname>
           
   # 36) - Another option of merging in git?
            git rebase is an alternative to merging in git.
            
   # 37) - Command to remove a file from git without removing it from local system?.
           The git rm --cached command is used to accomplish this.
           
   # 38) - Use of git rebase instead of git merge ?
           Git rebase is used to remove unnecessary merges before committing and merging to the main branch.Git rebase is more specific
           than git merge as it specifies which part of the main branch, we can merge our changes from our branch.
    
   # 39) - What is a repository in  git?.
           A repository is a file system which is tracked by the git version control system. Any changes like file addition, deletion 
           would be tracked by git.
           
   # 40) - Command used for commit in git?.
           The command is git commit -m (message)
           
   # 41) - What does commit object contain?
           A git commit object contains a hashed tree which contains the git id created by the SHA Algorithm as a blob and other related
           metadata.
           
   # 42) - One use of Github?.
          Github helps developers showcase their work, work and collobarate on open source projects together.
          
     
   # 43) - Alternative to Git?.
          SVN, Perforce.
          
   # 44) - What is gist in Git?.
           Gists are particular and specific services offered by a website like Github(eg: sharing code snippets)
           
   # 45) - What is a gist programming?.
            Gist Programming is a simple way of sharing codes, code snippets through a sharing platform.
           
           
   # 46) - Two git repository hosting services that are common?.
            Bitbucket, Sourceforge, Gitlab.
           
           
           
          
         
    
          
 
   
        
