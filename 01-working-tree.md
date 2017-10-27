# Working tree operations

  * Theory: Working directory and index
      - Working tree
      - Index
      - HEAD (top of history, `.git/HEAD`)
  * Theory: Repository
      - Bare repository (`HEAD`)
      - Working repository (plus worktree and index)
  * Repository initialization
      - `git init foobar` (with `.git` directory)
      - `git init --bare foobar.git`
      - `cd foobar; git init` (existing project with data)
  * Working with tree, index and HEAD
      - `git status`, `git diff`, `git diff --staged`
      - `git add <file>`
      - `git rm <file>`
      - `git rm --cached <file>`
      - `git checkout -- <file>` (undo rm from working tree)
      - `git mv`
      - `git add -u`
      - `git add .`
      - `git add -i`
  * Metadata configuration and first commit
      - `git config user.name "Franta Uživatel"`
      - `git config user.email uzivatel@example.net`
      - `git config core.editor` or `export EDITOR=`
      - `git add README`
      - `git commit -m <message>`
  * Ignoring files
      - Files ignored by `git status` and other tools
      - `.gitignore`
      - `$GIT_DIR/info/exclude`
      - `git config --global core.excludesfile <file>` (user gitignore)
  * Comparing the three states
      - `git diff` (index to workdir)
      - `git diff --cached` (HEAD to index)
      - `git diff HEAD` (HEAD to workdir)

Notes:

rm X -> git checkout X
git rm X -> git checkout HEAD X
