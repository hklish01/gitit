# gitit
Learn Git.

A repository of changes that I made.

$ git add [filename]

tells Git to start tracking a file or stage changes to an already tracked file

----------------------------

$ git commit [filename]

Record the staged changes

----------------------------

Modify index.html.  Run git status.  will show you that file was modified  To revert back:

$ git checkout index.html

will revert the file back to it’s unchanged version

$ git status

see that the file is no longer modified


----------------------------

Cancel staged commits

After running git add index.html the file will be staged

$ git reset HEAD index.html

will change it back to a modified but unstaged file

HEAD is the tip of the current branch


----------------------------

Cancel a commit with new changes that discard previous changes

$ git revert HEAD

use HEAD if you want to cancel the last commit.  Use a hash if you want to cancel a commit previous to that

----------------------------

Add items/changes to a commit.  

$ git add [filesnames]

Stage the file

$ git commit --amend

Commit your file but with the --amend parameter.  This will amend your last commit to include these additional changes or additions.

----------------------------

Testing git with a testweb
