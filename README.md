#Note
-----

- Build this app on the master branch with `npm run build_production`. Commit the changes to master, then run:

```
git checkout production
git pull production # ensure you are in sync with the origin
git rebase master
git push -f origin production
```
