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

## Question 9
The four steps were: edit the file, check it with git status, stage it with git add, and save it with git commit. After that I looked at git log to see the new commit.

## Question 10
README.md is the first thing people see when they open the repo on GitHub, so GitHub shows it on the front page automatically. It tells visitors what the project is and who made it, so it gets a special name and sits at the top level.

## Question 11
gh auth login signed me in to GitHub through the browser and saved a login token on my computer. Git uses that saved token when I push, so it doesn't ask for a password each time.

## Question 12
The front page shows my README.md, rendered as formatted text with my name and roll number, and below it the list of files. GitHub shows the README automatically because it is the file that introduces the project to visitors.

## Question 13
No, pushing did not change my local history. I still have the same three commits with the same hashes. The only thing that changed was a label (origin/main) next to the latest commit, showing that GitHub has a copy.

## Question 14
A private repo exists on GitHub, but only I and the people I invite (like my TAs) can see it. A repo that doesn't exist on GitHub at all has no online copy, so nobody can see it and it has no cloud backup. Private only controls who can see it, while "not existing" means it's not on GitHub in the first place.
