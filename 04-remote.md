# Remote operations and cooperation
  
  * Theory: Cooperation models
      - Centralized workflow
      - Integration manager workflow
      - Dictator and lieutenant workflow
      - Custom workflows
      - Pull requests
      - `git help workflows`
  * Theory: Git networking
      - `git-send-pack` and `git-receive-pack` (push mode)
      - `git-fetch-pack` and `git-upload-pack` (pull mode)
      - Git daemon (read-only)
      - HTTP/WebDAV/SmartHTTP (CGI sing `git-http-backend`)
      - SSH and user accounts
      - Gitosis/Gitolite nd SSH/HTTPS
  * Cloning repositories
      - `git clone <directory> [<new-directory>]` (only `HEAD` copied)
      - `git clone <user>@<server>:<directory>` (Git over SSH)
      - `git clone git://<server>/<directory>` (read-only anonymous Git)
      - `git clone https://<server>/<directory>` (authenticated HTTPS)
      - HTTPS using smart transport, webdav or dumb transport
      - `--depth 1` (shallow clone)
      - `--bare` (like `git init --bare`)
      - `--mirror` (all references copied, implies `--bare`)
  * Remote branches and cooperation
      - `git remote`
      - `git remote add origin <repository>`
      - `git fetch <remote> [<src>:<dst>]`
      - `git fetch --prune`
      - `git pull [<remote> [<src>:<dst>]] (`git fetch` and `git merge`)
      - `git push [-f] <remote> [<src>:<dst>]`
      - `git push <remote> :<branch>` (deletes a remote branch>
      - Using prefixed branches for clarity
  * Non-networked cooperation
      - Working offline or via mail
      - `git apply <patch>` (or use `patch` of course)
      - `git format-patch`, `git send-email` and `git am`
      - `git bundle`
