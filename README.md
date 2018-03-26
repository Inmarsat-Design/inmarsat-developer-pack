# Inmarsat Design System - Developer Pack

All you should need to get started building web apps based on the [Inmarsat Design System](https://design.inmarsat.com/).

## Prerequisites

This repo is intended to be as simple and framework agnostic as possible.

You will need to be confident with HTML and CSS. We use the [BEM](http://getbem.com/) methodology for styling components, as it is one of the simplest, well known methodologies that keep css maintainable on large projects.

## Getting started

Download the latest [release](/releases) of this project.

Include the `inm-styles.min.css` file in the head of your project. If you want to use the provided font, make sure it remains in the correct path relative to the css file.

### Global styles

The stylesheet should immediately take effect as we use bootstrap's [reboot](https://getbootstrap.com/docs/4.0/content/reboot/) and element selectors to apply the general style described in the [styles](https://design.inmarsat.com/styles) section of the Design System.

### Components

Example markup is provided for each design system [component](https://design.inmarsat.com/components) in the `html-samples/` directory of this project.
Copy and paste any of these into your site as a starting point and they will be styled by `inm-styles.min.css`.

### Assets

Logos, fonts and some icons that we have used in our examples are provided as assets in this project. And any new assets should follow the style guidelines set out in the design system.

## Licensing

```
MIT License

Copyright (c) 2018 Inmarsat

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
