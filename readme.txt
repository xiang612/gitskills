test for bug,when modify the same file in different branchs,you have to obey this sequence:
1.first:git cherry-pick <commit>
2.second:git stash pop
warning:otherwise it will conflict!

