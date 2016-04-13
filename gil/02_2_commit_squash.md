# Testing bugfix workflows

Initial setup:

1. fork on github
1. clone my fork
1. cd into clone and add XTUPLE remote
1. checkout XTUPLE/master
1. create file
1. git checkout -b branchName
1. git commit
1. git push -u my remote
1. create pull request on github 
1. simple merge

There are various workflows to test so the initial commit has several
copies of the same file. Factors to consider:

- number of commits on a branch
- number and timing of squashes
- type of merge - standard or squash
- location of merge - local work area or github
- direction of merge - from shared branch to working branch? from working branch to shared branch?
