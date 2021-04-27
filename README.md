# Class Materials for ds-east-042621 :floppy_disk:



# The first time you set up your lecture repo you will need to:

## 1. Fork the repository at https://github.com/learn-co-students/ds-east-042621-lectures.git


## 2. Clone down your forked repository
** this step only happens once**

### From your local folder with the forked repository

* If you have set the remote skip to step :two:

3. Add the learn-co lecture notes repo as the remote, **this step only happens once**
```
git remote add upstream https://github.com/learn-co-students/ds-east-042621-lectures.git
```

4. Check the remote is set and your lecture notes repo is correct.
You should see your forked repo after **origin**, and the learn-co-students repo after **upstream**

```
git remote -v
```

# To pull down new lecture material you will:

1. Update the changes from the upstream learn-co lecture notes repo
```
git fetch upstream main
```


2. Merge the new changes from the upstream learn-co lecture notes repo, with a commit message
```
git merge upstream/main -m 'pulled updates'
```



Push the changes to the forked lecture repo :raised_hands:
```
git push
```

This is a test