# hello-world

[gitguide](https://rogerdudler.github.io/git-guide/)

After creating the repo in a browser:

```
echo "# hello-world" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/doxylabs/hello-world.git
git push -u origin master
```


After making some changes in a directory, add changes to the commit, then commit:

```
git add .
git commit -m "adding info from github.com"
git push origin
```

Undoing the commit and pushing the undo:

```
git reset --hard HEAD~
git push origin +master
```

Receivng changes from elsewhere:

```
git pull
```

This will require a commit to your local directory if you have two places you're working on this code. This will not overwrite the original commit date.



