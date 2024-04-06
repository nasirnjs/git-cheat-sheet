1. **git init**: Initialize a new Git repository.
   `git init`

2. **git clone**: Clone a repository into a new directory.
   `git clone <repository_url>`

3. **git add**: Add file contents to the index (staging area) for committing.
   `git add filename.txt`

4. **git mv**: Move or rename a file, a directory, or a symlink.
   `git mv oldfilename.txt newfilename.txt`

5. **git rm**: Remove files from the working tree and from the index.
   `git rm filename.txt`

6. **git status**: Show the working tree status.
   `git status`

7. **git commit**: Record changes to the repository.
   `git commit -m "Commit message"`

8. **git reset**: Reset current HEAD to the specified state.
   `git reset HEAD filename.txt`

9. **git log**: Show commit logs.
   `git log`

10. **git show**: Show various types of objects.
    `git show HEAD`

11. **git branch**: List, create, or delete branches.
    `git branch new-branch`

12. **git checkout**: Switch branches or restore working tree files.
    `git checkout branch-name`

13. **git merge**: Join two or more development histories together.
    `git merge branch-name`

14. **git tag**: Create, list, delete or verify a tag object signed with GPG.
    `git tag -a v1.0 -m "Version 1.0"`

15. **git fetch**: Download objects and refs from another repository.
    `git fetch origin`

16. **git pull**: Fetch from and integrate with another repository or a local branch.
    `git pull origin master`

17. **git push**: Update remote refs along with associated objects.
    `git push origin master`

18. **git remote**: Manage set of tracked repositories.
    `git remote add origin <repository_url>`

19. **git submodule**: Initialize, update or inspect submodules.
    `git submodule add <repository_url>`

20. **git diff**: Show changes between commits, commit and working tree, etc.
    `git diff`

21. **git stash**: Stash the changes in a dirty working directory away.
    `git stash`

22. **git bisect**: Use binary search to find the commit that introduced a bug.
    `git bisect start`

23. **git grep**: Print lines matching a pattern.
    `git grep "pattern"`

24. **git blame**: Show what revision and author last modified each line of a file.
    `git blame filename.txt`

25. **git cherry-pick**: Apply the changes introduced by some existing commits.
    `git cherry-pick <commit-hash>`

26. **git revert**: Revert some existing commits.
    `git revert <commit-hash>`

27. **git rebase**: Reapply commits on top of another base tip.
    `git rebase master`

28. **git tag**: Create, list, delete or verify a tag object signed with GPG.
    `git tag -a v1.0 -m "Version 1.0"`

29. **git show-branch**: Show branches and their commits.
    `git show-branch`

30. **git show-ref**: List references in a local repository.
    `git show-ref`

31. **git update-ref**: Update the object name stored in a ref safely.
    `git update-ref refs/heads/test_branch <commit-hash>`

32. **git prune**: Prune all unreachable objects from the object database.
    `git prune`

33. **git fsck**: Verifies the connectivity and validity of the objects in the database.
    `git fsck`

34. **git gc**: Cleanup unnecessary files and optimize the local repository.
    `git gc`

35. **git show-index**: Show packed archive index.
    `git show-index`

36. **git verify-pack**: Check the connectivity and validity of objects within pack files.
    `git verify-pack -v .git/objects/pack/pack-name.pack`

37. **git ls-files**: Show information about files in the index and the working tree.
    `git ls-files`

38. **git rev-parse**: Pick out and massage parameters.
    `git rev-parse HEAD`

39. **git config**: Get and set repository or global options.
    `git config --global user.name "Your Name"`

40. **git help**: Display help information about Git commands.
    `git help commit`

41. **git shortlog**: Summarize git log output.
    `git shortlog`

42. **git describe**: Give an object a human readable name based on an available ref.
    `git describe --tags`

43. **git show-branch**: Show branches and their commits.
    `git show-branch`

44. **git reflog**: Manage reflog information.
    `git reflog`
