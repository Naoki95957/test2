#Misc. Info#
##Everything you'll ever need to know for a basic Github repository.##
###What is Git?###
Git is a version control system. This means that you can change files, save them, and commit them. These commits are then saved
outside of your work area.

Example: Say you're working on a project. You write up your changes, commit it, and keep working. You then realize the changes
in that lastest commit absolutely broke everything in your project. With a version control software like Git, you can roll back
your code to the version that worked. You have working software that isn't broken, and can fix it if necessary. Without Git,
you'd have to remember all of your changes and revert them manually.

A nice metaphor for how Git works is a tree. That's why, when viewing folders in repositories on Github, it says "tree" in the
URL right after the project name. Basically, your line of commits represents a branch. Usually, you only have one branch to
start, but you can create more later. Committing changes is like the branch growing. Reverting is just walking backward along
the branch, and when you commit again, the branch splits in two. Simple for now, right?

Now that's all well and good, but how do you use it? Here's how Git works on the command line.
---
git add <filename>: Add all of the changes you've made to the staging area. The staging area, or stage, is a location separate
from your workspace where code is stored until it is committed.
git commit -m "<message>": Commit the changes added earlier. The "-m" flag specifies that the next argument, in double quotes,
is a message that will be attached to the commit.

---
