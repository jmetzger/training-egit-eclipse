# The starting point (I) : the git-repository 

## Starting with a repo 

  * New Repo in eclipse 
    * Go to Window -> Perspective -> Open Perspective -> Other -> Git 
      * Use Icon 3 (from the left) of the git icons \\ (Create a new git repository and add it to this view)
      * It suggests (the userdir)/git. Please add the name of your directory to your path (e.g. training) 
      * Leave the box "create bare repository" UNCHECKED.
      * Click "Finish"  
    * Go to new Project -> Java Project (if you are using java)
      * IMPORTANT: Uncheck "Use default location" (otherwice the repo will 
  * after that: All the intelligence and logic is within the subdirectory .git
  * this means: folders/files are fully functional, also if the .git - folder is deleted  

## Alternative: Starting with a project (recommended !)

  * You can also start with a project 
    * e.g. New -> Java Project ->
  * After that make i a git-repo 
    * Team -> Share 
      * Do **Not** Check: Use or create repository in parent folder  
      * Use the seperated git folder here
      * After doing that, all code will be moved to repo - folder
        * and here in the workspace 
          * Example Structure 
            * ~/git/RepoName/ <- Workspace 
            * ~/git/RepoName/.git
