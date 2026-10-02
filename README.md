# Git-Lab1-BlakeHO
This is my first lab for Source Control.

1. Git shows these files as untracked because I created the files in my repos folder which doesn't start tracking them untill I use the git add command. Git acknowlegdes that there are new files in the repos folder but it hasn't started tracking its changes yet.

2. Git diff provides more detail about what was done to the files that were modified, such as what was add, what was deleted, and other useful information.

3. Git restore is very useful since it can revert your changes, say you made a mistake, back to your most recent commit. But not to your git push or GitHub.

4. 
i. Git revert fixed the mistaken line that was in the commit, but also saved a version of the bad commit to our version history.
ii. This makes git revert and git restore quite different because git restore doesn't log the mistaken file, it just immediantly corrects it back to the most recent commit. Along with that you can only use restore if the file hasn't been commited.