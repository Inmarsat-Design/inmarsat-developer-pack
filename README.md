# Inmarsat Design System - Developer Pack

All you should need to get started building web apps based on the [Inmarsat Design System](https://design.inmarsat.com/).

## Prerequisites

This repo is intended to be as simple and framework agnostic as possible.

You will need to be confident with HTML and CSS. We use the [BEM](http://getbem.com/) methodology for styling components, as it is one of the simplest, well known methodologies that keep css maintainable on large projects.

## Getting started

Download the relevent release of this project.

Include the `inm-styles.min.css` file in the head of your project. If you want to use the provided font, make sure it remains in the correct path relative to the css file.

### Styles

The stylesheet should immediately take effect, as we use bootstrap's [reboot](https://getbootstrap.com/docs/4.0/content/reboot/) utility, plus our own element selectors to apply the style described in the [styles](https://design.inmarsat.com/styles) section of the Design System.

#### Sass

The sass files are now also included if you prefer to work with them. However, currently, if you want to build the global styles from `scss/global/Style.scss` instead of using `inm-styles.min.css`, you will need set up your ecosystem so that the bootstrap imports inside `scss/global` resolve to your own _bootstrap 4_ dependency.

### Components

Example markup is provided for each design system [component](https://design.inmarsat.com/components) in the `html-samples/` directory of this project.
Copy and paste any of these into your site as a starting point and they will be styled by `inm-styles.min.css`.

### Assets

Fonts and some icons/logos that we have used in our examples are provided as assets in this project. For more designer assets and info on how to contribute, visit the [imagery](https://github.com/Inmarsat-Design/imagery) and [sketch-file](https://github.com/Inmarsat-Design/sketch-file) repos.

## Licensing

[MIT License](/LICENSE)
