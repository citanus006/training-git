# Advanced techniques and bonus topics

  * Submodules
      - `git submodule add <repo> <path>`
      - `git submodule init` (activation)
      - `git submodule update` (download current version)
      - `.gitmodules` and `.git/config` files
  * Delaying changes
      - `git stash [save [<message>]]
      - `git stash list`
      - `git stash show [<stash>]`
      - `git stash pop [<stash>]`
      - `git stash apply [<stash>]` (without popping)
      - `git stash drop [<stash>]` (without application)
      - `git stash clear` (drop all)
  * Maintainance
      - `git clean`
      - `git fsck`
      - `git fsck --unreachable` (unreachable objects)
      - `git gc [--prune=<date>]`
      - `git repack -ad` (repack databases, clean old packs)
  * Helper tools
      - `git archive`
      - `git bisect`
  * Hooks and automation
      - `.git/hooks`
      - `pre-commit`, `post-commit`
      - `post-checkout`
      - `update`, `post-update` (remote, reacts on git push)
      - `git config receive.denyCurrentBranch updateInstead` (Git 2.3)
  * Public hosting
      - GitHub, Bitbucket
      - repo.or.cz
  * Source of information
      - `git help`
      - `cheat-sheets.org`
      - `git-scm.com`
  * Bonus topics
      - `git-svn` and more
      - Binary file handling
      - Large file handling

