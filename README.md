# Creastel Pages - Hugo

Creastel Pages is a template for pages (legals, documentation, etc.) developed by Creastel.

This template is made for Hugo.

## Install

Inside the folder of your Hugo project, run:

```
git submodule add git@github.com:creastel/creastel-pages-hugo.git site/themes/creastel-pages
```

Note that the `site/` segment need to be added if using NetlifyCMS. Also, as the repository is private, an SSH key is needed to clone the submodule.

Open `config.toml`, change theme to "creastel-pages":

```
theme = "creastel-pages"
```