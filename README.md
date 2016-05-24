# test_repo
<<<<<<< HEAD

# bugfix000
pull request test
bug fix 000

# bugfixまえになんか修正しておく
わざとコンフリクト


# pull request memo
```
$ git checkout -b issue_001
$ git commit --allow-empty -m "resolve #1"
$ ... # modify
$ git commit
$ git push origin issue_001
```

## Step 1: From your project repository, bring in the changes and test.

```
$ git fetch origin
$ git checkout -b issue002 origin/issue002
$ git merge master
```

## Step 2: Merge the changes and update on GitHub.

```
$ git checkout master
$ git merge --no-ff issue002
$ git push origin master
```
