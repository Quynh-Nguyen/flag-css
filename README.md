# flag-css

> A collection of all country flags in SVG — plus the CSS for easier integration.

## Install

You can install it via NPM:

```bash
$ npm install flag-css
```

## Usage

For using the flags inline with text add the classes `.flag-css` and
`.fc-xx` (where `xx` is the
[ISO 3166-1-alpha-2 code](https://www.iso.org/obp/ui/#search/code/)
of a country) to an empty `<span>`. If you want to have a squared version flag
then add the class `fc-squared` as well. Example:

```html
<span class="flag-css fc-vn"></span>
<span class="flag-css fc-vn fc-squared"></span>
```

You could also using alpha-3 code or IOC code as well. Example:

```html
<span class="flag-css fc-alpha3-vnm"></span>
<span class="flag-css fc-alpha3-vnm fc-squared"></span>
```

```html
<span class="flag-css fc-ioc-vie"></span>
<span class="flag-css fc-ioc-vie fc-squared"></span>
```

You could also apply this to any element, but in that case you'll have to use the
`fc-background` instead of `flag-ccs` and you're set. This will add the
correct background with the following CSS properties:

```css
background-size: contain;
background-position: 50%;
background-repeat: no-repeat;
```

Which means that the flag is just going to appear in the middle of an element, so
you will have to set manually the correct size of 4 by 3 ratio or if it's squared
add also the `fc-squared` class.

## Development

Run the `npm install` to install the dependencies after cloning the project.

## Contributors

### Code Contributors

