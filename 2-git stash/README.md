There are two ways to save our code in Git or to save its changes:

## `git stash`

and

## `git commit`

If programmers want to save changes on the project they are working on without committing, they use `$ git stash` command. This command allows branches to change and work on another project without affecting existing changes. and can roll back changes whenever necessary and save the current state

## Conclusion

The command `$ git commit ` saves the changes permanently to our repository, while the command `$ git stash ` is used to backup files that we are working on but are not ready yet.

## git stash and git reset

<div align="center">

| git stash                                                                                | git reset                                                                                   |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| It is used to save files that have been modified but are not ready to run                | `reset git` can completely undo the changes and change the branch pointer to the new commit |
| Developers can switch branches and work on other tasks without affecting current changes | The changes we made will be discarded with `$ git reset`                                    |

</div>

## git stash and git stage

stage is used to prepare changes for the next commit, while stash is used to back up files that have been modified but are not yet ready for use.

<div align="center">

| git stage                                                                             | git stash                                                                                                                            |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| When we use `$ git add ` command Changes to git should be included in the next commit | `git stash` is used to back up files if you need to move to another branch while working on a feature or bug fix, we use `git stash` |

</div>
