# haskell-servant-example

Create backend api server with haskell.

# Database migration
This repository use `moo(https://hackage.haskell.org/package/dbmigrations)`.

## Install by stack
```
$ stack install dbmigrations
```

## Apply Database migration
```
$ moo upgrade -c migration.config
```

If you want to know dbmigrations more, you can check the official document.
(https://github.com/jtdaugherty/dbmigrations)
