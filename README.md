# learn-github-merge-options

## merge options
- merge pull request (default)
- squash and merge
- rebash and merge

## option - merge pull request
When you click the default Merge pull request option on a pull request on GitHub.com, all commits from the feature branch are added to the base branch in a merge commit. The pull request is merged using the --no-ff option

## option - squash and merge
When you select the Squash and merge option on a pull request on GitHub.com, the pull request's commits are squashed into a single commit. Instead of seeing all of a contributor's individual commits from a topic branch, the commits are combined into one commit and merged into the default branch. Pull requests with squashed commits are merged using the fast-forward option.

## option - rebase and merge
When you select the Rebase and merge option on a pull request on GitHub.com, all commits from the topic branch (or head branch) are added onto the base branch individually without a merge commit. In that way, the rebase and merge behavior resembles a fast-forward merge by maintaining a linear project history. However, rebasing achieves this by re-writing the commit history on the base branch with new commits.
