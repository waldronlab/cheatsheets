## Waldron Lab Cheat Sheets

Our cheat sheets provide a summary of some of the packages that
we've been working on.

## Links To Original Documents

[MultiAssayExperiment](https://docs.google.com/spreadsheets/d/1lfHq8EfO-Lxqtyj0ocV7gQET43t1366qZnDhombR91Y/edit?usp=sharing)
[TCGAutils](https://docs.google.com/spreadsheets/d/15UIHYvL1LbIayDJsqKyZgvUR7wFwpjVIYl0IxWluVO0/edit?usp=sharing)

## Convert PDF to PNG

For conversion from PDF to PNG, use the following commands:

```
convert -density 600 MultiAssayExperiment_QuickRef.pdf -quality 100 ./pngs/MultiAssayExperiment_QuickRef.png
```


```
convert -density 600 TCGAutils_QuickRef.pdf -quality 100 ./pngs/TCGAutils_QuickRef.png
```

Make sure you have `ImageMagick` installed to use the `convert` command.
