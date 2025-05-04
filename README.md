git config --global user.name "Victoria Chang"
git config --global user.email victoria.c.chang@gmail.com
git config --global core.editor vim
cat ~/.gitconfig
cd
pwd
mkdir git-papers
cd git-papers
git init
ls .git
vim journal.md
# To exit the journal, press "esc", type ":x", press enter
git status
git add journal.md
git status
vim journal.md
git commit
git status
# Write introduction section
vim journal.md
git status
git add journal.md
# Write Introduction
git commit
mkdir common
# Add a reference
vim common/references.txt
# Use reference in introduction
vim journal.md
# Track everything currently in the 'common' directly
git add common
# Verify that common/references.txt is now tracked
git status
# Add and commit all tracked files
git commit -am "Reference J Bloggs and add references file"
# Add second reference to introduction
vim journal.md
# View change to file
git diff journal.md
git add journal.md
# "Reference second paper in introduction"
git commit
git log
# View differences between current version and COMMITID
git diff COMMITID
git diff OLDER_COMMITID NEWER_COMMITID
git log
git checkout INITIAL_COMMITID
ls
git checkout -b paperWJohn
# Double check which branch we are working on
git branch
# Change title and add co-author
vim journal.md
git add journal.md
# "Modify title and add John as co-author"
git commit

