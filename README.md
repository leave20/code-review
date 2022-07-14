# code-review
## Standard commits
### Header
```
<Type>: <task ticket><short summary>
 ```
### Messages:
```
chore: first commit or configurations changes
ci: CI file changes
doc: documentation changes
feat: add new functionality
fix: bug fixes
refactor: changes in code optimization but does not add or modify the business.
test: add missing unit tests or fixes to existing tests.
style: changes that do not affect functionality used for formatting code, linters, etc.
```

### Correct sample:
Commit with scope on header
```
$ git commit -m "feat(transfer):NUM-2332 add form"
```

Commit without scope on header
```
$ git commit -m "test: NUM-2331 add code coverage"
```

Commit with header and body
```
$ git commit -m "test: NUM-2332 add code coverage"- m "update coverage to 85%
```

## Standard PR
### Structure
```
Title: <name branch><task>
Description:<Summary>
Revisors:<revisor one><revisor two>
```

## Standard Branch
### Main Branches
```
main
dev
```

### Feature or Support Banches
```
feature
bugfix
release
hotfix
```

### Structure branch
```
<type branch>/<task ticket>
```