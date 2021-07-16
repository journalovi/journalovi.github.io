This is a Quarto website; see the [Quarto](https://quarto.org/docs/getting-started/installation.html) docs for instructions on how to set it up.

Main website content is stored in `*.qmd` files in the base directory

Articles should be setup as [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) in the `articles/` subdirectory.

Thus, to clone this repo, ensure you update the submodules:

```
git clone --recurse-submodules git@github.com:journalovi/jovi-template-quarto.git
```

If you already cloned the project and forgot `--recurse-submodules`, you can run:
```
git submodule update --init
```

And then later, to update submodules, run:

```
git submodule update
```

After you've setup quarto, you can render the site with:

```
quarto render
```

Or render and serve locally with:

```
quarto serve
```

Or if you are using R, you can install the `quarto` package and then run:

```r
library(quarto)
quarto_serve()
```
