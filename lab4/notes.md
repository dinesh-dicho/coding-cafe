## Question 1
--global means the setting is saved for my whole computer account, so every repo uses the same name and email. If I left it out, Git would save it only for the one repo I'm in.

## Question 2
A hidden folder called .git showed up in ls -a. It's where Git keeps everything about the repo, like the history of commits and the settings.

## Question 3
Git offered to track a huge number of files, mostly from the .venv folder. I didn't write those, they're other people's Python packages, so they shouldn't go in my repo.

## Question 4
The .venv files and .DS_Store disappeared from the list, because .gitignore tells Git to skip them. Only .gitignore itself showed up as a new untracked file.

## Question 5
.gitignore should be committed. It's a normal file, and committing it means anyone who copies the repo gets the same ignore rules.

## Question 6
README.md moved from "Untracked files" to "Changes to be committed". In the three-places model, it went from the working directory to the staging area.

## Question 7
Git printed [main (root-commit) bc2b180] Lab work so far, and said 4 files changed, 58 insertions. Root-commit means it was my first commit.

## Question 8
bc2b180 is the short hash of the commit. It's a shorter version of the long commit ID, and I can use it to point to that commit, like in git show bc2b180.
