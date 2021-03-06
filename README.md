# Git-Commands
GIT Comands


-------------------------------------------------------------------------------------------------------------------
#GIT Checkout with Push
Purpose : Create New Git Branch in same repo. and push Entire code.
-------------------------
Syntax :
git checkout -b NewBranchName
git add .
git commit -m "Commit Message"
git push --set-upstream origin NewBranchName

Example :
git checkout -b feature/1-React-with-Redux-BasicDemo
git add .
git commit -m "Chandan Code Commit Test"
git push --set-upstream origin feature/1-React-with-Redux-BasicDemo

Note : Please make sure, you should be in the project(Command line path) folder when you run the command else you will get error.
-------------------------------------------------------------------------------------------------------------------

#Common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
  
  --------------------------------------------------------------------------------------------
  #BIT Bucket
  --------------------------------------------------------------------------------------------
  1. Get Clone of Repository- master branch | Other Branch
2. Create Branch on BitBucket using UI(https://bitbucket.org/)
3. Run Command : git fetch origin 
Note : It will show all the branches.So, confirm that your created branch is showing or not.
4. Run Command : git checkout GE1147
Note : GE1147 is New Branch Name






  
