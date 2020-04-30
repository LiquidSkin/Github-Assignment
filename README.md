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
           
           
          
         
    
          
 
   
        
