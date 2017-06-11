# DLx Styles
This repository contains styles and assets for DLx projects.

## Pattern Library
A pattern library demonstrating all the styles in the DLx stylesheet, along with example HTML markup and usage notes. [View the pattern library here.][1]

## LESS / CSS
Three LESS stylesheets and their accompanying CSS output are available in this repo's `less` and `css` folders. These are each made available on the DLx CDN and may be linked to at `https://cdn.digitallinguistics.io/less/{filename}` or `https://cdn.digitallinguistics.io/css/{filename}`.

- `classes.less`: DLx styles that require adding a class to an element in order to be applied
- `colors.less`:  LESS variables for each of the colors used in the DLx color schemes
- `dlx.less`:     A bundled version of all the DLx styles. Will apply all global styles and font declarations, and make all colors, classes, and LESS variables available.
- `fonts.less`:   Font declarations for the various fonts used by DLx.
- `global.less`:  Global styles that get applied without needing to explicitly add a class to the element. Includes styling from [`flexbox-reset`][2]. Does not include `@font-face` rules, colors, or classes (see `dlx.less` for a file which bundles all of these).

## Images
DLx images and icons are available in the `/img` folder, or may be downloaded or linked to at `https://cdn.digitallinguistics.io/img/{filename}`.

## Fonts
All fonts used by DLx projects may be found in the `/fonts` folder, and are available on the CDN at `https://cdn.digitallinguistics.io/fonts/{font}`.

## JavaScript Style Sheet
An ESLint style sheet for linting code written in JavaScript is available in `/stylesheets/.eslintrc`, or may be downloaded or linked to at `https://cdn.digitallinguistics.io/dev/.eslintrc`.

## Build Process
The build process requires first uploading the LESS files to the CDN, then once they are live, compiling them to CSS (because the LESS files themselves reference the CDN for imports), and then upload the CSS files to the CDN.

[1]: https://styles.digitallinguistics.io/
[2]: https://yarnpkg.com/en/package/flexbox-reset
