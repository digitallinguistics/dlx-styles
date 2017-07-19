# DLx Styles
This repository contains styles and assets for DLx projects.

## Pattern Library
A pattern library demonstrating all the styles in the DLx stylesheet, along with example HTML markup and usage notes. [View the pattern library here][1], where you can also find documentation on how to use DLx styles in your project.

## Images
DLx images and icons are available in the `/img` folder, or may be downloaded or linked to at `https://cdn.digitallinguistics.io/img/{filename}`.

## Fonts
All fonts used by DLx projects may be found in the `/fonts` folder, and are available on the CDN at `https://cdn.digitallinguistics.io/fonts/{font}`.

## JavaScript Style Sheet
An ESLint style sheet for linting code written in JavaScript is available in `/stylesheets/.eslintrc`, or may be downloaded or linked to at `https://cdn.digitallinguistics.io/dev/.eslintrc`.

## Build Process
The build process requires first uploading the LESS files to the CDN, then once they are live, compiling them to CSS (because the LESS files themselves reference the CDN for imports), and then uploading the CSS files to the CDN. These steps can all be accomplished automatically by running `npm run build` from the command line.

## Want to Contribute?
Check out DLx's [general contributing guidelines][3].

## Maintainers
This repo is maintained by:
- Daniel W. Hieber ([dhieber@umail.ucsb.edu](mailto:dhieber@umail.ucsb.edu))

[1]: https://styles.digitallinguistics.io/
[2]: https://yarnpkg.com/en/package/flexbox-reset
[3]: https://github.com/digitallinguistics/digitallinguistics.github.io/blob/master/CONTRIBUTING.md
