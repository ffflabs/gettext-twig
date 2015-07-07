# gettext-twig

Extract translatable strings from Twig template strings.

It was made to be used with [gmarty/gettext](https://github.com/gmarty/xgettext) and it's
mostly copied from [smhg/gettext-swig](https://github.com/smhg/gettext-swig)

**warning:** For the time being, it only extracts string in the form `{% trans "string here" %}` which
is the most basic case described in Twig's [The i18n Extension](http://twig.sensiolabs.org/doc/extensions/i18n.html)

## Example usage

```sh
./bin/xgettext-template  ./views/twig/menu.twig -k trans 
```


