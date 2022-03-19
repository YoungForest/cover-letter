# cover-letter

## Compile cover-letter to PDF

```shell
latexmk -pdf cover_letter.tex
```

## Clean up

After running LaTeX, the current directory is contaminated with a myriad of temporary files; you can get rid of them with

```shell
latexmk -c
```

This doesn’t delete the final `.pdf/.ps/.dvi` files. If you want to delete those too, use

```shell
latexmk -C
```

## References

- [latexmk](https://mg.readthedocs.io/latexmk.html)