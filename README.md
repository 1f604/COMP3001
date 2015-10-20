Team 6 COMP3001 Technology Management and Professional Issues
===

## Issue Management

Please raise tickets with github's internal tool for any issue or new features.

##[Git Protocol]

A guide for using git.

[git protocol]: https://github.com/thoughtbot/guides/blob/master/protocol/git/README.md

The first line of commit message should be the format of `ISSUE <issuee number> - <issue message>`. Every commit should have a corresponding issue. 

**Note**: Pull request will not be used. After squashing commits into one using 'git rebase', please checkout to master by `git checkout master` and cherry-pick that commit with `git cherry-pick <branch-name>`. Make the push after that.