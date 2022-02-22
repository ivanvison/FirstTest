# FirstTest
This is my first test with Git and GitHub... Interesting process...

As a personal note... Was getting the error Git push rejected "non-fast-forward" when going "git push origin master"... Because this was a test process, the solution was found in StackOverflow: https://stackoverflow.com/questions/20467179/git-push-rejected-non-fast-forward

git fetch origin master:tmp
git rebase tmp
git push origin HEAD:master
git branch -D tmp

Wouldn't try that in an old project... Seems like a tragedy.