# Gitbook custom theme for SIS documentation

This is a plugin for Gitbook since version 3.0.0.

This plugin was forked from the Corezoid theme project [here](https://github.com/akulov/gitbook-plugin-theme-corezoid). I've added the ability to easily configure the URL for the logo at the top right of the screen.

***Note: Multi-lingual support has been disabled and needs to be fixed.***

*It adds a new block with logo and list of languages. This theme extends HTML templates, CSS styles and JS scripts of a base GitBook theme [gitbook-plugin-theme-default](https://www.npmjs.com/package/gitbook-plugin-theme-default).*

*Additionally, translated title of the search result that does not exist in the Russian localization (ru.json).*

The plugin can be used as a blank theme template for GitBook.

![Image](https://github.com/SIS-MSC/gitbook-plugin-theme-sis/raw/master/preview.png)

## Usage

Add the theme to your book's configuration `book.json`:

```js
{
    "plugins": [
        "theme-sis"
    ],
    "pluginsConfig": {
        "theme-sis": {
            "langs": ["en"],
            "baseurl": "https://github.com/SIS-MSC/gitbook-plugin-theme-sis/tree/master"
        }
    }
},
```

Install by command:

``` bash
gitbook install
```

## Future Efforts

* Allow the image to be specified via the `book.json`.
* Fix multi-lingual support

## Links

This theme on [github.com](https://github.com/SIS-MSC/gitbook-plugin-theme-sis), [plugins.gitbook.com](https://plugins.gitbook.com/plugin/theme-sis), [npmjs.com](https://www.npmjs.com/package/gitbook-plugin-theme-sis)
