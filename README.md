This is a Quarto website; see the [Quarto](https://quarto.org/docs/getting-started/installation.html) docs for instructions on how to set it up. 

Main website content is stored in `*.qmd` files in the base directory

I suggest using RStudio and the Render Website / Preview Website buttons in it, but you can also use Quarto from the command line.
You can render the site with:

```
quarto render
```

Or render and serve locally with:

```
quarto serve
```

The website is re-rendered and deployed automatically via a Github Action, so you should (in theory) be able to edit the `.qmd` files directly (even via the Github editing interface) and the website will update when you commit to the `main` branch.
