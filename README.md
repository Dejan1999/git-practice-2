# Git Branching Practice - Complete Lesson

This repository contains a complete practice session focused on Git branching, merging, and conflict resolution.

## What was done:

1. Created a new folder named `git_vezba_2`.
2. Learned that branches are one of the most important and specific features of Git.
3. Created 3 HTML files: `home.html`, `about.html`, and `help.html` with some basic content.
4. Initialized the Git repository, added files to staging, committed, and checked status.
5. Created the first branch `feature-header` using `git branch`.
6. Switched from `master` to `feature-header` branch with `git checkout`.
7. Created a new file `header.html` and added content.
8. Added and committed changes in the `feature-header` branch.
9. Switched back to `master` and noticed `header.html` does not exist there.
10. Created and switched to a new branch `feature-footer` using `git checkout -b`.
11. Created `footer.html` with content, staged, and committed.
12. Returned to `master` branch; neither `header.html` nor `footer.html` exist there.
13. Created a temporary branch `for-delete`.
14. Created `invalid.txt` file in `for-delete`.
15. Added and committed the file.
16. Switched back to `master`.
17. Tried to delete `for-delete` with `git branch -d` which failed because the branch was not merged.
18. Forced deletion with `git branch -D`.
19. Merged branches back to `master` using `git merge`.
20. Created a new branch `feature-hamburger`.
21. Created a conflicting scenario by creating `hamburger.html` on both `master` and `feature-hamburger` branches with different content.
22. Attempted to merge and resolved conflicts by accepting changes or combining them.
23. Added and committed resolved conflicts.
24. Added `README.txt` file on both `master` and `feature-hamburger` branches to practice merge conflicts with text files.
25. Merged again and resolved conflicts using "accept both changes".

## Notes:

- This lesson demonstrates fundamental Git workflows including branching, switching branches, committing, merging, and resolving conflicts.
- It is recommended to use `.md` files for documentation to benefit from GitHub's markdown rendering.
- Branches remain after merging until explicitly deleted.

---

Feel free to explore the branches and commits to see the changes step-by-step.