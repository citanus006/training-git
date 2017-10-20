# Commit history 

  * Theory: Linear change history
      - Blob (a file)
      - Tree (a directory)
      - Commit (a snapshot with history)A
      - Tag (a tag object)
      - master (main branch, `.git/refs/heads/master`)
      - `HEAD` (current branch/commit pointer, `.git/HEAD`)
      - Packs and optimizations
  * Advanced commit workflow
      - `git commit`
      - `git commit -m "commit message"`
      - Author, commiter
      - `-a` (`git add -u`)
      - `-e` (edit commit message)
      - `--author` (specify author)
      - `--amend` (unsent commits only!)
  * History examination
      - `git log [--format=full] a..b`
      - `git show a`
      - `git diff a..b`
      - `git blame`
      - `gitk`
  * Tagging
      - `git tag`
      - `git tag -a`, `git tag -s`
      - `git describe -t`

Notes:

`git log -- DELETED_FILE`
`git log master --`
