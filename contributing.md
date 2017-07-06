# Contributing to the handbook

We contribute to the team handbook through pull requests (PRs). This allows us to do two things:

1. Look back at the history of the handbook and how it evolved over time
2. Have conversations about new additions to the content through the pull request process

## Why we do pull requests

The benefits to doing pull requests are:

- Allow others to explore changes to content
- Share information about what is changing
- Provide an opportunity for the team to help spot any potential oversights/shortcomings
- provide an opportunity to collaborate on improvements to the content

## General guidance

- Don't rely on someone else to spot and merge your pull requests - it's your job to find a reviewer and get the content merged
- It often makes sense to split separate chunks of content additions or improvements into multiple pull requests

## Opening a request

- Before opening the PR, make sure you're up to date with `master` so that your changes are easier to merge. For example:
  ```
  git checkout master
  git pull
  git checkout your-branch-name
  git rebase master
  ```
- The title and description should help the reviewer. Make the title succinct and descriptive, and then add detail in the description
- The description should summarise your changes, this will make it possible to read through the list of changes and see what happened when 
- When raising a PR, the title and description are emailed to those following the repo. Any subsequent changes are not emailed, so it's worth spending a bit of time getting it right at the point of raising the PR.

Note: The canonical description of changes should always be in the individual
commits - Pull Requests are an artefact of GitHub, and we would lose that data
if we switched away. Please refer to the [commit message
styleguide](/git.md#commit-messages).


### Helpful things to consider while reviewing

- Check that any relevant documentation (`README` files, things in the `doc` folder) is up to date with the changes



## Further reading

- [Anna Shipman](https://github.com/annashipman) has written a useful blog post about [how to raise a good pull request](http://www.annashipman.co.uk/jfdi/good-pull-requests.html)
- A great example of [a good pull request](https://github.com/alphagov/frontend/pull/784) raised by [Alice Bartlett](https://github.com/alicebartlett)

