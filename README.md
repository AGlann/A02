How to Install Git
  1. Download and install the latest version on https://git-scm.com/ for your operating system 
  2. Follow the instructions for your operating system

Getting GitHub
  1. Visit https://github.com/ then create an account or sign up
  2. Keep this website open because it will be needed for other steps


How to install WebStorm
  1. Go to https://www.jetbrains.com/webstorm/download/#section=windows and download the one for your operating system
  2. Follow the installation instructions for your operating system
  3. Launch WebStorm
     
How to Configure Git in WebStorm
  1. On WebStorm navigate to settings or simply press crtl+alt+s
  2. Navigate to version control and select Git
  3. Select the path to git executable ( this should be similar to C:\Program Files\Git\bin\git.exe)
  4. Press test to ensure everything has been linked correctly ( This will display the Git version)
  5. Click Ok to save

How to create a New Project and Git repository
 1. Select new project and rename the project (Should be similar to C:\Users\Name\WebstormProjects\ChangedName)
 2. Select create
 3. On the top banner select version control
 4. Press create Git Repository
 5. When prompted to select directory ensure that it is the same as the project created (E.g. C:\Users\Name\WebstormProjects\ChangedName)
 6. Select Ok (This creates a branch called master)

How to Commit Changes in WebStorm
  1. Right-click anywhere under project and select New>HTML
  2. Name this file index (should be all lowercase)
  3. You will be prompted to add the file to Git
  4. Select Add
  5. Make some changes to the file
  6. Navigate to commit section and add the changes
  7. Add a comment then press commit

How to Connect WebStorm to GitHub
  1. Go to the main menu or simply press alt+\
  2. Navigate to Git and select GitHub
  3. Select share project on GitHub
  4. Add repository name and press share (This creates a new repository on GitHub)

How to Push Changes to Github
  1. Make some changes to file and then navigate to commit section
  2. Add comments and select commit and push (Make sure the changed is checked off)
  3. On the pop-up window press push

How to Merge Changes
  1. Inside WebStorm project on the top banner select master branch
  2. Select update project or simply use ctrl+t
  3. Select the merge option and press Ok
     
     
     
    
Reference list
  1. https://docs.github.com/en/get-started/learning-about-github/github-glossary#merge
     



Glossary
**Branch:** A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version.
**Clone:** A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. 
**Commit:** A commit, or "revision", is an individual change to a file (or set of files).
**Fetch:** Adding changes from the remote repository to your local working branch without committing them
**GIT:** Git is an open source program for tracking changes in text files**
**Github:** Provides a service to an entire organization and use their own identity when performing their function
**Merge:** Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. 
**Merge Conflict:** A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.
**Push:** To push means to send your committed changes to a remote repository on GitHub.com.
**Pull:** Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date.
**Remote:** This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
**Repository:** A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private. 
