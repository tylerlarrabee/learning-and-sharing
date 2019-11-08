# learning-and-sharing


When adding a new script(s) follow:

1. checkout most recent master

```
git checkout master
git pull origin/master master
```

2. checkout a branch for your work

```
git checkout -b <branch-name>
```

3. added files and edit
4. commit the files you've been adding. Message should follow [best practices](https://github.com/erlang/otp/wiki/writing-good-commit-messages).

```
git add <filename>
git commit -m "<message>"
```

5. push branch up. Note: this automatically pulls the name of the current branch

```
git push -u origin $(git rev-parse --abbrev-ref HEAD)
```

<!--- 6. create a pull request ---> 
<!--- 7. have someone review as part of the PR --->
<!--- 8. merge the branch into master and delete the branch --->
