## git checkout:
```
* It will revert the changes made in local, as those files are not staged.
    git checkout <filename>
* File should be in commit area and if you are making any changes in working area, in that case only git checkout command works.
* git checkout command deletes the extra code.
* Makes the code similar to commit area.
```

## git reset: 
* Code changes are in commit area and not pushed to remote repository.
* 3 types of reset options available here:
    * soft reset
    * mixed reset
    * hard reset

    * soft reset:
        ```
        * Remove/delete the commit from commit area.
        * Code changes will be present in stage area.
        * git reset --soft HEAD~1
        ```
    * mixed reset:
        ```
        * Remove/delete the commit from commit area.
        * Code changes will be present in working area, not in staging area.
        * git reset --mixed HEAD~1
        ```
    * hard reset:
        ```
        * Remove/delete the commit from commit area.
        * Code changes will not be present in staging area.
        * git reset --hard HEAD~1
        ```
