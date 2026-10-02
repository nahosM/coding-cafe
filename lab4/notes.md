# Lab 4 Notes

## Question 1
--global applies the configuration setting to your entire user account on this machine. If left out, Git would throw an error when trying to commit because it wouldn't know your name or email for this specific repository.

## Question 2
The hidden directory `.git` appeared in `ls -a`. It contains all the version history, configuration files, and metadata that Git uses to track the repository.

## Question 3
Git is offering to track our untracked files (like README.md and week directories). Notice that the thousands of files inside `.venv/` are also hidden/ignored now (or if not yet ignored, they are listed unless ignored).

## Question 4
After creating .gitignore, everything inside `.venv/` disappeared from the untracked files list in git status.

## Question 5
.gitignore itself should be committed to the repository because your collaborators (and TAs) need it on their machines so they don't accidentally download or track junk files either.

## Question 6
README.md moved from "Untracked files" to "Changes to be committed". In the three-places model, it moved from the working directory into the staging area.

## Question 7
Git printed a summary showing the commit hash, the commit message, and how many files changed with insertions/deletions.

## Question 8
They are called the commit hash (or short hash). They serve as a unique ID to reference that specific commit in history.

