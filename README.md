# Shared static files for nauts.io

## Components

Styling:

* `css/presentation.scss` - Presentation styling, centered
* `css/workshop.scss` - Workshop styling, smaller font, left aligned

Generic styles:
* `_sass/_colors.scss` - Definition of Nauts.io colors
* `_sass/_reveal-theme.scss` - Standard reveal theme, with a few modifications for configurability

Images:

* `img/cargonaut.svg` - Yellow Naut


## Building locally

```
docker run -it --rm --volume=$(pwd):/srv/jekyll \
    -p 4000:4000 jekyll/jekyll:pages \
    jekyll s --force_polling
```
