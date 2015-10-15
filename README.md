# OutbreakResources/drat

Our [drat](https://github.com/eddelbuettel/drat) repository.  To rebuild the repository install `drat.builder` with

```
devtools::install_github("richfitz/drat.builder")
```

(the irony here is unintentional).

Rebuild the repository with:
```
drat.builder::build()
```

Or from the command line with

```
./drat.builder
```

After rebuilding, push with:

```
git push
```

If you removed history (with the `drop_history` argument or `--drop-history` switch) then you'll need to add a `-f` to that push.
