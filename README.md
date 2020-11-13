# Challenge

This is a simulation of multiple team members working on different features/branches at the same time. The team are using `git merge master` or `git pull master` (Which in turn does a merge) to ensure their feature branch is up to date with master before merging back into master with `git merge feature/branch`.

Using your git tools, I would like you to find where a bug was slipped into this "codebase".

1. What commit introduced the bug
2. Think about who introduced the bug (This is pretty obvious in this example but think about how you would find that amongst a larger team)
3. When did the bug get introduced date/time?
4. What branch was the commit part of when it was merged into master?
5. What are the surrounding commits that happened alongside the bug that might be of interest in finding the reason why it was added?

*Hint: Take a look at the `git log --pretty=oneline --graph --date=short --color` command to see the history of commits*