# saucesource

The web cookbook that doesn't suck.

## Publishing your recipe

Send a git patch with your recipe and if it's (not bloated) fine I'll merge it.
Every recipe is kept in its one folder under the `content/recipes/` directory.
The name of the directory should be the approx date you submit your recipe
followed by the name/slug of the recipe. 

For more information read
[http://saucesource.cc/about/](http://saucesource.cc/about/)

Take a look at the `content/recipes/` directory for examples of recipes and how
to format them.

## Building the site

This website uses [https://github.com/getzola/zola](Zola) to generate the html
files from the templates and markdown. To build the site run:

```sh
zola build
```

To launch a lightweight http server for development purposes run:

```sh
zola serve -p 8080
```

## TODO

* Finish Russian and Spanish translations
* Maybe add some kind of search functionality on the backend
* Maybe add some way to categorize recipes

## License

By contributing recipes to this project you agree to submit them under the
CC-BY-SA 3.0 license. Any contributions related to the functioning of the site
(stylesheets, templates) are licensed under the AGPLv3 license. For more
information read the LICENSE file.
