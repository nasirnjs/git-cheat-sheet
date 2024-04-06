
This breakdown categorizes Git commands into two main groups: PORCELAIN and PLUMBING.

**PORCELAIN**: These are high-level Git commands designed for ease of use and human interaction. They typically provide a more user-friendly interface and are commonly used in everyday Git workflows.

- **Main commands**: Core commands used for common Git operations like adding files, committing changes, pushing to and pulling from remote repositories.

- **Manipulators**: Commands used for manipulating Git configuration, managing references, and performing other administrative tasks.

- **Interrogators**: Commands used for inspecting the repository, examining history, and gathering information about Git objects and metadata.

- **Interactors**: Commands that facilitate interactive Git workflows, such as interactive rebasing, patch staging, and interactive conflict resolution.

**PLUMBING**: These are low-level Git commands that provide direct access to Git's internal data structures and functionalities. They are more suitable for scripting and automation purposes and are less commonly used by end-users directly.

- **Manipulators**: Commands that directly manipulate Git's internal objects, perform advanced operations, and interact with external systems.

- **Interrogators**: Commands used for querying Git's internal database, examining object contents, and retrieving information about references and commits.

- **Syncing**: Commands used for synchronization and communication with remote repositories and other Git instances.

- **Internal**: Commands that perform internal operations within Git, such as maintenance tasks, garbage collection, and repository integrity checks.

This breakdown provides a comprehensive overview of the types of Git commands available, categorized based on their functionality and usage patterns.


**PORCELAIN (82)**:
- **44 main commands** (e.g., add, commit, push, pull, ...)
- **11 manipulators** (e.g., config, reflog, replace, ...)
- **17 interrogators** (e.g., blame, fsck, rerere, ...)
- **10 interactors**

**PLUMBING (63)**:
- **19 manipulators** (e.g., send-email, p4, svn, ...)
- **21 interrogators** (e.g., cat-file, for-each-ref, ...)
- **5 syncing**
- **18 internal**

**TOTAL: 145**

## Here are the PORCELAIN Git commands
  **Main commands**:
  1. add
  2. am
  3. archive
  4. bisect
  5. branch
  6. bundle
  7. checkout
  8. cherry-pick
  9. citool
  10. clean
  11. commit
  12. describe
  13. diff
  14. fetch
  15. format-patch
  16. gc
  17. gui
  18. log
  19. merge
  20. mergetool
  21. mv
  22. notes
  23. pull
  24. push
  25. rebase
  26. reset
  27. revert
  28. rm
  29. shortlog
  30. show
  31. stash
  32. status
  33. submodule
  34. tag

  **Manipulators**:
  1. config
  2. credential
  3. difftool
  4. filter-branch
  5. gc
  6. help
  7. instaweb
  8. mergetool
  9. push
  10. rebase
  11. remote
  12. submodule
  13. worktree

  **Interrogators**:
  1. annotate
  2. blame
  3. grep
  4. log
  5. show

  **Interactors**:
  1. add--interactive
  2. rebase--interactive
  3. rebase--merge

## Here are all the PLUMBING Git commands
  **Manipulators**:
  1.   apply
  2.   checkout-index
  3.   commit-tree
  4.   hash-object
  5.   index-pack
  6.   merge-file
  7.   merge-index
  8.   mktag
  9.   mktree
  10.  pack-objects
  11.  prune-packed
  12.  read-tree
  13.  symbolic-ref
  14.  unpack-file
  15.  unpack-objects
  16.  update-index
  17.  update-ref

  **Interrogators**:
  1.   cat-file
  2.   diff-index
  3.   for-each-ref
  4.   ls-files
  5.   ls-remote
  6.   ls-tree
  7.   merge-base
  8.   name-rev
  9.   pack-redundant
  10.  rev-list
  11.  rev-parse
  12.  show-ref
  13.  unpack-objects

  **Syncing**:
  1.   fetch-pack
  2.   send-pack
  3.   receive-pack
  4.   upload-archive
  5.   upload-pack

  **Internal**:
  1.   check-attr
  2.   check-ignore
  3.   check-mailmap
  4.   check-ref-format
  5.   fmt-merge-msg
  6.   get-tar-commit-id
  7.   mailinfo
  8.   mailsplit
  9.   mailx
  10.  patch-id
  11.  sh-i18n
  12.  strip-headers
  13.  verify-commit
  14.  verify-pack
  15.  write-tree
