# git-best-practices
![fancy](fancy.png)


## What is this about?
- A simple process
- Very common between great IT companies
- Easy to learn
- Easy to implement
- Suits any project very well
- At least everyone should use


## It's not about git flow
![git flow](http://widgetsandshit.com/teddziuba/images/othergit.png)

## But it's related to it
![nice](http://widgetsandshit.com/teddziuba/images/github-branch.png)

## Commit best practices
- Make clean, single-purpose commits
- Write meaningful commit messages
- Commit early, commit often
- Don’t alter published history
- Don’t commit generated files

## Format git message
```
<type>(<scope>): <subject>

<body>

<footer>
```

## Message subject (first line)
- `<type>`
  - feat (new feature)
  - fix (bug fix)
  - docs (changes to documentation)
  - style (formatting, missing semi colons, etc; no code change)
  - refactor (refactoring production code)
  - test (adding missing tests, refactoring tests; no production code change)
  - chore (updating grunt tasks etc; no production code change)
- `<scope>`
  - init
  - runner
  - watcher
  - config
  - web-server
  - proxy
- `<body>`
  - uses the imperative, present tense: “change” not “changed” nor “changes”
  - includes motivation for the change and contrasts with previous behavior
- `<footer>`
  - Closes #234
  - Breaking changes

## Commands
- [ ] `git clone`
- [ ] `git remote `
- [ ] `git pull`
- [ ] `git fetch`
- [ ] `git add`
- [ ] `git commit`
- [ ] `git push`
- [ ] `git branch`
- [ ] `git checkout`
- [ ] `git merge`
- [ ] `git rebase`
- [ ] `git stash`
- [ ] `git reset`
- [ ] `git cherry-pick`
- [ ] `git log`
- [ ] `git reflog`

## Github settings
- You can configure branches permissions 

## References
- [git flow](https://nvie.com/posts/a-successful-git-branching-model/)
- [commit often, perfect later, publish once: git best practices](https://sethrobertson.github.io/GitBestPractices/#commit)
- [5 git best practices](https://deepsource.io/blog/git-best-practices/)
- [git commit msg](http://karma-runner.github.io/0.10/dev/git-commit-msg.html)
- [git reflog](https://www.atlassian.com/git/tutorials/rewriting-history/git-reflog)
- 
