# Branching and merging 

  * Theory: Non-linear history
      - Branch (development snapshot pointer)
      - Repository (branch data storage)
  * Branching and merging
      - `git branch <new-branch>`
      - `git checkout <branch>`
      - `git checkout -b <new-branch>`
      - `git merge <source-branch>`
      - Recursive merge, octopus merge
      - `git config --global merge.tool <tool>`
      - Merge tool like meld
  * Conflict resolution
      - `git merge [--no-commit] <source-branch>`
      - `git commit`
  * Detached HEAD state
      - `git checkout <commit>; git branch`
      - `git branch <new-branch>`
      - `git branch -d`
      - `git checkout -b <new-branch>`
  * Cheating: One step back
      - `git checkout -f`
      - `git reset --hard X` (HEAD, index, tree)
      - `git reset --mixed X` (HEAD, index)
      - `git reset --soft X` (HEAD)
      - `git commit --amend` (can be done using soft reset)
  * Cheating: Creating linear history, patching
      - `git rebase`
      - `git cherry-pick`
  * Cheating: Undoing cheating
      - `git reflog`

  * TODO: git reflog
  * TODO: git show branch:file
  * TODO: git ls-files

Note: how to list files from specific revision
