# Git and GitHub-week 2

  1. How do you see the files changed within each commit from git log?
  
        By using "git log --stat". This way we can see printed below each commit entry a list of modified files, how many files were changed, 
        and how many lines in those files were added and removed. It also puts a summary of the information at the end.
        
  2. How do you see the contents of what changed within each file from the git log?
  
        Using "git log -p". This command displays the contents of the changes made in each file by each commit.
        
  3. What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)
  
        HEAD refers to the current branch you're working on. It's a pointer to the last commit you made into your working directory. 
        That means it will be the parent of the next commit you do. 
        
                
               
