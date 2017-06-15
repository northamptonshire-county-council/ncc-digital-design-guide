---
title: How to contribute to the NCC Digital Design Guide
label: How to contribute
---

Developing a feature / making a change
-----
1. be in the project directory (cd path/to/dir)
1. be on master branch (git checkout master)
1. pull down the latest changes (git pull origin master)
1. checkout new branch (git checkout -b feature/name-of-feature)
1. make changes to the files needed to build the feature
1. test your changes do what they're supposed to do
1. back in git bash, add the files to the staging area (git add .)
1. commit the files (git commit -m 'your message here')
1. push your branch with the change (git push origin feature/name-of-feature)
1. in github, raise a pull request to the master branch
1. merge the pull request
1. stop or go to step 2.

Publishing
-----
1. be in the project directory (cd path/to/dir)
1. be on master branch (git checkout master)
1. pull down the latest changes (git pull origin master)
1. create a new version to publish (gulp publish)
1. checkout gh-pages branch (git checkout gh-pages)
1. back in git bash, add the files to the staging area (git add .)
1. commit the files (git commit -m 'your message here')
1. push the new published version to Github (git push origin gh-pages)​