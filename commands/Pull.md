#git pull

similar to a [git push](./PUSH.md), a `git pull` will interact with a remote repository. Only this time it will **pull** the changes it does not have from the remote down to the local repository.

This means any commits made that re of the remote repository will be pulled down and added to the local repository.

This can be done by adding the remote name and branch name:
```
git pull origin main
```

If there is any upstream connection established, you can use the`git pull` without specifying a remote or branch.

## Resources

- [Git Pull Documentation](https://git-scm.com/git-pull)

---

[Back to home](../README.md)