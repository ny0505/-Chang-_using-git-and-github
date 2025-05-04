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
vim journal.md
# Write introduction section
git status
git add journal.md
git commit
# Write Introduction
mkdir common
vim common/references.txt
# Add a reference
vim journal.md
# Use reference in introduction
git add common
# Track everything currently in the 'common' directly
git status
# Verify that common/references.txt is now tracked
git commit -am "Reference J Bloggs and add references file"
# Add and commit all tracked files
