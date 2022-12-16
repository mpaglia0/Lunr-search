# Lunr-search

This plugin is basically the copy of [tipue-search](https://github.com/pelican-plugins/tipue-search) plugin (deprecated) but amended in order to build an index file suitable for [Lunr.js](https://github.com/olivernn/lunr.js) search library.

Moreover now *categories* are no more indexed since you probably use categories in your menu or website pages. This plugin build an index only with `article.title` and `article.content`.
