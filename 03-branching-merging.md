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
