# saucesource

The web cookbook that doesn't suck.

## Project status

I am kind of deprecating the site, since it was basically a response to Luke
Smith's challenge to make a minimal recipe site and he's since launched his own
site that not-surprisingly has garnered quite a lot of attention. I recommend
you check [based.cooking](https://based.cooking)

I will still keep this site up for the foreseeable future, probably until I get
tired of paying the domain yearly fee. If, for any reason, you are still
interested, you can still submit your recipes by email or pull request.

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

This website uses [Zola](https://github.com/getzola/zola) to generate the html
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
