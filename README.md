# gitit
Learn Git.

A repository of changes.

----------------------------

will show you the file that was modified

$ git checkout index.html

will revert the file back to it’s unchanged version

$ git status

see that the file is no longer modified


----------------------------

Cancel staged commits

After running git add index.html the file will be staged

$ git reset HEAD index.html

will change it back to a modified but unstated file


----------------------------

Cancel a commit with new changes that discard previous changes

$ git revert HEAD

use HEAD if you want to cancel the last commit.  Use a hash if you want to cancel a commit previous to that


