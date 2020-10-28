# Main-Master-Forced-Update
When you cannot compare branches main and master because main is empty:
(Tested and confirmed)

*all commits to master(or whatever branch is open) must be pushed, stashed, or the files restored.

git checkout master

git branch main master -f

git checkout main

git push origin main -f


ORIGINALLY FROM:https://stackoverflow.com/questions/23344320/there-isnt-anything-to-compare-nothing-to-compare-branches-are-entirely-diffe/58657132#58657132?newreg=8f671bf539df429eb5178580bf6e20b5

credit: For the new "main" branch as default, you can do this way: git checkout master   git branch main master -f    git checkout main  git push origin main -f  – Henrique Bruno Oct 19 at 18:26 
