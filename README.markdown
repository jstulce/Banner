<<<<<<< HEAD
this is a updated readme file.


1. Rename your local branch.
If you are on the branch you want to rename:

1
git branch -m new-name
If you are on a different branch:

1
git branch -m old-name new-name
2. Delete the old-name remote branch and push the new-name local branch.

1
git push origin :old-name new-name
3. Reset the upstream branch for the new-name local branch.
Switch to the branch and then:

1
git push origin -u new-name
=======

Antonia has updated the master readme file.
>>>>>>> 5e5ea2ebce585086a2de638483bc5f5772bce1d2
