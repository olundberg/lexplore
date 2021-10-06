# lexplore
## Environment

The environment is managed by [anaconda](https://www.anaconda.com/).

To create the environment use:

```
conda env create -f environment.yml
```

To import changes:

```
conda env update --file environment.yml
```

To export changes:

Make sure the version is specified and that it exists for all relevant platforms in the conda channel.

```
conda env export --from-history | grep -v "^prefix: " > environment.yml
```
