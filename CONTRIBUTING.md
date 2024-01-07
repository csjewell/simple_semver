# Contributing to simple_semver 

## Committing

individual commits should have the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) tags. In my case, to help me do so, I've installed [gbc](https://github.com/AllanCapistrano/gbc) to do that. (I may write a better helper next.)

Note that the CI action on github also runs [golangci-lint](https://golangci-lint.run/) with [revive](https://revive.run/) as a linter. Please make sure that everything marked as an error is fixed. Warnings are fine to leave in temporarily.

## Releasing

When I'm ready to release a version, I'll tag it with [git-next-tag](https://github.com/csjewell/git-next-tag). 
