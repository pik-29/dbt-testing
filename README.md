# dbt-testing

## set up github

* consult: https://github.com/cli/cli/blob/trunk/docs/install_linux.md
* authentication

```
$ gh auth login
```

* clone repo

```
$ gh repo clone pik-29/dbt-testing
```

* create a branch and modify some code or add file

```
$ git checkout -b dev
```

* add, commit, push

```
$ git add .
$ git commit -m "test:configuration"
$ git push
```

You need to configure credential:

```
$ export GCM_CREDENTIAL_STORE=cache
$ git push --set-upstream origin dev
```

