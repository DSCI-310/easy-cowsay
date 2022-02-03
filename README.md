# Easy cowsay

## Description

Easy cowsay is a project specially designed to show the wonders of reproducibility through the `{renv}` R package.

## How to run

1. Open your favorite IDE (e.g., RStudio) or terminal
2. Clone this repository
3. Open the project folder
4. Run `renv::restore()` on the R console to install the R dependencies
5. Run the script `hello_world.R`
6. That's it! 🥳

Notice how you did not have to install any R package manually, `{renv}` took care of everything!

## Project structure

- `renv/` : Contains `{renv}` files
- `.Rprofile` : Used to activate renv for new R sessions launched in the project
- `README` : This very file you are reading
- `hello_world.R` : The central script of this project. Prints a cute message when excecuted
- `renv.lock` : The lockfile, describing the state of your project’s library at some point in time

## Useful links

- `{renv}` documentation: https://rstudio.github.io/renv/index.html
- `{cowsay}` documentation: https://sckott.github.io/cowsay/
