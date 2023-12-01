# Git related utilities

## hooks
Install hooks either by copying the file(s) to `.git/hooks` or by changing [`core.hooksPath`](https://git-scm.com/docs/git-config#Documentation/git-config.txt-corehooksPath). These hooks are currently available:
  * `pre-commit`:
    * check for .gitattributes settings
