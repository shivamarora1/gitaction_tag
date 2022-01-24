This repository contains a **GitHub Action** which will tag the repository whenever there is a push on the **master** branch. Normally developers tend to forget tagging the repository whenever some new stable code is merged on the **master** branch and eventually deployed on **production**. This workflow aims to automate the tagging process whenever there is a new deployment on **master** branch.

Some background on **Git tag** and **GitHub actions**

## Git Tag
Tags are like way to create a **snapshot** of Git repo. Git tags are reference that point to specific points in the Git history. A tag is a branch which never change. Tags are generally marked as semantic versioning (**v1.2.3**) . 

#### Creating a tag:
`git tag <tag_name>`

#### Publishing a tag:
`git push origin <tag_name>`

[*More info on tagging*](https://www.atlassian.com/git/tutorials/inspecting-a-repository/git-tag#:~:text=Tags%20are%20ref's%20that%20point,branch%20that%20doesn't%20change.)

## GitHub Actions
GitHub Actions is a platform that helps to automate the processes in software build, test, and deployment pipeline. You can create workflows in GitHubs actions which will executes whenever there is event/events occurred in git repository. Some examples of such events are push to a particular branch, creation of new issue, pull request etc. GitHub actions also provides facility to run workflow manually or in some cron job like timely maner.

[*More info on GitHub actions*](https://docs.github.com/en/actions/)
